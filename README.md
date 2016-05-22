# webcomponentsjs-empty-HTML-Imports-bug

A test case for a bug in [Web Components polyfill - webcomponents/webcomponentsjs](https://github.com/webcomponents/webcomponentsjs).

As you can see in [live example](http://tomalec.github.io/webcomponentsjs-empty-HTML-Imports-bug/) polyfill does not execute `.onload` callback for `<link rel="import">` that loads empty file `text/html 200 Ok ""`.


Issue reported at [webcomponents/webcomponentsjs#535](https://github.com/webcomponents/webcomponentsjs/issues/535)
