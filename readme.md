
# Lounge/Tor-Proxy Setup


# Setup for this repo

NOTE: I am running this image behind nginx reverse proxy, so after generation of config.json, 
set => reverseProxy: true
set => public: false

Bringing up entire stack

```bash
docker compose up -d
```

Creating a user in the lounge

```bash
docker exec -it thelounge s6-setuidgid abc thelounge add smk

```
