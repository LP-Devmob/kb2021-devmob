# Vie Quotidienne et cybersécurité, tous les oppose et pourtant ils sont si proches !

*présenté par Rachid Zerouali*

## La cybersécurité aujourd'hui 
Le volume du nombre d'incident par jours reste toujours conséquents et constant. Le problème est que ces incidents commencent à apparaitre et à être le quotidien des particuliers et des entreprises, comme par exemple l’usurpation d'identité (ex. réception de mails frauduleux se faisant passer pour une entreprise qui nous est familier) qui est devenu quotidiens dans nos boites mail.

Le point de faiblesse est l'humain car nous somme tous susceptibles de nous faire avoir.

## La cybersécurité vue par CFO/CISO
La cybersécurité ne se fait pas tous le temps après avoir été attaquée, car dans ce cas ce serait presque trop tard.
Il ne faut pas non plus que les développeur regardent les ops résoudre les cyberattaques 
--->Les dev et ops doivent coopérer et ne pas laisser que les ops gérer les cyberattaques.

### Exemples de ceux qui n'ont pas pensé à sécuriser leur logiciel/app avant de se faire attaquer : 
**Exemple 1** Chez décathlon , les chercheurs ont découvert des VPNmentor, une base de donnée de 9go comprenant 123 million d'enregistrements notamment sur les employés et les clients .
--> Solution simple : reverse proxy , serach-guard( solution open source, qui gère entre autre la partie authentification)

**Exemple 2 ** : Les MongoDB est une base de donnée nosql qui va stocker des documents. Chaque livre dans une bdd est un document. A une époque il n'y avait pas de sécurité et des cyber attaqueurs ont découvert 22.900 instances et ont fait un Backup. Ils ont ensuite fait du chantage à MongoDB -> Demande de rançon contre la récupération de la BDD
--> Solution : mettre un mecanisme simple d'authentification

Attention :  une application sécurisée aujourd'hui ne le sera peut être pas demain. 
Pour cela , nous pouvons utiliser des “scanners de sécurité” . Si le scanner de sécurité n'affiche aucune erreur à un instant T, cela ne veut pas non plus dire qu’il en affichera pas dans le futur. Il faut donc effectuer des scans de sécurité régulièrement sur nos applications. 

Un développer full-stack ne peut pas maitriser le front end / back end/ database /devops / l'application mobile. Ce n'est pas possible. Nous devons donc répartir les rôles en pensant, tout au long du projet,  à la cybersécurité.

### Cybersécurité , quelques pistes :
L'idée serait de créer des passerelles entre les équipes de développement et les équipes de sécurité pour qu'elles puissent travailler ensemble.
Il faut travailler en amont , communiquer avec les équipes , suivre l'application.
Il ne faut donc pas qu'une équipe de développement se piège en finalisant un projet sans avoir consulté une équipé sécurité au préalable car l’équipe sécurité pourrait refuser que l’application sorte sur le marché pour risques de cyberattaques.

Dev/Ops/Sec :
* Former / sensibiliser les équipes IT aux risques
* Outiller et accompagner ( il existe pléthore d'outils Open-sources)
- Travailler par pallier avec des solutions simples 

CFO / CISO 
* Rassurer / démontrer que la securite est un allié , pas un ennemi
* Sensibiliser sur les solutions All in One et leur potentielles risques



### Vie quotdienne
Nous avons tous des appareils connectés et passons de plus en plus de temps sur les réseaux.

17% des Français ont décidé de se lancer dans la téléconsultation via smartphone durant le confinement , un chiffre qui double auprès des 18-24 ans

Les menaces les plus serieuses pour les jeunes enfants incluents :
* les liens vers des sites web malveillants 
* le malware 
* les téléchargements furtifs
* les virus 

La cybersécurité est souvent entendue en entreprises , mais nous sommes tous concernés donc nous devons faire attention à utilisation que nous faisons de nos objets connectés.

#### Vie quotidienne : quelques pistes 
Pour les personnes âgées :
* Accompagnement via des médiateurs numériques qui traduisent dans des mots très simples des sujets parfois difficilement compréhensible.

Pour les plus jeunes :
* Control parental
* Accompagnement des parents
* Sensibilisation aux risques

Pour les utilisateurs:
* Ne pas utiliser son nom dans un mot de passe
* Ne pas installer d'applications sans autorisation
* Ne pas partager les mots de passe en dehors de la cellule familiale
* Ajouter uniquement les personnes que l'utilisateur connait sur les reseaux sociaux
* Avoir des mots de passes différents , gestionnaire de mdp peut être utile
* installer un anti-virus

#### Conclusion
La cybersécurité n'est pas innée, il faut se rapprocher des gens qui savent et diffuser . Avoir une bonne hygiène de sécurité est primordiale !

