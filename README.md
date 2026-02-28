# Face Detection (JavaScript)

Descripción
- Proyecto de ejemplo que usa `face-api.js` para detectar rostros, landmarks y expresiones desde la cámara web en el navegador.

Estructura relevante
- `index.html` — página principal.
- `script.js` — código que carga modelos y ejecuta la detección en el elemento `<video>`.
- `face-api.min.js` — librería face-api.
- `models/` — carpeta que contiene los modelos (.json y shards). Mantenerla en la raíz.

Cómo correr (local)
1. Abrir una terminal en la carpeta del proyecto (la que contiene `index.html` y `models/`).

2. Levantar un servidor HTTP simple (recomendado para evitar CORS):

```bash
python3 -m http.server 8000
# o, si prefieres npm:
# npx http-server -p 8000
```

3. Abrir en el navegador:

http://localhost:8000

4. Permitir acceso a la cámara cuando el navegador lo solicite.
