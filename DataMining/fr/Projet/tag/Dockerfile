# Dockerfile pour le conteneur de recommandation

# Utilisation d'une image de base avec les dépendances nécessaires
FROM python:3.9

# Copier les fichiers sources dans le conteneur
COPY Tags.ipynb /app/Tags.ipynb

# Définir le répertoire de travail
WORKDIR /app

# Installer les dépendances Python
RUN pip install scikit-learn

# Exécuter le script de recommandation au démarrage du conteneur
CMD ["python", "Tags.ipynb"]

