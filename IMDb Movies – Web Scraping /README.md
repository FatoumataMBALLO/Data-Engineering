# 🎬 IMDb Movies – Web Scraping Project

## 📌 Description du projet

Ce projet a pour objectif de **scraper des données de films depuis le site IMDb** afin de constituer un jeu de données exploitable pour des analyses ultérieures (data analysis, visualisation, BI, etc.).

Le script permet de collecter automatiquement plusieurs informations clés sur des films IMDb, de les structurer dans un DataFrame Pandas, puis de les exporter pour une utilisation future.

Le projet est implémenté sous forme de **notebook Jupyter**, ce qui facilite la lecture, l’exécution pas à pas et l’évolution du code.

---

## 🎯 Objectifs

* Comprendre la structure HTML du site IMDb
* Mettre en place un **web scraping robuste et lisible**
* Structurer les données avec **Pandas**
* Appliquer de bonnes pratiques (fonctions, temporisation, headers HTTP)
* Préparer les données pour une exploitation Data / BI

---

## 🛠️ Technologies utilisées

* **Python 3**
* **Requests** : requêtes HTTP
* **BeautifulSoup (bs4)** : parsing HTML
* **Pandas** : manipulation et structuration des données
* **Time / Random** : gestion des délais entre requêtes
* **Jupyter Notebook**

---

## 📂 Contenu du projet

* `Projet web scraping imdb Movies.ipynb` : notebook principal contenant :

  * la récupération des pages IMDb
  * l’extraction des informations des films
  * la structuration des données
  * l’export des résultats

---

## 🔍 Données collectées

Selon la disponibilité sur IMDb, le script permet d’extraire notamment :

* Titre du film
* Année de sortie
* Note IMDb
* Nombre de votes
* Durée
* Genre(s)
* Réalisateur(s) / Acteur(s) (si présents)

> ⚠️ Les données dépendent de la structure HTML du site IMDb et peuvent nécessiter des ajustements si celle-ci évolue.

---

## ▶️ Accès au notebook

Le notebook est accessible via Google Drive :

👉 **Lien direct** :
[https://drive.google.com/file/d/1W3R8BDxaE9nAq_zecXThooRCvjXrFmng/view?usp=sharing](https://drive.google.com/file/d/1W3R8BDxaE9nAq_zecXThooRCvjXrFmng/view?usp=sharing)

---

## 🚀 Exécution du projet

1. Télécharger le notebook depuis le lien ci-dessus
2. Ouvrir le fichier avec Jupyter Notebook ou Jupyter Lab
3. Installer les dépendances nécessaires si besoin :

   ```bash
   pip install requests beautifulsoup4 pandas
   ```
4. Exécuter les cellules du notebook dans l’ordre

---

## 🧠 Améliorations possibles

* Gestion avancée des erreurs HTTP et HTML
* Normalisation et nettoyage approfondi des données
* Stockage en base de données (SQL Server, PostgreSQL, etc.)
* Automatisation du scraping (batch / planification)
* Connexion à Power BI pour la visualisation

---

## ⚖️ Avertissement légal

Ce projet est réalisé **à des fins pédagogiques et personnelles uniquement**.
Merci de respecter les **conditions d’utilisation d’IMDb** et de ne pas surcharger leurs serveurs.

---

## 👤 Auteur

Projet réalisé par une **Data Analyst**, dans une démarche d’apprentissage et de montée en compétences sur le web scraping et la préparation de données.

---

📬 N’hésite pas à proposer des améliorations ou des retours sur le projet !

