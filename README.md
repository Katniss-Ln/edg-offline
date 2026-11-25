# EDG Offline — version web installable

Version web autonome pour GitHub Pages. Les fiches, portraits, favoris, cartes de mémorisation et notes sont conservés dans le navigateur de l’iPhone ; le service worker met en cache l’application et le contenu pour la consultation hors connexion.

## Publication gratuite

1. Utiliser le dépôt public `Katniss-Ln/edg-offline` déjà créé.
2. Ajouter à sa branche `main` tous les fichiers de ce dossier, à la racine du dépôt.
3. Dans **Settings → Pages**, choisir **GitHub Actions** comme source.
4. Après la première exécution réussie, l’adresse sera `https://katniss-ln.github.io/edg-offline/`.
5. Sur l’iPhone, ouvrir cette adresse dans Safari, choisir **Partager → Ajouter à l’écran d’accueil** et activer **Ouvrir comme app web** si l’option apparaît.

> Le dépôt doit être public pour utiliser GitHub Pages avec l’offre gratuite. Les données personnelles de révision restent dans le navigateur et ne sont pas envoyées à GitHub. Exporter les données avant d’effacer Safari ou de changer d’appareil.

## Mise à jour des contenus

Chaque publication du fichier `data/briefs-actualite.json` remplace ou ajoute les briefs au prochain chargement. Pour mettre à jour les packs, conserver les identifiants des fiches et des cartes afin de garder les révisions associées.
