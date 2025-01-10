### dart Code 
----

```dart

void main() {
  List<int> numbers = [10, 20, 30, 40];

  numbers.add(50); // Adds an element.
  numbers.addAll([60, 70]); // Adds multiple elements.
  numbers.remove(30); // Removes the element 30.
  numbers.removeAt(0); // Removes the element at index 0.
  numbers.sort(); // Sorts the list in ascending order.
  
  print(numbers); // [20, 40, 50, 60, 70]
  
  bool contains30 = numbers.contains(30); // Checks if 30 is present.
  print(contains30); // false
  
  List<int> evenNumbers = numbers.where((n) => n % 2 == 0).toList(); 
  print(evenNumbers); // [20, 40, 60, 70]
}



```