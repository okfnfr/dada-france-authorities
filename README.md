# dada-france-autorities

**Description :** Jeux de données des administrations publiques françaises et autres personnes morales pouvant faire l'objet d'une demande d'accès à un document administratif tel que défini dans l'Article L300-2 du Code des relations entre le public et l'administration. Les données ont été adaptées au [format alavateli](https://alaveteli.org/docs/running/admin_manual/) afin de pouvoir être utilisée sur le site http://madada.fr. **À ce jour (11 Août 2019) le jeu de données contient 61536 administrations et opérateurs de l'État dont 51123 ont une adresse email renseignée.**

**Licence :** Licence Ouverte

**Créé le :** 23 Juillet 2019

**Auteur :** Pierre Chrzanowski

**Source :** La liste des administrations provient de l'annuaire de l'administration https://lannuaire.service-public.fr/themes. Les données des administrations publiques locales sont disponibles sur data.gouv.fr https://www.data.gouv.fr/fr/datasets/service-public-fr-annuaire-de-l-administration-base-de-donnees-locales/#_. Les données des opérateurs de l'État proviennent du Ministère de l'Économie et des Finances et sont disponibles sur data.gouv.fr https://www.data.gouv.fr/fr/datasets/projet-de-loi-de-finances-pour-2019-plf-2019-annexe-budget-des-operateurs-de-letat-pour-2018/

## Description des colonnes

### #id

Numéro d'identifiant unique de l'administration fournit par l'annuaire des administrations publiques disponible sur le site https://lannuaire.service-public.fr.

###	name	

Nom de l'administration et son acronyme entre parenthèses.

### request_email	

Email de contact pour la demande d'accès.

### notes

Informations additionnelles, notamment l'adresse, et le téléphone.

### home_page	

Url du site web de l'administration ou de sa page sur le site https://lannuaire.service-public.fr

### tag_string

Mots clés séparès par un espace permettant de filtrer les administrations. Les administrations sont classées suivant les thèmes de niveau 2 utilisées par l'annuaire de l'administration sur le site https://lannuaire.service-public.fr/themes. Voir ci-dessous pour détail des thèmes et mots clés associés.

### Administration nationale  

  `administration-nationale`  

* [ ] Ambassades de France : `ambassade`   
* [x] Autorités indépendantes : `autorite-administrative-independante` ou `autorite-publique-independante`   
* [x] Institutions et juridictions : `institution` ou `juridiction`   
* [x] Ministères : `ministere`   

### Administration locale  

  `administration-locale`  

Centre de gestion de la fonction publique territoriale (CDG) : `cdg`   
Centre national de la fonction publique territoriale (CNFPT) - Antenne départementale : `cnfpt`   
* [x] Conseil départemental : `cg`   
* [x] Conseil économique, social et environnemental régional (CESER) : `cesr`   
* [x] Conseil régional : `cr`   
* [x] Intercommunalité : `epci`   
* [x] Mairie : `mairie`   
* [x] Préfecture : `prefecture`   
* [x] Préfecture de police de Paris, antenne d'arrondissement : `paris_ppp_antenne`   
* [x] Préfecture de région : `prefecture_region`   
* [x] Sous-préfecture : `sous_pref`   

### Social, santé  

`social-sante`  

* [x] Agence régionale de santé (ARS) : `ars`   
* [x] Agence régionale de santé (ARS) - Délégation départementale : `ars_antenne`   
* [x] Association de gestion du fonds pour l'insertion professionnelle des personnes handicapées (AGEFIPH) : `agefiph`   
* [x] Caisse d'allocations familiales (CAF) : `caf`   
* [x] Caisse d'assurance retraite et de la santé au travail (CARSAT) : `carsat`   
* [x] Caisse primaire d'assurance maladie (CPAM) : `cpam`   
* [x] Centre d'information de conseil et d'accueil des salariés (CICAS) : `cicas`   
* [x] Centre d'information sur les droits des femmes et des familles (CIDFF) : `cidf`   
* [x] Centre de protection maternelle et infantile (PMI) : `pmi`   
* [x] Centre hospitalier universitaire (CHU) : `chu`   
* [x] Direction de la cohésion sociale, du travail, de l'emploi et de la population (DCSTEP) - Outre-mer : `dcstep`  
* [x] Direction départementale de la cohésion sociale (DDCS) : `ddcs`   
* [x] Direction départementale de la cohésion sociale et de la protection des populations (DDCSPP) : `ddcspp`   
* [x] Maison départementale des personnes handicapées (MDPH) : `maison_handicapees`   
* [x] Mutualité sociale agricole (MSA) - réseau local : `msa`   
* [x] Plateforme d'accompagnement et de répit pour les aidants de personnes âgées : `accompagnement_personnes_agees`   
* [x] Point d'information local pour les personnes âgées : `clic`   
* [x] Point info famille : `pif`   
* [x] Union de recouvrement des cotisations de sécurité sociale et d’allocations familiales (URSSAF) : `urssaf`   

### Travail, emploi, formation  

`travail-emploi-formation`  

* [x] Agence nationale pour la formation professionnelle des adultes (Afpa) : `afpa`   
* [x] Association pour l'emploi des cadres (Apec) : `apec`   
* [x] Association pour l'emploi des cadres, ingénieurs et techniciens de l'agriculture et de l'agroalimentaire (Apecita) : `apecita`   
* [x] Cap emploi : `cap_emploi`   
* [x] Chambre de commerce et d’industrie (CCI) : `cci`   
* [x] Chambre de l'agriculture : `chambre_agriculture`   
* [x] Chambre des métiers et de l'artisanat (CMA) : `chambre_metier`   
* [x] Etablissement pour l'insertion dans l'emploi (EPIDE) : `epide`   
* [x] Maison* [x]  de services au public : `msap`   
* [x] Mission locale (pour les 16-25 ans) : `mission_locale`   
* [x] Pôle emploi : `pole_emploi`   

### Économie, finances, consommation  

`economie-finances-consommation`  

* [x] Banque de France (succursale) : `banque_de_france`   
* [x] Bureau de douane : `bureau_de_douane`   
* [x] Cadastre : `cadastre`   
* [x] Centre des impôts foncier : `centre_impots_fonciers`   
* [x] Conciliateur fiscal départemental : `conciliateur_fiscal`   
* [x] Cour des comptes (chambre régionale ou territoriale) : `crc`   
* [x] Crédit municipal : `credit_municipal`   
* [x] Direction départementale de la protection des populations (DDPP) : `ddpp`   
* [x] Direction départementale des finances publiques (DDFIP) : `dd_fip`   
* [x] Direction régionale de l'INSEE : `dr_insee`   
* [x] Direction régionale des douanes et droits indirects : `drddi`   
* [x] Direction régionale des entreprises, de la concurrence, de la consommation, du travail et de l'emploi (DIRECCTE) : `direccte`   
* [x] Direction régionale des entreprises, de la concurrence, de la consommation, du travail et de l'emploi (DIRECCTE) - unité départementale : `direccte_ut`   
* [x] Direction régionale des finances publiques (DRFIP) : `dr_fip`   
* [x] Direction spécialisée du contrôle fiscal : `dcf`   
* [x] Paierie départementale : `paierie_departementale`   
* [x] Paierie régionale : `paierie_regionale`   
* [x] Pôle de recouvrement spécialisé : `prs`   
* [x] Service de la publicité foncière : `hypotheque`   
* [x] Service départemental de l'enregistrement : `sde`   
* [x] Service des impôts des entreprises (SIE) : `sie`   
* [x] Service des impôts des particuliers (SIP) : `sip`   
* [x] Trésorerie : `tresoreri* [x] * [x] * [x] e`   

### Enseignement, recherche  

`enseignement-recherche`  

* [x] Centre d'information et d’orientation (CIO) : `cio`   
* [x] Centre de ressources, d'expertise et de performances sportives (CREPS) : `creps`   
* [x] Centre régional des œuvres universitaires et scolaires (CROUS) : `crous`   
* [x] Délégation régionale à la recherche et à la technologie : `drrt`   
* [x] Direction de services départementaux de l'Éducation nationale (DSDEN) : `inspection_academique`   
* [x] École supérieure du professorat et de l’éducation (ESPE) : `espe`   
* [x] Groupement d'établissements publics d'enseignement (GRETA) : `greta`   
* [x] Office national d'information sur les enseignements et les professions (ONISEP) - délégation régionale : `dronisep`   
* [x] Rectorat : `rectorat`   
* [x] Réseau Canopé - atelier départemental : `canope_atelier`   
* [x] Réseau Canopé - direction territoriale : `canope_dt`   
* [x] Service universitaire d'information et d'orientation (SUIO) : `suio`   

### Environnement, logement, transports  

`environnement-logement-transports`

* [x] Agence de l’environnement et de la maîtrise de l’énergie (ADEME) : `ademe`   
* [x] Agence départementale d'information sur le logement (ADIL) : `adil`   
* [x] Agence nationale de l’habitat (ANAH) - réseau local : `anah`   
* [x] Centre d'études et d'expertise sur les risques, l'environnement, la mobilité et l'aménagement (CEREMA) - direction territoriale : `cerema`   
* [x] Centre en route de la navigation aérienne (CRNA) : `cnra`   
* [x] Délégation à la mer et au littoral (DML) : `dml`   
* [x] Direction de la sécurité de l'aviation civile (DSAC) : `dac`   
* [x] Direction départementale des territoires (DDT) : `ddt`   
* [x] Direction des territoires, de l'alimentation et de la mer (DTAM) : `dtam`   
* [x] Direction interdépartementale des routes (DIR) : `did_routes`   
* [x] Direction interrégionale de la mer : `dir_mer`   
* [x] Direction interrégionale de Météo-France : `dir_meteo`   
* [x] Direction régionale de l'alimentation, de l'agriculture et de la forêt (DRAAF) : `draf`   
* [x] Direction régionale de l'environnement, de l'aménagement et du logement (DREAL) : `dreal`   
* [x] Direction régionale de l'environnement, de l'aménagement et du logement (DREAL) - unité territoriale : `dreal_ut`   
* [x] Direction régionale et interdépartementale de l'équipement et de l'aménagement (DRIEA) - Ile-de-France : `driea`   
* [x] Direction régionale et interdépartementale de l'équipement et de l'aménagement (DRIEA) - Ile-de-France - unité territoriale : `driea_ut`    
* [x] Direction régionale et interdépartementale de l'hébergement et du logement (DRIHL) - Île-de-France : `drihl`   
* [x] Direction régionale et interdépartementale de l'hébergement et du logement (DRIHL) - Île-de-France - unité territoriale : `drihl_ut`   
* [x] Office national des forêts (ONF) - direction territoriale : `onf`   
* [x] Société d'aménagement foncier et d'établissement rural (SAFER) : `safer`   
* [x] Voies navigables de France (VNF) : `service_navigation`   

### Sécurité, défense  

`securite-defense`  

* [x] Brigade de gendarmerie : `gendarmerie`   
* [x] Brigade motorisée de gendarmerie : `gendarmerie_moto`   
* [x] Centre d'information et de recrutement (CIR) de la gendarmerie nationale : `cirgn`   
* [x] Centre d'information et de recrutement des forces armées (CIRFA) : `cirfa`   
* [x] Centre de recrutement et de formation de la police nationale (CRFPN) : `crfpn`   
* [x] Centre du Service national : `bsn`   
* [x] Commissariat de police : `commissariat_police`   
* [x] Direction de la police aux frontières : `dz_paf`   
* [x] Direction départementale de la sécurité publique (DDSP) : `ddsp`   
* [x] Direction régionale de la police judiciaire (DRPJ) : `dir_pj`   
* [x] Groupement de gendarmerie départementale : `gendarmerie_departementale`   
* [x] Office national des anciens combattants et victimes de guerre (ONACVG) : `onac`   
* [x] Préfecture de police de Paris : `paris_ppp`   
* [x] Préfecture de police des Bouches-du-Rhône : `pp_marseille`   
* [x] Secrétariat général pour l'administration du ministère de l'Intérieur (SGAMI) : `sgami`   
* [x] Service départemental d'incendie et de secours (SDIS) : `sdis`   

### Droit, justice  

`droit-justice`  

* [x] Bureau d'aide aux victimes : `bav`    
* [x] Chambre départementale des huissiers de justice : `huissiers_justice`   
* [x] Chambre départementale des notaires : `chambre_notaires`   
* [x] Commission d'indemnisation des victimes d'infraction (Civi) : `civi`   
* [x] Commission départementale de conciliation : `commission_conciliation`   
* [x] Conseil de Prud'hommes : `prudhommes`   
* [x] Cour administrative d'appel : `caa`   
* [x] Cour criminelle départementale : `ccd`   
* [x] Cour d'appel : `cour_appel`   
* [x] Délégation départementale aux droits des femmes et à l'égalité (DDDFE) : `dd_femmes`   
* [x] Délégation régionale aux droits des femmes et à l'égalité (DRDFE) : `dr_femmes`   
* [x] Direction interrégionale de la protection judiciaire de la jeunesse (DIRPJJ) : `drpjj`   
* [x] Direction interrégionale des services pénitentiaires (DISP) : `drsp`   
* [x] Direction territoriale de l'Office français de l'immigration et de l'intégration (OFII) : `ofii`   
* [x] Direction territoriale de la protection judiciaire de la jeunesse (DTPJJ) : `ddpjj`   
* [x] Établissement pénitentiaire - Centre de détention : `centre_detention`   
* [x] Établissement pénitentiaire - Centre de semi-liberté : `csl`   
* [x] Établissement pénitentiaire - Centre pénitentiaire : `centre_penitentiaire`   
* [x] Établissement pénitentiaire - Maison centrale : `maison_centrale`   
* [x] Établissement pénitentiaire - Maison d'arrêt : `maison_arret`   
* [x] Établissement pénitentiaire spécialisé pour mineurs (ESM) : `esm`   
* [x] Maison de justice et du droit : `mjd`   
* [x] Ordre des avocats - Barreau : `ordre_avocats`   
* [x] Point d'accès au droit : `permanence_juridique`   
* [x] Service pénitentiaire d'insertion et de probation (SPIP) : `spip`   
* [x] Tribunal administratif : `ta`   
* [x] Tribunal d'instance : `ti`   
* [x] Tribunal de commerce : `tribunal_commerce`   
* [x] Tribunal de grande instance (TGI) : `tgi`   
* [x] Tribunal pour enfants : `te`   

### Associations, cultures, jeunesse  

`associations-culture-jeunesse`

* [x] Archives départementales : `ad`   
* [x] Bibliothèque départementale de prêt : `bibli`   
* [x] Centre de ressources et d'information des bénévoles (Crib) : `crib`   
* [x] Conseil d'architecture, d'urbanisme et de l'environnement (CAUE) : `caue`   
* [x] Conseil de la culture, de l'éducation et de l'environnement (CCEE) - Outre-mer : `conseil_culture`   
* [x] Délégué départemental à la vie associative (DDVA) : `ddva`   
* [x] Direction départementale de la jeunesse et des sports (DDJS) : `ddjs`   
* [x] Direction régionale des affaires culturelles (DRAC) : `drac`   
* [x] Fédération départementale de la pêche et de la protection du milieu aquatique : `fdapp`   
* [x] Fédération départementale des chasseurs : `fdc`   
* [x] Greffe des associations : `prefecture_greffe_associations`   
* [x] Information jeunesse (réseau local) : `cij`   
* [x] Mission d'accueil et d'information des associations (MAIA) : `maia`   
* [x] Unité départementale de l'architecture et du patrimoine (UDAP) : `sdac`

### Opérateurs de l'État

`associations-culture-jeunesse`

* [x] Association : `association`  
* [x] Établissement public à caractère industriel et commercial : `epic`  
* [x] Établissement publi à caractère administratif : `epa`  
* [x] Établissements publics à caractère scientifique, culturel et professionnel : `epscp`  
* [x] Établissement public à caractère scientifique et technologique : `epst`  
* [x] Groupement d'intérêt général : `gie`  
* [x] Groupement d'intérêt public : `gip`  
* [x] Fondation : `fondation`  
* [x] Sui generis : `sui-generis`  

