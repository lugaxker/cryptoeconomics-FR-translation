Sophisme de l'épuisement d'énergie
==================================

Il existe une théorie selon laquelle la [preuve de travail](ch101-glossary.md#preuve-de-travail) pourrait épuiser toute l'énergie à disposition des [gens](ch101-glossary.md#personne). La PDT convertit l'énergie en une barrière contre la [double dépense](ch101-glossary.md#double-dépense) qui [augmente de façon monotone](https://fr.wikipedia.org/wiki/Fonction_monotone) pour n'importe quelle [transaction](ch101-glossary.md#transaction) donnée. Ceci est comparable à l'énergie dépensée pour sécuriser n'importe quelle monnaie contre la contrefaçon (par son propre émetteur ou autre).

L'objectif de toute mesure de sécurité est de créer un coût nécessaire pour surmonter cette mesure, c'est-à-dire une barrière financière. Bitcoin crée sa barrière contre la double dépense en obligeant l'[attaquant](ch101-glossary.md#attaque) à remplacer la [branche](ch101-glossary.md#branche) de la transaction ciblée par une branche ayant un [travail](ch101-glossary.md#travail) probabiliste plus important. Il est intéressant de noter qu'un tel remplacement augmente la barrière pour les attaquants suivants. **L'énergie dépensée n'a pas d'importance indépendante, la barrière érigée représente la charge financière nécessaire de l'attaquant.**

La barrière de sécurité (S) d'un [bloc](ch101-glossary.md#bloc) est le produit du coût unitaire de [hachage](ch101-glossary.md#hachage) (C), du [taux de hachage](ch101-glossary.md#taux-de-hachage) (H) et de la [période](ch101-glossary.md#période) (T).

```
S = C * H * T
```

L'[ajustement](ch101-glossary.md#ajustement) fait varier le taux de hachage afin de maintenir une période constante pour un coût de hachage et une sécurité donnés.

```
T = S / (C * H)
```

Une période constante implique que le taux de hachage est inversement proportionnel au coût pour une sécurité donnée.

```
H ~ S / C
```

Lorsque l'offre d'énergie est réduite, son [prix](ch101-glossary.md#prix) doit augmenter, ce qui réduit la quantité dépensée pour un niveau de sécurité donné. Par conséquent, l'énergie ne peut pas être épuisée par le [minage](ch101-glossary.md#mine) et la théorie est invalide.

---

Texte original : [Energy Exhaustion Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Energy-Exhaustion-Fallacy)