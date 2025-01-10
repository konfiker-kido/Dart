###dart Code 
----

```dart

void main() {
  Set<String> cities = {"New York", "Paris", "Tokyo"};

  cities.add("London"); // Adds a new element.
  cities.addAll({"Berlin", "Rome"}); // Adds multiple elements.
  cities.remove("Paris"); // Removes an element.
  
  print(cities.contains("Tokyo")); // Checks if "Tokyo" is present: true
  print(cities); // {New York, Tokyo, London, Berlin, Rome}

  Set<String> europeanCities = {"Paris", "Berlin", "Rome"};
  print(cities.intersection(europeanCities)); // {Berlin, Rome}
  print(cities.union(europeanCities)); // {New York, Tokyo, London, Berlin, Rome, Paris}
}


```