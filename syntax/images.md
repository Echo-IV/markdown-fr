# Images

```markdown
# Inline
![Alternative text](/path/to/img.jpg "Optional title")

# Reference
![Alternative text][id]
[id]: url/to/image  "Optional title"
```
Comme vous avez dû le remarquer, les images en Markdown sont très semblables aux liens.  
La différence est la suivante :
* les crochets doivent être précédés par un point d'exclamation ;
* ils peuvent contenir un texte alternatif, qui s'affiche quand l'image ne peut être chargée.

---

Ici un quizz a propos des images en markdown.

Choisissez les images valides:
- [ ] `[Google logo](https://www.google.ru/logo.png)`
- [x] `![](https://www.google.ru/logo.png)`

> Les images doivent être préfixé avec un point d'exclamation.
Le texte alternatif et le titre sont optionnel.

Qu'est ce qui est vrai a propos de la ligne suivante: ```![Funny cat](http://cats.ru/funny.png "Share this")```
- [x] si l'url est 404, "chat fun" sera affiché
- [ ] Le point d'exclamation peut être ommis dans ce cas
- [ ] Si l'url est 404, "Partager ceci" sera affiché
- [x] Au survol de la souris sur l'image "Partager ceci" sera affiché

> De la même manière que pour les liens, les images ont 3 parties: un texte alternatif, une url et un titre. le point d'exclamation est necessaire.

---
