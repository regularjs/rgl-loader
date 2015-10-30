## rgl-loader

loader  for load regular template in webpack. 

### Setup

In your `webpack.config.js` or `gulp-webpack` options.

```

var path = require('path');

module.exports = {
    entry: "./src/index.js",
    output: {
        path: __dirname ,
        filename: "bundle.js"
    },
    module: {
        loaders: [
            { test: /\.rgl$/, loader: 'rgl' }
        ]

    }
};

```


### Example

[regularjs/example#webpack](https://github.com/regularjs/example#webpack)