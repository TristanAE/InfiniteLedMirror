# InfiniteLedMirror
Créer un système de réflexion de leds pour donner l’illusion de profondeur infinie

Projet inspiré de la vidéo : https://youtu.be/sAPGw0SD1DE?list=LL

# I-	Conception électronique 

Nous allons simplement utiliser un ruban de 30 leds programmables que nous allons relier à une Nodemcu. Cette carte nous permettra d’activer différents modes de lumières via l’application Blynk.

# II-	Conception informatique 
Une fois les leds connectées, nous allons utiliser l’interface de Blynk pour les piloter par wifi.

Nous mettons d’abord en place les différents boutons et pins virtuels sur l’application mobile, puis nous instancions le tout dans le code Arduino.

Afin de contrôler les leds individuellement, nous utilisons la bibliothèque FastLed. Ainsi, nous implémentons dans le code différents scénarios en fonction du bouton appuyé sur Blynk

# III-	Conception matérielle  

La conception matérielle est la plus importante. 

Nous utiliserons comme matériels :

•	Un miroir

•	Un plexiglass transparent

•	Un film sans tain

•	Un cadre

•	Une planche

•	Des supports de cadre

Dans un premier temps, nous fixons le ruban led à l’intérieur du cadre de manière à en faire le tour.

Nous venons ensuite placer ce cadre au centre de la planche, puis le miroir derrière.

Après avoir découpé le film sans tain et l’avoir déposé sur le plexiglass, nous fixons celui-ci devant le cadre sur la planche.

Pour maintenir le plexiglass et le miroir droits et en équilibre, nous imprimons en 3D des petits supports à fente permettant aux plaques de glisser dedans.

 
![Picture1](https://user-images.githubusercontent.com/92324336/205495520-6d5325c4-8fc8-44b7-b60b-567a8a3364dc.png)


# IV-	Rendu final 
 

![ezgif com-gif-maker (9)](https://user-images.githubusercontent.com/92324336/205495533-deb8435c-a4ed-4508-9648-fdcb7d7bf7c2.gif)


