# Arrays
Arrays are used for storing **ordered** collcetions of data.
Arrays are also numbered, and they start with **zero**.

## How array works
### Array with some data

```
let colors = ["Blue", "Red", "Purple"]
```

### Accessing data in the array

```
colors[0]
colors[2]
```

So the output would be **Blue** and **Purple**

### Replacing an element in the array

```
colors[1] = "Green"
```

So the new array is now

```
let colors = ["Blue", "Green", "Purple"]
```

### Adding a new element to the array

```
colors[3] = "Yellow"
```

So the new array is now

```
let colors = ["Blue", "Green", "Purple", "Yellow"]
```

### How to check the total count of elements in the array

```
colors.length
```

The output would be **4**

## Examples
Looping an array

```
let cars = ["Bmw", "Toyata", "Ferrari", "Miata"]
 
 for (let i = 0; i < cars.length; i++){
    console.log(cars[i])
 }
 ```
 
 The output would be **Bwm, Toyata, Ferrari, Miata**

 [Back to READ ME](README.md)