```bash
docker network create frontend
```

```bash
3b4e35ad8026   frontend  bridge    local
```

any changes to the static config(`config/traefik.yml`) file will require a restart of the container

```bash
docker compose up -d
```
