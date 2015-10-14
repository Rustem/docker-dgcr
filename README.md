Keep-in-touch local
-------------------

Dockerfiles that facilitates in deployment the following stack:
   - Django
   - Gevent
   - RabbitMQ
   - Cassandra

Designed to be used with Docker Compose, it will make things a lot easier.


Images Info
-----------

* base - Ubuntu 14.04 with commonly used packages for Django/Gevent/Python development.
* rabbitmq - RabbitMQ message brocker 3.2.4
* cassandra - Cassandra >= 2.2 database
* gevent - gevent application. Special port is exposed to be used and contains a few additional packages
* django - the same as gevent with respect to Django

