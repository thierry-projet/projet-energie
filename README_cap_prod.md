# projet-energie
Projet de Thierry ALLEM dans le cadre de la formation en Data Analyst chez DataScientest
========================================================================================================================================================
Analyse des capacités maximales annuelles de production

Pour la cartographie des capacités de production, RTE met à notre disposition deux fichiers permettant de renseigner les capacités de production installées dans chacune des régions.
•
Le premier fichier renseigne les principales installations de production par filière (nucléaire, thermique et hydraulique), hors solaire et éolien, leur localisation (longitude, latitude) et la capacité de production.
Nom du fichier :
"RA9partition_des_principales_installations_de_production_dC3C32C_hors_solaire_et_%C.csv»
Téléchargeable depuis l'adresse :
https://www.services-rte.com/fr/telechargez-les-donnees-publiees-par-rte.html?category=generation&type=installed_capacities&subType=capacities_per_production_type

•
Le second renseigne les capacités de productions éoliennes et solaires installées par région et renseignant l’année d’installation.
Il est nommé ‘parc-national-annuel-prod-eolien-solaire.csv’
Téléchargeable à l'adresse :
https://www.data.gouv.fr/fr/datasets/parc-national-annuel-de-production-eolien-et-solaire-2001-a-2024/

=========================================================================================================================================================
Reconstitution des capacités de production maximales par traitements de données sur les installations de production

RTE met à notre disposition 2 autres types de données pouvant nous être utiles :
➢ Le Registre National des installations de production d'électricité ;
➢ Les registres des indisponibilités des installations.

a. Le Registre National des installations de production d'électricité
Téléchargeable depuis l'adresse https://www.data.gouv.fr/fr/datasets/registre-national-des-installations-de-production-et-de-stockage-delectricite-au-31-03-2025-1/
Descriptif du fichier :
•  Données disponibles téléchargées : toutes du 01/01/1900 jusqu’en 2023
•  Nom du fichier : registre_national_installation_production_stockage_electricite
•  Format de fichier : CSV Microsoft Excel
•  Taille du fichier : 21 122 Ko
•  Nombres de lignes : 73 694
•  Nombre de colonnes : 49

b. Les fichiers des indisponibilités des installations de production d'électricité
Téléchargeables depuis l'adresse https://iip.cloud-rte-france.com/production-unavailability
(la mise à disposition de ces données a été modifiée depuis la réalisation de ce projet; les fichiers téléchargeables sont donc différents)
Descriptif des fichiers :
•
Données disponibles & téléchargées : de 2013 à 2023
• Nom des fichiers :
DonneesIndisponibilitesProduction_2013, DonneesIndisponibilitesProduction_2014, DonneesIndisponibilitesProduction_2015, DonneesIndisponibilitesProduction_2016, DonneesIndisponibilitesProduction_2017, DonneesIndisponibilitesProduction_2018, DonneesIndisponibilitesProduction_2019, DonneesIndisponibilitesProduction_2020, DonneesIndisponibilitesProduction_2021, DonneesIndisponibilitesProduction_2022
• Format de fichier : CSV
• Taille des fichiers : de 971 Ko à 8506 K
