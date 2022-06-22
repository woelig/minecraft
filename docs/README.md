# Start

```bash
docker-compose up -d
```

# Stop

```bash
docker-compose down
```

# View Logs

```bash
docker-compose logs -f
```

# Upgrade

```bash
docker-compose down
docker-compose pull
docker-compose up -d
```

# CLI Access

```bash
docker exec -i mc rcon-cli --port 25575 --password yourverysecurepassword
```

