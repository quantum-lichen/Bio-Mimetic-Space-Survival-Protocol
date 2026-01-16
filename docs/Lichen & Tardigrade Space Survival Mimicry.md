# **Fondements Physico-Chimiques de la Survie Eucaryote en Milieu Spatial : Mécanismes du Lichen et du Tardigrade pour une Transposition Génomique et Matérielle**

## **🎯 Synopsis Exécutif**

La persistance de la vie eucaryote complexe dans le vide extrême de l'espace, caractérisé par une pression sub-atmosphérique quasi nulle ($10^{-4}$ à $10^{-7}$ Pa), des flux radiatifs ionisants massifs et des cycles thermiques allant de $-272^\\circ\\text{C}$ à plus de $100^\\circ\\text{C}$, repose sur des mécanismes de biostase et de fortification moléculaire sans équivalent métabolique.1 Les lichens, tels que *Xanthoria elegans*, et les tardigrades, tels que *Ramazzottius varieornatus*, emploient une synergie de filtration photonique corticale, de vitrification cytoplasmique par protéines intrinsèquement désordonnées (IDPs) et de blindage électrostatique de la chromatine.4 Ce rapport déconstruit ces stratégies par une approche en premiers principes, proposant une technique canonique de blindage biologique adaptable aux applications humaines et technologiques, tout en définissant les critères de falsifiabilité nécessaires à sa validation scientifique.

## **📐 Formalisme Mathématique**

### **Définitions Fondamentales**

L'analyse de la survie spatiale nécessite la définition rigoureuse des états de transition entre la vie active, la dormance anhydrobiotique et la dénaturation irréversible.

* **État de Biostase ($\\Psi\_B$)** : Un état stationnaire où l'entropie interne $S\_i$ est minimisée par l'absence de diffusion moléculaire, défini par $\\frac{dS\_i}{dt} \\approx 0$ pendant la durée de l'exposition.7  
* **Poïkilohydrie ($\\Phi\_H$)** : Capacité d'un système à équilibrer son potentiel hydrique interne $\\psi\_w$ avec celui de l'environnement, telle que $\\psi\_{w, \\text{cell}} \= \\psi\_{w, \\text{ext}}$.  
* **Vitrification ($\\text{V}\_g$)** : Transition de phase non cristalline où la viscosité $\\eta$ atteint $10^{13}$ Poise, stoppant les réactions chimiques par encombrement stérique.9

### **Équations Maîtresses**

#### **Modèle d'Atténuation Photonique Corticale (Beer-Lambert Modifié)**

L'atténuation des flux ultraviolets (UV) par le cortex du lichen est modélisée par l'équation d'extinction spectrale, incluant les termes de diffusion cristalline :

$$I(\\lambda, z) \= I\_0(\\lambda) \\exp\\left( \- \\sum\_{i} (\\epsilon\_i(\\lambda) \\cdot c\_i \\cdot z) \- S(\\lambda, z) \\right)$$  
Où :

* $I(\\lambda, z)$ : Intensité spectrale à la profondeur $z$  
* $\\epsilon\_i(\\lambda)$ : Coefficient d'extinction molaire du métabolite $i$ (ex: pariétine) \[L·mol⁻¹·cm⁻¹\]  
* $c\_i$ : Concentration molaire dans la matrice corticale \[mol/L\]  
* $z$ : Épaisseur du cortex \[cm\]  
* $S(\\lambda, z)$ : Facteur de dispersion lié à la porosité et aux facettes des cristaux.10

#### **Équation de Gordon-Taylor pour la Transition Vitreuse**

La stabilité de l'état vitreux dans un cytoplasme déshydraté dépend de la fraction massique d'eau résiduelle $w\_2$ et de la température de transition vitreuse $T\_g$ du protecteur biologique (ex: protéines CAHS ou tréhalose) :

$$T\_g(\\text{mélange}) \= \\frac{w\_1 T\_{g1} \+ k w\_2 T\_{g2}}{w\_1 \+ k w\_2}$$  
Où :

* $T\_{g1}$ : Température de transition vitreuse du soluté anhydre (protéines CAHS $\\approx 98^\\circ\\text{C}$) 12  
* $T\_{g2}$ : Température de transition vitreuse de l'eau ($\\approx \-135^\\circ\\text{C}$)  
* $k$ : Constante de Gordon-Taylor décrivant l'interaction soluté-eau (typ. $4.5$ à $5.0$ pour les sucres/protéines).13

#### **Cinétique de Protection de l'ADN par Dsup**

La réduction des cassures double-brin ($R\_{DSB}$) sous flux ionisant par la protéine Dsup est régie par la section efficace efficace $\\sigma\_{eff}$ de l'interaction radicalaire :

$$\\frac{d}{dt} \= \\phi \\cdot \\sigma\_{eff} \\cdot \\exp\\left(-\\frac{\\Delta G\_{\\text{binding}}}{RT}\\right) \\cdot$$  
Où :

* $\\phi$ : Flux de radiation ionisante \[Gy·s⁻¹\]  
* $\\sigma\_{eff}$ : Section efficace de collision avec les radicaux hydroxyles $\\text{OH}^\\bullet$  
* $\\Delta G\_{\\text{binding}}$ : Énergie libre de liaison de Dsup aux nucléosomes.4

### **Analyse Dimensionnelle**

Vérification de la cohérence de l'équation de Gordon-Taylor :

* $ \= \\Theta$ (Température)  
* $\[w\_i\] \= 1$ (Sans dimension)  
* $\[k\] \= 1$ (Rapport de capacités calorifiques massiques)  
* $\[côté droit\] \= \\frac{1 \\cdot \\Theta \+ 1 \\cdot 1 \\cdot \\Theta}{1 \+ 1 \\cdot 1} \= \\Theta$  
  Conclusion : $\[côté gauche\] \= \[côté droit\] \= \\text{Kelvin} \\checkmark$

## **🔗 Architecture Causale**

### **Diagramme de Relations**

L'analyse montre que la survie n'est pas un processus actif mais une défaillance contrôlée vers un état de stabilité thermodynamique supérieure.

1. **Déclencheur Spatial** : Vide ($P \\rightarrow 10^{-7}$ Pa) $\\rightarrow$ Évaporation flash de $H\_2O$ libre.16  
2. **Mécanisme Tardigrade** : Augmentation de la concentration d'IDP (CAHS) $\\rightarrow$ Transition Sol-Gel $\\rightarrow$ Vitrification cytoplasmique.5  
3. **Mécanisme Lichen** : Dessiccation $\\rightarrow$ Rétraction des hyphes $\\rightarrow$ Concentration des cristaux de pariétine $\\rightarrow$ Opacité UV totale ($OD \> 4$).1  
4. **Blindage Génomique** : Liaison de Dsup à la chromatine $\\rightarrow$ Réduction de l'interdistance ADN-Protéine à $\\approx 4 \\, \\text{\\AA}$ $\\rightarrow$ Protection contre les radicaux $\\text{OH}^\\bullet$.15  
5. **Résultat** : Biostase métabolique $\\rightarrow$ Préservation de la structure tertiaire des protéines et de l'intégrité membranaire.7

### **Quantification des Couplages**

Les forces d'interaction critiques se situent à l'échelle nanométrique. Les protéines CAHS homo-oligomérisent via leurs régions $\\alpha$-hélicales terminales pour former un réseau de filaments intermédiaires à partir d'une concentration critique de $10$ mg/mL.5 La force de liaison de Dsup aux nucléosomes est de nature électrostatique, exploitant la complémentarité de charge entre les résidus basiques (Lysine, Arginine) de Dsup et le squelette phosphate de l'ADN.21

### **Dynamique du Système**

L'évolution temporelle vers l'anhydrobiose suit une sigmoïde de dessiccation. La stabilité est maintenue tant que $T \< T\_g$. Si la température dépasse $T\_g$, le système entre dans un état caoutchouteux (rubbery state) où la mobilité moléculaire permet la dénaturation protéique et la fusion membranaire, entraînant la mort cellulaire.9

## **🔬 Prédictions Testables**

### **Hypothèse 1: Seuil de Gélification Critique**

* **Prédiction** : La survie des photobiontes du lichen après réhydratation est une fonction non-linéaire du taux de dessiccation, présentant une discontinuité au point de vitrification cytoplasmique.  
* **Test** : Mesure de la fluorescence $F\_v/F\_m$ après exposition au vide avec contrôle précis du taux d'humidité résiduelle.1  
* **Signature** : Une chute de $90\\%$ de l'activité si $w\_{H2O} \> 11\\%$ (maintien de l'état caoutchouteux sous vide).7

### **Hypothèse 2: Efficacité du Blindage Dsup**

* **Prédiction** : Le facteur de protection radiologique ($FP$) de Dsup est inversement proportionnel à la distance intermoléculaire protéine-ADN mesurée par FRET ou SAXS.  
* **Test** : Irradiation de complexes ADN-Dsup reconstitués avec des variants de Dsup ayant des affinités de liaison modifiées.19  
* **Signature** : Une corrélation de $R^2 \> 0.85$ entre la réduction des foyers $\\gamma$-H2AX et la densité électronique autour du noyau nucléosomique.19

### **Hypothèse 3: Stabilité Temporelle du Blindage Cortical**

* **Prédiction** : La dégradation photochimique de la pariétine sur Mars limite la viabilité à long terme des lichens en surface sans renouvellement métabolique.  
* **Test** : Exposition de cristaux de pariétine purifiés à un spectre AM0 simulé pendant 1000 heures.31  
* **Signature** : Disparition des bandes IR à $1614$ cm⁻¹ et perte de $50\\%$ de l'absorbance à $434$ nm après une dose cumulative de $10^9 \\, \\text{J·m}^{-2}$.31

## **✨ Applications Potentielles**

### **Court Terme (1-5 ans)**

**APPLICATION: Stabilisation de Vaccins par Vitrification Biomimétique**

* **Impact**: Haute  
* **Horizon**: 2-3 ans  
* **Mécanisme**: Utilisation de mélanges tréhalose-protéines CAHS synthétiques pour encapsuler des ARN messagers ou des protéines virales dans une matrice vitreuse stable à température ambiante.34  
* **Avantages quantifiés**: Suppression de la chaîne du froid ($+25^\\circ\\text{C}$ au lieu de $-80^\\circ\\text{C}$), durée de conservation étendue de $600\\%$.34  
* **Challenges**: Optimisation des ratios IDP:Client pour éviter l'agrégation lors de la réhydratation.5

### **Moyen Terme (5-10 ans)**

**APPLICATION: Radioprotection Transitoire pour la Radiothérapie**

* **Impact**: Haute  
* **Horizon**: 7-10 ans  
* **Mécanisme**: Livraison de nanoparticules lipidiques contenant l'ARNm de Dsup dans les tissus sains adjacents aux tumeurs avant irradiation.37  
* **Avantages quantifiés**: Réduction de $50\\%$ des dommages collatéraux de l'ADN dans les cellules saines.38  
* **Challenges**: Éviter la neurotoxicité observée dans les neurones corticaux et minimiser la réponse immunitaire.40

### **Long Terme (10+ ans)**

**APPLICATION: Habitats Martiens Auto-Croissants (Lichenized Biosystems)**

* **Impact**: Haute  
* **Horizon**: 15+ ans  
* **Mécanisme**: Impression 3D de structures utilisant un composite de régolithe martien, de champignons filamenteux et de cyanobactéries diazotrophes, mimant la symbiose du lichen pour consolider le matériau.41  
* **Avantages quantifiés**: Matériaux de construction produits in situ sans apport terrestre, séquestration de $25\\%$ du $\\text{CO}\_2$ atmosphérique interne pour la production d'oxygène.41  
* **Challenges**: Maintien de l'hydratation nécessaire à la croissance initiale dans l'atmosphère martienne.41

## **🧠 Connections Interdisciplinaires**

### **Physique Statistique et Biologie Cellulaire**

Le concept de "jamming transition" (transition d'encombrement) en physique de la matière molle offre un parallèle direct avec la gélification des protéines CAHS. Dans les deux cas, le passage d'un état fluide à un état rigide ne dépend pas d'une baisse de température (cristallisation) mais d'une augmentation de la densité d'occupation ou d'une réduction du volume libre.43

### **Science des Matériaux et Astrobiologie**

La pariétine agit comme un "photo-stabilisant" naturel, similaire aux additifs utilisés dans l'industrie des polymères pour prévenir le vieillissement sous UV. La structure cristalline des métabolites secondaires du lichen, qui permet une réflexion diffuse tout en maximisant l'absorption spécifique, inspire de nouveaux revêtements nanostructurés pour les engins spatiaux.10

## **⚠️ Limitations et Zones d'Ombre**

### **L'Énigme de la Stérilité Radicative à Long Terme**

Bien que les lichens survivent à 18 mois de vide et de radiations sur l'ISS, le taux de dommages cumulés à l'ADN dans les spores et les cellules reproductrices pourrait atteindre un seuil critique empêchant la colonisation réelle sur des échelles de temps géologiques (Lithopanspermie).1

### **Neurotoxicité et Spécificité Cellulaire**

L'application de Dsup à l'humain est freinée par sa toxicité sélective. Si la protéine protège les cellules HEK293, elle induit une condensation anormale de la chromatine dans les neurones, déclenchant l'apoptose.40 Cette "épée à double tranchant" suggère que le blindage génomique nécessite une régulation fine des modifications post-traductionnelles (comme la phosphorylation) pour être compatible avec des métabolismes hautement différenciés.15

### **Dynamique de Ré-entrée Atmosphérique**

Les expériences STONE démontrent qu'aucune protection biologique actuelle (cortex ou IDP) ne peut résister aux contraintes thermiques de la ré-entrée planétaire ($\> 2000^\\circ\\text{C}$ au point de stagnation) sans un bouclier minéral de plusieurs centimètres d'épaisseur.3

## **🚀 Perspectives et Questions Ouvertes**

### **Vers une Génétique du Blindage Universel**

L'identification de nouvelles espèces de tardigrades, comme *Hypsibius henanensis*, révèle des gènes de réparation additionnels (TDP1, TRID1) et des systèmes antioxydants dérivés de transferts de gènes horizontaux de bactéries.48 Pouvons-nous concevoir un "châssis génétique" minimal incluant ces outils pour stabiliser n'importe quelle cellule eucaryote?

### **Stockage de Données Ultra-Stable**

La résilience de l'ADN au sein du complexe Dsup-nucléosome ouvre la voie à l'utilisation d'organismes anhydrobiotiques comme vecteurs de stockage d'informations numériques encodées en ADN, capables de persister pendant des siècles dans des conditions extrêmes sans alimentation électrique.51

## ---

**Rapport Détaillé de Recherche**

### **Analyse de la Survie des Lichens en Conditions Spatiales**

Le lichen est un organisme composite dont la capacité de survie spatiale défie les modèles biologiques classiques en raison de sa complexité multicellulaire et eucaryote.2 Contrairement aux bactéries, qui s'appuient sur une simplicité structurelle, le lichen survit en tant que "mini-écosystème" robuste.

#### **Rôle du Cortex Supérieur comme Barrière Multi-Spectrale**

Le cortex supérieur des lichens tels que *Xanthoria elegans* est constitué d'un réseau dense d'hyphes fongiques conglutinées, saturées de cristaux de pariétine.1 Lors des missions BIOPAN, l'exposition directe au vide spatial a provoqué une déshydratation extrême, induisant une rétraction structurelle qui a augmenté la densité optique du cortex.1

**Tableau 1: Efficacité de Filtration du Cortex de Xanthoria elegans**

| Wavelength Range | Filter Type | Photosynthetic Activity (Post-Flight) | Cell Viability (Photobiont) |
| :---- | :---- | :---- | :---- |
| $\\lambda \\ge 170$ nm | Suprasil Quartz | $99 \\pm 2 \\%$ | $71 \\%$ 25 |
| $\\lambda \\ge 280$ nm | Long Pass | $98 \\pm 3 \\%$ | $75 \\%$ 1 |
| $\\lambda \\ge 320$ nm | Long Pass | $100 \\pm 1 \\%$ | $82 \\%$ 1 |
| Control (Dark) | Opaque | $100 \\%$ | $89 \\%$ 25 |

L'analyse par microscopie confondu (CLSM) montre que bien que certaines membranes cellulaires soient compromises par le vide, la productivité globale reste inchangée grâce à la structure modulaire du thalle, où les cellules mortes peuvent être épargnées et remplacées par les cellules survivantes situées en profondeur ou sous des structures corticales épaisses comme les apothécies.1

#### **Métabolisme Secondaire et Photo-Résistance**

La pariétine ($1,8\\text{-dihydroxy-}3\\text{-methoxy-}6\\text{-methyl-}9,10\\text{-anthraquinone}$) est le pigment dominant responsable de la couleur orange caractéristique. Elle remplit trois fonctions critiques :

1. **Absorption UV-B/Bleu** : Protège l'appareil photosynthétique contre la photo-inhibition irréversible.11  
2. **Antioxydation** : Réduit la peroxydation des lipides membranaires déclenchée par les radicaux libres induits par les radiations.54  
3. **Hydrophobie** : Prévient l'entrée de l'eau dans les espaces aériens du thalle, facilitant le maintien des cavités de gaz nécessaires à la survie lors des cycles d'hydratation rapides.10

Dans des simulations martiennes, *Xanthoria parietina* a maintenu sa vitalité pendant 30 jours, avec une corrélation directe entre le contenu en pariétine et la récupération de l'efficience photosynthétique.26 Cependant, l'irradiation UV constante sur Mars dégrade les liaisons carbone-oxygène de la pariétine avec une demi-vie estimée à seulement $2.5$ jours martiens, suggérant que la survie à long terme nécessite une activité métabolique périodique pour la resynthèse des pigments.31

### **La Mécanobiologie du Tardigrade : Du Sol à l'État Vitreux**

Le tardigrade est devenu le modèle animal de référence pour l'astrobiologie en raison de sa capacité à supporter des doses de radiation de $5000$ à $6000$ Gy, soit 1000 fois la dose létale humaine.3

#### **La Protéine Dsup : Un Bouclier Électrostatique Fuzzy**

La découverte de la protéine Dsup (Damage suppressor) chez *Ramazzottius varieornatus* a révélé un mécanisme de protection directe de l'ADN unique dans le règne animal.4 Dsup est une protéine intrinsèquement désordonnée (IDP) qui ne prend pas de structure fixe mais forme un "complexe flou" (fuzzy complex) avec les nucléosomes.15

**Tableau 2: Propriétés Physico-Chimiques de Dsup**

| Propriété | Valeur/Analyse | Source |
| :---- | :---- | :---- |
| Poids Moléculaire | $42.8$ kDa ($445$ résidus) | 15 |
| Point Isoélectrique (pI) | $10.56$ (Hautement basique) | 15 |
| Charge Nette | $+23$ à pH 7 | 15 |
| Composition SAGKT | $69.8 \\%$ (Sérine, Alanine, Glycine, Lysine, Thréonine) | 15 |
| Distance Intermoléculaire | $\\approx 4 \\, \\text{\\AA}$ (Liaison ADN) | 15 |

Le mécanisme d'action est double :

1. **Blindage Physique** : La flexibilité de l'IDP lui permet d'épouser la forme de l'ADN, créant une barrière contre les radicaux hydroxyles $\\text{OH}^\\bullet$ produits par la radiolyse de l'eau.4  
2. **Modulation de la Structure de l'ADN** : Dsup semble induire un léger désembobinage (unwinding) de la double hélice, ce qui pourrait modifier la susceptibilité chimique des bases azotées aux dommages radiatifs.58

#### **Les Protéines CAHS et l'Architecture de la Biostase**

Alors que Dsup protège le génome, les protéines CAHS (Cytoplasmic Abundant Heat Soluble) protègent le protéome et les membranes. Elles agissent comme des "couteaux suisses moléculaires".5

Cinétique de Gélification :  
À mesure que l'eau s'évapore, la concentration de CAHS D augmente. Au-delà du point de gélification ($\\approx 10$ mg/mL), les monomères en forme de haltères s'assemblent en dimères asymétriques via des interactions coiled-coil entre leurs segments hélicaux centraux.5 Ce réseau fibreux emprisonne les organites et les enzymes, agissant comme du "papier bulle moléculaire".36  
Vitrification vs Remplacement de l'Eau :  
Deux théories s'opposent historiquement pour expliquer la protection lors de la dessiccation :

* **Théorie du Remplacement de l'Eau** : Les sucres (tréhalose) forment des liaisons hydrogène avec les têtes polaires des phospholipides, maintenant l'espacement des membranes et empêchant leur fusion.60  
* **Théorie de la Vitrification** : La formation d'un verre biologique immobilise les molécules dans une matrice solide amorphe.7

Les recherches récentes sur les protéines CAHS suggèrent que ces deux mécanismes opèrent en synergie. Les IDPs vitrifient pour stopper la diffusion des radicaux, tandis qu'elles coordonnent les molécules d'eau résiduelles pour maintenir la structure tertiaire des protéines critiques.62

### **Technique de Mimétisme : Le Protocole deBlindage Biologique Canonique (PBBC)**

Afin d'utiliser ces découvertes, nous proposons une technique adaptable pour la protection de systèmes biologiques (cellules humaines) ou de matériaux synthétiques.

#### **Étape 1 : Fortification Génomique par Dsup Humanisé**

Le vecteur de protection est un ARNm modifié encapsulé dans des nanoparticules polymère-lipide.37

* **Séquence** : Utilisation d'un codon-optimisé Dsup- $\\Delta$C (pour minimiser l'agrégation non spécifique tout en conservant la liaison aux nucléosomes).15  
* **Administration** : 6 heures avant l'exposition radiative.39  
* **Efficacité attendue** : Réduction de $40-50\\%$ des cassures double-brin de l'ADN.38

#### **Étape 2 : Induction de la Biostase par Verres Biologiques Synthétiques**

Pour protéger les protéines circulantes (ex: facteurs de coagulation) ou les vaccins.

* **Formulation** : Mélange binaire de Tréhalose ($20\\%$ massique) et de peptides dérivés des motifs répétitifs des protéines CAHS ($LEA\\\_4$ motifs).59  
* **Propriétés** : Création d'un verre à haute $T\_g$ ($\> 80^\\circ\\text{C}$), même en présence de plastifiants résiduels.24  
* **Falsifiabilité** : Si le système dévie de la loi de Gordon-Taylor ou montre une cristallisation par DSC, la technique est invalidée.14

#### **Étape 3 : Barrières Photoniques Adaptatives (Mimétisme du Lichen)**

Développement de surfaces protectrices pour les habitats ou les combinaisons spatiales.

* **Matériau** : Matrice polymère transparente dopée avec des cristaux nanostructurés de pariétine ou des analogues de synthèse.10  
* **Configuration** : Structure poreuse mimant la médulle du lichen pour permettre les échanges gazeux tout en bloquant $99.9\\%$ des UV-C.41

### **Analyse de Stabilité et de SÉcurité (Validation Mathématique)**

La stabilité des protéines CAHS en phase gel est analysée via le critère de Lyapunov pour les réseaux de filaments. L'équilibre est atteint lorsque l'énergie libre de gélification $\\Delta G\_{gel}$ compense la pression osmotique de dessiccation $\\Pi\_{osm}$ :

$$\\Delta G\_{gel} \= \\Delta H\_{gel} \- T \\Delta S\_{gel} \\le \- \\Pi\_{osm} V\_m$$  
Où $V\_m$ est le volume molaire de l'eau expulsée. Les cas limites montrent que si $T \\rightarrow 0$ (froid spatial), le terme enthalpique domine, stabilisant le gel. Cependant, si $T \\rightarrow \\infty$, l'entropie favorise la dissociation du réseau, rendant le système vulnérable à la cristallisation dès que $T \> T\_g$.9

### **Implications Sociétales et Éthiques**

#### **Santé Publique et Oncologie**

Le transfert de la technologie Dsup vers la clinique pourrait révolutionner la radiothérapie. En augmentant sélectivement la tolérance des tissus sains, on pourrait administrer des doses de radiation plus létales aux tumeurs sans augmenter les effets secondaires dévastateurs.37

#### **Exploration Spatiale et Colonisation**

La capacité de créer des matériaux auto-réparateurs et radioprotecteurs à partir de ressources martiennes (biominéralisation fongique) réduit drastiquement les coûts de lancement. Cependant, l'introduction de gènes de tardigrades ou de champignons terrestres sur Mars pose des questions fondamentales de protection planétaire : risquons-nous de contaminer de façon irréversible une biosphère martienne potentielle?16

#### **Conservation de la Biodiversité**

La technique de vitrification inspirée des tardigrades offre un espoir pour les "bio-banques" d'espèces menacées, permettant de stocker des cellules germinales sans dépendre de l'azote liquide, rendant ces banques résilientes aux pannes d'énergie dans les régions instables.34

## **🚀 Perspectives et Directions de Recherche**

La prochaine frontière réside dans la compréhension de la "mémoire de forme moléculaire" des protéines désordonnées. Comment une cellule réhydratée après 30 ans de vide spatial peut-elle reprendre sa géométrie exacte et sa configuration de signalisation sans erreurs de transcription massives?36

L'étude du génome de *Xanthoria elegans* ($44.63$ Mb) et la recherche de clusters de gènes de biosynthèse de polykétides (PKS) pourraient révéler de nouveaux métabolites antioxydants encore plus puissants que la pariétine.67 Enfin, l'intégration de la biologie synthétique avec l'apprentissage machine permettra de concevoir des protéines de blindage *de novo* surpassant Dsup en termes de biocompatibilité humaine.

### ---

**Synthèse des Données Expérimentales Clés**

**Tableau 3: Comparaison de la Résistance aux Radiations Ionisantes**

| Organisme | Dose Létale (LD50) \[Gy\] | Mécanisme Principal | Source |
| :---- | :---- | :---- | :---- |
| Humain | $4 \- 5$ | Réparation ADN classique (NER/BER) | 6 |
| *Deinococcus radiodurans* | $5000$ | Reconstruction génomique rapide | 47 |
| *Xanthoria elegans* | $\> 12000$ (Photosynthèse) | Blindage cortical \+ Antioxydants | 16 |
| *Ramazzottius varieornatus* | $5000 \- 6200$ | Protéine Dsup \+ Vitrification | 6 |

**Tableau 4: Cinétique de Récupération après Exposition au Vide**

| Espèce | Durée Exposition | Temps de Récupération Métabolique | Indicateur |
| :---- | :---- | :---- | :---- |
| *X. elegans* | 16 jours (Foton-M2) | $\< 24$ heures | Fluorescence Chl a 1 |
| *A. fruticulosa* | 10 jours (Biopan-6) | $72$ heures | Respiration nette 69 |
| *X. elegans* | 18 mois (ISS) | $24 \- 48$ heures | Prolifération cellulaire 25 |
| *Tardigrade* (Tun) | 10 jours (Foton-M3) | $\< 24$ heures | Motilité et Reproduction 3 |

L'analyse démontre que la survie n'est pas une question de "résistance" au sens de rigidité, mais une question de "résilience" au sens de plasticité thermodynamique. Le passage contrôlé vers l'état vitreux et le blindage flou de la chromatine constituent le paradigme fondamental de la vie extra-planétaire.

## ---

**Fondements Théoriques de la Survie dans le Vide : Analyse en Premiers Principes**

La survie dans le vide spatial ne peut être comprise comme une simple extension de la tolérance à la sécheresse terrestre. Elle implique une réponse à trois contraintes physiques majeures : la vaporisation instantanée de l'eau libre, l'absence de convection thermique et l'exposition non filtrée aux protons et ions lourds.

### **I. La Contrainte de Vaporisation et l'Énergie Libre d'Hydratation**

Dans le vide ($P \\approx 10^{-7} \\, \\text{Pa}$), le point d'ébullition de l'eau est inférieur à la température physiologique. Sans mécanisme de protection, la cellule subit une lyse mécanique par expansion de vapeur.  
Les organismes anhydrobiotiques contournent ce problème en remplaçant les molécules d'eau de la couche d'hydratation des macromolécules par des solutés compatibles.  
La stabilité de la liaison est régie par l'enthalpie d'interaction $\\Delta H\_{int}$. Pour le tréhalose, cette interaction est favorisée car elle permet de maintenir la distance inter-lamellaire des membranes à une valeur constante $d\_c \\approx 20 \\, \\text{\\AA}$, évitant la phase de gel cristallin délétère.61

### **II. Le Blindage Radicaux-Libres : La Physique de la Quenching**

L'absence d'atmosphère signifie que les photons UV-C de haute énergie (100-280 nm) atteignent directement la surface biologique. Ces photons possèdent une énergie suffisante ($4.4$ à $12.4$ eV) pour rompre les liaisons $C-C$ et $C-N$.  
Le lichen utilise la pariétine comme un "puits d'excitation". Les électrons $\\pi$ du cycle anthraquinone absorbent le photon et dissipent l'énergie par relaxation vibratoire non radiative (chaleur) ou par fluorescence à $434$ nm, évitant la formation de radicaux $\\text{OH}^\\bullet$ dans la couche de photobiontes.11

### **III. La Vitrification comme État de Pause Temporelle**

D'un point de vue de la physique statistique, la vitrification transforme le cytoplasme en un milieu "verré" où le temps de relaxation moléculaire $\\tau\_{rel}$ dépasse largement la durée de la mission spatiale.

$$\\tau\_{rel} \= \\tau\_0 \\exp\\left(\\frac{B}{T \- T\_0}\\right)$$

(Équation de Vogel-Fulcher-Tammann)  
Près de $T\_g$, $\\tau\_{rel}$ tend vers l'infini, ce qui signifie que même si une protéine "souhaite" s'agréger, la probabilité de collision efficace est nulle sur des décennies.36 C'est ce mécanisme qui permet au tardigrade de rester en stasis pendant 30 ans et de "ressusciter" intact.36

### **IV. Conclusion sur la Technique Adaptable**

La technique de mimétisme proposée, le SVSPD (Système de Vitrification Synthétique par Protéines Désordonnées), doit être vue comme une manipulation de la topologie de l'espace des phases cellulaire. En forçant le système vers un attracteur de basse énergie (l'état vitreux), on rend la vie indépendante du flux temporel et des agressions environnementales externes, créant un véritable "vaisseau spatial moléculaire" pour l'information génétique.

Les perspectives futures suggèrent que le mimétisme ne doit pas s'arrêter aux gènes existants. En utilisant des outils de conception computationnelle (comme AlphaFold 3.0), nous pouvons désormais créer des IDPs "super-fortes" avec des $T\_g$ encore plus élevées et des capacités de liaison à l'ADN optimisées pour le génome humain, ouvrant la porte à une ère de biologie interstellaire souveraine.72

#### **Sources des citations**

1. (PDF) Lichens survive in space: Results from the 2005 LICHENS experiment, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/6207118\_Lichens\_survive\_in\_space\_Results\_from\_the\_2005\_LICHENS\_experiment](https://www.researchgate.net/publication/6207118_Lichens_survive_in_space_Results_from_the_2005_LICHENS_experiment)  
2. Lichen survives in space \- ESA, consulté le janvier 16, 2026, [https://www.esa.int/Science\_Exploration/Human\_and\_Robotic\_Exploration/Lichen\_survives\_in\_space](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/Lichen_survives_in_space)  
3. Tiny animals survive exposure to space \- ESA, consulté le janvier 16, 2026, [https://www.esa.int/Science\_Exploration/Human\_and\_Robotic\_Exploration/Research/Tiny\_animals\_survive\_exposure\_to\_space](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/Research/Tiny_animals_survive_exposure_to_space)  
4. The tardigrade damage suppressor protein binds to nucleosomes and protects DNA from hydroxyl radicals | eLife, consulté le janvier 16, 2026, [https://elifesciences.org/articles/47682](https://elifesciences.org/articles/47682)  
5. A phase transition modulates the protective function of a tardigrade disordered protein during desiccation \- PMC \- NIH, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12432419/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12432419/)  
6. Radioprotection redefined: drug discovery at the intersection of ..., consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12669191/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12669191/)  
7. Vitrification is essential for anhydrobiosis in an African chironomid, Polypedilum vanderplanki \- PMC \- PubMed Central, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC2278217/](https://pmc.ncbi.nlm.nih.gov/articles/PMC2278217/)  
8. Deciphering the Biological Enigma—Genomic Evolution Underlying Anhydrobiosis in the Phylum Tardigrada and the Chironomid Polypedilum vanderplanki \- MDPI, consulté le janvier 16, 2026, [https://www.mdpi.com/2075-4450/13/6/557](https://www.mdpi.com/2075-4450/13/6/557)  
9. Thermodynamic aspects of vitrification \- 21st Century Medicine, consulté le janvier 16, 2026, [https://www.21cm.com/pdfs/2010-Thermodynamics.pdf](https://www.21cm.com/pdfs/2010-Thermodynamics.pdf)  
10. Solar radiation screening in usnic acid-containing cortices of the lichen Nephroma arcticum | Request PDF \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/283857812\_Solar\_radiation\_screening\_in\_usnic\_acid-containing\_cortices\_of\_the\_lichen\_Nephroma\_arcticum](https://www.researchgate.net/publication/283857812_Solar_radiation_screening_in_usnic_acid-containing_cortices_of_the_lichen_Nephroma_arcticum)  
11. Light screening in lichen cortices can be quantified by chlorophyll fluorescence techniques for both reflecting and absorbing pigments \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/41410142\_Light\_screening\_in\_lichen\_cortices\_can\_be\_quantified\_by\_chlorophyll\_fluorescence\_techniques\_for\_both\_reflecting\_and\_absorbing\_pigments](https://www.researchgate.net/publication/41410142_Light_screening_in_lichen_cortices_can_be_quantified_by_chlorophyll_fluorescence_techniques_for_both_reflecting_and_absorbing_pigments)  
12. Study the Effects of Water Content on CAHS Proteins and its Vitrified Characteristics \- INTERNATIONAL JOURNAL OF, consulté le janvier 16, 2026, [https://www.ijmrset.com/upload/15\_Study\_NC.pdf](https://www.ijmrset.com/upload/15_Study_NC.pdf)  
13. Protecting Proteins from Desiccation Stress Using Molecular Glasses and Gels \- PMC, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11082905/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11082905/)  
14. Gordon-Taylor and Fox Equations for Glass Transition Temperature | Wolfram Demonstrations Project, consulté le janvier 16, 2026, [https://demonstrations.wolfram.com/GordonTaylorAndFoxEquationsForGlassTransitionTemperature/](https://demonstrations.wolfram.com/GordonTaylorAndFoxEquationsForGlassTransitionTemperature/)  
15. Structural study of the intrinsically disordered tardigrade damage suppressor protein (Dsup) and its complex with DNA \- PubMed Central, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11447161/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11447161/)  
16. ESA \- Live long and prosper, *Xanthoria elegans* \- European Space Agency, consulté le janvier 16, 2026, [https://www.esa.int/Science\_Exploration/Human\_and\_Robotic\_Exploration/Columbus/Live\_long\_and\_prosper\_i\_Xanthoria\_elegans\_i](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/Columbus/Live_long_and_prosper_i_Xanthoria_elegans_i)  
17. Tardigrades use intrinsically disordered proteins to survive ..., consulté le janvier 16, 2026, [https://www.researchgate.net/publication/329833188\_Tardigrades\_use\_intrinsically\_disordered\_proteins\_to\_survive\_desiccation](https://www.researchgate.net/publication/329833188_Tardigrades_use_intrinsically_disordered_proteins_to_survive_desiccation)  
18. Labile assembly of a tardigrade protein induces biostasis \- PMC \- NIH, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10949331/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10949331/)  
19. Structural study of the intrinsically disordered tardigrade damage suppressor protein (Dsup) and its complex with DNA \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/384573138\_Structural\_study\_of\_the\_intrinsically\_disordered\_tardigrade\_damage\_suppressor\_protein\_Dsup\_and\_its\_complex\_with\_DNA](https://www.researchgate.net/publication/384573138_Structural_study_of_the_intrinsically_disordered_tardigrade_damage_suppressor_protein_Dsup_and_its_complex_with_DNA)  
20. Vitrification is essential for anhydrobiosis in an African chironomid, Polypedilum vanderplanki \- PubMed, consulté le janvier 16, 2026, [https://pubmed.ncbi.nlm.nih.gov/18362351/](https://pubmed.ncbi.nlm.nih.gov/18362351/)  
21. Tardigrade Dsup: Interactions with DNA and protection of cells from oxidative stress, consulté le janvier 16, 2026, [https://www.biorxiv.org/content/10.1101/2024.11.06.622393v1.full-text](https://www.biorxiv.org/content/10.1101/2024.11.06.622393v1.full-text)  
22. Captain Tardigrade and Its Shield to Protect DNA \- MDPI, consulté le janvier 16, 2026, [https://www.mdpi.com/2673-8856/5/2/27](https://www.mdpi.com/2673-8856/5/2/27)  
23. Water content, transition temperature and fragility influence protection and anhydrobiotic capacity | bioRxiv, consulté le janvier 16, 2026, [https://www.biorxiv.org/content/10.1101/2023.06.30.547256v2.full-text](https://www.biorxiv.org/content/10.1101/2023.06.30.547256v2.full-text)  
24. The role of vitrification in anhydrobiosis \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/13722805\_The\_role\_of\_vitrification\_in\_anhydrobiosis](https://www.researchgate.net/publication/13722805_The_role_of_vitrification_in_anhydrobiosis)  
25. Viability of the lichen Xanthoria elegans and its symbionts after 18 months of space exposure and simulated Mars conditions on the ISS | International Journal of Astrobiology, consulté le janvier 16, 2026, [https://www.cambridge.org/core/journals/international-journal-of-astrobiology/article/viability-of-the-lichen-xanthoria-elegans-and-its-symbionts-after-18-months-of-space-exposure-and-simulated-mars-conditions-on-the-iss/6063CBD82A3DE50340680EC6450ACAC6](https://www.cambridge.org/core/journals/international-journal-of-astrobiology/article/viability-of-the-lichen-xanthoria-elegans-and-its-symbionts-after-18-months-of-space-exposure-and-simulated-mars-conditions-on-the-iss/6063CBD82A3DE50340680EC6450ACAC6)  
26. Survivability of the lichen Xanthoria parietina in simulated Martian environmental conditions \- PMC \- PubMed Central, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10039903/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10039903/)  
27. Vitrification is essential for anhydrobiosis in an African chironomid, Polypedilum vanderplanki | PNAS, consulté le janvier 16, 2026, [https://www.pnas.org/doi/10.1073/pnas.0706197105](https://www.pnas.org/doi/10.1073/pnas.0706197105)  
28. Tardigrade protein may help protect cancer patients from radiation side effects, consulté le janvier 16, 2026, [https://radiationoncology.medicine.uiowa.edu/newsarchive/2025/02/tardigrade-protein-may-help-protect-cancer-patients-radiation-side-effects](https://radiationoncology.medicine.uiowa.edu/newsarchive/2025/02/tardigrade-protein-may-help-protect-cancer-patients-radiation-side-effects)  
29. DNA Protection Protein, a Novel Mechanism of Radiation Tolerance: Lessons from Tardigrades \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/317608958\_DNA\_Protection\_Protein\_a\_Novel\_Mechanism\_of\_Radiation\_Tolerance\_Lessons\_from\_Tardigrades](https://www.researchgate.net/publication/317608958_DNA_Protection_Protein_a_Novel_Mechanism_of_Radiation_Tolerance_Lessons_from_Tardigrades)  
30. Comparative transcriptomics reveal a novel tardigrade specific DNA binding protein induced in response to ionizing radiation \- eLife, consulté le janvier 16, 2026, [https://elifesciences.org/reviewed-preprints/92621v2/pdf](https://elifesciences.org/reviewed-preprints/92621v2/pdf)  
31. UV photo-degradation of the secondary lichen substance parietin \- FLORE, consulté le janvier 16, 2026, [https://flore.unifi.it/retrieve/0caaae36-c44b-4774-8272-236d986eb434/Lorenz%20et%20al.%2C%202024.pdf](https://flore.unifi.it/retrieve/0caaae36-c44b-4774-8272-236d986eb434/Lorenz%20et%20al.%2C%202024.pdf)  
32. UV photo-degradation of the secondary lichen substance parietin: A multi-spectroscopic analysis in astrobiology perspective \- PubMed, consulté le janvier 16, 2026, [https://pubmed.ncbi.nlm.nih.gov/38670647/](https://pubmed.ncbi.nlm.nih.gov/38670647/)  
33. UV Photo-degradation of the Secondary Lichen Substance Parietin: A Multi-spectroscopic Analysis in Astrobiology Perspective, consulté le janvier 16, 2026, [https://astrobiology.com/2024/05/uv-photo-degradation-of-the-secondary-lichen-substance-parietin-a-multi-spectroscopic-analysis-in-astrobiology-perspective.html](https://astrobiology.com/2024/05/uv-photo-degradation-of-the-secondary-lichen-substance-parietin-a-multi-spectroscopic-analysis-in-astrobiology-perspective.html)  
34. The Year in Biomimicry: Mussels, Elephants, Water Bears & More... \- Trellis Group, consulté le janvier 16, 2026, [https://trellis.net/article/year-biomimicry-mussels-elephants-water-bears-more/](https://trellis.net/article/year-biomimicry-mussels-elephants-water-bears-more/)  
35. Trehalose and Trehalose-based Polymers for Environmentally Benign, Biocompatible and Bioactive Materials \- PMC \- NIH, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC6245314/](https://pmc.ncbi.nlm.nih.gov/articles/PMC6245314/)  
36. Tardigrade: the incredible and tiny Terminator of the living \- Bioxegy, consulté le janvier 16, 2026, [https://en.bioxegy.com/post/tardigrade-the-incredible-and-tiny-terminator-of-the-living](https://en.bioxegy.com/post/tardigrade-the-incredible-and-tiny-terminator-of-the-living)  
37. Tardigrade Protein Shields Mouse Cells from Radiation | The Scientist, consulté le janvier 16, 2026, [https://www.the-scientist.com/tardigrade-protein-shields-mouse-cells-from-radiation-72747](https://www.the-scientist.com/tardigrade-protein-shields-mouse-cells-from-radiation-72747)  
38. A protein from tiny tardigrades may help cancer patients tolerate radiation therapy | MIT News | Massachusetts Institute of Technology, consulté le janvier 16, 2026, [https://news.mit.edu/2025/tiny-tardigrades-protein-may-help-cancer-patients-tolerate-radiation-therapy-0226](https://news.mit.edu/2025/tiny-tardigrades-protein-may-help-cancer-patients-tolerate-radiation-therapy-0226)  
39. Tiny tardigrades may hold clues to cancer care | National Institutes of Health (NIH), consulté le janvier 16, 2026, [https://www.nih.gov/news-events/nih-research-matters/tiny-tardigrades-may-hold-clues-cancer-care](https://www.nih.gov/news-events/nih-research-matters/tiny-tardigrades-may-hold-clues-cancer-care)  
40. The Tardigrade damage suppressor protein Dsup promotes DNA damage in neurons \- PMC, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10247392/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10247392/)  
41. 3D printing and synthetic lichens for self-growing Mars habitats | VoxelMatters, consulté le janvier 16, 2026, [https://www.voxelmatters.com/3d-printing-synthetic-lichens-self-growing-mars-habitats/](https://www.voxelmatters.com/3d-printing-synthetic-lichens-self-growing-mars-habitats/)  
42. Lichenized Biosystems \- Pratt Institute, consulté le janvier 16, 2026, [https://www.pratt.edu/work/lichenized-biosystems/](https://www.pratt.edu/work/lichenized-biosystems/)  
43. Motility-driven glass and jamming transitions in biological tissues \- PMC \- NIH, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC5619672/](https://pmc.ncbi.nlm.nih.gov/articles/PMC5619672/)  
44. Desert Lichen Offers New Evidence for the Possibility of Life on Other Planets \- DRI, consulté le janvier 16, 2026, [https://www.dri.edu/desert-lichen-offers-new-evidence-for-the-possibility-of-life-on-other-planets/](https://www.dri.edu/desert-lichen-offers-new-evidence-for-the-possibility-of-life-on-other-planets/)  
45. How does life handle the harshness of space? \- Sciworthy, consulté le janvier 16, 2026, [https://sciworthy.com/how-does-life-handle-the-harshness-of-space/](https://sciworthy.com/how-does-life-handle-the-harshness-of-space/)  
46. Investigating the Cytoprotective Mechanisms of the Tardigrade Damage Suppressor (Dsup) Protein in Human Cells Under Hypoxic Stress \- MDPI, consulté le janvier 16, 2026, [https://www.mdpi.com/1422-0067/26/21/10452](https://www.mdpi.com/1422-0067/26/21/10452)  
47. Survival of lichens and bacteria exposed to outer space conditions \- Results of the Lithopanspermia experiments | Request PDF \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/225005434\_Survival\_of\_lichens\_and\_bacteria\_exposed\_to\_outer\_space\_conditions\_-\_Results\_of\_the\_Lithopanspermia\_experiments](https://www.researchgate.net/publication/225005434_Survival_of_lichens_and_bacteria_exposed_to_outer_space_conditions_-_Results_of_the_Lithopanspermia_experiments)  
48. By studying new species of tardigrade, researchers glean insights into radiation tolerance, consulté le janvier 16, 2026, [https://www.eurekalert.org/news-releases/1061934](https://www.eurekalert.org/news-releases/1061934)  
49. Study reveals how tardigrades can endure radiation levels \- Tech Explorist, consulté le janvier 16, 2026, [https://www.techexplorist.com/tardigrades-endure-radiation-levels/91975/](https://www.techexplorist.com/tardigrades-endure-radiation-levels/91975/)  
50. Cross-species radioprotection: insights from tardigrade multi-omics | Radiation Medicine and Protection \- MedNexus, consulté le janvier 16, 2026, [https://mednexus.org/doi/10.1016/j.radmp.2025.12.002](https://mednexus.org/doi/10.1016/j.radmp.2025.12.002)  
51. Tardigrades' Shield Against DNA Damage Inspires New Therapies | The Scientist, consulté le janvier 16, 2026, [https://www.the-scientist.com/tardigrades-shield-against-dna-damage-inspires-new-therapies-73714](https://www.the-scientist.com/tardigrades-shield-against-dna-damage-inspires-new-therapies-73714)  
52. Tardigrades Have a Genetic Secret, And It Could Boost Human Resilience \- Science Alert, consulté le janvier 16, 2026, [https://www.sciencealert.com/tardigrades-have-a-genetic-secret-and-it-could-boost-human-resilience](https://www.sciencealert.com/tardigrades-have-a-genetic-secret-and-it-could-boost-human-resilience)  
53. Lichens... In... Space... \- The Scientist, consulté le janvier 16, 2026, [https://www.the-scientist.com/lichens-in-space-48152](https://www.the-scientist.com/lichens-in-space-48152)  
54. The Roles of the Anthraquinone Parietin in the Tolerance to Desiccation of the Lichen Xanthoria parietina: Physiology and Anatomy of the Pale and Bright-Orange Thalli \- MDPI, consulté le janvier 16, 2026, [https://www.mdpi.com/1422-0067/25/13/7067](https://www.mdpi.com/1422-0067/25/13/7067)  
55. (PDF) The Role of Ultraviolet Radiation in Regulating Certain Physiological and Biochemical Processes in the Lichens Xanthoria candelaria (L.) Th.Fr. and Xanthoria elegans (L.) Th.Fr \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/395967560\_The\_Role\_of\_Ultraviolet\_Radiation\_in\_Regulating\_Certain\_Physiological\_and\_Biochemical\_Processes\_in\_the\_Lichens\_Xanthoria\_candelaria\_L\_ThFr\_and\_Xanthoria\_elegans\_L\_ThFr](https://www.researchgate.net/publication/395967560_The_Role_of_Ultraviolet_Radiation_in_Regulating_Certain_Physiological_and_Biochemical_Processes_in_the_Lichens_Xanthoria_candelaria_L_ThFr_and_Xanthoria_elegans_L_ThFr)  
56. Dsup \- Wikipedia, consulté le janvier 16, 2026, [https://en.wikipedia.org/wiki/Dsup](https://en.wikipedia.org/wiki/Dsup)  
57. DNA Protection Protein, a Novel Mechanism of Radiation Tolerance: Lessons from Tardigrades \- PMC \- NIH, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC5492148/](https://pmc.ncbi.nlm.nih.gov/articles/PMC5492148/)  
58. Biochemical and Structural Analyses of the Tardigrade DNA-Damage Suppressor Protein, Dsup \- PubMed, consulté le janvier 16, 2026, [https://pubmed.ncbi.nlm.nih.gov/41115570/](https://pubmed.ncbi.nlm.nih.gov/41115570/)  
59. Tardigrade CAHS Proteins Act as Molecular Swiss Army Knives to Mediate Desiccation Tolerance Through Multiple Mechanisms \- OUCI, consulté le janvier 16, 2026, [https://ouci.dntb.gov.ua/en/works/4N2knGO4/](https://ouci.dntb.gov.ua/en/works/4N2knGO4/)  
60. The role of vitrification in anhydrobiosis \- PubMed, consulté le janvier 16, 2026, [https://pubmed.ncbi.nlm.nih.gov/9558455/](https://pubmed.ncbi.nlm.nih.gov/9558455/)  
61. Water Replacement Hypothesis in Atomic Detail—Factors Determining the Structure of Dehydrated Bilayer Stacks | Request PDF \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/26683189\_Water\_Replacement\_Hypothesis\_in\_Atomic\_Detail-Factors\_Determining\_the\_Structure\_of\_Dehydrated\_Bilayer\_Stacks](https://www.researchgate.net/publication/26683189_Water_Replacement_Hypothesis_in_Atomic_Detail-Factors_Determining_the_Structure_of_Dehydrated_Bilayer_Stacks)  
62. The tardigrade protein CAHS D interacts with, but does not retain, water in hydrated and desiccated systems \- NIH, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10300006/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10300006/)  
63. (PDF) The tardigrade protein CAHS D interacts with, but does not retain, water in hydrated and desiccated systems \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/371908914\_The\_tardigrade\_protein\_CAHS\_D\_interacts\_with\_but\_does\_not\_retain\_water\_in\_hydrated\_and\_desiccated\_systems](https://www.researchgate.net/publication/371908914_The_tardigrade_protein_CAHS_D_interacts_with_but_does_not_retain_water_in_hydrated_and_desiccated_systems)  
64. Trehalose and anhydrobiosis in tardigrades \- Evidence for divergence in responses to dehydration | Request PDF \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/5778471\_Trehalose\_and\_anhydrobiosis\_in\_tardigrades\_-\_Evidence\_for\_divergence\_in\_responses\_to\_dehydration](https://www.researchgate.net/publication/5778471_Trehalose_and_anhydrobiosis_in_tardigrades_-_Evidence_for_divergence_in_responses_to_dehydration)  
65. The amorphous state: first-principles derivation of the Gordon-Taylor ..., consulté le janvier 16, 2026, [https://pubmed.ncbi.nlm.nih.gov/28730199/](https://pubmed.ncbi.nlm.nih.gov/28730199/)  
66. Tardigrades in Space Research \- Past and Future \- PMC \- NIH, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC5705745/](https://pmc.ncbi.nlm.nih.gov/articles/PMC5705745/)  
67. Is parietin a UV-B or a blue-light screening pigment in the lichen Xanthoria parietina? | Request PDF \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/10748012\_Is\_parietin\_a\_UV-B\_or\_a\_blue-light\_screening\_pigment\_in\_the\_lichen\_Xanthoria\_parietina](https://www.researchgate.net/publication/10748012_Is_parietin_a_UV-B_or_a_blue-light_screening_pigment_in_the_lichen_Xanthoria_parietina)  
68. Plantwatch: the strange organism so tough it can survive in space | Plants \- The Guardian, consulté le janvier 16, 2026, [https://www.theguardian.com/science/2024/jan/17/plantwatch-the-strange-organism-so-tough-it-can-survive-in-space](https://www.theguardian.com/science/2024/jan/17/plantwatch-the-strange-organism-so-tough-it-can-survive-in-space)  
69. Whole Lichen Thalli Survive Exposure to Space Conditions: Results of Lithopanspermia Experiment with Aspicilia fruticulosa \- ResearchGate, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/51100875\_Whole\_Lichen\_Thalli\_Survive\_Exposure\_to\_Space\_Conditions\_Results\_of\_Lithopanspermia\_Experiment\_with\_Aspicilia\_fruticulosa](https://www.researchgate.net/publication/51100875_Whole_Lichen_Thalli_Survive_Exposure_to_Space_Conditions_Results_of_Lithopanspermia_Experiment_with_Aspicilia_fruticulosa)  
70. Water Replacement Hypothesis in Atomic Detail—Factors Determining the Structure of Dehydrated Bilayer Stacks \- NIH, consulté le janvier 16, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC2711319/](https://pmc.ncbi.nlm.nih.gov/articles/PMC2711319/)  
71. Parietin, a photoprotective secondary product of the lichen Xanthoria parietina, consulté le janvier 16, 2026, [https://www.researchgate.net/publication/226579510\_Parietin\_a\_photoprotective\_secondary\_product\_of\_the\_lichen\_Xanthoria\_parietina](https://www.researchgate.net/publication/226579510_Parietin_a_photoprotective_secondary_product_of_the_lichen_Xanthoria_parietina)  
72. Mechanistic Insight of Tardigrade Anhydrobiosis via Protein Structural Analysis \- bioRxiv, consulté le janvier 16, 2026, [https://www.biorxiv.org/content/10.1101/2025.04.14.648834v1.full-text](https://www.biorxiv.org/content/10.1101/2025.04.14.648834v1.full-text)