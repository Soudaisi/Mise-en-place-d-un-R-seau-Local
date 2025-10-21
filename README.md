# Mise en place d’un réseau local (LAN) d’entreprise

## Objectif du projet
Ce projet a pour but de concevoir et configurer un réseau local d’entreprise fonctionnel et sécurisé à l’aide de Cisco Packet Tracer.  
L’objectif est d’assurer la connectivité entre les différents services de l’entreprise tout en contrôlant les accès grâce aux ACL.


## Compétences et technologies utilisées
- Configuration de routeurs et de switchs Cisco  
- Création et gestion des VLANs  
- Attribution d’adresses IP statiques et dynamiques  
- Mise en œuvre des ACL (Access Control Lists) pour filtrer le trafic  
- Tests de connectivité (ping, traceroute)  
- Documentation du schéma réseau


## Architecture du réseau
Le réseau est divisé en plusieurs VLANs correspondant aux services de l’entreprise (Administration, Technique, Comptabilité).
Chaque VLAN est isolé, avec des règles d’accès définies par des ACL sur le routeur principal.


## Configuration principale
- **Switchs :** configuration des VLANs et des ports d’accès/trunk  
- **Routeur :** configuration des sous-interfaces, routage inter-VLAN, et ACL  
- **Postes clients :** configuration des IP et test de communication


## Résultats et vérifications
- Communication entre les VLANs autorisés  
- Blocage du trafic non autorisé par les ACL  
- Réseau stable et fonctionnel


## Fichiers inclus
- `Mohammadou_soudaisi_B1C.pkt` → fichier Cisco Packet Tracer du projet  
- `Vue de l'entreprise 1.PNG`, `Simulation du Réseau.PNG` → Captures du projet  


## Auteur
**Mohammadou Soudaisi**  
Étudiant en Bachelor 2 Réseaux et Systèmes — Formation Administrateur Réseaux et Sécurité  
