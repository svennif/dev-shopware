# Clerk Shopware 6

> This is for development only

[Link to Dockware / Shopware setup](https://developer.shopware.com/docs/guides/installation/community/dockware.html)

## Start the Docker container
```bash
docker-compose up -d
```
## Prepare development
```bash
mkdir -p ./src
docker cp shopware:/var/www/html/. ./src
```

After running the snippets above you should be able to access the website from `localhost` 