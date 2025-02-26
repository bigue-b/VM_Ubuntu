# 1️⃣ Prérequis
Avant de commencer, assurez-vous d'avoir installé :

     Vagrant
    VirtualBox
    Un terminal (CMD, PowerShell, Bash...)
    VSCode


🔧 Initialisation du Projet Vagrant

1️⃣ Créez un répertoire pour votre projet :

```bash
mkdir CreationVM-Vagrant
cd CreationVM-Vagrant
```
2️⃣ Initialisez Vagrant dans ce répertoire :

```bash
vagrant init
```
![helm](cap1.png)

📝 Cela génère un fichier Vagrantfile de configuration.

![helm](cap2.png)

⚙ Configuration du Vagrantfile

Modifiez le fichier Vagrantfile pour définir la machine virtuelle souhaitée sur VSCode ou votre éditeur préféré.

Choisissez une box : Visitez Vagrant Cloud et sélectionnez bento/ubuntu-22.04.

![helm](cap3.png)

✅Validation et Démarrage de la VM

Après avoir configuré le Vagrantfile, vous pouvez valider la configuration avec cette commande pour vérifier si la configuration est correcte.

1️⃣ Validez votre configuration

Cette commande permet de vérifier si la configuration est correcte :

```bash
vagrant validate
```
![helm](cap4.png)

2️⃣ Démarrez la machine virtuelle

```bash
vagrant up
```
![helm](cap5.png)

![helm](cap6.png)

3️⃣ Accédez à la VM via SSH

```bash
vagrant ssh 
```
![helm](cap7.png)

Après avoir créé votre machine, vous pouvez vous déconnecter .

```bash
exit
```

Pour suspendre la VM :

```bash
vagrant suspend
```
Pour arrêter la VM :

```bash
vagrant halt
```