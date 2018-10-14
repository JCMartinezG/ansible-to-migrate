Building a simple LAMP stack and deploying Application using Ansible Playbooks.
-------------------------------------------
Si hubiese logrado configurar todo de manera exitosa, el despliegue se harìa con la instruccion:

        ansible-playbook -i hosts site.yml

Tuve algunos inconvenientes, entre ellos la conexion con el SSH, fue el factor principal que me impidió correr todo,
al principio me funcionó cuando utilizaba el comando:

# ssh root@server01 -p 2221 -i ../key.private

luego no me funcionò.

Algo que destaco fue que sentí que aunque poco he aprendido en el curso, identifiqué mediante investigaciones 
los cambios que hay que realizar para migrar un servicio a otro sistama operativo, en este caso:
#CentOS a UBUNTU
E identificar las variables que hay que modificar.


