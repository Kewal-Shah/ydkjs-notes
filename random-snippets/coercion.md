1. Double equality operator allows coercion while comparison. 
```js
	0 == false	// Output: true
	1 == true	// Output: true
```
	
In the above example, JS engine coerces false as '0' and true as '1' before comparison and hence returns true as result. Hence, general assumption about double equality operator of comparing just values without bothering about the date type is not completely true. The main reason behind that is coercion.


2. Triple equality operator does not allow coercion before comparsion. Hence, below results.
```
	0 === false	// Output: false
	1 === true	// Output: false
```

No coercion is being performed before comparison.
