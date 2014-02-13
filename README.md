randomclass-directive
=====================

Very simple directive for randomizing a class on an element.

#### Install with Bower:

```
bower install randomclass-directive
```

#### Include the directive in your Angular module:

```
var myApp = angular.module('myApp', ['randomclass-directive']);
```

## Usage

Use the `random-class` directive on the element you want to apply a random class to. Also set the `classPrefix` as the prefix of your class. A random number will be appended to the class based on a range from the `min` and `max` you set.

```html
<div random-class class-prefix="example" min="1" max="10"></div>
```