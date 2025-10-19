# Docker Setup

```bash
# Start services
docker compose up -d

# Stop services
docker compose down
```

## Connection Details

- **PostgreSQL**: localhost:5432
- **Redis**: localhost:6379

## Commands

```bash
# Connect to PostgreSQL
docker compose exec postgres psql -U postgres -d myapp

# Connect to Redis
docker compose exec redis redis-cli

# View logs
docker compose logs
```
