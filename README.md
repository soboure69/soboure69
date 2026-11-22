# Soboure BELLO

**Data & IA · mathématiques appliquées et modélisation**

Alternant *Data, Digitalisation & IA* chez Nigay et étudiant en MSc Intelligence Artificielle à Epitech Lyon. Formé aux mathématiques appliquées à Polytech Lyon, je construis des modèles et des applications de données, je mesure ce qu'ils valent face à des références simples, et je les livre testés et documentés.

[LinkedIn](https://www.linkedin.com/in/sobourebello) · Auvergne-Rhône-Alpes, France

---

## 🌟 Activité GitHub (En direct)

<div align="center">

![Followers](https://img.shields.io/github/followers/soboure69?style=social)
![Stars](https://img.shields.io/github/stars/soboure69?style=social)
![Views](https://komarev.com/ghpvc/?username=soboure69&color=blueviolet)

</div>

---

## 📊 Statistiques GitHub

<div align="center">

### 🔥 Activité Générale
![Activité générale](./github-metrics/general.svg)

### 🏆 Trophées
![Trophées](./github-metrics/achievements.svg)

### 📚 Langages les plus utilisés
![Langages les plus utilisés](./github-metrics/languages.svg)

### 📈 Graphique de contribution
![Graphique de contribution](https://github-readme-activity-graph.vercel.app/graph?username=soboure69&theme=react-dark&hide_border=true)

</div>

---

## Projets

| Projet | Problème | Ce que montre le projet | Preuves |
|---|---|---|---|
| [**Hackathon Mobility Citiz**](https://github.com/soboure69/hackathon-mobility-citiz) | Où implanter des stations d'autopartage pour couvrir le plus d'habitants sous un budget ? | Pipeline de données ouvertes géospatiales, optimisation en nombres entiers | 146 tests · [vidéo](https://github.com/soboure69/hackathon-mobility-citiz/releases/tag/v1.0) |
| [**CinéData**](https://github.com/soboure69/Movie-Backend) | Rendre un jeu de données de films interrogeable et exploitable | API REST, SDK publié, application déployée | 40 tests en CI · [API](https://movie-backend-x8iq.onrender.com/docs) · [PyPI](https://pypi.org/project/films-sdk-sbre/) · [application](https://movies-analytics-by-soboure-bello.streamlit.app/) |
| [**Customer Churn**](https://github.com/soboure69/Customer-Churn) | Repérer les clients d'un opérateur télécom qui risquent de partir | Apprentissage supervisé évalué sans fuite, choix du seuil de décision | Notebook réexécuté de bout en bout · `predict.py` vérifié |
| [**DataWizFlow AI**](https://github.com/soboure69/datawizflow-ai) | Interroger ses données en langage naturel sans les envoyer à un service externe | Application LLM locale conçue avec des garde-fous | 41 tests · captures dans le README |

### Hackathon Mobility Citiz — aide à l'implantation de stations

*Hackathon Epitech × Citiz, 20–21 octobre 2026, réalisé seul.*

- **Méthode.** Ingestion de cinq sources ouvertes (GTFS, GBFS, OpenStreetMap, INSEE Filosofi, Admin Express) en couches bronze / silver / gold avec manifestes de traçabilité ; accessibilité à 5 minutes sur le réseau piéton réel ; couverture maximale sous budget résolue en programmation linéaire en nombres entiers (PuLP/CBC), contrôlée par un algorithme glouton, avec une variante équité.
- **Résultat (CA de La Rochelle, scénario de référence).** 10 stations pour 85 000 € sur 3 ans couvrent 18 816 habitants de plus ; la couverture Citiz passe de 9,8 % à 20,6 %.
- **Limites.** Le modèle prédictif de fréquentation n'a pas été livré ; les coûts sont des hypothèses de simulation.

### CinéData — API, SDK et application MovieLens

*Projet personnel, en deux dépôts : [Movie-Backend](https://github.com/soboure69/Movie-Backend) (API et SDK) et [Movies-Analytics](https://github.com/soboure69/Movies-Analytics) (analyse et application).*

- **Construit.** Base SQLite et API FastAPI de 11 points d'accès déployée sur Render ; SDK Python `films-sdk-sbre` publié sur PyPI par GitHub Actions, avec nouvelles tentatives automatiques ; notebooks d'analyse et application Streamlit qui consomment l'API via le SDK.
- **Qualité.** 31 tests de l'API et 9 du SDK lancés à chaque poussée. En écrivant ces tests, j'ai trouvé et corrigé deux défauts en production : une limite négative qui contournait le plafond de pagination (100 836 lignes renvoyées d'un coup) et des erreurs 500 sur 8 films sans identifiant TMDb. La clé de l'API d'affiches a été retirée du code et des données.
- **Limites.** API en lecture seule ; hébergement gratuit qui se met en veille (30 à 60 s au premier appel).

### Customer Churn — prédiction du désabonnement

*Projet de fin de semestre, Polytech Lyon (3e année, 2024 – 2025). Jeu public Telco (7 032 clients), repris et corrigé en 2026.*

- **Méthode.** Régression logistique à classes pondérées, choisie par validation croisée sans fuite parmi cinq modèles ; seuil de décision étudié sur des probabilités hors pli, puis selon la capacité de contact et un scénario de coûts.
- **Résultat.** F1 de 0,628 sur le test (précision 0,51, rappel 0,81), contre 0,564 pour la règle « contrat mensuel = churn » : un gain réel mais modeste, présenté comme tel.
- **Ce que j'ai corrigé.** Deux variables constantes à cause d'un encodage erroné, un script de prédiction qui ne fonctionnait pas, et des scores de validation croisée gonflés par un sur-échantillonnage fait avant la validation.

### DataWizFlow AI — interroger ses données en langage naturel

*Projet personnel commencé en septembre 2025. La version actuelle est utilisable et le projet continue d'évoluer.*

- **Construit.** Application Streamlit qui traduit une question en SQL avec un LLM local (Ollama), affiche et exporte le résultat, et propose des graphiques à partir d'une spécification JSON validée — aucun code généré n'est exécuté.
- **Garde-fous.** SQL limité à une instruction en lecture, connexion en lecture seule côté serveur, délai maximal (y compris sur SQLite), mots de passe de connexion chiffrés, image Docker sans secrets.
- **Limites.** Le filtre SQL ne remplace pas un compte en lecture seule ; SQL Server n'a pas été testé sur un vrai serveur.

---

## Comment je travaille

- **Comparer à une référence simple** avant de conclure : règle métier pour le churn, algorithme glouton pour l'optimisation.
- **Tester ce qui compte** et l'automatiser : suites `pytest` sur CinéData, le hackathon Citiz et DataWizFlow AI, lancées par GitHub Actions sur CinéData.
- **Écrire les limites** dans chaque README, au même niveau que les résultats.
- **Ne jamais publier de secret** : clés et mots de passe lus depuis l'environnement ou des fichiers ignorés par Git.
- **Rendre reproductible** : graines fixées, versions figées, notebooks réexécutés de haut en bas avant de recopier un chiffre.

## Compétences, et où les voir

| Domaine | Outils | Où |
|---|---|---|
| Modélisation et apprentissage | scikit-learn, imbalanced-learn, validation croisée, choix de seuil | Customer Churn |
| Optimisation | programmation linéaire en nombres entiers (PuLP/CBC) | Hackathon Citiz |
| Données géospatiales | GeoPandas, OSMnx, NetworkX, GTFS/GBFS | Hackathon Citiz |
| API et logiciel | FastAPI, SQLAlchemy, Pydantic, pytest, packaging PyPI | CinéData |
| LLM et applications | Ollama (local), Streamlit | DataWizFlow AI |
| Déploiement et CI | Docker, GitHub Actions, Render, Streamlit Community Cloud | CinéData, DataWizFlow AI |

## Parcours

- **2026 – 2028 · MSc Intelligence Artificielle**, Epitech Lyon, en alternance (titre RNCP niveau 7 *Architecte des systèmes d'information*).
- **Depuis octobre 2026 · Alternant Data, Digitalisation & IA**, Nigay (fabricant de caramel, Feurs).
- **2023 – 2026 · Cycle ingénieur Mathématiques appliquées et modélisation**, Polytech Lyon — parcours suivi jusqu'en 4e année.
- **2021 – 2023 · Licence de mathématiques appliquées**, Université Paris Cité.

## Autres travaux

Projets plus anciens ou pas encore remis au niveau des projets ci-dessus.

- [**NeuroPrice**](https://github.com/soboure69/NeuroPrice-PINN-Pricing) — projet ingénieur de 4e année, Polytech Lyon (2026). Pricing d'options par réseaux de neurones informés par la physique (PINN, PyTorch) : erreur relative de 0,09 % sur Black-Scholes 1D et 0,3 % sur une option à barrière ; pour les options asiatiques, le PINN n'a pas convergé et un modèle supervisé entraîné sur Monte Carlo a pris le relais. 49 tests, API FastAPI.
- [**Dashboard Power BI des ventes**](https://github.com/soboure69/Projet-d-Analyse-des-Ventes-Tableau-de-Bord-Dynamique-avec-Power-BI) — modèle en étoile, Power Query et mesures DAX sur les données d'exemple Contoso. La comparaison avec l'année précédente est à corriger quand aucune année n'est filtrée.
- [**Privacy SaaS**](https://github.com/soboure69/privacy-saas) — plateforme d'anonymisation de fichiers multi-organisations (FastAPI, SQLModel, React, Stripe en mode test). Prototype : tests partiels, pseudonymisation par hachage non salé à renforcer.
