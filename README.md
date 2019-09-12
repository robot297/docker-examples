# Docker Examples

Some basic examples on how to use Docker.

## Apache folder

This example showcases how you can build a simple website using apache.

* `cd apache`
* `docker build .` or `docker build . -t <imageName>` when you're ready to "tag"
* `docker run --name <canbewhateveryouwant> --rm -d -p 80:80 <imageName>`

## Drupal folder

* `cd drupal`
* `docker-compose up -d` - This will "deploy" your containers on your machine and build your infrastructure
* `docker-compose down` - This will tear down all your apps.