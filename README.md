# Dima Therapy 3.0 — despliegue de producción

Este repositorio contiene el resultado estático de Astro para https://dimatherapyonline.com, publicado en Hostinger.

La fuente editable está en https://github.com/FrancoMakoski/Dima y, en el entorno local, en la carpeta hermana `Web 3.0`. No editar los HTML compilados directamente.

Migración del 18 de septiembre de 2026: fuente `46d3d71`, con perfiles en hebreo y ruso, reservas, credenciales, términos y página 404. Conserva las redirecciones históricas.

Para publicar cambios, ejecutar `npm run check` y `scripts/prepare-release.ps1` desde la fuente, revisar el resultado, crear el commit de este repositorio y hacer push. El script conserva un respaldo y un manifiesto de archivos fuera de este repositorio.

La medición usa GA4 después del consentimiento. El panel y servidor experimental anterior fueron retirados; `/admin` y `/server` quedan bloqueados. Las credenciales de medición y los informes privados nunca se publican aquí.
