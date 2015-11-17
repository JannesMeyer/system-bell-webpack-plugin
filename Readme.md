# System Bell plugin for webpack

## Installation

	npm install system-bell-webpack-plugin --save-dev

## Usage

```js
var SystemBellPlugin = require('system-bell-webpack-plugin');

// webpack configuration
var config = {
	entry: …,
	output: {
		path: …,
		filename: …
	},
	plugins: [
		new SystemBellPlugin()
	]
};
module.exports = config;
```
