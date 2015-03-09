# flex-sass-mixins
Clean sass mixins for cross-browser and fallback flex.<br />
There are other mixins for flexbox using SASS, but this one is better.<br />
Also it is based on [@mmcbride1007](http://github.com/mmcbride1007)'s [`flexbox-mixins`]((http://github.com/mmcbride1007/flexbox-mixins) for `LESS`.<br />

<h2>How to use</h2>
1. Copy `_flex.scss` into your styles directory
2. Be sure to import the file into your project with either an `@import` or a `link` in the head
3. These mixins stick to the original class declarations of flex with few shortcuts, so all you have to do is:
```scss
.class{
  @include flex-display();
}
```
and then...$$$.
