Sophisme de l'auditabilité
==========================

La solvabilité d'un dépositaire de bitcoins ne peut être auditée. Un dépositaire custodial est une [personne](ch101-glossary.md#personne) ayant un pouvoir discrétionnaire à la fois sur la délivrance d'un actif et sur l'émission de titres en contrepartie de cet actif. Si la délivrance de l'actif et l'émission de titres en contrepartie sont contrôlées par des [règles de consensus](ch101-glossary.md#règles-de-consensus), alors la relation n'est pas réellement custodiale. C'est la distinction entre une [réserve](ch017-reservation-principle.md) et une [surcouche](ch101-glossary.md#surcouche). Une surcouche est imposée par un protocole (non custodiale) et ne requiert donc aucun audit.

**Un audit de solvabilité exige une preuve simultanée (atomique) du montant total de l'actif détenu par un dépositaire et des titres émis en contrepartie.** Dans le cas d'une réserve nationale de bitcoins, cela nécessiterait une preuve complète de tous les billets (par ex. le titre) émis en contrepartie de la réserve, ainsi que des bitcoins détenus en réserve. Même dans le cas où le titre est émis sur une [chaîne](ch101-glossary.md#chaîne) publique distincte, l'exigence d'atomicité n'est pas satisfaite.

Dans certains cas, il peut être considéré comme suffisant de renoncer à l'exigence d'atomicité, en acceptant l'inexactitude dans l'hypothèse où un écart substantiel finirait par être découvert. Cependant, dans le cas de la [banque d'État](ch077-reserve-currency-fallacy.md), détecter l'écart ne suffit pas. Historiquement, il n'a pas été difficile de détecter de telles écarts. La difficulté consiste à les faire cesser.

---

Texte original : [Auditability Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Auditability-Fallacy)