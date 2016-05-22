# webcomponentsjs-empty-HTML-Imports-bug

A test case for a bug in [Web Components polyfill - webcomponents/webcomponentsjs](https://github.com/webcomponents/webcomponentsjs).

It does not execute `.onload` callback for `<link rel="import">` that loads empty file `text/html 200 Ok ""`.
