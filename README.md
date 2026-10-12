# jlqch.github.io

Sitio raíz de GitHub Pages de Jose Luis Querido Chica: https://jlqch.github.io/

- `index.html`: portada con enlaces a las apps y a su documentación (`SOFTWARE_DOCS`).
- La portada es la **URL de marketing** de las apps en App Store Connect (Múltiplo y
  SPLOP!): es el «sitio web del desarrollador» de la ficha, y de ahí saca AdMob el
  dominio donde busca `app-ads.txt`.
- `app-ads.txt`: verificación de AdMob. Tiene que servirse en la raíz del
  dominio (`https://jlqch.github.io/app-ads.txt`), por eso vive en este
  repositorio y no en `SOFTWARE_DOCS`. Contiene el ID de editor de AdMob; vale
  para todas las apps de la cuenta y se cambia solo si cambia la cuenta.

Este repositorio tiene que llamarse exactamente `jlqch.github.io` para que
GitHub lo sirva en la raíz del dominio.
