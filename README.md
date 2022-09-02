# rosbot-test

## Available setups

### I

- on laptop:

```bash
docker compose -f compose.pc.yaml up
```

- on rosbot:

```
docker compose -f compose.rosbot.yaml -f compose.mapping.yaml up
```

### II

- on laptop:

```bash
docker compose -f compose.pc.yaml -f compose.mapping.yaml up
```

- on rosbot:

```
docker compose -f compose.rosbot.yaml up
```