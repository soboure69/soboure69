
# 👋 Soboure BELLO — Data Science Engineer

<div align="center">

### 📊 Polytech Lyon — Applied Mathematics & Modeling  
### 🎯 Data Science • Machine Learning • Data Engineering

</div>

---

## 🌟 GitHub Activity (Live)

<div align="center">

![Followers](https://img.shields.io/github/followers/soboure69?style=social)
![Stars](https://img.shields.io/github/stars/soboure69?style=social)
![Views](https://komarev.com/ghpvc/?username=soboure69&color=blueviolet)

</div>

---
## 📊 GitHub Stats

<div align="center">

### 🔥 Activité Générale  
![Stats](https://github-readme-stats-sigma-five.vercel.app/api?username=soboure69&show_icons=true&theme=radical&count_private=true&include_all_commits=true)

### 🏆 Trophées  
![Trophies](https://github-profile-trophy.vercel.app/?username=soboure69&theme=dracula&margin-w=10)

### 📚 Langages les plus utilisés  
![Top Langs](https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=soboure69&layout=compact&theme=radical)

### 📈 Contribution Graph  
![Graph](https://github-readme-activity-graph.vercel.app/graph?username=soboure69&theme=react-dark&hide_border=true)

</div>

---

## 🚀 About Me

Je suis étudiant ingénieur à Polytech Lyon, spécialisé en Mathématiques Appliquées et Modélisation. Passionné par la **data science, le machine learning et l'ingénierie des données**, je transforme des problématiques complexes en solutions concrètes et exploitables.

Je combine une rigueur mathématique, un esprit analytique et une forte capacité à communiquer mes résultats pour créer de la valeur business réelle. Actuellement en recherche de *CDI Data Scientist / Data Engineer / Data Analyst*.

---

## 💡 Core Competencies

### 🐍 *Langages & Programmation*

````
Python (Avancé)       ████████████░░  Pandas, NumPy, Scikit-learn, TensorFlow
SQL (Avancé)          ████████████░░  PostgreSQL, MySQL, Requêtes complexes
R (Intermédiaire)     ████████░░░░░░  ggplot2, dplyr
C++ (Intermédiaire)   ████████░░░░░░
````

### 📈 *Data Science & ML*
- *Supervised Learning* : Régression, Classification, Gradient Boosting (XGBoost, LightGBM)
- *Unsupervised Learning* : Clustering (K-Means, DBSCAN), Dimensionality Reduction (PCA)
- *Deep Learning* : Neural Networks, CNN, RNN, LSTM, Transformers
- *NLP* : Text classification, Sentiment analysis, Word embeddings
- *Model Optimization* : Hyperparameter tuning, Cross-validation, Feature engineering

### 🔧 *Data Engineering & Tools*
- *Orchestration* : Apache Airflow
- *Databases* : PostgreSQL, MySQL, SQLAlchemy ORM
- *Visualization* : Tableau, Power BI, Plotly, Matplotlib, Seaborn
- *Deployment* : Docker, Streamlit, Dash, Heroku
- *Cloud* : AWS (S3, EC2), Google Cloud (notions)
- *MLOps* : Git/GitHub, MLflow, Jupyter Notebook

### 🎯 *Soft Skills*
✓ Communication de résultats data  
✓ Présentation aux stakeholders non-techniques  
✓ Résolution analytique de problèmes  
✓ Collaboration équipes cross-fonctionnelles  

---

## 🏆 Portfolio Projects

### 1️⃣ *Machine Learning - Prédiction Churn Clients* 
Identification de 87% des clients à risque de départ

🎯 *Problématique* : Prédire les clients qui vont résilier leur contrat dans une entreprise télécommunications  
📊 *Dataset* : 7043 clients | 26.5% taux churn  
🤖 *Modèles* : Random Forest (86.1% accuracy) vs XGBoost (87.2%)  
💰 *Impact* : Économie potentielle 100K€/an via retention ciblée  
🔍 *Key Insights* :
- Contrat mensuel = 3x plus de churn vs annuel
- Tenure et charges clients = features critiques
- Feature importance analysis + confusion matrix

📚 *Stack* : Python • scikit-learn • XGBoost • pandas • Matplotlib • Seaborn  
🔗 *GitHub* : [01_ML_Classique_Churn](https://github.com/soboure69/portfolio/01_ML_Classique_Churn)

---

### 2️⃣ *Deep Learning - NLP Sentiment Analysis IMDB*
Prédiction du sentiment en temps réel avec 92.3% d'accuracy

🎯 *Problématique* : Classifier automatiquement les avis films en sentiments positifs/négatifs  
📊 *Dataset* : 50K reviews IMDB | 10K vocabulaire  
🤖 *Architecture* : Embedding (128 dims) → Bi-LSTM (64 units) → Dense layers  
📈 *Performance* :
- Accuracy: 92.3% | Precision: 91.5% | Recall: 93.1%
- ROC-AUC: 0.975 | Inference: <500ms/review

🌐 *Déploiement* : Streamlit app interactive (3 onglets : Predict, Analytics, About)  
📚 *Stack* : TensorFlow • Keras • NLTK • Streamlit • Python  
🔗 *Live Demo* : [sentiment-analysis-soboure69.streamlit.app](https://sentiment-analysis-soboure69.streamlit.app)  
🔗 *GitHub* : [02_DL_NLP_Sentiment](https://github.com/soboure69/portfolio/02_DL_NLP_Sentiment)

---

### 3️⃣ *Data Engineering - Pipeline ETL Multi-Sources*
Orchestration automatisée de 1000+ records/jour

🎯 *Architecture* : Extraction (Reddit, Twitter, OpenWeatherMap) → Transformation → Chargement  
📦 *Données* : 1000+ records/jour | Multi-sources APIs  
🔄 *Workflow* :
- Extractors Python (praw, tweepy, requests)
- Cleaning, validation, deduplication, feature engineering
- Chargement PostgreSQL via SQLAlchemy ORM

⚡ *Optimisation* : Réduction temps traitement de 60%  
🛡️ *Robustesse* : Error handling, data quality checks, retry mechanisms  
📚 *Stack* : Python • Apache Airflow • PostgreSQL • SQL • REST APIs  
🔗 *GitHub* : [03_Data_Engineering_Pipeline](https://github.com/soboure69/portfolio/03_Data_Engineering_Pipeline)

---

### 4️⃣ *Dashboard Business - Système Recommandation E-commerce*
Moteur recommandation intelligent & dashboard interactif

🎯 *Fonctionnalité* : Content-based filtering avec cosine similarity  
📊 *Interface* : 5 visualisations analytics interactives temps réel  
💡 *UX* : Sélection produit → 5 recommandations similaires instantanées  
⚡ *Performance* : Latence <500ms/requête  
💰 *Impact Business* :
- +25% panier moyen (simulé)
- +40% CTR sur recommandations

🌐 *Déploiement* : Heroku production  
📚 *Stack* : Python • Dash • Plotly • scikit-learn • Heroku  
🔗 *Live Demo* : [product-recommender-soboure69.herokuapp.com](https://product-recommender-soboure69.herokuapp.com)  
🔗 *GitHub* : [04_Dashboard_Recommendation](https://github.com/soboure69/portfolio/04_Dashboard_Recommendation)

---

## 📚 Education & Certifications

### 🎓 Diplômes
- *Cycle Ingénieur Polytech Lyon* | 2023-2027
  - Spécialisation Data Science, ML, Deep Learning, Optimisation
  - Cours : ML Algorithms, Deep Learning, NLP, Computer Vision, Advanced Statistics, Databases, Big Data
  
- *Licence Mathématiques Appliquées* | Université de Paris Cité | 2021-2023

### 🏅 Certifications
- Machine Learning Specialization - Stanford Online (Andrew Ng) | Coursera
- Deep Learning Specialization - DeepLearning.AI | Coursera
- TensorFlow Developer Certificate - Google (En cours)
- SQL for Data Science - UC Davis | Coursera
- Python for Data Science - IBM | DataCamp

---

## 🎯 Qualités Personnelles

| Qualité | Description |
|---------|-------------|
| 🧮 *Rigueur Mathématique* | Formation solide en mathématiques appliquées, modélisation statistique |
| 🔬 *Esprit Analytique* | Résolution systématique de problèmes complexes, analyse critique |
| 📊 *Synthèse & Communication* | Capacité à vulgariser travaux techniques à audiences non-spécialisées |
| 🚀 *Autonomie & Proactivité* | Apprentissage continu, gestion projets autonome, curiosité constante |
| 👥 *Travail Collaboratif* | Excellente intégration en équipes cross-fonctionnelles agiles |
| 🌍 *Intérêt Sociétal* | Conscience de l'impact éthique des données et modèles |

---


## 🤝 Let's Connect

Vous êtes intéressé par une collaboration, une discussion technique ou une opportunité professionnelle ?

| Plateforme | Lien |
|-----------|------|
| 📧 *Email* | [soboure.bello@gmail.com](mailto:soboure.bello@gmail.com) |
| 💼 *LinkedIn* | [linkedin.com/in/sobourebello](https://www.linkedin.com/in/sobourebello) |
| 🐙 *GitHub* | [github.com/soboure69](https://github.com/soboure69) |
| 📍 *Localisation* | Paris, Île-de-France, France |

---

## 📄 Additional Resources

- 📑 *[Mon CV Détaillé](./CV_ATS.pdf)* - Version complète avec expériences et formations
- 🎯 **[Portfolio Complet](https://github.com/soboure69/portfolio)** - Tous les projets data science
- 💡 **[Blog Medium](https://medium.com/@soboure)** - Articles techniques ML/Data

---

<div align="center">

### ⭐ Si mon travail vous plaît, n'hésitez pas à mettre une star ⭐

*"Transformer les données en insights, les insights en décisions, les décisions en impact."*

</div>

---

Last updated: December 2024
