# Polymer2-Concept

*Please run update all submodules command after clone this repository.*

**Polymer 2 Source**

https://github.com/Polymer/polymer

**Polymer 2 - TypeScript definition files**

https://github.com/Soul-Master/Polymer2-typing

**Polymer 2 - Bundling demo**

https://github.com/Soul-Master/Polymer2-CLI-Demo

- `ES6` HTML Import

https://cdn.rawgit.com/Soul-Master/Polymer2-Concept/master/build/html-import-es6/

- `ES5` HTML Import

https://cdn.rawgit.com/Soul-Master/Polymer2-Concept/master/build/html-import-es5/

- `ES6` HTML Bundled

https://cdn.rawgit.com/Soul-Master/Polymer2-Concept/master/build/html-bundled-es6/

- `ES5` HTML Bundled

https://cdn.rawgit.com/Soul-Master/Polymer2-Concept/master/build/html-bundled-es5/

- `ES6` Pure

https://cdn.rawgit.com/Soul-Master/Polymer2-Pure-ES6/master/index.html

- `ES5` Pure

https://cdn.rawgit.com/Soul-Master/Polymer2-Pure-ES5/master/

**For ES5 browser, please manually define custom element after `webcomponentsready` event is fired.**

```
window.addEventListener('WebComponentsReady', function () {
   var TestElement = function TestElement() { ... };
   
   window.customElements.define(TestElement.is, TestElement);
});
```

*For IE with dev tool, it might raise exception.*
![capture](https://user-images.githubusercontent.com/442046/29449839-7e8634e2-8426-11e7-84f0-e640461f7060.PNG)
