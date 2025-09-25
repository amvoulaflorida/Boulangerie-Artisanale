Projet Data – Dashboard des ventes (Boulangerie Artisanale)
🚩 Problématique

La boulangerie générait chaque jour un volume important de ventes mais :

Les données étaient brutes et dispersées

Impossible d’analyser le CA par produit, jour ou créneau horaire

Difficulté à identifier les meilleurs produits et périodes de vente

Les décisions étaient basées sur l’intuition plutôt que sur des indicateurs fiables

💡 Solution apportée

J’ai conçu un dashboard interactif Power BI permettant de :
✔️ Suivre les KPI globaux : chiffre d’affaires total, quantités vendues, transactions
✔️ Identifier les jours et horaires les plus rentables
✔️ Visualiser le Top 10 des produits les plus vendus
✔️ Suivre l’évolution du CA mensuel
✔️ Explorer les ventes avec un diagramme de flux (Produit → Horaire → Jour)

🗂️ Modélisation des données

Pour rendre l’analyse fluide, j’ai appliqué une modélisation en étoile (Star Schema) avec une table de faits centrale et plusieurs tables de dimensions.

📌 Schéma du modèle

🔹 Table de faits

Ventes : contient les mesures chiffrées (CA, Quantité, Transaction) et les clés de jointure

🔹 Tables de dimensions

Produit : catégories, prix, type de produit

Date : jour, mois, année (permet l’analyse temporelle)

Heure : heure précise et tranche horaire (matin, midi, soir)

✅ Avantage : cette modélisation facilite les relations simples et optimise les calculs dans Power BI (mesures DAX dynamiques).

📈 Résultats & Insights

Le samedi est le jour avec le plus de transactions (26 031)

Les ventes se concentrent le matin (42 %) et le midi (41 %)

L’activité traiteur génère +1,1 M€ de CA (35 % du total)

Le mois d’août est le plus performant (420K €), novembre le plus faible (139K €)

🛠️ Stack technique

Power BI Desktop : visualisation et storytelling

Power Query : nettoyage et transformation des données

DAX : mesures (CA total, % par tranche horaire, top produits)

Modélisation en étoile : meilleure performance et lisibilité

🚀 Impact

Grâce à ce tableau de bord, la boulangerie peut désormais :

Piloter ses ventes en temps réel

Adapter sa production aux pics de demande

Identifier les produits stratégiques

Prendre des décisions data-driven

------------------------
📩 Me contacter
** Amvoula Naïsia** Besoin d’un accompagnement personnalisé ? Vous êtes une TPE, PME ou une organisation en croissance sans solution  automatisée ? Vous souhaitez créer un tableau de bord adapté à vos besoins, même sans base de données initiale ?

👉 Je vous accompagne de A à Z pour :

Structurer vos données

Créer une base propre, exploitable dans Power BI

Concevoir des tableaux de bord visuels et dynamiques

Former vos équipes à l’analyse et à l’automatisation 💼 Data & Business Intelligence
📧 naisiaamvoula@gmail.com Linkdin:www.linkedin.com/in/naisia-florida-ndjaepimbi-amvoula-2b8130295
