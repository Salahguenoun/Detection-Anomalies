﻿# Détection d'Anomalies dans des Transactions Financières
## Introduction
Ce projet a pour objectif de détecter des anomalies dans un jeu de données de transactions financières. L'approche consiste à analyser les caractéristiques des transactions pour identifier les valeurs aberrantes pouvant correspondre à des fraudes ou des erreurs.

 **Note :** La base de données utilisée pour ce projet n'est pas partagée pour des raisons de confidentialité et de conformité aux réglementations en vigueur.

---

## Données
Le jeu de données analysé contient les colonnes suivantes :
- **id_transaction** : Identifiant unique de chaque transaction.
- **montant** : Montant de la transaction (en devise non précisée).
- **date** : Date de la transaction.
- **ville** : Ville associée à la transaction.

### Observations :
- La colonne `id_transaction` ne contient pas de doublons.
- Aucune valeur manquante n'est présente dans les colonnes du dataset.
- Des valeurs aberrantes ont été repérées dans la colonne `montant`, avec des valeurs extrêmement élevées.

---

## Installation
Avant d’exécuter le projet, assurez-vous d’avoir Python installé et les dépendances nécessaires.

### Installer les dépendances :
```bash
pip install -r requirements.txt
