# PCGuardControl

## 📝 Introduction

Welcome to **PCGuardControl** — a tool for remotely controlling your Windows computer via Telegram.

The bot lets you perform everyday actions on your PC right from chat: manage power and sound, work with files and applications, get screenshots, control processes, use a remote mouse and keyboard, start screen and camera streaming, and much more.

**One or multiple administrators** are supported. For example, you can grant access to several trusted users on the same computer.

The project receives updates with fixes, improvements, and new features.

---

## 🌟 Key features

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="resource/image/primarymenuserver.png" width="290px"><br>
        <b>🔧 Convenient navigation</b><br>
        Core functions are organized into clear sections: system, streaming, processes, media, applications, plugins, and other tools.
      </td>
      <td align="center">
        <img src="resource/image/livecamera.png" width="290px"><br>
        <b>📸 Camera</b><br>
        Get images from connected cameras and use video surveillance via Telegram.
      </td>
      <td align="center">
        <img src="resource/image/livedesktop.png" width="290px"><br>
        <b>🖥️ Live streaming</b><br>
        Watch your desktop in real time, choose the monitor, FPS, quality, and scale. Separate audio streaming is supported.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/language.png" width="290px"><br>
        <b>🌍 8 interface languages</b><br>
        English, Ukrainian, Russian, Spanish, Italian, French, German, and Arabic.
      </td>
      <td align="center">
        <img src="resource/image/botconfig.png" width="290px"><br>
        <b>🤖 Bot configuration</b><br>
        Manage administrators, token, proxy, users, and the configuration location. Each administrator can have separate access settings for bot features and sections.
      </td>
      <td align="center">
        <img src="resource/image/panelbot.png" width="290px"><br>
        <b>⚙️ Bot panel</b><br>
        Restart, run as administrator, autostart, notifications, language, updates, performance, configuration reset, and other settings.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/panelsystem.png" width="290px"><br>
        <b>🧰 System panel</b><br>
        Quick access to the system, dangerous functions, cleanup, app installer, applications, live streaming, processes, media, modules, and plugins.
      </td>
      <td align="center">
        <img src="resource/image/systemSection.png" width="290px"><br>
        <b>🖥️ Windows control</b><br>
        Power, screen lock, sign out, network, Wi-Fi, Explorer restart, brightness, battery, anti-theft protection, and motion sensor.
      </td>
      <td align="center">
        <img src="resource/image/PowerPC.png" width="290px"><br>
        <b>🔋 Power management</b><br>
        Shut down, restart, or hibernate your PC immediately or on a timer. Manual time entry and cancelling a scheduled action are available.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/playersettings.png" width="290px"><br>
        <b>🎵 Media control</b><br>
        Control playback and volume: pause/resume, previous/next track, mute, and volume level adjustment.
      </td>
      <td align="center">
        <img src="resource/image/devicecontrol.png" width="290px"><br>
        <b>🖱️ Keyboard, mouse, and clipboard</b><br>
        Control the mouse and keyboard, enter text, send key combinations, and work with the clipboard.
      </td>
      <td align="center">
        <img src="resource/image/takescreenshot.png" width="290px"><br>
        <b>🖼️ Screenshots</b><br>
        Take a screenshot of one or all monitors, enable cursor display, choose image format, size, and default monitor.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/processmonitoring.png" width="290px"><br>
        <b>📊 Process monitoring</b><br>
        Track application launches, use a blacklist, and get notifications about detected or unknown processes.
      </td>
      <td align="center">
        <img src="resource/image/checkprocess.png" width="290px"><br>
        <b>🗂️ Process manager</b><br>
        View running processes, PID, load, parent/child relationships, use search, and terminate a selected process.
      </td>
      <td align="center">
        <img src="resource/image/browsercontrol.png" width="290px"><br>
        <b>🌐 Browser control</b><br>
        Switch pages, refresh a tab, perform a search, open new tabs, scroll the page, and close tabs or the browser.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/installerapp.png" width="290px"><br>
        <b>🔧 App installation</b><br>
        Install applications via Chocolatey: choose categories, use search, multi-install, update outdated packages, or enter a program name manually.
      </td>
      <td align="center">
        <img src="resource/image/myaplication.png" width="290px"><br>
        <b>🈸 My applications</b><br>
        Add your own programs with a name and file path, then launch, edit, or remove them from the list.
      </td>
      <td align="center">
        <img src="resource/image/filemanager.png" width="290px"><br>
        <b>📂 File manager</b><br>
        View the current directory and the number of folders and files, navigate between drives and folders, go back, and manage files right from Telegram.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/clicker.png" width="290px"><br>
        <b>🔘 Auto-clicker</b><br>
        Start automatic mouse or keyboard clicks and pause them right from Telegram.
      </td>
      <td align="center">
        <img src="resource/image/jokemenu.png" width="290px"><br>
        <b>🤡 Prank menu</b><br>
        Beep sound, system warnings, chaotic mouse movement, screen freeze, audio playback, text-to-speech, and active window shaking.
      </td>
      <td align="center">
        <img src="resource/image/scaryfunc.png" width="290px"><br>
        <b>⚠️ Dangerous functions</b><br>
        A separate section for higher-risk actions, including triggering a BSOD and force-terminating a process.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/recording.png" width="290px"><br>
        <b>🎬 Recording</b><br>
        Take screenshots and camera photos, record webcam video, one or all monitors, and audio from a selected microphone. Device, monitor, and duration can be chosen for recording.
      </td>
    </tr>
  </table>
</div>

---

## 📂 File and folder management

PCGuardControl lets you work with the file system without direct desktop access.

- **📁 Folder navigation** — move between directories and view their contents.
- **📂 Folder creation** — create new directories in a chosen location.
- **✏️ Renaming** — change names of files and folders.
- **🔍 View contents** — get a list of files and folders in the current directory.
- **📥 Upload to PC** — send files from Telegram to the computer.
- **📤 Download from PC** — get needed files from the computer into Telegram.
- **🚀 Run files** — open files and programs from the selected directory.
- **🗑️ Deletion** — delete selected files and folders.
- **🔗 Download by link** — download files to the PC via a direct link.

---

## 🛠️ Additional features

- **💻 Console** — run Windows commands remotely.
- **✍️ Text input** — type text on the computer via Telegram.
- **⌨️ Key combinations** — send custom key combinations.
- **📦 Clipboard** — view and edit clipboard contents.
- **👀 Clipboard monitoring** — get notifications when it changes.
- **🗣️ Voice messages** — send audio to play back on the computer.
- **🛡️ Firewall** — manage Windows Firewall status from the bot.
- **🖥️ Monitor control** — turn the monitor on or off.
- **⌨️ Input lock** — restrict mouse and keyboard operation.
- **🪫 Battery monitoring** — track laptop battery charge and get notifications.
- **🗂️ Explorer restart** — restart Windows Explorer without rebooting the PC.
- **🌐 Network and Wi-Fi** — manage network features and Wi-Fi settings.
- **👮 Anti-theft protection** — enable a protective mode that can lock the screen when activity is detected.
- **🎥 Motion sensor** — use the camera to detect motion.
- **🧩 Modules and plugins** — extend the bot's capabilities through separate modules and a plugin manager.
- **🧹 Cleanup panel** — quick access to cleanup functions.

---

## 🖼️ Wallpaper management

- **📥 Image upload** — save the desired picture on the computer.
- **🎨 Set wallpaper** — send an image via Telegram and set it as the desktop background.

---

## 💬 Notifications

- **📝 System notifications** — show messages on the computer.
- **🔔 Bot notifications** — enable or disable notifications from the panel.
- **📢 Update notification** — the bot can report the release of a new version.
- **💡 Tips** — hints for individual functions can be enabled if needed.

---

## ⚙️ Bot panel and settings

The **bot panel** provides access to:

- restarting the bot;
- restarting with administrator rights;
- disabling the bot;
- enabling/disabling notifications;
- changing the language;
- update center;
- autostart management;
- settings;
- configuration reset;
- bot configuration;
- selecting the bot's performance profile.

---

## 🤖 Bot configuration

From Telegram you can open a separate configuration panel and manage:

- **administrators** — add and remove administrators, and configure each one's access to specific bot features and sections individually;
- the Telegram bot token;
- proxy;
- users;
- the configuration directory.

---

## 🖥️ Supported systems

| System | Support | Note |
|---|---:|---|
| Linux | ❌ | Not supported |
| macOS | ❌ | Not supported |
| Windows 7 | ✔️ | Autostart may require manual enabling via `msconfig` |
| Windows 8 | ✔️ | Autostart can be checked via `Task Manager → Startup` |
| Windows 10 | ✔️ | Supported |
| Windows 11 | ✔️ | Supported |

---

## ⚠️ Important information

- The project is **proprietary** and does not have open source code.
- Remote control, process, input, file, and system functions may draw increased attention from antivirus software.
- Only download the program from a source you trust.
- Do not use the same Telegram token in multiple instances of the program at the same time.
- Carefully check the selected action before using functions from the **Dangerous functions** section.
- Only use the program on your own computer or on devices you are authorized to control.

### What is `update.exe`?

`update.exe` is used to update PCGuardControl. It lets you download and install a new version without a full manual reinstall.

### About antivirus flags

Some antivirus software may react to remote-control programs due to their system, process, file, input, and network functions.

If your antivirus shows a warning:

1. make sure the file was obtained from an official or trusted source;
2. check the file using the tools available to you;
3. add it to exceptions only if you are confident about the file's origin.

### 🚨 Disclaimer

The developers are not responsible for illegal or unauthorized use of the program.

Do not use PCGuardControl to access other people's devices without permission, to interfere with other people's systems, or for actions that violate the law or the rights of others.

---

## ⚙️ Setting up the script

There are two ways to do the initial setup.

### Option 1 — automatic

1. Run the program.
2. If `settings.ini` is missing, it will be created automatically.
3. Enter your Telegram bot token and admin ID.

### Option 2 — manual

Create a `settings.ini` file next to the program:

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

> 💡 The `[Proxy]` section is optional. If you don't use a proxy, leave `use_proxy = False`. If needed, the program can create missing parameters automatically.

---

## 🌐 Proxy setup

A proxy can be used if a direct connection to Telegram is unavailable or a different connection route is required.

### With login and password

```ini
[Proxy]
use_proxy = True
proxy_type = http
proxy_url = 45.67.89.10:3128
proxy_user = mylogin
proxy_pass = mypassword
```

### Without authorization

```ini
[Proxy]
use_proxy = True
proxy_type = http
proxy_url = 45.67.89.10:3128
proxy_user =
proxy_pass =
```

Supported types:

- `http`
- `https`
- `socks5`

> ⚠️ Free public proxies are often unstable and may stop working at any time.

If the proxy is unavailable at startup, the bot makes up to **3 connection attempts**, after which it disables the proxy and starts via a direct connection. If the proxy stops working while the bot is running, it also switches to a direct connection and sends a notification to Telegram.

You can configure or change the proxy directly in the bot:

**Bot panel → Bot configuration → Proxy**

---

## 🔑 How to get the launch credentials

### 1. Telegram bot token

1. Open [@BotFather](https://t.me/BotFather).
2. Send the `/newbot` command.
3. Follow Telegram's instructions.
4. Copy the resulting token into the `token` parameter in the `settings.ini` file.

Format example:

```text
123456789:ABCDefghIJKLMNOPQRSTUVWXYZ
```

> Never share your real bot token with anyone. It can be used to gain control of the bot.

### 2. Administrator Telegram ID

You can get your Telegram ID via dedicated information bots, for example `@userinfobot`.

Add the ID to:

```ini
admin_list = 123456789
```

For multiple administrators, separate IDs with a comma:

```ini
admin_list = 123456789, 987654321
```

---