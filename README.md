# CSSheet v1.4 [Alpha]

The official repository for CSSheet! A simple, easy to learn and bootstrap-compatible CSS framework which allows you to make great websites easily! 

CSSheet works by creating CSS classes and allowing you to insert them into any HTML tag

# Documentation:

Documentation includes everything! Press CTRL+F to find specifics!

Includes: fonts, background color, background images, foreground color, border color, width, height, border radius, border width, border style, text align, font size, opacity/transparency, opacity on hover, Background with opacity, text decoration, word wrap, float, padding, columns and rows,

## How to add CSSheet to your web page

```html
<link rel="stylesheet" href="https://gitcdn.xyz/repo/cobwebdev/cssheet/main/css/cssheet.css">
```
Add this tag to your web-page inside of your pages `<head>` tag.

## CSSheet Syntax:

### Fonts:

Default CSSheet fonts: arial, georgia, courier

The font choice syntax is `ft-<font>`

Example:
```html
<body class="ft-arial">
```
This will create a html body with the font "Arial"

### Background color:

Default CSSheet colors: Black, white, red, orange, yellow, aqua, blue, purple (You can always add more yourself)

Brightness values: 1, 2, 3, 4, 5, 6, 7, 8, 9

The background color syntax is: `bg-<color>-<brightness>`

Example:
```html
<div class="bg-red-5">
```
This will create a divider with a red background and a brightness of 50% (default)

### Background images

Default CSSheet images: cloudy-peaks, lovely-mountain, midnight-city, night-sky, night-town, sea-rock

The background image syntax is `bgi-<image-name>`

Example:
```html
<body class="bgi-night-town">
```
This will give the page body the background image "night-town"

### Foreground (text) color: 

Default CSSheet colors: Black, white, red, orange, yellow, aqua, blue, purple (You can always add more yourself)

The foreground color syntax is: `fg-<color>`

Example:
```html
<p class="fg-white">This is some text</p>
```
This will create a `<p>` tag with White text

### Border color: 

Default CSSheet colors: Black, white, red, orange, yellow, aqua, blue, purple (You can always add more yourself)

The foreground color syntax is: `bdc-<color>`

Example:
```html
<div class="bdc-aqua">
```
This will set the border color to aqua

### (Responsive) width:

Width lengths (in vw): 10, 25, 50, 75, 100, auto

Width syntax is `wd-<width>`

Example:
```html
<div class="wd-10">
```
This will create a divider with a width of 10vw

### (Responsive) height:

Height lengths (in vh): 10, 25, 50, 75, 100, auto

Height syntax is `ht-<height>`

Example:
```html
<div class="ht-50">
```
This will create a divider with a height of 50vh

### Border radius:

Border radius styles: none, rounded, curved

Border radius syntax is `bdr-<style>`

Example:
```html
<div class="bdr-rounded">
```
This will create a divider with rounded corners.

### Border width:

Border width lengths: 1, 2, 3, 4, 5, 10

Border width syntax is `bdw-<width>`

Example:
```html
<div class="bdw-5">
```
This will create a divider with a border width of 5 pixels.

### Border styles:

Border styles: solid, dotted, dashed

Border style syntax is: `bds-<style>`

Example:
```html
<div class="bds-solid>
```
This will create a divider with a solid border.

### Text align:

Text align: left, center, right

Text align syntax is: `ta-<position>`

Example:
```html
<div class="ta-center">
```
This creates a divider where all of the text and elements inside of it will be centered inside of the divider.

### Font size:

Font sizes (in vw): 1, 2, 3, 4, 5, 6, 7, 8, 9, 10

Font size syntax is `fs-<size>`

Example:
```html
<p class="fs-4">
```
This creates a paragraph tag with a font size of 4vw

### Opacity/Transparency:

Opacity: 00, 01, 02, 03, 04, 05, 06, 07, 08, 09, 10 (00 = 0.0, 01 = 0.1)

Opacity syntax is `op-<opacity>`

Example:
```html
<div class="op-05">
```
This creates a divider with an opacity/transparency of 0.5

### Opacity on hover:

Opacity on hover: 00, 01, 02, 03, 04, 05, 06, 07, 08, 09, 10 (00 = 0.0, 01 = 0.1)

Opacity on hover syntax is `oh-<opacity>`

Example:
```html
<div class="oh-05">
```
This creates a divider and when the mouse hovers over it, the opacity will change to 0.5

### Backgrounds with opacity:

Default colors: black, white

Backgrounds with opacity syntax: `bg-<color>-op`

Example:
```html
<div class="bg-black-op">
```
This creates a divider, which is transparent and black

### Text decoration:

Text decorations: bold, underline, none

Text decoration syntax: `td-<decoration>`

Example:
```html
<a href="https://cob-web.dev/discord" class="td-underline">
```
This creates a hyperlink, with the text decoration underline.

### Word Wrap:

Wrap styles: normal, break-word, initial, inherit

Word wrap syntax: `wdw-<style>`

Example:
```html
<p class="wdw-break-word">
```
This will create a paragraph tag with the word wrap "break word".

### Padding: 

Padding (in vw and vh): 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16

Padding syntax: `pd-<padding>`

Example:
```html
<p class="pd-8">
```
This will create a padded paragraph tag with padding of 8vh and 8vw

### Floating:

Float values: left, right, none, inherit

Float syntax: `flt-<value>`

Example:
```html
<div class="ft-left">
```
This will create a divider that will float to the left

### Columns and Rows:

This is a bit more complicated to implement, Columns on web-pages usually split content across the webpage, so you can have multiple buttons on the same line, for example. 

To create a column you first need to add a row. The syntax for a row is: `row`
```html
<div class="row">
```

Afterwards you will need to add as many columns into your row as you see fit.

The syntax for a column is: `cl wd-<width>`

Columns need a width in order to display the full length of a column

#### Full row and column example:
```html
<div class="row">
  <div class="cl wd-25><h1>Column 1</h1></div>
  <div class="cl wd-25><h1>Column 2</h1></div>
  <div class="cl wd-25><h1>Column 3</h1></div>
</div>
```
This creates a row, and 3 columns with a maximum width of 25vw. Inside of the columns are headers.

* Columns and rows are mobile responsive

### Margins:

Margin values: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16

The syntax for margins are: `mg-<value>`

Example:
```html
<div class="mg-0">
```
This creates a divider with a margin of 0vw and 0vh (nothing)

### Position:

Position properties: static, relative, fixed, absolute, sticky

The syntax for position is: `pos-<position>`

Example:
```html
<div class="pos-relative">
```
This creates a divider with a relative position.


## Loader:
Add loader to your own website.

Example:
```html
<a href="btn"><div class="loader"></div></a>
```

## Themes:
Theres currently only 1 theme to use the theme the class for it is `thm-discord-<mode>` and modes are `dark and light`

Example:
```html
<body class="thm-discord-dark">
<!-- Your code here -->
</body>
```

Edit `Discord theme example file` for more details.
## Made with love by Cob:web Development and our Open source contributors:

Jaiden Collins - Lead Developer

Alex Carson - Former Lead Developer

Adam Salt - Former Lead Developer

### Please join the Cob:web Development discord to talk to us and contribute to our projects: https://cob-web.xyz/discord

* Please be aware that our CDN automatically updates, however it may take up to 2 hours for the cache to clear on the CDN.

