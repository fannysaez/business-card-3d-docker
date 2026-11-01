# Business Card 3D — Configuration Docker

Configuration Docker pour le frontend du projet [Business Card 3D](https://github.com/fannysaez/business-card-3d-frontend).

## Contenu

- `Dockerfile` — multi-stage (dev avec hot-reload, prod avec build Next.js standalone)
- `docker-compose.yml` — lance le frontend en mode développement

## Utilisation

Ce dépôt doit être placé **à côté** de `business-card-3d-frontend` :

```
business-card-3d/
├── business-card-3d-frontend/
└── business-card-3d-docker/
```

```bash
docker compose up --build
```

Ouvrir [http://localhost:3000](http://localhost:3000).

## Auteur

**Fanny Saez** — [GitHub](https://github.com/fannysaez) · [LinkedIn](https://www.linkedin.com/in/fannysaez/)