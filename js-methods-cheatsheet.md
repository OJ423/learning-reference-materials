## Array Methods

#### 1. Iterating
- `forEach()`
  ```javascript
  let numbers = [1, 2, 3, 4];
  numbers.forEach((num) => console.log(num));
  ```

- `map()`
  ```javascript
  let numbers = [1, 2, 3, 4];
  let doubled = numbers.map((num) => num * 2);
  ```

- `filter()`
  ```javascript
  let numbers = [1, 2, 3, 4];
  let evenNumbers = numbers.filter((num) => num % 2 === 0);
  ```

- `reduce()`
  ```javascript
  let numbers = [1, 2, 3, 4];
  let sum = numbers.reduce((acc, num) => acc + num, 0);
  ```

- `every()`
  ```javascript
  let numbers = [2, 4, 6, 8];
  let allEven = numbers.every((num) => num % 2 === 0);
  ```

- `some()`
  ```javascript
  let numbers = [1, 3, 5, 7];
  let hasEven = numbers.some((num) => num % 2 === 0);
  ```

#### 2. Searching and Sorting
- `indexOf()`
  ```javascript
  let fruits = ["apple", "orange", "banana"];
  let index = fruits.indexOf("orange");
  ```

- `lastIndexOf()`
  ```javascript
  let fruits = ["apple", "orange", "banana", "orange"];
  let lastIndex = fruits.lastIndexOf("orange");
  ```

- `includes()`
  ```javascript
  let fruits = ["apple", "orange", "banana"];
  let hasBanana = fruits.includes("banana");
  ```

- `find()`
  ```javascript
  let numbers = [1, 2, 3, 4];
  let even = numbers.find((num) => num % 2 === 0);
  ```

- `findIndex()`
  ```javascript
  let numbers = [1, 2, 3, 4];
  let index = numbers.findIndex((num) => num % 2 === 0);
  ```

- `sort()`
  ```javascript
  let fruits = ["banana", "apple", "orange"];
  fruits.sort();
  ```

#### 3. Modifying
- `concat()`
  ```javascript
  let arr1 = [1, 2, 3];
  let arr2 = [4, 5, 6];
  let combined = arr1.concat(arr2);
  ```

- `splice()`
  ```javascript
  let numbers = [1, 2, 3, 4, 5];
  numbers.splice(2, 1);
  ```

- `slice()`
  ```javascript
  let numbers = [1, 2, 3, 4, 5];
  let sliced = numbers.slice(1, 4);
  ```

- `reverse()`
  ```javascript
  let numbers = [1, 2, 3, 4, 5];
  numbers.reverse();
  ```

- `fill()`
  ```javascript
  let numbers = [1, 2, 3, 4, 5];
  numbers.fill(0, 2, 4);
  ```

### String Methods

#### 1. Manipulation
- `concat()`
  ```javascript
  let str1 = "Hello";
  let str2 = "World";
  let greeting = str1.concat(", ", str2, "!");
  ```

- `split()`
  ```javascript
  let sentence = "This is a sample sentence.";
  let words = sentence.split(" ");
  ```

- `replace()`
  ```javascript
  let message = "Hello, Name!";
  let updatedMessage = message.replace("Name", "John");
  ```

- `substring()`
  ```javascript
  let text = "Hello, World!";
  let subString = text.substring(0, 5);
  ```

- `substr()`
  ```javascript
  let text = "Hello, World!";
  let subString = text.substr(7, 5);
  ```

- `trim()`
  ```javascript
  let spacedText = "   Trim me!   ";
  let trimmedText = spacedText.trim();
  ```

#### 2. Searching and Extracting
- `charAt()`
  ```javascript
  let text = "Hello";
  let firstChar = text.charAt(0);
  ```

- `indexOf()`
  ```javascript
  let sentence = "JavaScript is fun!";
  let index = sentence.indexOf("fun");
  ```

- `lastIndexOf()`
  ```javascript
  let sentence = "JavaScript is fun and JavaScript is cool!";
  let lastIndex = sentence.lastIndexOf("JavaScript");
  ```

- `startsWith()`
  ```javascript
  let text = "Hello, World!";
  let startsWithHello = text.startsWith("Hello");
  ```

- `endsWith()`
  ```javascript
  let text = "Hello, World!";
  let endsWithWorld = text.endsWith("World!");
  ```

- `slice()`
  ```javascript
  let text = "Hello, World!";
  let slicedText = text.slice(7);
  ```

#### 3. Case Conversion
- `toUpperCase()`
  ```javascript
  let text = "hello";
  let upperCaseText = text.toUpperCase();
  ```

- `toLowerCase()`
  ```javascript
  let text = "WORLD";
  let lowerCaseText = text.toLowerCase();
  ```

### Object Methods

#### 1. Iterating
- `Object.keys()`
  ```javascript
  let person = { name: "John", age: 30, city: "New York" };
  let keys = Object.keys(person);
  ```

- `Object.values()`
  ```javascript
  let person = { name: "John", age: 30, city: "New York" };
  let values = Object.values(person);
  ```

- `Object.entries()`
  ```javascript
  let person = { name: "John", age: 30, city: "New York" };
  let entries = Object.entries(person);
  ```

#### 2. Object Manipulation
- `Object.assign()`
  ```javascript
  let obj1 = { a: 1, b: 2 };
  let obj2 = { b: 3, c: 4 };
  let mergedObj = Object.assign({}, obj1, obj2);
  ```

- `Object.defineProperty()`
  ```javascript
  let person = {};
  Object.defineProperty(person, "name", {
    value: "John",
    writable: true,
    enumerable: true,
    configurable: true,
  });
  ```

- `Object.freeze()`
  ```javascript
  let person = { name: "John" };
  Object.freeze(person);
  ```

- `Object.seal()`
  ```javascript
  let person = { name:

 "John" };
  Object.seal(person);
  ```

- `Object.create()`
  ```javascript
  let person = Object.create(null);
  person.name = "John";
  ```

### Math Methods

- `Math.abs()`
  ```javascript
  let number = -42;
  let absoluteValue = Math.abs(number);
  ```

- `Math.ceil()`
  ```javascript
  let decimalNumber = 7.89;
  let roundedUp = Math.ceil(decimalNumber);
  ```

- `Math.floor()`
  ```javascript
  let decimalNumber = 7.89;
  let roundedDown = Math.floor(decimalNumber);
  ```

- `Math.round()`
  ```javascript
  let decimalNumber = 7.49;
  let rounded = Math.round(decimalNumber);
  ```

- `Math.max()`
  ```javascript
  let numbers = [1, 5, 2, 8, 3];
  let maxNumber = Math.max(...numbers);
  ```

- `Math.min()`
  ```javascript
  let numbers = [1, 5, 2, 8, 3];
  let minNumber = Math.min(...numbers);
  ```

- `Math.pow()`
  ```javascript
  let base = 2;
  let exponent = 3;
  let result = Math.pow(base, exponent);
  ```

- `Math.sqrt()`
  ```javascript
  let number = 25;
  let squareRoot = Math.sqrt(number);
  ```

- `Math.random()`
  ```javascript
  let randomNum = Math.random();
  ```

### Date Methods

- `new Date()`
  ```javascript
  let currentDate = new Date();
  ```

- `getDate()`
  ```javascript
  let currentDate = new Date();
  let day = currentDate.getDate();
  ```

- `getMonth()`
  ```javascript
  let currentDate = new Date();
  let month = currentDate.getMonth();
  ```

- `getFullYear()`
  ```javascript
  let currentDate = new Date();
  let year = currentDate.getFullYear();
  ```

- `getDay()`
  ```javascript
  let currentDate = new Date();
  let dayOfWeek = currentDate.getDay();
  ```

- `getHours()`
  ```javascript
  let currentDate = new Date();
  let hours = currentDate.getHours();
  ```

- `getMinutes()`
  ```javascript
  let currentDate = new Date();
  let minutes = currentDate.getMinutes();
  ```

- `getSeconds()`
  ```javascript
  let currentDate = new Date();
  let seconds = currentDate.getSeconds();
  ```

- `toISOString()`
  ```javascript
  let currentDate = new Date();
  let isoString = currentDate.toISOString();
  ```

- `toLocaleDateString()`
  ```javascript
  let currentDate = new Date();
  let localDate = currentDate.toLocaleDateString();
  ```

- `toLocaleTimeString()`
  ```javascript
  let currentDate = new Date();
  let localTime = currentDate.toLocaleTimeString();
  ```

### Regular Expression Methods

- `test()`
  ```javascript
  let pattern = /\d+/;
  let result = pattern.test("123");
  ```

- `exec()`
  ```javascript
  let pattern = /\d+/;
  let result = pattern.exec("The price is $123");
  ```

- `match()`
  ```javascript
  let pattern = /\d+/;
  let result = "The price is $123".match(pattern);
  ```

- `replace()`
  ```javascript
  let pattern = /\d+/;
  let result = "The price is $123".replace(pattern, "456");
  ```

- `search()`
  ```javascript
  let pattern = /\d+/;
  let position = "The price is $123".search(pattern);
  ```

- `split()`
  ```javascript
  let pattern = /\s+/;
  let result = "Hello World".split(pattern);
  ```
