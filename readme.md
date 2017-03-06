# starterkit

destiné aux étudiants imd3 de eikon


## workflow

1. télécharger une distribution d'initializr http://www.initializr.com

   * placer l'archive téléchargée dans ./ressources/scripts

   * décompresser l'archive, la renommer en mirror, et la déplacer dans ./site

2. remplacer normalize.css par sanitize.css

   voir l'article sur http://cyrilvernier.net/teaching/ressource/css-reset.html

3. nettoyer le CSS de Boilerplate / initializr

4. compléter les déclarations de base (main.css ou _base.scss)
```scss
/* ==========================================================================
 * Base
 * ========================================================================== */

html {
    height: 100%;
}

body {
    font-size: 16px;
    min-height: 100vh;
    position: relative;
    
    text-rendering: optimizeLegibility !important;
    -webkit-font-smoothing: antialiased !important;
}

img {
    height: auto;
    width: 100%;
}

```
remplacer
premières opérations (rythme vertical, établir ratio typo http://type-scale.com/, …)
@import styles
passer styles print dans print.css
documenter les dossiers (SMACSS), usage de partials, nomenclature des classes (anglais et bas de casse), préfixage .l-, .t- et .[module]-
utiliser un GS dans layout
