#Docker-Environment

Local hosting with [Docker](https://www.docker.com/) environment with [NGINX](https://hub.docker.com/_/nginx/), [PHP](https://hub.docker.com/r/nicoorfi/php/), [MySQL](https://hub.docker.com/_/mysql/).

#### Default MySQL credentials
````
 root_password = root 
 user = db
 db_password= db
 ````
 
###How to use

Place your nginx .conf inside of './partials/nginx', your project or link to project root should be inside './www'.
~Default nginx .conf need a folder 'App', which can by link to your symfony project root.~

Also you can add a own *.conf for more project set in this case 'server_name'.

###Importend, when using ELK
A minimum of 3GB RAM assigned to Docker.
Elasticsearch alone needs at least 2GB of RAM to run.
A limit on mmap counts equal to 262,144 or more

[Source](http://elk-docker.readthedocs.io/#prerequisites)
 
### Elastic Search 
* Version: 1.7.3 
 
### PHP
* Version: 7.1.6

### MySQL
* Version: 5.7.18

### NGINX
* Version: 1.12.0 
* `/etc/nginx` is linked with the `./nginx/conf.d` folder.

##todo
- [x] add ELK
- [ ] add symfony logs to ELK
- [ ] create basic install file for symfony
- [ ] add php config file
