# WebGPU Webpack Starter

A starter template for WebGPU development that uses [webpack](https://webpack.js.org/) to build the code
and manage dependencies.

## Getting Started

After cloning the repo run

```
npm install
```

To install webpack, then you can run the serve task and point your browser to `localhost:8080`:

```
npm run serve
```

Where you should find our triangle.

To deploy your application, change the `mode` in `webpack.config.js` to `production` and run

```
npm run build
```

Then you can copy the content of the `dist/` directory to your webserver.

