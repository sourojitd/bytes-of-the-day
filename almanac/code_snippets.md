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

