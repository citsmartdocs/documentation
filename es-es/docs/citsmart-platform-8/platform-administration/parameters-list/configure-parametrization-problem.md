title: Configurar parametrización – problema
Description: La parametrización de "Problema" debe ser hecha para permitir la ejecución/uso de este proceso
#Configurar parametrización – problema
La gestión de problemas gestiona el ciclo de vida de todos los problemas desde la primera identificación, pasando por la investigación, documentación y eventual remoción. La parametrización de "Problema" debe ser hecha para permitir la ejecución/uso de este proceso, pudiendo ser posible definir el nombre del flujo estándar para problema, definir si serán notificados el responsable y grupo ejecutor cuando el plazo para evitar/solucionar el problema si haya expirado, entre otras acciones viables.

Procedimiento
-------------

1.  Acceder al menú principal Parametrización \> Gestión de Problema;

2.  Definir os valores dos parâmetros (atributos);

3.  Clicar no botão "Gravar" para efetuar a operação;

4.  A lista abaixo representa os parâmetros do "Problema" e a finalidade de cada
    um deles:

| **#** |                                                                            **Nombre**                                                                            | **Valores possíveis** |                                                                                                                                                                                                                                     **Finalidade**                                                                                                                                                                                                                                     |                                                         **Orientações complementares**                                                         |
|:-----:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------:|
|   31  |                                       Envíar el e-mail en la ejecución de los flujos de solicitudes/incidentes (Ej: S o N)                                       |         S o N         |                                                                                                                                                            Definir si se hará el envío de notificaciones por correo electrónico al solicitante al realizar la ejecución de los flujos de solicitud de servicios/incidentes.                                                                                                                                                            |                                                                  No se aplica                                                                  |
|  123  |                                                            Nombre del modelo de flujo para el problema                                                           | Ej.: ProblemaEstandar |                                                                                                                 Indicar el nombre del flujo predeterminado para el Problema. Si no se informa un flujo al problema, será establecido por el sistema el flujo (según lo informado en el valor del parámetro). Este flujo se define en la pantalla de "Diseño de Flujo”.                                                                                                                 |                                                                  No se aplica                                                                  |
|  124  |                                    Plantilla Identificación del e -mail que se envía al solicitante cuando se crea un problema                                   |                       |         Informar el número de identificación (ID) del modelo de correo electrónico de notificación de creación del problema.Al registrar un problema en la pantalla de "Registro de Problemas" se utilizará para enviar la notificación de creación del problema al modelo de correo electrónico definido. Donde esta notificación se enviará al solicitante. Este identificador de modelo de correo electrónico se registra en la pantalla de "modelo de correo electrónico".         | Si no se informa el número de identificación (ID) del modelo de correo electrónico, es posible que no se envíe el correo electrónico correcto. |
|  125  |                                  Plantilla Identificación del e -mail que se envía al solicitante cuando un asunto está en curso                                 |                       |                Informar el número de identificación (ID) del modelo de correo electrónico de notificación de progreso del problema. Al ejecutar el problema, en la pantalla de "Problema", se utilizará para el envío de la notificación del progreso del problema, el modelo de correo electrónico definido. Donde esta notificación se enviará al solicitante. Este ID del modelo de correo electrónico se registra en la pantalla de "modelo de correo electrónico".                | Si no se informa el número de identificación (ID) del modelo de correo electrónico, es posible que no se envíe el correo electrónico correcto. |
|  126  |                                  Plantilla Identificación del e -mail que se envía al solicitante cuando se finaliza un problema                                 |                       |             Informar el número de identificación (ID) del modelo de correo electrónico de notificación de finalización del problema. Al finalizar el problema en la pantalla de "Problema", se utilizará para el envío de la notificación de finalización del problema, el modelo de correo electrónico definido. Donde esta notificación se enviará al solicitante. Este ID de modelo de correo electrónico se registra en la pantalla de "Modelo de correo electrónico”.             | Si no se informa el número de identificación (ID) del modelo de correo electrónico, es posible que no se envíe el correo electrónico correcto. |
|  127  |                                     Template ID de correo electrónico que se envió al grupo objetivo de escalonar un problema                                    |                       | Informar el número de identificación (ID) del modelo de correo electrónico de notificación del escalonamiento del problema. Al escalar un problema para el grupo en la pantalla de "Gestión de problemas", se utilizará para enviar la notificación de la escalada del problema al modelo de correo electrónico definido. Cuando se envía esta notificación al grupo de destino. Este ID de modelo de correo electrónico se registra en la pantalla de "Modelo de correo electrónico”. | Si no se informa el número de identificación (ID) del modelo de correo electrónico, es posible que no se envíe el correo electrónico correcto. |
|  128  |           Template ID de correo electrónico que se envía al grupo responsable y ejecutar cuando el plazo para eludir / resolver un problema ha expirado          |                       |         Informar el número de identificación (ID) del modelo de correo electrónico de notificación de expiración del plazo para evitar/solucionar el problema. Cuando el plazo para evitar/solucionar un problema haya expirado, se enviará al responsable y grupo ejecutor, la notificación de expiración del plazo para evitar/solucionar el problema, según se define. Este ID de modelo de correo electrónico se registra en la pantalla de "Modelo de correo electrónico”.        | Si no se informa el número de identificación (ID) del modelo de correo electrónico, es posible que no se envíe el correo electrónico correcto. |
|  129  | Notifique grupo responsable y ejecutor de la expiración del período de aplicación de la solución / contorno del problema (por ejemplo, S o N - por default: 'S') |   S o N (Default: S)  |                                                                                                                                                                            Definir si serán notificados el responsable y el grupo ejecutor cuando el plazo para evitar/solucionar el problema haya expirado.                                                                                                                                                                           |                      Si no se informa el valor del parámetro, se utilizará el valor predeterminado del sistema: "S" (Sí).                      |
|  194  |                            ¿Habilita el problema de programación en las reglas de escalonamiento definidos? (Ej.: S o N - Default 'N')                           |   S o N (Default: N)  |                                                                                                                             Definir si el escalonamiento del problema determinado en las reglas de escalado será habilitado. Esta regla de escalonamiento del problema se define en la pantalla de "Reglas de Escalonamiento y Notificaciones Automáticas”.                                                                                                                            |                        Si no indica el valor del parámetro, se establece el valor predeterminado del sistema: "N" (No).                        |


Tabla 1 - Lista de parámetros

!!! tip "About"

    <b>Product/Version:</b> CITSmart Platform | 8.00 &nbsp;&nbsp;
    <b>Updated:</b>01/28/2019 – Larissa Lourenço