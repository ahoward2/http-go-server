# Dirt simple go http server

Serves static files and a json route.

## How to run

Must have go >= v1.18 installed.

```bash
go run server.go
```

- GET `/` route servers static files (frontend)
- GET `/hello` route returns a json payload
