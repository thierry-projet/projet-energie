# projet-energie
Analyse des  consommations électriques en France de 2013 à 2022 - Projet de Thierry ALLEM dans le cadre de la formation en Data Analyst chez DataScientest.
===========================================================================================================================================================
Ce repository a été créé après la fin de ma formation de Data Analyst dans le but de présenter une partie de mon travail auprès d'éventuels recruteurs.

Ma priorité étant actuellement la prospection des offres d'emploi, les fichiers "README" de chacune des branches seront complétées progressivement.
Merci pour votre compréhension.

Si vous souhaitez en savoir plussur moi, vous pouvez visiter ma pageLinkedln: www.linkedin.com/in/thierry-allem
===========================================================================================================================================================
Présentation
L’énergie est une ressource indispensable à notre quotidien et à l’économie, en effet se loger, se déplacer, se chauffer, se rafraîchir, se nourrir, fabriquer des objets à partir de matières premières… ces besoins et activités humaines consomment de l’énergie. 
Certains usages de l’électricité (éclairage, fonctionnement d’appareils électroménagers, etc.) sont qualifiés de « spécifiques » car ils ne peuvent être couverts que grâce à l’électricité.
La croissance démographique, l’accès d’une part grandissante de la population mondiale à l’énergie, le développement rapide de certaines économies, synonyme d’industrialisation, les pays développés habitués à une énergie abondante et relativement bon marché, sont autant de facteurs contribuant à une hausse continue de la consommation d’énergie.
Le secteur économique de l'énergie en France comprend la production locale et l'importation d'énergie primaire, Pour couvrir les besoins énergétiques de la France, la branche énergétique française utilise de l'énergie primaire, produite en France ou importée, puis la transforme et la distribue aux utilisateurs.

Nous nous intéressons à la production locale, ainsi la France compte dans son bouquet énergétique des énergies fossiles et d’autres renouvelables tels que : le nucléaire, le pétrole, le gaz naturel, des d'énergies renouvelables et déchets.

Le gestionnaire du réseau de transport d'électricité français RTE représente chaque jour, et en temps réel, les données liées à la consommation et production d’électricité sur sa plateforme Eco2Mix.
Dans le cadre de de notre projet consiste à explorer et visualiser les données à partir des données mise à notre disposition à partir de cette plateforme afin de constater le phasage entre la consommation et d'autres paramètres tels que la production énergétique au niveau national et au niveau régional (risque de black-out notamment), les conditions météorologiques ou la densité de population. Dans ce sens nous allons nous focaliser sur :
-	L’analyse au niveau régional pour en déduire une prévision de consommation ; 
-	L’analyse par filière de production : énergie nucléaire / renouvelable ;
-	Un focus sur les énergies renouvelables et leurs lieux d’implantation.
Pour y parvenir, nous allons utiliser un ensemble de données d’approximativement 2 millions d’enregistrements. Les données contiennent les informations sur la consommation d’électricité et sa production à partir de plusieurs de plusieurs sources d’énergie : thermique, nucléaire, solaire, éolienne, bioénergie et hydraulique, relevée toutes les 30 minutes pour chacune des 12 régions françaises métropolitaine (Corse non incluse dans l’étude).


La base de donnée nommée "eco2mix-regional-cons-def" utile à ce projet a été téléchargée au format ".csv "depuis le site "OPENDATA RESEAUX -ENERGIES",ODRE , à l'adresse
https://odre.opendatasoft.com/explore/dataset/eco2mix-regional-cons-def/information/?flg=fr-fr&disjunctive.libelle_region&disjunctive.nature"

Sa taille, au jour du téléchargement initial pour ce projet, est de 284 264 Ko.

Il contient 1 980 288 enregistrements et 32 colonnes des valeurs issues des relevés effectués toutes les 30 minutes, depuis le 01 janvier 2013 00:30:00 jusqu’au 31 Mai 2022 23:30:00 inclus.

