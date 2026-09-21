# Segmentation réseau — DMZ

## Objectif

Vérifier que la zone DMZ est correctement isolée du réseau LAN.

## Architecture

Le laboratoire utilise deux réseaux principaux :

| Réseau | Adresse | Rôle |
|---|---|---|
| LAN | 192.168.1.0/24 | Réseau interne |
| DMZ | 192.168.2.0/24 | Zone isolée pour les services |

### Machines utilisées

| Machine | Adresse IP | Rôle |
|---|---|---|
| pfSense LAN | 192.168.1.1 | Passerelle LAN |
| pfSense DMZ | 192.168.2.1 | Passerelle DMZ |
| Ubuntu-DMZ | 192.168.2.100 | Machine de test |

## Tests de connectivité

### Test 1 — DMZ vers pfSense DMZ

Depuis Ubuntu-DMZ :

```bash
ping 192.168.2.1
