# mdImage
mdImage is the fallback image directive

## Requirement
Note: You need [angular material](https://material.angularjs.org/latest/) to be installed in your project to use this directive

```html
<script src="mdImage.js"></script>
```
## app
```javascript
angular.module('myApp', ['mdImageFallback']);
```

## HTML
```html
<md-image src="src"></md-image>
```

## Controller
```javascript
$scope.src = 'your image src'
```
