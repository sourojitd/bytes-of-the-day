# Dev Tips (Mondays)

## 2017-10-30 (Monday)

### Dev Tips
**Code Review Best Practices** — Focus on logic and design over style, provide constructive feedback, and check for security vulnerabilities. Use automated tools for formatting and basic checks.

https://google.github.io/eng-practices/review/

---

## 2017-11-06 (Monday)

### Dev Tips
**Idempotent APIs** — Ensure that your API endpoints are idempotent, especially for write operations. Making the same call multiple times should produce the same result as making it once. This is critical for reliable distributed systems.

https://developer.mozilla.org/en-US/docs/Glossary/Idempotent

---

## 2017-11-13 (Monday)

### Dev Tips
**Semantic Versioning (SemVer)** — Adopt Semantic Versioning for your projects. Given a version number MAJOR.MINOR.PATCH, increment the: MAJOR version for incompatible API changes, MINOR version for backward-compatible functionality, and PATCH version for backward-compatible bug fixes.

https://semver.org/

---

## 2017-11-20 (Monday)

### Dev Tips
**Use Environment Variables for Configuration** — Never hardcode configuration like database credentials or API keys in your code. Use environment variables to manage configuration for different environments (development, staging, production).

https://12factor.net/config

---

