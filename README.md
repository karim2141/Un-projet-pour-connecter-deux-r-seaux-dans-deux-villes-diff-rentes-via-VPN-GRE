# Un-projet-pour-connecter-deux-r-seaux-dans-deux-villes-diff-rentes-via-VPN-GRE
Ce projet a été mis en œuvre pour connecter deux entreprises situées dans deux villes différentes, la première entreprise étant située à **Errachidia** tandis que la deuxième entreprise est située à **Rabat**. L'objectif du projet est de réaliser une connexion sécurisée et efficace entre les deux entreprises à l'aide d'un réseau privé virtuel (VPN) et des protocoles Cisco, tout en assurant la sécurité du réseau local.
	Détails du projet :

1.	Configurez la connexion via VPN GRE :
 Un tunnel **VPN GRE** a été créé entre les routeurs des deux sociétés pour permettre un transfert sécurisé des données sur Internet, permettant une communication fluide entre les employés des deux sociétés à Rabat et Rachidia.
2.	Mise en place du pare-feu ASA 5505** dans l'entreprise d'Errachidia :
 **ASA 5505** a été placé dans l'entreprise située à Errachidia pour agir comme un pare-feu, car il a été configuré pour appliquer des règles de sécurité qui empêchent l'accès non autorisé au réseau local, et une **zone DMZ** a été créée dans cette entreprise. réseau.
 La zone **DMZ** permet l'accès public à certains services comme les serveurs publics, tout en empêchant les utilisateurs externes d'accéder au réseau interne.
Nous disposons d'un serveur web et d'un serveur DNS dans une entreprise à Errachidia qui sont accessibles à tous, c'est-à-dire connectés à Internet. ‘’dmz zone "
Un serveur web est disponible dans l'entreprise à Rabat  Il n'est disponible que sur les connexions qui passent par le tunnel  VPN
3.	Configuration LAN utilisant les technologies Cisco : 
 EtherChannel a été configuré sur tous les commutateurs.
 Port Security est mis en œuvre pour sécuriser les ports, contrôler les appareils connectés au réseau local et empêcher tout accès non autorisé.
4.	Configurez la VoIP pour la communication entre les deux sociétés :
**Cisco VoIP** a été configuré sur les deux réseaux pour permettre la communication vocale entre les deux sociétés sur Internet.
 Grâce aux paramètres VoIP, les salariés des deux sociétés de Rabat et de Rachidia ont pu passer des appels téléphoniques fluides et de qualité sur le réseau.
Toutes les communications passent par un tunnel sécurisé (VPN)
5.	Testez la connexion et confirmez les performances :
Une fois les configurations terminées, des tests ont été effectués pour vérifier que VPN GRE fonctionnait correctement et sécurisait les réseaux locaux, et il a été confirmé que le pare-feu n'autorisait que le trafic sécurisé.
**EtherChannel** et **Port Security** ont également été testés pour garantir la stabilité et la sécurité du réseau local.
Il a été confirmé que le système **VoIP** réussit à transmettre une voix de haute qualité entre les deux sociétés.

