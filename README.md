# JavaScript 6

## Mencari 20 Built-in Method

### Array: length
```javascript
const carBrand = ['Toyota', 'Daihatsu', 'Suzuki', 'Ford', 'Mazda'];
console.log(carBrand.length);
```
Output: 5

### Array: concat
```javascript
const provinsi1 = ['Jawa Barat', 'Jawa Tengah', 'Jawa Timur'];
const provinsi2 = ['Kalimantan Barat', 'Kalimantan Tengah', 'Kalimantan Timur'];
const provinsi3 = provinsi1.concat(provinsi2);
console.log(provinsi3);
```
Output: ['Jawa Barat','Jawa Tengah','Jawa Timur','Kalimantan Barat','Kalimantan Tengah','Kalimantan Timur']

### Array: filter
```javascript
const planet = ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptune'];
const letterLessThan6 = planet.filter((word) => word.length < 6);
console.log(letterLessThan6);
```
Output: ['Venus','Earth','Mars']

### Array: sort
```javascript
const profession = ['Plumber', 'Architect', 'Programmer', 'Welder'];
profession.sort();
console.log(profession);
```
Output: ['Architect','Plumber','Programmer','Welder']

### Array: push
```javascript
const vehicle = ["bike", "car", "helicopter"];
const pushPlane = vehicle.push("plane");
console.log(pushPlane(vehicle));
```
Output: ['bike','car','helicopter','plane']

### String: toUpperCase
```javascript
const name = 'aldi dwi ardyansah';
console.log(name.toUpperCase());
```
Output: 'ALDI DWI ARDYANSAH'

### String: toLowerCase
```javascript
const greeting = 'HELLO WORLD';
console.log(greeting.toLowerCase());
```
Output: 'hello world'

### String: slice
```javascript
const language = 'JavaScript';
console.log(language.slice(0, 4));
```
Output: 'Java'

### String: includes
```javascript
const sentence = 'I am learning JavaScript';
console.log(sentence.includes('JavaScript'));
```
Output: true

### String: replace
```javascript
const message = 'Hello World';
console.log(message.replace('World', 'JavaScript'));
```
Output: 'Hello JavaScript'

### Number: toFixed
```javascript
const price = 150.567;
console.log(price.toFixed(2));
```
Output: '150.57'

### Number: toString
```javascript
const age = 25;
console.log(age.toString());
```
Output: '25'

### Number: toPrecision
```javascript
const value = 123.456;
console.log(value.toPrecision(4));
```
Output: '123.5'

### Number: isInteger
```javascript
console.log(Number.isInteger(10));
```
Output: true

### Number: isFinite
```javascript
console.log(Number.isFinite(100));
```
Output: true

### Object: keys
```javascript
const person = { name: 'Aldi', age: 30, profession: 'Teacher' };
console.log(Object.keys(person));
```
Output: ['name','age','profession']

### Object: values
```javascript
const student = { name: 'Budi', age: 20 };
console.log(Object.values(student));
```
Output: ['Budi',20]

### Object: entries
```javascript
const car = { brand: 'Toyota', year: 2024 };
console.log(Object.entries(car));
```
Output: [['brand','Toyota'],['year',2024]]

### Object: assign
```javascript
const original = { color: 'red' };
const additional = { size: 'large' };
const combined = Object.assign({}, original, additional);
console.log(combined);
```
Output: { color: 'red', size: 'large' }

### Object: freeze
```javascript
const settings = Object.freeze({ mode: 'dark' });
console.log(settings);
```
Output: { mode: 'dark' }

## Mencari 5 Built-in Function

### parseInt()
```javascript
console.log(parseInt("42.58"));
console.log(parseInt("10px"));
```
Output: 42
Output: 10

### parseFloat()
```javascript
console.log(parseFloat("300.5 km/h"));
console.log(parseFloat("120.75 m"));
```
Output: 300.5
Output: 120.75

### setTimeout()
```javascript
setTimeout(() => {
    console.log('Hello World!');
}, 5000);
```
Tulisan 'Hello World!' akan muncul setelah sekitar 5 detik

### setInterval()
```javascript
setInterval(() => {
    console.log('Console log ini akan muncul setiap 3 detik');
}, 3000);
```
Console log ini akan muncul berulang setiap sekitar 3 detik

### eval()
```javascript
console.log(eval('2 + 2'));
```
Output: 4