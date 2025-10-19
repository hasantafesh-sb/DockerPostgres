# PostgreSQL + Redis Docker Setup

Simple Docker setup for PostgreSQL and Redis databases.

## Environment Variables

Create a `.env` file in the project root with these variables:

- POSTGRES_USER=postgres
- POSTGRES_PASSWORD=password
- POSTGRES_DB=database

## Quick Start

1. **Start the services**:
   ```bash
   docker-compose up -d
   ```

2. **Check status**:
   ```bash
   docker-compose ps
   ```

## Connection Details

- **PostgreSQL**: localhost:5432
- **Redis**: localhost:6379

## Basic Commands

```bash
# Start services
docker-compose up -d

# Stop services
docker-compose down

# View logs
docker-compose logs

# Connect to PostgreSQL
docker-compose exec postgres psql -U postgres -d myapp

# Connect to Redis
docker-compose exec redis redis-cli
```
