<div align="center">
	<img width="250" src="./images/logo.png" alt="nikola-logo" />
	<h1 align="center">🌌 Nikola Snippets 🌌</h1>
</div>

## Javascript / Typescript

### `cl`

```javascript
console.log(${1:'$2', $3});
```

### `ce`

```javascript
console.error($1);
```

### `imp`

```javascript
import ${2:moduleName} from '${1:module}';
```

### `req`

```javascript
const ${2:moduleName} = require('${1:module}');
```

### `imd`

```javascript
import { $2 } from '${1:module}';
```

### `fn`

```javascript
const $1 = ($3) => $4;
```

### `afn`

```javascript
const $1 = async ($3) => $4;
```

### `c`

```javascript
const $1 = $2;
```

### `l`

```javascript
let $1 = $2;
```

### `obj`

```javascript
const $1 = {
  $2,
};
```

### `arr`

```javascript
const $1 = [$2];
```

### `des`

```javascript
const { $2 } = $1;
```

### `ed`

```javascript
export default $TM_FILENAME_BASE;
```

### `me`

```javascript
module.exports = ${ $TM_FILENAME_BASE };
```

## Testing

### `desc`

```javascript
describe('$1', () => {
	$0,
});
```

### `test`

```javascript
test('should $1', () => {
	$0,
});
```

### `testa`

```javascript
test('should $1', async () => {
	$0,
});
```

### `it`

```Javascript
it('should $1', () => {
	$0,
})
```

### `ita`

```Javascript
it('should $1', async () => {
	$0,
})
```

### `ut`

```javascript
export const $TM_FILENAME_BASE = () => {
  $0;
};
```

## React ⚛️

### `imr`

```javascript
import React from 'react';
```

### `imrd`

```javascript
import React-DOM from 'react-dom';
```

### `fm`

```
<>
	$0
</>
```

### `rfc`

```javascript
import React from 'react';

const $TM_FILENAME_BASE = () => {
  return (
    <>
      <h1>$TM_FILENAME_BASE</h1>
      $0
    </>
  );
};

export default $TM_FILENAME_BASE;
```

## MarkDown

### `c`

````markdown
```language
$0
```
````

### `a`

```markdown
[text](http://)
```

### `img`

```markdown
![alt](http://)
```

## CSS

### `var`

```css
var(--$1): $2;
```

### `rgb`

```css
rgb($1, $2, $3);
```

### `rgba`

```css
rgba($1, $2, $3, $4);
```

### `hsl`

```css
hsl($1, $2, $3);"
```

### `hsla`

```css
hsla($1, $2, $3, $4);
```

<br />

> 🇪🇦 Añade un pr si quieres que agrege tu snippet favorito

> 🇬🇧 Add one if you want me to add your favorite snippet

<br />

<div align="center">

Made with 💜 for [**NikolaM-Dev**]('https://github.com/NikolaM-Dev')

</div>
