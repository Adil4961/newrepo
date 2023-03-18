### 1. What is an object in JavaScript?

```
- Objecet is an non primitive data type.
- Objects are created with curly brashes
- Keys(Variable) and values are define in curly brashes
- Functions and array's are also can define in a Object
Example-
let details = {
  name: "Adil khan",
  mobileNumber: 8426064961,
  age: 21,
  address: "Jhotwara jaipur",
  function: function test() {},
};
console.log(
  "My name is " + details.name + " My mobile number is " + details.mobileNumber
);
```

### 2. What is the difference between dot notation and bracket notation for accessing object properties?
```
-Dot annoation = Dot annoation is like a path for object,
-With Dot annoation uses between Object Name and key Name
-Dot Annoation only take keys after " . "
Example-
let address = {
  area: "jhotwara ",
  district: "Jaipur ",
  state: "Rajsthan",
};
console.log("My address is " + address.area + address.district + address.state);

-Bracket Annoation = bracket annoation is also working as same dot annoation
-Bracket annoation is also like a path for object
-Bracket annoation syntax is [] square brackets and in string
Example -
let bankDetails = {
  accountNumber: 61350437752,
  accountHolderName: " Adil khan ",
  cifNumber: 656467547653,
  ifscCode: " SBIN0032425",
};
console.log(
  "My account details is " +
    bankDetails["accountNumber"] +
    bankDetails["accountHolderName"] +
    bankDetails["cifNumber"] +
    bankDetails["ifscCode"]
);
```

### 3 . How do you loop through the properties of an object in JavaScript?
```
let subjects = {
  english: 89,
  hindi: 67,
  math: 65,
};

for (let key in subjects) {
  console.log(key + ": " + subjects[key]);
}
```

### 4 . What is the difference between an object and an array in JavaScript?
```
- Array and Object both are using for store value's and data
for creating an array use [] square brackets
and for creating object use {} and key(variable) ,value's
array has functions to perform different type of tasks
object also have method and functions to perform specific tasks
```

### 5 . Write a JavaScript function to convert an object into a list of `[key, value]` pairs.

```
let object = {
  name: "adil",
  address: "jaipur",
  mobile: 8899743894,
};
for (let key in object) {
  console.log(key + ": " + object[key]);
}
```

### 6 . Write a function that takes an object representing a person and returns their full name.

```
let person = {
  firstName: "adil",
  lastName: "khan",
};
console.log(person.firstName + " " + person.lastName);
```

### 7 . Create an Object with your personal details. Now print all the keys of the object in ascending order.
```
let details = {
  name: "Adil khan",
  mobileNumber: 8426064961,
  age: 21,
  address: "Jhotwara jaipur",
};
let keys = Object.keys(details);
console.log(keys.sort());
```

### 8 . Create an Object with your personal details. Now filter out all the values of the object and show them in descending order.

```
let details = {
  name: "Adil khan",
  mobileNumber: 8426064961,
  age: 21,
  address: "Jhotwara jaipur",
};
let keys = Object.values(details);
keys.sort(function (val, val1) {
  return val1 - val;
});
console.log(keys);
```
