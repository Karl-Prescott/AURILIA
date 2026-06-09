# AURILIA - site temporaire

Site statique pret pour GitHub Pages.

## Publication GitHub Pages

1. Creer un depot GitHub nomme `aurilia`.
2. Envoyer ces fichiers dans le depot.
3. Dans GitHub, ouvrir `Settings > Pages`.
4. Choisir `Deploy from a branch`.
5. Choisir la branche `main` et le dossier `/root`.
6. Ajouter le domaine personnalise `aurilia.ca`.

## DNS chez WHC pour aurilia.ca

Ajouter ces enregistrements DNS:

```text
A     @     185.199.108.153
A     @     185.199.109.153
A     @     185.199.110.153
A     @     185.199.111.153
CNAME www   karlprescott.github.io
```

Ensuite, dans GitHub Pages, activer `Enforce HTTPS` quand l'option devient disponible.

## A remplacer

- Le lien Facebook dans `index.html`
- L'adresse `contact@aurilia.ca` si elle n'est pas encore active
