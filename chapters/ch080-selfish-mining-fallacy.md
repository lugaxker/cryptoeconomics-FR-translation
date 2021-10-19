Sophisme du minage égoïste
==========================

L'expression « [minage](ch101-glossary.md#mine) [égoïste](ch101-glossary.md#égoïste) » fait référence à une *optimisation* du minage. Cependant, un [article universitaire](https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf) présente l'optimisation comme suit :

> La sagesse conventionnelle affirme que le protocole de minage respecte la compatilité des incitations et est sécurisé contre les groupes minoritaires en collusion, c'est-à-dire qu'il incite les mineurs à suivre le protocole tel qu'il est prescrit. Nous montrons que le protocole de minage de Bitcoin ne respecte pas la constrainte de compatilité des incitations.
>
> Ittay Eyal and Emin Gün Sirer, Majority is not Enough

Cette affirmation suppose un « protocole de minage de Bitcoin prescrit » qui exclut la [rétention](ch101-glossary.md#rétention), ce qui est un [homme de paille](https://fr.wikipedia.org/wiki/%C3%89pouvantail_(rh%C3%A9torique)). Les [règles de consensus](ch101-glossary.md#règles-de-consensus) de Bitcoin sont nécessairement silencieuses à propos du moment des [annonces](ch101-glossary.md#annonce).

> Nous présentons une attaque avec laquelle les mineurs en collusion obtiennent un revenu supérieur à leur juste part.

Cette affirmation suppose un concept de « juste part » qui est étranger à Bitcoin, ce qui est un autre homme de paille. Un [mineur](ch101-glossary.md#mineur) est [récompensé](ch101-glossary.md#récompense) en fonction des [blocs](ch101-glossary.md#bloc) qui arrivent à [maturité](ch101-glossary.md#maturité), et non en fonction du [taux de hachage](ch101-glossary.md#taux-de-hachage) réel.

Ces hommes de paille sont explicitement attribués à la « sagesse conventionnelle ». En d'autres termes, l'article les utilise pour montrer que la sagesse conventionnelle est incorrecte. Cependant, l'article se trompe en déclarant inconditionnellement que cette supposée *violation injuste du protocole* constitue une attaque :

> Cette attaque peut avoir des conséquences importantes pour Bitcoin : les mineurs rationnels préféreront rejoindre les mineurs égoïstes, et le groupe en collusion augmentera en taille jusqu'à devenir majoritaire. À ce stade, le système Bitcoin cesse d'être une monnaie décentralisée.

C'est la source du sophisme. Ce n'est pas une attaque que la sagesse conventionnelle soit incorrecte, c'est une erreur dans la sagesse conventionnelle présumée. Le minage égoïste implique que Bitcoin présente une [pression de regroupement](ch039-pooling-pressure-risk.md) basée sur la [latence](ch101-glossary.md#latence), bien qu'il s'agisse d'un [défaut avéré](ch036-proximity-premium-flaw.md). Toutes les pressions de regroupement tendent à réduire le nombre de mineurs, exposant ainsi Bitcoin à des attaques.

**Les optimisations ne sont pas des attaques.** Le regroupement augmente les *possibilités* d'attaque, mais il ne faut pas confondre possibilité et action. Le terme « [attaque](ch101-glossary.md#attaque) » implique le vol. En fait, le [livre blanc](https://bitcoin.org/bitcoin.pdf) de Bitcoin utilise ce terme uniquement pour décrire les tentatives de [double dépense](ch101-glossary.md#double-dépense).

---

Texte original : [Selfish Mining Fallacy](https://github.com/libbitcoin/libbitcoin-system/wiki/Selfish-Mining-Fallacy)