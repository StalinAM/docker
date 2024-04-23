# Docker

## Comandos

- `docker images`: Listado completo de todas las imagenes que hemos descargado
- `docker pull 'imagen'` - Extraer una imagen de un registro.
- `docker image rm 'imagen'` - Eliminar imagen.
- `docker create mongo` - Crear un contenedor.
- `docker start 'id'` - Iniciar contenedor.
- `docker ps` - Verificar si se esta ejecutando el contenedor.
- `docker stop 'id'` - Detener ejecucion del contenedor.
- `docker ps -a` - Ver todos los contenedores.
- `docker create --name 'nombre' 'imagen'` - Crear un contenedor con un nombre especifico.
- `docker create -p'puerto-maquina-fisica':'puerto-mapear' --name 'nombre' 'imagen'` - Crear un contenedor con un puerto mapeado.
- `docker logs --follow 'name'` - Verificar si se ejecuto de manera correcta.
- `docker run 'imagen'` - Forma mas rapida para descargar la imagen, crear el contenedor e iniciar.
- `docker run -d 'imagen'` - Forma mas rapido pero sin mostrar los logs.

## Dockerizar un proyecto

- Crear un archivo con el nombre `Dockerfile` en la raiz del proyecto.
- `FROM`
