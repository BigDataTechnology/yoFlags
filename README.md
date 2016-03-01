# yoFlags

AngularJs directive for get flag from country code

  - Type some Markdown on the left
  - See HTML in the right
  - Magic
### Dependencies
  - Angular ~1.5.0

### Installation
Bower:

```sh
$ yoFlags=git@git.bdt.systems:dev/flags.git --save
```

```javascript
angular.module('appName', [
  'yoFlags'
])
```

### Use

```html
<flag country="us" size="16"></flag>
<flag country="us" size="32"></flag>
```