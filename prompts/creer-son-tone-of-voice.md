# Créer son tone of voice

Ce prompt lance avec Claude un atelier guidé pour capturer votre façon d'écrire et en faire un **skill**, c'est-à-dire un mode d'emploi de votre voix que Claude applique ensuite automatiquement à chaque fois qu'il rédige pour vous : emails, posts, messages, propositions.

Claude s'appuie sur son skill intégré **skill-creator** et vous accompagne en huit étapes : cadrage, corpus de vos textes, analyse, personnalité, règles d'écriture (lexique, emojis, adresse, forme), rédaction du skill, tests sur de vrais textes, installation.

## Avant de commencer

- **Activez les skills** sur [claude.ai](https://claude.ai) : dans Réglages → Capacités, activez « Exécution de code et création de fichiers », puis, dans la section Skills, le skill « skill-creator ». Sur un compte Team ou Enterprise, l'administrateur doit d'abord autoriser les skills. Les libellés peuvent varier légèrement selon les versions de l'interface.
- **Rassemblez vos textes** (Claude vous le redemandera à l'étape 2, mais c'est plus rapide si c'est prêt) : 5 à 15 textes écrits par vous, sans IA, dont vous êtes content et que vous enverriez tels quels aujourd'hui. Variez les canaux et les longueurs : quelques emails, quelques posts, un texte plus long, des messages courts. Retirez les informations confidentielles.
- **Prévoyez une heure** environ. L'atelier peut se faire en plusieurs fois dans la même conversation.

## Le prompt

Copiez le bloc ci-dessous (icône « Copier » en haut à droite), collez-le dans une nouvelle conversation et envoyez.

````text
Je veux créer mon tone of voice : un skill Claude qui capture ma façon d'écrire, pour que tout ce que tu rédiges en mon nom sonne comme moi, un bon jour, avec le temps de bien faire.

Utilise le skill skill-creator pour le construire avec moi, en suivant la démarche ci-dessous. Elle tient lieu de capture d'intention : l'intention est posée ici, tu la complètes par l'entretien. Si skill-creator n'est pas disponible dans cette conversation, dis-le-moi tout de suite et explique-moi comment l'activer (Réglages → Capacités : « Exécution de code et création de fichiers », puis le skill « skill-creator »). Si je ne peux pas l'activer, on suit quand même la démarche et tu me livres les fichiers du skill à télécharger.

# Comment on travaille

- Une étape à la fois, dans l'ordre. Annonce l'étape en cours (« Étape 3/8 : l'analyse du corpus »).
- Trois questions au maximum par message. Quand une question est abstraite, propose des options ou des exemples : je réponds plus vite en choisissant ou en corrigeant qu'en partant de zéro.
- À la fin de chaque étape, résume en quelques lignes ce que tu retiens et attends mon accord avant de passer à la suivante.
- Pars de mes textes avant de me demander de me décrire : je connais mal mes propres habitudes, mes textes les montrent mieux. Chaque fois que tu affirmes quelque chose sur ma voix, cite le passage qui le montre.
- Ne devine pas à ma place. Si une information manque, demande-la.
- Je peux répondre « passe » à n'importe quelle question : tu fais alors un choix raisonnable et tu le signales.

Commence par me présenter les huit étapes en une ligne chacune, puis lance l'étape 1.

# Étape 1 : le cadrage

Apprends à me connaître :
- qui je suis, mon métier, et pour qui j'écris (clients, prospects, collègues, communauté, proches) ;
- dans quelle(s) langue(s) j'écris ;
- les canaux à couvrir : propose-moi une liste à cocher (emails professionnels, emails personnels, LinkedIn, Instagram, newsletter, site web, messages WhatsApp / Slack / Teams, propositions commerciales, autres) ;
- ce qui sonne faux aujourd'hui quand une IA écrit pour moi.

Puis aide-moi à choisir la structure. Explique la distinction : la voix (qui je suis) reste la même partout, le ton (comment je parle) s'adapte au canal et au destinataire. Par défaut, recommande un seul skill avec un socle commun et une déclinaison par canal. Ne propose deux skills séparés que si deux voix n'ont presque rien en commun, par exemple une voix institutionnelle au nom d'une entreprise et une voix personnelle.

# Étape 2 : le corpus

Explique-moi quoi rassembler, puis attends que je l'apporte :
- 5 à 15 textes que j'ai écrits moi-même, sans IA, que je trouve réussis et que j'enverrais tels quels aujourd'hui, récents de préférence ;
- variés : au moins deux ou trois par canal retenu, et des longueurs différentes (un message court, un email, un texte long) ;
- pour chacun, une ligne de contexte : le canal, le destinataire, et ce que j'aime dedans ;
- en bonus, un à trois contre-exemples : des textes (de moi, d'autres ou d'une IA) qui me hérissent, avec une ligne sur ce qui me déplaît.

Je peux les coller dans la conversation ou joindre un document, en séparant les textes par un titre. Rappelle-moi de remplacer les informations confidentielles par des repères ([Client], [Montant]). Si le corpus est mince ou couvre un seul canal, dis-moi ce qui manque, sans bloquer.

# Étape 3 : l'analyse du corpus

Analyse mes textes et présente tes constats, chacun illustré par un extrait :
- le rythme : longueur des phrases et surtout leur variation, longueur des paragraphes ;
- les ouvertures et les clôtures, canal par canal ;
- le vocabulaire récurrent, les expressions-signature, les tournures qu'une IA ne produirait jamais d'elle-même ;
- le niveau de langue et l'adresse (tu ou vous) ;
- la façon de prendre position, de nuancer, l'humour s'il y en a ;
- la ponctuation, la mise en forme, les emojis ;
- ce qui est absent : ce que je ne fais jamais.

Ensuite je trie chaque constat : « c'est moi, garde », « accident, ne le reproduis pas » (fautes, tics dont je veux me débarrasser), « à nuancer ». Le skill décrit la voix que je veux, pas une photocopie de mes archives.

# Étape 4 : la personnalité

- Propose trois à cinq attributs de ma voix sous la forme « X mais pas Y » (« direct mais pas sec », « chaleureux mais pas familier »), tirés du corpus. Je choisis et j'ajuste. Pour chaque attribut retenu, précise ce qu'il veut dire et ce qu'il ne veut pas dire.
- Demande-moi ce que je veux que mon lecteur ressente ou pense en me lisant.
- Situe-moi sur les quatre curseurs du ton (Nielsen Norman Group) : formel ↔ décontracté, sérieux ↔ drôle, respectueux ↔ irrévérencieux, enthousiaste ↔ factuel. Donne ta lecture du corpus, canal par canal si ça varie, et je corrige.

# Étape 5 : les règles d'écriture

Un chapitre par message, dans cet ordre. Pour chacun, propose d'abord ce que tu as observé dans le corpus, puis pose tes questions.

a. L'adresse : tu ou vous selon le canal et la relation, formules d'ouverture et de clôture, signature.
b. Le lexique : les expressions que j'aime employer, les mots et tournures que je ne supporte pas, le jargon et les anglicismes autorisés ou non.
c. La forme : longueur des textes par canal, paragraphes, listes ou prose, gras, ponctuation (points d'exclamation, points de suspension, tiret cadratin).
d. Les emojis : est-ce que j'en utilise, lesquels, combien, à quel endroit du texte (fin de phrase, titre, jamais en début de ligne ?), dans quels canaux jamais.
e. Les tics d'IA : montre-moi la liste ci-dessous et demande-moi lesquels bannir absolument. Ajoutes-y ceux que tu repères dans mes contre-exemples.
   - Ponctuation et forme : tiret cadratin (—) en incise, gras partout, listes à puces systématiques, emojis en puce (✅ 🚀 en début de ligne), 👇.
   - Structures : « Ce n'est pas X, c'est Y » ; « Pas de X. Pas de Y. Juste Z. » ; énumérations systématiques par trois ; paragraphes tous de la même longueur ; « d'une part… d'autre part » ; questions rhétoriques auto-répondues (« Le résultat ? Bluffant. ») ; phrases courtes isolées pour l'effet dramatique ; méta-commentaires (« Voici ce que j'en retiens »).
   - Ouvertures et clôtures : « Bien sûr ! », « Absolument ! », « Dans un monde où… », « À l'ère du numérique… », « Plongeons dans… », « En conclusion », « En résumé », « N'hésitez pas à… », « J'espère que ce message vous trouve bien », la question d'engagement plaquée en fin de post (« Et vous, vous en êtes où ? »).
   - Vocabulaire : crucial, essentiel, incontournable, véritable, révolutionnaire, levier, synergie, booster, naviguer (dans la complexité), plonger, « force est de constater », « il convient de ».
   - Ton : enthousiasme artificiel, politesse excessive, prudence permanente (« on pourrait considérer que »), conclusions vagues sur l'avenir.
f. Les déclinaisons : pour chaque canal retenu, ce qui change (adresse, longueur, structure, ouverture, clôture, emojis) et ce qui ne bouge jamais.

# Étape 6 : l'écriture du skill

Rédige le skill selon les principes de skill-creator, avec cette structure :

- SKILL.md
  - frontmatter : un name court (par exemple « voix-prenom ») et une description franche sur le déclenchement : à utiliser dès qu'un texte sera envoyé ou publié en mon nom, ou que je demande d'écrire comme moi, en citant mes canaux. L'essentiel tient dans les 200 premiers caractères.
  - l'essence de ma voix, en un ou deux paragraphes ;
  - les attributs « X mais pas Y » ;
  - les règles non négociables, numérotées, chacune avec son pourquoi ;
  - le lexique : à employer, à bannir ;
  - un tableau des canaux : adresse, ouverture, clôture, emojis ;
  - le processus de rédaction : identifier le canal, lire la déclinaison correspondante, écrire, relire contre la checklist ;
  - une checklist de relecture, faite de points vérifiables ;
  - une boucle d'amélioration : quand je corrige un texte, identifier la règle manquante ou fautive et me proposer de l'ajouter au skill.
- references/<canal>.md : une déclinaison par canal retenu.
- references/exemples.md : des extraits authentiques de mon corpus, annotés (ce qui fait que c'est moi), et des paires avant / après (version IA générique → ma version).

Garde en tête :
- Les exemples valent mieux que les adjectifs. « Chaleureux » ne dit rien à un modèle, un extrait le montre.
- Chaque règle doit être précise et vérifiable : les mots exacts, pas « éviter le jargon ».
- Un SKILL.md court et dense, les détails dans references/. Trop de règles rend l'écriture mécanique, donc artificielle.

Montre-moi le SKILL.md et attends ma validation avant les tests.

# Étape 7 : les tests

Pas d'évaluation chiffrée : pour un style d'écriture, c'est moi qui juge.
- Demande-moi deux ou trois situations réelles où j'ai besoin d'écrire en ce moment, sur mes canaux principaux, et rédige-les avec le skill.
- Pour l'une d'elles, reprends le sujet d'un texte de mon corpus, écris ta version sans regarder l'original, puis compare-les et liste les écarts.
- À chaque correction que je fais, corrige le skill et pas seulement le texte, et montre-moi la règle ajoutée ou modifiée.

On itère jusqu'à ce que les textes soient publiables avec quelques retouches légères.

# Étape 8 : la livraison

- Emballe le skill en fichier .skill téléchargeable.
- Explique-moi comment l'installer (Réglages → Capacités → Skills → importer le fichier, puis l'activer) et comment vérifier qu'il se déclenche dans une nouvelle conversation.
- Donne-moi le mode d'emploi au quotidien : je demande simplement « écris un email à… » ; quand un texte ne me convient pas, je le corrige et je demande de mettre à jour le skill, puis je réimporte la nouvelle version.
- Termine par un résumé de ma voix en dix lignes, à coller dans les instructions personnelles d'un outil qui n'accepte pas les skills.
````
