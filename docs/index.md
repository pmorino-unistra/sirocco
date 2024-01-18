# Bienvenue sur la documentation Sirocco

Documentation de mkdocs : [mkdocs.org](https://www.mkdocs.org).

## Tout ce site est généré à partir de fichiers Markdown

Exemple de syntaxe basique :
```markdown
# Titre 1
## Titre 2 
### Titre 3...

**gras**
_italique_
```

Un petit bout de `code` peut être mis en avant facilement. 

Et un formattage automatique par langage est intégré : 

### Exemple SQL

```SQL title="script_postgre.sql"
SELECT *
FROM sirocco
WHERE annee_civile  = 2024;
```

### Exemple Python (pour Cédric)

Avec les numéros de ligne et le surlignage de la ligne 3.

```py linenums="1", hl_lines="3"
import sirocco

def super_entrepot():
    for i in range(len(id_univ)):
        //...

```

## Chaque page est un fichier texte en .md

En créant un fichier texte et en l'ajoutant au projet il est ajouté dans le menu de navigation. 

## Menu de navigation intégré

Comme le markdown gère les balises (titre 1, 2 ...) des menus de navigation interactifs sont générés automatique **sans que ça prenne le moindre temps !**
