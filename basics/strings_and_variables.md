## Strings and Variables!
---

### Variables

Variables are used to store a value to a keyword.

In Javascript, we have special words such as var, const, and let!

In JS, we use the single equal sign "=" to *assign*

```
var name = "Austin"

let favorite_animal = "mouse"

const DOB = "July 9, 1994"
```

What happens when we:

```
console.log(name)
```

<br>

Variable names should be something that makes sense to its corresponding value.

For instance, we might have a variable that stores the a grocery shopping list.

```
grocery_list = ["eggs", "milk", "rice", "kimchi", "bread"]
```

The value of the variable grocery_list is an array. We will go over what an array is
later!

Variables cannot have numbers in front of them "1my_variable" and cannot have
any spaces.

What happens if we try to do...
```
var first name = "Sam"
```

Returns an error! Javascript thinks that the variable name is simply the word "first",
and that we are trying to reassign a variable "name" that already exists to another value "Sam"...

In general, if we have a variable name with multiple words, we use..
<ul>
<li>"Camel Case": myFirstName</li>
<li>"Snake Case": my_first_name</li>
</ul>

<br>
Variables can be ***reassigned***
