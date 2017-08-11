### 5 manually
```js
function identify(context) {
	return context.name.toUpperCase();
}

function speak(context) {
	var greeting = "Hello, I'm " + identify( context );
	console.log( greeting );
}

var me = {
	name: "Jack"
};

var you = {
	name: "Nicolas"
};

identify( you ); // JACK
speak( me ); // Hello, I'm NICOLAS
```
