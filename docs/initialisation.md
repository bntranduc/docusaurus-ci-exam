# Initialisation du projet et configuration de Docusaurus

## Étapes

1. Création du dépôt GitHub.
2. Clonage du dépôt localement.
3. Initialisation d'un nouveau site Docusaurus.
4. Installation des dépendances.
5. Premier commit et push vers `main`.

## Commandes utilisées

```bash
npx create-docusaurus@latest my-website classic
mv my-website/* ./
mv my-website/.* ./
rm -rf my-website
npm install
git add .
git commit -m "Initialisation du projet Docusaurus"
git push origin main
