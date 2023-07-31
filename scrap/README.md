## Scrap

This repository handle the image built of PostgresSQL and RabbitMQ

The following microservices are integrated with postgres and RabbitMQ
1. [Scrap Scrapy](https://github.com/guimassoqueto/scrap-scrapy)
2. [Scrap Colly](https://github.com/guimassoqueto/scrap-colly)
3. [Scrap Puppet](https://github.com/guimassoqueto/scrap-puppet)
4. [Scrap Flask](https://github.com/guimassoqueto/scrap-flask)

1. create .env
```shell
make env
```

2. Add your gittoken inside the .env variable `MIGRATIONS_PATH`

3. build the containers
```shell
make up
```