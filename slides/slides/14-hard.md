### 14 explicit 2 - hard binding

```js
function foo(something) {
	console.log( this.a, something );
	return this.a + something;
}

var obj = {
	a: 2
};

var bar = foo.bind( obj );

var b = bar( 3 ); // 2 3
console.log( b ); // 5
```

- `bind(..)` returns a new function that is hard-coded to call the original function with the `this` context set as you specified.
