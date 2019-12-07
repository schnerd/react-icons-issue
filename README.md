```
$ node index.js

internal/modules/cjs/loader.js:236
      throw err;
      ^

Error: Cannot find module './node_modules/react-icons/lib'. Please verify that the package.json has a valid "main" entry
    at tryPackage (internal/modules/cjs/loader.js:228:19)
    at Function.Module._findPath (internal/modules/cjs/loader.js:365:18)
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:612:27)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Module.require (internal/modules/cjs/loader.js:683:19)
    at require (internal/modules/cjs/helpers.js:16:16)
    at Object.<anonymous> (index.js:1:15)
    at Module._compile (internal/modules/cjs/loader.js:776:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:787:10)
    at Module.load (internal/modules/cjs/loader.js:643:32) {
  code: 'MODULE_NOT_FOUND',
  path: './node_modules/react-icons/package.json',
  requestPath: 'react-icons'
}
```

```
$ node -v
v12.6.0
```
