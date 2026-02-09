# Todos

+ Ajouter 2 boutons pour changer de langues (IT + EN).
+ Ne pas ajouter de JS pour le faire.
Une page par langue.

Concrètement :
+ index.html → français
+ index-en.html → anglais
+ index-it.html → italien

Le bouton de langue ne serait ainsi qu'un lien vers une autre page.

```html
<nav class="lang-switch">
  <a href="index.html">FR</a> |
  <a href="index-en.html">EN</a> |
  <a href="index-it.html">IT</a>
</nav>
```
