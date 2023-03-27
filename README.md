## Despliegue de apps Spring Boot en Heroku

Crear archivo 'system.properties' en el proyecto con el contenido_

...
java.runtime.version=19
....

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador
    1. git config --global user.name "CarlosRabinal"
    2. git config --global user.email carlos.rabinal@atos.net
3. Subir el proyecto a GitHub desde IntelliJ IDEA desde la opción: VCS > Share project on GitHub
4. Desde Heroku, crear app y elegir método GitHub y buscar el repositorio subido
5. Habilitar deploy automático y ejecutar el Deploy