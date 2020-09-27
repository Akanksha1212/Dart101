# Dart101
<img src="https://raw.githubusercontent.com/kevmoo/dart_side/master/Dash%20Dart%20PNG%20%20-%20white.png" width=900>  

Open https://www.dartpad.dev/ and run all these snippets and experiement with them to undertand things more clearly  
## Hello World!:earth_asia:
```
void main(){
  print("Hello World!");
}
```

## Identifiers  
* First character must be an alphabet(uppercase or lowercase) or an underscore( _ )  
* Can not start with a digit.  
* No special character allowed except underscore. 2 succesive underscores not allowed.
* Keywords like print, main etc can not be used as an identifier.
* Dart is case sensitive so Abc and abc are not same.  

### Comments 
```
// single line comment
/* multiline
  comment */
/// Documentation comment
///* multiline documentation
  comment *///
  
void main(){
  int n=42;
  print("${n} is the answer to life, Universe and everything"); // We use ${expression} for String Interpolation.
}
```

## Data Types  
```
void main(){

   // Integer and Double
   int n = 10;
   double m = 10.5;
   
   // Strings
   var s = "Hi";
   String s1 = "Bye";
   
   //Boolean
   bool isValid = true;
   
   // In dart instead of array we have list
   var l = {1,2,3};
   var list = {1,'a',4,true}; // we can have all elements of all data type if list is of var type
   int l1 = {1,2,'a'}; // This will give us an error;
   print(list);
   
   // Maps are used to represent a set of values as key-value pairs
   var week = { 1:'Mon',2:'Tue',3:'Wed',4:'Thurs',5:'Fri',6:'Sat',7:'Sun'};
   print(week);
   
   //Rune is an integer representing a unicode code point.
   var heart = '\u2665';
   print("I ${heart} Flutter");
   
   // Dynamic is used when type of a variable is not explicitly specified
   dynamic n5;
}
```

## Operators  

```
void main(){
  
  //Assignment operators
  int n = 4;
  int n+=10; // Can be simplified as n = n+10
  // Similarly -=(subtract and assign),*=(multiply and assign),/=(divide and assign), %=(mod and assign) are used.
  // There are some other operators which can be used along with =
  // <<=(left shift an dassign) >>=(right shift and assign) &=(bitwise AND and assign) |=(bitwise OR and assign) ^=(bitwise XOR and assign)
  
  // Arithmetic Operators
  // +, -,*, / same as other languages
  //Unary minus used to reverse the sign of an expression like -(a-b)
  // 
  
  
  


}
```
