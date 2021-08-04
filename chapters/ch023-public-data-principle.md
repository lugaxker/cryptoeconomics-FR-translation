Principe des données publiques
==============================

Il découle du [Principe du partage des risques](ch023-risk-sharing-principle.md) que la sécurité du système dépend du [minage](ch101-glossary.md#mine) et du [commerce](ch101-glossary.md#commerce) clandestins. Une [monnaie](ch101-glossary.md#monnaie) existe en tant que [marché](ch101-glossary.md#marché) [mutuellement avantageux](ch042-balance-of-power-fallacy.md) entre les [mineurs](ch101-glossary.md#mineur) et les [commerçants](ch101-glossary.md#commerçant) pour la [confirmation](ch101-glossary.md#confirmation) des [transactions](ch101-glossary.md#transaction) au sein de [blocs](ch101-glossary.md#bloc) en [échange](ch101-glossary.md#échange) de [frais](ch101-glossary.md#frais).

Les activités clandestines nécessaires sont répertoriées par rôle :

**Mineur**

* Obtenir des blocs [à partir desquels construire]
* Obtenir des transactions non confirmées [afin de percevoir leurs frais]
* Créer et distribuer des blocs [sur lesquels les autres seront incités à s'appuyer]
* Recevoir le paiement des confirmations [pour financer l'exploitation minière]

**Commerçant**

* Obtenir des blocs [pour valider le paiement du client]
* Obtenir des transactions non confirmées (facultatif) [pour anticiper les paiements et les frais]
* Créer et distribuer des transactions [pour obtenir le paiement du client]
* Effectuer le paiement des confirmations [pour indemniser la confirmation]

Si les blocs ne peuvent pas être obtenus de manière anonyme, le système n'est pas sécurisé. L'impossibilité d'obtenir les blocs les plus [forts](ch101-glossary.md#forte) disponibles pour d'autres [personnes](ch101-glossary.md#personne) est une [cloison](ch101-glossary.md#cloison) du réseau, qui implique une insécurité locale. Cependant, ni l'anonymat, ni son contraire, l'[identité](ch101-glossary.md#identité), ne peuvent garantir que l'on voie la [branche](ch101-glossary.md#branche) la plus forte à un moment donné. En d'autres termes, toute tentative d'atténuer le cloisonnement avec l'introduction de l'identité est un [faux choix](https://fr.wikipedia.org/wiki/Faux_dilemme) qui sacrifie la sécurité du système pour la fausse promesse d'assurer une sécurité locale.

Il n'est pas essentiel que tous les mineurs ou commerçants voient toutes les transactions à un moment donné. Cependant, une large visibilité est préférable car elle produit la concurrence la plus robuste pour les frais et pour les informations de premier plan.

En d'autres termes, un marché où chaque participant voit toutes les transactions en permanence est un [marché parfait](https://fr.wikipedia.org/wiki/Concurrence_pure_et_parfaite). Demander au réseau des transactions spécifiques, par opposition à toutes les transactions (ou des informations récapitulatives sur toutes les transactions), est une source de salissure et doit être aussi évitée dans l'intérêt de la sécurité.

La création de blocs et de transactions n'expose pas intrinsèquement l'identité, mais la distribution publique des uns ou des autres est la principale source de [salissure](ch101-glossary.md#salissure). Dans la mesure où les mineurs s'identifient ouvertement, ils s'appuient sur l'hypothèse d'un [environnement à faible menace](ch033-threat-level-paradox.md), et ne contribuent pas à la sécurité du système. Éviter les salissures lors de la diffusion de blocs et de transactions nécessite l'utilisation d'une [connexion](https://fr.wikipedia.org/wiki/Proxy_anonymiseur) anonyme à un [serveur](ch101-glossary.md#nœud) communautaire. Cela garantit que le réseau de distribution n'a jamais accès aux informations d'identification.

La [preuve de travail](ch101-glossary.md#preuve-de-travail) préserve l'anonymat des mineurs. Il n'y a pas de signature associée au minage et l'énergie est supposée être omniprésente. De même, la possibilité de payer de manière anonyme pour la confirmation est la raison de l'intégration des frais de transaction. Il est [suffisant](ch081-side-fee-fallacy.md) de payer directement un mineur (hors [chaîne](ch101-glossary.md#chaîne)) pour la confirmation, mais cela expose le commerçant et le mineur l'un à l'autre, et rend plus difficile l'estimation anonyme des frais.

La nouveauté de Bitcoin réside dans le fait que toutes les transactions financières peuvent être [validées](ch101-glossary.md#validation) à partir de données publiques et sans identité. Les systèmes financiers centralisés reposent soit sur la confiance dans les connexions (identifiables cryptographiquement) avec d'autres parties, soit sur la confiance dans les signatures (vérifiables cryptographiquement) présentes dans les données transmises. Telle est l'essence des systèmes fondés sur la confiance ; certaines autorités possèdent des secrets que d'autres utilisent pour vérifier cette authenticité. **La raison de la validation est d'éliminer l'utilisation de l'identité et donc de l'autorité.**

---

Texte original : [Public Data Principle](https://github.com/libbitcoin/libbitcoin-system/wiki/Public-Data-Principle)