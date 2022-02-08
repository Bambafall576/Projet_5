# Projet_5
Création microLinux

Ce projet_5 consiste à crée un micro Linux qu'on pourra par la suite mettre dans une carte SD et l'intréger sur une carte rapberry_pi ou tout type d'appareils embarqués capables de prendre un OS.

Pour ce faire, on a suivi des tutoriels et ainsi télécharger virtuelBox sur notre machine personnelle ensuite télécharger la machine virtuelle pour Linux (UBUNTU) et grace au terminal de ce dernier, on exécute les commandes suivantes:

sudo apt-get install libncurses5-dev bc

sudo apt install build-essential #telecharger buildroot

sudo apt-get install manpages-dev unzip

sudo apt-get upgrade 

sudo apt-get update

git clone https://github.com/buildroot/buildroot.git # cloner buildroot

make raspberrypi3_defconfig #fichier de configuration pour notre platforme RP3

make menuconfig # Panneau de configuration

make #Pour Générer l'image

Vous pouvez télécharger l'image de MicroLinux ainsi crée sur le drive suivant: https://drive.google.com/file/d/17e6TqwNUmZGBkknBM2SkWO_1hIUnjBrL/view?usp=sharing.
