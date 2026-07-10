# CLAUDE.md — johaniefournieragr.ca

## Conventions posts

Les images de thumbnail vont toujours dans `posts/images/` et non dans le dossier du post (ex. `posts/welcome/`).

**Raison** : Quarto 1.9 traite tout fichier image référencé via `image:` dans le front matter comme un item de listing supplémentaire s'il est co-localisé avec le `index.qmd` du post. Cela génère une card vide (ghost item) dans les grilles de listing.

**Référence dans le post** :
```yaml
image: "../images/mon-post-thumbnail.jpg"
```
