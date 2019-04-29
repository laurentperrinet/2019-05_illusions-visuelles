---
author-meta:
- Laurent U Perrinet
category: review
date-meta: '2019-04-29'
description: XXX
keywords:
- Perception visuelle
- Illusions visuelles
- Hallucinations visuelles
- "Mod\xE9lisation neurale"
lang: fr-FR
papersize: a4
source: https://github.com/laurentperrinet/2019_illusions-visuelles
subject: XXX
summary: "Les objectifs sont : \u2013 mieux comprendre la fonction de la perception\
  \ visuelle en explorant certaines limites ; \u2013 mieux comprendre l\u2019importance\
  \ de l\u2019aspect dynamique de la perception ; \u2013 mieux comprendre le r\xF4\
  le de l\u2019action dans la perception."
thanks: L'auteur voudrait remercier...
title: 'Des illusions visuelles aux hallucinations: une porte sur la perception'
website: https://laurentperrinet.github.io/
...



[
<i class="fas fa-ban fa-lg"></i> **Document provisoire**<br>
Ce texte est en cours d'écriture - tout retour est bienvenu.
]{.banner .lightred}





<small><em>
This manuscript
([permalink](https://laurentperrinet.github.io/2019-05_illusions-visuelles/v/facbbb7cdafd376d618b773602c3642992a864d0/))
was automatically generated
from [laurentperrinet/2019-05_illusions-visuelles@facbbb7](https://github.com/laurentperrinet/2019-05_illusions-visuelles/tree/facbbb7cdafd376d618b773602c3642992a864d0)
on April 29, 2019.
</em></small>

## Authors



+ **Laurent U Perrinet**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-9536-010X](https://orcid.org/0000-0002-9536-010X)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [laurentperrinet](https://github.com/laurentperrinet)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [laurentperrinet](https://twitter.com/laurentperrinet)<br>
  <small>
     Institut de Neurosciences de la Timone, CNRS / Aix-Marseille Université
     · Funded by ANR project "Horizontal-V1" N°ANR-17-CE37-0006.
  </small>



## Résumé {.page_break_before}

Les illusions visuelles sont des créations d'artistes, de scientifiques et plus récemment du grand public grâce aux réseaux sociaux, qui proposent des situations souvent incongrues, dans lesquelles l'eau remonte une cascade, les personnes volent dans les airs ou des serpents se mettent à tourner. Au-delà de leur indéniable coté ludique, ces illusions nous apprennent beaucoup sur le fonctionnement du cerveau, notamment quand celles-ci se transforment en hallucinations visuelles, dépassant alors les limites des capacités normales de notre perception. En tant que chercheur en Neurosciences à l'Institut de Neurosciences de la Timone à Marseille, je dévoile ici des aspects du fonctionnement du cerveau qui sont souvent méconnus. En particulier, nous verrons pourquoi une image peut tromper nos sens ou comment des objets peuvent voyager dans le temps. Surtout nous essaierons de comprendre le fonctionnement de notre perception visuelle sur les bases d'une théorie de la vision, non pas comme une simple caméra qui enregistre passivement des images, mais comme un processus actif en relation directe avec le monde qui nous entoure.


Nous allons ici montrer comment les limites de la perception permettent et peuvent nous aider à mieux comprendre le fonctionnement du cerveau et de ses pathologies. En partant des illusions visuelles, nous allons ensuite explorer différentes hypothèses pour comprendre ses illusions, mais aussi pour aborder une neuro-anatomie fonctionnelle des hallucinations et illusions visuelles.

## Illusion visuelle et hallucinations

L’étymologie du mot illusion réfère à la tromperie et nous permet de définir les illusions visuelles comme une stimulation visuelle qui induit une perception décalée par rapport à la réalité physique (le stimulus proximal). Dans l’illusion classique dit de Hering par exemple (voir Figure @fig:hering), deux lignes parallèles placés sur un faisceau de lignes convergente semble courbées comme si le centre de l’image avait gonflé par rapport à sa périphérie. Cette illusion est robuste même si l’on prend une règle pour vérifier physiquement le parallélisme des lignes (ou simplement en enlevant les lignes fuyante): Il n’est pas possible de ne **pas** la percevoir. Ainsi, pour cette illusion comme pour une grande variété d’autres illusions visuelles statique ou dynamique ou sur d’autres modalités (comme le toucher), les illusions visuelles marquent tout d’abord par ce caractère quasi universel et intuitif, c’est-à-dire sans qu’il faille expliquer un mode d’emploi pour les illusions.

![
**Illusion de Hering.** Deux lignes parallèles (en rouge) paraissent bombées quand elles sont placées sur un faisceau de lignes convergentes.](https://raw.githubusercontent.com/laurentperrinet/2019-04-18_JNLF/master/figures/Hering_illusion.svg?sanitize=true "Hering illusion"){#fig:hering width=75% .white}

À ce titre, une illusion récente est remarquable à bien des égards. En effet, certaines illusions illusions comme le cube de Necker sont multi-stable, dans le sens où la perception peut alterner autour de plusieurs interprétations possibles de la même image. Dans le cas de [#LaRobe](https://en.wikipedia.org/wiki/The_dress), nous avons une image qui a le pouvoir de diviser une population entre des perceptions alternatives. De plus, au lieu d’être créée par des scientifiques, cette illusion est née par [sérendipité](https://fr.wikipedia.org/wiki/S%C3%A9rendipit%C3%A9) à partir d’une simple photo prise lors de la préparation d’une cérémonie de mariage. Postée sur les réseaux sociaux, cette photo a eu un destin fulgurant et mondial grâce a l’ambiguïté sur l'interprétation de la couleur de la robe. Ainsi si je vous demande de donner vous-même votre avis à partir de la Figure @fig:larobe, pensez-vous qu’elle est blanche et or ou alors qu’elle est bleu avec des bandes noires ? Même si le débat fait toujours rage, les explications scientifiques (entre autres articles scientifiques ou sessions spéciales de conférence) convergent sur une perception de la couleur de la figure qui est modifiée par le contexte du fond. En effet notre système visuel doit pouvoir identifier la couleur d’un objet (par exemple pour évaluer la maturité d’un fruit comme une balade) quelque soit les conditions lumineuses, un matin le midi avec une lumière crue ou le crépuscule avec une lumière orangée du soir. Ici le fond est surexposé et rend cette interprétation ambiguë et deux interprétations sont possibles pour cette image comme illustré dans la figure @fig:larobe2: L'illumination ambiante vire -t-elle vers le jaune (la robe est alors perçue bleue) ou le contexte est plutôt bleuâtre (la robe est alors blanche et jaune)? Je peux vous dévoiler que sur un échantillon représentatif une courte majorité voilà la robe bleue et noir. Un aspect remarquable de cette illusion et d’une part sa stabilité et d’autre part la difficulté de changer d’interprétation une fois une première interprétation formée, c’est-à-dire de passer une couleur bleue à une perception d’une couleur blanche. Cette illusion est à mes yeux d’autant plus puissante car elle met en évidence que les images sont interprétées par notre système visuel. Cela apporte aussi ce message universel qu'une propriété de nos fonctions cognitives et de pouvoir interpréter la même objet physique de différentes façons, et réconcilier des groupes humains qui peuvent avoir des façons contrastées de voir des objets physiques qui sont identiques. Pour reprendre le célèbre proverbe on pourrait dire que « l’illusion est humaine »!

![**#LaRobe.** La robe est-elle blanche avec des rayures dorées ou bleue avec des bandes sombres?](https://raw.githubusercontent.com/laurentperrinet/2019-04-18_JNLF/master/figures/The_Dress_(viral_phenomenon).png "#LaRobe"){#fig:larobe width=45% .white}
![Le contexte d'illumination ambiante permet de concilier les deux interprétations les plus communes. ](https://raw.githubusercontent.com/laurentperrinet/2019-04-18_JNLF/master/figures/Wikipe-tan_wearing_The_Dress.svg?sanitize=true "#LaRobe"){#fig:larobe2 width=75% .white}

Pour aller plus loin, il est intéressant de considérer cette image prise en 1971 par la sonde Viking d’une partie de la surface de la planète Mars (Figure @fig:viking). L’image est relativement floue, et les points noirs sont des erreurs de mesure  mais l’on distingue très clairement un visage de type humain comme une sculpture géante laisser là par une civilisation extraterrestre. Quelques 20 ans plus tard, de nouvelles images ont été réalisés par de nouvelles sondes spatiales et montrent aussi une forme de visage. Mais une fois la résolution de l’image affinée, les détails du relief révèlent qu’il n’y a pas physiquement de sculpture de ce type mais seulement un simple rocher. C’est un cas de [paréidolie](https://fr.wikipedia.org/wiki/Par%C3%A9idolie) : quelque chose est perçu alors qu’il est physiquement absent. De la même façon, on peut voir un cheval courir dans les nuages, ou le visage du Christ dans un toast, le constat est le même : le système visuel et en particulier la perception qui en découlent non seulement interprète les images, mais sur surtout, il ne peut pas faire autrement que de générer une interprétation à partir d’images, et comme on vient de le voir même si elles ne font pas a priori sens. Dans ce genre d’illusion on se rapproche donc d’une hallucination, qui peut être définie comme une perception sans objet.

![
**Un visage sur Mars.** En 1971, la sonde Viking prend une surprenante image de la surface de Mars. Une sculpture extraterrestre géante?](https://raw.githubusercontent.com/laurentperrinet/2019-04-18_JNLF/master/figures/Face-on-mars.jpg "Viking"){#fig:viking width=75% .white}

Pour résumer, les illusions visuelles, en plus de leur côté ludique, nous révèlent des caractéristiques essentielles de notre perception visuelle tant sur leurs caractéristiques universelles que sur les variabilités inter et intra individuelles. Malgré la diversité des formes des illusions visuelles et la diversité des explications qu’on peut leur faire correspondre, existe-t-il des points communs qui permettraient d’en avoir une compréhension unifiée ? Quelles pourraient être les liens profonds entre illusions visuelles avec des hallucinations aussi bien chez les sujets neuro-typique que dans des pathologies psychologiques?


## Perception visuelle et opérations prédictives

Avant d’essayer de donner une réponse à ces questions, rappelons une contrainte fondamentale à laquelle notre cerveau est confronté : l’environnement et dynamique et notre cerveau est (relativement) lent pour traiter ces informations. En effet les travaux de Simon Thorpe à Toulouse au Cerco ont montré des capacités de catégorisons Des capacités de catégorisation d’image chez les primates humains ou non nous n’en humains qui peuvent aller jusqu’à environ 100 ms chez l’humain [@QstYfgqz] et 80 ms chez le singe. C’est remarquablement rapide mais relativement long si l'on considère une tâche simple d’interception d’un objet en mouvement. Considèrons par exemple un agent qui suit une balle de tennis lancée à une vitesse de 20 m/s à une distance de 1 m devant son regard. Au moment de passer dans l’axe de vision du joueur de tennis, la balle va être perçue en arrière de la trajectoire à cause du délai sensoriel. Plus précisément la balle est placé à l’instant où l’image est prise à environ 45° d’angle visuel en retard sur la position réelle actuelle de la balle. À noter que la position de la balle est sur l’axe de vision (telle celle figurée par cette position des yeux), mais que pour le système sensoriel, cette position au temps présent doit être anticipée. Notons aussi notons aussi que la position de la balle, dans cette représentation rétinienne, au moment où l’action sera réalisé (après le délai sensorimoteur total) pourra être estimé à partir de la continuité du mouvement de la balle. C’est-à-dire qu’elle sera encore environ à 45° d’angle visuel mais cette fois ci en avant de la trajectoire, dans son futur. Il semble incroyable que ce genre de voyage dans le temps puisse s’opérer dans notre cerveau, mais une simple illusion visuelle permet de mettre ces mécanismes en évidence.

En effet, l’illusion du flash retardé ("Flash Lag Effect" en anglais) permet de mettre en évidence des dynamiques de traitement dans le système visuel. Dans cette illusion, l’observateur doit fixer environ au centre de l’écran. Une cible en mouvement horizontal apparaît et quand elle passe aux environs du centre de l’écran, un bref flash est présenté immédiatement au-dessous du centre de l'image. Perceptivement, on observe chez une vaste majorité d’observateurs que la cible en mouvement est perçue, au moment du flash, en avant de la trajectoire. L’hypothèse originale de Romi Nihjawhan propose que la cible est représenté perceptivement de telle façon à ce qu’elle occupe sa position au temps présent, donc de manière anticipative. Par contre, le flash est imprévu et sa position ne peut pas être anticipée. C’est ce que nous avons montré dans ce travail de modélisation qui montre une évaluation quantitative des production d’un tel modèle [@1BSbXPPDF].

Plus généralement, ce travail nous a conduit à émettre l’hypothèse que le cerveau utilise les régularité statistiques du monde pour arriver d’une façon ou d’une autre à compenser les contraintes de délai et par exemple à « prédire le présent ». Une telle hypothèse permet de formaliser un bon nombre d’illusions et en particulier l’illusion de Hering que nous avons défini ci-dessus. En effet, les lignes fuyante donne un contexte de perspective et en supposant un moment écologiquement significatif, comme une marche vers le point de fuite. À ce titre, les courbes horizontales sont le plus probablement perpendiculaires à l’axe de vision et à celui de la marche. Perceptivement, elles sont donc placés à des distances différentes de l’œil et sont alors anticiper dans l’espace rétiniens de telle sorte à ce que leur position est président prédit à l’instant présent d’où la forme bombé caractéristique de la perception dans cette illusion. Une extension de cette hypothèse est que le cerveau construisent par des processus prédictif une image mentale de la scène visuelle. Une telle hypothèse permet de créer un environnement de travail complet qui permet de valider quatre quantitativement cette compréhension du cerveau.

C’est une théorie formalisée par le professeur Karl Friston [@pnsTp4JV] sous le terme de principe de minimisation de l’énergie libre. À ce jour, c'est le seul paradigme théorique qui soit aussi complet pour expliquer le fonctionnement global du cerveau. Sans rentrer dans les détails mathématiques de ce principe, cette théorie permet de formaliser des modèles génératif pour toute sensation qui est reçu par nos organes et de considérer une représentation interne comme un État caché, c’est-à-dire un État une représentation et termes internes que l’on va essayer d’estimer, pour créer une variable d’énergie libre qui donne une borne supérieur à la surprise de l’agent de l’agent connaissant un modèle génératif religion sensations états internes et action. L’agent peut alors minimiser cette variable propre pour prédire au mieux son état, comme la position d’une cible. On peut aussi considérer un agent qui puisse agir sur cette environnement on parle on parle alors d’inférence active. En utilisant cette formalisation, il est alors possible de l’exprimer sous forme d’équation qui reprennent la structure du passage d’information dans le graphe formé par les différentes régions cérébrales.
Depuis les their sensoriel comme la rétine aux aires associatives comme celle qui forment les voies visuelles jusqu’aux airs regroupant les motoneurones qui vont permettre de générer une action motrice est un comportement.

Nous avons contribué avec Rick Adams et Karl Friston à l’application de ce principe pour expliquer des différences entre des patients Neuro typique et des schizophrènes. En se focalisant sur les mouvements des yeux, Espace nous avons démontré dans Adams 2012 que ce paradigme permet d’expliquer les différences dans les mouvements dit de poursuites lente. Il est alors remarquable d’observer en perturbant dans le modèle les gains synaptique des voies descendantes, c’est-à-dire celle qui permet d’affiner le modèle interne de représentation du monde, ont répliqué des caractéristiques comportementales des patients schizophrène. En particulier, c’est mouvements sont expliquées dans ce modèle comme une forme de Delusion quiDe délit vision qui consiste à accorder un poids relatif exagéré aux croyances représenté par le cerveau passeport à celle apportée par l’essence. Cette approche est étendu actuellement par le docteur Richard Adams afin d’ apporter à terme des solutions thérapeutiques et une meilleure compréhension de pathologies comme la schizophrénie.


## Vers une Neuro anatomie fonctionnelle des illusions et des hallucinations

Au cours de notre description des mécanismes sous-tendant les illusions visuelles nous nous approchons progressivement des hallucinations. Mais à la différence des illusions visuelles, celles-ci émergent sans stimulation sensorielle. Mais comment peut-on expliquer la formation d’images hallucinées, comme celle induite par la prise de drogue ou de psychotropes? Peut-on alors identifier des mécanismes qui sont impliqués dans le cerveau, et définir une neuro-anatomie fonctionnelle qui puisse expliquer ces illusions et hallucinations dans un cadre unifié?

### La contrainte de la représentation corticale

Une hypothèse novatrice proposée par Paul Bressloff et collègues en 2002 [@1FZ2hkaS5] est de voir l’origine de certaines illusions ou hallucinations dans l'interaction entre la structure de la représentation rétinienne et des représentations de cette espace visuel dans l’aire visuelle primaire. En effet, la représentation rétinienne de l’espace visuel est organisés de façon radiale depuis le point de fixation (polaire) avec une forte densité de photorécepteurs près de l’axe de vision. La représentation corticale d’une ligne est un segment dans l’espace cortical et inversement un segment dans l’espace cortical va apparaître et être perçu comme une spirale une fois re-projetée dans l’espace visuel codé par l’espace rétinien. En se basant sur une modélisation des connexions latérales entre des populations voisines de neurones de l’aire visuelle primaire, ces auteurs ont alors établi dans un modèle de champ neural qui régit la dynamique de la carte d’activité l’émergence structurée de représentations privilégiées. Comme nous l’avons décrit à l’échelle macroscopique avec notre modèle d’agent schizophrénique [@hQTLOkzF], ces auteurs ont alors analysé mathématiquement les états du système quand on perturbe certains paramètres du système, notamment les poids synaptiques régissant les interactions dans la carte corticale.
Ils ont alors montré un point essentiel : à partir d’un certain seuil de prise de drogue, des « hallucinations » peuvent émerger comme des structures stables dans la carte corticale. Étonnamment, ces états une fois un re-projetés sur l’espace visuel dessinent des spirales et des ensembles de lignes qui sont très proches des hallucinations telles qu’elles ont été rapportées après la prise de drogues diverses allant de la marijuana au peyotl ou à la mescaline. Ce type de modélisation permet d’un côté d’expliquer la formation d’hallucinations, mais aussi de définir une « neuro-géométrie », c’est-à-dire un formalisme mathématique reliant neurosciences et la géométrie des relations existant entre des sous module de l’aire visuelle primaire. On peut aussi imaginer alors des hallucinations plus complexes émerger de réseaux plus complexes qui représentent par exemple des superpositions de visages.

### Le rôle des vagues d'activité

Pour aller plus loin dans cette direction, peut-on étendre cette méthodologie à la dynamique présente dans certaines illusions, comme celle du « Point-Ligne » ? En effet, en présentant un simple point puis une ligne on induit une perception d’une expansion du point pour « remplir » la ligne (un mouvement dit Phi). L’originalité de l’étude de Jancke et collègues est d'utiliser une technique d’imagerie qui permet d’enregistrer l’activité sur le cortex visuel primaire (ici du chat anesthésié) lors de la présentation de cette illusion d’optique. À noter qu’en comparant l’activité produite par les deux éléments présentés séparément ou conjointement, on met en évidence une activité différentielle qui est caractéristique de la perception de cette illusion. Une même  méthodologie permet de mettre en évidence un mécanisme original. Pour cela on utilise cette fois une illusion encore plus simple qui consiste à montrer un point à une position de l’espace visuel puis un autre point exactement similaire mais à une distance proche (mais supérieure à la taille de ce point). On perçoit alors un et un seul point qui se déplace de la première à la seconde position. Au niveau des enregistrements (cette fois chez le macaque) la réponse différentielle montre que relativement à un traitement indépendant des deux points, il existe une vague d’activité qui se déplace sur le cortex qui en particulier supprime une partie de l’activité [@cAAUyqwj]. Une modélisation sur ordinateur a permis de montrer qu'une fonction de cette vague de suppression est de lever les ambiguïtés sur les différents mouvements possibles représentés sur la carte. Dans ce cas particulier, la vague permet de supprimer la représentation d’un mouvement dans le sens opposé. Toutefois, beaucoup de questions restent en suspens. Ces résultats montrent le rôle potentiel des vagues d’activité sur la surface du cortex comme un outil potentiel de traitement de l’information et de sa modulation [@9OxNsfYF]. Ces vagues peuvent en effet induire facilitations ou suppressions dans l'espace et le temps et produire une forme de « calcul » pour représenter au mieux l’image visuelle.


## Conclusion

Pour résumer, les illusions et hallucinations nous ouvre une porte sur les possibilités de la perception mais aussi sur une compréhension des mécanismes cérébraux qui les induisent. La modélisation, notamment celle que nous proposons, offre une opportunité nouvelles d’appréhender ces mécanismes. Les outils théoriques permettant de progresser dans cette voie de recherche existent mais ne sont pas pour le moment exploités à leur plein potentiel. Ils seront essentiels pour une meilleure compréhension des illusions visuelles, des hallucinations et de ce qui peut la provoquer, mais aussi du cerveau en général.



## Acknowledgements

We'd like to thank the individuals, not listed as authors, who provided comments on
<!--  [GitHub issues](https://github.com/search?l=&q=repo%3Agreenelab%2Fscihub+repo%3Agreenelab%2Fscihub-manuscript+repo%3Agreenelab%2Fscihub-browser-data+repo%3Adhimmel%2Fscopus+repo%3Agreenelab%2Flibrary-access&ref=advsearch&type=Issues&utf8=%E2%9C%93 "GitHub Issues in Project Repositories") or pull requests.
Specifically, [Ross Mounce](https://github.com/rossmounce), [Richard Smith-Unna](https://github.com/blahah), [Guillaume Cabanac](https://github.com/gcabanac), and [Stuart Taylor](https://github.com/StuartCT) provided valuable input while the study was underway.
In addition, we're grateful to GitHub for offering gratis Large File Storage as part of their education program. -->

## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
