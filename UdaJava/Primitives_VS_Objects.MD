# Primitives vs Objects

In java, there are two ways to variables get assign: 

* **Primitive value**: is simply a value, by itself, with no additional data.

``` java**
int age = 42
```


* **reference value** is a value that refers to an object stored in another location in memory.

```java

age -> reference, integer@505 ->, which points to data object id: 505,
Type: Integer, Value: 42

```
Why create reference value? B/C allows one to Object bundle the primitive value up with additional useful information and behavior. 

## Primitive Types

How to define a primitive variable?
```
type name = value;
```
---
Data Type	Size
byte	1 byte
short	2 bytes
int	4 bytes
long	8 bytes
float	4 bytes
double	8 bytes
boolean	1 byte
char	2 bytes

* As you can see in the table, each primitive type has a memory size allocation, meaning that if we created a variable with one of these types, that variable would have a certain size in memory (e.g., an int primitive is always allocated 4 bytes in memory).

* All of keywords for primitives start with a lowercase letter.

## Object Reference Types

* Creates a reference to a data object
* Java-defined types: String, Array
* User-defined classes
* Do not have a specific memory allocation size.
  
How to create?

```
Type name = value;
String text = "Hello there";
```

When you create have uppercase--and may have additional behavior and even other variables defined within them.

***** important
As we said above, reference types create a reference to a data object. This object can be a Java defined type, like String or Array or it can be a customized, user-defined object. This allows literally infinite flexibility, since you can define whatever object types you need for your particular application.
