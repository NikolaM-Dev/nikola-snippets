<div align="center">
	<img width="250" src="./images/logo.png" alt="nikola-logo" />
	<h1 align="center">🌌 Nikola Snippets 🌌</h1>
</div>

## Supported languages (file extensions)

- JavaScript (.js)
- JavaScript React (.jsx)
- TypeScript (.ts)
- TypeScript React (.tsx)
- CSS (.css)
- MarkDown (.md)

## Javascript / Typescript

|  Prefix | Method                                         |
| ------: | ---------------------------------------------- |
|  `imp→` | `import moduleName from 'module';`             |
|  `imd→` | `import { destructuredModule } from 'module';` |
|  `req→` | `const moduleName = require('module');`        |
| `reqd→` | `const { moduleName } = require('module');`    |
|   `ed→` | `export default moduleName`;                   |
|   `me→` | `module.exports = { moduleName };`             |
|   `cl→` | `console.log('', );`                           |
|   `ce→` | `console.error('');`                           |
|   `fn→` | `const functionName = (params) => `            |
|  `afn→` | `const functionName = async (params) => `      |
|    `c→` | `const name = value; `                         |
|    `l→` | `let name = value;`                            |
|  `obj→` | `const name = { value };`                      |
|  `arr→` | `const name = [ value, ];`                     |
|  `des→` | `const {name} = value;`                        |
| `desa→` | `const [name] = value;`                        |
|   `ut→` | `export const nameFunction = () => `           |

## React ⚛️

|  Prefix | Method                              |
| ------: | ----------------------------------- |
|  `imr→` | `import React from react';`         |
| `imrd→` | `import react-DOM from react-dom';` |
|   `fm→` | `<> fragment </>`                   |

## MarkDown

|   Prefix | Method                 |
| -------: | ---------------------- |
|     `c→` | ` ```language $0 ``` ` |
|     `a→` | `[text][http://]`      |
|   `img→` | `[alt][http://]`       |
| `table→` | `One table 2 x 2`      |

## CSS

|  Prefix | Method                                    |
| ------: | ----------------------------------------- |
|  `var→` | `var(--name);`                            |
| `dvar→` | `--name: value;`                          |
|  `rgb→` | `rgb(red, green, blue);`                  |
|  `rgb→` | `rgba(red, green, blue, alpha);`          |
|  `hsl→` | `hsl(hue, saturation, lightness);`        |
|  `hsl→` | `hsl(hue, saturation, lightness, alpha);` |

<br />

## Javascript / Typescript `View`

### `cl`

```javascript
console.log('');
```

### `ce`

```javascript
console.error(|);
```

### `imp`

```javascript
import moduleName from 'module';
```

### `imd`

```javascript
import { moduleName } from 'module';
```

### `req`

```javascript
const moduleName = require('module');
```

### `reqd`

```javascript
const { moduleName } = require('module');
```

### `fn`

```javascript
const nameFunction = (params) => |
```

### `afn`

```javascript
const nameFunction = async (params) => |
```

### `c`

```javascript
const name = value;
```

### `l`

```javascript
let name = value;
```

### `obj`

```javascript
const name = {
  value,
};
```

### `arr`

```javascript
const name = [value];
```

### `des`

```javascript
const { value } = name;
```

### `desa`

```javascript
const [value] = name;
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

## React ⚛️ `View`

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

## MarkDown `View`

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

## CSS `View`

### `var`

```css
var(--name);
```

`dvar`

```css
--name: value;"
```

### `rgb`

```css
rgb(red, green, blue);
```

### `rgba`

```css
rgba(red, green, blue, alpha);
```

### `hsl`

```css
hsl(hue, saturation, lightness);"
```

### `hsla`

```css
hsla(hue, saturation, lightness, alpha);
```

<br />

> 🇪🇦 Añade un pr si quieres que agrege tu snippet favorito

> 🇬🇧 Add one pr if you want me to add your favorite snippet

<br />

<div align="center">

Made with 💜 for [**NikolaM-Dev**]('https://github.com/NikolaM-Dev')

</div>
