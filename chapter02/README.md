# Initial setup

```
ng new auction
```

2018-01-24: I also had to install `angular-devkit` manually:

```
npm install @angular-devkit/core --save-dev
```

(see https://github.com/angular/devkit/issues/256)

Otherwhise the following error showed up when trying to create a new component using `ng generate component foo`:

```
>ng generate component product-item
module.js:557
    throw err;
    ^

Error: Cannot find module '@angular-devkit/core'
    at Function.Module._resolveFilename (module.js:555:15)
    at Function.Module._load (module.js:482:25)
    at Module.require (module.js:604:17)
    at require (internal/module.js:11:18)
    at Object.<anonymous> (C:\projects\_playground\angular_playground\book_angular2\chapter02\auction\node_modules\@angular-devkit\schematics\src\tree\virtual.js:10:
16)
    at Module._compile (module.js:660:30)
    at Object.Module._extensions..js (module.js:671:10)
    at Module.load (module.js:573:32)
    at tryModuleLoad (module.js:513:12)
    at Function.Module._load (module.js:505:3)
```
