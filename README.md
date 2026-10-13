# El Último Brindis

Web-app del juego de asesinato del retiro en Can Cervera (20–22 de noviembre de 2026).

- `index.html` — la web: historia, fichas de personaje cifradas, evidencias, libreta, programa y reglas.
- `manifest.webmanifest` + iconos — permiten instalarla en el móvil («Añadir a pantalla de inicio»).
- `sw.js` — guarda la web en el móvil para que funcione sin cobertura. Siempre intenta cargar la última versión cuando hay conexión.

Las fichas y los finales van cifrados (AES-GCM). Sin el código de cada persona no se pueden leer, aunque se mire el código fuente.

Se publica con GitHub Pages desde la rama `main`.
