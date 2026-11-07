# Política de privacidad — ARD Suite Monitor

**Última actualización: 7 de noviembre de 2026**

## 1. Finalidad

ARD Suite Monitor es una herramienta de uso personal destinada a supervisar la existencia y antigüedad de copias de seguridad cifradas almacenadas en Google Drive.

No es un servicio comercial ni está destinado a ofrecer acceso a terceros.

## 2. Acceso a Google Drive

La aplicación utiliza Google Drive API mediante OAuth 2.0 y solicita el permiso `drive.readonly`.

Este permiso permite leer archivos y metadatos de Google Drive, pero no permite modificarlos ni eliminarlos.

Aunque el permiso técnicamente permite consultar otros archivos de la cuenta, el monitoreo está diseñado para utilizar exclusivamente la carpeta de respaldos cifrados de ARD Suite.

## 3. Uso de la información

La herramienta consulta nombres, tamaños y fechas de archivos para comprobar la disponibilidad y antigüedad de los respaldos.

No necesita descifrar los respaldos ni acceder al contenido de la base de datos para realizar estas comprobaciones.

## 4. Almacenamiento y notificaciones

Las credenciales OAuth se almacenan localmente en la computadora autorizada.

El sistema de monitoreo está diseñado para enviar únicamente señales de estado a Healthchecks.io, que puede generar notificaciones por Telegram y correo electrónico.

No está diseñado para transmitir el contenido de los respaldos a esos servicios.

## 5. Compartición de información

ARD Suite Monitor no comercializa ni vende información de Google Drive.

La aplicación utiliza los servicios de Google para acceder a los archivos autorizados y Healthchecks.io para supervisar el estado de las comprobaciones.

## 6. Revocación del acceso

El propietario de la cuenta puede revocar el acceso OAuth de ARD Suite Monitor desde la configuración de seguridad de su cuenta de Google.

## 7. Cambios

Esta política podrá actualizarse cuando se incorporen nuevas funcionalidades o cambie el tratamiento de la información.
