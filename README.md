# faraday

> Click To Deploy Faraday CE — Open Source Vulnerability Management Platform

[![Sync](https://github.com/opensaasapps/faraday/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/faraday/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/faraday/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/faraday/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/faraday)](https://hub.docker.com/r/thefractionalpm/faraday)

Upstream: [infobyte/faraday](https://github.com/infobyte/faraday) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `POSTGRES_HOST` | ⚪ | |
| `POSTGRES_PORT` | ⚪ | |
| `POSTGRES_DB` | ⚪ | |
| `POSTGRES_USER` | ⚪ | |
| `POSTGRES_PASSWORD` | ✅ | |
| `PGSSLMODE` | ⚪ | |
| `CELERY_BROKER_URL` | ⚪ | |
| `CELERY_BACKEND_URL` | ⚪ | |
| `FARADAY_DISABLE_CHANGE_PASSWORD` | ⚪ | |

## Image

```
docker pull faradaysec/faraday:latest
docker pull thefractionalpm/faraday:latest
```

## Ports

| Port | Service |
|---|---|
| `5985` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
