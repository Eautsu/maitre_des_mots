# Maître des mots !

Jeu de cartes en ligne pour s'entraîner à l'**orthographe lexicale** au CE1.
Une page par séance, jouable seul, directement dans le navigateur : sans installation, sans compte,
sans collecte de données personnelles.

👉 **Jouer :** ouvrir [`index.html`](index.html) (sur GitHub Pages : `https://eautsu.github.io/<nom-du-depot>/`).

## Objectif pédagogique

Les mots travaillés sont ceux des dictées de la période, regroupés par **graphème ou difficulté**
(B et D, M et N, AN/AM/EN/EM, accents…). Le jeu vise à fixer l'orthographe de ces mots par un
**rappel actif** : l'élève doit retrouver et écrire le mot à partir d'une devinette, d'une image ou
d'une question, plutôt que de le relire.

Il poursuit trois objectifs :

1. **Mémoriser l'orthographe lexicale** : les lettres muettes, les doubles lettres, les accents,
   les mots invariables (mots-outils).
2. **Produire de l'écrit** : l'élève écrit chaque mot en entier, avec ses accents, et reçoit une
   correction immédiate.
3. **Comprendre pour retrouver** : chaque devinette donne une définition, une phrase-exemple avec
   le mot masqué `[…]`, et au besoin un indice sur le piège orthographique. L'élève travaille donc
   aussi le sens et le lexique, pas seulement la forme.

Le jeu **complète** les dictées et les apprentissages à la maison sans les remplacer. Il s'utilise :

- en **classe entière** (projection, une carte à la fois), deux fois par semaine ;
- en **autonomie** (atelier, APC, devoirs), seul sur tablette ou ordinateur ;
- à **distance**, pour reprendre une séance après une absence ;
- en **création par les élèves**, qui imaginent leurs propres cartes avec le même format.

Chaque carte est rattachée à un **lot** qui suit la progression des mots donnés en devoirs : l'élève
peut ne rejouer que les mots de la semaine, ou tout mélanger.

## Les séances

| Famille | Séance | Cartes |
|---|---|---|
| Consonnes proches | [B et D](maitre-des-mots-B-et-D.html) | 19 |
| | [D et T](maitre-des-mots-D-et-T.html) | 18 |
| | [F et V](maitre-des-mots-F-et-V.html) | 25 |
| | [M et N](maitre-des-mots-M-et-N.html) | 17 |
| | [P et Q](maitre-des-mots-P-et-Q.html) | 15 |
| Sons à plusieurs graphies | [CH et J](maitre-des-mots-CH-et-J.html) | 25 |
| | [AN AM et EN EM](maitre-des-mots-AN-AM-et-EN-EM.html) | 25 |
| | [IN et IM](maitre-des-mots-IN-et-IM.html) | 22 |
| | [ON OM OU](maitre-des-mots-ON-OM-OU.html) | 25 |
| Accents et groupes | [É È Ê](maitre-des-mots-accents.html) | 16 |
| | [Fr Pr Cr Br Vr Dr Tr Fl Pl Cl Bl](maitre-des-mots-Fr-Pr-Cr-Br-Vr-Dr-Tr-Fl-Pl-Cl-Bl.html) | 19 |

## Types de cartes

| Type | Principe |
|---|---|
| **Devinette** (libre) | « Qui suis-je ? » : l'élève lit ou écoute les indices et écrit le mot. |
| **Choix** | Plusieurs orthographes proposées : l'élève choisit la bonne. |
| **Vrai ou faux** | Une affirmation sur le mot (lettre muette, invariabilité…) à valider. |
| **Image** | Une illustration à nommer, puis à écrire. |

Réglages disponibles dans le jeu : lecture vocale des consignes, choix des types de cartes, filtre
par lot, accents obligatoires ou non, affichage des lettres accentuées. En cas d'erreur, la carte
montre la bonne réponse et le piège à retenir, et la liste des mots à revoir est affichée en fin de partie.

## Le générateur

[`generateur_maitre_des_mots.html`](generateur_maitre_des_mots.html) est un outil **pour les
enseignants**, utilisable dans le navigateur, sans serveur. Il permet de :

- **créer une nouvelle séance** : titre, cartes (type, devinette, réponse, lot, image, piège) ;
- **ouvrir un jeu existant** (par exemple l'une des onze séances ci-dessus) pour ajouter,
  modifier ou supprimer des cartes ;
- **télécharger le jeu solo** obtenu, une page HTML autonome prête à publier.

### Les onze séances comme exemples

Les onze séances de ce dépôt servent d'**exemples de référence**. Pour créer la vôtre :

1. ouvrez le générateur ;
2. chargez un jeu proche de ce que vous voulez (par ex. `maitre-des-mots-B-et-D.html`) et regardez
   comment les devinettes sont construites ;
3. modifiez les cartes ou repartez de zéro ;
4. téléchargez le fichier, ajoutez vos images dans `images/`, puis publiez.

Une bonne devinette suit la même structure dans tous les exemples : **une définition courte, une
phrase-exemple où le mot est remplacé par `[…]`, puis éventuellement un indice sur la difficulté
orthographique** (« J'ai un E à la fin qui fait sonner ma consonne »). Les mots de la même séance
ne doivent pas se trahir entre eux.

## Organisation du dépôt

```
index.html                         page d'accueil : séances classées par son
maitre-des-mots-*.html             un jeu par séance (onze séances)
generateur_maitre_des_mots.html    créer ou modifier une séance
images/                            illustrations des cartes (voir images/README.md)
README.md  LICENSE  NOTICE.md      documentation et licences
```
- Code, devinettes et documentation : **CC BY-NC-SA 4.0**, © Eautsu (voir [`LICENSE`](LICENSE)).
- Illustrations : issues de la bibliothèque **Canva** (contenu gratuit), **non couvertes** par cette
  licence ; voir [`NOTICE.md`](NOTICE.md) pour les conditions de réutilisation.

## Mesure d'audience

Chaque page utilise [GoatCounter](https://www.goatcounter.com), un compteur de visites sans cookie
et sans donnée personnelle.

## Auteur

Créé par **Eautsu**, enseignant·e de CE1.
