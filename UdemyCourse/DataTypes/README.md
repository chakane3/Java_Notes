# Data Types

We have this concept of primitive data types, these are built into the java language. These are 
<ul>
    <li>INTegral: byte, short, int, long</li>
    <li>Floating: float, double</li>
    <li>Char</li>
    <li>Boolean</li>
</ul>

<details>
    <summary>Heres a more detailed look at these types</summary>

| Type | Size | Range | Default Value |
| ---------------- | ------------------------------------------- | -------------- | --------------------------- |
| byte | 1 | -128 to 127 | 0 |
| short | 2 | -32768 to 32767 | 0 |
| int | 4 | -214748638 to -2147483647 | 0 |
| long | 8 | - | 0 |
| float | 4 | -+ 1.4E-45 to +/ 3.4E+38 | 0.0f |
| double | 8 | +/439E-324 to +/1.7E+308 | 0.0d |
| char | 2 | 0 to 65535 | \u0000 |
| boolean | - | true(0)/false(1) | false |
    
</details>

Variables will always have some kind of type. One byte is a unit of space. There are 8 bits in a byte. For evert data type there is a class for that already built in. For example:

``` java
int x;
Integer y;
```

## Variables
These are just names we give to our data. All variables must have some kind of data type. When we declare a variable some memory is being allocated for the data associated with it. 

## Literals
Think of theese as inferred types. For example

``` java
// here 3.14 is going to be treated as a double
area = 3.14d*radius*radius;
```

This idea happens with the other data types. This could be:
<ul>
    <li>3l</li>
    <li>2.4d</li>
    <li>2.0045f</li>
</ul>

Integer Literals and such can be represented in different number systems. Recall:


|uses 10 digits| Decimal | 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 |
|uses 2 digits| Binary | 0, 1 |
|uses 8 digits| Octal | 0, 1, 2, 3, 4, 5, 6, 7 |
|uses 16 digits| Hexadecimal | 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F |