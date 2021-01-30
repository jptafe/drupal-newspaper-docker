# drupal-newspaper-docker



###To install and run this:
```
composer install
docker-compose up
```

###prior to committal of changes to repo after update or reconfiguration:
```
rm -rf web/core
rm -rf vendor
mysqldump -u root drupal > sql/example_drupal_9.sql
```

[![Try in PWD](https://raw.githubusercontent.com/play-with-docker/stacks/master/assets/images/button.png)](https://labs.play-with-docker.com/?stack=https://raw.githubusercontent.com/jptafe/drupal-newspaper-docker/master/docker-compose.yml)
