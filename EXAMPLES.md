Examples
========

All mixins are named after the latest specification's syntax and take identical args (except `.flexbox()`).

All prefixes (`-webkit-, -moz-, -ms-, -o-`) are prepended to every property.

```sass
.flexbox();
// becomes:
display: box;
display: flex;

.flex(1);
// becomes:
box: 1;
flex: 1;

.flex-direction(column-reverse);
// becomes:
box-orient: vertical;
box-direction: reverse;
flex-direction: column-reverse;

.order(2);
// becomes:
box-ordinal-group: 2;
order: 2;
```
