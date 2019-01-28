# Objects Exercises

1. Create a "person" object for each member in your family (including yourself!). You should include name(str), age(number), relation(str), occupation(str), and hobbies(arr[str]) as keys.

For example:
```
var john = {
  name: "John Lee",
  age: 24,
  relation: "Tutor",
  occupation: "Web Developer",
  hobbies: ["Eating", "Games", "Singing"]
}
```

2. Create a function called getHobbies that takes in the "person" object and returns a string sentence. Pass in each object you created above into the function and console log it.
```
getHobbies(john) // => "John likes eating, games, and singing"
```

3. Add a method to one object you created above called getName that returns a sentence string of the person's name.
```
john.getName() => "My name is John Lee"
```

4. Add a method to a different object you created above called getHobbies that returns strings for each hobby in the object's "hobbies" property.
```
john.getHobbies() =>  "I like Eating"
                      "I like Games"
                      "I like Singing"
