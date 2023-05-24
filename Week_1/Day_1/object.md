# Objects

## Notes

---

### Primitive Types
* Boolean : true or false
* Null : explicit absence of value / empty value
* Undefined : unassigned value to variable
* Number : 5, 6 or 0
* BigInt : bigger than larger number we can store
* String : "This is a string"
* Symbol : Symbol('symbol')


### Objects
* With Objects we use keys to access values
* ``` const myObj {} ```
* We have two ways to access key + values
  * ``` object['key with space']```
  * ``` object.key ```
* The difference between the two is that [] can take a key with spaces and can be used in a ```for..in``` and ```for..of``` loop
* ```const``` on an object means we can change the data inside the object itself, not the fact that it is an object or changing the primitive type.

### Functions inside of Objects
* Typically called a method
``` 
const myObj = {
  firstName : 'Lorem',
  lastName : 'Ipsum',
  array : ['a','b','c'],
  sayHello : function(){
    console.log(`hello ${this.firstName}`);
  },
  myObj2 : {
    test : 'test'
  }
}
``` 
* We can call this method by ``` myObj.sayHello(); ```
* When working with a method/function inside of an object we can use ``` this ``` to access the values of the object its called in

* We can iterate through objects with 
```
for (const key in myObj) {
  console.log(key);
  console.log(myObj[key]);
}
```
```
for (const key in myObj){
  if (Array.isArray(myObj[key])){
    for (const element of myObj[key]){
      console.log(element);
    }
  }
}
```
* to iterate through array inside object
```
for (const element of myObj.array) {
  console.log(element);
}
```
* to iterate through object inside object
```
for (const key in myObj.myObj2) {
  console.log(key);
  console.log(myObj.myObj2[key]);
}
```

