#Docker-Environment

This is an environment for working with symfony.


###How to use

Default nginx .conf need a folder 'App', which can by link to your symfony project root.

Also you can add a own *.conf for more project set in this case 'server_name'.


###Importend, when using ELK
A minimum of 3GB RAM assigned to Docker.
Elasticsearch alone needs at least 2GB of RAM to run.
A limit on mmap counts equal to 262,144 or more

[Source](http://elk-docker.readthedocs.io/#prerequisites)

###Contact

bugs@freedmo.de

##todo
- [x] add ELK
- [ ] add symfony logs to ELK
- [ ] create basic install file for symfony
- [ ] add php config file
