# ionicLocalStorage
Local storage for ionic 1

## Install

```bash
bower install ionic-localstorage
```

## Example

```html
...
  <script src="lib/ionic-localstorage/ionicLocalStorage.js"></script>
...

```

```js
angular.module('app', ['ionic', 'ionicLocalStorage'])

.controller('abstractCtrl', function($scope, ionicLocalStoragenService) {
  ionicLocalStoragenService.set('var', 'test');
});

```

## License
MIT
