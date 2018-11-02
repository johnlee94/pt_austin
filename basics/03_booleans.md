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
