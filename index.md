# ARD Suite Monitor

ARD Suite Monitor es una herramienta de uso personal para supervisar la disponibilidad de copias de seguridad cifradas de ARD Suite almacenadas en Google Drive.

## Funcionamiento

- Utiliza Google Drive API mediante OAuth 2.0.
- Solicita acceso de solo lectura (`drive.readonly`).
- Comprueba la existencia y antigüedad de los respaldos.
- No modifica ni elimina archivos de Google Drive.
- Permite informar el resultado de las comprobaciones a un servicio de alertas.

Esta herramienta está destinada al uso privado de su desarrollador y no ofrece acceso a terceros.

[Política de privacidad](privacy.html)
