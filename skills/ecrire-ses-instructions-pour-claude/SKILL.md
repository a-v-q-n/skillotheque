---
name: ecrire-ses-instructions-pour-claude
description: Atelier guidé pour rédiger ou réviser les « Instructions pour Claude » du compte. À utiliser dès que l'utilisateur veut régler comment Claude lui répond partout ou corriger un défaut récurrent.
---

# Écrire ses instructions pour Claude

Ce skill aide l'utilisateur à rédiger le texte du champ « Instructions pour Claude » (Réglages → Général). Ce texte s'applique à toutes ses conversations et à Cowork : c'est le réglage par défaut de la façon dont Claude lui répond. L'atelier se termine par un texte prêt à coller, testé sur des demandes réelles.

Un bon texte d'instructions est court, précis et vérifiable. Il ne raconte pas toute une vie et ne fixe pas cinquante règles : il corrige ce qui agace, règle les préférences qui valent partout, et laisse le reste aux outils faits pour (projets, skills, mémoire).

Si l'utilisateur a déjà des instructions, commence par elles : il les colle, tu les audites (règles vagues, contradictoires, trop absolues, mal placées), puis tu ne reprends que les étapes utiles.

## Comment conduire l'atelier

- Une étape à la fois. Annonce l'étape en cours (« Étape 2/6 : l'entretien »).
- Trois questions au maximum par message. Propose des options ou des exemples : on répond plus vite en choisissant ou en corrigeant qu'en partant de zéro.
- À la fin de chaque étape, résume ce que tu retiens et attends son accord avant de passer à la suivante.
- Ne devine pas ses préférences. Si une information manque, demande-la. « Passe » est une réponse valide : la ligne correspondante n'entre pas dans le texte.

Commence par présenter les six étapes en une ligne chacune, puis lance l'étape 1.

## Étape 1 : le point de départ

- Demande-lui s'il a déjà des instructions et, si oui, de les coller. Rappelle que les anciennes instructions globales de Cowork y ont été versées : elles méritent une relecture.
- Demande pour quoi il utilise Claude, concrètement : les cinq ou six types de demandes les plus fréquentes (rédiger des emails, analyser des documents, réfléchir à une décision, coder, apprendre un sujet…). Le texte doit bien servir ces cas-là sans en casser aucun.
- Pose la question la plus productive : qu'est-ce qui l'agace aujourd'hui dans les réponses de Claude ? Propose des exemples s'il sèche : trop long, trop de listes, trop de compliments, cède dès qu'on le contredit, pose trop de questions ou pas assez, jargon, réponses tièdes qui ne tranchent pas, emojis.
- S'il a sous la main une réponse qu'il a adorée ou détestée, demande-la : un exemple vaut mieux qu'une description.

## Étape 2 : l'entretien

Un bloc par message, dans cet ordre. Pour chacun, propose ce que tu as compris de l'étape 1, puis pose tes questions.

a. Qui il est, en deux ou trois lignes : son métier ou son rôle, son pays ou sa ville (pour les unités, la monnaie, le droit applicable), son niveau d'expertise par domaine (expert ici, débutant là). Seulement ce qui change une réponse : ses loisirs n'ont rien à faire ici.
b. La langue : la langue de réponse, si elle vaut même quand il écrit dans une autre langue, et s'il veut que Claude le tutoie ou le vouvoie.
c. Les réponses : la longueur selon le type de demande (question rapide, analyse, document), commencer par la réponse ou par le contexte, prose ou listes, titres et tableaux, emojis.
d. La franchise : veut-il que Claude le contredise quand il se trompe, tienne sa position quand il insiste sans argument nouveau, dise clairement quand il n'est pas sûr, signale les faiblesses d'une idée avant ses forces.
e. La façon de travailler : poser une question avant d'agir quand la demande est ambiguë, ou avancer avec une hypothèse annoncée ; proposer des options ou trancher avec une recommandation ; citer ses sources ; vérifier avant d'affirmer.
f. Ce qu'il ne veut plus voir : propose une courte liste des tics les plus courants et laisse-le choisir (compliments d'ouverture comme « Excellente question ! », récapitulatif final qui répète la réponse, « N'hésitez pas à… », avertissements à rallonge, listes à puces pour tout, tiret cadratin, emojis). Ne garde que ceux qui l'agacent vraiment.
g. Ses skills : s'il a installé des skills personnels (son ton de voix, son contexte personnel ou d'autres), une ligne peut rappeler à Claude de s'en servir, par exemple « Quand j'écris en mon nom, utilise mon skill de ton de voix ».

## Étape 3 : le tri

Passe en revue ce qui est sorti de l'entretien et range ce qui n'a pas sa place dans les instructions globales. Explique-lui chaque déplacement :

| Ce qui est sorti | Où ça va |
|---|---|
| Une règle qui vaut pour toutes ses conversations | Les instructions pour Claude |
| Le contexte d'un client, d'un dossier, d'un sujet précis, avec ses documents | Un projet et ses instructions de projet |
| Sa façon d'écrire, ses textes en son nom | Un skill de ton de voix (le skill creer-son-ton-de-voix le fabrique) |
| Son parcours, ses goûts, ses valeurs, ses proches | Un skill de contexte personnel (le skill creer-son-contexte-personnel le fabrique) |
| Ses projets en cours, son équipe, ce qui change souvent | La mémoire de Claude, qui le capte au fil des conversations |
| Une méthode pour une tâche précise et répétée | Un skill dédié |

Sur un compte Team ou Enterprise, préviens-le que les instructions de l'organisation passent avant les siennes en cas de conflit.

## Étape 4 : la rédaction

Rédige le texte en suivant ces principes, et explique-lui brièvement ceux qui le surprennent :

- **Court.** Entre 150 et 400 mots. Le texte est lu au début de chaque conversation : plus il est long, plus chaque consigne se dilue et plus les contradictions guettent.
- **Écrit en « je » à Claude**, dans la langue de l'utilisateur, en paragraphes courts ou en quelques rubriques. Un texte écrit en prose donne des réponses moins chargées en listes : la forme des instructions déteint sur celle des réponses.
- **Précis et vérifiable.** « Sois concis » ne se vérifie pas ; « Pour une question simple, réponds en quelques phrases, sans introduction » se vérifie.
- **Avec sa portée.** Une règle absolue casse les cas légitimes : « Réponds toujours en trois lignes » abîme un document ou un tableau. Préciser quand la règle s'applique (« pour une question rapide… ; pour un document, la longueur qu'il faut »).
- **« Toujours » quand la règle vaut vraiment partout.** Claude applique une préférence de format ou de ton quand elle est pertinente pour la demande ; une règle universelle doit le dire (« Réponds toujours en français, même si je t'écris en anglais »).
- **Avec le pourquoi** quand il n'est pas évident. Une règle expliquée s'étend d'elle-même aux cas voisins ; « Pas de tableaux, je lis souvent sur mon téléphone » vaut mieux que « Pas de tableaux ».
- **Formulé en positif** autant que possible : dire ce qu'il veut plutôt que ce qu'il ne veut pas.
- **Ton normal.** Ni majuscules ni « IMPÉRATIF » ni « tu DOIS » : les modèles récents suivent leurs instructions de près et en font trop face à un ton crié.
- **Franchise demandée, pas silence.** « Dis-moi franchement quand je me trompe et tiens ta position si je n'apporte pas d'argument nouveau » fonctionne ; « Ne me contredis jamais » ou « Sois toujours d'accord » produit l'inverse de ce qu'il cherche.
- **Sans contradiction.** Relis l'ensemble : « très concis » et « explique toujours en détail » ne peuvent pas cohabiter. Fais-lui trancher.

Présente le texte dans un bloc de code, pour qu'il se copie en un clic, avec son nombre de mots. Attends sa validation ou ses corrections.

## Étape 5 : les tests

Un test dans la conversation de l'atelier ne vaut rien : Claude y connaît déjà l'intention. Le vrai test se fait en conditions réelles.

1. Il colle le texte dans Réglages → Général → Instructions pour Claude.
2. Il ouvre de nouvelles conversations, hors de tout projet, et envoie une batterie de cinq ou six messages adaptés à ses usages. Construis-la avec lui à partir de cette base :
   - une question factuelle rapide (longueur, introduction inutile) ;
   - une demande de document long (la règle de concision ne doit pas le tronquer) ;
   - un tableau ou du code s'il en utilise (le format ne doit pas casser) ;
   - une idée faible présentée avec aplomb, puis une insistance sans argument nouveau (Claude tient-il son désaccord ?) ;
   - une demande ambiguë (pose-t-il une question, ou avance-t-il avec une hypothèse annoncée, selon ce qu'il a choisi ?) ;
   - un message dans une autre langue, si la langue a été réglée ;
   - une question hors de son métier (le contexte personnel doit rester discret).
3. Il revient avec ce qui ne lui a pas plu. Pour chaque défaut, modifie ou ajoute une seule ligne, et montre-lui laquelle.

Si un même défaut résiste à deux corrections, propose une autre formulation plutôt qu'une règle plus insistante.

## Étape 6 : la livraison

- Donne la version finale dans un bloc de code, avec son nombre de mots.
- Rappelle où la coller : Réglages → Général → Instructions pour Claude. Elle vaut pour toutes les conversations et pour Cowork. Les libellés peuvent varier légèrement selon les versions de l'interface.
- Donne-lui la règle d'entretien : chaque fois que Claude retombe dans un travers qui l'agace, une ligne de plus ou une ligne précisée, pas un paragraphe. Tous les quelques mois, relire le texte en entier et retirer ce qui ne sert plus. Il peut relancer cet atelier pour une révision complète.
