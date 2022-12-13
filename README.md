![GitHub](https://img.shields.io/github/license/albertguedes/mysql-alpine-docker) ![GitHub last commit](https://img.shields.io/github/last-commit/albertguedes/mysql-alpine-docker) ![GitHub language count](https://img.shields.io/github/languages/count/albertguedes/mysql-alpine-docker)

# MySQL Alpine Docker

Docker compose structure to create a image of a MySQL 5.7 server with Alpine 3.8 
system as base.

We known that exists a official docker to MySQL by the Oracle, but the problem 
is that this image use Ubuntu as base system, whats turn the size of the image 
an inconvenient to small projects or a project that uses many instances of 
databases.

We use MariaDB 10.2 package that is equivalent to the MySQL 5.7 because 
aren't Alpine's package to MySQL from Oracle.


## References

- This project is based on repository of Akai-Z images: 
[https://github.com/akai-z/docker-alpine-mariadb](https://github.com/akai-z/docker-alpine-mariadb)
- Docker Documentation: [https://docs.docker.com/](https://docs.docker.com/)
- Alpine OS Image: [https://hub.docker.com/_/alpine](https://hub.docker.com/_/alpine)
