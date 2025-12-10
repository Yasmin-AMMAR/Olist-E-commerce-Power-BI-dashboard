# Dashboard Power BI – Analyse complète de la marketplace Olist

## Introduction à Olist

Olist est une plateforme e-commerce brésilienne qui connecte des milliers de petits commerçants aux plus grandes marketplaces du pays.  
Elle centralise la gestion des commandes, des paiements, de la logistique et du service client, permettant aux vendeurs d’élargir leur audience tout en offrant aux acheteurs une expérience unifiée et fiable.

Grâce à son modèle marketplace, Olist collecte un volume important de données transactionnelles, logistiques et comportementales.  
Ce projet utilise ces données pour analyser :

- la performance commerciale  
- le comportement d’achat  
- la qualité logistique  
- la satisfaction client  
- la fidélité vendeurs & clients
  
---

# I. Analyse – Vue d’ensemble

Les dashboards présentent les performances globales d’Olist entre **janvier 2017 et août 2018**, uniquement sur **les commandes livrées** 

![Vue d’ensemble 1](images/dashboard1_Vue%20d%27ensemble_1.png)

![Vue d’ensemble 2](images/dashboard1_Vue%20d%27ensemble_2.png)

## 1. Indicateurs clés (KPIs)
- **Chiffre d’affaires total : ** R$ 15,36M  
- **96,21K commandes**  
- **2,93K vendeurs actifs**  
- **92,06 % de livraisons à l’heure**  
- **Satisfaction client moyenne : 4,14 / 5**  
→ Le volume est élevé, la logistique performante, la satisfaction client globalement positive.

## 2. Évolution mensuelle CA & Commandes
•	Le CA et le nombre de commandes progressent régulièrement, avec un pic notable en novembre, typique des périodes de forte consommation (Black Friday + fêtes).
•	L'activité reste élevée et stable en 2018 malgré une légère baisse des commandes en milieu d’année.
→ Le business croît de manière saine et continue.

## 3. Top États vendeurs et clients
• São Paulo domine largement côté vendeurs (R$ 9,9M) et côté clients (R$ 5,7M).  
→ Forte concentration géographique du marché.

## 4. Top Catégories Produits
Le treemap montre les catégories qui génèrent le plus de revenus :
Catégorie leader : **health beauty** (R$ 1,4M).  
Le CA est relativement varié entre plusieurs catégories, indiquant un portefeuille de produits équilibré.
→ La marketplace n’est pas dépendant d’une seule famille de produits : le risque est bien diversifié.

👉 Ce premier Dashboard démontre une marketplace en croissance, bien diversifiée, mais très centralisée autour de São Paulo — à la fois côté vendeurs et côté clients.

---

# II. Analyse – Analyse des ventes

Ce tableau de bord permet de comprendre comment se répartissent les ventes sur la plateforme Olist, quelles catégories génèrent le plus de valeur et comment évoluent le panier moyen et la demande.

![Analyse des ventes](images/dashboard2_Analyse des ventes.png)

## 1. Indicateurs clés (KPIs)
- **CA : 15,36 M R$**  
- **96K commandes**  
- **Panier moyen : 159 R$**  
- **Freight maîtrisé**
→ Activité stable, cohérente avec le marché e-commerce brésilien.

## 2. CA & commandes par catégorie
Le graphique met clairement en lumière une forte concentration du CA sur quelques catégories clés :
### Catégories dominantes  
health beauty, watches gifts, bed bath table  
→ Elles combinent CA élevé et fort volume, ce qui en fait les véritables moteurs commerciaux d’Olist.
### Catégories solides  
sports leisure, computers accessories, furniture decor  
→ Elles contribuent de manière importante au volume global.
### Catégories faibles  
security and services, fashion children…  
→ Volume et CA négligeable, mais utile pour diversifier l’offre.

## 3. Performance des catégories (nuage de points)
Le nuage de points évalue la performance des catégories selon trois dimensions : chiffre d’affaires, volume de commandes et prix moyen (taille du point).
### Catégories stars (haut-droit) : elles dépassent les moyennes en CA et volume.
Exemples : health beauty, watches gifts, bed bath table, sports leisure.
→ Elles concentrent l’essentiel du revenu et doivent être renforcées.
### Catégories à faible potentiel (bas-gauche) : faible demande et faible CA.
Exemples : cine photo, christmas supplies, fashion sous catégories, fixed telephony…
→ Priorité business faible.
### Catégories intermédiaires (zone centrale) : proches des moyennes, avec un potentiel d’évolution.
Exemples : pet shop, office furniture, electronics…
→ Leviers possibles : marketing ciblé, cross-selling, optimisation logistique.

👉 L’analyse montre clairement que health beauty, watches gifts, bed bath table et sports leisure sont les principaux moteurs des ventes.
La majorité des catégories se situent en dessous des moyennes, confirmant une forte concentration du CA sur un nombre limité de segments.

---

# III. Analyse – Paiements

Ce dashboard analyse les comportements de paiement des clients sur Olist afin de comprendre quels modes de paiement génèrent le plus de valeur, comment ils influencent le panier moyen et quel est leur lien avec la satisfaction client. Il permet d’identifier les leviers clés qui stimulent les ventes, notamment l’utilisation des paiements multiples.
![Analyse des paiements](images/dashboard3_Analyse des paiements.png)

## 1. Performance des modes de paiement
**Carte bancaire : ~80 % du CA (12,2M R$)**  
**Boleto : panier plus faible, mais volume significatif**  
**Voucher / Debit card : marginal** 
→ La carte de crédit domine largement, à la fois en volume et en rentabilité.

## 2. Répartition des paiements
La distribution confirme cette domination :
**Carte bancaire : ~74 % des transactions**
**Boleto : •	19 % des transactions**  
**Voucher / Debit card : marginal** 
→ Toute stratégie commerciale (promotions, cashback, versements…) doit s’appuyer en priorité sur la carte bancaire.

## 3. Paiement multiple & panier moyen
Le graphique montre une relation nette : plus le panier moyen augmente, plus les clients utilisent les paiements en plusieurs fois.
**Credit card :** 67 % de paiements multiples et le panier moyen le plus élevé → levier majeur pour stimuler le CA.
**Boleto :** 0 % de versements → panier plus faible.
**Voucher :** 16 % de versements mais un CA limité.
→ Le paiement multiple est un moteur direct d’augmentation du panier moyen et des ventes.

## 4. Satisfaction client & nombre de versements
Tous les modes de paiement présentent une note moyenne stable autour de 4,1 – 4,2, quel que soit le nombre de versements.
**Credit card :** 4 versements, note ~4,1
**Boleto :** 1 versement, note ~4,1
**Voucher :** 2 versements, note ~4,1
**Debit card :** 1 versement, note légèrement supérieure (~4,2)
→ Les paiements multiples n’affectent pas la satisfaction client : c’est un levier sûr pour augmenter le panier moyen et les ventes.

👉 La carte bancaire est au cœur du modèle Olist : elle génère l’essentiel du CA et bénéficie fortement des paiements multiples, qui augmentent le panier moyen sans réduire la satisfaction client. Boleto reste utile mais moins rentable, tandis que voucher et debit card jouent un rôle marginal.

---

# IV. Analyse – Livraison & Logistique

Ce tableau de bord analyse l’efficacité de la chaîne logistique d’Olist, en mettant en évidence les délais de livraison, les zones à risque et l’impact des retards sur les coûts.

![Livraison & Logistique](images/dashboard4_Livraison & Logistique.png)

## 1. Indicateurs clés (KPIs)
-	Délai moyen de livraison : **–10,94 jours**  
→ Livraisons très en avance 
-	Taux de retard : **7,94 %** 
→ Le niveau global de retard reste faible, mais non négligeable.
-	Coût moyen du freight : **20,14 R$**
→ Coût maîtrisé.
-	Part du freight : **12,61 %** du chiffre d’affaires
→ Le freight représente un ratio raisonnable.

## 2. Évolution du délai et du taux de retard
Les délais sont globalement négatifs tout au long de la période → livraison anticipée régulière.
Quelques pics de retard apparaissent telques novembre 2017 (plus de 10%) et mars 2018 (plus de 20 %).
→ Probables problèmes saisonniers/logistiques, black Friday... (forte demande ou congestion).

## 3. Répartition des commandes par délai de livraison
•	83 % des commandes sont livrées en avance de plus de 5 jours.
•	9 % livrées avec 1 à 7 jours de retard.
•	Les retards importants (> 7 jours) restent rares (3 %).
→ La majorité des livraisons est sous contrôle et même en avance, ce qui améliore la satisfaction client.

## 4. Analyse du graphique — Performance logistique par État vendeur
Ce graphique compare les délais de livraison moyens et les taux de retard pour chaque État vendeur.
L’objectif : identifier les régions performantes et celles qui posent problème.
États problématiques :  
- **Amazonas (AM)** → +9 jours, 33 % de retard
- **Pará (PA) et Maranhão (MA)** → irrégularité élevée
→ Région la plus critique : distances longues, faible infrastructure, logistique complexe.
États performants : Sud & Sud-Est. → livraison rapide et fiable

## 5. Lecture générale du taux de retard
Le taux de retard varie fortement selon les États :
→ de 33 % (Amazonas) à 0 % (États performants du Sud).
Les zones éloignées, rurales ou difficiles d’accès montrent les pires résultats.
Les régions Sud et Sud-est, plus urbanisées, sont les plus régulières et offrent les délais les plus stables.

## 6. Impact des retards sur les coûts de freight
•	Les livraisons en avance présentent un coût de freight moyen plus bas (~20 R$).
•	Les commandes en retard > 7 jours ont le coût de freight le plus élevé (~24 R$).
→ Les retards entraînent un surcoût logistique direct, ce qui justifie une attention particulière dans les zones problématiques.

👉 Olist présente une logistique très performante, avec une large majorité de livraisons anticipées. Seuls quelques États (Amazonas, Pará, Maranhão) concentrent l’essentiel des retards et nécessitent des améliorations ciblées. Les retards augmentent les coûts, renforçant l’importance d’optimiser la logistique régionale. Globalement, la chaîne logistique soutient fortement la satisfaction client et la performance commerciale.

---

# V. Analyse – Satisfaction Client

Ce tableau de bord permet d’évaluer la perception des clients vis-à-vis de leur expérience d’achat sur Olist, en étudiant la satisfaction globale, son évolution dans le temps et les facteurs qui expliquent les bonnes et mauvaises notes.

![Satisfaction Client](images/ddashboard5_Analyse Satisfaction Client.png)

## 1. Indicateurs clés (KPIs)
- Note moyenne : **4,14 / 5** → La satisfaction est globalement bonne, mais laisse une marge d’amélioration.
- NPS : **65,43** → Forte proportion de clients promoteurs, signe d’une bonne expérience globale.
- **78,57 % de bonnes notes (4–5)** → La majorité des clients évaluent positivement leur achat.
- **13,14 % de mauvaises notes (1–2)** → Volume limité mais important pour identifier les points de friction (retards, qualité produit…).

## 2. Évolution dans le temps
La satisfaction reste stable autour de 4,0–4,2 durant toute la période analysée.
Les pics de taux de retard correspondent souvent à de légères baisses de satisfaction, confirmant l’impact direct de la logistique sur l’expérience client.

## 3. Satisfaction par État vendeur
La carte montre des niveaux de satisfaction sensiblement homogènes selon les régions, avec quelques zones en dessous de la moyenne.
Quelques États du Nord présentent des scores plus faibles, souvent liés à des distances plus longues et à un réseau logistique moins performant.
→ Les régions urbaines et proches des grands centres logistiques offrent généralement une meilleure expérience client.

## 4. Relation entre délai de livraison et coût
On observe que les meilleurs niveaux de satisfaction correspondent en général à des délais de livraison plus rapides.
Le coût du freight n’a pas un impact direct sur la satisfaction, mais les clients les plus satisfaits sont souvent ceux ayant profité de livraisons anticipées.
→ Une livraison rapide génère plus de satisfaction, même si le coût est similaire.

## 5. Volume de commandes par note
Les notes 5 représentent la majorité des commandes → clients très satisfaits dominants.
Les notes 1 et 2, bien que minoritaires, révèlent des problèmes importants (retards, qualité produit, SAV…).

👉 Olist présente une satisfaction élevée, soutenue par des livraisons rapides et un grand nombre de clients promoteurs. Les axes clés d’amélioration concernent la réduction des retards et l’analyse des avis négatifs pour renforcer encore l’expérience client.

---

# VI. Analyse – Cohortes (Vendeurs & Clients) – Partie 1

Ce dashboard explore la fidélisation des vendeurs et des clients à travers une analyse en cohortes, révélant leur niveau d’engagement et la stabilité de l’activité dans le temps.

![Cohortes Vendeurs 1](images/dashboard6_cohort_Vendeurs (1).png)

![Cohortes Clients 1](images/dashboard6_cohort_Clients (1).png)

## 1. Analyse— Cohorte Vendeurs
- 50–75 % reviennent au mois 1  
- 40–55 % reviennent entre mois 2 et 6  
- Rétention longue ≈ 30 %  
→ Très bonne fidélité vendeur.

## 2. Analyse— Cohorte Clients
- Retour mois 1 : **0,20–0,70 %**  
- Retour mois suivants : **0,10–0,30 %**  
- Rétention globale : **1,81 %** 
→ Très faible fidélisation client → comportement “one-shot”.

---

# VII. Analyse – Cohortes (Vendeurs & Clients) – Partie 2

Ce dashboard complète l’analyse des cohortes en offrant une lecture géographique et comportementale de la fidélité des vendeurs et des clients.
Il permet d’identifier les régions les plus actives, d’analyser la rétention réelle après plusieurs mois et de comparer la fidélité des vendeurs à celle des clients.

![Cohortes Vendeurs 2](images/dashboard6_cohort_Vendeurs (2).png)

![Cohortes Clients 2](images/dashboard6_cohort_Clients (2).png)

## 1. Cohorte Vendeurs – Lecture géographique
São Paulo domine largement avec 1 746 vendeurs actifs, suivi de Paraná (333) et Minas Gerais (234), tandis que la plupart des autres États comptent moins de 200 vendeurs.

Les États les plus actifs affichent une fidélité élevée (75–80 %) ; les taux de 100 % observés dans certains petits États ne sont pas significatifs.

La rétention globale est solide : 56 % reviennent au mois 1, 49 % au mois 2, 38 % au mois 4 et 30 % au mois 6.

→ Olist conserve un vendeur sur trois après 6 mois, ce qui confirme une excellente fidélité vendeur et une base d’offre stable à long terme.

## 2. Cohorte Clients – Lecture géographique
São Paulo concentre la majorité des clients actifs (39K), suivi de Rio de Janeiro et Minas Gerais (10–12K), ce qui montre une demande très regroupée dans les grandes zones urbaines.

Le taux de fidélité client est faible (≈ 1,8 %), ce qui est courant pour une marketplace généraliste ; quelques États montent à 3–4 %, mais ces cas restent marginaux.

## 3. Comparaison clients vs vendeurs 
Contrairement aux vendeurs très fidèles (~76 %), les clients ont un comportement majoritairement one-shot (~1–2 % de réachat), révélant une forte dépendance à l’acquisition et un faible réachat naturel.

👉 La base client est large mais peu récurrente, ce qui est typique du e-commerce multi-produits ; le faible taux de rétention est donc cohérent avec ce modèle.

---

# Conclusion Générale

L’analyse met en évidence :

### Points forts
- Forte performance commerciale  
- Catégories clés très rentables  
- Logistique rapide et efficace  
- Satisfaction client élevée  
- Vendeurs très fidèles  

### Axes d’amélioration
- Fidélisation client très faible  
- Optimisation logistique nécessaire dans le Nord  

👉 Olist est une marketplace robuste avec un fort potentiel de croissance, notamment via la fidélisation client et l’amélioration des performances logistiques régionales.

--- 

## Méthodologie

Ce projet suit une approche analytique complète, combinant Python et Power BI pour garantir une préparation rigoureuse des données et une analyse approfondie.

### 1️⃣ Préparation & Nettoyage des données (Python)

Le prétraitement des données a été réalisé en Python avec :

- **Pandas** pour :
  - le nettoyage des valeurs manquantes  
  - la normalisation des types  
  - la fusion des tables sources (clients, commandes, items, paiements…)  
  - la création de colonnes dérivées (délais, montants, dates)  

🔍 L’objectif : fournir à Power BI un dataset *propre, structuré et cohérent*, prêt pour la modélisation.

### 2️⃣ Modélisation des données (Power BI)

- Construction d’un **modèle en étoile** (Star Schema)  
- Séparation claire faits / dimensions  
- Relations 1—N optimisées  
- Types de données normalisés (dates, montants, catégories)

### 3️⃣ Création des mesures DAX

Développement de mesures avancées pour :

- KPIs commerciaux (CA, commandes, panier moyen)  
- Analyse logistique (délais, taux de retard, coût freight)  
- Satisfaction client (notes, NPS)  
- Cohortes clients & vendeurs (fidélisation, activation, rétention)

### 4️⃣ Visualisation & Storytelling

- Conception de **dashboards thématiques** (ventes, paiements, satisfaction, logistique, cohortes)  
- Visualisations avancées : heatmaps, cartes, scatters, histogrammes, matrices de cohortes  
- Mise en place d’une navigation fluide via signets & filtres  

### 5️⃣ Interprétation & Insights

- Identification des catégories stratégiques  
- Analyse des comportements clients & vendeurs  
- Détection des zones logistiques à risque  
- Recommandations business basées sur les données

---
## 🛠️ Compétences utilisées

### Business Intelligence & Data Analysis
![Power BI](https://img.shields.io/badge/Power%20BI-FFE200?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0A74DA?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-0E5C8A?style=for-the-badge&logo=microsoft&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-4CAF50?style=for-the-badge&logo=googleanalytics&logoColor=white)

### Programmation & Data Processing
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Visualisation & Dashboard Design
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-673AB7?style=for-the-badge&logo=tableau&logoColor=white)
![Storytelling](https://img.shields.io/badge/Storytelling%20With%20Data-FF9800?style=for-the-badge)

### 🔹 Git / Déploiement
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

© 2025 – **Projet Power BI MellowMood**  
Réalisé par *Yasmin AMMAR*

---

## Contact
**Email :** [yesmin.ammar001@email.com](mailto:yesmin.ammar001@email.com)  
**LinkedIn :** [https://www.linkedin.com/in/yasmin-ammar/](https://www.linkedin.com/in/yasmin-ammar/)
