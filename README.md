# Subreply CSS

<img src="./logo.png" align="right"
     alt="Subreply logo, but inverted" width="192" height="192">

Subreply CSS is a simple, yet modern and beautiful classless CSS style. It's
suitable for both personal blogs and as a bootstrap. It was influenced by the
clean social media [Subreply](https://subreply.com/about). (Hence the name)

* **Lightweight** - Only weights 4 kB! (original version)
* **Mobile responsive**
* **Automatic dark/light theme** (based on OS preferences)
* **Custom emojis** before `mailto:`, `sms:`, and `tel:` links
* **Custom blockquotes** and **code blocks**
* Beautiful font ([Route 159](https://dotcolon.net/font/route159/))
* Fixing missing features from the original Subreply, such as **radios and checkboxes**

Wanna try it first? Visit the [demo](https://raw.githack.com/HoangTuan110/subreply-css/main/test.html)
or go to [my website](https://tsk.bearblog.dev), which uses Subreply CSS.

# Installation

You can download the file `subreply.css` or `subreply.min.css`, or paste into your website's &lt;head&gt;
this snippet:

```css
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/HoangTuan110/subreply-css/subreply.css">
```

You can also use the minified version in production mode:

```css
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/HoangTuan110/subreply-css/subreply.min.css">
```

# Changelog

## v0.1

Initial release

## v0.2 (29/06/2022)

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
