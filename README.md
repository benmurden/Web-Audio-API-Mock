# Web-Audio-API-Mock
A mock class for testing apps that use Web Audio API. Compatible with headless browsers like PhantomJS.

Based on https://github.com/jsantell/allen, but passing jsHint and not using CoffeeScript, this is a simple `AudioContext` mock class that attaches to the `window` object, where there wouldn't ordinarily be such an object on headless browsers.

## Motivation
The prupose here is to mock away the API so you can focus on testing other things, with a little sanity checking thrown in. If you need a fully featured test API for Web Audio API, may I suggest https://github.com/mohayonao/web-audio-test-api.

However, if you don't need integration testing with your use of the API, and you want fast tests, this is for you.
