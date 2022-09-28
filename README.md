![logo de pret à dépenser](https://github.com/ONOKANA8/OC_Data_Scientist_P7/blob/main/logo-pret-a-depenser.png?raw=true)

# **OC_Data_Scientist_P7 - Projet 7 : Implémentation d'un modèle de scoring-crédit**

## Contexte
La société financière nommée "Prêt à dépenser" propose des crédits à la consommation pour des personnes ayant peu ou pas du tout d'historique de prêt.
L’entreprise souhaite mettre en œuvre un outil de “scoring crédit” pour calculer la probabilité qu’un client rembourse son crédit, puis classifie la demande en crédit accordé ou refusé. Elle souhaite donc développer un algorithme de classification en s’appuyant sur des sources de données variées (données comportementales, données provenant d'autres institutions financières, etc.).

De plus, les chargés de relation client ont fait remonter le fait que les clients sont de plus en plus demandeurs de transparence vis-à-vis des décisions d’octroi de crédit. Cette demande de transparence des clients va tout à fait dans le sens des valeurs que l’entreprise veut incarner.

Prêt à dépenser décide donc de développer un dashboard interactif pour que les chargés de relation client puissent à la fois expliquer de façon la plus transparente possible les décisions d’octroi de crédit, mais également permettre à leurs clients de disposer de leurs informations personnelles et de les explorer facilement. 


## Mission
* Construire un modèle de scoring qui donnera une prédiction sur la probabilité de faillite d'un client de façon automatique.
* Mise en place d'un dashboard interactif à destination des gestionnaires de la relation client et dont les spécifications visent à :

  * Permettre de visualiser le score et l’interprétation de ce score pour chaque client de façon intelligible pour une personne non experte en data science.
  * Permettre de visualiser des informations descriptives relatives à un client (via un système de filtre).
  * Permettre de comparer les informations descriptives relatives à un client à l’ensemble des clients ou à un groupe de clients similaires.


## Sources de données
|Sources|Liens sources|
|--|--|
|Données Kaggle|https://www.kaggle.com/c/home-credit-default-risk/data|


## Livrables
|Noms de fichiers et de dossier|Descriptions|
|--|--|
|Konan_Koffi_2_dossier_code_062022| Ce dossier contient les sous-dossiers code_modelisation, code_fastapi et code_dashboard renfermant les différents scripts de modélisation et d'applications, ainsi que le fichier liens_codes_sources_github.txt donnant accès aux dépôt de l'api et du dashboard mis en place|
|Konan_Koffi_1_dashboard_062022.pdf|Fichier contenant les adresses URL des applications disponibles sur le web|
|Konan_Koffi_3_note_méthologique_062022.pdf|Note méthodologique sur notre démarche|
|Konan_Koffi_4_présentation_062022.pdf|Support de présentation|

NB : Les livrables sus-mentionnés sont disponibles dans le dossier **P7_Implémenter_un_modèle _de_scoring_konan_koffi**