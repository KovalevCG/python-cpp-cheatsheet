## Python/C++ Sintax Cheat Sheet

<!-------------------------------------------------------- COMMENTS -------------------------------------------------------------->
### Comments
```C++
// C++

// This is a comment

/* This is a
multi-line comment */
```
```Python
# Python

# This is a comment

# This is a
# multi-line comment
```

<!-------------------------------------------------------- VARIABLES -------------------------------------------------------------->
### Variables
```C++
// C++
int age = 18;
int a[10];
```
```Python
# Python
age = 18
a = []
```
<!--
|  C++ |  Python |
| ------------ | ------------ |
| int age = 18; | age = 18 |
|int a[10];  | a = [] |
-->

<!-------------------------------------------------------- IF ELSE -------------------------------------------------------------->
### If Statement
```C++
// C++

if (a < 10) {
  cout << "a < 10" << endl;
}
else if (a == 10){
  cout << "a = 10" << endl;
}
else {
  cout << "a > 10" << endl;
}
```
```Python
# Python

if a < 10:
    print("a < 10")
elif a == 10:
    print("a = 10")
else:
    print("a > 10")
```

<!-------------------------------------------------------- TERNARY -------------------------------------------------------------->
### Ternary operator
```C++
// C++
string result = (time < 18) ? "Good day." : "Good evening.";
```
```Python
# Python
result = "Good day." if time < 18 else "Good evening."
```

<!-------------------------------------------------------- SWITCH -------------------------------------------------------------->
### Switch statement
```C++
// C++

switch(day){
  case 6:
    cout << "Today is Saturday";
    break;
  case 7:
    cout << "Today is Sunday";
    break;
  default:
    cout << "Looking forward to the Weekend";
}
```
```Python
# Python

match day:
    case 6: print("Today is Saturday")
    case 7: print("Today is Sunday")
    case default: print("Looking forward to the Weekend")

```

<!-------------------------------------------------------- WHILE LOOP -------------------------------------------------------------->
### While Loop
```C++
// C++

int i = 0;
while (i < 5) {
  cout << i << endl;
  i++;
}
```
```Python
# Python

i = 0
while i < 5:
    print(i)
    i += 1
```

<!-------------------------------------------------------- FOR LOOP -------------------------------------------------------------->
### For Loop
```C++
// C++

for (int i = 0; i < 5; i++) {
  cout << i << endl;
}
```
```Python
# Python

for i in range(5):
  print(i)
```
