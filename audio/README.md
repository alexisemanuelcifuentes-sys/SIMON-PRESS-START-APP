# Galería de audio — administración segura

IMPORTANTE: esta carpeta es pública. Nunca copiar aquí el audio original completo, proyectos, sesiones, stems, contratos ni información privada.

1. Crear fuera del repositorio una copia recortada de un máximo de 30 segundos.
2. Exportarla como MP3 u OGG con un nombre que no revele información privada.
3. Copiar únicamente esa muestra dentro de esta carpeta.
4. Opcionalmente copiar una portada JPG, PNG o WebP sin metadatos sensibles.
5. Agregar una entrada a `catalog.json`:

```json
{
  "tracks": [
    {
      "title": "Nombre público de la pista",
      "description": "Descripción breve.",
      "previewFile": "nombre-muestra-30s.mp3",
      "previewSeconds": 30,
      "cover": "portada.jpg",
      "coverAlt": "Descripción de la portada",
      "type": "Música original"
    }
  ]
}
```

La página no ofrece descarga y detiene el reproductor a los 30 segundos. Aun así, todo archivo publicado en Internet puede copiarse: la protección real consiste en subir solamente la muestra ya recortada y conservar el máster fuera del repositorio.