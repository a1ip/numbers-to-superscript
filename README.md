# numbers-to-superscript
Converts all numbers in text to superscript unicode characters

## Example

```javascript
const sup = require('numbers-to-superscript')

console.log(sup('21 Prove all things; hold fast that which is good.'))
```

Output:

```
²¹ Prove all things; hold fast that which is good.
```

## Install

```
npm i numbers-to-superscript
```

## API

### `require('numbers-to-superscript')(str)`
Converts all numbers in `str` into unicode superscript chracters

* `str` is a string containing any chracters

**Returns** `str` with all numbers converted to unicode superscript chracters

## License
(c) 2021 Philippe Rigovanov. MIT License
