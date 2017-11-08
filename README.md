# ETS_data
2005-2016 data from the European emissions trading scheme (ETS)

## What you'll find in this dataset

You will find a dataset in a txt format from ETS system, the European CO2 market, collected on [EUTL](http://ec.europa.eu/environment/ets/http://). The information about **14.000 installations** is available for **31 countries, 30 sectors, for the years 2005-2016**. 

The content lists information like the installation name and country, the account holder's name, the verified emissions for each year and the free allocations for each year, the parent company, the address.

To dowload the data, just click on the file.

#### August 29th of 2017 update

+ 2016 data has been added.

+ Also, a bug has been fixed. From 2013 on, EUTL diferentiates 3 categories of allowances : classic allowances, allowances given under article 10c of the ETS directive (followed by 4 stars), and allowances given as New entrant's reserve (NER) (followed by 5 stars). Those annyoing stars messed up the data ^^. In **Allowance_Allocation_20XX** column, I just separated the 3 figures by a slash, in case you need that granularity. But if you just need the total allowances, **Total_Allowance_Allocation_20XX** is the column you are looking for.

# ETS_data
Données 2005-2016 du marché européen des quotas de CO2 (ETS)

## Ce qu'il y a dans ces données

Retrouvez au format txt un jeu de données issues du système communautaire d'échange de quotas d'émission CO2 (EU ETS). Ce fichier contient les données des **14 000 installations** inscrites au [registre](http://ec.europa.eu/environment/ets/http://) européen public du marché de quotas de CO2. 

L'information est disponible pour **31 pays, 30 secteurs, pour les années 2005-2016**. Le contenu liste des informations telles que le nom et le pays de l'installation industrielle, le nom du teneur de compte, de la maison-mère, les émissions vérifiées pour chaque année ainsi que les allocations de quotas gratuits pour chaque année, ou encore l'adresse postale.

Pour récupérer les données, il vous suffit de cliquer sur le fichier pour le télécharger.

#### Actualisation 29 août 2017

+ Par rapport au fichier sur les données 2005-2015, les données 2016 ont été ajoutées. 

+ Par ailleurs, un bug a été corrigé. En effet pour la phase 3 du système (2013-2020), les cases du registre public européen livrent parfois trois chiffres différents avec des astérisques, différenciant par exemple les quotas gratuits pour les installations relevant de l'article 10c de la directive (électriciens d'Europe de l'Est, en grande partie). Ces chiffres n'étaient pas traités dans la version 2005-2015. Désormais, la somme de ces chiffres est disponible : l'allocation totale est livrée dans les colonnes **Total_Allowance_Allocation_20XX** par année.

+ Enfin, pour conserver la granularité de l'information, pour ces installations où plusieurs chiffres étaient précisés concernant les allocations (au titre d'un nouvel entrant, ou bien de l'article 10c de la directive), ces chiffres sont également livrés dans les colonnes **Allowance_Allocation_20XX**, et séparés par des slashs.

