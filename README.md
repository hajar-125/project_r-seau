# IMPLÉMENTATION D’UN RÉSEAU LOCAL SÉCURISÉ AVEC CISCO PACKET TRACER

## OVERVIEW DU PROJET:
### Description:
Le projet représente un exemplaire de l’implémentation d’un réseau sécurisé fictive d’une banque pour notre client à l’aide de Cisco Packet Tracer, et une infrastructure robuste et évolutive, capable de supporter les opérations critiques et de garantir la protection des données sensibles de la banque et de ses clients. Il inclura l’implémentation de protocoles de sécurité réseau et d’un service de transactions sécurisées via une API.


### Objectifs:
- Concevoir un réseau sécurisé et fonctionnel dans Packet Tracer pour assurer la communication entre les diﬀérent départements de la banque tout en assurant la sécurité et l’authentification des opérations.
- Configurer et tester des protocoles de sécurité réseau (pare-feu, VLAN, ACL).
- Mettre en place une API simulant des transactions sécurisées (authentification, gestion des permissions).
- Vérifier l’intégration du réseau et de l’API avec des tests de sécurité et de fonctionnalité.

#### API DE TRANSACTIONS SÉCURISÉES:
Utilisation de Python pour la création de l’API, implémentation de l’authentification.
Les transactions doivent inclure des informations sécurisées, comme des identifiants d’utilisateurs et des informations financières.
Utilisation du protocole HTTPS pour les communications entre les clients et l’API.

### Exigences fonctionnelles:
#### Sécurité réseau :
- Configuration de pare-feus, de listes de contrôle d'accès (ACL) standard pour SSH et de VLAN pour séparer les services et renforcer la sécurité.
- Subnetting et adressage IP.
- Configuration de la politique d'inspection du pare-feu.
- Configurations réseau sans fil.
- Configurations VPN.

#### Communication inter-départementale : 
Configuration du routage inter- VLAN sur les commutateurs de niveau 3 plus IP DHCP helper address.

#### Authentification et gestion des accès : 
Utilisation de protocoles d’authentification (comme AAA) pour sécuriser les accès des utilisateurs et des services.

#### Transactions sécurisées via API :
- Implémentation d'une API permettant de simuler des transactions.
- Gestion de l'authentification et des permissions pour chaque type d'utilisateur.
- Stockage sécurisé des informations de transaction.

### Outils et Technologies:
- Logiciels de simulations: Cisco Packet Tracer
- Languages et Frameworks: Python et Flask.
- Protocoles et Algorithmes:
  - Cryptages: HTTPS, TLS, AES-512, RSA, SHA-512
  - Sécurité: IDS/IPS, VLAN
  - Protocoles: ISO
### Tests:
- Tests de connectivité réseau.
- Tests de sécurité.
- Tests fonctionnels de l’API.
