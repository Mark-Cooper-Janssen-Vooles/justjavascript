From the course: 
https://justjavascript.com/


## The Javascript Universe

Recap:
- There are values, and then there’s code. We can think of values as different things “floating” in our JavaScript universe. They don’t exist inside our code, but we can refer to them from our code.
- There are two categories of values: there are Primitive Values, and then there are Objects and Functions. In total, there are nine separate types. Each type serves a specific purpose, but some are rarely used.
- Some values are lonely. For example, null is the only value of the Null type, and undefined is the only value of the Undefined type. As we will learn later, these two lonely values are quite the troublemakers!
- We can ask questions with expressions. Expressions exist in our code, so they are not values. Rather, JavaScript will answer our expressions with values. For example, the 2 + 2 expression is answered with the value 4.
- We can inspect the type of something by wrapping it in a typeof expression. For example, typeof(4) results in the string value "number".


#### Primitive Values 

- Undefined (undefined), used for unintentionally missing values.
- Null (null), used for intentionally missing values.
- Booleans (true and false), used for logical operations.
- Numbers (-100, 3.14, and others), used for math calculations.
- BigInts (uncommon and new), used for math on big numbers.
- Strings ("hello", "abracadabra", and others), used for text.
- Symbols (uncommon), used to perform rituals and hide secrets.


#### Objects and Functions

- Objects ({} and others), used to group related data and code. (Arrays are objects)
- Functions (x => x * 2 and others), used to refer to code.


#### Checking a type 

````js
console.log(typeof(2)); // "number"
console.log(typeof("hello")); // "string"
console.log(typeof(undefined)); // "undefined"
````