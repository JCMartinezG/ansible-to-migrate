DESPLIEGUE DE APLICACIONES USANDO ANSIBLE
-------------------------------------------
Si hubiese logrado configurar todo de manera exitosa, el despliegue se harìa con la instruccion siguiente, entrando a ansible-to-migrate:

        ansible-playbook -i hosts site.yml 
        

Tuve algunos inconvenientes, entre ellos la conexion con el SSH, fue el factor principal que me impidió correr todo,
al principio me funcionó cuando utilizaba el comando:

# ssh root@server01 -p 2221 -i ./key.private

luego no me funcionò. Apliqué los permisos de manera exitosa mediante chmod a-rwx ./key.private y u+rw ./key.private
pero al final no arrancó. Reinstalé el docker, eliminé todos los contenedores, hice todo de nuevo.

Algo que destaco fue que sentí que aunque poco he aprendido en el curso, identifiqué mediante investigaciones 
los cambios que hay que realizar para migrar un servicio a otro sistama operativo, en este caso:
#CentOS a UBUNTU
E identificar las variables que hay que modificar.

Como estudiante de Tecnologia En Sistemas siento que el curso tiene grandes retos, y creo que se pueden superar.


