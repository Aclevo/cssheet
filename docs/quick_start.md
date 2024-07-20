# Quick Start
To add CSSheet to your webpage, add the following to your html `<head>` tag:

```html
<link rel="stylesheet" href="https://gitcdn.xyz/repo/Aclevo/cssheet/main/css/cssheet.min.css">
```

> NOTE: It is recommended to put everything inside of a `div` tag with a `cs` class

## Custom Theme
If you want to use CSSheet with your own custom theme, you will need to install Sass. You can use npm to do that:
```npm
npm install -g sass
```
Then, clone the CSSheet repository:
```git
git clone https://github.com/Aclevo/cssheet
```
Go to `cssheet/sass/` and open the `variables.scss` file.
There you will find many scss variables, which you can edit to change the theme. The following table describes what each variable controls:

| Variable                        | Type   | Purpose                                                                                   |
|---------------------------------|--------|-------------------------------------------------------------------------------------------|
| `$blue`                         | Colors | Used for links, default primary color                                                     |
| `$cyan`                         | Colors | Default secondary color.                                                                  |
| `$yellow`                       | Colors |                                                                                           |
| `$orange`                       | Colors |                                                                                           |
| `$red`                          | Colors |                                                                                           |
| `$purple`                       | Colors |                                                                                           |
| `$grey`                         | Colors | Used as the link hover color, topnav background color.                                    |
| `$black`                        | Colors | Default foreground color, used as the text button hover color, button hover border color. |
| `$white`                        | Colors | Default background color, topnav foreground color, footer background color.               |
| `$light`                        | Colors | Default navbar hover color, text button hover background color, button border color.      |
| `$primary-font`                 | Fonts  | Default text font.                                                                        |
| `$secondary-font`               | Fonts  | Default font for headers.                                                                 |
| `$monospace-font`               | Fonts  | Default monospace font (used in code blocks, etc).                                        |
| `$primary-color`                | Colors | Primary accent color, default is `$blue`.                                                 |
| `$secondary-color`              | Colors | Secondary accent color, default is `$cyan`.                                               |
| `$text-color`                   | Colors | Foreground color, default is `$black`.                                                    |
| `$background-color`             | Colors | Background color, default is `$white`.                                                    |
| `$link-hover-color`             | Colors | Color of links on hover, default is `$grey`.                                              |
| `$border-width`                 | Layout | Width of borders, default is `3px`.                                                       |
| `$shadow-color`                 | Colors | Color of shadows, default is `rgba(0, 0, 0, 0.2)`.                                        |
| `$text-button-hover-background` | Colors | Background color of text button on hover, default is `$light`.                            |
| `$text-button-hover-color`      | Colors | Foreground color of text button on hover, default is `$black`.                            |
| `$button-border-color`          | Colors | Border color of buttons, default is `$light`.                                             |
| `$column-min-width`             | Layout | Minimum width of columns, required for them to wrap, default is `200px`.                  |
| `$default-margin`               | Layout | Margin for body and other elements, default is `10px`.                                    |
| `$default-padding`              | Layout | Padding for body and other elements, default is `10px`.                                   |
| `$column-spacing`               | Layout | Space between columns, default is `2vw`.                                                  |

To generate the `cssheet.css` file from the `cssheet.scss` file, run:
```npm
npm run css-build
```
You will find your custom `cssheet.css` file in the `css/` directory.
