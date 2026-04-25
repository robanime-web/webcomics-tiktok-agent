# Mission
Construire un système automatisé pour créer des TikTok carrousels à partir des œuvres WebComics autorisées par contrat.

# Utilisateur
L’utilisateur ne sait pas coder. Toute fonctionnalité doit être simple à lancer avec des boutons ou commandes documentées.

# Objectif produit
L’outil doit :
1. Rechercher des œuvres WebComics.
2. Récupérer les images autorisées.
3. Identifier les scènes les plus fortes.
4. Générer un script TikTok carrousel.
5. Associer une image à chaque slide.
6. Générer une description et des hashtags.
7. Exporter un dossier prêt à publier.
8. Plus tard : publier via TikTok API.

# Règles éditoriales
Audience TikTok française.
Style : action, dark, intense, masculin, tension dramatique.
Éviter romance légère, shojo, humour, ecchi.
Chaque TikTok doit viser la rétention.

# Format TikTok
Toujours produire :
- 6 slides
- texte court par slide
- visuel recommandé par slide
- description optimisée
- hashtags
- premier commentaire

# Règles légales
Le projet utilise uniquement WebComics, autorisé par contrat.
Ne pas utiliser d’autres plateformes sans autorisation.
Ne pas contourner de protections techniques.
Ne pas extraire de contenu payant sans accès autorisé.

# Stack technique
Backend : Python FastAPI
Scraping/navigation : Playwright
Base de données : SQLite au MVP, PostgreSQL plus tard
Frontend : React
Génération texte : OpenAI API
Export image : Pillow ou HTML-to-image
Automatisation : cron ou Celery plus tard

# Priorité MVP
Créer d’abord un outil local simple :
- entrer une URL WebComics
- extraire les images
- générer un script
- sélectionner 6 images
- exporter un dossier TikTok
