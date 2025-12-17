# Projet Docker 
ceci est un projet pour dockeriser une API simple en NodeJS.

## Commandes courantes 

1. aller dans votre projet

```bash 

# 2. Construire l'image
docker build -t unNomSuperSimple .

# 3. Voir/lister les images que l'on a construit
docker images 

# Lancer le container Docker
docker run -p 3000:3000 unNomSuperSimple

```