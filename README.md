# CC Journal — descargas

Journal de trading de futuros MNQ. App de escritorio para Windows, local-first:
todo se guarda en tu propia computadora, sin cuentas ni servidores.

## Descargar

**[⬇️ Descargar CC Journal (portable, Windows 64-bit)](https://github.com/TheLordJoan/cc-journal-releases/releases/latest)**

En la página de la última versión, baja el archivo `CC-Journal-1.0.0-portable.exe`.

## Cómo usarlo

1. Guarda el `.exe` donde quieras (Escritorio, Descargas, una USB — da igual).
2. Doble click. No hay instalación, no pide permisos de administrador.
3. La primera vez Windows SmartScreen puede avisar que es de un editor
   desconocido: **Más información → Ejecutar de todas formas**. Pasa porque el
   ejecutable no está firmado con un certificado de pago, no porque haya algo raro.

## Dónde quedan tus datos

El journal se guarda en `%APPDATA%\CC Journal\journal.sqlite`. Sigue ahí aunque
muevas o borres el `.exe`, y cada computadora tiene su propio journal.

## Datos de mercado

Los precios, fundamentales y estimaciones se leen en vivo de Finviz, Yahoo
Finance y TipRanks cada vez que abrís la app. No hace falta configurar ninguna
API key: solo tener internet.

---

El código fuente vive en un repo privado; acá solo se publican los ejecutables.
