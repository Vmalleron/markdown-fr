# Titres

Comme nous avons commencé à écrire un document en Markdown, nous devons ajouter un titre et quelques sous-titres.

Markdown supporte deux styles d'en-têtes, Setext et atx.

Les en-têtes de style Setext sont "soulignés" en utilisant des signes égaux (pour les en-têtes de premier niveau) et des tirets (pour les en-têtes de second niveau). Par exemple:

```
C'est un H1
===========

C'est un H1
-----------
```

Tout nombre de soulignement = ou - fonctionnera.

Les en-têtes de type Atx utilisent des caractères de hachage 1-6 au début de la ligne, correspondant aux niveaux d'en-tête 1-6. Par exemple:

```
# C'est un H1

## C'est un H2

###### C'est un H6
```


En option, vous pouvez "fermer" les en-têtes atx. C'est purement cosmétique - vous pouvez l'utiliser si vous pensez que ça a l'air mieux. Les hachages de fermeture n'ont même pas besoin de correspondre au nombre de hachages utilisés pour ouvrir l'en-tête. (Le nombre de hachages d'ouverture détermine le niveau d'en-tête.):

```
# C'est un H1 #

## C'est un H2 ##

### C'est un H3 ######
```


---

Voici un quiz sur les titres en Markdown.

Sélectionnez les en-têtes valides:
- [x] `# hello`
- [ ] `#hello`

> Les en-têtes ont besoin d'espace entre les caractères de hachage et le texte.

Sélectionnez les en-têtes valides:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seuls '=' et '-' sont acceptés pour souligner un en-tête.

---


