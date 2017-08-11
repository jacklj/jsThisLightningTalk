### 11 default binding

```js
function foo() {
	console.log( this.a );
}

var a = 2;

foo(); // 2
```

- variables declared in the global scope are synonymous with global-object
properties of the same name
- default binding - `this` points at the global object
