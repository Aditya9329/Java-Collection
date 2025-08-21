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
