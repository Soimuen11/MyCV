# CV de Philippe Iannetta

**CV en ligne d'un administrateur systèmes et réseaux : page web statique, responsive et optimisée pour l'impression, hébergée sur GitHub Pages.**

[![Site en ligne](https://img.shields.io/badge/CV-cv.phiannetta.xyz-38bdf8?style=for-the-badge&logo=githubpages&logoColor=white)](https://cv.phiannetta.xyz)
[![HTML5](https://img.shields.io/badge/HTML5-CSS3%20%7C%20JavaScript-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)

---

## À propos

Ce dépôt contient le code source de mon CV en ligne, accessible à l'adresse [cv.phiannetta.xyz](https://cv.phiannetta.xyz). Il présente mon parcours, mes compétences, mes formations, mes projets et mes langues.

Le CV est une page unique, sans framework ni étape de compilation : elle se charge rapidement, s'adapte à la taille de l'écran et peut être imprimée ou exportée en PDF.

---

## Contenu du CV

| Section | Description |
|:--------|:------------|
| **Expériences professionnelles** | Postes occupés, missions et responsabilités. |
| **Compétences** | Supervision, stockage, systèmes, virtualisation, automatisation, développement, réseaux, sauvegardes, etc. |
| **Formations** | Parcours scolaire et diplômes. |
| **Projets** | Projets d'infrastructure, de développement web et de programmation, réalisés à titre personnel ou en entreprise. |
| **Linguistique** | Langues parlées et niveaux (CECR). |

---

## Organisation du dépôt

| Élément | Rôle |
|:--------|:-----|
| `index.html` | Page du CV (structure, styles et scripts). |
| `pdf/` | Versions PDF du CV. |
| `kartunix.jpg` | Image utilisée par la page. |
| `CNAME` | Nom de domaine personnalisé (`cv.phiannetta.xyz`). |
| `readme.md` | Ce fichier. |

---

## Technologies

- HTML5, CSS3 et JavaScript, sans framework.
- [Font Awesome](https://fontawesome.com/v4/) pour les icônes de contact.
- [Google Fonts](https://fonts.google.com/) pour la typographie.
- [GitHub Pages](https://pages.github.com/) pour l'hébergement, avec un domaine personnalisé.

---

## Développement local

Aucune dépendance n'est nécessaire. Deux options :

```bash
# Option A : ouvrir directement le fichier dans un navigateur
xdg-open index.html

# Option B : lancer un serveur local (recommandé)
git clone https://github.com/Soimuen11/MyCV.git
cd MyCV
python3 -m http.server 8000
```

Avec l'option B, le CV est accessible à l'adresse `http://localhost:8000`.

---

## Mise à jour et déploiement

1. Modifier `index.html` (contenu, styles ou scripts).
2. Vérifier le rendu en local, notamment sur petit écran et à l'impression (`Ctrl+P`).
3. Mettre à jour le fichier PDF du dossier `pdf/` si le contenu a changé.
4. Pousser les modifications sur la branche `main` : GitHub Pages republie automatiquement le site.

---

## Retours

Il s'agit d'un CV personnel : les contributions directes au contenu ne sont pas acceptées. Les retours restent les bienvenus :

- une faute, une coquille ou un lien cassé : ouvrir une [issue](https://github.com/Soimuen11/MyCV/issues) ;
- un défaut d'affichage : ouvrir également une issue en précisant le navigateur, l'appareil et la taille d'écran utilisés.

---

## Auteur

**Philippe Iannetta** ([@Soimuen11](https://github.com/Soimuen11))

- Portfolio : [portfolio.phiannetta.xyz](https://portfolio.phiannetta.xyz)
- Blog : [blog.phiannetta.xyz](https://blog.phiannetta.xyz), dépôt [Blog](https://github.com/Soimuen11/Blog)
- Autre projet : [FreeWiki](https://freewiki.phiannetta.xyz), base de connaissances sur l'administration Linux et le shell
