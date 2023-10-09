# Symfony 7.0

## Docker
**Services** from https://github.com/cosminsandu/my_docker + PHP 8.2 (required by Symfony 7.0):
- web server (nginx) [localhost](http://localhost/)
- app (PHP 8.2 & composer & symfony CLI)
- database (mysql 8.0)
- cache (redis) -  OPTIONAL - commented
- debug (xdebug) - requires [this chrome extension](https://chrome.google.com/webstore/detail/xdebug-helper/eadndfjplgieldjbigjakmdgkmoaaaoc)

**Commands**
```bash
docker compose up -d  # compose/create the container(s) in detatch mode
docker compose ps   # List services
docker exec -it symfony70-app-1 bash
```