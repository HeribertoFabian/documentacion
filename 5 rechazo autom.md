Aquí tienes los casos de prueba que corresponden al requerimiento de "Rechazo Automático de Solicitudes Duplicadas" basados en la información proporcionada:

---

### Caso de Prueba 1: Verificación de Rechazo Automático por Duplicidad

| **Nombre de escenario**                  | Rechazo de Solicitud Duplicada en la Opción “Si ya estás constituido o eres titular de una marca” |
|------------------------------------------|----------------------------------------------------------------------------------------------------|
| **Nombre del Requerimiento**             | Rechazo Automático de Solicitudes Duplicadas                                                       |
| **ID paso de Prueba**                    | 1                                                                                                  |
| **Liga de Acceso**                       | /busquedaSolicitud                                                                                 |
| **Datos de entrada**                     | Ingresar una solicitud de DoRS con datos idénticos (nombre de persona moral y marca) a una solicitud ya autorizada. |
| **Resultado esperado**                   | El sistema debe generar un rechazo automático, mostrando un mensaje de error que indica la duplicidad de la solicitud. |
| **Evidencia de pantallas**               | Captura de pantalla del mensaje de error y la solicitud siendo rechazada.                          |
| **Observaciones durante la ejecución**   | Verificar que el mensaje de error sea claro y que la solicitud no avance en el proceso.            |

---

### Caso de Prueba 2: Validación de No Rechazo cuando no hay Duplicidad

| **Nombre de escenario**                  | Aceptación de Solicitud Única sin Duplicidad                                                       |
|------------------------------------------|----------------------------------------------------------------------------------------------------|
| **Nombre del Requerimiento**             | Rechazo Automático de Solicitudes Duplicadas                                                       |
| **ID paso de Prueba**                    | 2                                                                                                  |
| **Liga de Acceso**                       | /busquedaSolicitud                                                                                 |
| **Datos de entrada**                     | Ingresar una solicitud de DoRS con datos únicos (nombre de persona moral y marca) que no coincidan con ninguna solicitud previamente autorizada. |
| **Resultado esperado**                   | El sistema debe aceptar la solicitud sin mostrar ningún mensaje de error y permitir que avance en el proceso. |
| **Evidencia de pantallas**               | Captura de pantalla de la solicitud aceptada y avanzando en el flujo.                              |
| **Observaciones durante la ejecución**   | Asegurarse de que la solicitud se procese correctamente cuando no hay duplicidad.                  |

---



