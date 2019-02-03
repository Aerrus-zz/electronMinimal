# electronMinimal

```
cd mods
npm install
cd ..

npm install
npm start
```

Can use `npm rebuild` in project root to rebuild the module specifically.


```
> electron .


 App threw an error during load
Error: Module did not self-register.
    at process.module.(anonymous function) [as dlopen] (ELECTRON_ASAR.js:160:31)
    at Object.Module._extensions..node (internal/modules/cjs/loader.js:722:18)
    at Object.module.(anonymous function) [as .node] (ELECTRON_ASAR.js:160:31)
    at Module.load (internal/modules/cjs/loader.js:602:32)
    at tryModuleLoad (internal/modules/cjs/loader.js:541:12)
    at Function.Module._load (internal/modules/cjs/loader.js:533:3)
    at Module.require (internal/modules/cjs/loader.js:640:17)
    at require (internal/modules/cjs/helpers.js:20:18)
    at bindings (C:\Users\Yang\electronMinimal\mods\node_modules\bindings\bindings.js:112:48)
    at Object.<anonymous> (C:\Users\Yang\electronMinimal\mods\index.js:1:188)
```
