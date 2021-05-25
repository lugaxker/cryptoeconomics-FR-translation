Sophisme du bloc vide
=====================

Il existe une théorie selon laquelle le [minage](ch101-glossary.md#mine) de [blocs](ch101-glossary.md#bloc) vides constitue une [attaque](ch101-glossary.md#attaque). La théorie ne requiert pas que les blocs soient minés sur une [branche](ch101-glossary.md#branche) [faible](ch101-glossary.md#faible) pour tenter de permettre une [double dépense](ch101-glossary.md#double-dépense), ni ne spécifie quelle [personne](ch101-glossary.md#personne) est attaquée.

Considérerons ce qui suit :

* Le terme « attaque » sous-entend le vol. Le [livre blanc de Bitcoin](https://bitcoin.org/bitcoin.pdf), par exemple, n'utilise le terme que pour décrire les tentatives de double dépense.

* Une [récompense](ch101-glossary.md#récompense) se compose de [frais](ch101-glossary.md#frais) pour les [transactions](ch101-glossary.md#transaction) et d'une [subvention](ch101-glossary.md#subvention) pour le bloc. Le [mineur](ch101-glossary.md#mineur) qui renonce aux frais de transaction en n'incluant pas les transactions n'est pas récompensé pour celles-ci.

* La [puissance de hachage](ch101-glossary.md#puissance-de-hachage) du mineur contribue proportionnellement à la sécurité du réseau. La subvention est une compensation pour cette sécurité pendant la phase [inflationniste](ch101-glossary.md#inflation). Le but de l'inflation est de répartir rationnellement les [unités](ch101-glossary.md#unité). La distribution rationnelle se fait spécifiquement en [échange](ch101-glossary.md#échange) de puissance de hachage, pas de l'inclusion des transactions.

* La [confirmation](ch101-glossary.md#confirmation) des transactions n'est pas assurée. Les frais forment l'incitation à la confirmation. L'absence de confirmation implique objectivement des frais insuffisants.

* Le minage de blocs vides est entièrement conforme aux [règles de consensus](ch101-glossary.md#règles-de-consensus) et ne peut être raisonnablement empêché par une nouvelle [règle](ch101-glossary.md#règle).

En outre, si 10 % de la puissance de hachage mine des blocs vides, les confirmations prendront en moyenne 10 % plus longtemps. Pourtant, si un mineur supprime 10 % de la puissance de hachage totale, les confirmations prendront également 10 % plus longtemps en moyenne, jusqu'au prochain [ajustement](ch101-glossary.md#ajustement) de la [difficulté](ch101-glossary.md#difficulté). Le minage d'un bloc vide est par conséquent impossible à distinguer de l'absence de minage.

Il vaut la peine d'explorer la source du sophisme. En raison de la [Propriété de somme nulle](ch032-zero-sum-property.md), on peut supposer que le minage d'un bloc vide retire « injustement » l'opportunité de confirmation des transactions.

Un mineur engage des capitaux dans le minage, produisant de la puissance de hachage. En mettant à part les [effets du regroupement](ch039-pooling-pressure-risk.md), le mineur est subventionné proportionnellement au taux de hachage. Sans ce [travail](ch101-glossary.md#travail), d'autres mineurs produiraient le même nombre moyen de blocs à une difficulté proportionnellement plus faible. En d'autres termes, les attaques *réelles* seraient proportionnellement moins chères. Ainsi, bien qu'il n'ait pas été récompensé pour avoir inclus des transactions, le mineur de blocs vides sécurise les transactions précédemment confirmées.

Étant donné que le [coût marginal](https://fr.wikipedia.org/wiki/Co%C3%BBt_marginal) d'inclusion d'une transaction est nécessairement inférieur aux niveaux de frais moyens, le mineur de blocs vides subit un [coût d'opportunité](https://fr.wikipedia.org/wiki/Co%C3%BBt_d%27opportunit%C3%A9). Cela équivaut à une subvention de la sécurité de la [chaîne](ch101-glossary.md#chaîne) de la part du mineur.

Bien que ceci semble économiquement irrationnel, il peut en être autrement en raison du coût d'opportunité compensatoire d'attendre un nouveau [candidat](ch101-glossary.md#candidat) non vide après une [annonce](ch101-glossary.md#annonce). **Dans la mesure où il réduit les coûts des mineurs, le minage de blocs vides ne peut avoir aucun impact sur les frais ou sur le taux de confirmation.** La théorie est donc invalide.

Si un mineur donné peut considérer qu’il est avantageux de miner des blocs vides, il [appartient](ch101-glossary.md#pouvoir) à toute autre personne d'en faire autrement. À terme, c'est l'exercice de cette opportunité concurrentielle et intéressée qui sécurise la [monnaie](ch101-glossary.md#monnaie), contre les attaques réelles.

---

Texte original : [Empty Block Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Empty-Block-Fallacy)