# Offscreen
offscreen processing using invisible child iframes

### Overview
Uses iframes of zero width, height to load another document in the background. The child iframe calls a function of the parent's. This way two different JS contexts can communicate between each other on the same domain.

### To run

Serve the files from a basic static HTTP server. If you are on OSX, you can use SimpleHTTPServer

```
$ python -m SimpleHTTPServer
```
Open `http://localhost:8000/` in your browser

### Uses
1. Can be used for preloading and caching iframe documents, so they load faster
2. An alternative to Ajax

### Browser Compatibility
* Chrome 4.0+
* Firefox 3.0+
* IE 7+
* Opera 9.5+
* Safari 4.0+
* iOS Safari 3.2+
* Chrome for Android 31.0+

### License
MIT