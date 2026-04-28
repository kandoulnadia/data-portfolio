# À propos du fichier README d’un référentiel

Vous pouvez ajouter un fichier README à votre référentiel pour expliquer aux autres personnes pourquoi votre projet est utile, ce qu’elles peuvent faire avec votre projet et comment elles peuvent l’utiliser.

## À propos des README

Vous pouvez ajouter un fichier README à un référentiel pour communiquer des informations importantes sur votre projet. Un fichier README, ainsi qu’une licence de dépôt, fichier de citation, des recommandations de contribution et un code de conduite, pour communiquer les attentes de votre projet et vous aider à gérer les contributions.

Pour plus d’informations sur l’offre de recommandations pour votre projet, consultez [Ajouter un code de conduite à votre projet](/fr/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project) et [Configuration de votre projet pour des contributions saines](/fr/communities/setting-up-your-project-for-healthy-contributions).

Un README est souvent le premier élément qu’un visiteur verra lors de la consultation de votre référentiel. Les fichiers README incluent généralement des informations sur :

* Ce que le projet fait
* Pourquoi le projet est utile
* Prise en main du projet par les utilisateurs
* Où les utilisateurs peuvent obtenir de l’aide sur votre projet
* Qui maintient et contribue au projet

Si vous placez votre fichier README dans le répertoire `.github` caché, racine ou `docs` de votre référentiel, GitHub reconnaît et présente automatiquement votre fichier README pour les visiteurs du référentiel.

Si un référentiel contient plusieurs fichiers README, le fichier affiché est choisi parmi les emplacements suivants dans cet ordre : répertoire `.github`, puis répertoire racine du dépôt et enfin répertoire `docs`.

Lorsque votre fichier README est affiché sur GitHub, tout contenu au-delà de 500 Kio sera tronqué.

Si vous ajoutez un fichier LISEZMOI à la racine d’un référentiel public portant le même nom que votre nom d’utilisateur, ce fichier LISEZMOI apparaît automatiquement sur votre page de profil. Vous pouvez modifier votre fichier LISEZMOI avec GitHub Flavored Markdown pour créer une section personnalisée sur votre profil. Pour plus d’informations, consultez « [Gestion du README de votre profil](/fr/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme) ».

## Table des matières générée automatiquement pour les fichiers Markdown

Pour l’affichage rendu d’un fichier Markdown dans un référentiel, y compris les fichiers README, GitHub génère automatiquement une table des matières en fonction des titres de section. Vous pouvez afficher la table des matières d’un fichier README en cliquant sur l’icône de menu « Contour » <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-list-unordered" aria-label="Table des mati" role="img"><path d="M5.75 2.5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5ZM2 14a1 1 0 1 1 0-2 1 1 0 0 1 0 2Zm1-6a1 1 0 1 1-2 0 1 1 0 0 1 2 0ZM2 4a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg> dans le coin supérieur de la page rendue.

## Liens de section dans les fichiers Markdown et les pages blob

Vous pouvez créer un lien direct vers n’importe quelle section comportant un titre. Pour afficher l’ancre générée automatiquement dans un fichier rendu, survolez le titre de la section pour faire apparaître l’icône <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-link" aria-label="the link" role="img"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg> et cliquez sur l’icône pour afficher l’ancre dans votre navigateur.

![Capture d’écran d’un fichier README pour un référentiel. À gauche d'un titre de section, une icône de lien est indiquée en orange foncé.](/assets/images/help/repository/readme-links.png)

Pour des informations plus détaillées sur les liens de section, consultez [Liens de section](/fr/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links).

## Liens relatifs et chemins d’images dans les fichiers Markdown

Vous pouvez définir des liens et des chemins d’image relatifs dans vos fichiers affichés pour aider les lecteurs à accéder à d’autres fichiers de votre dépôt.

Un lien relatif est relatif par rapport au fichier actuel. Par exemple, si vous avez un fichier README à la racine de votre dépôt et que vous avez un autre fichier dans *docs/CONTRIBUTING.md*, le lien relatif vers *CONTRIBUTING.md* dans votre fichier README peut ressembler à ceci :

```text
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

GitHub transformera automatiquement votre lien relatif ou le chemin d'accès à l'image en fonction de la branche sur laquelle vous vous trouvez actuellement, de sorte que le lien ou le chemin d'accès fonctionne toujours. Le chemin du lien sera relatif au fichier actif. Les liens commençant par `/` seront relatifs à la racine du dépôt. Vous pouvez utiliser tous les opérandes de lien relatif, comme `./` et `../`.

Votre texte de lien doit se trouver sur une seule ligne. L’exemple ci-dessous ne fonctionnera pas.

```markdown
[Contribution
guidelines for this project](docs/CONTRIBUTING.md)
```

Les liens relatifs sont plus pratiques pour les utilisateurs qui clonent votre dépôt. Les liens absolus peuvent ne pas fonctionner dans les clones de votre dépôt. Nous vous recommandons d’utiliser des liens relatifs pour référencer d’autres fichiers au sein de votre dépôt.

## Wikis

Un README ne doit contenir que les informations nécessaires pour permettre aux développeurs de démarrer et de contribuer à votre projet. Les documentations plus longues sont mieux adaptées aux wikis. Pour plus d’informations, consultez « [À propos des wikis](/fr/communities/documenting-your-project-with-wikis/about-wikis) ».

## Pour aller plus loin

* [Ajout d’un fichier à un référentiel](/fr/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
* [5 conseils pour rendre votre page de profil GitHub accessible](https://github.blog/2023-10-26-5-tips-for-making-your-github-profile-page-accessible/) sur le blog GitHub
* [Faciliter la création et la reprise rapides de codespaces](/fr/codespaces/setting-up-your-project-for-codespaces/setting-up-your-repository/adding-a-codespaces-badge)# data-portfolio
