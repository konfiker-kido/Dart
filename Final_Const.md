# Final & Const Key Concept

#### 1. final

- A final variable is initialized at runtime, meaning its value is assigned when the program is running.
- Once initialized, its value cannot be changed.
- Can be used both inside and outside a class.
- Memory is allocated only when the variable is accessed or assigned.

#### 2. const

- A const variable is initialized at compile time, meaning its value is determined when the program is compiled.
- A const variable must be a compile-time constant (fixed value).
- Cannot be used as an instance variable unless marked as static.

#### Code Explanation

##### 1. Main Function

```dart

final String name = "Maurya";
// name = "Akash"; // will throw error "can only be set once"

```
Here, `name` is declared as a final variable.
The `final` keyword ensures that name cannot be reassigned after its initial assignment.
Uncommenting the line `name = "Akash";` will throw a compilation error: "can only be set once."
```dart

const double e = 2.7;
// e is declared as a const variable with a compile-time constant value of 2.7.
// This means e is a constant whose value is determined at compile time and cannot be modified.

```

#### Example Code

```dart

void main() {
  
    
   // final - runtime, can reside inside a class 
  // if u have not initialised it, then memory will not be assigned to a final var
  final String name = "Maurya";
  // name = "Akash"; // will throw error "can only be set once"
  
  
  // const - compile time, can't reside inside a class
  
  const double e = 2.7;
  
  
}

class Person{
   final String name ="Akash"; 
   static const age =25;  // if we use static then we can access this var to another class 
}

class Another{
   
     int age=Person.age;
//       String name =Person.name; // can not access bcz name is not static 
}



```