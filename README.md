2D Grid
=======

This is some css that allow add vertical space between bootstrap-col

## Getting Started
To enjoy it just link to your template or to your stylesheet the `css/bootstrap-2dgrid.css` file.

You can also use the scss file available at `scss/bootstrap-2dgrid.scss`. With this file you can overide easily customize the Sass variables listed below in order to define colors, sizes and more. There is no less version planned for now, if you would like one, report an issue, or use the v1.0 (written in less, but a little bit less good).

## Bower Usage
Install and manage Toggle Switch using Bower.
`$ bower install bootstrap-2dgrid`

## The Markup
Firstable, add to `.row` element the class `.row-2d` when you use the bootstrap grid system. This will put a vertical gutter between the cols (equals 30px).

``` (html)
    <div class="row grid">
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
    </div>
```

###Grid with a 10px setted gutter space
    <div class="row grid grid-10">
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
    </div>

###Grid with responsive setted gutter space
    <div class="row grid grid-xs-5 grid-sm-1 grid-md-30 grid-lg-40">
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
        <div class="col-xs-12 col-sm-6 col-md-4 col-lg-3"></div>
    </div>

## Less Variables
The variables can be founded in `/less/parameters/module`

* @2Dgrid_GeneratorLimit: 50
* @2Dgrid-gutterDefault-size: 30px
* @2Dgrid-screen-sm-min: 768px
* @2Dgrid-screen-md-min: 992px
* @2Dgrid-screen-lg-min: 1200px

designed by Loïc Goyet for AppVentus. with love from Nantes
