## Use Package locally

To use a package locally you have to:

### 1
Use `npm link`  on the root of the project you want to make public locally.


### 2 
Make `npm link <name-of-the-published-package>` on the root of the project that's going to use your package.

### 3 Execute
Just do the `node index.js` and be happy.

OBS: the linked package is going to be in the `node_modules` folder.
