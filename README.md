# DynaWP

DynaWP is a JavaScript wallpaper library that adds effect like Parallax.js engine.

## Installation

1) Import the code:
```html
<script src="DynaWP"></script>
```

2) Create a `div` and set attributes:
```html
<div id="wallpaper" effectscale="0.25" reactscale="2" effectimg="wallpaper.webp"></div>
```

## Usage
* `id`: To set a element as wallpaper, you need to change it's `id` to `wallpaper`.
* `effectscale`: Time to react the mouse move in seconds. For example, `0.25` means it'll take 0.25 second to complete requested animation.
* `reactscale`: Moving value of image in screen size's percentage. For example, `1` means it'll set image size as 102% and change image position between `-1vh`/`-1vw` and `1vh`/`1vw`.
* `effectimg`: Background image URL for element.
Note: You must set all `id`, `effectscale`, `reactscale`, `effectimg` attributes to work properly.
