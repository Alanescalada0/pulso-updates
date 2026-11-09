# PULSO — actualizaciones

Este repositorio no tiene código. Solo guarda, en sus **Releases**, las APK de PULSO y el manifiesto
`pulso-update.json` que la app lee para saber si hay una versión nueva.

- PULSO busca la actualización, la descarga, verifica su SHA-256, su paquete y su firma, y abre el
  instalador oficial de Android. No hace falta entrar acá.
- Cada APK se instala encima de la anterior (mismo paquete `com.convx.music.debug`, misma firma):
  no se pierde la biblioteca, el historial, los ajustes ni las cuentas.
- Las versiones se publican con `pulso-release/publicar-version.ps1` desde el proyecto de PULSO.
