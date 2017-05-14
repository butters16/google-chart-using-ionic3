
Steps to reproduce
1. create blank project using ionic3 cli
2. install google-chart `npm install angular2-google-chart`
3. modify app.module.ts to import GoogleChart and add it to declarations
4. override home.ts compnent to look like angular2-google-chart README

Error looks like this
```
platform-browser-dynamic.es5.js:170 Uncaught TypeError: (void 0) is not a function
    at Object.<anonymous> (platform-browser-dynamic.es5.js:170)
    at __webpack_require__ (bootstrap 3cf6321…:19)
    at Object.<anonymous> (src async:7)
    at __webpack_require__ (bootstrap 3cf6321…:19)
    at Object.<anonymous> (main.js:111954)
    at __webpack_require__ (bootstrap 3cf6321…:19)
    at bootstrap 3cf6321…:65
    at bootstrap 3cf6321…:65
```
