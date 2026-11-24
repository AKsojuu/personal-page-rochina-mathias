PERSONAL PAGE

Práctica de despliegue de una página web en una máquina virtual de Azure con Nginx.

AUTOR
Mathias Rochina
Tecnología Superior en Desarrollo de Software
Universidad Tecnológica Equinoccial (UTE)

DESCRIPCIÓN
Es una página personal hecha con HTML y CSS. Tiene un menú, una sección principal, logos de empresas, una sección de por qué elegirnos, el equipo y un footer con formulario de suscripción y enlaces.

ARCHIVOS
- index.html: la estructura de la página
- styles.css: los estilos de la página
- README.md y README.txt: la descripción del proyecto

CÓMO SE VE EN LOCAL
1. Clonar el repositorio
2. Dejar index.html y styles.css en la misma carpeta
3. Abrir index.html en el navegador

DESPLIEGUE EN EL SERVIDOR
1. Conectarse a la máquina virtual de Azure por la terminal
2. Instalar Nginx
3. Clonar este repositorio en /var/www
4. Editar el archivo default en /etc/nginx/sites-available y cambiar la línea root a la carpeta del proyecto, por ejemplo /var/www/personal-page
5. Reiniciar Nginx con sudo systemctl restart nginx
6. Abrir la IP pública de la máquina virtual en el navegador

TECNOLOGÍAS
- HTML
- CSS
- Git y GitHub
- Nginx
- Azure
