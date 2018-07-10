<h1 align="center">
  <br>
  <a href="http://www.diwanee.com"><img src="https://storage.googleapis.com/fbgabudhabi/2017/09/DIWANEE.jpg" alt="diwanee" width="200"></a>
  <br>
</h1>

<h4 align="center">Layout Examples & Review of the CSS Grid Layout Module Done by Diwanee Development Team <br> <a href="http://www.diwanee-serbia.rs/" target="_blank">Diwanee Serbia</a>.</h4>

<p align="center">
  <a href="#setup">Local Setup</a> •
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#examples">Examples</a> •
  <a href="#fallbacks">Fallbacks</a> •
  <a href="#resources">Resources</a>
</p>

<br>

![screenshot](https://cdn-images-1.medium.com/max/1600/1*QJZ8nT3u5zwQQhFNddtSbA.gif)

<br>

## Setup

For installing project localy use instructions from [webedia-fe-starter](https://github.com/Demiourgos87/webedia-fe-starter) by [Bojan Knezević](https://github.com/Demiourgos87).

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
- Cross browser support, except for well known few.

  - Full support for all major browsers and 87.73% global usage. Fallbacks are needed for IE11 and below.

  ![caniuse](/caniuse.png)

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

Grid does things that are pretty much impossible with older layout methods. So, in order to replicate Grid in browsers that don’t have support, you would need to do a lot of work in JavaScript. Even on a well-resourced computer, with a fast rendering engine that is likely to give you something of a janky experience as heights are calculated and items positioned. As we already know, **the browsers that don’t support grid are older**, slower browsers or browsers most often found on lower powered devices in emerging markets. Forcing a bunch of JavaScript on them is not smart. Solution?

### BROWSERS IGNORE CSS THEY DON’T UNDERSTAND

This means that you can use some old CSS, for example `floats`, <br>
`display:inline-block`, or `display: table-cell` to provide a grid type layout for older browsers, just as you would in the past. The browsers that do not support Grid Layout will use this layout and ignore all the grid instructions.
For more information see [this](https://rachelandrew.co.uk/css/cheatsheets/grid-fallbacks).

## Resources

Books, articles and tools related to _css grid module_.

- [Get Ready for CSS Grid Layout
  ](https://www.goodreads.com/book/show/28485920-get-ready-for-css-grid-layout) - book by Rachel Andrew
- [Grid by Example](https://gridbyexample.com/) - awesome tutorial and guides
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Grid guide on CSS-TRICKS simillar to flexbox cheatsheet.
- [CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - MDN web docs
- [cssgr.id](https://cssgr.id/) - An interactive CSS Grid code tool and generator
- Emojis are taken from [here](https://github.com/arvida/emoji-cheat-sheet.com)
- [Layoutit](https://www.layoutit.com/grid) - A CSS Grid Layout Interface Builder

---

> [Veljko Blagojevic](http://veljkoblagojevic.com)
