# PCGuardControl

## 📝 Introduction

Bienvenue dans **PCGuardControl** — un outil pour contrôler à distance votre ordinateur Windows via Telegram.

Le bot vous permet d'effectuer des actions quotidiennes sur votre PC directement depuis le chat : gérer l'alimentation et le son, travailler avec des fichiers et des applications, obtenir des captures d'écran, contrôler les processus, utiliser une souris et un clavier à distance, lancer la diffusion de l'écran et de la caméra, et bien plus encore.

**Un ou plusieurs administrateurs** sont pris en charge. Par exemple, vous pouvez accorder l'accès à plusieurs utilisateurs de confiance sur le même ordinateur.

Le projet reçoit des mises à jour avec des corrections, des améliorations et de nouvelles fonctionnalités.

---

## 🌟 Fonctionnalités principales

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="resource/image/primarymenuserver.png" width="290px"><br>
        <b>🔧 Navigation pratique</b><br>
        Les fonctions principales sont regroupées dans des sections claires : système, diffusion, processus, multimédia, applications, plugins et autres outils.
      </td>
      <td align="center">
        <img src="resource/image/livecamera.png" width="290px"><br>
        <b>📸 Caméra</b><br>
        Obtenez des images des caméras connectées et utilisez la vidéosurveillance via Telegram.
      </td>
      <td align="center">
        <img src="resource/image/livedesktop.png" width="290px"><br>
        <b>🖥️ Diffusion en direct</b><br>
        Regardez votre bureau en temps réel, choisissez le moniteur, les FPS, la qualité et l'échelle. La diffusion audio séparée est prise en charge.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/language.png" width="290px"><br>
        <b>🌍 8 langues d'interface</b><br>
        Anglais, ukrainien, russe, espagnol, italien, français, allemand et arabe.
      </td>
      <td align="center">
        <img src="resource/image/botconfig.png" width="290px"><br>
        <b>🤖 Configuration du bot</b><br>
        Gérez les administrateurs, le token, le proxy, les utilisateurs et l'emplacement de la configuration. Chaque administrateur peut disposer de paramètres d'accès distincts aux fonctions et sections du bot.
      </td>
      <td align="center">
        <img src="resource/image/panelbot.png" width="290px"><br>
        <b>⚙️ Panneau du bot</b><br>
        Redémarrage, exécution avec droits administrateur, démarrage automatique, notifications, langue, mises à jour, performances, réinitialisation de la configuration et autres paramètres.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/panelsystem.png" width="290px"><br>
        <b>🧰 Panneau système</b><br>
        Accès rapide au système, aux fonctions dangereuses, au nettoyage, à l'installateur de programmes, aux applications, à la diffusion en direct, aux processus, aux médias, aux modules et aux plugins.
      </td>
      <td align="center">
        <img src="resource/image/systemSection.png" width="290px"><br>
        <b>🖥️ Contrôle de Windows</b><br>
        Alimentation, verrouillage de l'écran, déconnexion, réseau, Wi-Fi, redémarrage de l'Explorateur, luminosité, batterie, protection antivol et détecteur de mouvement.
      </td>
      <td align="center">
        <img src="resource/image/PowerPC.png" width="290px"><br>
        <b>🔋 Gestion de l'alimentation</b><br>
        Éteignez, redémarrez ou mettez votre PC en veille prolongée immédiatement ou via une minuterie. Saisie manuelle de l'heure et annulation d'une action programmée disponibles.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/playersettings.png" width="290px"><br>
        <b>🎵 Contrôle multimédia</b><br>
        Contrôlez la lecture et le volume : pause/reprise, piste précédente/suivante, muet et ajustement du niveau de volume.
      </td>
      <td align="center">
        <img src="resource/image/devicecontrol.png" width="290px"><br>
        <b>🖱️ Clavier, souris et presse-papiers</b><br>
        Contrôlez la souris et le clavier, saisissez du texte, envoyez des combinaisons de touches et travaillez avec le presse-papiers.
      </td>
      <td align="center">
        <img src="resource/image/takescreenshot.png" width="290px"><br>
        <b>🖼️ Captures d'écran</b><br>
        Prenez une capture d'un moniteur ou de tous, activez l'affichage du curseur, choisissez le format d'image, la taille et le moniteur par défaut.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/processmonitoring.png" width="290px"><br>
        <b>📊 Surveillance des processus</b><br>
        Suivez le lancement des applications, utilisez une liste noire et recevez des notifications sur les processus détectés ou inconnus.
      </td>
      <td align="center">
        <img src="resource/image/checkprocess.png" width="290px"><br>
        <b>🗂️ Gestionnaire de processus</b><br>
        Affichez les processus en cours, le PID, la charge, les relations parent/enfant, utilisez la recherche et terminez le processus sélectionné.
      </td>
      <td align="center">
        <img src="resource/image/browsercontrol.png" width="290px"><br>
        <b>🌐 Contrôle du navigateur</b><br>
        Changez de page, actualisez un onglet, effectuez une recherche, ouvrez de nouveaux onglets, faites défiler la page et fermez les onglets ou le navigateur.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/installerapp.png" width="290px"><br>
        <b>🔧 Installation de programmes</b><br>
        Installez des applications via Chocolatey : choisissez des catégories, utilisez la recherche, l'installation multiple, mettez à jour les paquets obsolètes ou saisissez le nom du programme manuellement.
      </td>
      <td align="center">
        <img src="resource/image/myaplication.png" width="290px"><br>
        <b>🈸 Mes applications</b><br>
        Ajoutez vos propres programmes avec un nom et un chemin de fichier, puis lancez-les, modifiez-les ou supprimez-les de la liste.
      </td>
      <td align="center">
        <img src="resource/image/filemanager.png" width="290px"><br>
        <b>📂 Gestionnaire de fichiers</b><br>
        Affichez le répertoire actuel et le nombre de dossiers et de fichiers, naviguez entre les disques et les dossiers, revenez en arrière et gérez les fichiers directement depuis Telegram.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/clicker.png" width="290px"><br>
        <b>🔘 Auto-clicker</b><br>
        Lancez des clics automatiques de la souris ou du clavier et mettez-les en pause directement depuis Telegram.
      </td>
      <td align="center">
        <img src="resource/image/jokemenu.png" width="290px"><br>
        <b>🤡 Menu de blagues</b><br>
        Signal sonore, avertissements système, mouvement chaotique de la souris, gel de l'écran, lecture audio, synthèse vocale et secousse de la fenêtre active.
      </td>
      <td align="center">
        <img src="resource/image/scaryfunc.png" width="290px"><br>
        <b>⚠️ Fonctions dangereuses</b><br>
        Une section distincte pour les actions à risque accru, notamment le déclenchement d'un BSOD et la fermeture forcée d'un processus.
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="resource/image/recording.png" width="290px"><br>
        <b>🎬 Enregistrement</b><br>
        Prenez des captures d'écran et des photos avec la caméra, enregistrez une vidéo de la webcam, d'un ou de tous les moniteurs et du son d'un microphone sélectionné. Le périphérique, le moniteur et la durée peuvent être choisis pour l'enregistrement.
      </td>
    </tr>
  </table>
</div>

---

## 📂 Gestion des fichiers et dossiers

PCGuardControl permet de travailler avec le système de fichiers de l'ordinateur sans accès direct au bureau.

- **📁 Navigation dans les dossiers** — déplacez-vous entre les répertoires et consultez leur contenu.
- **📂 Création de dossiers** — créez de nouveaux répertoires à l'emplacement choisi.
- **✏️ Renommage** — modifiez les noms des fichiers et dossiers.
- **🔍 Affichage du contenu** — obtenez une liste des fichiers et dossiers du répertoire actuel.
- **📥 Envoi vers le PC** — envoyez des fichiers de Telegram vers l'ordinateur.
- **📤 Téléchargement depuis le PC** — récupérez les fichiers nécessaires de l'ordinateur vers Telegram.
- **🚀 Exécution de fichiers** — ouvrez des fichiers et des programmes depuis le répertoire sélectionné.
- **🗑️ Suppression** — supprimez les fichiers et dossiers sélectionnés.
- **🔗 Téléchargement via lien** — téléchargez des fichiers sur le PC via un lien direct.

---

## 🛠️ Fonctionnalités supplémentaires

- **💻 Console** — exécutez des commandes Windows à distance.
- **✍️ Saisie de texte** — tapez du texte sur l'ordinateur via Telegram.
- **⌨️ Combinaisons de touches** — envoyez des combinaisons de touches personnalisées.
- **📦 Presse-papiers** — affichez et modifiez le contenu du presse-papiers.
- **👀 Surveillance du presse-papiers** — recevez des notifications lors de sa modification.
- **🗣️ Messages vocaux** — envoyez de l'audio à lire sur l'ordinateur.
- **🛡️ Pare-feu** — gérez l'état du pare-feu Windows depuis le bot.
- **🖥️ Contrôle du moniteur** — allumez ou éteignez le moniteur.
- **⌨️ Verrouillage des entrées** — limitez le fonctionnement de la souris et du clavier.
- **🪫 Contrôle de la batterie** — suivez le niveau de charge de l'ordinateur portable et recevez des notifications.
- **🗂️ Redémarrage de l'Explorateur** — redémarrez l'Explorateur Windows sans redémarrer le PC.
- **🌐 Réseau et Wi-Fi** — gérez les fonctions réseau et les paramètres Wi-Fi.
- **👮 Protection antivol** — activez un mode de protection pouvant verrouiller l'écran en cas d'activité détectée.
- **🎥 Détecteur de mouvement** — utilisez la caméra pour détecter les mouvements.
- **🧩 Modules et plugins** — étendez les capacités du bot via des modules distincts et un gestionnaire de plugins.
- **🧹 Panneau de nettoyage** — accès rapide aux fonctions de nettoyage.

---

## 🖼️ Gestion du fond d'écran

- **📥 Téléchargement d'image** — enregistrez l'image souhaitée sur l'ordinateur.
- **🎨 Définir le fond d'écran** — envoyez une image via Telegram et définissez-la comme fond d'écran du bureau.

---

## 💬 Notifications

- **📝 Notifications système** — affichez des messages sur l'ordinateur.
- **🔔 Notifications du bot** — activez ou désactivez les notifications depuis le panneau.
- **📢 Notification de mise à jour** — le bot peut signaler la sortie d'une nouvelle version.
- **💡 Conseils** — des astuces pour des fonctions spécifiques peuvent être activées si nécessaire.

---

## ⚙️ Panneau du bot et paramètres

Le **panneau du bot** donne accès à :

- redémarrage du bot ;
- redémarrage avec droits administrateur ;
- désactivation du bot ;
- activation/désactivation des notifications ;
- changement de langue ;
- centre de mises à jour ;
- gestion du démarrage automatique ;
- paramètres ;
- réinitialisation de la configuration ;
- configuration du bot ;
- sélection du profil de performance du bot.

---

## 🤖 Configuration du bot

Depuis Telegram, vous pouvez ouvrir un panneau de configuration distinct et gérer :

- **les administrateurs** — ajouter et supprimer des administrateurs, et configurer individuellement l'accès de chacun aux fonctions et sections spécifiques du bot ;
- le token du bot Telegram ;
- le proxy ;
- les utilisateurs ;
- le répertoire de configuration.

---

## 🖥️ Systèmes pris en charge

| Système | Support | Remarque |
|---|---:|---|
| Linux | ❌ | Non pris en charge |
| macOS | ❌ | Non pris en charge |
| Windows 7 | ✔️ | Le démarrage automatique peut nécessiter une activation manuelle via `msconfig` |
| Windows 8 | ✔️ | Le démarrage automatique peut être vérifié via `Gestionnaire des tâches → Démarrage` |
| Windows 10 | ✔️ | Pris en charge |
| Windows 11 | ✔️ | Pris en charge |

---

## ⚠️ Informations importantes

- Le projet est **propriétaire** et n'a pas de code source ouvert.
- Les fonctions de contrôle à distance, de traitement des processus, de saisie, de fichiers et de système peuvent attirer l'attention accrue des antivirus.
- Téléchargez le programme uniquement depuis une source de confiance.
- N'utilisez pas le même token Telegram simultanément dans plusieurs instances du programme.
- Avant d'utiliser les fonctions de la section **Fonctions dangereuses**, vérifiez attentivement l'action sélectionnée.
- Utilisez le programme uniquement sur votre propre ordinateur ou sur des appareils que vous êtes autorisé à contrôler.

### Qu'est-ce que `update.exe` ?

`update.exe` sert à mettre à jour PCGuardControl. Il permet de télécharger et d'installer une nouvelle version sans réinstallation manuelle complète.

### À propos des alertes antivirus

Certains antivirus peuvent réagir aux programmes de contrôle à distance en raison de leurs fonctions liées au système, aux processus, aux fichiers, à la saisie et au réseau.

Si votre antivirus affiche un avertissement :

1. assurez-vous que le fichier provient d'une source officielle ou de confiance ;
2. vérifiez le fichier avec les moyens dont vous disposez ;
3. ajoutez-le aux exceptions uniquement si vous êtes certain de l'origine du fichier.

### 🚨 Clause de non-responsabilité

Les développeurs déclinent toute responsabilité en cas d'utilisation illégale ou non autorisée du programme.

N'utilisez pas PCGuardControl pour accéder à des appareils appartenant à d'autres personnes sans autorisation, pour interférer avec des systèmes appartenant à des tiers ou pour des actions enfreignant la loi ou les droits d'autrui.

---

## ⚙️ Configuration du script

Il existe deux façons de procéder à la configuration initiale.

### Option 1 — automatique

1. Lancez le programme.
2. Si `settings.ini` est absent, il sera créé automatiquement.
3. Indiquez le token du bot Telegram et l'ID de l'administrateur.

### Option 2 — manuelle

Créez un fichier `settings.ini` à côté du programme :

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

> 💡 La section `[Proxy]` est facultative. Si vous n'utilisez pas de proxy, laissez `use_proxy = False`. Si nécessaire, le programme peut créer automatiquement les paramètres manquants.

---

## 🌐 Configuration du proxy

Un proxy peut être utilisé si une connexion directe à Telegram n'est pas disponible ou si un autre itinéraire de connexion est requis.

### Avec identifiant et mot de passe

```ini
[Proxy]
use_proxy = True
proxy_type = http
proxy_url = 45.67.89.10:3128
proxy_user = mylogin
proxy_pass = mypassword
```

### Sans autorisation

```ini
[Proxy]
use_proxy = True
proxy_type = http
proxy_url = 45.67.89.10:3128
proxy_user =
proxy_pass =
```

Types pris en charge :

- `http`
- `https`
- `socks5`

> ⚠️ Les proxys publics gratuits sont souvent instables et peuvent cesser de fonctionner à tout moment.

Si le proxy n'est pas disponible au démarrage, le bot effectue jusqu'à **3 tentatives de connexion**, après quoi il désactive le proxy et démarre via une connexion directe. Si le proxy cesse de fonctionner pendant que le bot est en cours d'exécution, il bascule également vers une connexion directe et envoie une notification à Telegram.

Vous pouvez configurer ou modifier le proxy directement dans le bot :

**Panneau du bot → Configuration du bot → Proxy**

---

## 🔑 Comment obtenir les données de connexion

### 1. Token du bot Telegram

1. Ouvrez [@BotFather](https://t.me/BotFather).
2. Envoyez la commande `/newbot`.
3. Suivez les instructions de Telegram.
4. Copiez le token obtenu dans le paramètre `token` du fichier `settings.ini`.

Exemple de format :

```text
123456789:ABCDefghIJKLMNOPQRSTUVWXYZ
```

> Ne communiquez le token réel du bot à personne. Il permet d'obtenir le contrôle du bot.

### 2. ID Telegram de l'administrateur

Vous pouvez obtenir votre ID Telegram via des bots d'information spécialisés, par exemple `@userinfobot`.

Ajoutez l'ID dans :

```ini
admin_list = 123456789
```

Pour plusieurs administrateurs, indiquez les ID séparés par des virgules :

```ini
admin_list = 123456789, 987654321
```

---