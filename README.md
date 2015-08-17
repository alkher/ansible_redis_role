Redis
=====

Instalación de [redis](http://redis.io/) 

Requisitos
==========

Sistemas operativos soportados:

- CentOS 7 

Variables
=========

	---
	# defaults file for redis
	redis_conexiones_remotas: false  # Verdadero para permitir que el servidor redis reciba conexiones remotas (por defecto false)

Dependencias
============

Ninguna

Ejemplo de playbook
===================

    - hosts: servers
      roles:
         - { role: alkher.redis }

Licencia
========

BSD

Autor
=====

Andoni Alcalde
- @alkher
- http://zenway.es
- alcher [at] zenway [dot] es