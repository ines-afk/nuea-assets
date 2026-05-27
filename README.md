# Nuea Assets

CDN interne pour les assets publics de Nuea Agency.

## Contenu

- `signature/` — images de la signature email d'Inès (photo + logo)

## Hébergement

Déployé sur Cloudflare Pages, branche `main`, auto-deploy depuis ce repo.

URL : `https://nuea-assets.pages.dev/`

## Pourquoi ce repo

Les services d'hébergement d'images gratuits (ImgBB, Imgur) suppriment ou bloquent les images après quelques semaines. Ce repo garantit des URLs stables à vie pour la signature email et autres assets distribués.

## Ajouter un asset

1. Pose le fichier dans le bon sous-dossier
2. `git add . && git commit -m "add: nom du fichier" && git push`
3. Cloudflare deploy en ~30s
