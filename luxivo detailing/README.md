# Luxivo Detailing — Site vitrine + Dashboard Admin

Site vitrine (`index.html`) connecté en direct à Supabase : tout le contenu (packs, équipe, témoignages, partenaires, paramètres) est géré depuis le dashboard admin (`/admin`) et se met à jour automatiquement sur le site, sans redéploiement.

## Structure
- `index.html` — site vitrine public
- `admin/index.html` — dashboard admin (accès protégé par connexion Supabase Auth)
- `robots.txt` — bloque l'indexation de `/admin`

## Déploiement
Connecté à Vercel. Un `git push` sur la branche `main` déclenche un redéploiement automatique.

## Gestion du contenu
Tout le contenu éditorial (packs, équipe, témoignages, partenaires, numéro WhatsApp) se gère via `/admin`, pas en modifiant ce code.
  .
