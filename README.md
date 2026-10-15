# Libft

Libft est une bibliothèque en C réalisée dans le cadre du cursus de l’école 42. Elle rassemble des réimplémentations de fonctions courantes de la libc et des fonctions utilitaires pour travailler avec les chaînes de caractères, la mémoire et les listes chaînées.

## Contenu

- Fonctions de manipulation des caractères et de conversion
- Fonctions de gestion de la mémoire
- Fonctions de manipulation des chaînes de caractères
- Fonctions d’écriture vers un descripteur de fichier
- En bonus : outils pour créer, parcourir et libérer des listes chaînées (`t_list`)

## Compilation

Depuis la racine du dépôt, compiler la bibliothèque principale :

```sh
make -C libft
```

Pour ajouter les fonctions bonus à l’archive :

```sh
make -C libft bonus
```

La compilation génère l’archive statique `libft/libft.a`, à réutiliser et à lier à un projet C. Les prototypes sont regroupés dans `libft/libft.h`.

## Nettoyage

```sh
make -C libft clean   # supprime les fichiers objets
make -C libft fclean  # supprime les fichiers objets et l’archive
make -C libft re      # reconstruit la bibliothèque principale
```
