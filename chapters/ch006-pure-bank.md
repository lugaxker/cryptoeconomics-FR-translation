Banque Pure
===========

Le concept de Banque Pure peut être utile pour décrire le fonctionnement du [prêt](ch101-glossary.md#prêter) en général.

Une Banque Pure ne fournit que les services suivants :

* Elle emprunte de l'argent (dette des créanciers)
* Elle prête de l'argent (crédit des débiteurs)
* Elle stocke de l'argent (réserve)

Les différences essentielles par rapport à une banque réelle sont :

* Aucune intervention de l'État (banque libre)
* Aucun coût de fonctionnement (parfaitement efficace)

La banque appartient à ses créanciers au prorata de leur crédit, comme pour toute société. Il existe de grandes banques qui appartiennent à leurs détenteurs de comptes, comme l'[USAA](https://www.usaa.com) et [Vanguard](https://investor.vanguard.com), ce n'est donc pas un critère distinctif d'une banque réelle. Ni une Banque Pure ni une banque réelle n'a de « capital propre » à prêter, car tout le capital est emprunté aux investisseurs sous une forme ou une autre. L'objectif des créanciers est de maximiser leur taux de rendement. L'objectif des débiteurs est de minimiser leurs frais d'[intérêt](ch101-glossary.md#intérêt).

Les comptes des créanciers sont des [substituts monétaires](https://wiki.mises.org/wiki/Money_substitutes). Cet aspect distingue une banque d'un fonds d'investissement. Le substitut monétaire peut être soit un [dépôt à vue](https://fr.wikipedia.org/wiki/Compte_courant), soit un [fonds monétaire](https://en.wikipedia.org/wiki/Money_market_fund). La distinction réside dans l'allocation de la réserve insuffisante (taux de rendement négatif), qui se base dans le premier cas sur le principe du « [premier arrivé, premier servi](https://fr.wikipedia.org/wiki/Panique_bancaire) » et dans le second sur la « [fracture de parité](https://en.wikipedia.org/wiki/Money_market_fund#Breaking_the_buck) » (*breaking the buck*).

L'absence d'intervention étatique est le concept courant de [banque libre](https://fr.wikipedia.org/wiki/Banque_libre), où il n'y a pas de [contrôle statutaire](https://fr.wikipedia.org/wiki/R%C3%A9serve_f%C3%A9d%C3%A9rale_des_%C3%89tats-Unis), d'[assurance publique](https://www.fdic.gov), de [taux d'escompte](https://en.wikipedia.org/wiki/Discount_window) ou de [seigneuriage](https://fr.wikipedia.org/wiki/Seigneuriage). Sauf indication contraire, la banque utilise une [monnaie-marchandise](ch005-money-taxonomy.md), ce qui simplifie les calculs en [éliminant](ch013-inflation-principle.md) la nécessité de tenir compte de l'[inflation](https://fr.wikipedia.org/wiki/Inflation) ou de la [déflation des prix](https://fr.wikipedia.org/wiki/D%C3%A9flation).

L'efficacité parfaite ne diffère d'une banque réelle que par le taux de rendement, puisque rien n'est consommé dans la gestion. Tous les gains sont une conséquence de la [préférence temporelle](ch085-time-preference-fallacy.md). L'intérêt uniforme est supposé, car l'[arbitrage](https://fr.wikipedia.org/wiki/Arbitrage_(finance)) entre les taux est une dépense. Le [demeurage](https://fr.wikipedia.org/wiki/Demeurage_(finance)) est une dépense de stockage de la monnaie. Le ratio de dépenses (y compris le demeurage) est de 1 pour la Banque Pure.

Le capital [réservé](ch098-reserve-definition.md) est la monnaie avec laquelle les crédits et les dettes sont [réglés](https://fr.wikipedia.org/wiki/%C3%89change,_compensation_et_r%C3%A8glement) ([échéance](https://fr.wikipedia.org/wiki/%C3%89ch%C3%A9ance_(finance)) zéro). La [dépréciation](ch011-depreciation-principle.md) est le [coût d'opportunité](https://fr.wikipedia.org/wiki/Co%C3%BBt_d%27opportunit%C3%A9) du fait de ne pas prêter cet argent, également connu sous le nom de « *cash drag* » ou délai de trésorerie. Les relations d'intérêt supposent une seule [période de composition](https://fr.wikipedia.org/wiki/Int%C3%A9r%C3%AAts_compos%C3%A9s) avec le taux d'intérêt pour cette période. Cette simplification de la présentation n'a aucune conséquence sur les relations impliquées.

Compte tenu de la définition précédente d'une Banque Pure, les relations suivantes sont absolues.

```
réservé      = emprunté - prêté
demeurage    = taux de demeurage * réservé
dépréciation = taux d'intérêt * réservé
intérêt      = taux d'intérêt * prêté
rendement    = ratio des dépenses * intérêts
```

Pour la Banque Pure, le [ratio de réserve](https://fr.wikipedia.org/wiki/R%C3%A9serves_obligatoires) détermine entièrement le [ratio de capital](https://en.wikipedia.org/wiki/Capital_requirement), le [ratio d'endettement](https://en.wikipedia.org/wiki/Debt_ratio) et le ratio d'épargne.

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

#### Ratio d'endettement

```
ratio d'endettement = emprunté / réservé
ratio d'endettement = emprunté / (emprunté - prêté)
```

#### Ratio d'épargne

```
ratio d'épargne = prêté / réservé
ratio d'épargne = prêté / (emprunté - prêté)
```

#### Bilan

La Banque Pure n'a pas de passif, seulement le capital propre des actionnaires.

|actifs bancaires  |capitaux propres   |
|------------------|-------------------|
|prêté + réservé   |emprunté           |

#### Taux de rendement

Le taux de rendement du créancier est en outre fonction du taux d'intérêt. Le taux de rendement du créancier est inférieur au taux d'intérêt du débiteur en raison du délai de trésorerie, la dépense nécessaire en demande de retrait. Pour réduire ces dépenses, des contraintes temporelles sont généralement incluses dans les [contrats de banques réelles](https://www.chase.com/content/dam/chasecom/en/checking/documents/deposit_account_agreement.pdf). Par exemple, en vertu de la loi s'appliquant aux États-Unis, tout retrait d'un compte bancaire portant intérêt peut être retardé de sept jours. Le créancier ne peut éliminer le [délai de trésorerie](https://www.investopedia.com/terms/p/performance_drag.asp) qu'en l'investissant directement (c'est-à-dire sans garantie de règlement).

```
taux de rendement = taux d'intérêt * prêté / emprunté
```

Comme le montre la [Relation d'épargne](ch091-saving-relation.md), les ratios de capital individuels déterminent entièrement le taux d'intérêt du [marché](ch101-glossary.md#marché). Lorsque nous considérons chaque personne opérant comme une banque pure, il devient clair que le ratio de capital détermine le taux d'intérêt. Un ratio de capital de 0 % pour toutes les personnes implique que le capital est gratuit et n'a pas de rendement. À des ratios de capital croissants, le taux d'intérêt augmente en conséquence. À un niveau de thésaurisation totale, le coût du capital est « infini » - aucune quantité de capital ne peut être obtenue pour la production.

La supposition de la [relation monétaire](ch013-inflation-principle.md) est que le prix est proportionnel au rapport de l'offre à la demande. Mais comme le montre la Relation d'épargne, l'offre et la demande de capital existent dans une relation à somme nulle. Une augmentation de la [thésaurisation](ch101-glossary.md#thésauriser) implique une diminution correspondante des prêts et l'inverse implique une augmentation. De ce fait, ni le ratio de capital ni le taux d'intérêt ne sont linéaires par rapport à l'évolution du montant thésaurisé (ou prêté). Cela a conduit certains à rechercher une « [règle d'or](https://fr.wikipedia.org/wiki/R%C3%A8gle_d%27or_de_l%27accumulation) », un ratio idéal. Pourtant, étant donnée la subjectivité de la valeur, il s'agit en fin de compte d'un exercice futile.

Pourtant, les ratios de capital déterminent pleinement le taux d'intérêt. Comme chaque personne tente individuellement d'obtenir un ratio idéal basé sur ses propres préférences, un taux d'intérêt du marché en résulte. La substitution du ratio de capital au taux d'intérêt démontre l'effet de la réserve sur la Banque Pure, sous l'hypothèse supplémentaire que tout le monde fonctionne comme une Banque Pure et avec le même ratio de capital. Le ratio de capital comprend la dépréciation des biens présents, ce qui, pour la monnaie, est le demeurage. Le ratio de demeurage de la Banque Pure est de 1, donc on peut l'éliminer.

```
taux de rendement = ( réservé * ratio de demeurage / prêté ) * (prêté / emprunté)
taux de rendement = ( réservé / emprunté ) * ratio de demeurage
taux de rendement = réservé / emprunté
```

Le taux de rendement de l'investissement de la Banque Pure devient le ratio de réserve. Cela n'implique pas qu'une Banque Pure individuelle puisse définir son propre rendement en fixant son ratio de capital. Cela reflète simplement que le ratio de capital du marché détermine le rendement du capital. Si *tous les prêteurs* doublaient leur ratio de capital actuel, leurs rendements doubleraient nécessairement, car le coût du capital, et donc son rendement, doublerait.

#### Banques réelles

Les ratios de capital indépendants de toutes les personnes, basés sur la préférence temporelle individuelle, déterminent le taux d'intérêt du marché. La substitution ci-dessus du ratio de capital propre de la banque en tant que taux d'intérêt implique que la banque fixe le taux d'intérêt. Cependant, cela est propre au concept de préférence temporelle. Une banque peut définir le niveau d'intérêt qu'elle préfère. Il n'y a aucune hypothèse pour les banques réelles que le marché suivra, de sorte que l'intérêt du marché et, par conséquent, les rendements du marché sont présumés.

``` 
taux de rendement du marché = taux d'intérêt du marché * ( prêté / emprunté )
taux de rendement du marché = ratio de capital du marché * ( prêté / emprunté )
```

La Banque Libre diffère également de la Banque Pure par les dépenses de fonctionnement, ce qui réduit directement le taux de rendement.

```
taux de rendement de la banque libre = taux de rendement sur le marché * ratio des dépenses
```

La Banque Réelle ne diffère de la banque libre que par l'impôt (y compris les dépenses réglementaires), ce qui réduit directement le taux de rendement.

```
taux de rendement réel = taux de rendement de la banque libre * ratio des dépenses fiscales
```

La Banque Centrale (l'État) ne diffère de la banque réelle que par la subvention par les contribuables (y compris les emprunts aux taux directeurs), ce qui augmente directement le taux de rendement.

```
taux de rendement de la banque centrale = taux de rendement bancaire * taux de rendement bancaire
```

Lorsque l'impôt comprend le seigneuriage de la monnaie bancaire, l'[équation de Fisher](https://fr.wikipedia.org/wiki/%C3%89quation_de_Fisher) doit être appliquée ci-dessus pour convertir le taux d'intérêt d'un taux nominal à un taux réel. Aucun autre changement n'est impliqué en dehors de l'impôt, qui est comptabilisé par la Banque Réelle ci-dessus. Cet impôt est généralement la source de subvention, qui est comptabilisée par la Banque Centrale ci-dessus.

Chaque [personne](ch101-glossary.md#personne), ou société de personnes, est une Banque Réelle, et l'[État](ch101-glossary.md#état) est une Banque Centrale. Une Banque Réelle produit le service de l'investissement liquide, un [bien économique](https://fr.wikipedia.org/wiki/Bien_(%C3%A9conomie)). Le coût de production est la dépréciation de sa réserve. Cela est le modèle de toute production.

---

Texte original : [Pure Bank](https://github.com/libbitcoin/libbitcoin-system/wiki/Pure-Bank)
