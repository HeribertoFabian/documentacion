
---

### Caso de Prueba 1: Verificación de la Eliminación de los Roles Específicos en el ComboBox

| **Nombre de escenario**                  | Verificación de la Eliminación de los Roles Específicos en el ComboBox "Rol Solicitante"           |
|------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **Nombre del Requerimiento**             | Eliminación de Usuarios en el ComboBox "Rol Solicitante" en Solicitudes a Firmar                    |
| **ID paso de Prueba**                    | 1                                                                                                  |
| **Liga de Acceso**                       | /solicitudesAFirmar                                                                                 |
| **Datos de entrada**                     | Acceder al comboBox "Rol Solicitante" desde el perfil de súper usuario y desplegar las opciones.    |
| **Resultado esperado**                   | Los roles "SEDECOS", "DELEGACIONES", "DICTAMINADOR", "FIRMANTE", "SUPERUSUARIO", y "ADMINISTRADOR" no deben aparecer en la lista de opciones del comboBox "Rol Solicitante". |
| **Evidencia de pantallas**               | Captura de pantalla del comboBox desplegado sin las opciones mencionadas.                           |
| **Observaciones durante la ejecución**   | Asegurarse de que los roles especificados hayan sido eliminados del comboBox.                       |

---

### Caso de Prueba 2: Verificación de la Integridad Visual y Funcional del ComboBox tras la Eliminación

| **Nombre de escenario**                  | Validación de la Integridad Visual y Funcional del ComboBox tras la Eliminación de Usuarios         |
|------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **Nombre del Requerimiento**             | Eliminación de Usuarios en el ComboBox "Rol Solicitante" en Solicitudes a Firmar                    |
| **ID paso de Prueba**                    | 2                                                                                                  |
| **Liga de Acceso**                       | /solicitudesAFirmar                                                                                 |
| **Datos de entrada**                     | Acceder al comboBox "Rol Solicitante" y utilizar las opciones restantes para seleccionar un rol y proceder con la creación de una solicitud. |
| **Resultado esperado**                   | El comboBox debe funcionar correctamente y no debe presentar ningún error visual o funcional después de la eliminación de los roles especificados. |
| **Evidencia de pantallas**               | Captura de pantalla del comboBox funcionando con las opciones restantes y la solicitud creada exitosamente. |
| **Observaciones durante la ejecución**   | Asegurarse de que el comboBox sigue siendo funcional y que la interfaz no presenta errores visuales o de estilo. |

---

