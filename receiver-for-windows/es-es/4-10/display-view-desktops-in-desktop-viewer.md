---
layout: leftnav
title: Mostrar los dispositivos en Desktop Viewer
menu: subnav
---

# Mostrar los dispositivos en Desktop Viewer

Citrix Receiver para Windows detecta los dispositivos que están conectados al equipo y le permite elegir cuáles de ellos quiere usar con las aplicaciones y los escritorios alojados en servidores.

* Puede usar los parámetros de **Preferencias** > **Conexiones** para personalizar si quiere o no que los dispositivos, tales como micrófonos y cámaras Web, se conecten con la sesión virtual.
* Los dispositivos conectados a la máquina local aparecen en la lista Dispositivo en **Preferencias** > **Dispositivos**.
* Si ha conectado un dispositivo, pero no lo ve en la lista Dispositivo, haga clic en **Actualizar**.
* Una vez conectados, los dispositivos aparecen como **Optimizado**, **Restringido por directiva** o **Genérico**.

| Dispositivo | Descripción |
| --- | --- |
| Optimizado | El dispositivo tiene un canal virtual de Citrix y está disponible automáticamente tanto en la sesión remota como en la máquina local al mismo tiempo. La columna Conexión actual para los dispositivos optimizados muestra que el dispositivo está conectado tanto a la Máquina local como a la **Sesión remota**. La casilla Redirigir está marcada y no se puede modificar. Se puede cambiar entre Optimizado y Genérico usando el botón Cambiar a en la columna Canal virtual. Por ejemplo, seleccione Cambiar a genérico si el canal virtual no respalda la funcionalidad completa del dispositivo. |
| Genérico | El dispositivo no tiene un canal virtual de Citrix y no se puede usar en la máquina local y en la sesión remota al mismo tiempo. Marque la casilla Redirigir para cambiar la disponibilidad del dispositivo entre la sesión remota y la máquina local. Puede ver el estado actual de la conexión en la columna Conexión actual. |
| Restringido por directiva | El administrador ha definido una directiva que restringe el uso de este tipo de dispositivo. Por ejemplo, los punteros y teclados USB están normalmente restringidos por directiva de manera predeterminada porque su comportamiento se controla automáticamente en la sesión remota sin respaldo USB. Otros dispositivos, como los dispositivos de red, pueden estar restringidos por motivos de seguridad. La columna Conexión actual para los dispositivos restringidos por directiva muestra solo **Máquina local**. En un dispositivo Restringido por directiva no se puede marcar la casilla Redirigir. |

