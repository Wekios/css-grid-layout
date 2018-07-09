<h1 align="center">
  <br>
  <a href="http://www.diwanee.com"><img src="https://storage.googleapis.com/fbgabudhabi/2017/09/DIWANEE.jpg" alt="diwanee" width="200"></a>
  <br>
</h1>

<h4 align="center">Layout Examples & Review of the CSS Grid Layout Module Done by Diwanee Development Team <br> <a href="http://www.diwanee-serbia.rs/" target="_blank">Diwanee Serbia</a>.</h4>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#examples">Examples</a> •
  <a href="#fallbacks">Fallbacks</a> •
  <a href="#resources">Resources</a>
</p>

<br>

![screenshot](https://cdn-images-1.medium.com/max/1600/1*EW174m7OIIpJwMHkrTW3Xg.gif)

## Key Features

- Two dimensional layout - Control both axis of the element

  - Flexbox is essentially for laying out items in a single dimension – in a row OR a column. Grid is for layout of items in two dimensions – rows AND columns.

- [Feature queries](https://www.w3.org/TR/css3-conditional/#at-supports)

  - the ‘@supports’ rule

  ```
  @supports (display: grid) {
   // code that will only run if CSS Grid is supported by the browser }
  ```

- Highly performant, for details click [here](https://blogs.igalia.com/jfernandez/2015/06/24/performance-on-grid-layout/)
- Grid areas
  - You can organize your layout by custom naming areas that you wannna fill.
- Grid Inspector for most browsers.
- New flexible length
  - flex is a dimension with the fr unit, which represents a fraction of the leftover space in the grid container. Tracks sized with fr units are called flexible tracks as they flex in response to leftover space similar to how flex items fill space in a flex container.
- Cross browser full support, except for well known few (Looking at you IE).

  - Full support, and 87.73% global usage. Fallbacks are needed for IE11 and below.

  ![alt text](/caniuse.png)

## How To Use

CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a 1-dimensional system. You work with Grid Layout by applying CSS rules both to a parent element (which becomes the Grid Container) and to that elements children (which become Grid Items).

`Grid container` - The element on which `display:grid` is applied.

`Grid item` - The children (e.g. direct descendants) of the grid container.

`Grid Line` - The dividing lines that make up the structure of the grid. They can be either vertical ("column grid lines") or horizontal ("row grid lines") and reside on either side of a row or column.

`Grid Area` - A grid area may be comprised of any number of grid cells.

Note: for real in depth understanding of the grid layout [see this guide](https://css-tricks.com/snippets/css/complete-guide-grid/) or use [official docs](https://www.w3.org/TR/css-grid-2/).

## Examples

| Grid Layout               |                      Link                      |
| ------------------------- | :--------------------------------------------: |
| _Full Page Layout Change_ |       [here](https://wekios.github.io/)        |
| _Renault Vu blocks_       | [here](https://wekios.github.io/renault.html)  |
| _Grid Calendar_           | [here](https://wekios.github.io/calendar.html) |
| _Feature Query Overwrite_ | [here](https://wekios.github.io/fallback.html) |

**_Resize the browser window to see page layout change_**

## Fallbacks

## Fallbacks

This software uses code from several open source packages.

- [Electron](http://electron.atom.io/)
- [Node.js](https://nodejs.org/)
- [Marked - a markdown parser](https://github.com/chjj/marked)
- [showdown](http://showdownjs.github.io/showdown/)
- [CodeMirror](http://codemirror.net/)
- Emojis are taken from [here](https://github.com/arvida/emoji-cheat-sheet.com)
- [highlight.js](https://highlightjs.org/)

## Related

[markdownify-web](https://github.com/amitmerchant1990/markdownify-web) - Web version of Markdownify

## Support

<a href="https://www.buymeacoffee.com/5Zn8Xh3l9" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

<p>Or</p>

<a href="https://www.patreon.com/amitmerchant">
	<img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## You may also like...

- [Pomolectron](https://github.com/amitmerchant1990/pomolectron) - A pomodoro app
- [Correo](https://github.com/amitmerchant1990/correo) - A menubar/taskbar Gmail App for Windows and macOS

## License

MIT

---

> [amitmerchant.com](https://www.amitmerchant.com) &nbsp;&middot;&nbsp;
> GitHub [@amitmerchant1990](https://github.com/amitmerchant1990) &nbsp;&middot;&nbsp;
> Twitter [@amit_merchant](https://twitter.com/amit_merchant) -->
