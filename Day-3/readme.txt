Day 3: Arrays and Objects

Topic 1: Working with Arrays
- Creating arrays: Learn how to create arrays in JavaScript and initialize them with values.
  - Example:
    ```javascript
    let numbers = [1, 2, 3, 4, 5];
    ```

- Accessing array elements: Understand how to access individual elements in an array using their indices.
  - Example:
    ```javascript
    console.log(numbers[0]); // Output: 1
    ```

- Modifying array elements: Explore techniques to modify array elements by assigning new values.
  - Example:
    ```javascript
    numbers[2] = 10;
    console.log(numbers); // Output: [1, 2, 10, 4, 5]
    ```

- Array length: Discover how to determine the length of an array using the `length` property.
  - Example:
    ```javascript
    console.log(numbers.length); // Output: 5
    ```

- Array methods: Learn about various useful array methods like `push`, `pop`, `shift`, `unshift`, `splice`, etc., and their applications.
  - Example:
    ```javascript
    numbers.push(6); // Adds 6 to the end of the array
    numbers.pop(); // Removes the last element from the array
    ```

- Looping through arrays: Practice looping through arrays using `for` loops and the `forEach` method.
  - Example using `for` loop:
    ```javascript
    for (let i = 0; i < numbers.length; i++) {
      console.log(numbers[i]);
    }
    ```

  - Example using `forEach` method:
    ```javascript
    numbers.forEach(function(num) {
      console.log(num);
    });
    ```

Topic 2: Introduction to Objects
- Creating objects: Understand how to create objects in JavaScript and define their properties and values.
  - Example:
    ```javascript
    let person = {
      name: "John",
      age: 25,
      profession: "Developer"
    };
    ```

- Accessing and modifying object properties: Learn how to access and modify object properties using dot notation and bracket notation.
  - Example:
    ```javascript
    console.log(person.name); // Output: "John"
    person.age = 30;
    ```

- Object methods: Explore how to add methods to objects and invoke them.
  - Example:
    ```javascript
    let person = {
      name: "John",
      sayHello: function() {
        console.log("Hello, " + this.name + "!");
      }
    };

    person.sayHello(); // Output: "Hello, John!"
    ```

- Object literals vs. object constructors: Understand the differences between object literals and object constructors, and when to use each approach.

Topic 3: JSON (JavaScript Object Notation)
- Overview of JSON format: Learn about the JSON format and its structure.
  - Example:
    ```json
    {
      "name": "John",
      "age": 25,
      "profession": "Developer"
    }
    ```

- Converting JavaScript objects to JSON: Learn how to convert JavaScript objects to JSON using the `JSON.stringify()` method.
  - Example:
    ```javascript
    let person = {
      name: "John",
      age: 25,
      profession: "Developer"
    };

    let json = JSON.stringify(person);
    ```

- Parsing JSON data: Understand how to parse JSON data back into JavaScript objects using the `JSON.parse()` method.
  - Example:
    ```javascript
    let json = '{"name":"John","age":25,"profession":"Developer"}

    Certainly! Here's the continuation of Day 3 content:

    let person = JSON.parse(json);
    console.log(person.name); // Output: "John"

Examples and Problem Brainstorming:

1. Example: Array Sorting
   - Explain how to sort an array of numbers in ascending or descending order using the `sort()` method.
   - Provide an example demonstrating the sorting process.
   - Encourage students to try sorting arrays with different data types or custom sorting criteria.

2. Example: Object Iteration
   - Demonstrate how to iterate over an object and access its properties using a `for...in` loop.
   - Show an example where the loop iterates over an object and logs each property and its value.

3. Problem Brainstorming: Shopping Cart
   - Present a problem scenario where students need to create a shopping cart using arrays and objects.
   - Define the required functionalities such as adding items, removing items, calculating total price, etc.
   - Encourage students to design a solution using arrays to store the items and objects to represent each item.
   - Guide them through the process step by step, highlighting the usage of array and object methods.

