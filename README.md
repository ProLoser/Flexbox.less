Flexbox.less
============

CSS Flexbox mixins for LESS that adds back-compatibility for the 2009 syntax

All mixins use the **latest flexbox syntax** and merely add additional properties in the original syntax for you, 
as well as browser prefixes.

[Mozilla Documentation on Flexbox](https://developer.mozilla.org/en-US/docs/CSS/Using_CSS_flexible_boxes)

[A fun demo in 2009 syntax](http://flexiejs.com/playground/) (try setting box-flex to 1)

## Contribute

I will slowly be adding every flexbox property as I find a few spare minutes here and there. But if you are impatient
and want a specific property added, feel free to open a Pull Request. Please try to add backwards-compatibility
properties for the 2009 syntax to add a much larger range of browser support.

Values aren't always identical across syntaxes, in which case you can use [.flex-direction()](https://github.com/ProLoser/Flexbox.less/blob/master/mixins.less#L31-L60)
as an example of how to accomplish this.

## Conflicts

At this time, I'm unaware of any problems that may arise from using both the old and new syntax side by side in this
manner. If you find problems, feel free to open an issue, just be sure to **provide the browser version number.**

## TODO List

* align-content
* align-items
* align-self
* flex-basis
* flex-flow
* flex-grow
* flex-shrink
* flex-wrap
* justify-content
