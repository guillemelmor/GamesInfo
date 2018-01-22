# GamesInfo
# Descripción de la web
Esta aplicación está dirigida a usuarios aficionados a los videojuegos. Será un web donde encontrar información acerca de videojuegos como la trama, la compañía, la puntuación pública y profesional, … Además, podrá ojear los eventos que se celebrarán próximamente y hacerse listas en su perfil con los juegos que le interesen.
- **Parte pública**: el usuario podrá navegar por las distintas entidades descritas más adelante.

- **Parte privada**: el usuario deberá iniciar sesión para poder puntuar, comentar los juegos u ojear sus listas. Gracias al servicio de correo electrónico estará al tanto de su juego o compañía favorita.

# Entidades principales
-   **Usuario**: se distinguirá entre usuario registrado, no registrado y administrador. Este portará un Id, un Correo, una Contraseña y otros datos menos relevantes.
-   **Juego**: Portará un Id, el Nombre, la Fecha de Salida, Descripción, Id compañía, Puntuación, Comentarios
-   **Compañía**: Información de la compañía encargada de desarrollar el juego ya sea indie o empresa grande. Contiene Id, País, Fecha de Fundación, Historia, …
-   **Comentario**: cada usuario podrá aportar su opinión sobre dicho juego. Este portará un Id, Cuerpo, IdUsuario, IdJuego
-   **Puntuación**: contendrá la puntuación del juego, tanto de los usuarios, como del sector profesional. Contendrá un Id, IdJuego, PuntuacionUsuarios, PuntuacionProfesional
-   **Persona**: Desarrollador, Artista o Ponente de evento. Relación N.M con juego y con evento. Portará un Id, Nombre, Nacionalidad, Profesión, …
-   **Evento**: Relación N:M con juego y persona. Contendrá un Id, Fecha, Lugar, Precio, Descripción…

# Servicio Interno
En todo momento el usuario estará al tanto de información nueva sobre cada juego, así como al tanto de los movimientos de una determinada compañía por medio del correo electrónico.

# Integrantes
Doble Grado Diseño y Desarrollo de Videojuegos e Ingeniería de Computadores.
-  **Agustín López Arribas**: 
    -   E-mail: a.lopezarri@alumnos.urjc.es
    -   Github:
        

-  **Zhong Hao Lin Chen**:
    -   E-mail: z.linc@alumnos.urjc.es
    -   Github: lalinlulelo
        
-  **Guillermo Meléndez Morales**:
    -   E-mail: g.melendezm@alumnos.urjc.es
    -   Github: guillemelmor