# Readme

# Init project

1. Run **docker-compose up -d --build** - instantiate containers
2. Run **docker exec -it sylius_dev sh** - get into container
3. Run **composer install**
4. Configure db mysql connection via DATABASE_URL env variable
5. Run **bin/console sylius:install**
