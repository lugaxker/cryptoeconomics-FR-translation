Propriété de somme nulle
========================

Le [minage](ch101-glossary.md#mine) de Bitcoin est un [jeu à somme nulle](https://fr.wikipedia.org/wiki/Jeu_%C3%A0_somme_nulle). En moyenne, la [chaîne](ch101-glossary.md#chaîne) augmente toutes les 10 minutes d'un [bloc](ch101-glossary.md#bloc), dont la [récompense](ch101-glossary.md#récompense) complète est contrôlée par son [mineur](ch101-glossary.md#mineur). Les mineurs se font concurrence pour obtenir cette récompense et, en excluant les [pressions de regroupement](ch039-pooling-pressure-risk.md), chacun d'entre eux obtient en moyenne un nombre de récompenses proportionnel à son [taux de hachage](ch101-glossary.md#taux-de-hachage). La différence entre le coût d’un mineur et cette récompense est au fil du temps l’[intérêt](ch101-glossary.md#intérêt) sur le capital [investi](ch101-glossary.md#prêter) dans la mine.

Il existe deux aspects de la propriété de somme nulle :

* Pendant la période entre les [coordinations](ch101-glossary.md#coordination), un mineur gagne une récompense et le reste des mineurs n'en gagne aucune. Ni le prix, ni le taux de hachage, ni la [difficulté](ch101-glossary.md#difficulté), ni l'[inflation](ch101-glossary.md#inflation), ni les [frais](ch101-glossary.md#frais), ni rien d'autre n'a d'effet sur cette propriété.

* L'ampleur des récompenses, caculée en [unités](ch101-glossary.md#unité) de [monnaie](ch101-glossary.md#monnaie) ou selon le [prix](ch101-glossary.md#prix) d'[échange](ch101-glossary.md#échange), n'a aucun effet sur le taux de rendement du capital. 

Le minage dans le Bitcoin idéalisé est un [système fermé](https://fr.wikipedia.org/wiki/Syst%C3%A8me_ferm%C3%A9). Le rendement du capital varie par rapport aux autres mines, en raison des défauts protocolaires de la [prime de proximité](ch036-proximity-premium-flaw.md) et de la [décote de variance](ch037-variance-discount-flaw.md), ainsi que de l'[économie d'échelle](https://fr.wikipedia.org/wiki/%C3%89conomie_d%27%C3%A9chelle) et de l'efficacité des exploitants. **Pourtant, comme ces facteurs n'ont d'incidence que sur le coût relatif de la puissance de hachage, seule la proportionnalité des taux de rendement est affectée, pas les rendements globaux.**

Le Bitcoin réel n'est pas un système fermé. La pression de regroupement du [marché](ch101-glossary.md#marché) et celle hostile au marché, qui sont respectivement la [variation](ch101-glossary.md#variation) et la [distorsion](ch101-glossary.md#distorsion), sont externes. Fondamentalement, Bitcoin existe pour défendre les marchés, opposant nécessairement la distorsion à la variation (ou leur absence).

Lorsqu'une distorsion est appliquée à un mineur dans ce système à somme nulle, tous les autres mineurs sont affectés. Par exemple, une [subvention](https://fr.wikipedia.org/wiki/Subvention) (à ne pas confondre avec la [subvention](ch101-glossary.md#subvention) du [consensus](ch101-glossary.md#consensus)) d'un mineur agit comme un taxe sur tous les autres, et une taxe sur un mineur agit comme une subvention de tous les autres. Le mineur subventionné fonctionne à un coût inférieur pour le même taux de hachage, ou possède un taux de hachage effectif (c'est-à-dire une [puissance de hachage](ch101-glossary.md#puissance-de-hachage)) plus élevé pour le même coût. Le mineur taxé fonctionne à un coût plus élevé pour le même taux de hachage, ou possède un taux de hachage effectif inférieur pour le même coût.

Un subventionneur n'attend aucun rendement de son capital, sinon il / elle serait considéré comme un investisseur. L'investissement est une force de marché par laquelle le mineur paie un prix de marché pour le capital. Avec un taux de rendement effectif plus élevé, le mineur subventionné attire plus de capitaux que les autres mineurs, continuant à étendre la puissance de hachage jusqu'à ce qu'il y ait un [mineur](ch101-glossary.md#mineur) possédant une [majorité du taux de hachage](ch101-glossary.md#puissance-de-hachage-majoritaire). L’objectif du subventionneur est à terme de *contrôler* la mine subventionnée.

Une taxe sur le minage a pour effet de déplacer la puissance de hachage vers des mines non taxées, hors de la portée de l'autorité fiscale, car le capital recherche les rendements du marché. Si elle est appliquée généralement, cela peut donner le contrôle à l'autorité par le biais de sa propre exploitation minière. En d'autres termes, l'autorité peut supprimer la concurrence. Cela peut également être accompli grâce à une taxe de 100 %, par laquelle l'autorité [coopte](ch101-glossary.md#cooptation) les mines. L'effet est le même, le mineur taxé est mis en faillite et le produit de la taxe est appliqué au contrôle.

Les conséquences du minage à somme nulle et de sa pression de regroupement inhérente sont explorées dans le [Paradoxe du niveau de menace](ch033-threat-level-paradox.md).

---

Texte original : [Zero Sum Property](https://github.com/libbitcoin/libbitcoin-system/wiki/Zero-Sum-Property)