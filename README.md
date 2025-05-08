# Apothéose App – Environnement de Développement 3-Tiers

## 📦 Contenu du repo
- `frontend/` : Vue.js avec Vite (client)
- `wordpress/` : Backend headless WordPress
- `docker-compose.yml` : Stack locale 3-tiers (front + WP + MySQL + phpMyAdmin)
- `.env` : Configuration MySQL
- `phpMyAdmin` : Accessible sur `http://localhost:8081`

## 🚀 Démarrage rapide
```bash
cp .env.example .env
docker compose up --build