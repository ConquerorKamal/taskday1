Objects and its internal representation of Javascript.

In JavaScript, An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects).
In order for us to learn this concept of object we can throw in some practical examples.



 const person = {
  name: "kamal" ,
  age: 23,
  isStudent: true,
  sayHello: function() {
    console.log('Hello!');
  },
};

1) Object Literals:

   The most common way to create objects is using object literals:
   In the above code, person is an object with properties like name, age, isStudent, and a method sayHello.
 
2) Accessing Object Properties: 

   You can access object properties using dot notation or square bracket notation.

   console.log(person.name) ------------ dot notation.
   console.log(person["age"]) ---------- Square bracket notation.

3) Adding and Modifying Properties:
    
   person.city = 'Bangalore' ---------adding properties.
    person.age = 26 ------------------modifying properties.

4) Object Methods: 

   Objects can contain functions as properties, which are often referred to as methods
   in the above code, you can see there is a function used to say hello.

5) object prototypes:
   
   In JavaScript, prototype-based inheritance is a key mechanism for object-oriented programming.Each object in JavaScript has an associated prototype, and this forms    a chain of objects linked together.The prototype chain is used for property and method lookup.
   for the above given code, we can find its prototype by:
   
   console.log(person.__proto__); ---> which gives the output as {} .

6) Properties:

  Objects in JavaScript consist of properties, where each property has a key and a corresponding value. The key is always a string or a symbol, and the value can be   any JavaScript data type, including other objects.

7) [[Get]] and [[Set]]:

   The internal methods [[Get]] and [[Set]] are used when retrieving and setting values on an object, respectively. These methods are part of the internal mechanism       that allows you to access object properties using dot notation or square bracket notation.


Understanding the internal representation of objects is not always necessary for everyday JavaScript programming, but having a basic understanding can help you write more efficient and performant code. The details mentioned above may vary between different JavaScript engines, as they are implementation details.
