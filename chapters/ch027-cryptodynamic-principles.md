Principes cryptodynamiques
==========================

La cryptodynamique est un terme inventé ici dans le but de se référer facilement aux principes fondamentaux de [Bitcoin](ch101-glossary.md#bitcoin). Cela vise à la fois à cultiver la compréhension de Bitcoin et à le différencier des autres technologies. Les principes forment le sous-ensemble minimal des principes cryptoéconomiques nécessaires pour atteindre cet objectif.

Bien que le choix du nom ne soit pas trop important, une justification est fournie ci-dessous.

**Crypto**

« Une cryptomonnaie est une [monnaie] qui utilise la cryptographie forte pour sécuriser les transactions financières, contrôler la création des unités supplémentaires et vérifier le transfert de propriété de ces unités. » - [Wikipédia](https://en.m.wikipedia.org/wiki/Cryptocurrency)

**Dynamique**

« La dynamique [...] est une discipline de la mécanique classique qui étudie les corps en mouvement sous l'influence des actions mécaniques qui leur sont appliquées. » - [Wikipédia](https://fr.wikipedia.org/wiki/Dynamique_(m%C3%A9canique))

**Crypto + Dynamique**

La cryptodynamique est l'ensemble des forces qui sécurisent les [transactions](ch101-glossary.md#transaction) dans Bitcoin en contrôlant (1) la [définition](ch101-glossary.md#validité) des [unités](ch101-glossary.md#unité), et (2) le [transfert](ch101-glossary.md#transfert) des unités.

**Principes**

La force de sécurité est de nature entièrement humaine. Les [gens](ch101-glossary.md#personne) doivent agir pour sécuriser toute chose, y compris Bitcoin. En tant que système économique, la sécurité de Bitcoin ne peut seulement s'attendre à ce que les gens agissent de manière économiquement rationnelle (intérêt personnel). De ce fait, les forces de sécurité de Bitcoin sont entièrement basées sur les actions intéressées de personnes individuelles, plus précisément :

* [Le partage du risque](ch016-risk-sharing-principle.md)
* [La dissipation de l'énergie](ch072-proof-of-stake-fallacy.md)
* [La régulation de la puissance](ch028-censorship-resistance-property.md)

Ces forces dépendent les unes des autres dans cet ordre. Sans partage du risque, l'énergie ne peut pas être introduite dans le système pour réguler la [puissance](ch101-glossary.md#pouvoir) d'un censeur. Avec ces trois forces intactes, Bitcoin peut être sécurisé. Une technologie dépourvue de l'une d'entre elles n'est pas Bitcoin.

On ne [peut pas supposer](ch004-axiom-of-resistance.md) que, compte tenu de l'incorporation de ces forces, une implémentation de Bitcoin soit sécurisable. En outre, l'une peut l'être plus qu'une autre. **Une technologie est un Bitcoin seulement si elle incorpore ces forces ; sans elles, ce n'est plus le cas.**

La possibilité de sécurité offerte par ces forces peut être qualifiée de « sécurité cryptodynamique ». Ainsi, par exemple, une « blockchain permissionnée » viole le principe de partage du risque, une technologie de [preuve d'enjeu](ch101-glossary.md#preuve-d-enjeu) stricte viole le principe de dissipation de l'énergie, et une monnaie se reposant entièrement sur la [subvention](ch101-glossary.md#subvention) pour la compensation de confirmation viole le principe de régulation de la puissance. Aucun de ces systèmes n'est sécurisé sur le plan cryptodynamique.

---

Texte original : [Cryptodynamic Principles](https://github.com/libbitcoin/libbitcoin-system/wiki/Cryptodynamic-Principles)