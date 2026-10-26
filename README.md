# Aniimo Scout · versiones

Aquí se publican las versiones de **Aniimo Scout** (el código está en un repositorio privado).

- **Ya lo tienes:** se actualiza solo. Scout mira aquí al abrirse y cada 3 horas, descarga la versión nueva junto a tu
  `AniimoScout.exe` y la pone al cerrarlo (o al momento con «Actualizar» arriba en la ventana). Tus datos no se tocan.
- **Primera vez:** descarga `AniimoScout.exe` de la [última versión](../../releases/latest) y ábrelo desde la carpeta que
  quieras. Windows puede avisar (SmartScreen: «Más información» → «Ejecutar de todos modos»): el programa no está firmado.
- **Comprobar la descarga:** `certutil -hashfile AniimoScout.exe SHA256` debe dar lo que pone `SHA256SUMS.txt`.

`latest.json` es lo que lee el actualizador: versión, enlace, huella SHA-256, tamaño y novedades.
