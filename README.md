# 12columns.css

Simple grid system based on Flexbox and CSS Grid Layout. View demo [here](https://kathykato.github.io/12columns).

## How to Use

Add the [CSS file](https://raw.githubusercontent.com/kathykato/12columns/master/12columns.css) to your project:
```html
<link href="12columns.css" rel="stylesheet" type="text/css">
```

## Usage

This grid system uses a 12-column grid and is fully responsive. Columns are wrapped within a ```grid``` class.
```html
<div class="grid">
  <div class="column-xs-12 column-md-1">1</div>
  ...
  <div class="column-xs-12 column-md-12">12</div>
</div>
```

## Browser Support
12columns uses [Flexbox](https://caniuse.com/#feat=flexbox) by default and ```@supports``` as a fallback for the browsers supporting [CSS Grid Layout](https://caniuse.com/#feat=css-grid).

## License
[MIT License](https://opensource.org/licenses/MIT)
