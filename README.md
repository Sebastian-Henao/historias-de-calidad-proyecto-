# Aplicacion: Pagina web para gestion de OVAs (Objetos Virtuales para el Aprendizaje)

## Historia 1
***Escalabilidad***
- **Prioridad:** Alta. 
- **Atributo de calidad:** Escalabilidad.
- **Cuando:** La cantidad de usuarios simultáneos aumenta significativamente.  
- **Dado que:** Los profesores suben simuladores y calculadoras didácticas a la plataforma, y los estudiantes deben acceder a estos recursos sin interrupciones.  
- **Yo como:** Administrador del sistema.  
- **Quiero:** Que la aplicación web pueda soportar un alto número de usuarios concurrentes sin degradar el rendimiento.  
- **Y debe suceder:** Que el sistema escale automáticamente sus recursos (servidores, bases de datos, almacenamiento) para mantener tiempos de respuesta óptimos y garantizar el acceso ininterrumpido a los OVA.

## Historia 2
- **Prioridad:** Alta
- **Atributo de calidad:** Disponibilidad
- **Cuando:** Un profesor intente subir o actualizar un OVA.
- **Dado que:** El sistema se encuentra en estado normal.
- **Yo como:** Profesor.
- **Quiero:** Subir o actualizar simuladores o calculadoras didácticas sin interrupciones ni errores.
Y debe suceder: El sistema deberá permitir la carga o actualización de recursos sin caídas ni pérdida de datos, garantizando que los cambios estén disponibles para los estudiantes en menos de 5 segundos después de la publicación.

## Historia 3

- **Prioridad:** Alta  
- **Atributo de calidad:** Seguridad  
- **Cuando:** Un usuario intente acceder a los Objetos Virtuales de Aprendizaje (OVA).  
- **Dado que:** La aplicación maneja recursos educativos que deben estar protegidos contra accesos no autorizados.  
- **Yo como:** Usuario del sistema (profesor o estudiante).  
- **Quiero:** Que el acceso a los OVA esté protegido mediante autenticación segura y control de permisos.  
- **Y debe suceder:** Que solo los usuarios autorizados (profesores y estudiantes registrados) puedan acceder a los recursos educativos, evitando accesos no autorizados mediante autenticación segura, cifrado de datos y protección contra ataques externos. 

## Historia 4

- **Prioridad:** Media  
- **Atributo de calidad:** Monitoreo  
- **Cuando:** Un administrador quiera supervisar el uso de los Objetos Virtuales de Aprendizaje (OVA).  
- **Dado que:** Es importante conocer cómo se utilizan los recursos educativos dentro de la plataforma.  
- **Yo como:** Administrador del sistema.  
- **Quiero:** Tener acceso a métricas y reportes sobre el uso de los OVA por parte de profesores y estudiantes.  
- **Y debe suceder:** Que el sistema registre y muestre información en tiempo real sobre la cantidad de accesos, frecuencia de uso y tipos de recursos utilizados, permitiendo generar reportes para mejorar la gestión y optimización de los OVA.  

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


