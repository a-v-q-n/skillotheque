# Skillothèque AVQN

Des skills pour Claude, développés pour les clients d'[AVQN](https://avqn.ch). Un skill s'installe une fois dans Claude, puis se relance autant de fois qu'on veut, simplement en le demandant.

## Les skills

| Skill | À quoi il sert | Télécharger |
|---|---|---|
| [Créer son ton de voix](skills/creer-son-ton-de-voix/SKILL.md) | Claude vous accompagne pas à pas pour capturer votre façon d'écrire et en faire votre skill de ton de voix, pour que tout ce qu'il rédige ensuite sonne comme vous. | [creer-son-ton-de-voix.zip](https://github.com/a-v-q-n/skillotheque/releases/latest/download/creer-son-ton-de-voix.zip) |
| [Créer son contexte personnel](skills/creer-son-contexte-personnel/SKILL.md) | Claude vous interroge en profondeur (parcours, carrière, projets, valeurs, goûts, voyages) et en tire votre skill « tout savoir sur moi », rangé par tiroirs, qu'il consulte dès que vous connaître améliore sa réponse. | [creer-son-contexte-personnel.zip](https://github.com/a-v-q-n/skillotheque/releases/latest/download/creer-son-contexte-personnel.zip) |
| [Écrire ses instructions pour Claude](skills/ecrire-ses-instructions-pour-claude/SKILL.md) | Claude vous aide à rédiger le texte du champ « Instructions pour Claude » de vos réglages : court, précis, testé sur vos vraies demandes, pour qu'il vous réponde partout comme vous le voulez. | [ecrire-ses-instructions-pour-claude.zip](https://github.com/a-v-q-n/skillotheque/releases/latest/download/ecrire-ses-instructions-pour-claude.zip) |

## Installer un skill

1. Sur [claude.ai](https://claude.ai), ouvrez les réglages et activez « Exécution de code et création de fichiers » : les skills en ont besoin. Sur un compte Team ou Enterprise, l'administrateur doit d'abord autoriser les skills.
2. Téléchargez le fichier .zip du skill dans le tableau ci-dessus.
3. Dans Personnaliser → Skills, importez le fichier, puis activez le skill.

Les libellés peuvent varier légèrement selon les versions de l'interface.

## Lancer un skill

Dans une nouvelle conversation, dites simplement ce que vous voulez : « je veux créer mon ton de voix », « aide-moi à créer mon contexte personnel », « aide-moi à écrire mes instructions pour Claude ». Claude reconnaît la demande et lance le skill.

### Créer son ton de voix

- **Rassemblez vos textes** avant de commencer : 5 à 15 textes écrits par vous, sans IA, dont vous êtes content et que vous enverriez tels quels aujourd'hui. Variez les canaux et les longueurs : quelques emails, quelques posts, un texte plus long, des messages courts. Retirez les informations confidentielles.
- **Prévoyez une heure** environ, en une ou plusieurs fois.
- **Huit étapes** : cadrage, corpus, analyse de vos textes, personnalité, règles d'écriture (adresse, lexique, forme, emojis, tics d'IA à bannir), rédaction de votre skill, tests sur de vrais textes, installation.

### Créer son contexte personnel

- **Rassemblez ce qui existe déjà** : votre CV ou l'export de votre profil LinkedIn, une bio, la page « À propos » de votre site. Claude en tire les faits et concentre l'entretien sur ce qui manque.
- **Prévoyez deux à trois heures**, en plusieurs fois. Répondre en dictée vocale va plus vite et donne des réponses plus riches.
- **Vous décidez de ce qui entre.** Chaque question peut être passée, et chaque fichier porte un niveau de sensibilité que vous choisissez. Votre skill vit dans votre compte Claude : n'y mettez rien que vous ne voudriez pas y voir.
- L'entretien s'inspire de [grill-me](https://github.com/mattpocock/skills), le skill de Matt Pocock qui interroge sans relâche jusqu'à ce que rien ne reste dans le flou, et du Life Story Interview du psychologue [Dan McAdams](https://en.wikipedia.org/wiki/Dan_P._McAdams), qui raconte une vie en chapitres et en scènes clés.

### Écrire ses instructions pour Claude

- **Le champ concerné** : Réglages → Général → Instructions pour Claude. Ce texte s'applique à toutes vos conversations et à Cowork. Si vous en avez déjà un, gardez-le sous la main : Claude commence par le relire.
- **Pensez à ce qui vous agace** dans les réponses de Claude aujourd'hui : c'est le meilleur point de départ.
- **Prévoyez une demi-heure**, plus quelques conversations de test une fois le texte collé.
- **Six étapes** : point de départ, entretien (qui vous êtes, langue, format des réponses, franchise, façon de travailler, tics à bannir), tri de ce qui a sa place ailleurs (projet, skill, mémoire), rédaction, tests en conditions réelles, livraison.
