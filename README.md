Preferences
===========

This repo contains files for my configs, prefs, code style and standard templates



Configs and Prefs
-----------------

* [`.gitconfig`](.gitconfig) - My personal list of Git command aliases
  * In Windows, line endings should be written in Windows-style `CRLF`, and committed as Unix-style `LF`
* [`.gitignore_global`](.gitignore_global) - My personal list of files for Git to ignore



Standard templates
------------------
* [`html.html`](html.html) - Specification and standard compliant HTML document ready for use on websites
* [`jade.jade`](jade.jade) - Equivalent of `html.html` written in Jade
* [`reboot.css`](`reboot.css`) - CSS reset utilising Nicolas Gallagher's [Normalize.css](https://github.com/necolas/normalize.css) and Bootstrap's [Reboot](https://github.com/twbs/bootstrap/blob/v4-dev/scss/_reboot.scss)
* [`css-selector-order.md`](`css-selector-order.md`) - CSS selector order inspired by Jens Oliver Meiert's [How to Order CSS Selectors](http://meiert.com/en/blog/20130130/how-to-order-css-selectors/)



Code style
----------

### HTML/CSS
* [HTML class namespacing](http://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/) with [BEM class naming convention](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/)
  * Class names are written as lowercase words separated by hyphens (`-`) and <span style="color:red">avoid using camel case or underscores</span>
  * Example namespaced class names:
    * `o-object`
    * `c-component`
    * `t-theme`
    * `s-scope`
    * `u-utility`
    * `_hack`
    * `js-javascript-hooks`
    * `qa-qa-hooks`
  * Example namespaced class names with BEM convention:
    * `c-component__element`
    * `c-component--modifier`


### CSS
* [`.csscomb.json`](.csscomb.json) - My config for [CSScomb](https://github.com/csscomb/csscomb.js)
  * Includes my CSS property sort order (inspired by Nicolas Gallagher's [Idiomatic CSS declaration order](https://github.com/necolas/idiomatic-css#declaration-order))
* [`.csscomb.js`](.csscomb.js) - JavaScript version of `.csscomb.js` with comments


### JavaScript
* Should generally pass JSHint linting


### Python
* Adhere to [PEP 8](https://www.python.org/dev/peps/pep-0008/) as close as possible
