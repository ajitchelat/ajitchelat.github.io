---
layout: leftnav
title: Cambiar la contraseña automáticamente
menu: subnav
category: Administrar contraseñas
---

El asistente de cambio de contraseña de Single Sign-on automatiza el proceso de cambio de contraseñas en programas identificados. Según cómo haya configurado Single Sign-on su empresa, puede que le esté permitido crear su propia contraseña, o que tenga que dejar que Single Sign-on cree una automáticamente.

**Nota:** Puesto que las contraseñas generadas por el asistente de cambio de contraseña consisten en un grupo al azar de letras, números y otros caracteres, su nivel de seguridad es muy alto. Como Single Sign-on administra las contraseñas y no es necesario que las recuerde, tenga presente esta función.

Dependiendo de cómo lo haya configurado la empresa, el asistente de cambio de contraseña se inicia de alguna de estas dos maneras:

* Cuando el programa indica que la contraseña debe cambiarse
* Cuando usted inicia el proceso de cambio de la contraseña del programa

En algunos casos, puede que Single Sign-on no detecte el proceso de cambio de contraseña y por tanto no dé inicio al asistente de cambio de contraseña. En estos casos, debe cambiar la contraseña manualmente tanto en el sitio Web o programa como en Single Sign-on, para asegurarse de que ambas contraseñas sean iguales.

## Elegir cómo crear una nueva contraseña

Si la empresa ofrece esta opción, la página **Elija cómo crear la nueva contraseña** del asistente de cambio de contraseña le permite seleccionar la forma en que se creará su nueva contraseña. Las opciones son:

* **Elegir una contraseña generada por el sistema**: Si selecciona esta opción y hace clic en **Siguiente**, el asistente de cambio de contraseña creará una contraseña de alta seguridad. Esta contraseña no se revela durante este proceso, porque se guarda directamente en Single Sign-on y usted no necesita conocerla. Sin embargo, si la empresa configura Single Sign-on para que se pueda ver la contraseña, puede verla después de cerrar el asistente, si lo desea.

**Nota:** Puesto que las contraseñas generadas por el asistente de cambio de contraseña consisten en un grupo al azar de letras, números y otros caracteres, su nivel de seguridad es muy alto. Como Single Sign-on administra las contraseñas y no es necesario que las recuerde, tenga presente esta función.

* **Crear la contraseña**: Si selecciona esta opción y hace clic en **Siguiente**, el asistente de cambio de contraseña le permite crear y enviar su propia contraseña. Dicha contraseña debe seguir las directivas establecidas por la empresa en cuanto a la longitud, complejidad y otros factores que pueden afectar a la seguridad.

## Espera de la confirmación

La página **Esperando la confirmación** del asistente de cambio de contraseña aparece cuando el asistente determina si se cambió la contraseña o si el cambió falló.

Si usted decide que el cambio de contraseña ha tenido éxito antes de que el asistente de cambio de contraseña cierre la página **Esperando la confirmación**, haga clic en **Omitir** para ir a la página **Confirmar el cambio de contraseña**.

## Confirmar el cambio de contraseña

La página Confirmar el cambio de contraseña del asistente de cambio de contraseña puede aparecer si la empresa la activó. Si aparece, le va a preguntar que determine si la contraseña se cambió o no. Hay tres opciones disponibles:

* **Sí**: La ausencia de la página para volver a configurar la contraseña o un mensaje notificando que se cambió indican que el cambio de la contraseña tuvo éxito. Seleccione **Lo hizo** y haga clic en **Siguiente** para indicarle al asistente de cambio de contraseña que el cambio se realizó con éxito. El asistente termina el proceso.

* **No**: La presencia de la página para volver a configurar la contraseña o un mensaje notificando que el cambio falló indican que el cambio de la contraseña no se realizó. Seleccione **No lo hizo** y haga clic en **Siguiente** para indicarle al asistente de cambio de contraseña que el programa no ha aceptado la nueva contraseña. El asistente se cierra sin cambiar la contraseña.

* **No sé si lo hizo**: Si selecciona **No sé si lo hizo** y hace clic en **Siguiente**, pasará a una página que describe cómo determinar si la contraseña se cambió. Hay otra forma de determinar si el asistente tuvo éxito, si creó su propia contraseña: ponga Single Sign-on en pausa e inicie una sesión en el programa con la nueva contraseña.

**Nota:** Puede ser que necesite mover la ventana del asistente de cambio de contraseña para ver si la ventana de volver a configurar la contraseña del programa aún se encuentra abierta o si el programa le proporcionó alguna respuesta relacionada con la contraseña.

## Confirmar que la contraseña no cambió

Si el asistente de cambio de contraseña detecta que la contraseña no cambió o si elige **No lo hizo** en la página **Confirmar el cambio de contraseña**, aparecerá la página **La contraseña no se cambió**.

La página **La contraseña no se cambió** ofrece dos opciones:

* **Intentar con otra contraseña**: Use esta opción solamente si el formulario de cambio de contraseña se encuentra aún abierto. Si se usa después de cerrarse el formulario, las contraseñas en su programa y en Single Sign-on podrían no coincidir. Seleccionando **Intentar con otra contraseña** y haciendo clic en **Siguiente** se puede intentar enviar otra contraseña al programa. Dependiendo de cómo esté configurado el asistente de cambio de contraseña, puede darse alguna de las siguientes situaciones:
   * Aparece la página Elija cómo crear la nueva contraseña. Puede seleccionar entre contraseñas generadas por el sistema o crear una propia.
   * Aparece la página Crear la contraseña.
   * Se crea y envía una contraseña generada por el sistema. El asistente de cambio de contraseña busca luego confirmación del cambio de contraseña.

* Salir del asistente sin hacer nada más. Seleccionando **Salir del asistente sin hacer nada más** se pone fin a los intentos de cambiar la contraseña del programa. Puede, sin embargo, reiniciar el asistente de cambio de contraseña e intentarlo de nuevo en otro momento.

## Salir del asistente sin hacer nada más

La página La contraseña no se cambió aparece si el asistente de cambio de contraseña detecta que la contraseña no cambió, o si se elige **No lo hizo** en la página **Confirmar el cambio de contraseña**.

Si el Asistente de cambio de contraseña falló, haga lo siguiente para cambiar la contraseña:

* Haga clic en **Finalizar** en la página **La contraseña no se cambió** para cerrar el asistente y luego reinicie el asistente para intentarlo de nuevo.
* Cambie la contraseña manualmente en el programa y en Single Sign-on
* Póngase en contacto con el servicio de asistencia técnica de la empresa

## Salir del asistente después de cambiar la contraseña

La página **La contraseña se cambió correctamente** aparece cuando el Asistente de cambio de contraseña detecta que la contraseña cambió, o si se elige **Lo hizo** en la página **Confirmar el cambio de contraseña**.

En este momento, el programa acepta la nueva contraseña y Single Sign-on la guarda.

## Determinar si el programa aceptó la nueva contraseña

Si selecciona **No sé si lo hizo** y hace clic en **Siguiente** en la página **Confirmar el cambio de la contraseña** verá una página que describe cómo determinar si la contraseña cambió o no.

Otra forma de determinar si el asistente tuvo éxito es poner Single Sign-on en pausa y luego iniciar una sesión en el programa con la nueva contraseña.

Haciendo clic en **Siguiente** en esta página se hace que vuelva a aparecer la página **Confirmar el cambio de contraseña**.

## Crear la contraseña

La página para **Crear la contraseña** del asistente de cambio de contraseña aparece si seleccionó Crear la contraseña en la página **Elija cómo crear la nueva contraseña**. Esta página no aparece si la empresa no le proporciona la opción de crear sus propias contraseñas.

Para evitar el envío de una contraseña mal escrita, debe escribirla en las casillas **Nueva contraseña** y **Confirmar la contraseña**. El asistente de cambio de contraseña le indicará si las contraseñas no son iguales. Si las contraseñas son iguales, el botón **Siguiente** se verá disponible.

El asistente de cambio de contraseña requiere que siga todas las directivas establecidas por la empresa para las contraseñas. Los siguientes son algunos ejemplos de directivas establecidas por la empresa:

* Las contraseñas anteriores no se pueden volver a usar
* Las contraseñas deben contener una mezcla de números y letras
* Las contraseñas no pueden incluir ciertos caracteres
* Las contraseñas deben ser de cierta longitud

