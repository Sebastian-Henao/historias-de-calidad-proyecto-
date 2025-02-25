### Aplicacion: Pagina web para gestion de OVAs (Objetos Virtuales para el Aprendizaje)

## Historia 5
- **Prioridad:** Alta
- **Atributo de calidad:** Mantenibilidad
- **Cuando:** Un administrador del sistema, añada, modifique o elimine una ayuda didactica
- **Dado que:** El sistema se encuentra en estado normal
- **Yo como:** Administrador del sistema
- **Quiero:** Poder realizar cambios en las ayudas didacticas de forma rapida y facil, sin afectar la funcionalidad del resto de ayudas
- **Y debe suceder:** Los cambios deben reflejarse en maximo 5 minutos despues de haberlos aceptado.

## Historia 6
***Pruebas automatizadas***
- **Prioridad:** Alta
- **Atributo de calidad:** Estabilidad y Correctitud del Sistema
- **Cuándo:** Un desarrollador realice cambios en el código del sistema.
- **Dado que:** El sistema cuenta con una suite de pruebas automatizadas configurada.
- **Yo como:** Desarrollador.
- **Quiero:** Ejecutar pruebas automatizadas con JUnit, Mockito, Jasmine y Karma para validar que las modificaciones en el código no introducen errores ni afectan el rendimiento del sistema.
- **Y debe suceder:** El sistema deberá ejecutar pruebas unitarias y de integración automáticamente en cada cambio de código, asegurando que las funcionalidades sigan operando correctamente sin introducir regresiones. Además, las pruebas deberán ejecutarse en menos de 10 segundos y generar reportes claros para facilitar la depuración de errores.

# historias-de-calidad-proyecto-

## Disponibilidad

**Prioridad:** Alta

**Atributo de calidad:** Disponibilidad

**Cuando:** Un profesor intente subir o actualizar un OVA.

**Dado que:** El sistema se encuentra en estado normal.

**Yo como:** Profesor.

**Quiero:** Subir o actualizar simuladores o calculadoras didácticas sin interrupciones ni errores.
Y debe suceder: El sistema deberá permitir la carga o actualización de recursos sin caídas ni pérdida de datos, garantizando que los cambios estén disponibles para los estudiantes en menos de 5 segundos después de la publicación.