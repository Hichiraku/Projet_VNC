### 1. Pré-requis
Il vous faudra : 

>> Téléchargement :
>Rendez vous sur ce lien : https://www.tightvnc.com/download.php et cliquez sur **"Installer for Windows (64-bit)"**
>![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install1.png?raw=true)


>VM : Serveur
> Windows Serveur 2022
> 8GB de RAM
> 2 CPU
> 30GB d'espace de stockage

>> Sa carte réseau doit etre réglé sur "Internal Network".
>> Les Pare-feu doivent être désactivés.
>> 
>> ![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/ConfigVM.png?raw=true)

>une VM : Client
>Windows 10
> 4GB de RAM
> 2 CPU
> 30GB d'espace de stockage

>>Sa carte réseau doit être réglé sur "Internal Network".
>>Les Pare-feu doivent être désactivés.
>>
>>![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install2.png?raw=true)

### 2. Installation du serveur TightVNC sur votre Machine Serveur
Une fois le téléchargement terminé : lancez l'installer 

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install2.png?raw=true)


Cliquez sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install3.png?raw=true)

Acceptez les termes de la license (après l'avoir lu) et clique sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install4.png?raw=true)

Sélectionnez l'option **"Custom"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install5serve.png?raw=true)

Dans un premier temps effectuez un clique **GAUCHE** sur l'icone de **"TightVNC Viewer"**  
Ensuite selectionnez l'option **"Entire feature will be unavailable"**  
Grâce à cela, nous évitons d'installer le **"Client"** de TighVNC qui nous est inutile sur la machine **Server** pour le projet.

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install6serve.png?raw=true)

Laissez les paramètres par défaut et appuie sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install7serve.png?raw=true)

Cliquez sur le bouton **"Installer"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install8serve.png?raw=true)

Cette étape est optionnel mais je vous recommande fortement de saisir vos mots de passe pour   
protéger votre serveur TightVNC et empêcher tout client essayant de prendre le controle de votre Serveur  
sans en avoir le mot de passe !    

(Si vous ratez cette étape, pas de panique vous pourrez les configurer plus tard)

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install9serve.png?raw=true)

Félicitations, vous avez terminé l'installation de votre Serveur VNC sur votre Serveur Windows 2022 !

### 3. Installation du client TightVNC sur votre Machine Client

Une fois le téléchargement terminé : lancez l'installer 

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install2.png?raw=true)

Cliquez sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install3.png?raw=true)

Acceptez les termes de la license (après l'avoir lu) et clique sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install4.png?raw=true)

Sélectionnez l'option **"Custom"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install5client.png?raw=true)

Dans un premier temps effectuez un clique **GAUCHE** sur l'icone de **"TightVNC Server"**   

Ensuite selectionnez l'option **"Entire feature will be unavailable"**  

Grâce à cela, nous évitons d'installer le "server" de TighVNC qui nous est inutile sur la machine **Client** pour le projet.  

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install6client.png?raw=true)

Laissez les paramètres par défaut et appuie sur le bouton **"Next"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install7client.png?raw=true)

Cliquez sur le bouton **"Installer"**

![img](https://github.com/Hichiraku/Projet_VNC/blob/main/ressource/install8client.png?raw=true)

Félicitations, vous avez terminé l'installation de votre Client VNC sur votre Windows 10 !

Je vous laisse donc vous rendre dans la partie USER_GUIDE.md pour effectuer les configurations d'usages et lancer votre première prise de contrôle.
