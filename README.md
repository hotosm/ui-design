# HOTOSM Design Library

You'll find here a HOTOSM UI design system to be implemented by any
HOT project, including the [HOTOSM UI library](https://github.com/hotosm/ui).

## Assets

Check the `/assets` folder for logos and font files.

## Design

Check `/pdf` folder for design.

### Figma

[Check the Figma files](https://www.figma.com/design/1i7QtxacGpUp5dchd6DQTB/hotosm-ui-design-v0%E2%80%A42?m=auto&t=TD5gEf36gZTs7BIe-1)

## CSS

A CSS implementation is available in the /css folder, including themes
for common frameworks like Shoelace and Web Awesome.

All CSS files are available in a CDN:

* https://cdn.jsdelivr.net/npm/hotosm-ui-design@latest/dist/hot.css
* https://cdn.jsdelivr.net/npm/hotosm-ui-design@latest/dist/hot-font-face.css

Including lib themes:

* https://cdn.jsdelivr.net/npm/hotosm-ui-design@latest/dist/hot-sl.css (Shoelace)
* https://cdn.jsdelivr.net/npm/hotosm-ui-design@latest/dist/hot-wa.css (Web Awesome)


And you can also install the NPM package:

`npm i hotosm-ui-design`

And import the CSS files:

```
@import 'hotosm-ui-design/dist/hot.css';
@import 'hotosm-ui-design/dist/hot-font-face.css';
```

For using `hot-font-face.css`, you'll need the `.ttf` files available in `public/assets/fonts`.


