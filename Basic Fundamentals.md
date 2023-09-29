#### Virtual Functions

A virtual function (also known as virtual methods) is a member function that is declared within a base class and is re-defined (overridden) by a derived class

#### Default Values
Functions can also specify the default values for function parameters, if no specified value is called in function argument than default value will be used in function parameter

```java
public void greet(String name, String title = "Mr.") {
  System.out.println("Hello, " + title + " " + name);
}
```

The title parameter is optional, and has a default value of "Mr.". This means that when the greet() method is called without a value for the title parameter, the default value will be used.

Ex

```java
// Call the greet() method with a value for the title parameter.
greet("John Doe", "Dr.");

// Call the greet() method without a value for the title parameter.
greet("Jane Doe");
```

Output
```
Hello, Dr. John Doe
Hello, Ms. Jane Doe
```

#### Operator Overloading

<p>Operator overloading is a feature in some programming languages that allows you to define custom behaviors for built-in operators (such as +, -, *, /, ==, <, >, etc.) when applied to user-defined data types or objects. It allows you to make your classes and objects work with operators in a way that makes sense for your specific application.</p>


```c++
 Complex operator+(const Complex& other) const {...}
```

#### Pointers and References
<p>
Pointers - is a variable that stores the address of another variable
Size of pointers depends upon the architecture of the machine
</p>

```c++
int a = 10;
int* p = &a;
printf("%d\n", *p);
```

Output: 10

References - are aliases for other variables. This means that when you create a reference to a variable, you are essentially creating another name for that variable.


```c++
int& r = a;
```
