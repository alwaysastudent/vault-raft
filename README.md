# Vault test with raft storage

PoC of vault with raft storage.

# build
Run in this directory:
```
docker-compose build
```

# Start
Run in this directory:
```
docker-compose up -d
```

# view TOKENS
Run in this direcoty:
```
docker-compose logs|grep TOKEN
```
output
```
vault0_1  | [INFO] VAULT ROOT TOKEN: s.fOCUAwUjp6Tdh3NtPgKAa0MY
vault0_1  | [INFO] VAULT UNSEAL TOKEN: HT0rgLmbDD2hEbbIUJWbInMavR7rtLXgXui3baB4lms=
```

# Destroy
Run in this directory:
```
docker-compose down
```
