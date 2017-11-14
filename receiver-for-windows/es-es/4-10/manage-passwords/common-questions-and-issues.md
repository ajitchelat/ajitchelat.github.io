---
layout: leftnav
title: Preguntas y problemas comunes
menu: subnav
category: Administrar contraseñas
---

La siguiente es una lista de preguntas y problemas que puede encontrarse al trabajar con Single Sign-on.

## Recibí un mensaje de error indicando que mi contraseña va a caducar

Una de la mejores formas de mantener la información segura es cambiando la contraseña periódicamente. En función de los parámetros que haya establecido su empresa, Single Sign-on le enviará un mensaje cuando sus contraseñas no hayan cambiado por mucho tiempo.

Continuará recibiendo estos mensajes hasta que cambie la contraseña.

## No quiero ejecutar Single Sign-on ahora

Algunas veces no va a querer ejecutar Single Sign-on. Por ejemplo, si necesita trabajar en una página de inicio de sesión no deseará que Single Sign-on inicie una sesión en el programa.

En estos casos, use la función Pausa de Single Sign-on. La función Pausa detiene el inicio de sesión automático, pero mantiene Single Sign-on abierto y disponible.

## El programa rechaza mi nueva contraseña

Cambió la contraseña para un programa en particular a través del asistente de cambio de contraseña, pero cuando trata de iniciar una sesión en el programa, éste rechaza la nueva contraseña.

Es muy posible que la nueva contraseña fuera almacenada por Single Sign-on, pero no fuera aceptada por el programa. Como resultado, Single Sign-on está enviando una contraseña incorrecta.

Si la empresa la ha habilitado, use la función Recuperar contraseña anterior para solucionar este problema.

**Nota**: Si esta función no está disponible, póngase en contacto con el servicio de asistencia técnica de su empresa.

## Para restaurar una contraseña anterior del programa

1. En el área de notificación de Microsoft Windows, normalmente en la parte derecha de la barra de tareas, haga clic con el botón secundario en el icono de Citrix Receiver y luego haga clic en **Contraseñas** > **Administrar contraseñas**.
1. En la ventana Administrar contraseñas, seleccione el programa o sitio Web que desee y haga clic en **Modificar**. Aparece un cuadro de diálogo que contiene las propiedades para el programa seleccionado.
**Nota**: En este punto, es posible que su empresa haya activado un proceso de verificación de identidad. Si es así, introduzca su nombre de usuario y contraseña de Windows cuando lo pida el sistema. (Si inicia la sesión con una tarjeta inteligente u otro método de autenticación, úselo para verificar su identidad cuando lo pida el sistema.)
1. Haga clic en **Recuperar contraseña anterior** y luego haga clic en **Sí** para confirmar la acción.

## No puedo acceder a mis datos de usuario

Cuando inicia una sesión en su equipo, Single Sign-on se conecta con el servidor donde la empresa almacena la información de Single Sign-on relativa a los usuarios. Si la conexión se establece con éxito y se confirma su identidad, Single Sign-on se inicia.

Si por alguna razón, la conexión o la identificación no tienen éxito, Single Sign-on no se iniciará y muy probablemente reciba un mensaje de error indicando que no se puede acceder a sus datos de usuario. Si esto ocurre póngase en contacto con el servicio de asistencia técnica de la empresa.

## Mi explorador Web no funciona con Single Sign-on

Single Sign-on sólo proporciona respaldo para su utilización con Microsoft Internet Explorer. El uso de otros exploradores Web podrá dar resultados no esperados.

## Después de cerrar una sesión, Single Sign-on vuelve a iniciarla

En algunas instancias, cuando se cierra la sesión de un programa o sitio Web protegido por contraseña, el programa puede volver a la pantalla de inicio de sesión. Si esto sucede, en función de cómo la empresa haya configurado Single Sign-on, puede que éste reaccione a la página de inicio reiniciando la sesión en el programa.

Si esto sucede, tiene las siguientes opciones:

* Si la empresa la ha habilitado, use la función Pausa de Single Sign-on antes de cerrar la sesión
* Si la función Pausa no está disponible, cierre la sesión en el programa y rápidamente cierre la ventana del mismo antes de que Single Sign-on pueda volver a iniciar una sesión

**Nota**: Explique la situación al servicio de asistencia técnica de la empresa y sugiera que el administrador de Single Sign-on active el parámetro de detección avanzada de definición de aplicaciones denominado **Procesar solamente el primer inicio de sesión de esta aplicación**.

## ¿Debo hacer algo especial antes de trabajar sin conexión a la red?

Si la empresa instaló Single Sign-on en el equipo local en lugar de ejecutarlo desde un servidor en la red de la empresa, actualice la licencia antes de trabajar sin conexión a la red. Esto asegura que tendrá el tiempo total permitido para la licencia hasta que pueda volver a conectarse a la red de la empresa.

## Para actualizar la licencia de Single Sign-on

1. En el área de notificación de Microsoft Windows, normalmente en la parte derecha de la barra de tareas, haga clic con el botón secundario en el icono de Citrix Receiver y luego haga clic en **Contraseñas** > **Administrar contraseñas**.
**Nota**: En este punto, es posible que su empresa haya activado un proceso de verificación de identidad. Si es así, introduzca su nombre de usuario y contraseña de Windows cuando lo pida el sistema. (Si inicia la sesión con una tarjeta inteligente u otro método de autenticación, úselo para verificar su identidad cuando lo pida el sistema.)
1. Haga clic en Acerca de. Aparecerá la ventana Acerca de Citrix Single Sign-On.
1. Haga clic en **Actualizar la licencia**.
1. Haga clic en **Aceptar**. La ventana **Acerca de Citrix Single Sign-On** se cerrará.

## ¿Por qué bloquea Single Sign-on mi estación de trabajo?

Single Sign-on bloquea la estación de trabajo cada vez que se quiere realizar una tarea que requiere un nivel de seguridad extra. Estas tareas pueden incluir cambiar o revelar una contraseña.

Una vez bloqueada la estación de trabajo, usted debe verificar su identidad ante Single Sign-on suministrando la contraseña de la cuenta. En algunos casos, se le puede pedir que responda a unas preguntas de seguridad. Mediante dicha verificación, Single Sign-on evita que otras personas puedan acceder a información confidencial.

Aunque esto parezca una molestia, se hace para proteger al usuario, sus datos y a la empresa.

