# karma-no-mocha

> karma-mocha without the peer dependency of mocha

**You probably don't want this package; install [karma-mocha](https://www.npmjs.com/package/karma-mocha) instead.**

This is [karma-mocha](https://www.npmjs.com/package/karma-mocha), slightly tweaked to test [Mocha](https://www.npmjs.com/package/mocha) itself.  

## Options

In your Karma config file, the `karmaMocha.mochaDir` key is available to specify the path to the `mocha` package root dir:

```js
{
  karmaMocha: {
    mochaDir: '/path/to/node_modules/mocha'
  }
}
```

In the case of `mocha` itself, the value of `mochaDir` is just `__dirname`.
