[![Build Status](https://travis-ci.org/studio107/flexy-block-grid.svg?branch=master)](https://travis-ci.org/studio107/flexy-block-grid)

# mixin: flexy-block-grid

```scss
.b-block-grid {
  // flexbox block-grid
  @include flexy-block-grid(false);
  
  // float-left block-grid (legacy)
  @include flexy-block-grid(true);
}
```

# default classes

```scss
.b-block-grid
```

```html
<div class="b-block-grid b-block-grid_small_2 b-block-grid_medium_4">
    <div class="b-block-grid__item">
        hello grid
    </div>
</div>
```
