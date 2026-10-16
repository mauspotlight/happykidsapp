# Happy Kids · Reservas

App interna para que el equipo de Happy Kids vea el calendario de juegos reservados y registre nuevas reservas (fecha, juego y cliente).

## Estado actual: modo prueba

Esta versión guarda las reservas y los usuarios **solo en el navegador de cada persona** (localStorage). Sirve para probar las funciones, pero lo que registra una persona no lo ven las demás. El siguiente paso es conectar una base de datos compartida (por ejemplo Firebase) para que todo el equipo vea la misma agenda.

## Cómo usarla

1. La primera vez se crea la cuenta de administrador.
2. Desde **Equipo** el administrador crea los usuarios del personal.
3. También se puede **entrar como invitado** para ver y registrar reservas.

## Publicación

Es un solo archivo, `index.html`. Se publica con GitHub Pages: *Settings → Pages → Deploy from a branch → main / (root)*.
