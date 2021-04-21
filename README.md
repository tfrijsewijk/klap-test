# l2

* clone repo
* `npm install` (or `yarn install`)
* `npm run build` (or `yarn build`)

NPM or Yarn, doesn't matter ->

```
SyntaxError: Unexpected token (3:9) in D:\temp\l2\src\loader.js
(node:27024) UnhandledPromiseRejectionWarning: Error: SyntaxError: Unexpected token (3:9) in D:\temp\l2\src\loader.js
    at build (D:\temp\l2\node_modules\klap\dist\index.js:2360:1139206)
(node:27024) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). To terminate the node process on unhandled promise rejection, use the CLI flag `--unhandled-rejections=strict` (see https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode). (rejection id: 3)
```

To fix this, rename the word `process` in `src/loader.js` to something else, capitalize it for all I care and tada!
