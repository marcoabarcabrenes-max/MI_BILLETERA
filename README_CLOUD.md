# MI BILLETERA — compilación desde el teléfono

Este proyecto incluye un flujo de GitHub Actions que puede construir el APK en un servidor de GitHub, sin Android Studio ni computadora local.

1. Crea un repositorio en GitHub llamado `MI_BILLETERA`.
2. Sube el contenido de esta carpeta al repositorio (incluyendo `.github/workflows/build-apk.yml`).
3. En GitHub abre **Actions** → **Construir MI BILLETERA APK** → **Run workflow**.
4. Cuando termine correctamente, abre la ejecución y descarga el artefacto `MI_BILLETERA_APK`.
5. Dentro encontrarás `app-debug.apk`. Instálalo en tu Android.

El uso de GitHub Actions para ejecutar builds y guardar artefactos está documentado por GitHub.
