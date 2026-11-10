# Leer Instagram

Lector experimental de reels públicos. Usa yt-dlp para descargar el video y faster-whisper para transcribir el audio en español. No requiere API de OpenAI.

## Uso
En Actions > Leer reel de Instagram > Run workflow, pegar la URL del reel. Al finalizar, descargar el artefacto `reel-resultado` con transcripción, metadatos y archivo multimedia si la descarga fue exitosa.

Instagram puede bloquear el acceso o exigir una sesión. No se usan cookies ni credenciales y no se eluden restricciones de acceso.
