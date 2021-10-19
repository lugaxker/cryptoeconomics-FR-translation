Appellation impropre du spam
============================

Le terme de [spam](https://fr.wikipedia.org/wiki/Spam) en informatique faisait originellement référence à une publication croisée excessive sur Usenet et est devenu plus tard synonyme de diffusion de courrier électronique indésirable. Bien qu'il n'y ait pas de distinction claire entre les courriers électroniques désirables et indésirables, les messages portent une identité, ne sont pas fongibles et ne comportent pas de paiement pour le traitement par le destinataire. En comparaison, les transactions en bitcoins sont [nécessairement anonymes](ch016-risk-sharing-principle.md), fongibles et assorties d'un paiement pour leur traitement.

Bien que la détection de spam pour le courrier électronique soit un processus subjectif, elle est nécessaire en raison de l'absence de paiement pour le traitement. Ce processus est facilité par l'identité et l'absence de fongibilité. En revanche, en raison de l'anonymat et de l'objectif de fongibilité, il n'est pas possible d'analyser la légitimité des [transactions](ch101-glossary.md#transaction) et, grâce au paiement, il n'y en a pas besoin. En d'autres termes, **toutes les transactions valides sont pareillement légitimes**, et cela ne soumet pas les nœuds à un déni de service. Un nom approprié pour une transaction payant des [frais](ch101-glossary.md#frais) bas est : « transaction à bas frais ».

La soumission d'un volume élevé de transactions redondantes est un problème de déni de service typique qui est indépendant des frais de transaction et qui peut être effectué par n'importe quelle [personne](ch101-glossary.md#personne), sans être limité à celui qui [dépense](ch101-glossary.md#dépense). Les transactions non redondantes qui intègrent des dépenses contradictoires ne constituent pas un risque de déni de service, puisqu'elles sont soit rejetées comme invalides, soit acceptées en raison d'une augmentation des frais suffisante.

---

Texte original : [Spam Misnomer](https://github.com/libbitcoin/libbitcoin-system/wiki/Spam-Misnomer)