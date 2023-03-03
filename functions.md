# Functions
Functions are the main "building blocks" of the program. They allow the code to be called many time without having to retype it multiple times.

## How functions work
### Function Declaration
To create a function, use a **function declaration**.

```
function showMessage(){
    alert("Quack!")
}
```

To call a function, you call it by its name.

```
showMessage()
```

So now it would **alert: Quack**.

### Parameter
Parameters is a named variable passed into a function. Parameter variables are used to import arguments into functions.

```
function showMessage(from, text) {
     alert(from + ': ' + text)
}
```

Here the parameters are **from** and **text**.

```
showMessage("Ann", "Hello")
showMessage("Ann", "What's up?")
```

When the function is called in the first and second line of code, the given values (in this case **"Ann", "Hello"** and **"Ann", "What's up?"**) are copied to local variables **from** and **text**. Then the function can use them.

### Arrow function
Arrow functions is a compact alternative to a normal function.

```
function hello(name) {
    return "Hello" + name
}

hello("World")
```

Here is a normal function turned into a arrow function.

```
const hello = (name) => {
    return "Hello" + name
}
```

[Back to READ ME](README.md)