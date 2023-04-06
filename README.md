# FuseeAAir
Sources matérielles et pédagogiques autour des fusées à air utilisées à Planète Sciences Occitanie
![](ImagesRampes/LogoPSOC.jpg)

![](./assets/Pictures/1000000000000A2000001200BF33EDC3F166AD6B.jpg){width="10.188cm" height="18.113cm"}

# []{#anchor}Notes de versions. 

Attention, les versions citées sont celles des versions matérielles, non pas celles du présent document, lui-même bien moins souvent mis à jour que le matériel.

-   V1 Base initiale dont le réservoir d'air est constitué d'un tube PVC pour conduite d'eau pression (genre piscine) diamètre 90 (à vérifier) , d'un raccord en T et divers raccords et bouchons. A été reproduit en quelques exemplaires, mais chaque fois avec des fuites sans possibilité de rattrapage parce que non-démontable.

-   V2 Version dont le réservoir est constitué d'un raccord femelle-femelle diamètre 100, d'un tampon de visite et de divers raccord. Présente l'avantage d'être démontable pour rattraper les mauvais collages, mais nous avons eu des explosions lors d'animations.

-   V3 Version dont le réservoir est constitué d'un vase d'expansion vendu garanti pour 10 bars.

    -   V 3.0 Version initiale. Le support bois découpé laser consomme 4 planches 300\*600 e10.
    -   V 3.1 Support bois à flancs ajourés sur 2 planches.
    -   V3.2 Divers ajustements sur le support. Quelques problèmes récurrents d'introduction en travers des raccords métal/plastique.
    -   V 3.3 Utilisation d'un T 1 pouce au lieu de 3/4 de pouce, ce qui permet de limiter les destructions de filetages plastique, en particulier au niveau de l'électro-vanne. Ajustement du support.
    -   V 3.4 Ajustement du support.
    -   V3.5 Version de travail du document de fabrication intermédiaire
    -   V3.6 Mise au propre des documents pour publication sur https://github.com/PSOC-31

# 

# []{#anchor-1}Inventaire des éléments

  ---------------------------------------------------------------------------- ----------------------------------------- --------------------- ----------------- ------ ------- -------
  Electro vanne                                                                1\" FF JTV 9V RBIRD                       IrriJardin            421020            1      49,99   54,42
  Vase d'expension Gitral HY5                                                  Partedis                                  Partedis              17119             1      54,42   54,42
  Tube renforcé 7\*13                                                          rlx 25m pvc tresse 7\*13                  CIR                   1025V130007       5      45,72   9,14
  Té laiton FFF 26X34 1pouce                                                                                             Partedis              29407             1      8,3     8,3
  Réduction laiton MF 6 pans JT plat 26-20                                                                               Partedis              68472             1      2,54    2,54
  Réduction laiton MF 6 pans JT plat 26-15                                                                               Partedis              68467             1      3,91    3,91
  Réduction laiton MF 6 pans JT plat 15-8                                                                                Partedis              68320             1      1,06    1,06
  Mamelon MM 6 pans plastique 1pouce                                                                                     IrriJardin            181755            1      5       5
  Tétine (à refaire)                                                           douille cann male co.gaz                  CIR                   1230717           1      5,55    5,55
  Collier                                                                      6 colliersgalva 9-16 sachet l8mm          Leroy Merlin Balma    h 80153727        2      3,25    1,08
  Pompe a pied 500                                                             Pompe a pied 500                          Decatlon escalquens   1829519           1      16      16
  Valve pour roue voiture                                                                                                Feu Vert                                1      0       0
  Raccord fileté PVC                                                           Raccord fil Pvc M32 F25 26\*34            IrriJardin            120639            1      3,4     3,4
  Tube IRO                                                                     Tube tulipe irl lm d25mm gris 2.5m        Leroy Merlin Balma    h3447640069375    0,35   1,35    0,19
  Tampon de visite d40                                                         bouchon D40                               Leroy Merlin Balma    h 3343340668804   2      0,65    1,3
  Manchon ff d40                                                               Manchon ff d40                            Leroy Merlin Balma    h 3343340465205   2      0,25    0,5
  Tube écoulement d40                                                                                                    Leroy Merlin Balma                      2      0,15    0,15
  Fil électrique double conducteur, double isolation, souple.                                                                                                    6              0
  Connecteur pile 9V                                                                                                                                             1              0
  Interrupteur à bascule marche-arrêt 12mm avec couvercle de protection 1021   AliExpress                                088 electric Store                      1      1,89    1,89
  Pile 9V                                                                                                                Opitec                                  1      20,99   2,1
  Planche CTP 10 mm 300\*600                                                   FabRiquet                                                                         2      10      20
  Découpe laser                                                                FabRiquet                                                                         0,33   40      13,2
  Tige filetée M10                                                                                                       Castorama                               0,25   1,9     0,48
  Ecrou façon rondelle M10                                                     Ecrou emb. Crantée din -çé » ZG M10 X25   Bricoman                                4      5       0,8
  Rondelle large 10                                                            Rondelles extralarge ZG D10X36X2 X25      Bricoman                                4      3,58    0,57
  Ecrou papillon                                                                                                                                                 4      1,09    1,09
                                                                                                                                                                                
  Total                                                                                                                                                                         207,1
  ---------------------------------------------------------------------------- ----------------------------------------- --------------------- ----------------- ------ ------- -------

# 

# Montage de la chambre de pression.

La chambre de pression est le volume d'air immédiatement à l'arrière de l'électrovanne. C'est le vase d'expansion, les divers raccords et le tuyau de gonflage qui sont sous pression, dans l'attente du lancement.

La première étape consiste a assembler entre eux les éléments de la chambre de pression afin qu'il ne forme qu'un seul élément.

## Généralités sur l'étanchéité.

L'ensemble des parties sous pression devront supporter plusieurs bars. L'étanchéité du montage des raccords est donc primordial. D'une façon générale, l'utilisation de joints est largement recommandé, mais pour cela il est nécessaire qu'une surface d'appui existe, ce qui n'est pas le cas dans l'ensemble des objets choisi. Après avoir essayé diverses solutions, de la pâte spécialisée au fil imprégné, ma préférence personnelle reste au ruban PTFE (Téflon, antonomase). Je recommande sur un montage métal-métal de faire au moins une dizaine de tours, dans le sens du dévissage pour éviter le déroulement lors de l'introduction. Si lors des essais en pression dans un bac d'eau, on voit apparaître des fuites, on peu démonter le raccord et ajouter des tours supplémentaires. Sur un raccord plastique-métal ou plastique-plastique, il faut généralement moins de tours.

Attention au début du vissage, on part très vite en travers, surtout dans les montages métal-plastique, et on a tendance à flinguer la partie plastique. Je recommande, lors de la pose du ruban PTFE, d'épargner les premiers millimètres. Ça aide à une introduction correcte.

## Montage des raccords.

-   Monter sur la partie pe![](./assets/Pictures/100000000000120000000A201FF5C98A7CA0C93A.jpg){width="12.264cm" height="6.899cm"}rpendiculaire du raccord en T femelle/femelle/femelle 1 pouce (26X34), la réduction mâle-femelle 26-15.
-   Sur cette même réduction, monter une tétine mâle XXX pour tuyau 7\*13.
-   Sur une branche du T, monter un mamelon double mâle-mâle 1 pouce (26X34) en plastique.
-   Sur ce mamelon, monter l'électrovanne, coté entrée (empennage de la flèche sur l'électrovanne).
-   De l'autre coté de ce mamelon, en face sur l'autre branche du T, visser une réduction femelle-femelle 26-20.
-   Dans ce dernier mamelon, visser le vase d'expansion 5 litres.

# []{#anchor-2}Montage de la ligne de gonflage.

Voir le document commun pour les rampes fusée à eau et rampes fusée à air « Fabrication de la ligne de gonflage pour Bases de lancement Fusées à Air et Fusées à Eau. V1.1 »

# Montage de la commande de l'électrovanne.

Il y a plusieurs types d'électrovannes. Certaines sont nominalement alimentées en 24V. Je suppose que c'est pour se prémunir contre les possibles pertes en lignes dues à de très longs câblages dans un champ. Pour une utilisation à notre pression, avec de l'air et avec un câblage soigné, une tension nominale de 9V est suffisante. Cependant, je recommande l'utilisation de piles alcalines.

![](./assets/Pictures/1000000000000109000001D6B16CA39BC4EA84B0.jpg){width="3.57cm" height="6.313cm"}

Le boîtier de commande est un assemblage de tubes d'écoulement d'eau de diamètre 40.

Poncez-collez deux manchons femelle/femelle sur une longueur de tube de 60 mm. Au extrémités des manchons, collez les tampons de visite en ayant préalablement dévissé les bouchons des tampons.![](./assets/Pictures/1000000000000A20000012008A9F51622785CF56.jpg){width="2.9cm" height="5.154cm"}

Percez et usinez les bouchons pour, d'un coté, placer l'interrupteur,

![](./assets/Pictures/1000000000000A200000120069481E8F2CB96162.jpg){width="3.718cm" height="6.609cm"} de l'autre pour faire passer un câble électrique type double conducteur, double isolation, souple, de 6 mètres.

![](./assets/Pictures/1000000000000087000000EF4C38F23DFB7A1FEC.jpg){width="3.582cm" height="6.336cm"}Taillez un bout de polystyrène extrudé ou de la mousse un peu dure, diamètre 30, épaisseur 20, pour caler la pile 9V.

![](./assets/Pictures/10000000000001CA000001034FA7C422806491F8.jpg){width="6.932cm" height="3.919cm"}

Montez et câblez un interrupteur sur un bouchon de tampon. Vissez ce bouchon et câblez le connecteur de pile et le câble secteur. Bien sûr, vous n'avez pas oublié de faire passer ce câble dans le trou de l'autre bouchon!

![](./assets/Pictures/100000000000006B000000BF00B170B81C33D0AC.jpg){width="2.854cm" height="5.048cm"}![](./assets/Pictures/100000000000006A000000BD7DFC5B5936A8E1A3.jpg){width="2.824cm" height="4.995cm"}![](./assets/Pictures/100000000000006C000000BF1EE38344B79F5540.jpg){width="2.861cm" height="5.061cm"}![](./assets/Pictures/100000000000006E000000C292477F65A4B31EF9.jpg){width="2.919cm" height="5.163cm"}![](./assets/Pictures/1000000000000930000010401AC2FF3374275BB6.jpg){width="2.912cm" height="5.151cm"}Glissez d'abord la cale en polystyrène, puis la pile connectée. Placez un collier de serrage plastique (Rislan ou Colson, antonomase ) sur le câble, et serrez bien. Vissez le bouchon en faisant quelques tours en arrière avant de visser (pour éviter d'avoir un câble vrillé à l'intérieur).

![](./assets/Pictures/10000000000000EB0000009CA299E6215BB7E979.jpg){width="6.227cm" height="4.15cm"}Connectez l'électrovanne à l'autre extrémité en soudant et utilisant de la gaine gaine thermo-rétractable et thermo-collante.

Fixez le![](./assets/Pictures/1000000000000A2000001200F9C16F9CC16F3A00.jpg){width="3.614cm" height="6.426cm"} câble à l'électro-vanne avec un collier de serrage plastique (Rislan ou Colson, antonomase ).

# 

# Configuration du vase d'expansion.

Le vase d'expansion est prévu pour permettre une dilatation de l'eau dans un circuit (cas de la partie chaude de l'eau sanitaire), sans mettre en contact l'eau avec l'air pour limiter l'oxydation des parties métalliques. Par construction, il existe une chambre à air intégrée dans le vase, gonflé à 2 bars. Pour notre utilisation, il est nécessaire de dégonfler entièrement cette chambre pour profiter de la vitesse maximum d'éjection de l'air. Donc, dans un premier temps, on va dévisser le protége-cul du vase, et appuyer avec un objet quelconque sur la valve pour dégonfler.

Photo à venir.

Ensuite, pressuriser avec la pompe à vélo le circuit principal (dans le vase, pour chasser le reste d'air de la chambre) et recommencer à appuyer sur la valve. Refaire 2 ou 3 fois cette opération pour vider complètement la chambre.

# Tests de l'ensemble.

Testez le montage en plongeant l'ensemble sous pression (2 bars mini) dans l'eau. N'oubliez pas de tester les deux extrémités du tuyau d'air.

Pour les raccords filetés, voir note «Généralités sur l'étanchéité» en début de notice.

Pour les raccords avec collier inox, un resserrage suffit la plupart du temps.

De plus, un test à pression élevé est recommandé (je dirais env 6 bars mais pas plus de 10, limite de la garantie du vase d'expansion) en prenant des précautions en cas d'éclatement, genre carton ou couverture autour. Attention, à forte pression, il arrive que l'électro-vanne ne se déclenche pas. La dépressurisation peux se faire à distance en déconnectant la pompe à vélo et agir mécaniquement sur la valve du tube. Pour une utilisation dans ces pressions, on peu envisager un déclenchement avec 2 plies 9v, donc 18v.

# []{#anchor-3}**Fabrication du support**.

# Tube de lancement.

![](./assets/Pictures/100000000000009D000000ECE8B7F1ADA8A4EC09.jpg){width="4.161cm" height="6.241cm"}Coupez une longueur de 350 mm de tube IRO (isolant rigide ordinaire) ou IRL (isolant rigide lisse), et non pas ICTA (isolant cintrable transversalement annelé*), *vendu en rayon électricité, de diamètre 32. Collez-le sur un raccord fileté Pvc M32 F25 26\*34. Laisser sécher au moins 24h.

Cet ensemble tube/raccord sert au montage de l'ensemble actif de la rampe sur le support en bois et permet de renter une rampe, voire deux, dans une malle.

N'oubliez pas dans les achats les longueurs de tube IRO nécessaires en tant que mandrin pour la fabrication des fusées elles-mêmes. Leur nombre dépendra du nombre d'enfants par atelier.
