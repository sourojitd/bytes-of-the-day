# Code Snippets (Wednesdays)

## 2018-01-03 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2018-01-10 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2018-01-17 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2018-01-24 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining**

```javascript
const city = user?.address?.city;
```

---

## 2018-01-31 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2018-02-07 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2018-02-14 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2018-02-21 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2018-02-28 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2018-03-07 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2018-03-14 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [073]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

