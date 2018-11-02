# IF statements

If statements are a powerful Javascript statement that checks a condition before
running code.

Remember our isFreezing variable from earlier we used to store a Boolean value?

```
let temp = 32
let isFreezing = temp <= 32

if(isFreezing) {
  console.log("Omg it's lit outside")
}
```

Do we expect the above console log to run?

How can we change the code above so that console log doesn't run?

This is known as **flow control**, so that we can exactly control how and when certain
parts of our program runs.

<br>

To modify our code above, this would also work:
```
let temp = 32

if (temp <= 32) {
  console.log("Omg it's still lit")
}
```

This is how if statements will be more commonly used and seen in JS.

<hr>

The general skeleton of if statements looks like this:

```
if(boolean) {
  //code if boolean is true
} else if(boolean) {
  //code if this boolean is true
} else {
  //code
}
```

When the JS interpretor sees the keyword *if*, it checks to see *if* the given
condition is true, and then runs the code if it is true. If the if() statement runs,
it will ignore all the *else if* and *else* statements.

However, if the if() statement is NOT run, the JS interpretor will move on to the
*else if* statements one by one. You can have as many else if statments in a code block
as you need. If any of the else if statements run, the JS interpretor will escape from
the code block.

Finally, if the if() and else if() statements are false and not ran, the else statement will run.
Think of the else statement as a final "catch-all" statement that will run only if all conditional
statements returned false.

CHECK YOUR UNDERSTANDING.
```
var day;

if(day === "Sunday") {
  console.log("Today is Sunday")
} else if (day === "Monday") {
  console.log("Mondays are the worst!")
} else if (day === "Tuesday") {
  console.log("ZZZ")
} else if (day === "Wednesday") {
  console.log("Half way there...")
} else if (day === "Thursday") {
  console.log("Tomorrow's Friday!!!")
} else if (day === "Friday") {
  console.log("Queue Rebecca Black's Friday...")
} else if (day === "Saturday") {
  console.log("I'm out of ideas")
} else {
  console.log("Please give me a valid day of the week.")
}
```
If we set day = "Sunday", JS will hit the first if() statement, and since the conditional
returns true, the console will log "Today is Sunday" and skip the rest of the code block.

If we set day = "Friday", JS will continue running through the code block starting from the
very first if() statement and continue to run through our else if() statements until it reaches an else if statement that has a conditional evaluating to true. (day === "Friday")

Finally, if we set day = "Something that's not a day", JS will run through all the statements, see
that none of the if or else if statements return true. It will then default to the else statment block!

<br>

What's the difference here?
```
let day = "Tuesday"
if(day === "Sunday") {
  //code
}

if(day === "Monday") {
  //code
}

if(day === "Tuesday") {
  console.log("We made it!")
}
```
In the case above, EVERY single if() statement is run. That's because each if code block is
its own domain. Else if and Else statements can ONLY be attached to an if statement!
