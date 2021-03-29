Sophisme de la preuve d'enjeu
=============================

La sécurité des [confirmations](ch101-glossary.md#confirmation) requiert une autorité pour sélectionner les [transactions](ch101-glossary.md#transaction). Bitcoin confie périodiquement cette autorité au [mineur](ch101-glossary.md#mineur) qui produit la plus grande [preuve](ch101-glossary.md#preuve) de [travail](ch101-glossary.md#travail). Toutes les formes de travail [se ramènent nécessairement](ch070-proof-of-memory-fallacy.md) à la [consommation d’énergie](ch053-energy-waste-fallacy.md). Il est [essentiel](ch028-censorship-resistance-property.md) qu’une telle preuve soit indépendante de l’historique de la chaîne. Celle-ci peut être appelée la preuve « externe ».

L’unique autre source d’autorité sélective dépend par conséquent de l’historique de la chaîne, source qui peut être désignée comme « interne ». Il existe une théorie selon laquelle une telle [preuve d’enjeu](https://fr.wikipedia.org/wiki/Preuve_d%27enjeu) (PDE) constitue une alternative comparable à la [preuve de travail](ch101-glossary.md#preuve-de-travail) (PDT) en matière de sécurité des confirmations. Il est vrai que la PDE et la PDT délèguent toutes les deux le contrôle sur la sélection des transactions à une personne en charge de la plus grande réserve d’un certain capital.

La différence se situe dans la déployabilité du capital. La PDT exclut le capital qui ne peut pas être converti en travail, alors que la PDE exclut tout capital qui ne peut pas acquérir des [unités](ch101-glossary.md#unité) de la [monnaie](ch101-glossary.md#monnaie). Cette différence a une conséquence importante sur la sécurité.

Dans le [Principe des autres moyens](ch014-other-means-principle.md), il est montré que la résistance à la [censure](ch101-glossary.md#censure) dépend des personnes qui paient les mineurs pour [vaincre](ch101-glossary.md#puissance) le censeur. **Vaincre la censure n’est pas possible dans un système de PDE, puisque le censeur a acquis la part majoritaire et ne peut pas être évincé.** De ce fait, les systèmes de PDE ne sont pas résistants à la censure et la théorie est par conséquent invalide.

---

Texte original : [Proof of Stake Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Proof-of-Stake-Fallacy)