All you need to do in your karma config

```js
module.exports = function (config) {
  config.set({
    basePath: '',
    frameworks: ['jasmine', '@angular-devkit/build-angular'],
    plugins: [
      ...
      require('@windmillcode/karma-chronium-edge-launcher'),
    ],
  ....
    browsers: ['Edge'],


  });
};

```
that's it
