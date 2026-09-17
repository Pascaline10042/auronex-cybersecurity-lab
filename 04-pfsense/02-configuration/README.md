# Configuration pfSense

Documentation de la configuration réseau de pfSense dans le laboratoire AURONEX.

## Architecture réseau

Le laboratoire utilise trois interfaces réseau :

- WAN : connexion vers le réseau externe
- LAN : réseau interne
- DMZ : zone destinée aux services isolés

## Interfaces

| Interface | Nom pfSense | Rôle |
|---|---|---|
| em0 | WAN | Accès externe |
| em1 | LAN | Réseau interne |
| em2 | DMZ | Zone démilitarisée |

## Configuration

### WAN

- Interface : em0
- Rôle : connexion WAN
- Configuration : à documenter

### LAN

- Interface : em1
- Rôle : réseau interne
- Adresse IP : à documenter

### DMZ

- Interface : em2
- Rôle : réseau isolé pour les services
- Adresse IP : à documenter

## Tests

Les tests de connectivité et de communication entre les différentes interfaces seront documentés ici.

## Objectif

Mettre en place une architecture réseau permettant de pratiquer la segmentation, le filtrage réseau et la cybersécurité défensive avec pfSense.
