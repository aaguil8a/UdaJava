# Type Casting

Changing one type into another

```
2 -> 2.0
```

Two ways to do casting:

### Automatic

* Automatic type casting converts a smaller type into a larger type. Example:
  
```
int intNumber = 3;
double doubleNumber = intNumber;
# It will print out 3.0

```
Note: There is no precision lost going from a smaller type into a larger type. 




### Manual 
Manual type casting is necessary when we want to do either of these things:

* Convert a larger type into a smaller type

* Convert one object type into another
```
double doubleNumber = 3.5;
int intNumber = (int)doubleNumber;
# It prints 3

```
Note when we go to larger type into a smaller type, precision is lost. 

