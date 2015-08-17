*****
Redis
*****

Instalación de redis_ 

**********
Requisitos
**********

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

*********
Variables
*********

::

	---
	# defaults file for redis
	redis_conexiones_remotas: false  # Verdadero para permitir que el servidor redis reciba conexiones remotas (por defecto false)

************
Dependencias
************

N/A

*******************
Ejemplo de playbook
*******************

::

    - hosts: servers
      roles:
         - { role: alkher.redis }

********
Licencia
********

BSD

*****
Autor
*****

Andoni Alcalde
- @alkher
- http://zenway.es
- alcher [at] zenway [dot] es


.. _redis: http://redis.io/