# Galería de audio

1. Copiar el archivo MP3, OGG o WAV dentro de esta carpeta.
2. Opcionalmente copiar una portada JPG, PNG o WebP.
3. Agregar una entrada a `catalog.json`:

```json
{
  "tracks": [
    {
      "title": "Nombre de la pista",
      "description": "Descripción breve.",
      "file": "nombre-pista.mp3",
      "cover": "portada.jpg",
      "coverAlt": "Descripción de la portada",
      "type": "Música original",
      "download": true
    }
  ]
}
```

Para ocultar el enlace de descarga usar `"download": false`. La reproducción seguirá disponible.