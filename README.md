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
		
		
		
		














