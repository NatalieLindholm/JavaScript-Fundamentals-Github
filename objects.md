# Objects
Are used for storing collections of data

## How objects work
### Creating an object with data

```
let user = {
    name: "Bonkers",
    age: "29"
}
```

### Accessing the data in the object

```
alert(user.name)
alert(user.age)
```

So the output would be **Bonkers** and **29**.

### Adding data to an object
To add data to an object, you put the variabel name (in this case user) and a **.** + the data you wanna add.
```
user.lastName = "Stonkers"
```
### Remove data from an object

```
delete user.lastName;
```

This removes the data of **lastName** from the object.

## Examples
Heres an object storing salaries of a team:

```
let salaries = {
    John: 100,
    Ann: 160,
    Pete: 130
}
```

Heres a code that summarize all salaries which should be **390** and stores it in the variable **sum**. If salaries is empty, the result is **0**.

```
let sum = 0;

for (let name in salaries) {
    sum = sum + salaries[name] // 100, 160, 130
}

alert(sum)
```

The sum = sum + salaries[name] adds togheter all the salaries which is **100 + 160 + 130**. So the output when it alert(sum) is **390**.

[Back to READ ME](README.md)