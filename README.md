# 42-netpractice

**Ressources utiles :**

https://www.codequoi.com/adresses-ipv4-routage-et-masques-de-sous-reseau/

https://www.codequoi.com/architecture-du-reseau-internet/

https://www.youtube.com/watch?v=ecCuyq-Wprc

https://openclassrooms.com/fr/courses/6944606-concevez-votre-reseau-tcp-ip/7234467-tirez-le-meilleur-de-ce-cours

http://www.kevinsubileau.fr/informatique/astuces-tutoriels/linux-unix-conversion-base-ligne-de-commande-bc.html

**Conseils :**
* Attention au chevauchement des adresses ip
* Bien comprendre la différence entre un commutateur (switch) et un routeur, ainsi que les valeurs de la table de routage (destination et next hop)
* Attention aux adresses ip privées que l'on ne peut pas utiliser : de 10.0.0.0 à 10.255.255.255 ; de 172.16.0.0 à 172.31.255.255 ; de 192.168.0.0 à 192.168.255.255
* De même pour l'ip locale (de 127.0.0.1 à 127.255.255.254)
* Avoir bien en tête les valeurs de la table CIDR :

![Capture d’écran 2023-02-19 à 22 25 34](https://user-images.githubusercontent.com/96736158/219976132-2aaf8871-1ad9-4331-8a7c-47951499ff9d.png)

**Et si vous restez bloquer sur un niveau :**

Vous trouverez indices et explications pas à pas ici :

https://github.com/tblaase/Net_Practice

https://github.com/viruskizz/42bangkok-netpractice

https://github.com/Laubester/NetPractice
