# Subreply CSS

The beautiful CSS style used by [Subreply](https://subreply.com/about). Heavily modified for classless usage.

# Why?

Why not? Subreply has very nice style and colors, and I thought it would be a good idea to turn it into an
independent CSS style.

# I want to see a demo first

You can try this [demo](https://srht.githack.com/~tsukii/subreply-css/blob/main/test.html) of the
test.html file included with Subreply CSS, or go to [my website](https://tsk.bearblog.dev/)

# Features

- Completely classless
- Nice-looking
- Automatic dark/light theme
- Adding features missing in the original Subreply, such as radios and checkboxes
- Custom blockquotes from [here](https://css-tricks.com/snippets/css/simple-and-nice-blockquote-styling/) and custom code block from [here](https://adis.ca/entry/2011/pretty-code-block-in-css/)
- Custom emojis for `mailto:`, `tel:`, `sms:`

# Installation

Paste into your website's &lt;head&gt; this snippet:

```css
<link rel="stylesheet" href="https://git.sr.ht/~tsukii/subreply-css/blob/main/subreply.css">
```

You can also use the minified version in production mode:

```css
<link rel="stylesheet" href="https://git.sr.ht/~tsukii/subreply-css/blob/main/subreply.min.css">
```

# Is This Ready To Use?

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
- Blockquotes now use background colors as the opposite colors of the text colors for readability
- Add minified version of the style

# Copyright and credits

Copyright 2022-present [Dang Hoang Tuan](https://tsk.bearblog.dev).

Original code by [Lucian Marin](https://github.com/lucianmarin).

This CSS style is under the MIT license.
