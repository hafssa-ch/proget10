# TP 11 – Collections en Java
 ### Objectif

Ce TP a pour but d’explorer les collections Java et de comprendre l’utilisation des principales interfaces (List, Set, Map) ainsi que leurs différentes implémentations.
Chaque exercice illustre un aspect essentiel de la manipulation des collections.

## Exercice 1 – Manipulation de List

Créer une liste de chaînes de caractères, y ajouter des éléments, les parcourir et les trier.
Utilisation de ArrayList et Collections.sort().
Vérification de la présence d’un élément et suppression d’un autre.
<img width="625" height="634" alt="image" src="https://github.com/user-attachments/assets/67f1e80c-fe80-411e-86ff-8df13e838536" />


## Exercice 2 – Gestion des doublons avec Set

Créer un ensemble (HashSet) pour stocker des prénoms sans doublons.
Ajout d’éléments répétitifs pour observer le comportement du Set.
Parcours de l’ensemble avec une boucle for-each.
<img width="597" height="623" alt="image" src="https://github.com/user-attachments/assets/bc21c990-ac54-4e43-bbae-68e9b14b59c7" />


## Exercice 3 – Comparaison entre HashSet, LinkedHashSet et TreeSet

Observer les différences de comportement entre :
HashSet → ordre aléatoire
LinkedHashSet → ordre d’insertion
TreeSet → tri alphabétique automatique
Chaque implémentation est testée avec les mêmes données pour visualiser les résultats.
<img width="1585" height="559" alt="image" src="https://github.com/user-attachments/assets/e0a124bd-d4fe-49cb-be9c-c99dfd35bc0d" />


 ## Exercice 4 – Dictionnaire bilingue avec Map

Implémenter un dictionnaire anglais → français à l’aide de :
HashMap (rapide, sans ordre)
LinkedHashMap (préserve l’ordre d’ajout)
TreeMap (classement alphabétique)
Ajout, suppression, recherche et affichage des traductions sont pris en charge.
L’exercice met en évidence les différences entre les trois types de Map.
<img width="554" height="608" alt="image" src="https://github.com/user-attachments/assets/48b21fad-0436-4931-9cad-8b37368a5699" />


## Exercice 5 – Gestion d’un Annuaire Téléphonique

Créer un programme pour gérer un annuaire de contacts :
Utilisation d’un Map<String, String> (nom → numéro).
Fonctions d’ajout, de recherche, de suppression et d’affichage.
Possibilité d’utiliser TreeMap pour un tri alphabétique des contacts.
<img width="1559" height="273" alt="image" src="https://github.com/user-attachments/assets/86b34b64-05e5-43e0-ad1b-e831128e3066" />
