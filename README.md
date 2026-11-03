# FocusNotch

Temporizador flotante para macOS y Windows 11. Canal oficial de instaladores y actualizaciones firmadas; el código fuente se mantiene privado.

## Descargar

- [macOS: FocusNotch 2.11.0.dmg](https://github.com/Soakkk/FocusNotch-Releases/releases/download/v2.11.0/FocusNotch-2.11.0.dmg). macOS 14 o posterior; Apple Silicon e Intel.
- [Windows 11 x64: FocusNotch Setup 2.11.0](https://github.com/Soakkk/FocusNotch-Releases/releases/download/windows-v2.11.0/FocusNotch-Windows-x64-Setup.exe). Instalación por usuario.

## Novedades de 2.11.0

- **Panel grande revisado:** tipografía propia de cada tema, reloj digital, sesión actual y estudio de hoy claramente separados, con acciones lado a lado.
- **Barra fina y redondeada:** café y flecha son dos botones independientes. El café controla el descanso y la flecha despliega el panel.
- **Finalizar desde la barra:** doble clic sobre el reloj abre «¿Finalizar sesión?». «Seguir» cancela; «Finalizar y guardar» conserva lo estudiado. Arrastrar no activa la confirmación.
- Conserva el historial, la cuenta de Google, los ajustes y la misma instalación con actualizaciones automáticas.

## Historial compartido con Google

**Un historial entre tus equipos.** «Continuar con Google» abre el navegador y conecta la cuenta que ya utilizas. El tiempo guardado al pausar, descansar, finalizar o cerrar se reúne en el historial. Cada equipo mantiene su reloj y sus ajustes: el otro ordenador no reanuda el minuto exacto donde lo dejaste. Sin conexión, el estudio queda guardado y se sincroniza después. Las sesiones y los intervalos de estudio solapados no se cuentan dos veces.

En Mac entra en **Ajustes → General**; en Windows, **Ajustes → Cuenta**. Inicia sesión una vez en cada equipo con la misma cuenta de Google y concede el permiso para guardar los datos propios de FocusNotch. No necesitas instalar Drive ni elegir carpetas.

El historial se guarda en el espacio privado de la aplicación en Google Drive. FocusNotch no solicita acceso a Gmail ni a tus otros archivos de Drive. La conexión es opcional: puedes seguir usando la app solo en tu equipo. [Política de privacidad](PRIVACY.md).

**Cinco temas revisados:** Grafito, Marfil, Cristal, Neón suave y Pixel. Cada uno conserva sus colores y controles; Neón y Pixel tienen dígitos propios. Cristal utiliza el material translúcido del sistema cuando está disponible y respeta la opción de reducir transparencia.

**Barra más cómoda en Mac.** Se puede arrastrar por todas las zonas libres, incluida la parte derecha. La mano se abre al pasar por una zona de arrastre y se cierra al agarrarla. Los botones conservan sus acciones.

## Estudio y descanso

Puedes dar al primer bloque una duración distinta a los siguientes: por ejemplo, **50/10 → 25/5**, además de los preajustes uniformes. El resumen diario cuenta el tiempo estudiado, y el historial conserva los días anteriores.

En Mac, **Ajustes → Sesión → Confirmar los cambios entre estudio y descanso** mantiene el estudio en «Tiempo extra» al terminar el bloque. Ese tiempo sigue sumando. **El botón del café** inicia el descanso completo cuando lo decides; al terminar, **Volver a estudiar** inicia el siguiente bloque. Los avisos tienen volumen ajustable.

## Si ya tienes FocusNotch

Utiliza las actualizaciones de la propia app. Reemplazan la misma instalación y conservan el historial y los ajustes.

- En Mac, la búsqueda y descarga automáticas están activadas por defecto; también puedes usar «Buscar actualizaciones». Se instala al salir cuando es posible.
- En Windows, con las actualizaciones automáticas activadas, la app comprueba la nueva versión al arrancar, la descarga en segundo plano y aplica la actualización al salir o en el siguiente inicio.

Para una primera instalación en Mac, abre el DMG y arrastra FocusNotch a Aplicaciones. Si ya existe allí, sustitúyela. En Windows, ejecuta el instalador. Los ZIP de código fuente que GitHub genera automáticamente no son instaladores.

Esta distribución personal de macOS usa firma local ad hoc, sin notarización de Apple. Mantiene sandbox y firmas del catálogo y actualizaciones, con una excepción de validación de bibliotecas limitada a FocusNotch para cargar el actualizador.

Este repositorio contiene únicamente información de distribución, catálogos firmados e instaladores. No contiene código fuente de la app, claves privadas ni datos de sesiones.
