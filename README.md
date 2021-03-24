# MyLibrary
This is a library website


```
function calculatePrice(price, quantity){
	const total = price * quantity;
	console.log(`${quantity} items cost you ${total} bucks`);
}

calculatePrice(10, 3);
```

```
calculatePrice(undefined, null);
```

```
function calculatePrice(price, quantity){
	price = price ?? 2;
	quantity = quantity ?? 1;
	const total = price * quantity;
	console.log(`${quantity} items cost you ${total} bucks`);
}
calculatePrice(undefined, '');
```

```
console.log(`%c This is red text`, ‘color: red’);
```

```
function calculatePrice(price, quantity){
	price = price ?? 2;
	quantity = quantity ?? 1;
	const total = price * quantity;
	console.log(`%c ${quantity} items cost you ${total} bucks`, 'color: green');
}
calculatePrice(30, 2);
```

```
const name = 'Minal';
const city= 'Chicago';
const details = {
    name: name,
    city: city
}
console.log(details);
```

```
const name = 'Minal';
const city= 'Chicago';
const details = {
    name,
    city
}
console.log(details);
```



