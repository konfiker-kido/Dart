# Core Data Types
### 1. Numbers
- `int`: Integer values `(e.g., 1, 42, -7)`
-  `double`: Floating-point values `(e.g., 3.14, -0.5)`

##### Key Functions:

- `isEven`, `isOdd`: Check if an integer is even or odd.
- `toString()`: Convert a number to a string.
- `toInt()`, `toDouble()`: Convert between int and double.

----

### 2. Strings
Sequence of characters, enclosed in single or double quotes (e.g., `'Hello'`, `"World"`).

##### Key Functions:

- `toUpperCase()`, `toLowerCase()`: Change case.
- `substring(start, [end])`: Extract a portion of the string.
- `split(delimiter)`: Split into a list based on a delimiter.
- `contains(pattern)`: Check if a string contains a pattern.
- `trim()`: Remove whitespace from the beginning and end.

----

### 3. Booleans
   
`true` or `false`.

### Key Functions:

- Used for logical operations and conditions.
**Example:** `!isTrue, &&, ||`

----

### 4. Lists
   
Ordered collection of items (e.g., `[1, 2, 3]`).

##### Key Functions:

- `add(value)`: Add an element to the list.
- `remove(value)`: Remove an element from the list.
-`contains(element)`: Check if an element exists.
- `map(callback)`: Transform elements using a callback.


----

### 5. Maps

Key-value pairs (e.g., `{'name': 'John', 'age': 25}`).

##### Key Functions:

- `addAll(map)`: Add multiple key-value pairs.
- `remove(key)`: Remove a key-value pair.
- `keys, values`: Get all keys or values.
- `containsKey(key)`, `containsValue(value)`: Check for keys/values.


----

### 6. Sets

Unordered collection of unique items (e.g., `{1, 2, 3}`).

#####  Key Functions:

- `add(value)`: Add an element.
- `remove(value)`: Remove an element.
- `contains(element)`: Check for an element.
- `union(otherSet)`, `intersection(otherSet)`: Perform set operations.

----

### 7. Null

Represented by `null`.

----

Additional Features

Dynamic Typing: Use dynamic to allow any type.

`List<dynamic> arr =["Maurya",21]; // can store variable of any Data types`

```dart

dynamic variable = 42;
variable = "Now a string";
```
### Type Checking and Conversion

`is`, `as`: Type-checking and casting.

```dart

if (x is String) print(x.length);

```
---
 ##### Dart Example Code 
 ```dart
    void main() {
  
            String name="Maurya";
            bool male =true;
            int age =21;
            List<String> fruits =["Mango","Grapes"];
            List<dynamic> arr =["Maurya",21]; // can store variable of any Data types
            Map<String,dynamic> profile = {
              "name":name,
              "age":age,
              "male":male,
              "fruits":fruits
            };
          
          print(profile);
          print(arr);
  
}
    
 ```
##### OUTPUT:
`
{name: Maurya, age: 21, male: true, fruits: [Mango, Grapes]}
[Maurya, 21]
`



