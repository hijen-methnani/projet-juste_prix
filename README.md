# projet-juste_prix
# Le Juste Prix — Bot de Simulation Intelligente

## Description du projet
Ce projet simule le jeu **"Le Juste Prix"** en Python.  
Un bot autonome tente de deviner un nombre secret compris entre 1 et 1000 en un nombre limité d’essais.  
L’objectif est de maximiser les gains en utilisant une **stratégie de recherche binaire** efficace.

Le programme met en avant la logique algorithmique, la prise de décision et la gestion des probabilités appliquées à un jeu de hasard simulé.

---

## Règles du jeu
Le joueur (ou le bot) dispose de **7 tentatives** pour trouver le nombre secret, avec les caractéristiques suivantes :

- Premier essai gratuit, sans mise initiale.  
- Gain de consolation de 10 euros, même en cas d’échec.  
- Les gains diminuent selon le nombre d’essais nécessaires.

### Grille des gains

| Essai | Gain (€) |
|:------:|:---------:|
| 1er (gratuit) | 1000 |
| 2e | 800 |
| 3e | 600 |
| 4e | 400 |
| 5e | 200 |
| 6e | 100 |
| 7e | 50 |

---

## Fonction principale

```python
def bot_juste_prix_casino(a=1, b=1000):
    """
    Simule une partie du Juste Prix jouée par un bot.
    
    - Génère un nombre secret aléatoire entre a et b.
    - Le bot effectue jusqu’à 7 tentatives pour le deviner.
    - Utilise une stratégie de recherche binaire pour optimiser les essais.
    - Calcule le gain final en fonction du nombre d’essais nécessaires.
    """
```

Le bot ajuste automatiquement les bornes minimale et maximale après chaque tentative afin d’optimiser sa recherche.

---

## Compétences mises en œuvre
- Programmation en Python (fonctions, boucles, conditions)
- Algorithmes de recherche binaire
- Simulation et logique de jeu
- Gestion de structures de données
- Optimisation et stratégie automatique

---

## Améliorations possibles
- Ajouter une interface graphique (Tkinter ou Streamlit)
- Enregistrer les scores des joueurs
- Comparer plusieurs stratégies de bots
- Générer des statistiques sur les performances

---

## Auteur
**Hijèn Methnani**  
Projet académique 
