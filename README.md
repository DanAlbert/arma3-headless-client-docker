# Arma 3 Headless Client

**This repository is no longer maintained.** See
https://github.com/mschabhuettl/arma3-hc-docker for an up-to-date version of
this.

Docker image for Arma 3 headless clients.

```bash
docker run -it danalbert/arma3-headless-client \
  -e STEAM_USER=$USER -e STEAM_PASS=$PASS \
  -e ARMA_HOST=$SERVER_ADDR -e ARMA_PORT=$SERVER_PORT -e ARMA_PASS=$SERVER_PASS
```
