# ng2 Dynamic Forms

ng2 Dynamic Forms is a form automation library built upon the official Angular 2
[dynamic form cookbook](https://angular.io/docs/ts/latest/cookbook/dynamic-form.html).
It simplifies all the hard, troublesome work of handcrafted form building to intuitive metadata declaration.
Moreover it offers a flexible system of dynamic ui components with out of the box support for
**Angular 2 Material** and **Bootstrap**.

##Getting Started

1. Install the **core** package:
```
npm install @ng2-dynamic-forms/core --save
```
2. Choose your ui library, e.g. Angular 2 Material, and install the corresponding package:
```
npm install @ng2-dynamic-forms/ui-material --save
```
3. When using **SystemJS**, update your configuration file:
```
    var map = {

        // ...here goes all the rest

        "@ng2-dynamic-forms": "node_modules/@ng2-dynamic-forms"

    };

    var ng2DynamicFormsPackageNames = [

        "@ng2-dynamic-forms/core",
        "@ng2-dynamic-forms/ui-material"
    ];

    ng2DynamicFormsPackageNames.forEach(function (packageName) {

        packages[packageName] = {
            main: "index.js",
            defaultExtension: "js"
        };
    });
```
4. Define your dynamic form model:
```
// TODO
```
5. Plug in your ui component:
```
// TODO
```