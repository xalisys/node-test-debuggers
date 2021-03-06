### Simple test cases for node debuggers based on 'hello world'.

`npm install && npm run build` to run webpack build which creates sourcemaps

- `npm start` - execute index.js without a debugger
- `npm run debug` - debug with https://nodejs.org/api/debugger.html
- `npm run chrome` - debug with chrome - https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27
- `npm run chrome:webpack` - same as above but runs webpack build output
- `npm run node-inspector` - debug with https://github.com/node-inspector/node-inspector
- `npm run devtool` - debug with https://github.com/Jam3/devtool
- `npm run iron-node` - debug with https://github.com/s-a/iron-node
- `npm run vscode` - opens https://code.visualstudio.com/ with config for debugging
- `npm run webstorm` - opens https://www.jetbrains.com/webstorm/ with config for debugging
