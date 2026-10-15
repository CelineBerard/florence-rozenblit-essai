# Site de Florence Rozenblit

Avocat honoraire, médiatrice et négociatrice à Avignon. Site d'essai, non référencé.

- Hébergement : Cloudflare (projet dédié `florence-rozenblit-site`, sans ressource partagée).
- Pages : dossier `public/`, générées par un script local à partir des textes validés.
- Publication : `npx wrangler deploy`.
- `public/_redirects` : redirections des anciennes adresses du site actuel (bascule du domaine).
- `public/_headers` : masquage aux moteurs de recherche pendant l'essai.
