# Design

## The principles of beautiful web design

### Layout and Composition

When most people think about grids, they think about engineering and architecture. However, the **grid is an essential tool for graphic design** as well, and the use of grids in website design have exploded in popularity in the last few years.

With the foundation framework you can [start with responsive templates.](http://foundation.zurb.com/templates.html)

![](http://foundation.zurb.com/assets/img/sites-templates/foundation6-templates-03.svg)

**Protip:** Keep It Simple. Try to follow the principes of [goodui.org](http://goodui.org/).

_Challenges:_

* [ ] Download a template
* [ ] Hack the grid and build your own layout
* [ ] If you feel lost just edit this file for now `<PROJECT_NAME>/src/pages/index.html`

### Color

At the beginnig a beautiful webdesign only need 3 colors. In this example you can see one main contrasted color \(red\), versus others colors \(green\).

![](/assets/webdesign-colors.png)

Don't write CSS here. We are going to use SCSS variables.

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

**Protip:** There are a lot of color scheme generator, try to use one like [colorhunt.co](http://www.colorhunt.co/)

_Challenges:_

* [ ] Find a great color scheme
* [ ] Edit this file`<PROJECT_NAME>/src/assets/scss/settings.scss`

### Typography

For a great font pairing you can use [fonts.google.com](https://fonts.google.com/)

In the foundation world, you only need to edit theses variables and BAM your hole website is updated.

```scss
$body-font-family: 'Helvetica Neue', Helvetica, Roboto, Arial, sans-serif;
```

```scss
// 4. Base Typography
// ------------------

$header-font-family: $body-font-family;
```

**Protip:** Maximum 2 types of differents fonts because web performance matters.

_Challenges:_

* [ ] Find a great font combinaison
* [ ] Edit this file`<PROJECT_NAME>/src/assets/scss/settings.scss`

### Icons

One the fastest solution to have icons is to use [fontawesome.io](http://fontawesome.io/)

Just add the CDN link on your `<head>`

```html
<link href="https://netdna.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
```

_Challenges:_

* [ ] Choose an icon library
* [ ] Edit this file`<PROJECT_NAME>/src/layouts/default.html`

### Imagery

[unsplash.com](https://unsplash.com/) is a great website for high-resolution photos.

**Bonus:**

* [ ] You can use the [gravatar](https://fr.gravatar.com/) API if you need your face
* [ ] Use the [ImageOptim-CLI](https://github.com/JamieMason/ImageOptim-CLI) because web performance matters



