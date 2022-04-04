**Java cheatshet**

*helloworld.java*
```java
class main {
    public static void main(String[] args) {
        System.out.println("Hello World"); 
    }
}
```
code we write in a  <ins>.java</ins> file is transformed into <ins>byte code</ins> by a compiler before it is executed by the Java Virtual Machine(jvc) on your computer


For compiling a java program

```javac helloworld.java```

A successful compilation produces a .class file: helloworld.class, that we execute with the terminal command:

```java helloworld```

**Comments**
```java
// this is a single line comment

/*a b c d e f g h i j k
this is a multi line commment
1 2 3 4 5 6 7 8 9*/
```
**Statement**
```java
System.out.println("Hello world");
```

**variables**

```java
int x = 1;
String x = "mohit";
double x = 5.634563;
boolean x = true;
float x = 11.11;
```


- int - stores integers without decimals
- String - stores text, such as "Hello"
- char - stores single characters, such as 'a'
- double - stores fractional numbers. Sufficient for storing 15 decimal digits
- boolean - stores values with two states: true or false
- float - stores floating point numbers, with decimals


**for loop**

```java
for(int i = 0;i<10;i++){
	arr[i];
}
```

**for each loop**

```java
int arr[]  = {1,2,3,4,5,6};
for(int i:arr){
System.out.println(i);
}

```

**while loop**
repeated if statement
```java
while(i<9){
	//to be code
}
```
**do while loop**
iterate a part of the program repeatedly, until the exit point is not met
```java
do{
	//to be code
}
while(i<9)
```

**if else condition**
```java
if(x<3){
	//to be code
}
else if(x=4){
	//to be code
}
else{
	//to be code
}
```

**switch case**
```java
int day = 4;

switch (day) {
  case 1:
    System.out.println("Monday");
    break;
  case 2:
    System.out.println("Tuesday");
    break;
  case 3:
    System.out.println("Wednesday");
    break;
  case 4:
    System.out.println("Thursday");
    break;
  case 5:
    System.out.println("Friday");
    break;
  case 6:
    System.out.println("Saturday");
    break;
  case 7:
    System.out.println("Sunday");
    break;
}
// Outputs "Thursday" (day 4)
```
