# PCGuardControl

## 📝 Introducción

Bienvenido a **PCGuardControl** — una herramienta para controlar de forma remota tu computadora Windows a través de Telegram.

El bot te permite realizar acciones cotidianas en tu PC directamente desde el chat: gestionar la energía y el sonido, trabajar con archivos y aplicaciones, obtener capturas de pantalla, controlar procesos, usar un mouse y teclado remotos, iniciar transmisión de pantalla y cámara, y mucho más.

Se admite **uno o varios administradores**. Por ejemplo, puedes otorgar acceso a varios usuarios de confianza en la misma computadora.

El proyecto recibe actualizaciones con correcciones, mejoras y nuevas funciones.

---

## 🌟 Funciones principales

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="resource/image/primarymenuserver.png" width="290px"><br>
        <b>🔧 Navegación cómoda</b><br>
        Las funciones principales están organizadas en secciones claras: sistema, transmisión, procesos, multimedia, aplicaciones, plugins y otras herramientas.
      </td>
      <td align="center">
        <img src="resource/image/livecamera.png" width="290px"><br>
        <b>📸 Cámara</b><br>
        Obtén imágenes de las cámaras conectadas y usa videovigilancia a través de Telegram.
      </td>
      <td align="center">
        <img src="resource/image/livedesktop.png" width="290px"><br>
        <b>🖥️ Transmisión en vivo</b><br>
        Observa tu escritorio en tiempo real, elige el monitor, los FPS, la calidad y la escala. Se admite transmisión de audio por separado.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/language.png" width="290px"><br>
        <b>🌍 8 idiomas de interfaz</b><br>
        Inglés, ucraniano, ruso, español, italiano, francés, alemán y árabe.
      </td>
      <td align="center">
        <img src="resource/image/botconfig.png" width="290px"><br>
        <b>🤖 Configuración del bot</b><br>
        Administra administradores, token, proxy, usuarios y la ubicación de la configuración. Cada administrador puede tener configuraciones de acceso independientes a las funciones y secciones del bot.
      </td>
      <td align="center">
        <img src="resource/image/panelbot.png" width="290px"><br>
        <b>⚙️ Panel del bot</b><br>
        Reinicio, ejecución con derechos de administrador, inicio automático, notificaciones, idioma, actualizaciones, rendimiento, restablecimiento de configuración y otros ajustes.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/panelsystem.png" width="290px"><br>
        <b>🧰 Panel del sistema</b><br>
        Acceso rápido al sistema, funciones peligrosas, limpieza, instalador de programas, aplicaciones, transmisión en vivo, procesos, multimedia, módulos y plugins.
      </td>
      <td align="center">
        <img src="resource/image/systemSection.png" width="290px"><br>
        <b>🖥️ Control de Windows</b><br>
        Energía, bloqueo de pantalla, cierre de sesión, red, Wi-Fi, reinicio del Explorador, brillo, batería, protección antirrobo y sensor de movimiento.
      </td>
      <td align="center">
        <img src="resource/image/PowerPC.png" width="290px"><br>
        <b>🔋 Gestión de energía</b><br>
        Apaga, reinicia o pon en hibernación tu PC de inmediato o mediante un temporizador. Se dispone de entrada manual de tiempo y cancelación de una acción programada.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/playersettings.png" width="290px"><br>
        <b>🎵 Control multimedia</b><br>
        Controla la reproducción y el volumen: pausa/reanudación, pista anterior/siguiente, silencio y ajuste del nivel de volumen.
      </td>
      <td align="center">
        <img src="resource/image/devicecontrol.png" width="290px"><br>
        <b>🖱️ Teclado, mouse y portapapeles</b><br>
        Controla el mouse y el teclado, introduce texto, envía combinaciones de teclas y trabaja con el portapapeles.
      </td>
      <td align="center">
        <img src="resource/image/takescreenshot.png" width="290px"><br>
        <b>🖼️ Capturas de pantalla</b><br>
        Toma una captura de un monitor o de todos, activa la visualización del cursor, elige el formato de imagen, el tamaño y el monitor predeterminado.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/processmonitoring.png" width="290px"><br>
        <b>📊 Monitoreo de procesos</b><br>
        Rastrea el inicio de aplicaciones, usa una lista negra y recibe notificaciones sobre procesos detectados o desconocidos.
      </td>
      <td align="center">
        <img src="resource/image/checkprocess.png" width="290px"><br>
        <b>🗂️ Administrador de procesos</b><br>
        Visualiza los procesos en ejecución, PID, carga, relaciones padre/hijo, usa la búsqueda y finaliza el proceso seleccionado.
      </td>
      <td align="center">
        <img src="resource/image/browsercontrol.png" width="290px"><br>
        <b>🌐 Control del navegador</b><br>
        Cambia de página, actualiza una pestaña, realiza una búsqueda, abre nuevas pestañas, desplaza la página y cierra pestañas o el navegador.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/installerapp.png" width="290px"><br>
        <b>🔧 Instalación de programas</b><br>
        Instala aplicaciones mediante Chocolatey: elige categorías, usa la búsqueda, instalación múltiple, actualiza paquetes obsoletos o introduce el nombre del programa manualmente.
      </td>
      <td align="center">
        <img src="resource/image/myaplication.png" width="290px"><br>
        <b>🈸 Mis aplicaciones</b><br>
        Agrega tus propios programas con un nombre y una ruta de archivo, y luego ejecútalos, edítalos o elimínalos de la lista.
      </td>
      <td align="center">
        <img src="resource/image/filemanager.png" width="290px"><br>
        <b>📂 Administrador de archivos</b><br>
        Visualiza el directorio actual y la cantidad de carpetas y archivos, navega entre unidades y carpetas, retrocede y administra archivos directamente desde Telegram.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/clicker.png" width="290px"><br>
        <b>🔘 Autoclicker</b><br>
        Inicia clics automáticos del mouse o del teclado y pausálos directamente desde Telegram.
      </td>
      <td align="center">
        <img src="resource/image/jokemenu.png" width="290px"><br>
        <b>🤡 Menú de bromas</b><br>
        Pitido, advertencias del sistema, movimiento caótico del mouse, congelación de pantalla, reproducción de audio, texto a voz y sacudida de la ventana activa.
      </td>
      <td align="center">
        <img src="resource/image/scaryfunc.png" width="290px"><br>
        <b>⚠️ Funciones peligrosas</b><br>
        Una sección separada para acciones de mayor riesgo, incluyendo provocar una pantalla azul (BSOD) y finalizar un proceso de forma forzada.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/recording.png" width="290px"><br>
        <b>🎬 Grabación</b><br>
        Toma capturas de pantalla y fotos con la cámara, graba video de la webcam, de uno o de todos los monitores y audio desde un micrófono seleccionado. Para la grabación se puede elegir el dispositivo, el monitor y la duración.
      </td>
    </tr>
  </table>
</div>

---

## 📂 Gestión de archivos y carpetas

PCGuardControl permite trabajar con el sistema de archivos de la computadora sin acceso directo al escritorio.

- **📁 Navegación por carpetas** — desplázate entre directorios y visualiza su contenido.
- **📂 Creación de carpetas** — crea nuevos directorios en la ubicación elegida.
- **✏️ Renombrar** — cambia los nombres de archivos y carpetas.
- **🔍 Ver contenido** — obtén una lista de archivos y carpetas del directorio actual.
- **📥 Subir a la PC** — envía archivos desde Telegram a la computadora.
- **📤 Descargar de la PC** — obtén los archivos necesarios de la computadora hacia Telegram.
- **🚀 Ejecutar archivos** — abre archivos y programas del directorio seleccionado.
- **🗑️ Eliminación** — elimina los archivos y carpetas seleccionados.
- **🔗 Descarga por enlace** — descarga archivos a la PC mediante un enlace directo.

---

## 🛠️ Funciones adicionales

- **💻 Consola** — ejecuta comandos de Windows de forma remota.
- **✍️ Entrada de texto** — escribe texto en la computadora a través de Telegram.
- **⌨️ Combinaciones de teclas** — envía combinaciones de teclas personalizadas.
- **📦 Portapapeles** — visualiza y edita el contenido del portapapeles.
- **👀 Monitoreo del portapapeles** — recibe notificaciones cuando cambia.
- **🗣️ Mensajes de voz** — envía audio para reproducirlo en la computadora.
- **🛡️ Firewall** — administra el estado del firewall de Windows desde el bot.
- **🖥️ Control del monitor** — enciende o apaga el monitor.
- **⌨️ Bloqueo de entrada** — restringe el funcionamiento del mouse y el teclado.
- **🪫 Control de batería** — supervisa la carga de la batería del portátil y recibe notificaciones.
- **🗂️ Reinicio del Explorador** — reinicia el Explorador de Windows sin reiniciar la PC.
- **🌐 Red y Wi-Fi** — administra las funciones de red y la configuración Wi-Fi.
- **👮 Protección antirrobo** — activa un modo de protección que puede bloquear la pantalla al detectar actividad.
- **🎥 Sensor de movimiento** — usa la cámara para detectar movimiento.
- **🧩 Módulos y plugins** — amplía las capacidades del bot mediante módulos separados y un administrador de plugins.
- **🧹 Panel de limpieza** — acceso rápido a las funciones de limpieza.

---

## 🖼️ Gestión de fondos de pantalla

- **📥 Carga de imagen** — guarda la imagen deseada en la computadora.
- **🎨 Establecer fondo** — envía una imagen a través de Telegram y establécela como fondo del escritorio.

---

## 💬 Notificaciones

- **📝 Notificaciones del sistema** — muestra mensajes en la computadora.
- **🔔 Notificaciones del bot** — activa o desactiva las notificaciones desde el panel.
- **📢 Notificación de actualizaciones** — el bot puede informar sobre el lanzamiento de una nueva versión.
- **💡 Sugerencias** — de ser necesario, se pueden activar sugerencias para funciones individuales.

---

## ⚙️ Panel del bot y configuración

A través del **panel del bot** se puede acceder a:

- reinicio del bot;
- reinicio con derechos de administrador;
- desactivación del bot;
- activación/desactivación de notificaciones;
- cambio de idioma;
- centro de actualizaciones;
- gestión del inicio automático;
- configuración;
- restablecimiento de la configuración;
- configuración del bot;
- selección del perfil de rendimiento del bot.

---

## 🤖 Configuración del bot

Desde Telegram se puede abrir un panel de configuración independiente y administrar:

- **administradores** — agregar y eliminar administradores, y configurar individualmente el acceso de cada uno a funciones y secciones específicas del bot;
- el token del bot de Telegram;
- proxy;
- usuarios;
- el directorio de configuración.

---

## 🖥️ Sistemas compatibles

| Sistema | Compatibilidad | Nota |
|---|---:|---|
| Linux | ❌ | No compatible |
| macOS | ❌ | No compatible |
| Windows 7 | ✔️ | Puede requerirse habilitación manual del inicio automático mediante `msconfig` |
| Windows 8 | ✔️ | El inicio automático se puede verificar en `Administrador de tareas → Inicio` |
| Windows 10 | ✔️ | Compatible |
| Windows 11 | ✔️ | Compatible |

---

## ⚠️ Información importante

- El proyecto es **propietario** y no cuenta con código fuente abierto.
- Las funciones de control remoto, procesos, entrada, archivos y sistema pueden llamar la atención de los antivirus.
- Descarga el programa únicamente de una fuente en la que confíes.
- No uses el mismo token de Telegram simultáneamente en varias instancias del programa.
- Antes de usar las funciones de la sección **Funciones peligrosas**, verifica cuidadosamente la acción seleccionada.
- Usa el programa únicamente en tu propia computadora o en dispositivos cuyo control esté autorizado.

### ¿Qué es `update.exe`?

`update.exe` se utiliza para actualizar PCGuardControl. Permite descargar e instalar una nueva versión sin una reinstalación manual completa.

### Sobre las alertas de antivirus

Algunos antivirus pueden reaccionar ante programas de control remoto debido a sus funciones relacionadas con el sistema, los procesos, los archivos, la entrada y la red.

Si tu antivirus muestra una advertencia:

1. asegúrate de que el archivo provenga de una fuente oficial o confiable;
2. verifica el archivo con las herramientas disponibles;
3. agrégalo a las excepciones solo si estás seguro del origen del archivo.

### 🚨 Descargo de responsabilidad

Los desarrolladores no se hacen responsables del uso ilegal o no autorizado del programa.

No uses PCGuardControl para acceder a dispositivos ajenos sin permiso, interferir en sistemas de terceros o realizar acciones que infrinjan la ley o los derechos de otras personas.

---

## ⚙️ Configuración del script

Existen dos formas de realizar la configuración inicial.

### Opción 1 — automática

1. Ejecuta el programa.
2. Si falta `settings.ini`, se creará automáticamente.
3. Indica el token del bot de Telegram y el ID del administrador.

### Opción 2 — manual

Crea junto al programa un archivo `settings.ini`:

```ini
[BotConfig]
token = YOUR_BOT_TOKEN
admin_list = 123456789, 987654321

[Proxy]
use_proxy = False
proxy_type = http
proxy_url = ip:port
proxy_user =
proxy_pass =
```

> 💡 La sección `[Proxy]` es opcional. Si no usas proxy, deja `use_proxy = False`. Si es necesario, el programa puede crear los parámetros faltantes automáticamente.

---

## 🌐 Configuración de proxy

Se puede usar un proxy si la conexión directa a Telegram no está disponible o se requiere otra ruta de conexión.

### Con usuario y contraseña

```ini
[Proxy]
use_proxy = True
proxy_type = http
proxy_url = 45.67.89.10:3128
proxy_user = mylogin
proxy_pass = mypassword
```

### Sin autorización

```ini
[Proxy]
use_proxy = True
proxy_type = http
proxy_url = 45.67.89.10:3128
proxy_user =
proxy_pass =
```

Tipos compatibles:

- `http`
- `https`
- `socks5`

> ⚠️ Los proxies públicos gratuitos suelen ser inestables y pueden dejar de funcionar en cualquier momento.

Si el proxy no está disponible al inicio, el bot realiza hasta **3 intentos de conexión**, tras lo cual desactiva el proxy e inicia mediante una conexión directa. Si el proxy deja de funcionar mientras el bot está en ejecución, también cambia a una conexión directa y envía una notificación a Telegram.

Puedes configurar o cambiar el proxy directamente en el bot:

**Panel del bot → Configuración del bot → Proxy**

---

## 🔑 Cómo obtener los datos de inicio

### 1. Token del bot de Telegram

1. Abre [@BotFather](https://t.me/BotFather).
2. Envía el comando `/newbot`.
3. Sigue las instrucciones de Telegram.
4. Copia el token obtenido en el parámetro `token` del archivo `settings.ini`.

Ejemplo de formato:

```text
123456789:ABCDefghIJKLMNOPQRSTUVWXYZ
```

> No compartas el token real del bot con nadie. Con él se puede obtener el control del bot.

### 2. ID de Telegram del administrador

Puedes obtener tu ID de Telegram a través de bots de información especializados, por ejemplo `@userinfobot`.

Agrega el ID en:

```ini
admin_list = 123456789
```

Para varios administradores, indica los ID separados por comas:

```ini
admin_list = 123456789, 987654321
```

---