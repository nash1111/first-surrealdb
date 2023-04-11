start surrealdb with user=root, password=root
```
docker run --rm --pull always -p 8000:8000 surrealdb/surrealdb:latest start --user root --pass root
```

run main.rs
```
cargo run
```

[Detail](https://surrealdb.com/docs/integration/libraries/rust)