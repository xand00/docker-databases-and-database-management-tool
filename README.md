# Backend services
1.Adminer: last version

2.Postgres: 14

## Installation

1. Copy .env.example to .env
2. Configure .env
3. Execute command
```bash
docker-compose build --build-arg UID=$(id -u) --build-arg GID=$(id -g)
```