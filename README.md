# Dr Death


# <p align="center">Le contexte de projet</p>
  
Le contexte des données fournies est lié à un ensemble de cas des meurtre de doctor shipman impliquant des personnes de différentes tranches d'âge, de sexes différents et des lieux de décès variés. Chaque cas de décès est également associé à une décision spécifique concernant la cause du décès, avec presque toutes les entrées indiquant "Unlawful killing" (meurtre). La période couverte par les données va de 1975 à 1998, chaque cas étant identifié par le nom de la personne décédée, la date du décès et d'autres attributs. Et des valeurs numériques pour différentes heures de la journée, avec les pourcentage des meurtre associées de "Shipman" et "Comparison" ( les les autre médecin) .

![Image](https://allthatsinteresting.com/wordpress/wp-content/uploads/2021/03/harold-shipman-headshot.jpg)
#

### La veille sur Microsoft Power BI

Power BI est un outil d'analyse commerciale développé par Microsoft. Il permet aux utilisateurs de collecter, de visualiser et d'analyser des données provenant de différentes sources. Power BI est une solution complète qui peut être utilisée par les entreprises de toutes tailles.

Voici quelques-unes des fonctionnalités de Power BI :

* Collecte des données : Power BI peut connecter à une variété de sources de données, y compris des bases de données, des feuilles de calcul, des applications Web et des fichiers.
* Visualisation des données : Power BI offre une variété de façons de visualiser les données, y compris des graphiques, des tableaux, des cartes et des diagrammes.
* Analyse des données : Power BI permet aux utilisateurs de faire des analyses avancées sur leurs données, y compris des calculs, des corrélations et des prévisions.
* Partage des données : Power BI permet aux utilisateurs de partager leurs rapports et leurs tableaux de bord avec d'autres personnes, soit via le Web, soit par e-mail.

Power BI est un outil puissant qui peut aider les entreprises à améliorer leur prise de décision. En collectant, en visualisant et en analysant leurs données, les entreprises peuvent identifier des tendances, prendre des décisions plus éclairées et améliorer leurs performances.

Voici quelques exemples d'utilisation de Power BI :

* Une entreprise peut utiliser Power BI pour suivre ses ventes, ses revenus et ses dépenses.
* Une banque peut utiliser Power BI pour analyser les risques de crédit.
* Un hôpital peut utiliser Power BI pour suivre les résultats des patients.
* Une agence gouvernementale peut utiliser Power BI pour suivre les dépenses publiques.

Power BI est un outil en constante évolution. Microsoft ajoute régulièrement de nouvelles fonctionnalités à Power BI, ce qui en fait un outil encore plus puissant.


# Problématique étudiée :
La problématique qui pourrait être étudiée à partir de ces données est la suivante : comprendre et analyser les cas de décès enregistrés, en mettant l'accent sur les caractéristiques spécifiques telles que l'âge, le sexe, le lieu de décès, les décisions concernant la cause des décès et comparent les heure de décès pendant la journée entre les passion de Shipman et les passion des autre médecin

Les questions qui pourraient être abordées lors de l'analyse des données sont les suivantes :

- Quelle est la répartition des décès par sexe ? Y a-t-il des différences significatives entre les décès chez les hommes et les femmes ?
- Quelles sont les tranches d'âge les plus touchées par les décès ? Y a-t-il des tendances spécifiques en fonction de l'âge des victimes ?
- Quels sont les lieux de décès les plus fréquents ? Le lieu de décès influence-t-il les décisions concernant la cause du décès ?
- Comment les décisions concernant la cause des décès sont-elles réparties ? Y a-t-il des motifs récurrents de décisions de "Unlawful killing" (meurtre) ?
- Existe-t-il des tendances ou des heures spécifiques où les valeurs diffèrent davantage ?
        
#### Voici ce que représente chaque colonne dans les données fournies :

- **DateofDeath** : La date du décès de la personne.

- **Name** : Le nom de la personne décédée.

- **Age** : L'âge de la personne décédée au moment du décès.

- **PlaceofDeath** : Le lieu où la personne est décédée

- **Decision** : La décision concernant la cause du décès 

- **yearOfDeath** : L'année du décès de la personne.

- **ageBracket** : La tranche d'âge dans laquelle la personne décédée est classée

- **gender2** : Une variable catégorielle indiquant le sexe de la personne décédée

- **Hour** : Les heures de la journée, exprimée en format 24 heures (de 00 à 23).

- **Shipman** : Le pourcentage de personnes décédées associées à Harold Shipman pour une heure spécifique de la journée.

- **Comparison** : Le pourcentage de personnes décédées associées à d'autre médecin pour une heure spécifique de la journée.   



# Analyse des données :

![Image](https://github.com/djameleddine-saim/Dr_Death/assets/115147662/bc5fe27b-9c78-494b-941a-79fe7b307732)

### Répartition des décès par tranche :
<img width="500" alt="Capture d'écran 2023-07-28 133342" src="https://github.com/djameleddine-saim/Dr_Death/assets/115147662/67a125d9-a673-4d1f-b2b2-43e5d6320308">

### Répartition de nombre de décès pour chaque lieu de décès :
<img width="500" alt="Capture d'écran 2023-07-28 133342" src="https://github.com/djameleddine-saim/Dr_Death/assets/115147662/14b065e5-834b-4c85-babf-e4fd5e276c55">


### pourcentage décès pour chaque sexe (hommes et femmes) :
<img width="500" alt="Capture d'écran 2023-07-28 133342" src="https://github.com/djameleddine-saim/Dr_Death/assets/115147662/286331a6-8d7f-4821-85a9-2b4bedb920c8">


### pourcentage de décès pour chaque décisions (condamnation et Meurtre illégal) :
<img width="500" alt="Capture d'écran 2023-07-28 133342" src="https://github.com/djameleddine-saim/Dr_Death/assets/115147662/f4423500-48d9-4ca4-b405-a3ff5ec964be">


### Répartition de sexe des décès au file des année :
<img width="500" alt="Capture d'écran 2023-07-28 133342" src="https://github.com/djameleddine-saim/Dr_Death/assets/115147662/4bf5d001-a724-4e2e-a508-a275e3e56aee">


### Répartition des valeurs "Shipman" et "Comparison" en fonction des heures de la journée :
<img width="500" alt="Capture d'écran 2023-07-28 133342" src="https://github.com/djameleddine-saim/Dr_Death/assets/115147662/fb84938e-2b6c-4382-ad60-1ce86d6263d2">


# Conclusion :
