FROM python:latest
# Création du répertoire de travail
RUN mkdir /app
WORKDIR /app

# Exposition du port 5000
EXPOSE 5000

# Copie des éléments
COPY . .

# Installation des prérequis
RUN pip install -r requirements.txt

# Démarrer le projet flask sur le localhost
CMD ["flask", "run", "--host=0.0.0.0"]