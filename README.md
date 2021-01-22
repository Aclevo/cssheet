# CSSheet (beta)
The official repository for CSSheet! A Bootstrap-compatible CSS framework which allows you to make great websites easily! 

CSSheet works by creating CSS classes and allowing you to insert them into any HTML tag

v1.0 beta
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

