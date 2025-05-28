# My App

Setup of the all my app modules and submodules with Docker.

## Installation steps

1. Clone this repo with the submodules.

```bash
git clone --recursive git@github.com:RufenDev/my-app.git
```

*If you already cloned the repository without `--recursive`, use this:*

```bash
git submodule update --init --recursive
```

2. Get the `.env`.

3. Run `docker-compose`.

### Dev mode

```bash
docker compose -f docker-compose-dev.yml up --build
```

### Prod mode

```bash
docker compose -f docker-compose.yml up --build
```
