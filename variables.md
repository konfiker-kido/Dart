# Data Types

- `"Akash"` ,`'a'` - string
- `21` = `int`, `5.53` = `double`
- `true`, `false` = `bool`
- `["apple", ""mango]` = List<String>
-  `[3, 7, 21]` = List<int>
- `{
    "name" :"Akash",
     "age": 25
    }`   = map


 ```dart
    void main() {
  
    String name="Maurya";
    bool male =true;
    int age =21;
    List<String> fruits =["Mango","Grapes"];
    List<dynamic> arr =["Maurya",21];
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