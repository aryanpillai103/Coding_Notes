
```javascript
//for loop
for(let rep = 1 ; rep <= 10 ; rep++){
	console.log(`Lifting weight repetition ${rep}`);
}
```

```javascript
const jonas = [
	'Jonas',
	'Schemdtmann',
	46,
	'teacher',
	['Michael','Peter','Steven']
];

//hardcoded
for(let i = 0 ; i < 5 ; i++){
	console.log(jonas[i]);
}

//dynamically typed
for(let i = 0 ; i < jonas.length ; i++){
}

//array of types of array above
const types = [];
for(int i = 0 ; i < jonas.length ; i++){
	types[i] = typeof jonas[i];
	//types.push(typeof jonas[i]); more cleaner version
}
console.log(types);

const years = [1991,2007,2009,2020];
const ages = [];
for(let i = 0 ; i < years.length ; i++){
	ages.push(2037 - years[i]);
}
console.log(ages);
```
