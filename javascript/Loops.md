
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
	console.log(jonas[i]);
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

//continue
for(let i = 0 ;i < jonas.length ; i++){
	if(typeof jonas[i] !== 'string') continue;
	console.log(typeof jonas[i])
}

//break
for(let i = 0 ;i < n ; i++){
	if(typeof jonas[i] == 'number')break;
	console.log(jonas[i]);
}
```

```javascript
//loop backward
//4,3,2,1,0
for(int i = 4 ; i >= 0 ; i--){
	console.log(i,jonas[i]);
}

//nested loop
for(int exercise = 1 ; exercise <= 3 ; exercise++){
	console.log(`starting exercise ${exercise}`);
	for(int rep = 1 ; rep < 6 ; rep++){
		console.log(`Exercise ${exercise}: Lifting weight repitition ${rep}`);
	}
}
```

```javascript
//while loop
let rep = 1;//initialization
while(rep <= 10){ //condition
	console.log(rep);
	rep++; //increment;
}

```