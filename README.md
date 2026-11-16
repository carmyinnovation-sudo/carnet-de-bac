# Carnet de bac 2027

Web app de révision pour la terminale (HGGSP, philosophie, grand oral), à installer sur l'écran d'accueil d'un téléphone.

- **Ce soir** : un plan de 45 minutes, le compte à rebours jusqu'au bac et la série de soirées réussies.
- **Réviser** : cartes mémoire avec répétition espacée, quiz, exercices type bac avec auto-correction guidée, « explique-le avec tes mots », minuteur et carnet d'erreurs.
- **Progrès** : temps de travail, temps TikTok déclaré, notes, erreurs par type et journal des séances.

## Comment ça marche

- La page est un fichier HTML autonome, hébergé par GitHub Pages, qui fonctionne aussi hors ligne.
- Les données sont stockées dans Supabase. Elles ne sont lisibles qu'avec la clé secrète contenue dans le lien personnel du carnet (`?k=…`), qui n'est pas dans ce dépôt.
- La clé Supabase présente dans le code est la clé publique du projet : elle ne donne accès à rien sans cette clé secrète.

Programme et dates : session 2027 (notes de service du 11 septembre 2026).
