<p align="center">
   <img align="center" width="50%" src="https://github.com/fanny-lamoliatte/EMPLOI_MANCHE/blob/Emploi_Manche/la_manche_logo.png" />
</p>
<br>
<br>
<br>

## <ins> OBJECTIF </ins> ##

### **<ins>Etablissement du profil de la Manche selon :</ins>**
- Ses 5 principaux secteurs d’activités
- Ses types d’entreprises (ETI, PME, GE) ainsi que leurs localisations
- Son marché du travail (besoin en main d’œuvre, déclaration préalable à l’embauche, types d’emploi pourvus)
- Ses critères de logement
- Sa cartographie dynamique de la politique publique territoriale visant à rendre ce département plus attractif
<br>

## <ins> PRESENTATION DES DONNEES </ins> ##

### Dans le cadre de cette étude, nous exploiterons des données en open source issues de plateformes telles que Data.gouv, l'INSEE, l'Observatoire des territoires..., couvrant la période 2018-2021. 
<br>

Tout au long de cette étude, nous nous baserons sur notre **base de données principale, les entreprises manchoises**, leurs types, leurs localisations, les différents contrats de travail qu'elles proposent ... 
<br>

<ins>**Elle sera consolidée par des données portant sur:**</ins>
 - la démographie du département
 - le logement
 - les besoins en main d'oeuvre (BMO) des entreprises
 - les déclarations préalables à l'embauche (DPAE) de strutures économiques locales
 - la polique publique du département pour attirer les populations
<br>

Nous aurons de plus recours à la <ins>**table de conversion des codes NAF (nomenclature d'actiivité) vers les grands secteurs d'activité GS)**</ins>
<br>
<br>

### **<ins>Annuaire des entreprises manchoises</ins>**
<p align="center">
   <img align="center" width="85%" src="https://github.com/fanny-lamoliatte/EMPLOI_MANCHE/blob/Emploi_Manche/VISUALISATION%20DATA/Base%20des%20%C3%A9tablissements%20%C3%A9conomiques.PNG" />
</p>
<br>

### **<ins>Besoins en main d'oeuvre</ins>**
<p align="center">
   <img align="center" width="85%" src="https://github.com/fanny-lamoliatte/EMPLOI_MANCHE/blob/Emploi_Manche/VISUALISATION%20DATA/BMO.PNG" />
</p>
<br>

### **<ins>Déclarations préalables à l'embauche</ins>**
<p align="center">
   <img align="center" width="85%" src="https://github.com/fanny-lamoliatte/EMPLOI_MANCHE/blob/Emploi_Manche/VISUALISATION%20DATA/DPAE.PNG" />
</p>
<br>

### **<ins>Démographie Logement/ins>**
<p align="center">
   <img align="center" width="100%" src="https://github.com/fanny-lamoliatte/EMPLOI_MANCHE/blob/Emploi_Manche/VISUALISATION%20DATA/D%C3%A9mographie_Logement.PNG" />
</p>
<br>

### **<ins>Table de conversion</ins>**
<p align="left">
   <img align="center" width="20%" src="https://github.com/fanny-lamoliatte/EMPLOI_MANCHE/blob/Emploi_Manche/VISUALISATION%20DATA/Table%20de%20conversion%20NAF__GS.PNG" />
</p>
<br>

### **<ins>Politique publique</ins>**
<p align="left">
   <img align="center" width="100%" src="https://github.com/fanny-lamoliatte/EMPLOI_MANCHE/blob/Emploi_Manche/VISUALISATION%20DATA/Politique%20publique.PNG" /> 
</p>
<br>
<br>

## <ins> METHODOLOGIE </ins> ##

- <ins>**Important travail de collecte data ce projet ayant été réalisé en totale autonomie**</ins>
  - BDD de référence : établissements professionnels dans la Manche 1.5 Mo
  - Besoins en main (BMO) 4 BDD 3 000 Ko chacune
  - Besoins en main (BMO) 4 BDD 3 000 Ko chacune
  - Déclarations préalables à l’embauche (DPAE) 42 000 Ko
  - Démographie, logements sociaux 1 000 Ko
  - Politique publique 30 000 Ko
  - Table correspondance APE (activité principale) GS grands secteurs activités 50 Ko
  - Table correspondance ROME_GS 2 Ko
  - Table correspondance ROME_NAF (branche activité principale entreprise) 150 Ko
  - Table sous classe NAF_APE 50 Ko
<br>

- <ins>**Data cleaning général sur GoogleColab**</ins>
  - Filtrations des données sur le territoire de la Manche, ainsi que sur la plage 2018/2021
  - Suppressions des données non pertinentes à l’étude
  - Gestion des tables de conversion afin d'établir des relations avec les autres bases de données
  - Téléchargement des datasets sur Power BI
<br>

- <ins>**Data cleaning approfondi sur Power BI**</ins>
  - Uniformisations des noms de colonnes, des types, des données numériques
  - Normalisations des modalités en vue de l'établissement de futures mesures DAX
  - Création de tables de fait FACT, afin de lier les différentes tables entre elles
  - Création de visuels (cartes géographiques interractives, treemap, pie charts, …)
  - Mise en place de liens hypertextes, offres d'emploi, présentation des entreprises
  - Création de filtrations dynamiques, de widgets ...
 <br> 

### **<ins>Le marché de l'emploi dans la Manche</ins>**
<p align="left">
   <img align="center" width="100%" src="https://github.com/fanny-lamoliatte/EMPLOI_MANCHE/blob/Emploi_Manche/VISUALISATION%20DATA/March%C3%A9%20de%20l'emploi.PNG" /> 
</p>
<br> 
<br> 

### **<ins>Politique publique mise en place dans la Manche</ins>**
<p align="left">
   <img align="center" width="100%" src="https://github.com/fanny-lamoliatte/EMPLOI_MANCHE/blob/Emploi_Manche/VISUALISATION%20DATA/Politique%20publique%20screen.PNG" /> 
</p>
<br> 

## <ins> CONCLUSIONS </ins> ##
### Il ressort de cette étude que la Manche, bien qu’étant un territoire considéré comme "fragile", tend depuis 2021 à favoriser l’emploi pérenne afin d’attirer de nouvelles populations.
### Premier département agricole de France, elle se distingue par une forte activité de transformation agroalimentaire, complétée par une tradition ancrée de pêche, de transport et de construction navale. 
### es secteurs dynamisent également le commerce local.
### Par ailleurs, le tourisme y occupe une place plus que significative.
### Marquée par une identité rurale affirmée, la Manche compte 31 % de communes hors de toute influence urbaine, contre une moyenne nationale de 21 %. 
### Pour renforcer son attractivité, l’État et les collectivités locales ont déployé divers programmes de politique publique : aides financières, exonérations fiscales, réhabilitation des centres-villes et de l’habitat, contribuant ainsi au renouveau du territoire.
<br> 
<br> 

## <ins> LIMITES DE L'ETUDE </ins>

- Impossibilité de mise en place d’une relation directe entre les besoins en mains d’œuvre et les déclarations préalables à l’embauche
- Inexistence d’une table de correspondance administrative entre les codes métiers BMO et DPAE, d'où l'impossibilité de mise en relation directe entre ces 2 tables
- Nombreuses tentatives de contournement par le biais d'autres tables normalisées du secteur de l'emploi (codes ROME, NAF, APE)
- Etablissement final d'une **relation secondaire** via des tables de fait

  #### Dans un esprit de précision, cette étude gagnerait à être consolidée par des informations plus précises, notamment sur les infrastructures, le logement et les services proposés aux populations, ainsi que par un approfondissement des spécificités des entreprises manchoises.



