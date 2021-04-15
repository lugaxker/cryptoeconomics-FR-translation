# Lexique

## Fondamentaux

#### Personne
Un décideur.

#### Machine
Un suiveur d'instructions.

## Accord

#### Bitcoin
Ensemble des principes qui sécurisent une [Monnaie](#monnaie) de l'[État](etat).
> Le terme et les principes sont définis par Satoshi dans « Bitcoin: A Peer-to-Peer Electronic Cash System ».

#### Consensus
Un accord entre les [Personnes](#personne).
> Aussi l'ensemble des gens qui participent dans un accord.

#### Monnaie
Un [Consensus](#consensus) concernant un moyen mutuellement acceptable pour le [Commerce](#commerce).
> BTC est une Monnaie.

#### Règles de consensus
Ensemble de contraintes qui définissent une [Monnaie](#monnaie).

#### Règle
Un sous-ensemble des [Règles de consensus](#regles-de-consensus).

#### Validité
Conformité aux [Règles de consensus](#regles-de-consensus).

#### Validation
Procédure pour déterminer la [Validité](#validite).

#### Application
Acte de rejeter une donnée [Invalide](#validite).

## Objets

#### Unité
Un montant minimal transférable de propriété biens représenté par une [Monnaie](#monnaie).
> Le Satoshi est l'unité de Bitcoin.

#### Transfert
Changement de contrôle sur certaines [Unités](#unite).

#### Transaction
Trace écrite [Valide](#validite) d'un [Transfert](#transfert).

#### Bloc
Une ensemble [Valide](#validite) de [Transactions](#transaction) avec [Horodatage](#horodatage) et une [Preuve](#preuve).

#### Chaîne
La [Branche](#branche) ayant le plus de [Preuve](#preuve) cumulée.

## Transactions

#### Script
Un ensemble d'[Opérations](#operation) qui autorisent un [Transfert](#transfert).

#### Opération
Une déclaration d'intention insécable.

#### Contrat
Un [Script](#script) qui exprime des conditions de [Transfert](#transfert).
> Script de clé publique (scriptPubKey) est un anachronisme pour ceci.

#### Approbation
Un [Script](#script) qui satisfait un [Contrat](#contrat).
> Script de signature (scriptSig) est un anachronisme pour ceci.

#### Point
Une référence à une [Sortie](#sortie) ou une [Entrée](#entree).

#### Sortie
Un [Transfert](#transfert) explicite et un [Contract](#contract).

#### Input
Un [Point](#point) de [Sortie](#sortie) et une [Approbation](#approbation).

#### Sortie précédente
[Sortie](#sortie) à laquelle se réfère une [Entrée](#entree).

#### Temps de verrouillage
Une expression de la plus ancienne [Validité](#validite) de la [Transaction](#transaction).

#### Poussière
Un nombre insuffisant d'[Unités](#unite) pour le [Transfert](#transfert) par une [Sortie](#sortie).
> Les règles de consensus de BTC interdisent le transfert de moins d'une unité.

## Blocs

#### Horodatage
Une déclaration du temps de la production du [Bloc](#bloc).

#### Temps passé médian
Une moyenne des [Horodatages](#horodatages) des précédents [Blocs](#bloc).

#### Preuve
Marque [Valide](#validité).

#### Preuve de travail
[Preuve](#preuve) probabilistique d'une quantité de [Travail](#travail) effectuée (PDT).

#### Preuve de mémoire
[Preuve](#preuve) probabilistique d'une quantité mémoire de calcul utilisable (PDM).

#### Preuve d'enjeu
[Preuve](#preuve) cryptographique d'une quantité de [Propriété](#propriétaire) (PDE)

#### Branche
Une séquence [Valide](#validite) de [Blocs](#bloc).

#### Faible
Une [Branche](#branche) avec moins de [Preuve](#proof) cumulée qu'une autre.
> Orphelin est un abus de langage pour ceci.

#### Forte
Une [Branche](#branche) avec plus de [Preuve](#proof) cumulée qu'une autre.

## Enchaînement

#### Confirmation
Inclusion d'une [Transaction](#transaction) dans un [Bloc](#bloc).

#### Non confirmée
Une [Transaction](#transaction) qui n'existe pas dans un [Bloc](#bloc).

#### Réserve des transactions
Ensemble des [Transactions non confirmées](#non-confirmee).
> Zone mémoire est un abus de langage pour ceci.

#### Réserve des blocs
Ensemble des [Blocs faibles](#faible)
> Réserve des orphelins est un abus de langage pour ceci.

#### Genèse
Premier [Bloc](#bloc) de toutes les [Branches](#branche) d'une [Monnaie](#monnaie).

#### Profondeur
1 plus le nombre de [Blocs](#bloc) après une [Confirmation](#confirmation).

#### Hauteur
Nombre de [Blocs](#bloc) précédents dans une [Branche](#branche).

#### Segment
Un sous-ensemble contigu d'une [Branche](#branche).

#### Coordination
Une [Annonce](#annonce) ajoutant un [Bloc](#bloc) à la [Chaîne](#chaine).

#### Période
Temps moyen entre les [Coordinations](#coordination).

#### Surcouche
[Commerce](#commerce) utilisant une série de [Transactions](#transaction) [Non confirmées](#non-confirmee) qui peuvent être [Réglées](#règlement) par l'une ou l'autre des parties. 

#### Règlement
[Confirmation](#confirmation) des [Transactions](#transaction) en [Surcouche](#surcouche).

## Monnaie

#### Dépense
Publication initiale d'une [Transaction](#transaction).

#### Double dépense
[Approbation](#approbation) du même [Contrat](#contrat) de [Sortie](#sortie) par des [Dépenses](#dépense) distinctes.

#### Subvention
Émission de nouvelles [Unités](#unite) pour un [Mineur](#mineur).

#### Inflation
Augmentation de l'[Offre](#offre) résultant de la [Subvention](#subvention).
> Aussi inflation monétaire, à ne pas confondre avec l'inflation des prix.

#### Frais
Un [Transfert](#transfert) implicite à un [Mineur](#mineur).

#### Récompense
Somme de la [Subvention](#subvention) et des [Frais](#frais) pour un [Bloc](#bloc).

#### Base de pièce
Une [Transaction](#transaction) qui [transfère](#transfert) une [Récompense](#recompense).

#### Maturité
[Profondeur](#profondeur) à laquelle la [Sortie](#sortie) d'une [Base de pièce](#base-de-piece) devient [Transférable](#transfert).

#### Réduction de moitié
Réduction du taux de [Subvention](#subvention) (de moitié).

#### Difficulté
Niveau de [Preuve](#preuve) requis pour la [Validité](#validite).

#### Ajustement
Un changement de la [Difficulté](#difficulte).

#### Plafond
Limite de l'[Offre](#offre) de tous temps.

#### Prix
Une moyenne mobile du taux de [Échange](#echange).

#### Capitalisation
Produit du [Prix](#prix) et de l'[Offre](#offre).

## Économie

#### Commerce
Un troc volontaire de biens entre deux [Personnes](#personne).

#### Utilité
Caractère utile d'un certain bien pour une [Personne](#personne).

#### Valeur
Préférence d'une [Personne](#personne) pour un certain bien par rapport à un autre.

#### Offre
Ensemble de toutes les [Unités](#unite) émises.

#### Échange
[Commerce](#commerce) d'[Unités](#unite) pour un autre bien.

#### Inflation des prix
Augmentation des prix moyens d'[Échange](#echange) au fil du temps.

#### Thésauriser
[Posséder](#propriétaire) pour un usage futur.
> Ce n'est ni de la spéculation ni de l'investissement.

#### Spéculer
[Posséder](#propriétaire) dans l'attente d'une augmentation du [Prix](#prix).
> Aussi, emprunter dans l'attente d'une diminution du prix.

#### Prêter
[Commercer](#commerce) du temps sans [Unité](#unite) contre un bien de plus grande [Utilité](#utilite).
> Investir est un autre nom pour ceci.

#### Emprunter
[Commercer](#commerce) du temps avec des [Unités](#unite) contre un bien de plus grande [Utilité](#utilite) pour le [Prêteur](#preter).

#### Intérêt
Taux d'accroissement en [Utilité](#utilite) du [Prêt](#preter).

#### Profit
Retour sur [Investissement](#investissement) au-dessus du taux de [Marché](#marché) de l'[Intérêt](#intérêt)

#### Perte
Échec d'un [Investissement](#preter) à générer des [Intérêts](#interet).
> C'est du profit négatif.

#### Volatilité
Variation du [Prix](#prix) au fil du temps.

#### Marché
[Commerce](#commerce) dans un certain bien.

## Réseau

#### Communication
Transfert de données entre des [Machines](#machine).

#### Protocole
Un ensemble de conventions de [Communication](#communication).

#### Pair-à-pair
Un [Protocole](#protocole) symétrique.

#### Client-serveur
Un [Protocole](#protocole) asymétrique.

#### Latence
Délai inhérent à la [Communication](#communication).

#### Cloison
Une incapacité de certains [Nœuds](#noeud) à [Communiquer](#communication).

#### Déni de service
Utiliser la [Communication](#communication) pour exploiter les défauts du [Protocole](#protocole) ou de l'[Implémentation](#implementation) afin de dégrader leur performance.
> Couramment appelé DoS.

## Composants

#### Mine
Un [Outil](#outil) qui effectue du [Travail](#travail).

#### Hacheuse
Un [Outil](#outil) qui effectue du [Hachage](#hachage).

#### Relais
Un [Outil](#outil) qui diffuse les nouveaux [Blocs](#bloc).

#### Nœud
Un [Outil](#outil) qui effectue la [Validation](#validation).

#### Portefeuille
Un [Outil](#outil) qui crée les [Transactions](#transaction).

#### Outil
Un ensemble d'instructions de [Machine](#machine).

#### Implémentation
Un ensemble spécifique d'[Outils](#outil).

## Acteurs

#### Mineur
Une [Personne](#personne) qui gère une [Mine](#mine).

#### Hacheur
Une [Personne](#personne) qui gère une [Hacheuse](#hacheuse).

#### Relayeur
Une [Personne](#personne) qui gère un [Relais](#relais).

#### Marchand
Une [Personne](#personne) qui accepte des [Unités](#unite) dans le [Commerce](#commerce).
> Utilisateur est un autre nom courant pour ceci.

#### Propriétaire
Une [Personne](#personne) qui contrôle certaines [Unités](#unite).
> Détenteur est un autre nom courant pour ceci.

#### Développeur
Une [Personne](#personne) qui crée une [Implémentation](#implementation).

#### Créancier
Une [Personne](#personne) qui détient une créance sur un bien sous le contrôle d'un [Dépositaire](#dépositaire). 
> Aussi titulaire d'un privilège, actionnaire, prêteur ou déposant.

#### Dépositaire
Une [Personne](#personne) qui contrôle le bien d'autrui. 

## Minage

#### Travail
Procédé de production de [Blocs](#bloc).

#### Candidat
Un [Bloc](#bloc) potentiel avec une [Preuve](#preuve) indéterminée.

#### Hachage
Un calcul insécable pour [Prouver](#preuve) la [Validité](#validite) d'un [Candidat](#candidat).

#### Taux de hachage
Vitesse de [Hachage](#hachage).

#### Puissance de hachage apparente
Une fraction de [Blocs](#bloc) dans un [Segment](#segment) de [Chaîne](#chaine).
> Les estimations publiques de la puissance de hachage sont basée là-dessus.

#### Puissance de hachage majoritaire
Un sous-ensemble de [Mineurs](#mineur) avec suffisamment de [Puissance de hachage](#puissance-de-hachage) pour exécuter une [Attaque](#attack) soutenue.
> 51 % est une approximation courante de la puissance suffisante.

#### Optimisation
Un changement [Outil](#outil) qui réduit le coût du [Minage](#mine).

#### Annonce
Première communication d'un [Bloc](#bloc) à une autre [Personne](#personne).

#### Retenue
Retard intentionnel de l'[Annonce](#annonce).

#### Honnête
Un [Mineur](#mineur) qui construit à partir des [Blocs](#bloc) des autres.

#### Égoïste
Un [Mineur](#mineur) qui n'est pas toujours [Honête](#honnete).

#### Variance
Fréquence variable d'obtention d'une [Récompense](#recompense).

#### Découpler
Une [Mine](#mine) qui partage la [Récompense](#recompense) avec une autre pour réduire la [Variance](#variance).

## Déviations

#### Fork
Une divergence dans les [Règles de consensus](#regles-de-consensus).

#### Hard fork
Un [Fork](#fork) qui implique une [Scission](#scission).
> Expansion de l'ensemble des blocs potentiellement valides.

#### Soft fork
Un [Fork](#fork) qui implique une [Scission](#scission) à moins d'être [Appliquée](#application) par la [Puissance de hachage majoritaire](#puissance-de-hachage-majoritaire).
> Contraction de l'ensemble des blocs potentiellement valides.

#### Scission
Bifurcation d'une [Monnaie](#monnaie).

#### Recoordination
Une [Annonce](#annonce) qui promeut une [Branche faible](#faible) de la [Chaîne](#chaine).
> Reorg est une abréviation de ceci.

#### Caler
Manque d'augmentation de la [Hauteur](#hauteur) au fil du temps.

#### Activation
Début de l'[Application](#application) d'une nouvelle [Règle](#regle).

#### Signal
Indication d'un [Mineur](#mineur) par le biais des données du [Bloc](#bloc) de son intention d'[Appliquer](#application) une nouvelle [Règle](#regle).

## Confidentialité

#### Identité
Moyen d'associer la [Communication](#communication) à une [Personne](#personne).

#### Salissure
Détermination de la [Propriété](#propriétaire).

## Sécurité

#### Puissance
Niveau relatif de contrôle d'une [Personne](#personne) sur une [Chaîne](#chaine) ou une [Monnaie](#monnaie).

#### Economie
Ensemble de tous les [Marchands](#marchand).

#### Puissance économique
Une fraction de tous les biens offerts dans l'[Échange](#echange).

#### Puissance de hachage
Une fraction du [Taux de hachage](#taux-de-hachage) de toutes les [Mines](#mine).

#### Attaque
Utilisation de la [Puissance de hachage](#puissance-de-hachage) pour permettre la [Double dépense](#double-depense).
> L'entrave de la confirmation est un cas de permission de double dépense.

#### Cooptation
Utilisation de l'agression pour contrôler la [Puissance de hachage](#puissance-de-hachage).

#### Coercition
Utilisation de l'agression pour contraindre l'[Activation](#activation).

#### Altération
Agression contre le [Marché](#marche) qui fausse le coût du [Minage](#mine).

#### Variation
Différences dans le coût des ressources de [Minage](#mine).

#### Censure
[Confirmation](#confirmation) subjective.

#### État
Ensemble de [Personnes](#personne) qui utilisent l'agression à la place du [Commerce](#commerce).
> Opère typiquement en toute impunité au sein de frontières géographiques.

#### Politique
Qui concerne les actions des [États](#etat).

## Faiblesses

#### Agrégation
Tendance à une participation réduite dans le [Minage](#mine) ou la [Validation](#validation).
> Implique un regroupement ou une centralisation. 

#### Regroupement
Tendance vers moins de [Mineurs](#miner), y compris la consolidation par [Relais](#relais).
> Connivence est un autre nom courant pour ceci.

#### Centralisation
Tendance vers moins de [Marchands](#marchand).
> Les marchands contrôlent directement la validation.

#### Décentralisation
Tendance s'opposant à la [Centralisation](#centralisation)

#### Délégation
Tendance vers moins de [Propriétaires](#propriétaire).
> Les propriétaires contrôlent directement la dépense.

#### Cloisonnement
Tendance vers des [Cloisons](#cloison) permanentes.
> L'identité implique l'exclusion.

#### Corrélation
Capacité à [Salir](#salissure) en utilisant l'analyse statistique de [Chaîne](#chaine).

---

Texte original : [Glossary](https://github.com/libbitcoin/libbitcoin-system/wiki/Glossary)