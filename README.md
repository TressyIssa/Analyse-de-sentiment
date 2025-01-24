# **Analyse de Sentiments sur les Commentaires de Tweets**
**Contexte et Motivation**
L'analyse de sentiments est essentielle pour comprendre les opinions des utilisateurs sur des plateformes comme Twitter. Ce projet vise à classer les tweets en sentiments positifs,
négatifs ou neutres, permettant d'identifier les tendances et d'améliorer la prise de décision, par exemple dans le cadre du service client, du marketing ou des études de marché.

**Pipeline du Projet**
- **Collecte des Données :**

Utilisation d'un dataset de tweets contenant des commentaires et leurs sentiments associés.

- **Nettoyage des Données :**

Suppression des URL, mentions, hashtags et caractères spéciaux.
Conversion des textes en minuscules et suppression des stopwords.
- **Tokenisation :**

Fractionnement des tweets en mots individuels pour faciliter le traitement.
Vectorisation avec TF-IDF :

Transformation des tokens en vecteurs numériques en utilisant la méthode TF-IDF (Term Frequency-Inverse Document Frequency).
Modélisation :

Entraînement de modèles supervisés comme Random Forest, Logistic Regression ou SVM pour prédire les sentiments.
Évaluation :

Mesure des performances avec des métriques telles que l'accuracy, la précision, le rappel et le F1-score.
Technologies Utilisées
Librarie de NLP : NLTK, spaCy
Vectorisation : Scikit-learn (TF-IDF Vectorizer)
Modélisation : Scikit-learn
Visualisation : Matplotlib, Seaborn
