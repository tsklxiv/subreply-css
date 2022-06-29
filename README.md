# Subreply CSS

The beautiful CSS style used by [Subreply](https://subreply.com/about). Heavily modified for classless usage.

# Why?

Why not? Subreply has very nice style and colors.

# Features

- Completely classless
- Nice-looking
- Adding features missing in the original Subreply, such as radios and checkboxes
- Custom blockquotes from [here](https://css-tricks.com/snippets/css/simple-and-nice-blockquote-styling/) and custom code block from [here](https://adis.ca/entry/2011/pretty-code-block-in-css/)
- Custom emojis before `mailto:`, `tel:`, `sms:`

# Installation

Copy the file `subreply.css` to your project, and BAM!, you are done!

# Is This Ready For use?

Very much.

# Changelog

## v0.1

Initial release

## v0.2

Changes:

- The `margin: 0; padding: 0;` CSS style has been removed to allow for natural rendering
- Links (`a`) now uses the accent (nice blue) color instead of black to make it unique from texts
- Uses the same style for both `input[type="submit"]` and `button`
- Remove the `float: right;` style on buttons and `input[type="submit"]` elements, as it's annoying when using in paragraphs.
- Add emojis before `mailto:`, `tel:`, and `sms:` links to differentiate them from normal links
- Clean out a bunch of class-based CSS, which is not what we wanted for a classless CSS
- Getting checkboxes to work
- Fixing the problem why the text in checkboxes are under the checkbox
- Removing the hover in `input[type="submit"]` and `button` for good.
- Remove `display: block;` for image to avoid awkward displaying
- Update blockquote text color so that it automatically updates to black if the devices prefers black color scheme

# Copyright and credits

Copyright 2014(?)-Present Lucian Marin (https://github.com/lucianmarin)
Straight up ripped from Subreply and heavily modified by Dang Hoang Tuan (https://tsk.bearblog.dev)

This CSS style is under the MIT license.
