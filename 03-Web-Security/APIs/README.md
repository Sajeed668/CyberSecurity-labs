# APIs

## Objective

Understand how web applications expose and consume APIs and how HTTP requests carry API data.

## Concepts

- Endpoints
- HTTP methods
- Query parameters
- Request bodies
- JSON
- Response status codes
- Authentication headers

## Python Practice

```python
import requests

response = requests.get("https://example.com")
print(response.status_code)
```

## VAPT Relevance

API testing can reveal authorization, input-validation and authentication weaknesses when performed against authorized applications.