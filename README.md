# Personal Page

Práctica de despliegue de una página web en una máquina virtual de Azure con Nginx.

## Autor

Mathias Rochina
Tecnología Superior en Desarrollo de Software
Universidad Tecnológica Equinoccial (UTE)

## Descripción

Es una página personal hecha con HTML y CSS. Tiene un menú, una sección principal, logos de empresas, una sección de por qué elegirnos, el equipo y un footer con formulario de suscripción y enlaces.

## Archivos

- index.html: la estructura de la página
- styles.css: los estilos de la página
- README.md y README.txt: la descripción del proyecto

## Cómo se ve en local

1. Clonar el repositorio
2. Dejar index.html y styles.css en la misma carpeta
3. Abrir index.html en el navegador

## Despliegue en el servidor

1. Conectarse a la máquina virtual de Azure por la terminal
2. Instalar Nginx
3. Clonar este repositorio en /var/www
4. Editar el archivo default en /etc/nginx/sites-available y cambiar la línea root a la carpeta del proyecto, por ejemplo /var/www/personal-page
5. Reiniciar Nginx con sudo systemctl restart nginx
6. Abrir la IP pública de la máquina virtual en el navegador

## Tecnologías

- HTML
- CSS
- Git y GitHub
- Nginx
- Azure
# personal-page-rochina-mathias
