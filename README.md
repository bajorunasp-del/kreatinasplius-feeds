# Kreatinas+ XML srautai

Prekių XML srautai kainų palyginimo svetainėms. Failai atnaujinami automatiškai kas 3 valandas
(`.github/workflows/feeds.yml`) iš Shopify Storefront API ir skelbiami per GitHub Pages:

- kainos.lt: `https://bajorunasp-del.github.io/kreatinasplius-feeds/kainos.xml`
- kaina24.lt: `https://bajorunasp-del.github.io/kreatinasplius-feeds/kaina24.xml`
- PerkuVisur.lt: `https://bajorunasp-del.github.io/kreatinasplius-feeds/perkuvisur.xml`

Prekių sąrašas ir pavadinimai – `scripts/build_feeds.py` (`FEED`). Rankinis paleidimas:
Actions → „XML srautų atnaujinimas“ → Run workflow.

Jei nepavyksta gauti duomenų iš Shopify, seni failai lieka nepakeisti.
