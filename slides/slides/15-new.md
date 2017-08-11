### 15 new binding

```js
function foo(a) {
	this.a = a;
}

var bar = new foo( 2 );
console.log( bar.a ); // 2
```

- `new` is not class based OOP
