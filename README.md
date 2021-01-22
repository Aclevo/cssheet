# CSSheet (beta)
The official repository for CSSheet! A Bootstrap-compatible CSS framework which allows you to make great websites easily! 

CSSheet works by creating CSS classes and allowing you to insert them into any HTML tag

v1.0.0 beta
# Documentation:

Documentation includes everything! Press CTRL+F to find specifics!

Includes: background color, foreground color, border color, width, height, border radius, border width, border style, text align

## How to add CSSheet to your web-page

```html
<link rel="stylesheet" href="https://cobwebdev.github.io/cssheet/css/cssheet.css">
```
Add this tag to your web-page inside of your pages `<head>` tag.

## CSSheet Syntax:

### Background color:

Default CSSheet colors: Black, white, red, orange, yellow, aqua, blue, purple (You can always add more yourself)

The background color syntax is: `bg-<color>`

Example:
```html
<div class="bg-red">
```
This will create a divider with a red background

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

Width lengths: 10%, 25%, 50%, 75%, 100%, auto

Width syntax is `wd-<width>`

Example:
```html
<div class="wd-10">
```
This will create a divider with a width of 10%

### (Responsive) height:

Height lengths: 10%, 25%, 50%, 75%, 100%, auto

Height syntax is `ht-<width>`

Example:
```html
<div class="ht-50">
```
This will create a divider with a height of 50%

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

# Credits
Made with love by Adam Salt and Cob:web Development

#### Please join the Cob:web Development discord to talk to us and contribute to our projects: https://discord.gg/RsJDffM9gd
