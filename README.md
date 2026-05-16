# jscpp.js
A package to run C++ in JavaScript.

For example:
```js
function include(...names) {
const env = {};

  for (const name of names) {
    if (libs[name]) {
      Object.assign(env, libs[name]);
    } else {
      throw new Error("Library not found: " + name);
    }
  }
const intmain = "";
function StdCout(...args) {
console.log(...args)
}

  return env;
}
}
include(iostream)
intmain.StdCout("Hello");

rtn.number;
```
