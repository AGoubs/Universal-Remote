# Universal Remote
Universal remote controler with arduino

Library Download : https://github.com/markszabo/IRremoteESP8266

Hardware : 

![alt tag](https://user-images.githubusercontent.com/39366401/40787534-2884d036-64ee-11e8-9586-2d007c10d1d0.jpg)

More information [here](https://github.com/AGoubs/Projet-Stage/blob/master/Doc/README.md)

Description : 

This box allows you to save a code when the switch is activated (a remote control button code for example). When a code is detected, the              led flashes and the code is stored in the read-only memory of the card.
When the switch is desactivated, you can activate the box with internet and the bix will return the saved code. (To turn your TV on...)

The basic application of this box is to turn on projectors via a web interface:

![alt tag](https://user-images.githubusercontent.com/39366401/41294090-70e8a2ae-6e57-11e8-9c2b-2744ffa6bab3.png)

On this interface you can:
- Turn ON or OFF video projector
- Change DNS name
- Configure if the projector is turned on by pressing the button 1 or 2 times or a second OFF button
- Erase memory

/***********************************************************************************************************************************/
# Télécommande universelle

Télécommande universelle commandée par Arduino

Téléchargement de la librairie : https://github.com/markszabo/IRremoteESP8266

Hardware : 

![alt tag](https://user-images.githubusercontent.com/39366401/40787534-2884d036-64ee-11e8-9586-2d007c10d1d0.jpg)

Plus d'information [ici](https://github.com/AGoubs/Projet-Stage/blob/master/Doc/README.md)

Description:

Ce boîtier permet d'enregistrer un code lorsque le switch est activé (un code de bouton d'allumage de télécommande par exemple).
Lorsqu'un code est détécté, la led clignote et le code est enregistré dans la mémoire morte de la carte.

La deuxième application de ce boitier est qu'a l'activation sur internet, le boitier peut renvoyer le code enregistré (pour allumer un vidéoprojecteur ou une télé par exemple).


L'application de base de ce boîtier est d'allumer des projecteurs via une interface web :

![alt tag](https://user-images.githubusercontent.com/39366401/41294090-70e8a2ae-6e57-11e8-9c2b-2744ffa6bab3.png)

Sur cette interface vous pouvez :
- **Allumer :** Envoie le code d'allumage du projecteur
- **Eteindre :** Envoie le code d'allumage du projecteur (pour l'éteindre)
- **Eteindre avec confirmation :** Envoie le code d'allumage du projecteur deux fois. Certains vidéoprojecteurs nécessite une confirmation     pour éteindre le projecteur.

- **Allumer :** Envoie le code d'allumage du projecteur
- **Eteindre :** Envoie le code d'extinction du projecteur (certains projecteurs nécessite deux boutons pour allumer/éteindre le vp)
- **Eteindre avec l'EEPROM :** Envoie le code enregistré dans la mémoire

- **Nom du DNS :** Permet de changer le nom du DNS
- **Eteindre **: Enregistre dans la mémoire que par défaut, ce projecteur ne nécessite qu'un code pour éteindre et allumer le vp
- **Eteindre avec confirmation :** Enregistre dans la mémoire que par défaut, ce projecteur nécessite deux code pour éteindre et allumer le   vp

- **Code d'extinction différent de l'allumage :** Permet d'enregistrer le deuxième code pour les vp nécessitant deux boutons
- **Tout effacer :** Permet d'effacer la mémoire
