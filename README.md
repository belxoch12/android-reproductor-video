<h1 align="center">Reproductor de Video</h1>

<p align="center">
  App Android que busca los videos guardados en el dispositivo y los reproduce.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/min_SDK-24-blue" alt="min SDK 24">
</p>

---

## Funcionalidades

- Recorre el almacenamiento del dispositivo buscando videos (`.mp4`, `.avi`, `.3gp`, `.mkv`).
- Muestra los videos encontrados en una lista con un adaptador personalizado.
- Al tocar un video, lo abre en el reproductor.

## Estructura

```
app/src/main/java/com/example/reproductordevideo/
├── MainActivity.java   # Búsqueda de archivos y manejo de la lista
├── VideoAdapter.java   # Adaptador de la lista de videos
└── VideoItem.java      # Modelo de cada video
```

## Tecnologías

Java · Android SDK (min 24, target 33) · Material Components · ConstraintLayout

## Cómo ejecutarlo

1. Clona el repositorio y ábrelo en **Android Studio**.
2. Espera a que Gradle sincronice las dependencias.
3. Ejecútalo en un emulador o dispositivo y concede el permiso de lectura de almacenamiento.

## Autoría

Desarrollado por [belxoch12](https://github.com/belxoch12).
