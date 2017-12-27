# Code Snippets (Wednesdays)

## 2017-11-01 (Wednesday)

### Code Snippet
**Fail-Fast Timeouts**

```java
HttpClient client = HttpClient.newBuilder()
    .connectTimeout(Duration.ofSeconds(3))
    .build();
// Wrap calls with CompletableFuture.orTimeout for per-request caps
```
Short timeouts + retries help avoid thread starvation.

---

## 2017-11-08 (Wednesday)

### Code Snippet
**List Comprehensions**

```python
squares = [x*x for x in range(10)]
# A concise way to create lists based on existing lists.
```
List comprehensions offer a shorter syntax when you want to create a new list based on the values of an existing list.

---

## 2017-11-15 (Wednesday)

### Code Snippet
**Snippet (JavaScript): ES6 Arrow Functions**

```javascript
const add = (a, b) => a + b;
// A more concise syntax for writing function expressions.
// Arrow functions also lexically bind the `this` value.
```

---

## 2017-11-22 (Wednesday)

### Code Snippet
**Snippet (SQL): Common Table Expressions (CTEs)**

```sql
WITH RegionalSales AS (
  SELECT region, SUM(amount) AS total_sales
  FROM orders
  GROUP BY region
)
SELECT region, total_sales
FROM RegionalSales
WHERE total_sales > 1000;
```
CTEs help break down complex queries into simple, readable steps.

---

## 2017-11-29 (Wednesday)

### Code Snippet
**Using the Stream API**

```java
List<String> strings = Arrays.asList("a", "b", "c", "");
long count = strings.stream().filter(String::isEmpty).count();
// The Stream API provides a functional approach to processing collections of objects.
```

---

## 2017-12-06 (Wednesday)

### Code Snippet
**Dictionaries**

```python
# Creating and accessing a dictionary
person = {'name': 'Alice', 'age': 30}
print(person['name'])  # Outputs: Alice

# Safely get a value with .get()
print(person.get('city', 'Unknown')) # Outputs: Unknown
```
Dictionaries are a fundamental data structure for key-value storage.

---

## 2017-12-13 (Wednesday)

### Code Snippet
**Snippet (JavaScript): `let` and `const`**

```javascript
let count = 0; // block-scoped, can be reassigned
const PI = 3.14; // block-scoped, cannot be reassigned

// Prefer const by default, and use let only when you need to reassign a variable.
```
ES6 introduced `let` and `const` for block-scoped variables, largely replacing `var`.

---

## 2017-12-20 (Wednesday)

### Code Snippet
**The `requests` Library**

```python
import requests

response = requests.get('[https://api.github.com](https://api.github.com)')
if response.status_code == 200:
    print('Success!')
    print(response.json())
```
The `requests` library is the de facto standard for making HTTP requests in Python.

---

## 2017-12-27 (Wednesday)

### Code Snippet
**Snippet (JavaScript): Destructuring Assignment**

```javascript
const person = { name: 'Bob', age: 42 };
const { name, age } = person;

console.log(name); // 'Bob'
console.log(age); // 42
```
Destructuring makes it easy to extract properties from objects or items from arrays into distinct variables.

---

