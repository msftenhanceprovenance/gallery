# gallery

Super lightweight lightbox gallery with no dependencies.

## Usage
Will look for images with the attribute `data-gallery-src` and open a lightbox gallery on click.

Look in `example.html` for example usage.

### Available tags
#### `data-gallery-src`
URL to large image to use in gallery

#### `data-gallery-desc`
*(Optional)* Description text/html to use below image in gallery

#### `data-gallery-id`
*(Optional)* Used to group multiple images in a gallery. If not specified will treat image to be part of global gallery.

## Override styles
You can override the styles in `gallery` by plain css. The selectors used that can be overriden are:
```
.gallery-lightbox
.gallery-lightbox.-open
.gallery-lightbox > .close
.gallery-lightbox > .close
.gallery-lightbox > .close:after
.gallery-lightbox > .close:before
.gallery-lightbox > .description
.gallery-lightbox > .image
.gallery-lightbox > .image > img
.gallery-lightbox > .next
.gallery-lightbox > .next:after
.gallery-lightbox > .next:before
.gallery-lightbox > .prev
.gallery-lightbox > .prev:after
.gallery-lightbox > .prev:before
```