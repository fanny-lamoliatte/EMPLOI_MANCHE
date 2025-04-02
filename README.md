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

- <ins>**Important travail de collecte data** ce projet ayant été réalisé en totale autonomie</ins>
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

  

	Data Cleaning général 
Filtrations des données sur le territoire de la Manche
Suppressions des données non pertinentes à l’étude
Chargements des datasets sur Power BI
Data Cleaning en détails Power Query
Uniformisation des colonnes, noms, types
Normalisations des modalités pour futures mesures DAX
Création d’une table de fait FACT
Mises en place de relations entre les tables
Création de visuels (cartes géographiques, treemap, pie charts, …)
Mises en place de filtrations dynamiques, de widgets …
