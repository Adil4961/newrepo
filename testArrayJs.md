### 1.Create an array with three elements and print out the second element.
```
let arr = [1, 2, 3];
let arrSlice = arr.slice(1, 2);
console.log(arrSlice);
```
### 2.Create an array with five elements and print out the length of the array.

```
let arr = [2, 4, 5, 76, 4];
let arrLength = arr.length;
console.log(arrLength);
```
### 3.Create an array with four elements and print out each element using a for loop.
```
let arr = [3, 4, 6, 8];
for (i = 0; i < arr.length; i++) {
  console.log(arr[i]);
}
```
### 4.Create an array with six elements and print out each element using a forEach loop.
```
let arr = [3, 4, 6, 8, 9, 4];
```
### 5.Create an array with three elements and add a fourth element to the end of the array.
```
let arr = [5, 6, 4];
arr.push(9);
console.log(arr);
```
###D 6.Create an array with four elements and remove the second element.
```
let arr = [3, 5, 7, 9];
arr.splice(1, 1);
console.log(arr);
```
## 7.Create an array with five elements and remove the last element.
```
let arr = [3, 4, 2, 5, 7];
arr.pop();
console.log(arr);
```
## 8.Create an array with three elements and check if the array includes a specific value.
```
let arr = [3, 8, 5];
if (arr.includes(7)) {
  console.log("yes");
} else {
  console.log("no");
}
```
## 9.Create an array with four elements and sort the array in ascending order.
```
let arr = [4, 7, 9, 3];
function ascending(a, b) {
  return a - b;
}
console.log(arr.sort(ascending));
```
## 10.Create an array with five elements and sort the array in descending order.
```
let arr = [4, 7, 9, 3];
function descending(a, b) {
  return b - a;
}
console.log(arr.sort(descending));
```
## 11.Create two arrays, concatenate them and print out the resulting array.
```
let arr = [2, 4, 56, 8, 45];
let arr1 = [4, 45, 6, 7];
let arrConcat = arr.concat(arr1);
console.log(arrConcat);
```
## 12.Create an array with three elements and convert it to a string.
```
let arr = [2, 4, 6];
let arrToString = arr.toString();
console.log(arrToString);
```
## 13.Create an array with four elements and reverse the order of the elements.
```
let arr = [3, 5, 6, 7];
arr.reverse();
console.log(arr);
```
## 14.Create an array with five elements and find the index of a specific value.
```
let arr = [3, 4, 5, 7, 9];
let arrIndex = arr.indexOf(7);
console.log(arrIndex);
```
## 15.Create an array with six elements and slice the array to create a new array with the first three elements.
```
let arr = [3, 4, 6, 7, 4, 3];
let a = arr.slice(0, 3);
let arr1 = a;
console.log(arr1);
```
## 16.Create an array with six elements and use the map method to double each element.
```
let arr = [2, 4, 56, 7, 8, 3];
function double(num) {
  return num * 2;
}
console.log(arr.map(double));
```
## 17.Create an array with four elements and use the while loop to calculate the sum of all elements.
```
let i = 0;
let arr = [3, 4, 56, 7];
let sum = 0;
while (i < arr.length) {
  sum = sum + arr[i];
  i++;
}
console.log(sum);
```
## 18.Create an array with five elements and use the filter method to return only the even numbers.
```
let arr = [3, 5, 7, 4, 2];
function even(num) {
  return num % 2 === 0;
}
console.log(arr.filter(even));
```
## 19.Create an array with three elements and use the join method to concatenate the elements with a dash (-) separator.
```
let arr = [3, 4, 6];
let arrJoin = arr.join("-");
console.log(arrJoin);
```
## 20.Create two arrays with three elements each and use the concat method to combine them into a new array.
```
let arr = [2, 3, 6];
let arr1 = [3, 5, 7];
let arrConcat = arr.concat(arr1);
console.log(arrConcat);
```
