---
permalink: /encadrement-doctoral/
title: "Encadrement doctoral"
author_profile: true
---
Voici le contenu de ma nouvelle page.
Au cours de ma carrière, j'ai encadré quatre thèses de doctorat : deux réalisées dans le cadre d'une convention CIFRE en partenariat avec l'entreprise [FRS Consulting](https://www.frsconsulting.fr/), et deux thèses académiques financées sur contrat doctoral ministériel.

![Historique des thèses encadrées](images/schema_theses.pdf)
*Figure — Historique des thèses encadrées : à partir d'une proposition de recrutement initial (me concernant) de l’entreprise FRS Consulting, deux thèses CIFRE ont été créées, chacune ayant donné lieu par la suite à une thèse académique. Le schéma illustre l’articulation entre partenariat industriel et dynamique académique.*

---

## Thèse de Kymble CHRISTOPHE (2016–2019)

- **Titre de la thèse :** *Essays on empirical evaluation of the European R&D policy*  
- **Doctorant :** Kymble CHRISTOPHE  
- **Financement :** CIFRE en partenariat avec FRS Consulting  
- **Taux d'encadrement :** 50%  
- **Laboratoire :** EconomiX  
- **Discipline :** Sciences économiques  
- **École doctorale :** Économie, organisations, société (EOS)  
- **Dates :** 03/10/2016 — 16/12/2019  

**Jury :**  
Lionel RAGOT — Directeur de thèse — Professeur des universités — Université Paris Nanterre, LIP6  
François DELBOT — Co-encadrant académique — Maître de conférences — Université Paris Nanterre, LIP6  
Gaétan LE CHAT — Co-encadrant industriel — Chef de projet R&D — FRS Consulting  
Nadine LEVRATTO — Présidente — Directrice de recherche CNRS — Université Paris Nanterre, EconomiX  
Corinne AUTANT-BERNARD — Rapporteure — Professeure des universités — Université de Saint-Étienne  
Emmanuel DUGUET — Rapporteur — Professeur des universités — Université Paris-Est Créteil  
Angelo SECCHI — Examinateur — Professeur des universités — Université Paris 1 Panthéon-Sorbonne  

**Poursuite professionnelle :**  
Après 3 ans au Ministère de l’Économie et des Finances (évaluation des politiques publiques), Kymble est désormais Économiste-économètre chez Bpifrance.

**Résumé :**  
Cette thèse propose d’utiliser un cadre empirique pour évaluer la politique européenne en matière de recherche et développement. Le programme-cadre (PCRD) est au cœur de l’analyse. Trois études sont menées : (i) analyse du réseau de collaboration des projets soutenus pour caractériser la structure de l’Espace Européen de la Recherche, sa résilience et son efficacité ; (ii) effet de la structure des projets collaboratifs sur la création de connaissances, en distinguant les interactions internes/externes aux partenariats ; (iii) impact micro-économique du PCRD sur les entreprises lauréates via des analyses de causalité appliquées à la solvabilité, la productivité et la rentabilité, avec comparaison à EUREKA.

### Publications et communications issues de la thèse (sélection automatique)
{% assign pubs = site.publications | where: "category", "kymble" | sort: "date" | reverse %}
{% if pubs.size > 0 %}
  {% assign groups = pubs | group_by_exp: "p", "p.date | date: '%Y'" %}
  {% for y in groups %}
  #### {{ y.name }}
  {% for post in y.items %}{% include archive-single.html %}{% endfor %}
  {% endfor %}
{% else %}
_Aucune entrée trouvée portant `category: kymble` dans `_publications/`._
{% endif %}

---

## Thèse de Vincent Grollemund (2017–2021)

- **Titre de la thèse :** *Exploration et modélisation de données peu ou pas structurées*  
- **Doctorant :** Vincent Grollemund  
- **Financement :** CIFRE en partenariat avec FRS Consulting  
- **Taux d'encadrement :** 50%  
- **Laboratoire :** LIP6  
- **Discipline :** Informatique  
- **École doctorale :** École doctorale Informatique, télécommunications et électronique de Paris (EDITE)  
- **Dates :** 02/11/2017 — 25/06/2021  

**Jury :**  
Jean-François PRADAT-PEYRE — Directeur de thèse — Professeur des universités — Université Paris Nanterre, LIP6  
François DELBOT — Co-encadrant académique — Maître de conférences — Université Paris Nanterre, LIP6  
Gaétan LE CHAT — Co-encadrant industriel — Chef de projet R&D — FRS Consulting  
Emmanuelle ENCRENAZ — Présidente — Professeure des universités — Sorbonne Université, LIP6  
Pierre-François PRADAT — Examinateur — Praticien Hospitalier, HDR — Hôpital de la Pitié-Salpêtrière, LIB  
Hélène BLASCO — Rapporteure — PU–PH — CHU de Tours, iBrain  
Patrice BERTAIL — Rapporteur — Professeur des universités — Université Paris Nanterre, MODAL’X  

**Poursuite professionnelle :**  
Expert en Intelligence Artificielle et Cheminformatique chez Bayer.

**Résumé :**  
Les données réelles sont souvent rares, incomplètes et biaisées. La thèse étudie une approche non supervisée pour isoler des échantillons minoritaires dans deux contextes : pronostic de la SLA et recommandation d’aides publiques à l’innovation. Les données sont projetées avec **UMAP**, les minorités sont identifiées via **DBSCAN** et **alpha-shapes**. Malgré des contraintes fortes, l’approche met au jour des corrélations pertinentes et isole les sous-populations d’intérêt, améliorant l’aide à la décision.

### Publications et communications issues de la thèse (sélection automatique)
{% assign pubs = site.publications | where: "category", "vincent" | sort: "date" | reverse %}
{% if pubs.size > 0 %}
  {% assign groups = pubs | group_by_exp: "p", "p.date | date: '%Y'" %}
  {% for y in groups %}
  #### {{ y.name }}
  {% for post in y.items %}{% include archive-single.html %}{% endfor %}
  {% endfor %}
{% else %}
_Aucune entrée trouvée portant `category: vincent` dans `_publications/`._
{% endif %}

---

## Thèse de Valentin Bouquet (2019–2022)

- **Titre de la thèse :** *Problèmes de domination et partitionnement de graphes : complexité, structure, criticité*  
- **Doctorant :** Valentin BOUQUET  
- **Financement :** Ministériel  
- **Taux d'encadrement :** 33%  
- **Laboratoire :** Cédric  
- **Discipline :** Informatique  
- **École doctorale :** Sciences des Métiers de l'Ingénieur (SMI)  
- **Dates :** 01/09/2019 — 10/11/2022  

**Jury :**  
Christophe PICOULEAU — Directeur de thèse — Professeur des universités — CNAM, Cédric  
François DELBOT — Co-encadrant — Maître de conférences — Université Paris Nanterre, LIP6  
Stéphane ROVEDAKIS — Co-encadrant — Maître de conférences — CNAM, Cédric  
Claire HANEN — Présidente — Professeure des universités — Université Paris Nanterre, LIP6  
Tinaz EKIM — Rapporteure — Professeure des universités — Université du Bosphore, Istanbul  
Bernard RIES — Rapporteur — Professeur des universités — Université de Fribourg  
Denis CORNAZ — Examinateur — Maître de conférences — Université Paris-Dauphine, LAMSADE  
Dimitri WATEL — Examinateur — Enseignant-Chercheur — ENSIIE, SAMOVAR  

**Poursuite professionnelle :**  
Depuis septembre 2023, maître de conférences en informatique à l'Université Paris Nanterre, rattaché au LIP6 (équipe RO).

**Résumé :**  
Deux volets. **(1) Ensemble dominant minimum.** Décision en temps polynomial sur certaines classes (sans griffe et sans chemin induit court). Étude des sommets communs à tous les ensembles dominants minimums et des **arêtes critiques** (dont la suppression modifie le nombre de domination), avec bornes optimales en graphes triangulés et résultats de complexité en sous-classes planaires. **(2) Partitionnement par satisfaction locale** : pour un ratio \(a/b\), existence d’une partition où chaque sommet a au moins \(a/b\) de voisins dans sa communauté. Bornes minimales par classes, liens au **couplage disconnectant** dans les graphes réguliers et étude du **couplage parfait disconnectant** avec résultats de complexité (planaires, degré borné, bipartis, diamètre borné, sans-griffe, sans-\(P_5\)).

### Publications et communications issues de la thèse (sélection automatique)
{% assign pubs = site.publications | where: "category", "valentin" | sort: "date" | reverse %}
{% if pubs.size > 0 %}
  {% assign groups = pubs | group_by_exp: "p", "p.date | date: '%Y'" %}
  {% for y in groups %}
  #### {{ y.name }}
  {% for post in y.items %}{% include archive-single.html %}{% endfor %}
  {% endfor %}
{% else %}
_Aucune entrée trouvée portant `category: valentin` dans `_publications/`._
{% endif %}

---

## Thèse de Thibault Anani (2021–2025)

- **Titre de la thèse :** *Métaheuristiques pour l'Apprentissage Machine : Applications au Domaine Médical et à la Théorie des Graphes*  
- **Doctorant :** Thibault ANANI  
- **Financement :** Ministériel  
- **Taux d'encadrement :** 80%  
- **Laboratoire :** LIP6  
- **Discipline :** Informatique  
- **École doctorale :** École doctorale Informatique, télécommunications et électronique de Paris (EDITE)  
- **Dates :** 01/09/2021 — 11/09/2025  

**Jury :**  
Jean-François PRADAT-PEYRE — Directeur de thèse — Professeur des universités — Université Paris Nanterre, LIP6  
François DELBOT — Co-encadrant académique — Maître de conférences — Université Paris Nanterre, LIP6  
Hélène BLASCO — Rapporteure — PU–PH — CHU de Tours, iBrain  
Zacharie ALES — Rapporteur — Maître de conférences, HDR — ENSTA, UMA  
Pierre-François PRADAT — Examinateur — Praticien Hospitalier, HDR — Hôpital de la Pitié-Salpêtrière, LIB  
Claire HANEN — Examinatrice — Professeure des universités — Université Paris Nanterre, LIP6  
Marta RUKOZ — Examinatrice — Professeure des universités — Université Paris Nanterre, LAMSADE  

**Poursuite professionnelle :**  
Thibault souhaite rejoindre l’industrie pour poursuivre ses travaux de recherche.

**Résumé :**  
La thèse étudie des **métaheuristiques** pour la **sélection de variables** (problème \(\mathcal{NP}\)-difficile) et propose **TiDE** (*Tournament in Differential Evolution*) avec mécanismes adaptatifs d’initialisation, mutation et croisement. Un benchmark hétérogène évalue robustesse et généricité. Applications médicales : SLA et pneumopathie Covid-19, avec gains prédictifs et réduction dimensionnelle, tout en conservant l’interprétabilité. Enfin, transposition aux **conjectures en théorie des graphes** : génération et réfutation assistées, comparatifs expérimentaux montrant l’intérêt des métaheuristiques en contexte fondamental.

### Publications et communications issues de la thèse (sélection automatique)
{% assign pubs = site.publications | where: "category", "thibault" | sort: "date" | reverse %}
{% if pubs.size > 0 %}
  {% assign groups = pubs | group_by_exp: "p", "p.date | date: '%Y'" %}
  {% for y in groups %}
  #### {{ y.name }}
  {% for post in y.items %}{% include archive-single.html %}{% endfor %}
  {% endfor %}
{% else %}
_Aucune entrée trouvée portant `category: thibault` dans `_publications/`._
{% endif %}
