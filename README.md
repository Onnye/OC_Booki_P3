# OC_Booki_P3

## Transformez une maquette en site web avec HTML & CSS

### Booki - Trouvez votre hébergement pour des vacances de rêve

_(Projet 3 - Formation Integrateur Web - Openclassrooms)_

[![forthebadge](http://forthebadge.com/images/badges/uses-html.svg)](http://forthebadge.com) [![forthebadge](http://forthebadge.com/images/badges/uses-css.svg)](http://forthebadge.com)

## Scénario

Vous débutez votre **alternance en tant que développeur web** au sein de la start-up Booki. L’entreprise souhaite développer un site Internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix.

Vous êtes chargé **d'intégrer l'interface** du site avec du code **HTML et CSS**. Pour cela, vous travaillez en étroite collaboration avec Sarah, la CTO, et Loïc, l’UI designer.

Sarah vous envoie un e-mail pour vous présenter l’avancée du projet.

## Note de synthèse

Voici l’ensemble des points techniques et fonctionnels à prendre en
compte pour le développement du nouveau site Booki. L’ensemble de ces
éléments ont été validés par l’équipe Produit, il est donc important de les
respecter.

### Spécifications fonctionnelles

● Les usagers pourront rechercher des hébergements dans la ville de leur choix.
Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être
édité par l’utilisateur.
Il faut englober ce champ dans un formulaire. La partie Recherche ne doit pas
être fonctionnelle - il s’agit d’une première version pour valider l’interface.

● Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils
doivent mener respectivement vers la section “Hébergements à Marseille” et
“Activités à Marseille”.

● Chaque carte d’hébergement ou d’activité devra être cliquable dans son
intégralité (pas uniquement le titre).
Pour l’instant, les liens sont vides. On peut utiliser un attribut `href=”#”` pour
simuler la présence d’un lien.

● Les hébergements peuvent être filtrés par thématique, comme le budget ou
l’ambiance.
Les filtres doivent changer de couleur au survol de la souris.
Les filtres ne doivent pas être fonctionnels - il s’agit juste d’une première version
pour valider l’interface..

### Spécifications techniques

● Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer
une largeur maximum de 1440 px. Au-delà, une marge blanche doit apparaître sur les
côtés et le contenu doit se limiter à 1440 px de large.
Une largeur minimum doit être fixée à 1025 px. En-deçà de cette largeur des versions
tablette/mobile seront mises en place ultérieurement (ce n’est pas attendu dans cette
première version du site).

● Les icônes proviennent de la bibliothèque Font Awesome.

● Les couleurs de la charte sont le bleu (#0065FC), le bleu clair (#DEEBFF) et le gris pour le
fond (#F2F2F2).

● La police du site est Raleway. Nous pouvons passer par Google Fonts pour importer
facilement cette police dans le code : https://fonts.google.com/specimen/Raleway.

● Il est recommandé d'utiliser Flexbox.

● Il est important d’utiliser des balises sémantiques, au minimum “header”, “nav”,
“h1-h2-h3”, “main”, “section”, “article” et “footer”.

● Aucun IDE ou éditeur de code particulier n’est imposé pour le développement.
Le code doit être valide aux validateurs W3C HTML et CSS.
Le code HTML ne doit pas contenir de propriété CSS.
Privilégier l’utilisation des classes CSS pour cibler un élément, plutôt que d’utiliser
le nom de l’élément lui-même.
Ne pas dupliquer des classes CSS inutilement. Exemple : si 4 éléments sont
identiques du point de vue de la mise en forme, alors utiliser une seule et même
classe CSS, et non pas 4.

● La maquette doit être compatible avec les dernières versions de Google Chrome et de
Mozilla Firefox. Il faudra tester la page web sur ces deux navigateurs.

● Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
Aucun autre langage ne doit être utilisé (comme JavaScript, par exemple).

## Compétences évaluées

- Intégrer du contenu conformément à une maquette

- Implémenter une interface responsive

## Ressources utilisées

- [Validateur W3C](https://validator.w3.org/) - Outil pour vérifier que le code est conforme aux standards du Web.
- [Visual Studio Code](https://code.visualstudio.com/) - Editeur de codes

## Auteurs

- **Laura TUFO** _alias_ [@Onnye](https://github.com/Onnye)
