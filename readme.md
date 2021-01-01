# proto-props

> List of prototype properties for [JavaScript types](https://github.com/sindresorhus/js-types)

It's just a [JSON file](proto-props.json) and can be used wherever.


## Install

```
$ npm install proto-props
```


## Usage

```js
const prototypeProperties = require('proto-props');

console.log(prototypeProperties);
/*
{
	Array: [
		'length',
		'constructor',
		'toString',
		'toLocaleString',
		'join',
		'pop',
		…
	],
	ArrayBuffer: [
		'constructor',
		'byteLength',
		'slice'
	],
	…
}
*/
```


## Dev

The JSON file is generated by running:

```
$ npm run make
```


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
