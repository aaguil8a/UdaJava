# What is a Variable?

A variable lets you store data within an application: It is combination of both:

* A location in the computer memory.
* An associated name that we use in our code to refer to the data in that memory location. Example:

``` java
age = 42;
```

Specifically, variables help us store state data:

> State data is data related to the current state of the program as it is running.

## Using Variables in Java

In Java, when we declare or define a variable one has to specify the data type, name and any value. 

``` java
int age = 42;

```

Note that the variable is able to vary: 
``` java

int age = 42;
age = 43;
age = 44;


```
These lines are referred to as assignment statements(because we are assigning the value on the right to the variable named on the left) and the = sign is called the assignment operator.


Notice that, in Java, we must specify the data type (e.g., int). This is becouse Java is a statically typed language. Here are the key points to remember about static typing:

* The data type is bound to the variable when the variable is first declared.
* The data type is checked when the code is compiled.
* The data type for a variable cannot later be changed.



Note: Java uses semicolon to know when a statement is done. 
