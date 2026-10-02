---
name: creer-son-contexte-personnel
description: Entretien en profondeur qui crée le skill « tout savoir sur moi » de l'utilisateur. À utiliser dès qu'il veut que Claude le connaisse, ou créer ou enrichir son contexte personnel.
---

# Créer son contexte personnel

Ce skill conduit un entretien en profondeur avec l'utilisateur (parcours, carrière, projets, façon de travailler, valeurs, goûts, voyages) et en tire **son propre skill « tout savoir sur moi »**, que Claude consultera ensuite de lui-même chaque fois que mieux le connaître améliore une réponse, sans qu'il ait à se représenter à chaque conversation.

Le skill produit est rangé par tiroirs : un portrait de haut niveau, une chronologie, puis un fichier par domaine de sa vie. Claude n'ouvre que le tiroir utile à la question.

L'entretien s'inspire de deux méthodes : grill-me (Matt Pocock), qui interroge sans relâche, une question à la fois, jusqu'à ce que rien ne reste dans le flou ; et le Life Story Interview du psychologue Dan McAdams, qui raconte une vie en chapitres et en scènes clés.

Si le skill skill-creator est disponible, appuie-toi sur ses conseils d'écriture et sur son script d'emballage. Pour tout le reste, la démarche ci-dessous prime sur la sienne : l'intention est déjà posée ici, l'entretien la complète.

Si l'utilisateur a déjà un skill de contexte (il le joint ou il est installé), propose de l'enrichir plutôt que de repartir de zéro : lis-le, montre les domaines absents, vides ou dont la date de vérification est ancienne, et ne reprends que ceux qu'il choisit.

## Comment interroger

- Une question à la fois. Une relance seulement si la réponse est vague ou ouvre une piste qui compte.
- Chaque réponse peut ouvrir des branches (un poste évoqué, une personne, un déménagement, une passion). Note-les et explore-les avant de quitter le domaine en cours. Tiens à jour la liste des branches ouvertes et montre-la quand il la demande.
- Sur les faits (dates, lieux, postes, études), ne propose jamais de réponse : tu ne peux pas deviner sa vie. Pose la question, ou propose des options quand ça l'aide à se souvenir.
- Sur les préférences et les façons de faire, tu peux avancer une hypothèse tirée de ce qu'il a déjà dit, toujours marquée « hypothèse, à confirmer ». On réagit plus vite à une proposition qu'à une page blanche.
- « Je ne sais pas » et « passe » sont des réponses valides. Note « non renseigné » et avance.
- Pas de complaisance : ne commente pas ses réponses par des compliments, pose la question suivante.
- Ne garde que ce qui changerait une réponse future de Claude. « J'aime les choses bien faites » ne sert à rien ; « je préfère un premier jet rapide à un plan détaillé » sert.
- Rappelle-lui en début d'entretien que répondre en dictée vocale va plus vite et donne des réponses plus riches.

## Les règles du contenu

- N'écris que ce qu'il a dit ou confirmé. Toute déduction est soit validée par lui, soit jetée.
- Les dates sont absolues (« depuis 2019 », jamais « il y a cinq ans »).
- Les autres personnes apparaissent par leur prénom et leur rôle (« Julie, son associée »), sans détail qu'elles ne voudraient pas lire. Demande si une information vient d'une confidence : si oui, elle n'entre pas.
- Ne note jamais de numéro d'identité, de coordonnée bancaire, de mot de passe ni d'adresse précise.
- Chaque fichier porte un niveau de sensibilité qu'il choisit : publique (peut nourrir un texte destiné à d'autres), privée (pour l'usage de Claude, jamais cité tel quel), intime (seulement s'il pose la question lui-même).

## Étape 1 : le cadrage

- S'il a joint un CV, une bio ou un profil LinkedIn, extrais-en les faits, présente-les en liste et fais-les confirmer. L'entretien se concentrera sur ce qui manque. Sinon, propose-lui de joindre ce qu'il a : c'est un gain de temps.
- Demande à quoi servira ce contexte : surtout le travail, surtout la vie perso, les deux.
- Propose la liste des domaines de l'étape 2 à cocher, et demande s'il en manque un ou s'il en retire.
- Demande ce qui est hors limites : les sujets à ne ni aborder ni noter.
- Préviens que l'entretien complet prend deux à trois heures et peut se faire en plusieurs fois.

Commence par présenter les étapes en une ligne chacune, puis lance l'étape 1.

## Étape 2 : l'entretien, domaine par domaine

Un domaine à la fois, dans l'ordre qu'il choisit (par défaut celui-ci). À la fin de chaque domaine, rédige le fichier correspondant, montre-le, et attends sa validation avant de passer au suivant. Ainsi rien ne se perd si l'entretien s'étale.

1. Identité et situation : où il vit, fuseau horaire, langues, situation de vie au niveau de détail qu'il choisit, ce qui occupe ses journées.
2. Formation : études, diplômes, formations marquantes, ce qu'il a appris en dehors des écoles.
3. Carrière : les postes et activités dans l'ordre, ce qu'il y faisait vraiment, ses réalisations, ce qu'il sait faire, ce qu'il ne sait pas ou ne veut plus faire.
4. Projets en cours : ce sur quoi il travaille, les objectifs et les échéances, ce qui bloque. C'est le fichier qui périme le plus vite.
5. Personnes clés : les gens qui comptent dans sa vie pro et perso, prénom et rôle.
6. Travailler avec lui : comment il décide, son rapport au risque et à l'erreur, ce qui lui donne de l'énergie et ce qui lui en prend, comment il veut que Claude lui réponde (longueur, franchise, plan d'abord ou résultat d'abord, tolérance au désaccord), ce qui l'agace dans les réponses d'une IA.
7. Valeurs et positions : ce qui compte le plus pour lui, ses lignes rouges même quand elles coûtent, ses convictions sur les sujets qui lui tiennent à cœur et comment elles ont évolué. Rappelle que ce fichier est sensible par nature et demande son niveau.
8. Goûts : livres, films, séries, musique, cuisine, sport, esthétique, ce qu'il déteste. Quand l'entretien s'essouffle, quelques questions du questionnaire de Proust relancent bien (sa vertu préférée, son idée du bonheur, ses héros, sa devise).
9. Voyages et lieux : où il a vécu, où il a voyagé et ce qu'il en a retenu, comment il aime voyager, les endroits qui l'attirent.
10. Récit de vie (Life Story Interview) : si sa vie était un livre, ses chapitres (de deux à sept), avec un titre et la bascule vers le suivant ; puis quelques scènes clés : un sommet, un point bas, un tournant, un souvenir d'enfance marquant, un moment où il a compris quelque chose d'important ; enfin le prochain chapitre qu'il imagine. Pour chaque scène : ce qui s'est passé, quand, et ce que ça dit de lui.

À mesure que les dates tombent, alimente la chronologie.

Si la conversation devient trop longue, dis-le. Donne-lui alors les fichiers déjà validés à télécharger et la liste des domaines restants : il les joindra dans une nouvelle conversation en demandant de reprendre son contexte personnel, et ce skill repartira de là.

## Étape 3 : l'écriture du skill

Assemble son skill avec cette structure :

- SKILL.md
  - frontmatter : name « tout-savoir-sur-<prénom> » en minuscules et tirets, et une description franche sur le déclenchement, de 200 caractères au plus (limite de claude.ai) : à utiliser dès qu'une réponse gagne à le connaître (conseil, recommandation, décision, texte écrit pour lui ou en son nom), même s'il ne le demande pas ;
  - un portrait de haut niveau en dix à quinze lignes : qui il est, ce qu'il fait, ce qui compte pour lui ;
  - l'essentiel de « travailler avec lui », en quelques puces ;
  - l'index des fichiers : pour chacun, ce qu'il contient, quand le lire, son niveau de sensibilité ;
  - les règles d'usage : ne lire que le fichier utile ; ne jamais extrapoler au-delà de ce qui est écrit, et dire « je ne sais pas » plutôt qu'inventer ; respecter les niveaux de sensibilité ; signaler une information volatile vérifiée il y a plus de six mois ; quand il apprend à Claude quelque chose de nouveau sur lui au fil d'une conversation, lui proposer la mise à jour du fichier concerné ;
  - la liste des sujets hors limites.
- references/chronologie.md : un tableau trié (année ou période, lieu, événement ou rôle, fichier détaillé), avec les chapitres de son récit de vie comme intertitres.
- references/<domaine>.md : un fichier par domaine retenu. En tête de chacun : sensibilité, date de dernière vérification, stable ou volatil. Dans le corps : des faits courts et datés, et quelques-unes de ses phrases citées quand elles montrent sa façon de penser mieux qu'un résumé.

Le SKILL.md reste court : il oriente, les fichiers détaillent. Montre-le et attends sa validation avant les tests.

## Étape 4 : les tests

Pas d'évaluation chiffrée : c'est lui qui juge. Prends quatre ou cinq questions qu'il pourrait poser un jour, par exemple « recommande-moi un livre pour les vacances », « aide-moi à préparer mon entretien de mardi », « rédige ma bio pour une conférence », « où partir trois jours en novembre ? ». Pour chacune, dis quels fichiers tu lirais, puis réponds avec son skill. Vérifiez ensemble trois choses : le bon tiroir est ouvert, rien n'est inventé, rien de privé ou d'intime ne fuit dans un texte destiné à d'autres. Chaque défaut corrige le skill, pas seulement la réponse.

## Étape 5 : la livraison

- Emballe le skill dans un fichier .zip dont la racine est le dossier du skill (le dossier contient SKILL.md et references/), et donne-le-lui à télécharger.
- Explique-lui comment l'installer : sur claude.ai, Personnaliser → Skills, importer le fichier, puis l'activer. Les libellés peuvent varier légèrement selon les versions de l'interface. Puis comment vérifier qu'il se déclenche : dans une nouvelle conversation, poser une question qui demande de le connaître et voir Claude annoncer qu'il utilise le skill.
- Explique comment le tenir à jour : quand sa vie change, il dit « mets à jour mon contexte » dans une conversation où le skill est actif, puis réimporte la nouvelle version ; ou il relance cet entretien pour enrichir un domaine. Les projets en cours se relisent chaque trimestre.
- Conseille-lui de garder une copie des fichiers chez lui : c'est la version maîtresse, réutilisable dans d'autres outils.
