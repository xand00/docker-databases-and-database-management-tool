# Backend services
1. Adminer
2. Postgres
3. Mysql

## Installation

1. Copy .env.example to .env
2. Configure .env
3. Execute command
```bash
docker-compose -f docker-compose.yml -f docker-compose.postgres.yml -f docker-compose.mysql.yml up -d
```