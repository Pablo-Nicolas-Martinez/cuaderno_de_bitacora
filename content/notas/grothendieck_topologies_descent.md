+++
title = "Topologías de Grothendieck y descenso"
date = 2025-09-14
draft = false
+++

El objetivo de estas notas es reflejar las nociones básicas y elementales de topologías de Grothendieck y teoría de descenso de manera informal e intuitiva. Las principales referencias a seguir son las notas de Halpern-Leistner, la sección de Vistoli de _FGA Explained_, y las notas de ...

## Prehaces de forma general

Un prehaz en un espacio topológico \\( (X, \mathcal{T}) \\) es simplemente una asignación de un objeto matemático (como espacio vectorial, módulo, representación, etc.) a cada abierto \\( U \in \operatorname{Op}(X) \\) de manera que los morfismos de inclusión \\( i \colon V \to U \\) inducen morfismos de restricción. De manera más general, si entendemos el sistema \\( \operatorname{Op} X \\) de abiertos como una categoría, un prehaz no es más que un funtor contravariante \\( \mathcal{F} \colon (\operatorname{Op} X)^\text{op} \to \mathcal{C} \\) para alguna categoría de llegada \\( \mathcal{C} \\).

<p class="definition">Dadas dos categorías \( \mathcal{C} \) y \( \mathcal{D} \), un <i>prehaz</i> en \( \mathcal{C} \) con valores en \( \mathcal{D} \) es un funtor contravariante de \( \mathcal{C} \) a \( \mathcal{D} \).</p>

Dado que los funtores contravariantes tienen su importancia propia dentro de la teoría de categorías, es natural preguntarse por qué es necesario dotarles de un nombre diferente. El objetivo de esta sección es mostrar que, si uno está dispuesto a tomar seriamente la analogía entre prehaces y funciones en un espacio topológico, podemos llegar a afirmaciones interesantes sobre la estructura de los prehaces.

Existe un modelo de prehaz distinguido que formará la base del resto de la disertación. Para el caso de nuestra categoría modelo, \\( \operatorname{Op} X \\), el conjunto de objetos tiene de forma natural unos mapas de inclusión \\( i \colon U \to X \\) de forma canónica. En otras palabras, los objetos de la categoría quedan completamente identificados con dichos mapas de inclusión. Una forma de reescribir estas condiciones es mediante un isomorfismo de categorías \\( \operatorname{Op} X \simeq \operatorname{Hom}(\cdot, X) = \mathrm{h}_X \\). En esta circunstancia concreta, basta con dar la imagen de nuestro funtor en el espacio total \\(X\\): efectivamente, el resto de imágenes se obtienen por naturalidad simplemente restringiendo el dominio. Este resultado es la esencia del conocido como _lema de Yoneda_.

<p class="lemma">Dado un prehaz $ \mathcal{F} \colon \mathcal{C}^\text{op} \to \operatorname{Set} $, existe una correspondencia ....</p>

La demostración en el caso de ..... $X = 0$.
\\[
    \int_{\Omega} \mathrm{d} \omega = \int_{\partial \Omega} \omega.
\\]

## Referencias

<div class="csl-bib-body" style="line-height: 1.35; margin-left: 2em; text-indent:-2em;">
  <div class="csl-entry" style="margin-bottom: 1em;">Goldberg, Samuel I. 1998. <i>Curvature and Homology</i>. 1. publ., Unabridged, corr.enl. Republ. of the 2. print. 1970. Dover Books on Mathematics. Dover Publ.</div>
  <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_id=urn%3Aisbn%3A978-0-486-40207-9&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=book&amp;rft.btitle=Curvature%20and%20homology&amp;rft.place=Mineola%2C%20NY&amp;rft.publisher=Dover%20Publ&amp;rft.edition=1.%20publ.%2C%20unabridged%2C%20corr.%2C%20and%20enl.%20republ.%20of%20the%202.%20print.%201970&amp;rft.series=Dover%20books%20on%20mathematics&amp;rft.aufirst=Samuel%20I.&amp;rft.aulast=Goldberg&amp;rft.au=Samuel%20I.%20Goldberg&amp;rft.date=1998&amp;rft.tpages=395&amp;rft.isbn=978-0-486-40207-9&amp;rft.language=eng"></span>
  <div class="csl-entry">Wall, C. T. C. 1993. <i>A geometric introduction to topology</i>. Dover Publications.</div>
  <span class="Z3988" title="url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_id=urn%3Aisbn%3A978-0-486-67850-4&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=book&amp;rft.btitle=A%20geometric%20introduction%20to%20topology&amp;rft.place=New%20York&amp;rft.publisher=Dover%20Publications&amp;rft.aufirst=C.%20T.%20C.&amp;rft.aulast=Wall&amp;rft.au=C.%20T.%20C.%20Wall&amp;rft.date=1993&amp;rft.tpages=168&amp;rft.isbn=978-0-486-67850-4"></span>
</div>