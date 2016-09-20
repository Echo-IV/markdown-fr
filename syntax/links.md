# Links

Markdown supporte deux styles de liens: en ligne et référence.

Pour les deux styles, le lien texte est délimité par des [crochets].

Pour créer un lien en ligne, utilisez une paire de parentheses régulière immédiatement après le lien texte fermant les crochets. A l'intérieur des parentheses, mettez l'url ou vous voulez que le lien pointe, avec un titre optionnel pour le lien entouré de guillemets. Par exemple:
```markdown
[Je suis un lien en ligne](https://www.google.com)

[Je suis un lien en ligne avec un titre](https://www.google.com "Google's Homepage")

[Je suis un lien de référence][Texte de référence insensible à la casse]

[Je suis un lien relatif vers un répertoire de fichiers](../blob/master/LICENSE)
```

Les liens de référence utilisent une seconde paire de crochets, a l'intérieur desquels vous pouvez mettre un label que vous choisissez pour identifié le lien:
```markdown
Ceci est [un exemple][id] de lien de référence.
```

Vous pouvez optionnellement utiliser un espace pour séparer les paires de crochets:
```markdown
Ceci est [un exemple] [id]  de lien de référence.
```

Ensuite, partout dans le document, vous pouvez définir vos label de lien comme ceci, sur une ligne:
```markdown
[id]: http://exemple.com/  "Ici titre optionnel"
```

**GitHub** and **GitBook** supports URL autolinking. They will autolink standard URLs, so if you want to link to a URL (instead of setting link text), you can simply enter the URL and it will be turned into a link to that URL.


---

Here's a quiz about markdown links.

Select the valid links:
- [x] `[a link](http://google.fr)`
- [ ] `(a link)[http://google.fr]`

> The link text is delimited by [square brackets].

What are the correct informations from this link: ```[a link](http://google.fr "google")```
- [ ] the link is https://google.fr
- [x] the title of the link is "google"
- [ ] it'll show the text "google"
- [x] it'll show the text "a link"

> Links can have 3 parts: the text, the url and a title.

---

