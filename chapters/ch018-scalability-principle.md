Principe de scalabilité
=======================

La [scalabilité](https://fr.wikipedia.org/wiki/Extensibilit%C3%A9) est l'augmentation proportionnelle dans certains aspects de performance lorsque davantage de matériel informatique est utilisé. Le débit [transactionnel](ch101-glossary.md#transaction) de Bitcoin est parfaitement non scalable car aucune quantité de matériel ne l'augmente.

La [règle de consensus](ch101-glossary.md#règles-de-consensus) de la limite de taille des [blocs](ch101-glossary.md#bloc) établit le compromis arbitraire entre l'[utilité](ch101-glossary.md#utilité) et la sécurité du système. Une augmentation de la taille des blocs augmente légèrement le débit transactionnel et par conséquent le coût en ressources de la [validation](ch101-glossary.md#validation) des transactions (c'est-à-dire le traitement, le stockage et la bande passante). À mesure que le coût de la validation augmente, la sécurité [économique](ch101-glossary.md#économie) est affectée défavorablement par un [risque de centralisation](ch038-centralization-risk.md) accru. Puisque le compromis est arbitraire, il n'y a pas de taille idéale.

Quelle que soit la taille des blocs, le système reste non scalable en raison de la nécessité de la finalité des [confirmations](ch101-glossary.md#vconfirmation). Un ensemble fini de transactions doit être sélectionné, ce qui implique que d'autres peuvent être exclues. Cette exclusion est motivée financièrement par le [coût d'opportunité](https://fr.wikipedia.org/wiki/Co%C3%BBt_d%27opportunit%C3%A9) de la non-utilisation du capital [minier](ch101-glossary.md#mine) déployé et est la manifestation de la non-scalalibité. Cette limite intrinsèque nécessite un [marché](ch101-glossary.md#marché) concurrentiel pour la confirmation et elle le finance au prorata de la demande pour la [monnaie](ch005-money-taxonomy.md).

La capacité de transport effective des transactions, et donc l'utilité, peut être augmentée par le traitement en [surcouche](ch101-glossary.md#surcouche). Cela représente un compromis de sécurité *local* et *limité dans le temps*, contrairement au compromis de sécurité *systématique* et *persistant* de l'augmentation de la taille des blocs.

Les deux compromis abaissent le [seuil d'utilité](ch031-utility-threshold-property.md) mais ne l'éliminent pas, ce qui implique que la [propriété de stabilité](ch030-stability-property.md) est préservée.

**Par conséquent, la stabilité et la non-scalabilité existent pour n'importe quelle taille des blocs et pour n'importe quel niveau de traitement en surcouche.**

---

Texte original : [Scalability Principle](https://github.com/libbitcoin/libbitcoin-system/wiki/Scalability-Principle)