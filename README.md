# Serre automatisée

---

## Description

Cette branche est dédiée à la partie du projet qui concerne le développement sur le Raspberry Pi.

Cette partie du projet est en cours de développement, la branche la plus stable est [main-raspberry-pi](https://github.com/TitienZagaroli/serre-auto/tree/main-raspberry-pi).

Pour plus d'informations sur le projet, veuillez vous référer à la [branche principale](https://github.com/TitienZagaroli/serre-auto).

## Prérequis

Pour utiliser ce projet, vous aurez besoin des éléments suivants:
- Un Raspberry Pi (de préférence un modèle 3 ou plus récent)
- Une carte microSD (8 Go minimum)
- Une alimentation pour le Raspberry Pi (5V, 2.5A minimum)
- Une connexion internet (au moins pour l'installation des dépendances)
- Raspbian (ou un autre système d'exploitation compatible avec le Raspberry Pi)

Pour plus d'informations sur l'installation de Raspbian, veuillez vous référer à la [documentation officielle](https://www.raspberrypi.com/documentation/computers/getting-started.html#install-an-operating-system).

## Installation

Pour installer le projet sur votre Raspberry Pi, veuillez suivre les instructions suivantes:

1. Cloner le projet sur votre Raspberry Pi dans le répertoire de votre choix:
```bash	
git clone -b dev-raspberry-pi https://github.com/TitienZagaroli/serre-auto.git
cd serre-auto
```

2. Installer les dépendances:
```bash
pip3 install -r requirements.txt
```

## Utilisation

Pour lancer le programme sur votre Raspberry Pi, veuillez exécuter la commande suivante:
```bash
streamlit run ./src/streamlitApp.py --server.port 8502
```	

## Documentation

La documentation du projet est disponible dans le répertoire [docs](./docs).
