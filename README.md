# JavaScript 6

## Mencari 20 built-in method

### Array: length
```
const carBrand = ['Toyota', 'Daihatsu', 'Suzuki', 'Ford', 'Mazda'];
console.log(carBrand.length);
```
Output: 5

### Array: concat
```
const provinsi1 = ['Java Barat', 'Jawa Tengah', 'Jawa Timur'];
const provinsi2 = ['Kalimantan Barat', 'Kalimantan Tengah', 'Kalimantan Timur'];
const provinsi3 = provinsi1.concat(provinsi2);
console.log(provinsi3)
```
Output: ['Java Barat','Jawa Tengah','Jawa Timur','Kalimantan Barat','Kalimantan Tengah','Kalimantan Timur']

### Array: filter
```
const planet = ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptune'];
const letterLessThan6 = planet.filter((word) => word.length < 6);
console.log(letterLessThan6);
```
Output: ['Venus','Earth','Mars']

### Array: sort
```
const profession = ['Plumber', 'Architec', 'Programmer', 'Welder'];
profession.sort();
console.log(profession);
```
Output: ['Architec','Plumber','Programmer','Welder']

### Array: push
```
const vehicle = ['bike','car','helicopter'];
const pushPlane = vehicle.push('plane');
console.log(vehicle);
```
Output: ['bike','car','helicopter','plane']

## Mencari 5 built-in function

### parseInt()
```
parseInt("42.58"); 
parseInt("10px");
```
Mengembalikan nilai integer 42
Mengembalikan nilai integer 10

### parseFloat()
```
parseFloat("300.5 km/h");
parseFloat("120.75 m");
```
Mengembalikan nilai float 300.5
Mengembalikan nilai float 120.75

### setTimeout()
```
setTimeout(() => {
    console.log('Hello World!');
}, 5000);
```
Tulisan 'Hello World!' akan muncul dalam 5 detik

### setInterval()
```
setInterval(() => {
    console.log('Console log ini akan muncul setiap 3 detik');
}, 3000);
```
Console log ini akan muncul setiap 3 detik

### eval()
```
eval('2 + 2');
```
Mengembalikan nilai integer 4