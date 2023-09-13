# CTSTask_2242945
 Task
 
 
 
 --------------------------------------------------------------------------------------------------------------
P1Q1.java
  Basic Lambda Expressions:
• Write a lambda expression that takes two integers and returns their sum.

Step 1. Create a one Calculate interface and make a one sum methode with a,b int parameter and return int value

Step 2. Making a one P1Q1 class and implement  the main methode.

Step 3. initialize the interface and add the logic and return the sum of value.

step 4. and using interface reference call the sum methode and pass the value and print

-------------------------------------------------------------------------------------------------------------

• Write a lambda expression that takes a string and returns its uppercase version.

Step 1. Create a one Utility interface and make a one makeUpperCase methode with str String parameter and return the Sting value

Step 2. Making a one P1Q1 class and implement  the main methode.

step 3.  initialize the interface and  return the UpperCase string of value and print.

step 4. and using interface reference call the UpperCase methode and pass the value and print.

-------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------
 P1Q2.java
 
      2.Comparator Using Lambda
	  
     • Given a list of strings, sort them based on their length using a lambda expression.

Step 1. create a List<String> and add some string value.

step 2. by using Collections.sort method pass the list and create a lambda exp to make comparator interface and compare methode compare the length.

step 3. sprint the list and get the sorted list based on length of string.

-------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------

P1Q3.java

3. Runnable Using Lambda:

           • Create a new thread using the Runnable interface and lambda expressions.
		   
              The thread should print "Lambda Runnable in action!" when run.

Step 1. create a one Runnable interface and using lambda print "Lambda Runnable in action!".

step 2. create a one thread and pass the parameter and start the thread.


***************************************************************************************************************

P2Q1.java

Part 2: Functional Programming

1. Streams:

• Convert a list of integers into a stream, filter out the odd numbers, and collect the result into a new list.

Step 1. create a List<Integer> and add some integer value.

step 2. by using stream api add filter api and make a predicate like x -> x % 2 != 0.

step 3. and again collect into List value and print the values.


-------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------

P2Q2.java

 Map-Filter-Reduce:
 
• Using a list of strings, convert all strings to uppercase (map), filter out strings

that are less than 4 characters long, and concatenate the remaining strings (reduce).


step 1. create a List<String> and add some string value.

step 2. using stream map api making a all list of string as a upper case.

step 3. after filter api filter the all value that length is less than 4.

step 4. after using reduce api concatenate the remaining string and print the value.


-----------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------
P2Q3.java

Function Composition:

• Create two Function<Integer, Integer> definitions:

    a. One that multiplies the given number by 2.


step 1. create a one Composition Function  Function<Integer, Integer> and make lambda exp and return a login to value multiply by 2.

step 2.  pass the values using apply to given number and print the value;

------------------------------------------------------------------------------------------------------------
    b. Another that adds 3 to the given number.
	

step 1. create a one Composition Function  Function<Integer, Integer> and make lambda exp and return a login to value added by 3.

step 2.  pass the values using apply to given number and print the value;

----------------------------------------------------------------------------------------------------------------

• Compose the two functions into a new function that multiplies a given number by 2 and then adds 3.


step 1. create a one Composition Function like  Function<Integer, Integer> and by using andThen combine the both upper composition function.

step 2.  pass the values using apply to given int value and print the value;


***************************************************************************************************************

P3Q1.java

Part 3: Using Pre-defined Functional Interfaces

1. Predicates:

• Write a predicate that checks if a number is even.


step 1. create a one List<Integer> list and  add some value.

step 2. create a one predicate function and add the login if the value is even then its return true else false.

step 3. using filter to pass above predicate function and return the list and print.


-----------------------------------------------------------------------------------------------------------
• Write a predicate that checks if a string's length is greater than 5.


step 1. create a one List<String> list and add some value.

step 2. create a one predicate function and add the logic if the value length is greater than 5 its return true else false.

step 3. using filter to pass above predicate function and return the list and print.


-----------------------------------------------------------------------------------------------------------
• Combine the two predicates to check a list of strings and filter out those that

   are even in length and have a length greater than 5.
   

step 1. create a one List<String> list and add some value.

step 2. create a one predicate function and add the login if the string value length is even then its return true else false.

step 3. again create a predicate function and add the logic if the value length is greater than 5 its return true else false.

step 4. again create a predicate function and  add both  predicate using "and" method and combine both.

step 5. using filter to pass above predicate function and return the list and print.
-----------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------

P3Q2.java

2. Function Interface:

• Write a function that takes a string and returns its length.


step 1. create a one Utility1 interface and make add @FunctionalInterface so using this annotation specify the anable to add andy another abstract method.

step 2. add method like returnLength and pass string value and return the int value;

step 3. using lambda exp initialize the interface and write the logic to count the length.

step 4. using interface object call the returnLength method and print the value.

-----------------------------------------------------------------------------------------------------------------------
• Write a function that takes a string and returns its lowercase version.

step 1. create a one Utility2 interface and make add @FunctionalInterface so using this annotation specify the arable to add andy another abstract method.

step 2. add method like returnLowerCase and pass string value and return the string value;

step 3. using lambda exp initialize the interface and write the logic to return the given string as lower case.

step 4. using interface object call the returnLowerCase method and print the value.

-----------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------
P3Q3.java

Consumer and Supplier:

• Write a consumer that prints the string it receives.



step 1. create a one  Consumer<String> consumer and add some logic to print the given sting using lambda exp.

step 2. using consumer object call the "accept" those and pass the value.

step 3. and you can see the given values is printed.


-----------------------------------------------------------------------------------------------------------
• Write a supplier that returns the current date-time as a formatted string.


step 1. create a one Supplier<String> supplier and add some logic to print the Current date-time  with specific "dd-MMM-yyyy hh:mm:ss a" pattern using lambda exp.

step 2. using supplier object run supplier "get()" and return thous string to print.

step 3. and you can see the given values is printed.


***************************************************************************************************************

