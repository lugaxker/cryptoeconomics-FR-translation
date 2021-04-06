Banque pure
===========

Le concept de banque pure peut être utile pour décrire le fonctionnement du [prêt](ch101-glossary.md#prêter) en général.

Une banque pure ne fournit que les services suivants :

* Elle emprunte de l'argent (dette des créanciers)
* Elle prête de l'argent (crédit des débiteurs)
* Elle stocke de l'argent (réserve)

Les différences essentielles par rapport à une banque réelle sont :

* Aucune intervention de l'État (banque libre)
* Aucun coût d'opération (parfaitement efficace)

La banque appartient à ses créanciers au prorata de leur crédit, comme pour toute société. Il existe de grandes banques qui appartiennent à leurs détenteurs de comptes, comme l'[USAA](https://www.usaa.com) et [Vanguard](https://investor.vanguard.com), ce n'est donc pas une distinction d'une banque réelle. Ni une banque pure ni une banque réelle n'a de « capital propre » à prêter, car tout le capital est emprunté aux investisseurs sous une forme ou une autre. L'objectif des créanciers est de maximiser leur taux de rendement. L'objectif des débiteurs est de minimiser leurs frais d'[intérêt](ch101-glossary.md#intérêt).

Les comptes des créanciers sont des [substituts monétaires](https://wiki.mises.org/wiki/Money_substitutes). Cet aspect distingue une banque d'un fonds d'investissement. Le substitut monétaire peut être soit un [dépôt à vue](https://fr.wikipedia.org/wiki/Compte_courant), soit un [marché monétaire](https://fr.wikipedia.org/wiki/March%C3%A9_mon%C3%A9taire). La distinction réside dans l'allocation de la réserve insuffisante (taux de rendement négatif), qui se base dans le premier cas sur le principe du « [premier arrivé, premier servi](https://fr.wikipedia.org/wiki/Panique_bancaire) » et dans le second sur le « [cassage du taux d'échange](https://en.wikipedia.org/wiki/Money_market_fund#Breaking_the_buck) ».

L'absence d'intervention étatique est le concept courant de la [banque libre](https://fr.wikipedia.org/wiki/Banque_libre), où il n'y a pas de [contrôle statutaire](https://fr.wikipedia.org/wiki/R%C3%A9serve_f%C3%A9d%C3%A9rale_des_%C3%89tats-Unis), d'[assurance publique](https://www.fdic.gov), de [capital au rabais](https://en.wikipedia.org/wiki/Discount_window) ou de [seigneuriage](https://fr.wikipedia.org/wiki/Seigneuriage). Sauf indication contraire, la banque utilise une [monnaie marchandise](ch005-money-taxonomy.md), ce qui simplifie les calculs en [éliminant](ch013-inflation-principle.md) la nécessité de contrebalancer l'[inflation](https://fr.wikipedia.org/wiki/Inflation) ou la [déflation des prix](https://fr.wikipedia.org/wiki/D%C3%A9flation).

L'efficacité parfaite ne diffère d'une banque réelle que par le taux de rendement, puisque rien n'est consommé dans la gestion. Tous les gains sont une conséquence de la [préférence temporelle](ch085-time-preference-fallacy.md). L'intérêt uniforme est supposé, car l'[arbitrage](https://fr.wikipedia.org/wiki/Arbitrage_(finance)) des taux est une dépense. Le [demeurage](https://fr.wikipedia.org/wiki/Demeurage_(finance)) est une dépense de stockage de la monnaie. Le ratio de dépenses (y compris le demeurage) est de 1 pour la banque pure.

Le capital [réservé](ch098-reserve-definition.md) est la monnaie avec laquelle les crédits et les dettes sont [réglés](https://fr.wikipedia.org/wiki/%C3%89change,_compensation_et_r%C3%A8glement) ([échéance](https://fr.wikipedia.org/wiki/%C3%89ch%C3%A9ance_(finance)) zéro). La [dépréciation](ch011-depreciation-principle.md) est le [coût d'opportunité](https://fr.wikipedia.org/wiki/Co%C3%BBt_d%27opportunit%C3%A9) pour ne pas être prêté, également connu sous le nom de « cash drag » ou retard de trésorerie. Les relations d'intérêt supposent une seule [période de composition](https://fr.wikipedia.org/wiki/Int%C3%A9r%C3%AAts_compos%C3%A9s) avec le taux d'intérêt pour cette période. Cette simplification de la présentation n'a aucune conséquence sur les relations impliquées.

Compte tenu de la définition précédente d'une banque pure, les relations suivantes sont absolues.

```
réservé      = emprunté - prêté
demeurage    = taux de demeurage * réservé
dépréciation = taux d'intérêt* réservé
intérêt      = taux d'intérêt * prêté
rendement    = ratio des dépenses * intérêts
```

Pour la banque pure, le [ratio de réserve](https://fr.wikipedia.org/wiki/R%C3%A9serves_obligatoires) détermine entièrement le [ratio de capital](https://en.wikipedia.org/wiki/Capital_requirement), le [ratio d'endettement](https://en.wikipedia.org/wiki/Debt_ratio) et le ratio d'épargne

#### Ratio de réserve

```
ratio de réserve = réservé / emprunté
ratio de réserve = (emprunté - prêté) / emprunté
```

#### Ratio de capital

```
ratio de capital = réservé / prêté
ratio de capital = (emprunté - prêté) / prêté
```

#### Ratio de dette

```
ratio d'endettement = emprunt / réservé
ratio d'endettement = emprunté / (emprunté - prêté)
```

#### Ratio d'épargne

```
> ratio d'épargne = prêt / réservé
> ratio d'épargne = prêté / (emprunté - prêté)
```

#### Bilan

La banque pure n'a pas de passif, seulement le capital propre des actionnaires.

|actifs bancaires  |capitaux propres   |
|------------------|-------------------|
|prêté + réservé   |emprunté           |

#### Taux de rendement

Le taux de rendement du créancier est en outre fonction du taux d'intérêt. Le taux de rendement du créancier est inférieur au taux d'intérêt du débiteur en raison du retard de trésorerie, la dépense nécessaire en demande de retrait. Pour réduire ces dépenses, des contraintes temporelles sont généralement incluses dans les [contrats de banques réelles](https://www.chase.com/content/dam/chasecom/en/checking/documents/deposit_account_agreement.pdf). Par exemple, en vertu de la loi, tout retrait d'un compte bancaire américain portant intérêt peut être retardé de sept jours. Le créancier ne peut éliminer le [retard de trésorerie](https://www.investopedia.com/terms/p/performance_drag.asp) qu'en l'investissant directement (c'est-à-dire sans garantie de règlement).

```
taux de rendement = taux d'intérêt * prêt/emprunté
```

Comme le montre la [Relation d'épargne](ch091-saving-relation.md), le ratio de capital est le taux d'intérêt. Le ratio de capital comprend la dépréciation des biens actuels, qui, pour l'argent, est le demeurage. Le demeurage de la banque pure est 1, donc on peut l'éliminer. En substituant le ratio de capital, on obtient un taux de rendement en matière de capital emprunté et prêté. 

```
taux de rendement = (réservé * ratio de demeurage / prêté) * (prêté / emprunté)
taux de rendement = (réservé / emprunté) * ratio de demeurage
taux de rendement = réservé / emprunté
```

**Le taux de rendement de l'investissement de la banque pure devient le ratio de réserve.**

#### Banques réelles

Les ratios de capital indépendants de toutes les personnes, basés sur la préférence temporelle individuelle, déterminent le taux d'intérêt du [marché](ch101-glossary.md#marché). La substitution ci-dessus du ratio de capital propre de la banque en tant que taux d'intérêt implique que la banque fixe le taux d'intérêt. Cependant, cela est propre au concept de préférence temporelle. Une banque peut définir le niveau d'intérêt qu'elle préfère. Il n'y a aucune hypothèse pour les banques réelles que le marché suivra, de sorte que l'intérêt du marché et, par conséquent, les rendements du marché sont présumés.

``` 
taux de rendement du marché = taux d'intérêt du marché * (prêts / empruntés)
taux de rendement du marché = ratio de capital du marché * (prêts / empruntés)
```

La banque libre diffère également de la banque pure par les dépenses opérationnelles, ce qui réduit directement le taux de rendement.

```
taux de rendement de la banque libre = taux de rendement sur le marché * ratio des dépenses
```

La banque réelle ne diffère que de la banque libre par l'impôt (y compris les dépenses réglementaires), ce qui réduit directement le taux de rendement.

```
taux de rendement réel = taux de rendement de la banque libre * ratio des dépenses fiscales
```

La banque centrale (l'État) ne diffère de la banque réelle que par la subvention par les contribuables (y compris les emprunts au rabais), ce qui augmente directement le taux de rendement.

```
taux de rendement de la banque centrale = taux de rendement bancaire * taux de rendement bancaire
```

Lorsque l'impôt comprend le seigneurage de la monnaie bancaire, l'[équation de Fisher](https://fr.wikipedia.org/wiki/%C3%89quation_de_Fisher) doit être appliquée ci-dessus pour convertir le taux d'intérêt d'un taux nominal à un taux réel. Aucun autre changement n'est impliqué en dehors de l'impôt, qui est comptabilisé par la banque réelle ci-dessus. Cet impôt est généralement la source de subvention, qui est comptabilisée par la banque centrale ci-dessus.

Chaque [personne](ch101-glossary.md#personne), ou société de personnes, est une banque réelle, et l'[État](ch101-glossary.md#état) est une banque centrale. Une banque réelle produit le service de l'investissement liquide, un [bien économique](https://fr.wikipedia.org/wiki/Bien_(%C3%A9conomie)). Le coût de production est la dépréciation de sa réserve. Cela est le modèle de toute production.

---

Texte original : [Pure Bank](https://github.com/libbitcoin/libbitcoin-system/wiki/Pure-Bank)
