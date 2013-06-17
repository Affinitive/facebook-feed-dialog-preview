Facebook Feed Dialog Preview
============================

This tool is an attempt at being able to preview how attachments to stories
created with the feed dialog look when posted on Facebook. Note that
Facebook may change their stylesheets at any time so this may be out of date.
We are linking directly to Facebook's stylesheets to attempt to get the most
accurate representation possible. The picture preview is also likely not exact.
We are simply using the CSS3 background-size property to have the picture fit
the available space.

The main purpose of this tool is to make it possible to tell if the
name, caption, and description of the link attachment will fit in Facebook's
current design without being truncated.
[This bug](https://developers.facebook.com/bugs/125436114284682)
was filed and was determined to be working as designed. The previous functionality
had a "See More" link that could be clicked to expand the entire feed attachment.
This is no longer available and the only option is to click through to the link destination.

This is a completely client-side application.
No data is sent to backend servers.
This project is open source under the MIT license.

Todo
----

- Create a preview of the attachment in the new News Feed design (i.e. the one
  being rolled out Q2 of 2013)
- Create a preview of the attachment in a mobile News Feed
