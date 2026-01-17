# Sinapsis / En Bruto

Blog personal sobre la interseccion entre tecnologia, sociedad, economia y politica. Bajo la filosofia de "Slow blogging", se centra en el analisis reflexivo, opiniones fundamentadas y rigor tecnico, alejandose del ruido de las noticias rapidas.

## Desarrollo Local

Para ejecutar este blog en tu entorno local (Linux), sigue estos comandos:

### 1. Instalacion de dependencias
Asegurate de tener Ruby y Bundler instalados, luego ejecuta:
```bash
bundle install
```

### 2. Compilacion y ejecucion
Para levantar el servidor local con recarga automatica:
```bash
bundle exec jekyll serve
```
El sitio estara disponible en `http://localhost:4000`.

### 3. Solo compilacion
Si solo deseas generar los archivos estaticos en la carpeta `_site`:
```bash
bundle exec jekyll build
```