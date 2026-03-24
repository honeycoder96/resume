# Resume

HTML resume for Honey Sharma, served via nginx in a Docker container and deployed on Dokploy.

## Stack

- Plain HTML/CSS — no build step
- nginx:alpine — serves `index.html`
- Deployed via Dokploy with Docker Compose

## Local preview

Open `index.html` directly in a browser, or run with Docker:

```bash
docker compose up --build
```

Then visit `http://localhost`.

## Deployment

Deployed on Dokploy. To update:

1. Edit `index.html`
2. Commit and push to `main`
3. Trigger a redeploy in Dokploy
