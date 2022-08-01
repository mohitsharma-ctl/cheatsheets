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

**Arrays**

1D
```java
int[] array = new int[10];
```
2D

```java
int[][] array = new int[10][10];
```

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
**[String Methods](https://www.w3schools.com/java/java_ref_string.asp)**

charAt()
```java
String name = "mohit";
name.charAt(0);  /* Used to print the char at given index
'm'
*/
```
length()
```java
String name = "mohit";
name.length();  /* Used to print the char at given index
'5'
*/
```

**Hashmap**

Stores the data in key, value pairs
```java
HashMap<Character,Integer> map = new HashMap<Character,Integer>();
hm.put(key,value); for inserting
hm.get(key,value); //for fetching
hm.containsKey(key); //for checking if key exist or not
hm.size(); 	    //length
hm.isEmpty();    


```

**Array List**

Just like list in python , with insert , append , delete functionality 
```java
import java.util.ArrayList;
ArrayList<Integer> nums = new ArrayList<Integer>();

nums.add(1);
nums.get(0);
nums.remove(0);
nums.insert(0,2);
nums.size();
nums.clear();
```

**Vector**

 Implements a growable array of objects
```java
import java.util.Vector;
Vector<Integer> nums = new Vector<Integer>();
nums.add(1);
nums.get(0);
nums.insertElementAt("Hello", 2);
```

**Stack**

```java
Stack<Integer> st = new Stack<Integer>();
st.push(1);     //insert element into stack
st.peek();	//check the top element of the stack
st.pop();	//removing out the element from stack
```

**Queue**

Queue is a interface so we cant create its object directly, we have to first implement it in some other class

```java
Queue<Integer> q = new LinkedList<Integer>();
q.add(1);     //insertion
q.peek();    //returns first element of the q
q.remove();  //remove the first element of q
```

**Exception Handling**

*try catch*

It will catch the exception as well as handle it

```java
try{
//peice of code
}
catch (Exception e){
//handles the exception
}
```

*throws*

Whenever it will see the exception , it will throw the exception <ins>not handle</ins> it

```java
public class Main{
public int division() throws ArithmeticException
{
int a = 4;
int b = 0;
return a/b;
}
}
```

*throw*

It will explicitly throws the exception
```java
public void checkAge(int age){
if(age<18){
throw new ArithmeticException("Not eligible to vote");
}
}
```
*finally*

It is printed at the end of try catch statement , it is used so that even when program terminate , whatever stored inside finally will execute


```java
try{
//peice of code
}
catch {
//handles exception
}
finally{
//everytime executes
}
```
*Common Exceptions*

NullPointerException -
ArrayIndexOutOfBoundsException - 
ArithmeticException - 
ClassNotFoundException - 
InstantiationException - 
