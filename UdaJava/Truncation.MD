# Truncation
Truncation is a loss of precision when going from one to type to another. Basically, we are cutting off or "truncating" the additional data.

Another way to put it: Loss of precision when going from one to type to another--not same thing as rounding up or down since we are cutting off data. * It only happens manual type casting.

```
8 bytes -> double doubleNumber = 3.5;

4 bytes -> int IntNumber = (int) doubleNumber;

# It prints out 3

```
When does truncation occur?

When doing manual casting to convert a larger type to a smaller type.

Truncation occurs because smaller types allocate less memory than larger types.


