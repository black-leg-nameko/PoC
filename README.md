# Vulnerability PoC Collection

This repository contains a collection of vulnerability PoCs for educational and research purposes.

| PoC | Vulnerability | Tech Stack | Directory |
|-----|---------------|------------|-----------|
| SQLi (Basic) | SQL Injection | PHP + SQLite | [poc-sqli-basic](./poc-sqli-basic) |
| Stored XSS | Cross-Site Scripting | Node.js + Express | [poc-xss-stored](./poc-xss-stored) |
| CSRF (No Token) | CSRF | Flask | [poc-csrf-token-missing](./poc-csrf-token-missing) |

## Usage

Each PoC is self-contained. Go to the respective directory and run:

```bash
docker-compose up --build
```


! For educational use only. Do not deploy these systems in production.
