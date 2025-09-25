
```javascript
const friends = ['Michael' , 'Steven' , 'Peter'];
console.log(friends);
const year = new Array(1991, 1994, 2008 , 2020);

console.log(friends[0]);//returns first element of array
console.log(friends.length);//returns length of array

console.log(friends.length);
friends[2] = 'Jay';//replace value at index 2
const firstName = 'Jonas';
const jonas = [firstName, 'Schmedmann',2037-1991,'teacher',friends];
```

```javascript
const newLength = friends.push('Jay'); //returns length of array without calculating
friennds.unshift('John'); //add element at first place
friends.pop() //remove the last element of the array
friends.shift();//remove first element of the array
```

```javascript
console.log(friends.insertOf('Steven'));
console.log(friends.insertOf('Bob'));

console.log(friends.include('Steven'));//check if the element exist in array
```