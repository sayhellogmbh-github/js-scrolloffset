# Watch window scroll offset

jQuery script which watches the window scroll position and adds/removes a CSS
class to the HTML object as appropriate.

## Usage

By including this script, no further action is necessary. The CSS class name
`s-has--scrolloffset` will be applied and can be referenced in CSS:
`html.s-has--scrolloffset {…}`. The class name convention adheres to BEM
naming conventions: `s-has` being the block identifier and `--scrolloffset`
being the modifier.

Modify sayhellogmbh_js_scrolloffset in your own code if you want to react
after a certain number of pixels - e.g. 50 will add/remove the class when
the window scroll offset is 50px.

## Changelog

### 1.1.0 2019-09-24

* Add sayhellogmbh_js_scrolloffset control variable.

### 1.0.0 2019-07-05

* Initial @sayhellogmbh version.
