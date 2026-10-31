# Le site de La Cour du Roy

Double-clique sur [accueil.html](./accueil.html) pour ouvrir le site dans ton navigateur. Aucune installation ni connexion Internet n'est nécessaire pour afficher la page.

## Les fichiers

- [accueil.html](./accueil.html) contient les titres, paragraphes, liens et sections.
- [apparence.css](./apparence.css) contient les couleurs, les espacements et la mise en page sur ordinateur et téléphone.
- [images/logo-club.png](./images/logo-club.png) est le logo fourni avec la maquette.
- Le dossier [maquette](./maquette/) contient les références extraites de l'archive originale.

## Comment modifier le site

1. Ouvre le fichier HTML dans ton éditeur et change le texte entre les balises, par exemple `<h1>Mon titre</h1>`.
2. Pour changer une couleur ou une taille, ouvre le fichier CSS. Les commentaires expliquent chaque groupe de règles.
3. Enregistre puis actualise le navigateur avec F5.

Une classe relie le HTML au CSS : `class="carte"` utilise les règles `.carte`. Un lien `href="#contact"` mène à la section portant `id="contact"`. Les règles `@media` adaptent la page aux petits écrans. Les questions se déplient avec les balises HTML `details` et `summary`, sans JavaScript.

## Limites à connaître

Le site utilise uniquement HTML et CSS, sans bibliothèque, sans JavaScript et sans serveur. Le formulaire est une démonstration : son bouton est volontairement désactivé et aucune information n'est envoyée. Pour recevoir les demandes, il faudra ajouter un service d'envoi et configurer son adresse dans l'attribut `action` du formulaire. Le téléphone permet déjà de contacter le club et le lien Google Maps ouvre l'itinéraire.

Les textes, dates d'actualités, horaires et coordonnées proviennent de la maquette : les faire confirmer par le club avant publication. Le site est enregistré localement, il n'est pas publié sur Internet. Les polices Georgia et Arial sont installées sur la plupart des ordinateurs pour éviter des téléchargements externes.
