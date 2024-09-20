FROM python:3.9-slim

# Définir le répertoire de travail de l'application
WORKDIR /app

# Copier le fichier requirements.txt dans le conteneur
COPY requirements.txt requirements.txt

# Installer les dépendances nécessaires
RUN pip install --no-cache-dir -r requirements.txt

# Copier tout le code source dans le conteneur
COPY . .

# Exposer le port 8000 sur lequel FastAPI va tourner
EXPOSE 8000

# Définir les variables d'environnement pour la clé API (facultatif)
# ENV GROQ_API_KEY=ton_api_key

# Commande pour lancer l'application FastAPI avec Uvicorn
CMD ["uvicorn", "mini_groq:app", "--host", "0.0.0.0", "--port", "8000"]

