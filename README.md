# SVG Placeholders For Testing

This repo provides a gh-page from which the included graphics can be hotlinked.

Each image is originally 500px x 500px. They deviate from each other in the attributes that are specified on the SVG tag:

- `<svg ... viewBox="0 0 500 500" width="500px" height="500px" preserveAspectRatio="xMinYMin meet"> ...` (as per [these tests](http://soqr.fr/testsvg/svg-inside-img.php))
- `<svg ... viewBox="0 0 500 500" width="500px" height="500px"> ...` (Illustrator default)
- `<svg ... viewBox="0 0 500 500"> ...` (as per [this answer on StackOverflow](http://stackoverflow.com/questions/9777143/svg-in-img-element-proportions-not-respected-in-ie9/9792254#9792254))
- `<svg ...> ...`

This repo is largely a result of issues arising from attempting to properly scale SVG images in IE9+. Progress, hints, and tests are available in [this gist](https://gist.github.com/larrybotha/7881691) and [this codepen](http://codepen.io/larrybotha/pen/hmlAs).

All graphics are copyright of [Fixate](http://fixate.it). Please place a credit on any page using any of these images, thanks!
