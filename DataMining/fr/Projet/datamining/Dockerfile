# Dockerfile pour le conteneur d'analyse des données

# Utilisation d'une image de base avec les dépendances nécessaires
FROM python:3.9

# Copier les fichiers sources dans le conteneur
COPY Visu.ipynb /app/Visu.ipynb

# Définir le répertoire de travail
WORKDIR /app

# Installer les dépendances Python
RUN pip install pandas numpy

# Exécuter le script d'analyse des données au démarrage du conteneur
CMD ["python", "Visu.ipynb"]
