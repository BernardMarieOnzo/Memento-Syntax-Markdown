# Memento-Syntax-Markdown

Il est possible d'utiliser le Markdown à divers endroits sur GitHub :

* Les Gists
* Les commentaires dans les issues et pull request
* Les fichiers avec l'extension `.md` ou `.markdown`

## Texte

### Paragraphes

Pour créer des paragraphes, il suffit de laisser une ligne vide entre le texte. Les simples sauts de lignes ne sont pas pris en compte et poursuivent sur la même ligne.

```
Voici un paragraphe !

En voilà un autre

Ceci est une phrase avec un saut
de ligne
```

**Résultat :**

Voici un paragraphe !

En voilà un autre

Ceci est une phrase avec un saut
de ligne

### Emphase

Gras :

\*\*Texte en gras\*\* = **Texte en gras**

Italique :

\*Texte en italique\* = *Texte en italique*

Barré :

\~\~Texte barré\~\~ = ~~Texte barré~~

### Les titres

```
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6
```

**Résultat :**

# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6

### Barres de séparation

Plusieurs tirets ou étoiles, au choix

````
----------------

****************
````

**Résultat :**

----------------

## Les listes

### Liste non ordonnée

````
* Element 1
* Element 2
* Element 3
    * Element 3.1
    * Element 3.2
        * Element 3.2.1
* Element 4
````

**Résultat :**

* Element 1
* Element 2
* Element 3
    * Element 3.1
    * Element 3.2
        * Element 3.2.1
* Element 4

### Liste ordonnée

````
1. Element 1
2. Element 2
3. Element 3
    * Element 3.1
    * Element 3.2
        * Element 3.2.1
4. Element 4
````

**Résultat :**

1. Element 1
2. Element 2
3. Element 3
    * Element 3.1
    * Element 3.2
        * Element 3.2.1
4. Element 4

## Liens

````
[Texte du lien](url du lien)

Du texte avec un lien vers [OpenClassrooms](https://openclassrooms.com/)
````

**Résultat :**

[Texte du lien](url du lien)

Du texte avec un lien vers [OpenClassrooms](https://openclassrooms.com/)

## Citations

````
Voici une citation :

> Ceci est une citation
>
> sur plusieurs lignes.
> Les simples sauts de lignes fonctionnent
>
> > Les citations a l'interieur
> > d'autres citations aussi
````

Voici une citation :

> Ceci est une citation
>
> sur plusieurs lignes.
> Les simples sauts de lignes fonctionnent
>
> > Les citations a l'interieur
> > d'autres citations aussi

## Insertion de code

### Code en ligne

````
Du texte avec un peu `de code` à l'intérieur
````

**Résultat :**

Du texte avec un peu `de code` à l'intérieur

### Blocs de code

````

```
Ceci est un bloc de code
sur plusieurs lignes
```

``` javascript
alert("Ceci est un bloc de code javascript avec coloration syntaxique")
console.log("Hello World !")
```

````

**Résultat :**

```
Ceci est un bloc de code
sur plusieurs lignes
```

``` javascript
alert("Ceci est un bloc de code javascript avec coloration syntaxique")
console.log("Hello World !")
```

## Liste des taches

````
- [x] Fait
- [ ] A faire
- [x] Fait
````

**Résultat :**

- [x] Fait
- [ ] A faire
- [x] Fait

## Tableaux

````
Titre premère colonne | Titre deuxième colonne
----------------------|-----------------------
Contenu première colonne | Contenu deuxième colonne
Deuxième ligne | Deuxième ligne
 | <- Case vide
Quatrième ligne | Quatrième ligne
````

**Résultat :**

Titre premère colonne | Titre deuxième colonne
----------------------|-----------------------
Contenu première colonne | Contenu deuxième colonne
Deuxième ligne | Deuxième ligne
 | <- Case vide
Quatrième ligne | Quatrième ligne

## Images

````
![Texte Alternatif](lien de l'image)
````

## Emoji

GitHub supporte l'utilisation d'emoji. Vous trouverez la liste
[ici](http://www.webpagefx.com/tools/emoji-cheat-sheet/).

````
:smile: :dizzy_face:

:heart:
````

**Résultat :**

:smile: :dizzy_face:

:heart:

## Autres

> Je sais faire quelque chose en HTML mais j'y arrive pas en Markdown! :sob:

Pas de panique! Sur GitHub, il est possible d'ajouter du HTML dans son fichier Markdown :smile:

````
Ceci est du Markdown

<p>Et voici du HTML<p>

Sur la <a href="#">même<a> ligne
````

**Résultat :**

Ceci est du Markdown

<p>Et voici du HTML<p>

Sur la <a href="#">même<a> ligne
