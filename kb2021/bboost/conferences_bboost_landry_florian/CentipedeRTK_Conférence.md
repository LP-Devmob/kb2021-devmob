# BBOOST </br> <strong style="color: #890089; text-decoration: underline;">Centipède RTK : des base GPS en autonomie à faible coût </br></br> Conférence par Julien Ancelin</strong> </br> 
<strong style="font-size:20px">Florian Landry</strong>

## <strong style="color:#890089">Présentation</strong>

Centipède RTK est une solution OpenSource pour créer ses propres bases GPS et utilsier celles du réseau. C'est majoritairement utilisé dans le milieu de l'agriculture.
Usuellement, le GPS utilise plutôt des récepteurs GNSS, mais peu utilisés dans l'agriculture, de par les prix élevés. De plus, c'est assez complexe, et parfois le manque d'information à ce propos peut l'empêcher de devenir connu. 

## <strong style="color:#890089">Problème</strong>

On doit donc atuellement dépendre de services tiers qui peuvent aussi parfois être onéreux.<br>
De plus, la couche atmosphérique réduit la précision des GPS, et donc peut empêcher l'utilisation sur des échelles très petites, comme de l'ordre du centimètre.

## <strong style="color:#890089">Solution</strong>

C'est ainsi que le RTK existe. Il est là pour donner une précision au centimètre près. Le but du fonctionnement est de corriger le signal GPS reçu à l'aide de la position précise connue de la balise. C'est cette correction qui est envoyée aux utilisateurs afin de corriger leur localisation.
Le réseau Centipède en est donc une alternative open source.

## <strong style="color:#890089">RTKBase</strong>

RTKBase est donc un logiciel qui a été créé à partir du vécu de nombreuses limites, notamment le maximum de 10 kilomètres autour de la balise installée ou la latence pour avoir les informations.
C'est ainsi qu'est venue l'idée d'avoir sa propre base.<br>
En 2019, la première version fonctionnelle de RTKBase est créée. C'est grâce à une nouvelle puce multi fréquence que la zone a été augmentée à un maximum de 50 kilomètres en plus d'une latence réduite. En outre, le prix a aussi été grandement réduit.

## <strong style="color:#890089">Une nouvelle échelle</strong>

Le projet a intéressé l'INRAE, qui a participé au financement de douze bases comme la précédente.
Mais un gros problème était présent : celui du manque d'interface, comme une interface web. <br>
C'est ainsi qu'en 2020, une première interface web a été réalisée en deux mois. Il a ensuite été décidé de créer et vendre des kits de montage pour pouvoir faire ses propres bases sans avoir à commander toutes les pièces unes par unes. (la vente en ligne est bientôt disponible)

### <strong style="color:#890089"><i>Disponibilités</i></strong>

Depuis 2020, il y a eu trois nouvelles versions majeures et deux nouvelles versions intermédiaires. Ils en sont maintenant à 200 bases installées dans le monde, la plupart en France, principalement utilisée par des agriculteurs. Et le tout est disponible en opensource directement du GitHub.