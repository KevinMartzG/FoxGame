# Zorro Aventura — APK para Android

Dos formas de obtener el .apk (elige una):

## A) Con Android Studio (en tu PC)
1. Instala Android Studio (gratis).
2. Abre la carpeta `android` de este proyecto (File > Open).
3. Espera a que termine de sincronizar y pulsa Build > Build Bundle(s) / APK(s) > Build APK(s).
4. El archivo queda en `android/app/build/outputs/apk/debug/app-debug.apk`. Pásalo al móvil e instálalo.

## B) Sin instalar nada (GitHub, gratis)
1. Crea un repositorio nuevo en GitHub y sube TODO el contenido de esta carpeta (incluida la carpeta oculta `.github`).
2. Entra en la pestaña "Actions" > "Construir APK" > Run workflow.
3. A los pocos minutos, descarga `ZorroAventura-apk` (contiene el app-debug.apk) y pásalo al móvil.

En el móvil: abre el .apk y acepta "instalar apps de origen desconocido".

## Si cambias el juego
Compila el juego (`npm run build` en la carpeta del juego), copia `dist` como `www` aquí y ejecuta `npx cap sync android`.
