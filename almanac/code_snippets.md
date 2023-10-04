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

## 2019-07-10 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [191]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2019-07-17 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [198]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2019-07-24 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [205]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2019-07-31 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [212]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2019-08-07 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [219]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2019-08-14 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [226]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2019-08-21 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [233]**

```javascript
const city = user?.address?.city;
```

---

## 2019-08-28 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [240]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2019-09-04 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [247]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2019-09-11 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [254]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2019-09-18 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [261]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2019-09-25 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [268]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2019-10-02 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [275]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2019-10-09 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [282]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2019-10-16 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [289]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2019-10-23 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [296]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2019-10-30 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [303]**

```javascript
const city = user?.address?.city;
```

---

## 2019-11-06 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [310]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2019-11-13 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [317]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2019-11-20 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [324]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2019-11-27 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [331]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2019-12-04 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [338]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2019-12-11 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [345]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2019-12-18 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [352]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2019-12-25 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [359]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2020-01-01 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-01-08 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-01-15 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-01-22 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-01-29 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-02-05 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-02-12 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-02-19 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-02-26 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-03-04 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-03-11 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-03-18 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-03-25 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-04-01 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-04-08 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-04-15 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-04-22 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-04-29 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-05-06 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-05-13 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-05-20 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-05-27 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-06-03 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-06-10 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-06-17 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-06-24 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-07-01 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-07-08 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-07-15 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-07-22 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-07-29 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-08-05 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-08-12 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-08-19 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-08-26 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-09-02 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-09-09 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-09-16 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-09-23 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-09-30 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-10-07 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-10-14 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-10-21 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-10-28 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-11-04 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-11-11 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-11-18 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-11-25 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-12-02 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-12-09 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-12-16 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-12-23 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2020-12-30 (Wednesday)

### Code Snippet (bash)
```bash
echo 'Hello from history-safe commit'
```

---

## 2021-01-06 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2021-01-13 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2021-01-20 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2021-01-27 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining**

```javascript
const city = user?.address?.city;
```

---

## 2021-02-03 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2021-02-10 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2021-02-17 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2021-02-24 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2021-03-03 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2021-03-10 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2021-03-17 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [076]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2021-03-24 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [083]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2021-03-31 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [090]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2021-04-07 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [097]**

```javascript
const city = user?.address?.city;
```

---

## 2021-04-14 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [104]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2021-04-21 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [111]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2021-04-28 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [118]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2021-05-05 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [125]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2021-05-12 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [132]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2021-05-19 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [139]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2021-05-26 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [146]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2021-06-02 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [153]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2021-06-09 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [160]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2021-06-16 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [167]**

```javascript
const city = user?.address?.city;
```

---

## 2021-06-23 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [174]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2021-06-30 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [181]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2021-07-07 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [188]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2021-07-14 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [195]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2021-07-21 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [202]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2021-07-28 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [209]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2021-08-04 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [216]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2021-08-11 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [223]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2021-08-18 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [230]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2021-08-25 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [237]**

```javascript
const city = user?.address?.city;
```

---

## 2021-09-01 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [244]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2021-09-08 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [251]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2021-09-15 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [258]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2021-09-22 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [265]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2021-09-29 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [272]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2021-10-06 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [279]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2021-10-13 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [286]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2021-10-20 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [293]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2021-10-27 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [300]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2021-11-03 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [307]**

```javascript
const city = user?.address?.city;
```

---

## 2021-11-10 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [314]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2021-11-17 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [321]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2021-11-24 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [328]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2021-12-01 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [335]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2021-12-08 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [342]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2021-12-15 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [349]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2021-12-22 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [356]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2021-12-29 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [363]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2022-01-05 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2022-01-12 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2022-01-19 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2022-01-26 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining**

```javascript
const city = user?.address?.city;
```

---

## 2022-02-02 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2022-02-09 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2022-02-16 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2022-02-23 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2022-03-02 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2022-03-09 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2022-03-16 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [075]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2022-03-23 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [082]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2022-03-30 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [089]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2022-04-06 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [096]**

```javascript
const city = user?.address?.city;
```

---

## 2022-04-13 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [103]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2022-04-20 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [110]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2022-04-27 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [117]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2022-05-04 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [124]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2022-05-11 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [131]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2022-05-18 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [138]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2022-05-25 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [145]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2022-06-01 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [152]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2022-06-08 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [159]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2022-06-15 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [166]**

```javascript
const city = user?.address?.city;
```

---

## 2022-06-22 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [173]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2022-06-29 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [180]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2022-07-06 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [187]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2022-07-13 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [194]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2022-07-20 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [201]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2022-07-27 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [208]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2022-08-03 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [215]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2022-08-10 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [222]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2022-08-17 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [229]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2022-08-24 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [236]**

```javascript
const city = user?.address?.city;
```

---

## 2022-08-31 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [243]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2022-09-07 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [250]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2022-09-14 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [257]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2022-09-21 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [264]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2022-09-28 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [271]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2022-10-05 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [278]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2022-10-12 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [285]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2022-10-19 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [292]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2022-10-26 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [299]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2022-11-02 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [306]**

```javascript
const city = user?.address?.city;
```

---

## 2022-11-09 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [313]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2022-11-16 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [320]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2022-11-23 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [327]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2022-11-30 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [334]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2022-12-07 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [341]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2022-12-14 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [348]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2022-12-21 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [355]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2022-12-28 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [362]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2023-01-04 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2023-01-11 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2023-01-18 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2023-01-25 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining**

```javascript
const city = user?.address?.city;
```

---

## 2023-02-01 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2023-02-08 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2023-02-15 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2023-02-22 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2023-03-01 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2023-03-08 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2023-03-15 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [074]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2023-03-22 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [081]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2023-03-29 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [088]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2023-04-05 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [095]**

```javascript
const city = user?.address?.city;
```

---

## 2023-04-12 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [102]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2023-04-19 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [109]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2023-04-26 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [116]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2023-05-03 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [123]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2023-05-10 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [130]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2023-05-17 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [137]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2023-05-24 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [144]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2023-05-31 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [151]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2023-06-07 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [158]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2023-06-14 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [165]**

```javascript
const city = user?.address?.city;
```

---

## 2023-06-21 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [172]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2023-06-28 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [179]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2023-07-05 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [186]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2023-07-12 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [193]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2023-07-19 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [200]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2023-07-26 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [207]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

## 2023-08-02 (Wednesday)

### Code Snippet
**Snippet (bash): Find slowest lines [214]**

```bash
time (your_cmd) 2>&1 | tail -n 3
```

---

## 2023-08-09 (Wednesday)

### Code Snippet
**Snippet (python): Dictionary comprehension [221]**

```python
squares = {x: x*x for x in range(10)}
```

---

## 2023-08-16 (Wednesday)

### Code Snippet
**Snippet (java): Streams to Map safely [228]**

```java
Map<String,User> m = users.stream()
 .collect(Collectors.toMap(User::id,u->u,(a,b)->a,LinkedHashMap::new));
```

---

## 2023-08-23 (Wednesday)

### Code Snippet
**Snippet (javascript): Optional chaining [235]**

```javascript
const city = user?.address?.city;
```

---

## 2023-08-30 (Wednesday)

### Code Snippet
**Snippet (sql): Detect duplicates [242]**

```sql
SELECT col, COUNT(*) c FROM t GROUP BY col HAVING c>1;
```

---

## 2023-09-06 (Wednesday)

### Code Snippet
**Snippet (bash): Retry with backoff [249]**

```bash
for i in {1..5}; do cmd && break; sleep $((2**i)); done
```

---

## 2023-09-13 (Wednesday)

### Code Snippet
**Snippet (python): Walrus operator [256]**

```python
if (n := len(items)) > 100:
    print(n)
```

---

## 2023-09-20 (Wednesday)

### Code Snippet
**Snippet (java): HTTP timeouts [263]**

```java
HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(3)).build();
```

---

## 2023-09-27 (Wednesday)

### Code Snippet
**Snippet (go): Context timeouts [270]**

```go
ctx, cancel := context.WithTimeout(ctx, 3*time.Second)
```

---

## 2023-10-04 (Wednesday)

### Code Snippet
**Snippet (javascript): Debounce [277]**

```javascript
const debounced = _.debounce(fn, 200);
```

---

