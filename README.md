# ptero-compose 🔥

Pterodactyl Panel & Wings (v1+) setup with docker compose

## Installation

First, git clone the repository.

```bash
git clone https://github.com/creepinson/ptero-compose
cd ptero-compose
cp .env.example .env
```

Next, change the various .env parameters to fit your environment.
Then, run `./start.sh` to run the panel.

Now you can create your first user for the panel:

```
docker-compose exec panel php artisan p:user:make
```

Now, head to your app url to login (eg. `http://localhost:8448`).
