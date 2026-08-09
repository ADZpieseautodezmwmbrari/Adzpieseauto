# ADZ Piese Auto

Site static gata pentru GitHub Pages.

## Publicare
1. Creează un repository GitHub numit `adzpieseauto`.
2. Urcă toate fișierele din acest folder.
3. Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. La Custom domain scrie `adzpieseauto.ro`.

## DNS pentru domeniu
Pentru domeniul principal adaugă A records:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Pentru `www`, adaugă CNAME către `<username-ul-tau>.github.io`.

După propagare activează `Enforce HTTPS`.

## Google
Adaugă site-ul în Google Search Console și trimite:
`https://adzpieseauto.ro/sitemap.xml`
