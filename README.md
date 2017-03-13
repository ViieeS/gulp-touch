# gulp-touch

Update the access and modification times of each FILE to the current system time.

## Example

```js
var gulp = require('gulp');
var touch = require('gulp-touch');

gulp.task('default', function() {
  gulp
    .src('./src/**/*')
    .pipe(gulp.dest('./dest'))
    .pipe(touch());
});
```
