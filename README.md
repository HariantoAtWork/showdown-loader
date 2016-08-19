# markdown (showdown-ghost) loader for webpack


## Installation

```sh
npm install -S showdown-loader
```


## Usage

In your `webpack.config.js` file:

```js
module.exports = {
  module: {
    loaders: [{
      test:   /\.md/,
      loader: 'showdown'
    }]
  }
};
```

See `webpack` documentation.

## License

MIT (http://www.opensource.org/licenses/mit-license.php)