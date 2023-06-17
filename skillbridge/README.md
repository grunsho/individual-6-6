# individual-6-6

**Ejercicio Individual 6-6**

Como continuación del trabajo anterior, se crearon dos grupos de usuarios: **Moderadores** y **Usuarios**. Se crearon dos usuarios por cada grupo con las siguientes credenciales:

**Moderadores**

- moderador1: moderapass

- moderador2: passmodera

**Usuarios**

- otrousuario: otropass

- Chimichanga: passwordchanga

Los moderadores son parte del staff, por lo que pueden ingresar a la página de administración del sitio, mientras que a los usuarios no les está permitido ingresar con sus credenciales.

Los moderadores a su vez pueden crear nuevos usuarios, pero no nuevos moderadores. Estos sólo pueden ser creados por el admin (superuser, credenciales admin: admin).

Al ingresar a la página principal, todos llegan al landing. En este lading el navbar muestra sólo dos links: *Inicio* e *Ingresar*. Haciendo click en Ingresar se llega al login, en donde dependiendo de las credenciales ingresadas, redirige al index de usuario (con una bienvenida específica a cada usuario) o al index de moderador (con un resumen de estadísticas del sitio).

Finalmente, al estar logueado como moderador, se agregan dos links al navbar: *Usuarios* y *Agregar Usuario*, el primero resumiendo los usuarios del sitio, con su información completa y el segundo con el formulario para crear un nuevo usuario.