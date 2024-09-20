# Git2

# Bonjour votre star rapaldos est ici pour vous fournir la fameuse "help" que le monde à besoin § 

# Comment cloner le dépôt
git clone https://github.com/ton-compte/ton-depot.git

# Comment installer les dépendances :
pip install -r requirements.txt


# Comment exécuter les tests :
pytest 
# ou encore
Tox 

# Comment interagir avec l'API :
uvicorn main:app --reload
# et commander l'API : 
GET http://127.0.0.1:8000/status

# Exemples de requête 
curl -X GET "http://127.0.0.1:8000/status"



