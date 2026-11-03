# Privacidad de FocusNotch

Actualizado el 3 de noviembre de 2026.

FocusNotch es un temporizador de estudio para macOS y Windows. Funciona sin cuenta y conserva el historial en el equipo. No registra el contenido de otras aplicaciones, documentos, navegación ni pulsaciones de teclado.

## Sincronización opcional con Google

Al elegir «Continuar con Google», la aplicación utiliza tu identificador de Google y tu correo para reconocer la misma cuenta en ambos equipos. Solicita únicamente los permisos `openid`, `email` y `drive.appdata`. No solicita acceso a Gmail ni a los demás archivos de tu Drive.

El tiempo de estudio y las etiquetas de asignaturas del historial se guardan en el espacio privado de FocusNotch en tu propio Google Drive. También se conservan identificadores de registros y dispositivos y revisiones para evitar duplicados y propagar correcciones. El temporizador en marcha, sus puntos de recuperación y los ajustes permanecen en cada equipo.

Las credenciales de acceso se conservan en el Llavero de macOS o protegidas con DPAPI para el usuario de Windows. La conexión con Google usa HTTPS. FocusNotch no dispone de un servidor propio que reciba tu historial ni utiliza esos datos para publicidad o entrenamiento de modelos. El uso y la transferencia de información obtenida mediante las APIs de Google se ajustan a la [Política de Datos del Usuario de las APIs de Google](https://developers.google.com/terms/api-services-user-data-policy), incluidos sus requisitos de uso limitado.

## Control de tus datos

Puedes usar FocusNotch sin sincronización, exportar una copia local del historial o cerrar la sesión de Google desde Ajustes. Cerrar sesión elimina las credenciales locales y detiene la sincronización; conserva el historial local y la copia de Google.

La opción de borrar historial elimina los registros conocidos por la aplicación y, si hay una cuenta conectada, propaga esa eliminación al sincronizar. Un equipo sin conexión puede tardar en recibirla; registros todavía no sincronizados desde otro equipo pueden aparecer posteriormente. Google permite gestionar o revocar las conexiones de aplicaciones desde tu Cuenta de Google.

## Actualizaciones y contacto

Las comprobaciones y descargas de actualizaciones utilizan GitHub y no envían el historial de estudio. Se aplican las políticas de los servicios utilizados para sus propias conexiones y registros técnicos.

Para consultar o comunicar un problema de privacidad, utiliza [el repositorio de distribución de FocusNotch](https://github.com/Soakkk/FocusNotch-Releases/issues). No incluyas historial personal ni credenciales en una incidencia pública.
