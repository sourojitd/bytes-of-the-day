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

