# Covid19

_(English version below)_

## French

Vous trouverez dans ce dépôt les fichiers suivants : 

- french_counts.csv : nombre de cas confirmés cumulés par région française depuis le 4 mars (date des premiers chiffres régionaux publiés par Santé Publique France)
- Covid19_France.rmd / .html : script R markdown et son résultat en html avec graphiques interactifs, pour l'instant l'analyse est vraiment minimaliste (attention le script utilise aussi les données de l'université Johns Hopkins pour la partie internationale)

Format du fichier french_counts (4 colonnes, 1 ligne par jour et par région) : 

- code_reg : code INSEE de la région (format 2016)
- lib_reg : libellé de région
- date : au format standard %Y-%m-%d (année - mois - jour)
- count : nombre de cas cumulés annoncé par Santé Publique France (généralement arrêté à 15h le jour considéré)

Les données sont mises à jour quotidiennement après l'annonce des nouveaux effectifs qui a lieu vers 20h. 

## English

You could find here the following files : 

- french_counts.csv : number of cumulative confirmed cases per French region starting on March the 4th (no data available before - source : Santé Publique France)
- Covid19_France.rmd / .html : R markdown script and its result in html

Content of french_counts file (4 columns, 1 line per day and region) : 

- code_reg : code for linkage with INSEE data
- lib_reg : labels of regions
- date : format %Y-%m-%d (year - month - day)
- count : number of cumulative confirmed counts given by Santé Publique France (at 3 pm on each day)

All data are updated daily on evening. 
