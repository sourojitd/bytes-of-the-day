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

