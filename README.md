# Funkwhale

A self-hosted funkwhale application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/funkwhale/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/funkwhale" ~/.local/srv/docker/funkwhale
cd ~/.local/srv/docker/funkwhale
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install funkwhale
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
