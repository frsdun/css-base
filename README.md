# css-base
A simple css library that normalizes and provides basic styling

Based on milligram v1.3.0 | MIT License | https://github.com/milligram/milligram

Build: `npm run build`

### File structure
```
css
├─── base.css
└─── base.min.css

scss
├─── base.scss
│
└─── base
      ├─── _blockquote.scss
      ├─── _button.scss
      ├─── _code.scss
      ├─── _color.scss
      ├─── _divider.scss
      ├─── _form.scss
      ├─── _image.scss
      ├─── _link.scss
      ├─── _list.scss
      ├─── _normalize.scss
      ├─── _shadow.scss
      ├─── _sizing.scss
      ├─── _spacing.scss
      ├─── _table.scss
      ├─── _transition.scss
      └─── _typography.scss
```

### Class based api:
All other css effect tags directly (these are the only classes used)
* `.muted` (typography) changes the text color to a muted color
* `.button` (button) changes an anchor tag into a button
* `.button-solid` (button) changes a button into a solid button
* `.button-clear` (button) changes a button into a clear button

### Dev dependencies
* node-sass
* uglifycss