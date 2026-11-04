# CalorII_CuestionarioFinal
Cuestionario de Transferencia de Calor II
Profesor Ph.D. Juan Sandoval Herrera
Universidad de América · 2026

Cuestionario interactivo en HTML con 54 preguntas de selección única, elaborado como recurso formativo a partir de los documentos de la asignatura.

Temas
Evaporadores y condensadores.
Torres de enfriamiento y calderas.
Chillers y autoclaves.
Intercambiadores regenerativos.
Calentamiento solar térmico de piscinas.
Secadores de bandejas.
Características
Orden aleatorio de preguntas y opciones en cada intento.
Pistas sin penalización.
Retroalimentación inmediata con explicación y referencia al material de apoyo.
Navegación entre preguntas y mapa de avance.
Reporte final con aciertos, errores y desempeño por tema.
Calificación de 0,00 a 5,00, calculada como: 5 × aciertos / 54.
Descarga del reporte en TXT o JSON e impresión o guardado como PDF.
Diseño adaptable a computadores y celulares.
Uso local
Descarga 
index.html
 y ábrelo en un navegador con JavaScript habilitado. No requiere instalación, conexión a internet ni bibliotecas externas.

Selecciona una opción y confirma tu respuesta para ver la explicación. Las respuestas confirmadas no pueden modificarse. El reporte estará disponible después de responder todas las preguntas.

Publicación en GitHub Pages
Crea un repositorio en GitHub.
Sube 
index.html
 a la raíz del repositorio.
Ingresa a Settings → Pages.
Selecciona Deploy from a branch.
Elige la rama main y la carpeta / (root); guarda los cambios.
Abre el enlace que GitHub proporciona cuando termine el despliegue.
Archivos

index.html
: cuestionario completo y autocontenido.

preguntas.json
: copia del banco de preguntas para consulta y edición.

README.md
: descripción e instrucciones.
El HTML contiene su propio banco de preguntas: modificar únicamente 
preguntas.json
 no cambia el cuestionario. Para editarlo, actualiza también el arreglo BANK dentro de 
index.html
. La primera opción de cada pregunta es la correcta antes de la aleatorización.

Privacidad y alcance
El cuestionario no envía datos del estudiante ni guarda respuestas automáticamente. Al recargar o cerrar la página se pierde el intento; descarga el reporte para conservarlo.

Es una herramienta de aprendizaje, no una plataforma segura de evaluación: las respuestas están disponibles en el código fuente. No incluye autenticación ni envío de notas al profesor, y no establece un umbral institucional de aprobación.

Los PDF de referencia no se incluyen. Los ejercicios numéricos presentan supuestos didácticos y el contenido no sustituye manuales de operación, protocolos de seguridad ni validación de procesos.

Licencia
© 2026 Profesor Ph.D. Juan Sandoval Herrera.

El contenido original de este proyecto se distribuye bajo la licencia Creative Commons Atribución 4.0 Internacional (CC BY 4.0). Se permite compartirlo y adaptarlo, incluso con fines comerciales, siempre que se reconozca la autoría, se incluya un enlace a la licencia y se indiquen los cambios realizados. No debe sugerirse respaldo del autor a las modificaciones.

Consulta los términos: https://creativecommons.org/licenses/by/4.0/deed.es

Esta licencia no incluye los PDF de referencia ni otros materiales de terceros, cuyos derechos corresponden a sus respectivos titulares. Solo se aplica al material sobre el cual el licenciante tiene derechos suficientes. Creative Commons no recomienda sus licencias para software; esta declaración no asigna una licencia de software al código del cuestionario.
