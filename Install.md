### 1. Pré-requis
Il vous faudra : 

>> Téléchargement :
>Rendez vous sur ce lien : https://www.tightvnc.com/download.php et cliquez sur **"Installer for Windows (64-bit)"**
>![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/install1.png?raw=true)


>VM Windows Serveur 2022

>> Sa carte réseau doit etre réglé sur "Internal Network".
>> Les Pare-feu doivent être désactivés.
>> 
>> ![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/ConfigVM.png?raw=true)

>une VM Windows 10

>>Sa carte réseau doit être réglé sur "Internal Network".
>>Les Pare-feu doivent être désactivés.
>>
>>![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/ConfigVM.png?raw=true)

### 2. Installation du serveur TightVNC sur votre Serveur
Une fois le téléchargement terminé : lancez l'installer 

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/install2.png?raw=true)
Cliquez sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/install3.png?raw=true)
Acceptez les termes de la license (après l'avoir lu) et clique sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/install4.png?raw=true)
Sélectionnez l'option **"Custom"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/install5serve.png?raw=true)
Dans un premier temps effectuez un clique **GAUCHE** sur l'icone de **"TightVNC Viewer"** 
Ensuite selectionnez l'option "Entire feature will be unavailable"
Grâce à cela, nous évitons d'installer le "Client" de TighVNC qui nous est inutile pour le projet.

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/install6serve.png?raw=true)
Laissez les paramètres par défaut et appuie sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/install7serve.png?raw=true)
Cliquez sur le bouton Installer

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/install8serve.png?raw=true)
Cette étape est optionnel mais je vous recommande fortement de saisir vos mots de passe pour protéger votre serveur TightVNC et empêcher tout client essayant de prendre le controle de votre Serveur sans en avoir le mot de passe !
(Si vous ratez cette étape, pas de panique vous pourrez les configurer plus tard)

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/data/install9serve.png?raw=true)
Félicitations, vous avez terminé l'installation de votre Serveur VNC sur votre Serveur Windows 2022 !

### 3. Installation du client TightVNC
