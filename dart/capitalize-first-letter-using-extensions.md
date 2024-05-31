Hello ! We all had a chance once working in a tech industry related to very small feature called Capitalize the first letter of String.
Here how you can do that 

**DART**
In dart programming language you can capitalize the first letter of the string using :
```dart
 String text = "hello";
  String capitalizeText = text[0].toUpperCase() + text.substring(1).toLowerCase();
  print(capitalizeText);  //This will print Hello
```

**Using Extension**
```dart
 void main() {
  String test = "flutterdevs";
  print(test.capitalize()); //This will print Flutterdevs
}

extension CurrentString on String {
  String capitalize() {
    return "${this[0].toUpperCase()}${this.substring(1).toLowerCase()}";
  }
}

```
