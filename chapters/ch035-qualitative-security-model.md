Modèle de sécurité qualitatif
=============================

**Modèle de décentralisation**

Dans le [Principe de réseau social](ch024-social-network-principle.md), il est montré que Bitcoin est un réseau de relations [humaines](ch101-glossary.md#personne). Il peut être modélisé sous la forme d'un [graphe orienté](https://fr.wikipedia.org/wiki/Graphe_orient%C3%A9) dans lequel chaque sommet représente un [commerçant](ch101-glossary.md#commerçant) et chaque arête représente un [échange](ch101-glossary.md#commerce) pour du bitcoin. Les arêtes indiquent la direction du mouvement de [monnaie](ch101-glossary.md#monnaie) et sont quantifiés en nombre d'[unités](ch101-glossary.md#unité) échangées. Tous les [propriétaires](ch101-glossary.md#propriétaire) sont présumés avoir été des commerçants au moment de la réception des pièces, y compris en tant que mineurs (vente de [confirmations](ch101-glossary.md#confirmation)) et en tant que bénéficiaires de charité (vente de [survaleur](https://fr.wikipedia.org/wiki/Goodwill)).

Si une personne n'accepte pas personnellement la monnaie ou ne [valide](ch101-glossary.md#validation) pas personnellement la monnaie acceptée, la personne ne peut pas rejeter la monnaie invalide. La personne confie cette tâche à une autorité centrale. **Toutes les personnes utilisant le même délégué sont réduites à un seul sommet qui représente le délégué.**

Pour une période de temps donnée, la sécurité [économique](ch101-glossary.md#économie) est fonction du nombre de commerçants et de la similitude des montants échangés. L'économie la plus forte serait celle dans laquelle tous les habitants du monde échangeraient le même nombre d'unités pendant la période, idéal que l'on peut appeler une économie « distribuée » (ou entièrement décentralisée). L'économie la plus faible serait celle dans laquelle un délégué accepterait toutes les unités échangées au cours de la période, ce qui serait une économie « centralisée ».

Plus précisément, le système le plus économiquement décentralisé est celui qui possède le plus grand nombre de sommets (commerçants) et le coefficient de [variation](https://fr.wikipedia.org/wiki/Coefficient_de_variation) le plus bas pour les arêtes entrantes (recettes). En définissant une fonction de distribution comme l'inverse du coefficient de variation, on obtient :

```
décentralisation-économique = distribution( recettes ) × commerçants
```

Similairement à la sécurité économique, la sécurité de confirmation peut être modélisée sous la forme d'un [graphe sans arête](https://fr.wikipedia.org/wiki/Graphe_nul). Chaque [mineur](ch101-glossary.md#mineur) est représenté par un sommet du graphe. Un [hacheur](ch101-glossary.md#hacheur) n'est pas un mineur car le hacheur n'a aucune capacité de décision, seul le mineur est représenté. La [puissance de hachage](ch101-glossary.md#puissance-de-hachage) totale employée par un mineur est le poids du sommet.

Pour une période de temps donnée, la sécurité de confirmation est fonction du nombre de mineurs et de la similitude de leur puissance de hachage dirigée. La résistance à la censure la plus forte serait celle où tous les habitants du monde mineraient à la même puissance de hachage pendant la période, idéal que l'on peut appeler la confirmation « distribuée » (ou entièrement décentralisée). La résistance à la censure la plus faible serait celle où un mineur posséderait 100 % de la puissance de hachage, ce qui serait une confirmation « centralisée ».

Plus précisément, le système le plus décentralisé dans la confirmation est celui qui possède le plus grand nombre de sommets (mineurs) et la distribution de poids la plus élevée (puissance de hachage) :

```
décentralisation-de-confirmation = distribution( puissance-de-hachage ) × mineurs
```

**Modèle de sécurité**

La [décentralisation](ch101-glossary.md#décentralisation) à elle seule n’est pas la sécurité. La sécurité est le produit de l'activité, de la distribution de cette activité et de la fraction de l'humanité participante.

```
sécurité = activité × distribution × participation
```

Étant donné qu'il n'y a pas de limite à l'humanité, au commerce ou au calcul, le niveau de sécurité sur chaque axe est illimité. La sécurité est également illimitée avec une distribution parfaite (c'est-à-dire une décentralisation infinie). Un niveau minimum de zéro sur chaque axe est atteint en l'absence de participation ou d'activité. La sécurité économique et la sécurité de confirmation peuvent ainsi être définies comme :

```
sécurité-économique      = recettes             × distribution( recettes )             × [ commerçants / humanité ]
sécurité-de-confirmation = puissance-de-hachage × distribution( puissance-de-hachage ) × [ mineurs     / humanité ]
```
**Limites du modèle**

Ces relations ne disent rien de l'efficacité absolue représentée par une valeur quelconque, ou de l'efficacité relative de deux valeurs quelconques, sauf le fait qu'une valeur plus élevée représente une plus grande efficacité. Ceci n'est pas dû à une insuffisance du modèle. Les facteurs incluent des personnes, et en particulier l'efficacité de leurs capacités individuelles à [résister](ch004-axiom-of-resistance.md) et leur perception de la [valeur](ch101-glossary.md#valeur) de la monnaie. Tous ceux qui valident ou minent offrent un certain niveau de résistance, mais il n'y a pas de continuité impliquée. On parle d'un « niveau » de sécurité et non d'une « quantité » de sécurité.

Comme le montre le [Principe des données publiques](ch023-public-data-principle.md), l'anonymat est un outil qui aide quelqu'un à défendre sa capacité à échanger et / ou à miner. De ce fait, le niveau de décentralisation ne peut jamais être mesuré ; le modèle est une aide conceptuelle. Comme montré dans le [Sophisme de l'équilibre des pouvoirs](ch042-balance-of-power-fallacy.md), les sécurités offertes par chacun des deux sous-modèles sont complémentaires et indépendantes l'une de l'autre. Alors que les gens pourraient décider d'échanger et / ou de miner indépendamment à l'avenir, le [Sophisme du cafard](ch045-cockroach-fallacy.md) montre qu'ils ne contribuent pas à la sécurité tant qu'ils ne le font pas. Le modèle représente la sécurité telle qu'elle existe durant la période.

---

Texte original : [Qualitative Security Model](https://github.com/libbitcoin/libbitcoin-system/wiki/Qualitative-Security-Model)