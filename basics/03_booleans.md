# Booleans

Booleans are another Javascript primitive data type.

They represent a binary data structure, or in other words, they are simply true or false.

In javascript, *true* and *false* are special keywords that are considered of boolean type.

For instance ..
```
let isBored = true
```

What kind of situations can a simple true or false data be useful for?

What about a simple room light? A light can either only be "on" or "off", and so
a boolean might be the perfect way to represent this information.

```
// The room is currently dark

let lightIsOn = false

function lightSwitch() {
  lightIsOn = !lightIsOn
}

//let's turn the light on!
lightSwitch()

//let's turn the light off..
lightSwitch()

// and then on again?
lightSwitch()
```

In the above simple lights example, we create and assign the variable lightIsOn to the
Boolean value of false (Since it says the room is currently dark 0-0)

Then we create a function to toggle the value of lightIsOn between true and false using the ! or NOT operator.
The ! operator is used to simply return the opposite of the current Boolean value.

(I know we haven't gone over what a function is yet and you may not know what a function in JS is YET, just know that a function is a special JS tool use to execute specific lines of code in certain situations)

Try in your console:
```
!true

!false
```

What do you think we would get for..
```
!!true
!!!!false
```

ALL JS values are either *truthy* or *falsey*, or can be evaluated to being true or false.

To check whether a value is truthy of falsey, you can simply run the Boolean() function!

```
Boolean(true)

Boolean(false)

Boolean(0)

Boolean(1)

Boolean(null)

Boolean(undefined)

Boolean('')

Boolean('hello')
```
