Flexbox.less
============

CSS Flexbox mixins for LESS that adds back-compatibility for the 2009 syntax

All mixins use the **latest flexbox syntax** and merely add additional properties in the original syntax for you, 
as well as browser prefixes.

## Demo

Checkout this [demo page](http://proloser.github.com/Flexbox.less/demo.html) in different browsers.

## Why?

**Combining 2009 and Edge syntaxes will give you the greatest browser support coverage!**

> The old 2009 syntax has surprisingly good browser "support": Chrome, Firefox 2+, Safari 3.1+... Pretty much everything except IE 9- and Opera anything. I say "support" because the actual implementations were partial and differed a bit (hence the re-write).
>
> Despite more support, it's not smart to be using the older syntax. The old spec is gone with the wind. Browsers might drop support for the old syntax in the future. At the least, it's very likely the new syntax is easier to understand and will be implemented more deeply and more consistently. Browsers that don't yet support Flexbox will implement the new spec, which is in "CR" (Candidate Recommendation) status.
>
> New syntax support is: Chrome 21+, Opera (& Opera Mobile) 12.1+, and Blackberry 10+.
>
> \- [_Chris Coyier_](http://css-tricks.com/old-flexbox-and-new-flexbox/)

## References

* [CanIUse.com browser-coverage](http://caniuse.com/#feat=flexbox)
* [Official Spec](http://www.w3.org/TR/css3-flexbox/)
* [Mozilla Documentation on Flexbox](https://developer.mozilla.org/en-US/docs/CSS/Using_CSS_flexible_boxes)
* [Paul Irish / HTML5 Rocks](http://www.html5rocks.com/en/tutorials/flexbox/quick/)
* [Chris Coyier / Old vs New flexbox](http://css-tricks.com/old-flexbox-and-new-flexbox/)

## Contribute

I will slowly be adding every flexbox property as I find a few spare minutes here and there. But if you are impatient
and want a specific property added, feel free to open a Pull Request. Please try to add backwards-compatibility
properties for the 2009 syntax to add a much larger range of browser support.

Values aren't always identical across syntaxes, in which case you can use [.flex-direction()](https://github.com/ProLoser/Flexbox.less/blob/master/flexbox.less#L46-L75)
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
* justify-content

## License

#### [WTFPL](http://www.wtfpl.net/about/)
