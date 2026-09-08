# Error codes (draft)

| Status | Code | Meaning |
|---|---|---|
| 400 | invalid_request | A parameter is missing or out of range |
| 401 | invalid_token | The access token is missing, expired or revoked |
| 404 | not_found | The resource does not exist |
| 409 | edit_conflict | The recipe changed since it was read |
| 429 | rate_limited | Too many requests; see the retry-after header |
