# default-under-construction

A minimal SvelteKit placeholder site that shows an “Under Construction” page. Dark/light mode follows the system theme.

## Stack

- **SvelteKit 2** + **Svelte 5** (runes)
- **Tailwind CSS** · **Lucide Svelte** icons
- **adapter-node** for Docker / Node hosting

## Local development

```bash
pnpm install
pnpm dev
```

Open [http://localhost:5173](http://localhost:5173).

```bash
pnpm build
pnpm preview
```

## Docker

```bash
docker compose up --build
```

App is served on [http://localhost:3000](http://localhost:3000).

## Environment

Copy `.env.example` to `.env` and set `DOMAIN` (and optional Traefik vars) for use with `docker compose`. The compose file includes Traefik labels for routing and TLS.
