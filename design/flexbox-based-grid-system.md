# Flex Grid

**Deep dive into our flexible, powerful grid:**

Learn how to quickly build complex responsive layouts using the Foundation grid.

/Users/cerebro/tmp/trash/

@include foundation-grid;

// @include foundation-flex-grid;

`<PROJECT_NAME>/src/assets/scss/app.scss`

`<PROJECT_NAME>/src/assets/scss/_settings.scss`

$global-flexbox: false;

_Challenge_

* [ ] Activate the flexbox grid

## [Block grid](http://foundation.zurb.com/sites/docs/flex-grid.html#block-grids)

Create evenly spaced blocks and get elements to line up easily. You can **define column widths at the row-level**, instead of the individual column level.

```html
<div class="row small-up-1 medium-up-2 large-up-3">
  <div class="column">1 per row on small</div>
  <div class="column">2 per row on medium</div>
  <div class="column">3 per row on large</div>
</div>
```

## [Source Ordering](http://foundation.zurb.com/sites/docs/flex-grid.html#source-ordering)

Shift columns around between our breakpoints to dictate how responsive layouts are viewed.


~~~html
<div class="row">
  <div class="column small-order-2 medium-order-1">
    This column will come second on small, and first on medium and larger.
  </div>
  <div class="column small-order-1 medium-order-2">
    This column will come first on small, and second on medium and larger.
  </div>
</div>
~~~

