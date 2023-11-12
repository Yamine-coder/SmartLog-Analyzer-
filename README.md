# 🧠 Log Mining Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Unsupervised-green)
![Logs](https://img.shields.io/badge/Log%20Analysis-Cyber%20&%20DevOps-purple)
![License](https://img.shields.io/badge/License-MIT-green)

> Ce projet a pour objectif de réaliser une **analyse intelligente de logs systèmes** afin de détecter des **anomalies** et **comportements suspects**, à l’aide de techniques de **machine learning non supervisé**.

---

## 🎯 Objectifs du projet

- 🧠 Identifier automatiquement des patterns récurrents dans des fichiers de logs
- 🔍 Détecter des anomalies de comportement ou d’usage
- 📊 Visualiser les clusters de lignes similaires
- 💡 Appliquer une logique **data-driven** à des fichiers souvent peu exploités

---

## 📁 Cas d’usage

Ce projet s’applique à plusieurs contextes :

- 🔐 **Cybersécurité** : détection de comportements suspects dans les logs (accès anormaux, commandes inhabituelles)
- 🧰 **DevOps / SRE** : analyse d’incidents récurrents, identification de pannes
- 🧾 **Conformité** : surveillance de fichiers système, audit RGPD

---

## 🧪 Techniques utilisées

| Technique / Module    | Description |
|-----------------------|-------------|
| `TF-IDF`              | Vectorisation des lignes de logs |
| `KMeans`              | Clustering non supervisé |
| `t-SNE` / `PCA`       | Réduction de dimension |
| `matplotlib` / `seaborn` | Visualisations des clusters |
| `NLTK`                | Prétraitement du texte |

---

## 🧰 Stack technique

- Python 3.10+
- scikit-learn
- pandas / numpy
- NLTK
- matplotlib, seaborn
- Jupyter Notebook

---

## 🚀 Lancer le projet

### 1. Cloner le dépôt

```bash
git clone https://github.com/Yamine-coder/log-mining-analysis.git
cd log-mining-analysis
```

### 2. Créer un environnement virtuel

```bash
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Lancer le notebook

```bash
jupyter notebook
```

---

## 📂 Structure

```bash
📁 data/            # Exemple de fichiers de logs
📁 notebooks/       # Analyse principale (.ipynb)
📄 requirements.txt # Dépendances Python
```

---

## 📊 Résultats

Le notebook produit :
- Un clustering visuel des logs
- Un classement des types de commandes/séquences dominantes
- Une détection automatique d’anomalies


---

## 📄 Licence

Ce projet est sous licence MIT – libre d’utilisation, modification et distribution.

---

## 👨‍💻 Auteur

**Yamine Moussaoui**  
🎓 MSc Intelligence Artificielle & Big Data  
💼 Consultant en Solutions Data & IA  
🔗 [LinkedIn](https://www.linkedin.com/in/yamine-moussaoui-672a25205/) 
📧 moussaouiyamine1@gmail.com  
🔎 [GitHub](https://github.com/Yamine-coder)


