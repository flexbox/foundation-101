# Design

## The principles of beautiful web design

### Layout and Composition

When most people think about grids, they think about engineering and architecture. However, the **grid is an essential tool for graphic design** as well, and the use of grids in website design have exploded in popularity in the last few years.

With the foundation framework you can [start with responsive templates.](http://foundation.zurb.com/templates.html)

![](http://foundation.zurb.com/assets/img/sites-templates/foundation6-templates-03.svg)

**Protip:** Keep It Simple. Try to follow the principes of [goodui.org](http://goodui.org/)

_Challenges:_

* [ ] Download a template
* [ ] Hack the grid and build your own layout

### Color

Don't write CSS here. We are going to use SCSS variables. First try to edit this file`<PROJECT_NAME>/src/assets/scss/settings.scss`

```scss
$foundation-palette: (
  primary: #1779ba,
  secondary: #767676,
  success: #3adb76,
  warning: #ffae00,
  alert: #cc4b37,
);
$light-gray: #e6e6e6;
$medium-gray: #cacaca;
$dark-gray: #8a8a8a;
$black: #0a0a0a;
$white: #fefefe;
```

Now you have defined your own colors your can use `$primary-color`, `$secondary-color` or `$black` for your design.

### Typography

### Icons

### Imagery

**Bonus:** you can use the [gravatar](https://fr.gravatar.com/) API if you need your face



