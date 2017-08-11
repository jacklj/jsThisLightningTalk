### 13 explicit binding

```js
function foo() {
	console.log( this.a );
}

var obj = {
	a: 2
};

foo.call( obj ); // 2
```

- invoking foo with explicit binding by `foo.call(..)` allows us to force its `this` to be `obj`
