Défaut de la prime de proximité
===============================

La [latence](ch101-glossary.md#latence) est le temps nécessaire pour la [communication](ch101-glossary.md#communication). Les informations se déplacent à une vitesse inférieure à la [vitesse de la lumière](https://fr.wikipedia.org/wiki/Vitesse_de_la_lumi%C3%A8re) et, par conséquent, la latence ne peut pas être éliminée.

Les différences de distance entre les [mineurs](ch101-glossary.md#mineur) impliquent que les [annonces](ch101-glossary.md#annonce) seront connues de certains avant d'autres. Tant qu'un mineur demeure ignorant d'une annonce, il gaspille du capital à [hacher](ch101-glossary.md#hacheuse) à partir d'un [candidat](ch101-glossary.md#candidat) [faible](ch101-glossary.md#faible). À mesure que le temps passe, il devient exponentiellement moins probable que le mineur soit [récompensé](ch101-glossary.md#récompense) pour le candidat. Les mineurs se font donc concurrence pour voir les annonces avant les autres mineurs, car cela réduit le [coût d'opportunité](https://fr.wikipedia.org/wiki/Co%C3%BBt_d%27opportunit%C3%A9).

Si nous devions disperser des mineurs possédant un même [taux de hachage](ch101-glossary.md#taux-de-hachage) à des points équidistants autour de la Terre, ils subiraient la même latence moyenne. Pourtant, en raison de l'avantage financier que représente la réduction de la latence, ils auraient tendance à se rapprocher les uns des autres. Les mineurs obtiennent une prime sur les rendements grâce à l'[agrégation](ch101-glossary.md#agrégation).

Cette [pression de regroupement](ch039-pooling-pressure-risk.md) basée sur la proximité est une conséquence de l'ordre linéaire des [blocs](ch101-glossary.md#bloc) requis par les [règles de consensus](ch101-glossary.md#règles-de-consensus). **Bitcoin prescrit un ordre où tout va au vainqueur, ce qui produit un coût d'opportunité disproportionné.** La [remise de variance](ch037-variance-discount-flaw.md) est l'autre pression de regroupement causée par le [consensus](ch101-glossary.md#consensus).

La [défense](ch004-axiom-of-resistance.md) que Bitcoin *veut* mobiliser est la défense du [marché](ch101-glossary.md#marché) contre les forces ([étatiques](ch101-glossary.md#état)) hostiles au marché. Pour ce faire, la [puissance de hachage](ch101-glossary.md#puissance-de-hachage) doit être largement distribuée entre les [personnes](ch101-glossary.md#personne) afin qu'il devienne difficile de la [coopter](ch101-glossary.md#cooptation). Cependant, les pressions de regroupement inhérentes au [consensus](ch101-glossary.md#consensus) vont à l'encontre de cet objectif. De ce fait, la caractéristique est appelée un défaut, bien qu'aucun moyen d'éliminer ce défaut n'ait été découvert.

---

Texte original : [Proximity Premium Flaw](https://github.com/libbitcoin/libbitcoin-system/wiki/Proximity-Premium-Flaw)
