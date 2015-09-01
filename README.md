2D Grid
=======

This is some css that allow add vertical space between bootstrap-col

## Getting Started
To enjoy it just link to your template or to your stylesheet the `css/bootstrap-2dgrid.css` file.

You can also use the scss file available at `scss/bootstrap-2dgrid.scss`. With this file you can overide easily customize the Sass variables listed below in order to define colors, sizes and more. There is no less version planned for now, if you would like one, report an issue, or use the v1.0 (written in less, but a little bit less good).

## Bower Usage
Install and manage Toggle Switch using Bower.
`$ bower install bootstrap-2dgrid`

## The 2D grid
Firstable, add to `.row` element the class `.row-2d` when you use the bootstrap grid system. This will put a vertical gutter between the cols (equals 30px).

```html
    <div class="row row-2d">
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
    </div>
```

## The row variant
In addition, we added variant in order to enjoy into your markup different gutter row. Add `.row-small` for smaller gutter (20px) or `.row-large` for larger gutter (40px).

```html
    <div class="row row-small">
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
    </div>
```

```html
    <div class="row row-large">
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
    </div>
```

## The 2d grid + variant
You can easily combine the both 2d grid and variant, just adding the two class to your row element.
```html
    <div class="row row-2d row-small">
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
    </div>
```
