# Créer son contexte personnel

Ce prompt lance avec Claude un entretien en profondeur sur vous : parcours, carrière, projets, façon de travailler, valeurs, goûts, voyages. Il en tire un **skill « tout savoir sur moi »** que Claude consulte ensuite de lui-même chaque fois que mieux vous connaître améliore sa réponse, sans que vous ayez à vous représenter à chaque conversation.

Le skill est rangé par tiroirs : un portrait de haut niveau, une chronologie, puis un fichier par domaine de votre vie. Claude n'ouvre que le tiroir utile à la question : une recommandation de livre lit vos goûts, pas votre parcours professionnel.

L'entretien s'inspire de deux méthodes : [grill-me](https://github.com/mattpocock/skills), le skill de Matt Pocock qui interroge sans relâche, une question à la fois, jusqu'à ce que rien ne reste dans le flou ; et le [Life Story Interview](https://en.wikipedia.org/wiki/Dan_P._McAdams) du psychologue Dan McAdams, qui raconte une vie en chapitres et en scènes clés.

## Avant de commencer

- **Activez les skills** sur [claude.ai](https://claude.ai) : dans Réglages → Capacités, activez « Exécution de code et création de fichiers », puis, dans la section Skills, le skill « skill-creator ». Sur un compte Team ou Enterprise, l'administrateur doit d'abord autoriser les skills. Les libellés peuvent varier légèrement selon les versions de l'interface.
- **Rassemblez ce qui existe déjà** pour gagner du temps : votre CV ou l'export de votre profil LinkedIn, une bio, la page « À propos » de votre site. Claude en tire les faits et concentre l'entretien sur ce qui manque.
- **Prévoyez deux à trois heures**, en plusieurs fois. L'entretien se reprend dans la même conversation. Répondre en dictée vocale va plus vite et donne des réponses plus riches.
- **Vous décidez de ce qui entre.** Tout est facultatif, chaque question peut être passée. Le skill vit dans votre compte Claude : n'y mettez rien que vous ne voudriez pas y voir (numéros d'identité, coordonnées bancaires, informations confiées par d'autres).

## Le prompt

Copiez le bloc ci-dessous (icône « Copier » en haut à droite), collez-le dans une nouvelle conversation et envoyez. Joignez votre CV ou votre bio au même message si vous les avez.

````text
Je veux créer mon contexte personnel : un skill Claude « tout savoir sur moi », pour que tu disposes de tout ce qui t'aide à bien m'aider, sans que j'aie à me représenter à chaque conversation.

Utilise le skill skill-creator pour le construire avec moi, en suivant la démarche ci-dessous. Elle tient lieu de capture d'intention : l'intention est posée ici, tu la complètes par l'entretien. Si skill-creator n'est pas disponible dans cette conversation, dis-le-moi tout de suite et explique-moi comment l'activer (Réglages → Capacités : « Exécution de code et création de fichiers », puis le skill « skill-creator »). Si je ne peux pas l'activer, on suit quand même la démarche et tu me livres les fichiers du skill à télécharger.

# Comment tu m'interroges

- Une question à la fois. Une relance seulement si ma réponse est vague ou ouvre une piste qui compte.
- Chaque réponse peut ouvrir des branches (un poste évoqué, une personne, un déménagement, une passion). Note-les et explore-les avant de quitter le domaine en cours. Tiens à jour la liste des branches ouvertes et montre-la-moi quand je te la demande.
- Sur les faits (dates, lieux, postes, études), ne propose jamais de réponse : tu ne peux pas deviner ma vie. Pose la question, ou propose des options quand ça m'aide à me souvenir.
- Sur les préférences et les façons de faire, tu peux avancer une hypothèse tirée de ce que je t'ai déjà dit, toujours marquée « hypothèse, à confirmer ». Je réagis plus vite à une proposition qu'à une page blanche.
- « Je ne sais pas » et « passe » sont des réponses valides. Note « non renseigné » et avance.
- Pas de complaisance : ne commente pas mes réponses par des compliments, pose la question suivante.
- Ne garde que ce qui changerait une de tes réponses futures. « J'aime les choses bien faites » ne sert à rien ; « je préfère un premier jet rapide à un plan détaillé » sert.

# Les règles du contenu

- N'écris que ce que j'ai dit ou confirmé. Toute déduction est soit validée par moi, soit jetée.
- Les dates sont absolues (« depuis 2019 », jamais « il y a cinq ans »).
- Les autres personnes apparaissent par leur prénom et leur rôle (« Julie, mon associée »), sans détail que je ne voudrais pas qu'elles lisent. Demande-moi si une information me vient d'une confidence : si oui, elle n'entre pas.
- Ne note jamais de numéro d'identité, de coordonnée bancaire, de mot de passe ni d'adresse précise.
- Chaque fichier porte un niveau de sensibilité que je choisis : publique (peut nourrir un texte destiné à d'autres), privée (pour ton usage, jamais cité tel quel), intime (seulement si je pose la question moi-même).

# Étape 1 : le cadrage

- Si j'ai joint un CV, une bio ou un profil, extrais-en les faits, présente-les en liste et fais-les-moi confirmer. L'entretien se concentrera sur ce qui manque.
- Demande-moi à quoi servira ce contexte : surtout le travail, surtout la vie perso, les deux.
- Propose-moi la liste des domaines ci-dessous à cocher, et demande s'il en manque un ou si j'en retire.
- Demande-moi ce qui est hors limites : les sujets que tu ne dois ni aborder ni noter.

Commence par me présenter les étapes en une ligne chacune, puis lance l'étape 1.

# Étape 2 : l'entretien, domaine par domaine

Un domaine à la fois, dans l'ordre que je choisis (par défaut celui-ci). À la fin de chaque domaine, rédige le fichier correspondant, montre-le-moi, et attends ma validation avant de passer au suivant. Ainsi rien ne se perd si l'entretien s'étale.

1. Identité et situation : où je vis, fuseau horaire, langues, situation de vie au niveau de détail que je choisis, ce qui occupe mes journées.
2. Formation : études, diplômes, formations marquantes, ce que j'ai appris en dehors des écoles.
3. Carrière : les postes et activités dans l'ordre, ce que j'y faisais vraiment, mes réalisations, ce que je sais faire, ce que je ne sais pas ou ne veux plus faire.
4. Projets en cours : ce sur quoi je travaille, les objectifs et les échéances, ce qui bloque. C'est le fichier qui périme le plus vite.
5. Personnes clés : les gens qui comptent dans ma vie pro et perso, prénom et rôle.
6. Travailler avec moi : comment je décide, mon rapport au risque et à l'erreur, ce qui me donne de l'énergie et ce qui m'en prend, comment je veux que tu me répondes (longueur, franchise, plan d'abord ou résultat d'abord, tolérance au désaccord), ce qui m'agace dans les réponses d'une IA.
7. Valeurs et positions : ce qui compte le plus pour moi, mes lignes rouges même quand elles coûtent, mes convictions sur les sujets qui me tiennent à cœur et comment elles ont évolué. Rappelle-moi que ce fichier est sensible par nature et demande-moi son niveau.
8. Goûts : livres, films, séries, musique, cuisine, sport, esthétique, ce que je déteste. Quand l'entretien s'essouffle, quelques questions du questionnaire de Proust relancent bien (ma vertu préférée, mon idée du bonheur, mes héros, ma devise).
9. Voyages et lieux : où j'ai vécu, où j'ai voyagé et ce que j'en ai retenu, comment j'aime voyager, les endroits qui m'attirent.
10. Récit de vie (Life Story Interview de Dan McAdams) : si ma vie était un livre, ses chapitres (de deux à sept), avec un titre et la bascule vers le suivant ; puis quelques scènes clés : un sommet, un point bas, un tournant, un souvenir d'enfance marquant, un moment où j'ai compris quelque chose d'important ; enfin le prochain chapitre que j'imagine. Pour chaque scène : ce qui s'est passé, quand, et ce que ça dit de moi.

À mesure que les dates tombent, alimente la chronologie.

Si la conversation devient trop longue, dis-le-moi. Donne-moi alors les fichiers déjà validés à télécharger et la liste des domaines restants : je les joindrai avec ce prompt dans une nouvelle conversation pour reprendre là où on s'est arrêtés.

# Étape 3 : l'écriture du skill

Assemble le skill selon les principes de skill-creator, avec cette structure :

- SKILL.md
  - frontmatter : name « tout-savoir-sur-<mon prénom> », et une description franche sur le déclenchement : à utiliser dès qu'une réponse gagne à me connaître (conseil, recommandation, décision, préparation d'un rendez-vous, texte écrit pour moi ou en mon nom, organisation d'un voyage), même si je ne demande pas explicitement d'utiliser mon contexte. L'essentiel tient dans les 200 premiers caractères.
  - un portrait de haut niveau en dix à quinze lignes : qui je suis, ce que je fais, ce qui compte pour moi ;
  - l'essentiel de « travailler avec moi », en quelques puces ;
  - l'index des fichiers : pour chacun, ce qu'il contient, quand le lire, son niveau de sensibilité ;
  - les règles d'usage : ne lire que le fichier utile ; ne jamais extrapoler au-delà de ce qui est écrit, et dire « je ne sais pas » plutôt qu'inventer ; respecter les niveaux de sensibilité ; signaler une information volatile vérifiée il y a plus de six mois ; quand j'apprends quelque chose de nouveau sur moi au fil d'une conversation, me proposer la mise à jour du fichier concerné ;
  - la liste des sujets hors limites.
- references/chronologie.md : un tableau trié (année ou période, lieu, événement ou rôle, fichier détaillé), avec les chapitres de mon récit de vie comme intertitres.
- references/<domaine>.md : un fichier par domaine retenu. En tête de chacun : sensibilité, date de dernière vérification, stable ou volatil. Dans le corps : des faits courts et datés, et quelques-unes de mes phrases citées quand elles montrent ma façon de penser mieux qu'un résumé.

Le SKILL.md reste court : il oriente, les fichiers détaillent. Montre-le-moi et attends ma validation avant les tests.

# Étape 4 : les tests

Pas d'évaluation chiffrée : c'est moi qui juge. Pose-toi quatre ou cinq questions que je pourrais te poser un jour, par exemple « recommande-moi un livre pour les vacances », « aide-moi à préparer mon entretien de mardi », « rédige ma bio pour une conférence », « où partir trois jours en novembre ? ». Pour chacune, dis quels fichiers tu lirais, puis réponds avec le skill. Vérifie trois choses avec moi : le bon tiroir est ouvert, rien n'est inventé, rien de privé ou d'intime ne fuit dans un texte destiné à d'autres. Chaque défaut corrige le skill, pas seulement la réponse.

# Étape 5 : la livraison

- Emballe le skill en fichier .skill téléchargeable.
- Explique-moi comment l'installer (Réglages → Capacités → Skills → importer le fichier, puis l'activer) et comment vérifier qu'il se déclenche dans une nouvelle conversation.
- Explique-moi comment le tenir à jour : quand ma vie change, je dis « mets à jour mon contexte » dans une conversation où le skill est actif, puis je réimporte la nouvelle version. Les projets en cours se relisent chaque trimestre.
- Conseille-moi de garder une copie des fichiers chez moi : c'est la version maîtresse, réutilisable dans d'autres outils.
````
