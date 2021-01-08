# Variables

The first step towards really understanding programming is looking back at algebra. If you remember it from school, algebra starts with writing terms such as the following.

```text
3 + 5 = 8
```

You start performing calculations when you introduce an unknown, for example x below:

```text
3 + x = 8
```

Shifting those around you can determine x:

```text
x = 8 - 3
-> x = 5
```

When you introduce more than one you make your terms more flexible - you are using variables:

```text
x + y = 8
```

You can change the values of x and y and the formula can still be true:

```text
x = 4
y = 4
```

or

```text
x = 3
y = 5
```

The same is true for programming languages. In programming, variables are containers for values that change. Variables can hold all kind of values and also the results of computations. Variables have a name and a value separated by an equals sign \(=\). Variable names can be any letter or word, but bear in mind that there are restrictions from language to language of what you can use, as some words are reserved for other functionality.

Let's check out how it works in Javascript, The following code defines two variables, computes the result of adding the two and defines this result as a value of a third variable.

```javascript
var x = 5;
var y = 6;
var result = x + y;
```

