# Simple media queries [![npm][npm-image]][npm-url]
[npm-image]: https://img.shields.io/npm/v/simple-media-queries.svg
[npm-url]: https://npmjs.org/package/simple-media-queries

This repository contains SCSS-mixins which allow you to easily use media queries in SCSS. With this approach, you don't override previous defined code, but only target the desired screenrange.

## The mixins

```scss
.selector {
  // Include general theming here
  
  @include down(600) {
    // Theming for small screens here
  }

  @include between(600, 1200) {
    // Theming for screens between 600px and 1200px here 
  }

  @include up(1200) {
    // Theming for big screens here
  }

  @include outside(600, 1200) {
    // Theming for screens below 600px and above 1200px 
  }
}
```

[Codepen-demo](https://codepen.io/MartijnCuppens/pen/XaKmBJ) 
