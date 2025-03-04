## Ejercicio API Cine

> Tenemos un cine y queremos modernizarnos. Queremos que la información de la cartelera y las sesiones esté accesible. Actualmente está disponible en nuestra página web, pero queremos que otras aplicaciones puedan trabajar con esa información de forma sencilla obteniéndola de nuestro servicio web para conseguir visibilidad. Aprovechando esta oportunidad queremos también utilizar este sistema para poder trabajar nosotros él. ¿Nos podrías ayudar?

**Peliculas**

| Método          |      Ruta                       |    Información
| --------------- |     -----------                 |    -----------
| GET             |     /peliculas                  |     Lista de peliculas
| GET             |     /peliculas/:id/             |     Información de una pelicula especifica
| GET             |     /peliculas/:id/sesiones     |     Sesiones de una pelicula especifica
| POST            |     /peliculas                  |     Crear una pelicula
| PUT             |     /peliculas/:id              |     Actualizar una pelicula especifica
| DELETE          |     /peliculas/:id              |     Eliminar una pelicula especifica

**Sesiones**

| Método          |      Ruta             |    Información
| --------------- |     -----------       |    -----------
| GET             |     /sesiones         |     Lista de sesiones
| GET             |     /sesiones/:id     |     Información de una sesión especifica
| POST            |     /sesiones         |     Crear una sesión
| PUT             |     /sesiones/:id     |     Actualizar una sesión especifica
| DELETE          |     /sesiones/:id     |     Eliminar una sesión especifica
