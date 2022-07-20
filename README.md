## Python/C++ Sintax Cheat Sheet


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

### Variables

|  C++ |  Python |
| ------------ | ------------ |
| int age = 18; | age = 18 |
|int a[10];  | a = [] |

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
