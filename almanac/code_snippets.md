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

## 2018-03-21 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [080]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2018-03-28 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [087]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2018-04-04 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [094]**

```javascript
const city = user?.address?.city;
```

---

## 2018-04-11 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [101]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2018-04-18 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [108]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2018-04-25 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [115]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2018-05-02 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [122]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2018-05-09 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [129]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2018-05-16 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [136]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2018-05-23 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [143]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2018-05-30 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [150]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2018-06-06 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [157]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2018-06-13 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [164]**

```javascript
const city = user?.address?.city;
```

---

## 2018-06-20 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [171]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2018-06-27 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [178]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2018-07-04 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [185]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2018-07-11 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [192]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2018-07-18 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [199]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2018-07-25 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [206]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2018-08-01 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [213]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2018-08-08 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [220]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2018-08-15 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [227]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2018-08-22 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [234]**

```javascript
const city = user?.address?.city;
```

---

## 2018-08-29 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [241]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2018-09-05 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [248]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2018-09-12 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [255]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2018-09-19 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [262]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2018-09-26 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [269]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2018-10-03 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [276]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2018-10-10 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [283]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2018-10-17 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [290]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2018-10-24 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [297]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2018-10-31 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [304]**

```javascript
const city = user?.address?.city;
```

---

## 2018-11-07 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [311]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2018-11-14 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [318]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2018-11-21 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [325]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2018-11-28 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [332]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2018-12-05 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [339]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2018-12-12 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [346]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2018-12-19 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [353]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2018-12-26 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [360]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2019-01-02 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2019-01-09 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2019-01-16 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2019-01-23 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining**

```javascript
const city = user?.address?.city;
```

---

## 2019-01-30 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2019-02-06 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2019-02-13 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2019-02-20 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2019-02-27 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2019-03-06 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2019-03-13 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [072]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2019-03-20 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [079]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2019-03-27 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [086]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2019-04-03 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [093]**

```javascript
const city = user?.address?.city;
```

---

## 2019-04-10 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [100]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2019-04-17 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [107]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2019-04-24 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [114]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2019-05-01 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [121]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2019-05-08 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [128]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2019-05-15 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [135]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2019-05-22 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [142]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2019-05-29 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [149]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2019-06-05 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [156]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2019-06-12 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [163]**

```javascript
const city = user?.address?.city;
```

---

## 2019-06-19 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [170]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2019-06-26 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [177]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2019-07-03 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [184]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

