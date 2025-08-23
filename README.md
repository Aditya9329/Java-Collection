# Java-Collection

Java Set Interface
The Set interface is part of the Java Collections Framework and is used to store a collection of unique elements.


## Common Set Methods
- Method	Description
- add()	Adds an element if it's not already in the set
- remove()	Removes the element from the set
- contains()	Checks if the set contains the element
- size()	Returns the number of elements
- clear()	Removes all elements

## Practice of comman methods
	//create hashset class
		HashSet<String> s = new HashSet<String>();
		//add element
		s.add("ABCD");
		s.add("Bolero");
		s.add("Thar");
		
		//contains
		System.out.println(s.contains("Thar"));
		
		//size()
		System.out.println(s.size());
		
		//remove
		s.remove("Thar");
		
		System.out.println(s.size());



## Java Map Interface
The Map interface is a part of the Java Collections Framework and is used to store key-value pairs. Each key must be unique, but values can be duplicated.
Common Map Methods
- Method	Description
- put()	Adds or updates a key-value pair
- get()	Returns the value for a given key
- remove()	Removes the key and its value
- containsKey()	Checks if the map contains the key
- keySet()	Returns a set of all keys

## Java HashMap class
A HashMap stores items in key/value pairs, where each key maps to a specific value
HashMap<String,String> CapitalCities = new HashMap<String,String>();
		
		//adding keys aand values
		CapitalCities.put("India","Delhi");
		CapitalCities.put("England", "London");
		CapitalCities.put("USA", "Washington");
		
		System.out.println(CapitalCities);
		
		//access item
		System.out.println(CapitalCities.get("England"));
		
		//remove item
		
		//--CapitalCities.remove("England");//
		
		//printing keys
		
		for(String x:CapitalCities.keySet())
		{
			System.out.println(x);
		}
		
		
		
		//printing values
		for(String y:CapitalCities.values())
		{
			System.out.println(y);
		}
		
		
		///printing keys anad values
		
		HashMap<String,String> CapitalCities = new HashMap<String,String>();
		
		//adding keys aand values
		CapitalCities.put("India","Delhi");
		CapitalCities.put("England", "London");
		CapitalCities.put("USA", "Washington");
		
		System.out.println(CapitalCities);
		
		//access item
		System.out.println(CapitalCities.get("England"));
		
		//remove item
		
		//--CapitalCities.remove("England");//
		
		//printing keys
		
		for(String x:CapitalCities.keySet())
		{
			System.out.println(x);
		}
		
		
		
		//printing values
		for(String y:CapitalCities.values())
		{
			System.out.println(y);
		}
		
		
		///printing keys anad values
		
		for(String i:CapitalCities.keySet())
		{
			System.out.println(i+  CapitalCities.values());
		}
		
		HashMap<String,String> CapitalCities = new HashMap<String,String>();
		
		//adding keys aand values
		CapitalCities.put("India","Delhi");
		CapitalCities.put("England", "London");
		CapitalCities.put("USA", "Washington");
		
		System.out.println(CapitalCities);
		
		//access item
		System.out.println(CapitalCities.get("England"));
		
		//remove item
		
		//--CapitalCities.remove("England");//
		
		//printing keys
		
		for(String x:CapitalCities.keySet())
		{
			System.out.println(x);
		}
		
		
		
		//printing values
		for(String y:CapitalCities.values())
		{
			System.out.println(y);
		}
		
		
		///printing keys anad values
		
		for(String i:CapitalCities.keySet())
		{
			System.out.println(i+  CapitalCities.values());
		}
		
		HashMap<String,String> CapitalCities = new HashMap<String,String>();
		
		//adding keys aand values
		CapitalCities.put("India","Delhi");
		CapitalCities.put("England", "London");
		CapitalCities.put("USA", "Washington");
		
		System.out.println(CapitalCities);
		
		//access item
		System.out.println(CapitalCities.get("England"));
		
		//remove item
		
		//--CapitalCities.remove("England");//
		
		//printing keys
		
		for(String x:CapitalCities.keySet())
		{
			System.out.println(x);
		}
		
		
		
		//printing values
		for(String y:CapitalCities.values())
		{
			System.out.println(y);
		}
		
		
		///printing keys anad values
		
		for(String i:CapitalCities.keySet())
		{
			System.out.println(i+  CapitalCities.get(i));
		}
		



  ## Core Java Interview Question
Part-1
-- https://rahulshettyacademy.com/blog/index.php/java-interview-questions/ --
Question 1: Write a Java Program to reverse a String.
Question 2:  Write a Java Program to swap two given Strings
Question 3: Write a Java Program to print the Fibonacci Series.
Question 4: Write a Java Program to check if a number is Armstrong number or not.
Question 5: Write a Java Program to print the sum of digits of a given integer.
Question 6: Write a Java Program to check if a number is Prime or not.
Question 7:  Write a Java Program to count the number of characters in a given String.
Question 8: Write a Java Program to find the duplicates of a given String.
Question 9: Write a Java Program for swapping of 2 numbers.
Question 10: Write a Java Program to reverse an array?
Question 11: Write a Java Program to get the count of Capitalized words in a String.
Question 12: Write a Java Program to find the longest consecutive occurrence of integers in a given array.

Part-2

-> Question 13: Write a Java Program to generate Output "aabbbcccc" with the input "a2b3c4"
-> Question 14: Write a Java Program to print the product of an array except self?
-> Question 15: Write a Java Program to reverse a number using Stack.
-> Question 16:  Write a Java Program to print the second largest number in a given array.
-> Question 17: Write a Java Program to print the first non repeating character in a given String.
-> Question 18: Write a Java Program to print the maximum consecutive ones in a given array.
-> Question 19: Write a Java Program to print the first and last position of a number in a given array.
-> Question 20: Write a Java Program to print numbers 1 to 100 without using any loop(for/while/do-while).
-> Question 21: Write a Java Program to shift all zeros on the right.
-> Question 22: Write a Java Program to remove the duplicates from an array.
-> Question 23: Write a Java Program to iterate through the HashMap.
-> Question 24: Write a Java Program to convert HashMap to ArrayList.
-> Question 25: Write a Java Program to print the missing number in a given Array.

Part-3

1. Write a Program to check if an element is part of a collection or not.
2. Write a program to reverse an ArrayList.
3. Write a program to convert ArrayList to LinkedList and vice versa.
4. How to get the highest and lowest values of a List?
5. How to make a collection read-only?
6. What is the difference between Iterator & Enumerator?
7. Compare different Collection classes with respect to their properties.
List
8. What are the differences between List & Set?
9. What are the differences between Array and ArrayList?
10. What are the differences between Arraylist & LinkedlList?
Set
11. What are the differences between Set & Map?
12. What are the differences between HashSet & TreeSet?
Map
13. What are the differences between HashSet & HashMap?
14. What are the differences between HashMap & TreeMap?


Part-4

1. What is the difference between JDK, JRE, and JVM?
2. What are the different types of constructors in Java? And How to overload Constructor?
3. What is the static keyword? How it can be used?
4. What is this final keyword? how I can be used?
5. What is the difference between method overloading and method overriding?
6. Could you explain IS-A and HAS-A relationship?
7. Explain this and super keyword
8. How to check instance of Specified type? Explain with example
9. What is a package in Java? What are different types of packages? Can we create a custom package?
10. What is run time polymorphism in Java?
11. What is the difference between static and dynamic binding in java?


Part-5

1. How to make class read-only explain briefly?
2. What is Object Class explain?
3. What is the difference between Mutable and Immutable Object? Explain String and StringBuilder in the same context
4. What are the different types of exceptions in java?
5. Can we have a Single Catch Block and Multiple Try block?
6. Can we have try block without catch block? How do you handle multiple exception with single try block?
7. Tell me the difference between == and .equals
8. Tell me some helpful string methods in Java
9. Why should avoid static methods in Java? Explain
10. How can I use the thread concept in Java, Explain two types


Part-6

1. How can we achieve Pass by value and pass by reference in Java?
2. Explain Different types of interfaces in the Collection framework
3. What is the difference between Array List and LinkedList? Which is better explain?
4. What is the difference between List and Set?
5. What is the difference between HashSet and HashMap?
6. Explain Collection and Collections in Java?
7. Explain the difference between Comparable and Comparator.
8. Are Array and Array List are the same? If Not, How do we convert them to each other?
9. What is Generic Class? Could you explain with a small snippet?
10. How Sub Class is different from Inner Class?
11. What is a singleton class? Explain with a small code snippet
12. Explain Thread life cycle briefly? What are some commonly used methods?
13. What is garbage collection? How to force Garbage Collection?

Part-7

1. What is Typecasting explain with small code snippet?
2. Write a program to reverse a string  without using string.reverse() method
3. Write a program to calculate the occurrences of each character in the string
4. Write a program to check the magic number
5. Write a program to check if two strings are an anagram
6. Write a program to create a deadlock in java
7. Consider I have data like below distance to the city from your hometown

Part-8

1. Write a program to sort ArrayList using Comparable and Comparator
2. I have arrayList like [Test1, Test2, Test3, Test4, Test5] Write a Program to replace the "Test2" with string "ReplacedTest"
3. Write a Java program to insert the specified element at the end of a linked list
4. Write a program to perform Pairwise swap elements of a given linked list
5. Check if two arrays have same number of items and values
6. Write a Java Program to find the largest and smallest word in a string
7. Java Program to Check if a Given Number is Perfect Square
8. Write a Program to cover all major concepts of OOPs
9. Write a program to find the length of the string without using string.length();













  
		
		














