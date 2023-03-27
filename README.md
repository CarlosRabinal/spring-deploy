## Despliegue de apps Spring Boot en Heroku

Crear archivo 'system.properties' en el proyecto con el contenido_

...
java.runtime.version=19
....

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador (ejecutar únicamente la primera vez que se instala git)
    1. git config --global user.name "carlos.rabinal"
    2. git config --global user.email carlos.rabinal@atos.net
3. Subir el proyecto a GitHub desde IntelliJ IDEA desde la opción: VCS > Share project on GitHub
4. Desde Heroku, crear app y elegir método GitHub y buscar el repositorio subido
5. Habilitar deploy automático y ejecutar el Deploy

##Ejercicio 1

* Probar a empaquetar la aplicación con maven package desde IntelliJ IDEA
* Desde terminal en IntelliJ IDEA verificar que se ejecuta correctamente con el comando:

...
java -jar target/spring-deploy-0.0.1-SNAPSHOT.jar
...

* Crear un perfil para dev y otro para test con una propiedad nueva que carguemos en el controlador.

## Ejercicio 2

Desplegar el API REST de Laptops en Heroku y verificar funcionamiento desde POSTMAN.

## Proveedores Cloud
* Heroku -- Java, Spring, PostgreSQL
* Netlify -- Fronted (React, Angular...)
* Vercel -- Fronted (React, Angular...)