# Projet_Final_Bial_x

Ce projet consiste en une étude approfondie des données d’un bailleur social concernant les états des lieux de sortie de logements de 2014 à 2023. L'objectif est d'analyser ces données afin de répondre à deux problématiques principales.

## Contexte

L'analyse se concentre sur les états des lieux de sortie des logements gérés par un bailleur social. Cette étude vise à mieux comprendre les facteurs influençant la nécessité de pré-visites et à identifier des profils de locataires à risque.

## Problématiques

- **Sujet A** : Cibler les logements où une pré-visite est nécessaire.
- **Sujet B** : Identifier un profil de locataire à risque pour déterminer si un état des lieux de sortie est nécessaire.

## Fonctionnalités

- Exploration et nettoyage des données.
- Analyse statistique pour cibler les logements nécessitant une pré-visite.
- Modélisation pour identifier les locataires à risque.
- Visualisations interactives pour présenter les résultats.
- Analyse ciblée sur les logements résultant de la création d’une nouvelle catégorie “État de logement”. 
- Annotation des logements de A+ (meilleur état)  à D (très dégradé).
- Création d’une note Profil en fonction de la situation familiale, du motif de sortie, du nombre d’occupants. 
- Détermination du “Profil à risque” en 5 catégories en fonction de la note Profil : de “Très faible” à “Très Élevé”.
- Machine learning : Prédire l’état de profil
- Modèle basé sur la méthode Random Forest (“Forêt aléatoire” basé sur l’assemblage d’arbres de décision) pour prédire la note de l’état de profil qui va, ensuite,  déterminer le profil à risque.
- Pourcentage de succès du modèle: 88 %

## Technologies Utilisées

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/ton-utilisateur/Projet_Final_Bial_x.git
2. Accédez au dossier du projet :
   ```bash
   cd Projet_Final_Bial_x
4. Installez les dépendances :
   ```bash
    pip install -r requirements.txt

## Installation

1. Lancez Jupyter Notebook :
   ```
   jupyter notebook
2. Ouvrez le fichier Projet_Final_Bial_x.ipynb et exécutez les cellules pour reproduire les analyses.

## Contributions

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez le projet.
2. Créez une branche (git checkout -b feature/nom-de-la-fonctionnalité).
3. Apportez vos modifications et committez (git commit -m 'Ajoute une nouvelle fonctionnalité').
4. Poussez la branche (git push origin feature/nom-de-la-fonctionnalité).
5. Ouvrez une pull request.
   
## License
Ce projet est sous licence privée. Veuillez ne pas redistribuer sans autorisation.


