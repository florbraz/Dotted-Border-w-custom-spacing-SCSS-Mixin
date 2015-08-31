# Dotted Border with increased spacing - A SCSS Mixin

Ever wanted to increase spacing between the dots of border-style:dotted? Now you can (easy SCSS implementation)!  :) 
This mixin will help you implement spaced dotted borders in a quick and easy way.

##Usage

`@include dottedBorder`

Will add the border to element's top, dots measuring 1px and 5px spacing between dots.

##Documentation

To change default settings, use `@include dottedBorder($color: #000, $size:2px)`

| Property     | Possible Values                      | Default Value |
|--------------|--------------------------------------|---------------|
| $color       | Color (hexadecimal, rgba...)         | `#8f8f8f`     |
| $orientation | `horizontal` or `vertical`           | `horizontal`  |
| $position    | `top`, `bottom`, `left`, `right`     | `top`         |
| $spacing     | CSS measure unit (`5px`, `1em` etc.) | `5px`         |
| $size        | CSS measure unit (`5px`, `1em` etc.) | `1px`         |


##Todo:
* Support for multiple borders (all around, 2+ orientations)
* Add SASS mixin

