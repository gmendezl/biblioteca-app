# Biblioteca de Gastón — página

Página para ver y agregar material a la biblioteca. No contiene datos:
lee y escribe las fichas en el repositorio privado `biblioteca-datos` usando un token
personal de GitHub que se guarda solo en el navegador de cada dispositivo.

También funciona abriendo `index.html` directamente desde el computador.

## Entrar con contraseña

`acceso.json` guarda la llave de GitHub cifrada (AES-GCM, clave derivada de la contraseña con
PBKDF2-SHA256, 600.000 iteraciones). Sin la contraseña el archivo no sirve. Para cambiar la
contraseña: ⚙︎ → "Crear contraseña" y reemplazar `acceso.json` con el texto que entrega la página.
