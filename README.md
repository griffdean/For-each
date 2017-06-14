# For-each

Foreach loops are pretty simple loops that evaluates each value individually. It is used on a collection, not an index, and returns the values in order. It is useful in traversing items in a collection or an array.

For example:
string[] pets = {"dog", "cat", "bird"};
foreach(string value in pets){
  print(value);
}
//outputs dog cat bird

string[] numbers = {"1", "9", "4"};
foreach(string value in numbers){
  print(value);
}
//outputs 1 9 4
**you can also sort the numbers as well

string[] name = {"Bill","Bob", "Jack"};
foreach(string value in name){
  print("Hello " + name);
}
//outputs Hello Bill, Hello Bob, Hello Jack

int[] num = {2,3,4,5};
foreach(int value in num){
  print(num);
}
//outputs 2, 3, 4, 5
