# map-filter-reduce-assignment


## 1. filterGeese

Write a function called filterGeese that takes a list of strings as an argument and returns a filtered list containing the same elements but with the "geese" removed.

The geese are:

```js
["African", "Roman Tufted", "Toulouse", "Pilgrim", "Steinbacher"]
```

For example:

```js
filterGeese(["Mallard", "Hook Bill", "African", "Crested", "Pilgrim", "Toulouse", "Blue Swedish"])
=> ["Mallard", "Hook Bill", "Crested", "Blue Swedish"]
```

---

## 2. capitalizeAll

Given a list of names, that can be in any case, return a list of names with proper capitalization.

```js
capitalizeAll(["joE", "jIM", "CinDY"]) => ["Joe", "Jim", "Cindy"]
```

---

## 3. getInitials

Given a list of name objects, return their names with only the initials in the following format:

```js
getInitials([ { first: "Bob",  last: "Michaels"}, { first: "Sam", last: "Fritz" }, { first: "Dan", last: "Kustin"} ])
=> ["B. M.", "S. F.", "D.K."]
```

---

## 4. shortNamesOnly

Write a function called `shortNamesOnly` that takes an array of names and returns a new array containing only the names that are fewer than 7 characters long.

```js
shortNamesOnly(["Maya", "Christopher", "Jordan", "Zoe"]) => ["Maya", "Jordan", "Zoe"]
```

---

## 5. isDName

Write a function called isDName that takes an array of names as an argument and returns all of the names that start with the letter "D".

```js
isDName(["Diana", "Marcus", "William", "Danny", "Dominic"]) => ["Diana", "Danny", "Dominic"]
```

---

## 6. containsLowercase

Write a function called `containsLowercase` that takes an array of strings as an argument and returns all of the strings that contain at least one lower case character You can assume you will only be given non-symbol/non-numeric strings as input.

```js
containsLowercase(["HELLO", "Hello", "I Love JavaScript") => ["Hello", "I Love JavaScript"]

```

---

## 7. totalAdultAges

Write a function called `totalAdultAges` that takes an array of ages and returns the sum of all ages that are 18 or older.

```js
totalAdultAges([12, 25, 17, 30, 16, 21]) => 76
```

---

## 8. doubledEvenNumbers

Write a function called `doubledEvenNumbers` that takes an array of numbers and returns a new array containing only the even numbers, with each one doubled.

```js
doubledEvenNumbers([1, 2, 3, 4, 5, 6]) => [4, 8, 12]
```

---

## 9. totalCharacters

Write a function called `totalCharacters` that takes an array of strings and returns the total number of characters across all strings.

```js
totalCharacters(["cat", "hello", "JS"]) => 10
```

---

## 10. highValueOrdersTotal

Write a function that takes an array of order objects and returns the total amount of all orders that are $50 or more.

Each object has this shape:

```js
{ id: number, customer: string, total: number }
```

```js
highValueOrdersTotal([
  { id: 1, customer: "Maya", total: 120 },
  { id: 2, customer: "John", total: 35 },
  { id: 3, customer: "Sara", total: 75 },
  { id: 4, customer: "Leo", total: 50 }
]) => 245
```

---

## 11. discountedHighValueOrders

Write a function that takes an array of order objects and returns the total revenue after applying a 10% discount only to orders that are $100 or more.

Each object has this shape:

```js
{ id: number, customer: string, total: number }
```

```js
discountedHighValueOrders([
  { id: 1, customer: "Maya", total: 120 },
  { id: 2, customer: "John", total: 40 },
  { id: 3, customer: "Sara", total: 200 },
  { id: 4, customer: "Leo", total: 90 }
]) => 418
```

---
