1. run `mkdir consensus execution`

2. Generate a jwt and move it to `./jwt`
```openssl rand -hex 32 | tr -d "\n" > "jwt.hex"```

3. run `docker compose up`