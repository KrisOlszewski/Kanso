# [Kanso - Semantic Flat Buttons](http://www.kolszewski.com/kanso)
Set of semantic flat buttons written in CSS (Sass) and HTML. Font Awesome compatible.

Kanso (簡素), in Japanese aesthetics, means simplicity or elimination of clutter. Things are expressed in a plain, simple, natural manner. Reminds us to think not in terms of decoration but in terms of clarity, a kind of clarity that may be achieved through omission or exclusion of the non-essential.

[Live demo](http://www.kolszewski.com/kanso)

## Usage

**Base + Variation**
```html
<a class="Button">Default</a>
<a class="Button Button--primary">Primary</a>
<a class="Button Button--secondary">Secondary</a>
<a class="Button Button--outline">Outline</a>
<a class="Button Button--link">Link</a>
<a class="Button Button--info">Info</a>
<a class="Button Button--success">Success</a>
<a class="Button Button--warning">Warning</a>
<a class="Button Button--error">Error</a>
```

**Small**
```html
<a class="Button Button--small">Small</a>
```

**Large**
```html
<a class="Button Button--large">Large</a>
```

**Form**
```html
<input type="submit" class="Button" value="Submit">
<input type="Button" class="Button" value="Button">
<input type="reset" class="Button" value="Reset">
<button class="Button">Button</button>
```

**Disabled**
```html
<a class="Button is-disabled">Disabled</a>
```

**Button w/out text + Font Awesome**
```html
<a class="Button"><i class="fa fa-fw fa-search"></i></a>
```

**Button + Font Awesome**
```html
<a class="Button"><i class="fa fa-fw fa-search"></i> Search</a>
```

**Horizontal Group + Button + Font Awesome**
```html
<div class="ButtonGroup ButtonGroup--horizontal">
  <div class="ButtonGroup-item">
    <a class="Button Button--small Button--success"><i class="fa fa-fw fa-check"></i> New Email</a>
  </div>
</div>
<div class="ButtonGroup ButtonGroup--horizontal">
  <div class="ButtonGroup-item">
    <a class="Button Button--small Button--outline"><i class="fa fa-fw fa-mail-forward"></i> Forward</a>
  </div>
  <div class="ButtonGroup-item">
    <a class="Button Button--small Button--outline"><i class="fa fa-fw fa-archive"></i> Archive</a>
  </div>
  <div class="ButtonGroup-item">
    <a class="Button Button--small Button--outline"><i class="fa fa-fw fa-folder"></i> Move</a>
  </div>
</div>
<div class="ButtonGroup ButtonGroup--horizontal">
  <div class="ButtonGroup-item">
    <a class="Button Button--small Button--error"><i class="fa fa-fw fa-trash"></i> Delete</a>
  </div>
</div>
```

**Vertical Group + Small Button + Font Awesome**
```html
<div class="ButtonGroup ButtonGroup--vertical">
  <div class="ButtonGroup-item">
    <a class="Button Button--small Button--outline"><i class="fa fa-fw fa-euro"></i> EUR</a>
  </div>
  <div class="ButtonGroup-item">
    <a class="Button Button--small Button--outline"><i class="fa fa-fw fa-gbp"></i> GBP</a>
  </div>
  <div class="ButtonGroup-item">
    <a class="Button Button--small Button--outline"><i class="fa fa-fw fa-dollar"></i> USD</a>
  </div>
</div>
```

## Support
IE8+

## License & credits
The [MIT License](https://github.com/KrisOlszewski/Kanso/blob/master/LICENSE.md) (MIT).

Font Awesome Icons by [Dave Gandy](http://fontawesome.io/).
