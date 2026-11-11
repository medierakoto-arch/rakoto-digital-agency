# Rakoto Digital Solutions - Site web

Site statique (HTML + CSS), déployé sur Vercel.

## Structure

- `index.html` : page principale (accueil, services, tarifs, processus, à propos, contact)
- `style.css` : styles du site
- `mentions-legales.html` : mentions légales
- `robots.txt`, `sitemap.xml` : référencement (SEO)

## Déploiement

Chaque `git push` sur la branche principale redéploie automatiquement le site sur Vercel.

## Quand le nom de domaine (.com / .mg) sera acheté

Remplacer `https://rakoto-digital-agency.vercel.app` par le nouveau domaine dans :
`index.html` (balises `og:url` et JSON-LD), `robots.txt` et `sitemap.xml`.

## À ne pas faire

- Ne pas renommer ni supprimer le projet sur Vercel sans raison : l'adresse `.vercel.app` changerait.
