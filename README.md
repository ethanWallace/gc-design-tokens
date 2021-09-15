[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v1.4%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)

# GC Design Token Experimental Working Space

([Français](#espace-de-travail-experimental-sur-les-jetons-de-conceptions-du-gouvernement-canadien))

A repository set as the experimental space for design tokens that should inform the GC Design System Product Team. We will primarily explore the naming convention of design tokens through the use of tools like:
* [Style Dictionary](https://amzn.github.io/style-dictionary)
* [Diez](https://diez.org/)
* [Theo](https://github.com/salesforce-ux/theo)

### How to Contribute

This project was created with [Diez](https://diez.org).

#### What's in the box

The `design-language` directory contains a Diez design language project. It is the living source of truth for your design language.

The `example-codebases` directory contains example projects connected to your Diez project. Note that the example apps are only present for demonstration purposes, and can be safely removed.

```
.
├── design-language
|   └── src
|       ├── index.ts
|       └── DesignLanguage.ts
└── example-codebases
    ├── android
    ├── ios
    └── web
```

#### Quickstart

To quickly experience how Diez works, simply run `yarn demo` or `npm run demo` from `design-language`. This command will use Diez to compile a JavaScript SDK for your design language and link it to the example web project located in `codebases/web`, then start the example web project in your browser.

Check out our [Getting Started guide](https://diez.org/getting-started/) to learn more.

See [CONTRIBUTING.md](CONTRIBUTING.md)

### License

Unless otherwise noted, the source code of this project is covered under Crown Copyright, Government of Canada, and is distributed under the [MIT License](LICENSE).

The Canada wordmark and related graphics associated with this distribution are protected under trademark law and copyright law. No permission is granted to use them outside the parameters of the Government of Canada's corporate identity program. For more information, see [Federal identity requirements](https://www.canada.ca/en/treasury-board-secretariat/topics/government-communications/federal-identity-requirements.html).
______________________

[![Pacte des contributeurs](https://img.shields.io/badge/Pacte%20des%20contributeurs-v1.4%20adoptée-ff69b4.svg)](CODE_OF_CONDUCT.md)

# Espace de travail expérimental sur les jetons de conceptions du gouvernement canadien

([English](#gc-design-token-experimental-working-space))

Un dépôt de code défini comme l'espace de travail expérimental pour les jetons de conception qui devrait informer l'Équipe de produit du système de conception GC. Nous explorerons principalement la convention de nommage des jetons de conception à l'aide d'outils tels que&nbsp;:
* [Style Dictionary](https://amzn.github.io/style-dictionary)
* [Diez](https://diez.org/)
* [Theo](https://github.com/salesforce-ux/theo)

### Comment contribuer

Voir [CONTRIBUTING.md](CONTRIBUTING.md)

### Licence

Sauf indication contraire, le code source de ce projet est protégé par le droit d'auteur de la Couronne du gouvernement du Canada et distribué sous la [licence MIT](LICENSE).

Le mot-symbole « Canada » et les éléments graphiques connexes liés à cette distribution sont protégés en vertu des lois portant sur les marques de commerce et le droit d'auteur. Aucune autorisation n'est accordée pour leur utilisation à l'extérieur des paramètres du programme de coordination de l'image de marque du gouvernement du Canada. Pour obtenir davantage de renseignements à ce sujet, veuillez consulter les [Exigences pour l'image de marque](https://www.canada.ca/fr/secretariat-conseil-tresor/sujets/communications-gouvernementales/exigences-image-marque.html).