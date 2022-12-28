1. Generate a jwt and move it to `./jwt`
```openssl rand -hex 32 | tr -d "\n" > "jwt.hex"```

2. run `docker compose up`