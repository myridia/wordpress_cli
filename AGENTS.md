# AGENTS.md — wordpress_cli

## What this is
A Docker wrapper over the official WordPress CLI image, adding rsync and PHP Composer tools for WordPress management.

## Stack
- Docker
- WP-CLI
- rsync
- PHP Composer

## Build
```bash
docker build -t wordpress_cli .
```

## Run
```bash
docker run --rm -it wordpress_cli wp <command>
```

## Structure
- `Dockerfile` — image build definition

## Conventions
- No comments in code unless asked.
- Verify: `docker build .`
