Alright alright.

Let's talk about...

#DICTIONARIES

Dictionaries are cool cuz they're like an array's cool older brother who, instead of going to college and getting a boring business degree, went out and saw the world and experienced different cultures.

Let's get an example going.

```swift
  var super: [String: String] = ["Superman": "Clark Kent", "Spider-Man": "Peter Parker", "Squirrel Girl": "Doreen Green"]
```
Notice how we have keys instead of position numbers. A key can be of any data type and so can the values.

Let's see what else we can do in dictionaries.

```swift
  var super: [String: String] = ["Superman": "Clark Kent", "Spider-Man": "Peter Parker", "Squirrel Girl": "Doreen Green"]
  
  //Add new key-value pair 
  super["Batman"] = "Bruce Wayne"
  
  //Change a value
  print(super["Spider-Man"])
  //prints "Peter Parker"
  super["Spider-Man"] = "Miles Morales"
  print(super["Spider-Man"])
  //now prints "Miles Morales"
  
  //Declare an empty dictionary
  var emptyDict = [String:String]()
  //or
  var emptyDict2: [String: Int] = [:]
```

#END OF THE LESSON CHALLENGE THING

1. For every month there must be a meme. Let's create a dictionary for the memes of the past 4 months. October had PPAP; November had Joe Biden; December was the month of Evil Kermit; January had Salt Bae.

2. Hold up I change my mind. Let's change January's meme to Cash Me Ousside Howbow Dah? Reset January's me to that.
