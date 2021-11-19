# Lexique

## Fondamentaux

#### Personne
Un décideur.

#### Machine
Un suiveur d'instructions.

## Accord

#### Bitcoin
Ensemble des principes qui sécurisent une [Monnaie](#monnaie) contre l'[État](état). Le terme et les principes sont définis par Satoshi dans « Bitcoin: A Peer-to-Peer Electronic Cash System ».

#### Consensus
Accord entre les [Personnes](#personne). Aussi, l'ensemble des gens qui participent à un accord.

#### Monnaie
[Consensus](#consensus) concernant un moyen mutuellement acceptable pour le [Commerce](#commerce). BTC est une Monnaie. On emploie également les termes « cryptomonnaie » et « *coin* ».

#### Règles de consensus
Ensemble de contraintes qui définissent une [Monnaie](#monnaie).

#### Règle
Sous-ensemble des [Règles de consensus](#règles-de-consensus).

#### Validité
Conformité aux [Règles de consensus](#règles-de-consensus).

#### Validation
Procédure pour déterminer la [Validité](#validité).

#### Application
Acte de rejeter une donnée [Invalide](#validité).

## Objets

#### Unité
Montant minimal [Transférable](#transfert) de biens représentés par une [Monnaie](#monnaie). Le satoshi est l'unité de Bitcoin.

#### Transfert
Modification du contrôle sur certaines [Unités](#unité).

#### Transaction
Trace écrite [Valide](#validité) d'un [Transfert](#transfert).

#### Bloc
Ensemble [Valide](#validité) de [Transactions](#transaction) avec un [Horodatage](#horodatage) et une [Preuve](#preuve).

#### Chaîne
La [Branche](#branche) ayant le plus de [Preuve](#preuve) cumulée.

## Transactions

#### Script
Ensemble d'[Opérations](#opération) autorisant un [Transfert](#transfert).

#### Opération
Déclaration d'intention insécable.

#### Contrat
[Script](#script) qui exprime des conditions de [Transfert](#transfert). Parfois désigné par l'expression anachronique « script de clé publique ».

#### Approbation
[Script](#script) qui satisfait un [Contrat](#contrat). Parfois désignée par l'expression anachronique « script de signature ».

#### Point
Référence à une [Sortie](#sortie) ou une [Entrée](#entrée).

#### Sortie
Un [Transfert](#transfert) explicite et un [Contract](#contrat).

#### Entrée
Un [Point](#point) de [Sortie](#sortie) et une [Approbation](#approbation).

#### Sortie précédente
[Sortie](#sortie) à laquelle se réfère une [Entrée](#entrée).

#### Temps de verrouillage
Expression de la plus ancienne [Validité](#validité) de la [Transaction](#transaction).

#### Poussière
Nombre insuffisant d'[Unités](#unité) pour le [Transfert](#transfert) par une [Sortie](#sortie). Les [Règles de consensus](#règles-de-consensus) de BTC interdisent le transfert de moins d'une unité.

## Blocs

#### Horodatage
Déclaration du temps de la production du [Bloc](#bloc).

#### Temps passé médian
Moyenne des [Horodatages](#horodatage) des précédents [Blocs](#bloc).

#### Preuve
Marque [Valide](#validité).

#### Preuve de travail
[Preuve](#preuve) probabilistique d'une quantité de [Travail](#travail) effectuée (PDT).

#### Preuve de mémoire
[Preuve](#preuve) probabilistique d'une quantité de mémoire informatique utilisable (PDM).

#### Preuve d'enjeu
[Preuve](#preuve) cryptographique d'une quantité de [Propriété](#propriétaire) (PDE)

#### Branche
Séquence [Valide](#validité) de [Blocs](#bloc).

#### Faible
Une [Branche](#branche) ayant moins de [Preuve](#preuve) cumulée qu'une autre. Aussi appelée « orpheline » par abus de langage.

#### Forte
Une [Branche](#branche) ayant plus de [Preuve](#preuve) cumulée qu'une autre.

## Enchaînement

#### Confirmation
Inclusion d'une [Transaction](#transaction) dans un [Bloc](#bloc).

#### Non confirmée
Une [Transaction](#transaction) qui n'existe pas dans un [Bloc](#bloc) de la [Chaîne](#chaîne).

#### Réserve des transactions
Ensemble des [Transactions](#transaction) [Non confirmées](#non-confirmée). Aussi appelée « zone mémoire » par abus de langage.

#### Réserve des blocs
Ensemble des [Blocs](#bloc) [Faibles](#faible). Aussi appelée « réserve des orphelins » par abus de langage.

#### Genèse
Premier [Bloc](#bloc) de toutes les [Branches](#branche) d'une [Monnaie](#monnaie).

#### Profondeur
1 plus le nombre de [Blocs](#bloc) après une [Confirmation](#confirmation).

#### Hauteur
Nombre de [Blocs](#bloc) précédents dans une [Branche](#branche).

#### Segment
Sous-ensemble contigu d'une [Branche](#branche).

#### Coordination
[Annonce](#annonce) ajoutant un [Bloc](#bloc) à la [Chaîne](#chaîne).

#### Période
Temps moyen entre les [Coordinations](#coordination).

#### Surcouche
[Commerce](#commerce) utilisant une série de [Transactions](#transaction) [Non confirmées](#non-confirmée) qui peuvent être [Réglées](#règlement) par l'une ou l'autre des parties. 

#### Règlement
[Confirmation](#confirmation) des [Transactions](#transaction) en [Surcouche](#surcouche).

## Monnaie

#### Dépense
Publication initiale d'une [Transaction](#transaction).

#### Double dépense
[Approbation](#approbation) du même [Contrat](#contrat) de [Sortie](#sortie) par des [Dépenses](#dépense) distinctes.

#### Subvention
Émission de nouvelles [Unités](#unité) pour un [Mineur](#mineur).

#### Inflation
Augmentation de l'[Offre](#offre) résultant de la [Subvention](#subvention). Aussi appelée inflation monétaire, à ne pas confondre avec l'[Inflation des prix](#inflation-des-prix).

#### Frais
[Unités](#unité) [Transférées](#transfert) implicitement à un [Mineur](#mineur).

#### Récompense
Somme de la [Subvention](#subvention) et des [Frais](#frais) pour un [Bloc](#bloc).

#### Base de pièce
[Transaction](#transaction) qui [Transfère](#transfert) une [Récompense](#récompense).

#### Maturité
[Profondeur](#profondeur) à laquelle la [Sortie](#sortie) d'une [Base de pièce](#base-de-pièce) devient [Transférable](#transfert).

#### Halving
Réduction du taux de [Subvention](#subvention) (de moitié).

#### Difficulté
Niveau de [Preuve](#preuve) requis pour la [Validité](#validité).

#### Ajustement
Changement de la [Difficulté](#difficulté).

#### Plafond
Limite définitive de l'[Offre](#offre).

#### Prix
Moyenne mobile du taux d'[Échange](#échange).

#### Capitalisation
Produit du [Prix](#prix) et de l'[Offre](#offre).

## Économie

#### Commerce
Troc volontaire de biens entre deux [Personnes](#personne).

#### Utilité
Caractère utile d'un certain bien pour une [Personne](#personne).

#### Valeur
Préférence d'une [Personne](#personne) pour un certain bien par rapport à un autre.

#### Offre
Ensemble de toutes les [Unités](#unité) émises.

#### Échange
[Commerce](#commerce) d'[Unités](#unité) pour un autre bien.

#### Inflation des prix
Augmentation des [Prix](#prix) au fil du temps.

#### Thésauriser
[Posséder](#propriétaire) pour un usage futur.

#### Spéculer
[Posséder](#propriétaire) dans l'attente d'une augmentation du [Prix](#prix). Aussi, [Emprunter](#emprunter) dans l'attente d'une diminution du prix.

#### Prêter
[Échanger](#commerce) du temps sans [Unité](#unité) contre un bien de plus grande [Utilité](#utilité). « Investir » est un synonyme.

#### Emprunter
[Échanger](#commerce) du temps en possession d'[Unités](#unité) contre un bien de plus grande [Utilité](#utilité) pour le [Prêteur](#prêter).

#### Intérêt
Taux d'accroissement en [Utilité](#utilité) du [Prêt](#prêter).

#### Profit
Retour sur [Investissement](#investissement) au-dessus du taux d'[Intérêt](#intérêt) du [Marché](#marché).

#### Perte
Échec d'un [Investissement](#prêter) à générer un [Intérêt](#intérêt) au-dessus du taux du [Marché](#marché).

#### Volatilité
Variation du [Prix](#prix) au fil du temps.

#### Marché
[Commerce](#commerce) dans un certain bien.

## Réseau

#### Communication
Transfert de données entre des [Machines](#machine).

#### Protocole
Ensemble de conventions de [Communication](#communication).

#### Pair-à-pair
Un [Protocole](#protocole) symétrique.

#### Client-serveur
Un [Protocole](#protocole) asymétrique.

#### Latence
Délai inhérent à la [Communication](#communication).

#### Cloison
Incapacité de certains [Nœuds](#noeud) à [Communiquer](#communication).

#### Déni de service
Utiliser la [Communication](#communication) pour exploiter les défauts du [Protocole](#protocole) ou de l'[Implémentation](#implémentation) afin de dégrader leur performance. Couramment appelé DoS.

## Composants

#### Mine
[Outil](#outil) qui effectue du [Travail](#travail).

#### Hacheuse
[Outil](#outil) qui effectue du [Hachage](#hachage).

#### Relais
[Outil](#outil) qui diffuse les nouveaux [Blocs](#bloc).

#### Nœud
[Outil](#outil) qui réalise la [Validation](#validation).

#### Portefeuille
[Outil](#outil) qui crée les [Transactions](#transaction).

#### Outil
Ensemble d'instructions de [Machine](#machine).

#### Implémentation
Ensemble spécifique d'[Outils](#outil).

## Acteurs

#### Mineur
[Personne](#personne) qui gère une [Mine](#mine).

#### Hacheur
[Personne](#personne) qui gère une [Hacheuse](#hacheuse).

#### Relayeur
[Personne](#personne) qui gère un [Relais](#relais).

#### Commerçant
[Personne](#personne) qui accepte des [Unités](#unité) dans le [Commerce](#commerce). Un autre nom courant est « utilisateur ».

#### Propriétaire
[Personne](#personne) qui contrôle certaines [Unités](#unité). Un autre nom courant est « détenteur ».

#### Développeur
[Personne](#personne) qui crée une [Implémentation](#implémentation).

#### Créancier
[Personne](#personne) qui détient une créance sur un bien contrôlé par un [Dépositaire](#dépositaire). On parle aussi de titulaire de privilège, d'actionnaire, de [prêteur](#prêter) ou de déposant.

#### Dépositaire
[Personne](#personne) qui contrôle le bien d'autrui d'un commun accord.

## Minage

#### Travail
Procédé de production de [Blocs](#bloc).

#### Candidat
[Bloc](#bloc) potentiel avec une [Preuve](#preuve) indéterminée.

#### Hachage
Calcul insécable permettant de [Prouver](#preuve) la [Validité](#validité) d'un [Candidat](#candidat).

#### Taux de hachage
Vitesse de [Hachage](#hachage).

#### Puissance de hachage apparente
Une fraction de [Blocs](#bloc) dans un [Segment](#segment) de [Chaîne](#chaîne). Les estimations publiques de la [Puissance de hachage](#puissance-de-hachage) d'un [Mineur](#mineur) spécifique sont basées là-dessus.

#### Puissance de hachage majoritaire
Sous-ensemble de [Mineurs](#mineur) avec suffisamment de [Puissance de hachage](#puissance-de-hachage) pour exécuter une [Attaque](#attaque) soutenue. 51 % est une approximation courante de la puissance suffisante.

#### Optimisation
Changement d'[Outil](#outil) qui réduit le coût du [Minage](#mine).

#### Annonce
Première [Communication](#communication) d'un [Bloc](#bloc) à une autre [Personne](#personne).

#### Rétention
Retard intentionnel de l'[Annonce](#annonce).

#### Honnête
Un [Mineur](#mineur) qui construit à partir des [Blocs](#bloc) des autres.

#### Égoïste
Un [Mineur](#mineur) qui n'est pas toujours [Honnête](#honnête).

#### Variance
Fréquence variable d'obtention d'une [Récompense](#récompense).

#### Découpler
Une [Mine](#mine) qui partage la [Récompense](#récompense) avec une autre pour réduire la [Variance](#variance).

## Déviations

#### Fork
Divergence dans les [Règles de consensus](#règles-de-consensus).

#### Hard fork
[Fork](#fork) qui implique une [Scission](#scission). Expansion de l'ensemble des [Blocs](#bloc) potentiellement [Valides](#validité).

#### Soft fork
[Fork](#fork) qui implique une [Scission](#scission) à moins d'être [Appliqué](#application) par la [Puissance de hachage majoritaire](#puissance-de-hachage-majoritaire). Contraction de l'ensemble des [Blocs](#bloc) potentiellement [Valides](#validité).

#### Scission
Bifurcation d'une [Monnaie](#monnaie).

#### Recoordination
[Annonce](#annonce) qui promeut une [Branche](#branche) [Faible](#faible) de la [Chaîne](#chaîne). On utilise aussi le terme « réorganisation » et son abréviation « réorg ».

#### Ralentissement
Manque d'augmentation de la [Hauteur](#hauteur) au fil du temps.

#### Activation
Début de l'[Application](#application) d'une nouvelle [Règle](#règle).

#### Signal
Indication d'un [Mineur](#mineur) par le biais des données du [Bloc](#bloc) de son intention d'[Appliquer](#application) une nouvelle [Règle](#règle).

## Confidentialité

#### Identité
Moyen d'associer une [Communication](#communication) à une [Personne](#personne).

#### Salissure
Détermination de la [Propriété](#propriétaire).

## Sécurité

#### Pouvoir
Niveau relatif de contrôle d'une [Personne](#personne) sur une [Chaîne](#chaîne) ou une [Monnaie](#monnaie).

#### Économie
Ensemble de tous les [Commerçants](#commerçant).

#### Pouvoir économique
Fraction de tous les biens offerts dans l'[Échange](#échange).

#### Puissance de hachage
Fraction du [Taux de hachage](#taux-de-hachage) de toutes les [Mines](#mine).

#### Attaque
Utilisation de la [Puissance de hachage](#puissance-de-hachage) pour permettre la [Double dépense](#double-dépense).

#### Cooptation
Utilisation de l'agression pour contrôler la [Puissance de hachage](#puissance-de-hachage).

#### Coercition
Utilisation de l'agression pour contraindre l'[Activation](#activation).

#### Distorsion
Agression contre le [Marché](#marché) qui fausse le coût du [Minage](#mine).

#### Variation
Différences dans le coût des ressources de [Minage](#mine).

#### Censure
[Confirmation](#confirmation) subjective.

#### État
Ensemble de [Personnes](#personne) utilisant l'agression à la place du [Commerce](#commerce). Opère typiquement en toute impunité au sein de frontières géographiques.

#### Politique
Qui concerne les actions des [États](#état).

## Faiblesses

#### Agrégation
Tendance à une participation réduite dans le [Minage](#mine) ou la [Validation](#validation). Implique un [Regroupement](#regroupement) ou une [Centralisation](#centralisation). 

#### Regroupement
Tendance vers moins de [Mineurs](#miner), ce qui inclue la consolidation par [Relais](#relais).

#### Centralisation
Tendance vers moins de [Commerçants](#commerçant). Les commerçants contrôlent directement la [Validation](#validation). Peut aussi concerner le [Regroupement](#regroupement).

#### Décentralisation
Tendance s'opposant à la [Centralisation](#centralisation)

#### Délégation
Tendance vers moins de [Propriétaires](#propriétaire). Les propriétaires contrôlent directement la [Dépense](#dépense).

#### Cloisonnement
Tendance vers des [Cloisons](#cloison) permanentes.

#### Corrélation
Capacité à [Salir](#salissure) en utilisant l'analyse statistique de [Chaîne](#chaîne).

---

Texte original : [Glossary](https://github.com/libbitcoin/libbitcoin-system/wiki/Glossary)