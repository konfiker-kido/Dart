### dart Code 
----

```dart

void main() {
  String message = "  Hello Dart  ";

  print(message.trim()); // Removes leading and trailing whitespaces.
  print(message.toUpperCase()); // Converts to uppercase: "HELLO DART"
  print(message.toLowerCase()); // Converts to lowercase: "hello dart"
  print(message.contains("Dart")); // Checks if "Dart" is present: true
  print(message.replaceAll("Hello", "Hi")); // Replaces all occurrences: "  Hi Dart  "
  print(message.substring(2, 7)); // Extracts substring: "Hello"
  
  List<String> words = message.split(" "); // Splits the string into a list.
  print(words); // [ '', '', 'Hello', 'Dart', '' ]
}

```
