# Link checks

Unauthenticated HTTP retrieval on October 29, 2026. Redirect destination query strings are omitted.

| Result | URLs |
| --- | --- |
| HTTP error; review link | 2 |
| TLS verification failed; unverified | 4 |
| access restricted or rate limited; unverified | 32 |
| network lookup or timeout; unverified | 8 |
| reachable | 369 |
| redirected to personal site; directory purpose unverified | 1 |
| redirected to survey-moved notice; submission route unverified | 1 |

HTTP 200 means a page responded. It can still be a login, moved notice, retired program or unrelated site. HTTP 403/429 and network/TLS failures do not establish that a service is closed. No TLS verification was disabled.

[Complete results](data/link-checks.csv)
