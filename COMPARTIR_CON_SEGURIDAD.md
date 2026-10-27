# Publicación del portafolio

## Qué contiene este proyecto

Ejercicio de aprendizaje basado en IT Spend Analysis, muestra pública de Microsoft/obviEnce con datos anonimizados. No representa información de FEMSA, Castaño, clientes ni proveedores del autor.

## Paquete propuesto

- README, atribución y licencia de la fuente.
- Captura del dashboard, PDF estático del informe y capturas del análisis de Excel.
- Medidas DAX propias y descripción de las validaciones.
- Libro de Excel de muestra que ya forma parte del repositorio.

El PBIX y el proyecto completo de Power BI se conservan localmente. No se incluyen en esta actualización pública: el modelo contiene datos importados y consultas heredadas que apuntan a una ruta local de la fuente original. Un archivo PBIX puede contener mucho más que lo visible en los gráficos. El filtro de un visual y ocultar columnas no eliminan los datos del archivo.

## Revisión realizada el 26 de octubre de 2026

- Se inspeccionaron las definiciones de tablas, consultas, medidas y relaciones exportadas por Power BI.
- Se identificó una ruta heredada a Data.xlsx de obviEnce; no corresponde a un sistema laboral del autor. La actualización automática no está validada y no se promete que funcione en otro equipo.
- No se encontraron contraseñas, tokens ni conexiones a sistemas de FEMSA o Castaño en esas definiciones.
- Se inspeccionaron metadatos, conexiones y vínculos externos del Excel incluido. No contiene macros VBA. Conserva el vínculo heredado a Info ya documentado en README.
- Los cachés binarios del modelo no se auditaron registro por registro. Por ese motivo no se incluyen nuevos archivos de datos ni modelos binarios en el paquete propuesto.
- Las imágenes públicas deben mostrar solo el informe, sin escritorio, correos, notificaciones, teléfonos ni rutas del equipo.
- Se revisó visualmente la exportación PDF y su imagen. El PDF tiene una página, sin archivos adjuntos y sin rutas locales en el texto extraído. Sus metadatos indican PDFium como creador/productor, sin nombre de usuario ni correo.

Esto documenta controles concretos, no una garantía absoluta de seguridad ni una revisión de todos los demás repositorios del autor.

## Regla para próximos proyectos

1. Usar datos públicos con permiso y atribución, o datos ficticios creados para demostrar el trabajo.
2. No subir documentos del empleador, bases personales, facturas reales, RUT, correos privados, credenciales ni respaldos.
3. Revisar todas las hojas, tablas ocultas, consultas, conexiones, archivos incrustados, metadatos y cachés; no solo la hoja o página visible.
4. Revisar la lista exacta de archivos y el cambio antes de publicar. No ejecutar `git add .` sin inspeccionarlo.
5. Mantener .env, bases privadas y configuraciones locales fuera del repositorio. .gitignore no elimina archivos que ya estaban publicados ni limpia el historial.
6. Si se publica una credencial por error, revocarla y revisar el historial; borrar el archivo actual no es suficiente.
7. Conservar una copia local del original. Publicar solo el paquete revisado.

Fuentes:
- https://learn.microsoft.com/en-us/power-bi/create-reports/sample-it-spend
- https://learn.microsoft.com/en-us/power-bi/create-reports/sample-datasets#legal-guidelines-for-using-samples
- https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-overview
