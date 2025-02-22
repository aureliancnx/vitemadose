<a href="https://covidtracker.fr/vitemadose"><img src="./.github/assets/logo.png" width="150" alt="Vite Ma Dose !" /></a>

[Vite Ma Dose !](https://covidtracker.fr/vitemadose) est un outil open source de [CovidTracker](https://covidtracker.fr) permettant de détecter les rendez-vous disponibles dans votre département afin de vous faire vacciner (sous réserve d'éligibilité).

[![Contributeurs][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![Licence][license-shield]][license-url]
![Coverage][coverage-shield]

## Plateformes supportées

| Plateforme        | Lien           | Supporté  |
| ------------- |:-------------:| :-----:|
| <img src="https://www.ch2p.bzh/wp-content/uploads/2020/02/Logo-doctolib-bleu-tr.png" width="100" /> | https://doctolib.fr/ | <font style="color: green; font-size: 16px;">✓</font> |
| <img src="https://www.keldoc.com/keldoc-logo.nolqip.e7abaad88d1642c9c1f2.png" width="100" /> | https://keldoc.com | <font style="color: green; font-size: 16px;">✓</font> |
| <img src="https://www.rmingenierie.net/wp-content/uploads/2019/12/logo-Maiia-vert.png" width="100" /> | https://maiia.com | <font style="color: green; font-size: 16px;">✓</font> |
| <img src="https://www.ordoclic.fr/wp-content/uploads/2019/03/Logo.png" width="100" /> | https://ordoclic.fr | <font style="color: green; font-size: 16px;">✓</font> |

## Développement collaboratif

La [documentation](https://hackmd.io/YHcjKsUzQ1-cMomOUuTpXw) permet de centraliser les informations importantes relatives au développement de l'outil.

Ouvrez une [issue Github](https://github.com/CovidTrackerFr/vitemadose/issues/new) si vous souhaitez signaler un problème.
Pour signaler un problème : 

Pour proposer une modification ou un ajout sur l'outil de détection, ouvrez une [Pull Request](https://github.com/CovidTrackerFr/vitemadose/pulls).

## Utilisation

Installer les dépendances (À la racine de `vitemadose`) :

```bash
make install
```

Lancer le scraper :

```bash
make scrape
```

Générer des statistiques :

```bash
make stats
```

Lancer des tests unitaires :

```bash
make test
```

<!-- shield cards !-->
[contributors-shield]: https://img.shields.io/github/contributors/CovidTrackerFr/vitemadose.svg?style=for-the-badge
[contributors-url]: https://github.com/CovidTrackerFr/vitemadose/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/CovidTrackerFr/vitemadose.svg?style=for-the-badge
[forks-url]: https://github.com/CovidTrackerFr/vitemadose/network/members
[issues-shield]: https://img.shields.io/github/issues/CovidTrackerFr/vitemadose.svg?style=for-the-badge
[issues-url]: https://github.com/CovidTrackerFr/vitemadose/issues
[license-shield]: https://img.shields.io/github/license/CovidTrackerFr/vitemadose.svg?style=for-the-badge
[license-url]: https://github.com/CovidTrackerFr/vitemadose/blob/master/LICENSE
[coverage-shield]: https://raw.githubusercontent.com/CovidTrackerFr/vitemadose/data-auto/.github/coverage.svg
