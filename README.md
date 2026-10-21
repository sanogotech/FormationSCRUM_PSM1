# Portail de révision PSM I

Application web autonome (un seul fichier HTML) pour préparer la certification **Professional Scrum Master I (PSM I)** de Scrum.org.

Elle reprend la structure du *Portail de révision CISSP* (quiz FR, quiz EN, fiches REX, cheat sheet, glossaire), ajoute **5 innovations** pédagogiques et **5 onglets d'entraînement** supplémentaires.

- **Fichier :** `Portail_Revision_PSM_I.html` (environ 220 Ko)
- **Référence :** Scrum Guide 2020 et Professional Scrum Competencies de Scrum.org
- **Langues :** français et anglais
- **Auteur :** SANOGO Souleymane, Consultant Formateur et Expert SI
- **Version :** 2.0, octobre 2026 (ajout de 5 onglets)

---

## Sommaire

1. [L'examen PSM I en bref](#1-lexamen-psm-i-en-bref)
2. [Démarrage rapide](#2-démarrage-rapide)
3. [Contenu du portail](#3-contenu-du-portail)
4. [Les 5 innovations](#4-les-5-innovations)
4 bis. [Les 5 onglets d'entraînement ajoutés en v2](#4-bis-les-5-onglets-dentraînement-ajoutés-en-v2)
5. [Répartition des questions par thème](#5-répartition-des-questions-par-thème)
6. [Plan de révision sur 7 jours](#6-plan-de-révision-sur-7-jours)
7. [Mode d'emploi détaillé](#7-mode-demploi-détaillé)
8. [Raccourcis clavier](#8-raccourcis-clavier)
9. [Données enregistrées et confidentialité](#9-données-enregistrées-et-confidentialité)
10. [Utilisation en formation](#10-utilisation-en-formation)
11. [Architecture technique](#11-architecture-technique)
12. [Ajouter ou modifier des questions](#12-ajouter-ou-modifier-des-questions)
13. [Compatibilité](#13-compatibilité)
14. [Dépannage](#14-dépannage)
15. [Ressources officielles](#15-ressources-officielles)
16. [Avertissements](#16-avertissements)

---

## 1. L'examen PSM I en bref

| Élément | Valeur |
|---|---|
| Nombre de questions | 80 |
| Durée | 60 minutes |
| Seuil de réussite | 85 % (68/80) |
| Objectif recommandé | 90 % (72/80) |
| Formats | Choix unique, choix multiple, Vrai/Faux |
| Langue | Anglais uniquement |
| Rythme moyen | 45 secondes par question |

**Grille de lecture des scores**

| Score | Interprétation |
|---|---|
| Moins de 68/80 | Préparation à renforcer |
| 68/80 | Seuil théorique de réussite |
| 72/80 | Objectif recommandé |
| 76/80 et plus | Très bonne maîtrise |

> Scrum.org ne publie pas de répartition officielle des questions par thème. La répartition utilisée dans le portail est une **estimation pédagogique**.

---

## 2. Démarrage rapide

1. Téléchargez `Portail_Revision_PSM_I.html`.
2. Double-cliquez sur le fichier : il s'ouvre dans votre navigateur.
3. Sur l'accueil, choisissez un thème ou suivez le **plan de 7 jours**.

Aucune installation, aucun compte, aucun serveur n'est nécessaire. Une connexion Internet sert uniquement à charger les polices ; sans connexion, le portail fonctionne avec les polices du système.

---

## 3. Contenu du portail

| Onglet | Rôle |
|---|---|
| **Accueil** | Vue d'ensemble, tableau de maîtrise, score prédit, plan 7 jours, cartes des 13 thèmes |
| **Quiz FR** | 111 questions en français, termes anglais de l'examen surlignés |
| **Quiz EN** | 111 questions en anglais, formulées comme l'examen réel |
| **Simulateur 80 q.** | Examen blanc chronométré en conditions réelles (innovation N°1) |
| **Carnet d'erreurs** | Révision espacée des questions ratées (innovation N°2) |
| **Guide ou mythe ?** | Vrai/Faux éclair contre les idées reçues (innovation N°5) |
| **Le bon ordre** | Remettre dans l'ordre les étapes de 12 processus Scrum |
| **Atelier formules** | Exercices chiffrés générés à l'infini, avec correction détaillée |
| **Associations** | Relier 6 termes anglais à leur traduction, au chrono |
| **Études de cas** | 8 scénarios terrain en 3 décisions, en Afrique de l'Ouest |
| **Progression** | Objectif quotidien, jours de suite, activité, historique, code de sauvegarde |
| **Fiches REX** | Une fiche par thème : notions, pièges, état de l'art 2026, bonnes pratiques, exam tips |
| **Cheat sheet** | Synthèse d'une page à relire la veille de l'examen |
| **Glossaire** | 57 termes anglais avec traduction et définition, filtrables par thème |

**Chiffres clés**

- 222 questions (111 FR + 111 EN), chacune avec une explication et un REX
- 3 formats : choix unique, choix multiple (2 réponses), Vrai/Faux
- 13 fiches REX
- 30 énoncés « Guide ou mythe ? »
- 57 termes de glossaire
- 12 processus à ordonner, 8 types d'exercices chiffrés, 8 études de cas (24 décisions)

### Structure d'une question

Chaque question affiche :

- son **type** (choix unique, choix multiple, Vrai/Faux) ;
- l'**énoncé**, avec les termes anglais de l'examen surlignés ;
- après validation en mode Apprentissage : le **verdict**, l'**explication** fondée sur le Scrum Guide et le **REX**, c'est-à-dire le piège d'examen à retenir.

### Les deux modes de quiz

| Mode | Fonctionnement |
|---|---|
| **Apprentissage** | Correction immédiate après chaque réponse, retour possible à la question précédente |
| **Examen** | Aucune correction avant la fin, comme le jour J |

---

## 4. Les 5 innovations

### N°1 · Simulateur PSM I en conditions réelles

- 80 questions tirées selon la répartition estimée des 13 thèmes
- Chronomètre de 60 minutes, passage en rouge à 5 minutes de la fin
- Indicateur de rythme : questions répondues comparées au rythme cible de 45 secondes
- Grille de navigation des 80 questions, retour possible sur chaque question
- Marquage « à revoir »
- Confirmation avant soumission, avec le nombre de questions sans réponse et marquées
- Soumission automatique à la fin du temps
- Résultat par thème et correction détaillée
- Historique des 30 derniers examens blancs
- Langue au choix : anglais (comme l'examen) ou français (entraînement)

### N°2 · Carnet d'erreurs à répétition espacée

Fondé sur la méthode des boîtes de Leitner :

| Boîte | Signification |
|---|---|
| Boîte 1 | Erreur récente, à revoir en priorité |
| Boîte 2 | En cours d'apprentissage |
| Boîte 3 | Presque acquise |
| Maîtrisée | Réussie après la boîte 3 |

- Toute question ratée, dans n'importe quel module, entre en boîte 1.
- Une bonne réponse lors d'une révision du carnet fait monter la question d'une boîte.
- Une erreur la renvoie en boîte 1.
- Chaque session pioche jusqu'à 20 questions, en commençant par la boîte 1.

### N°3 · Indice de certitude

Avant de valider, l'apprenant indique son niveau de confiance : **Sûr**, **Hésitant** ou **Au hasard**. Le bilan classe les réponses en quatre catégories :

| | Juste | Faux |
|---|---|---|
| **Sûr** | Acquis | **Idée reçue à corriger en priorité** |
| **Pas sûr** | À consolider | À apprendre |

Les réponses « sûr mais faux » sont les plus dangereuses à l'examen : elles sont signalées dans la correction.

### N°4 · Tableau de maîtrise et score prédit

- Taux de réussite par thème, alimenté par tous les modules (quiz, simulateur, carnet)
- Barre colorée : rouge sous 70 %, orange entre 70 et 85 %, vert au-delà ; trait vertical à 85 %
- **Score prédit sur 80** : moyenne des taux par thème, pondérée par la répartition des 80 questions
- La prédiction n'utilise que les thèmes avec au moins 3 réponses et indique leur nombre
- Comparaison au seuil de 68/80 et à l'objectif de 72/80

### N°5 · Guide ou mythe ?

- 20 affirmations tirées parmi 30
- 8 secondes par affirmation, barre de temps visible
- Réponse : « Guide 2020 » ou « Mythe » ; le temps écoulé compte comme une erreur
- Justification après chaque réponse et record personnel enregistré
- Cible les mythes fréquents : Sprint 0, vélocité, trois questions du Daily, comité de Product Owners, Sprint de hardening, user stories obligatoires…

---

## 4 bis. Les 5 onglets d'entraînement ajoutés en v2

### Le bon ordre

Remettez dans l'ordre chronologique les étapes de 12 processus Scrum, à l'aide des flèches ↑ ↓, puis cliquez sur **Vérifier l'ordre**.

| Processus | Thème |
|---|---|
| Les événements dans un Sprint | Events |
| Les trois sujets du Sprint Planning | Events |
| Le cycle empirique | Empiricism |
| Le parcours d'un élément du Product Backlog | Product Backlog Management |
| L'annulation d'un Sprint | Events |
| Le déroulé d'une Sprint Review | Events |
| Le déroulé d'une Sprint Retrospective | Events |
| La construction du Sprint Backlog | Artifacts |
| Le traitement d'un obstacle | Coaching |
| Le passage à plusieurs équipes | Scrum Team |
| La demande d'une partie prenante | Stakeholders & Customers |
| Des objectifs du plus long au plus court terme | Artifacts |

Séries de 12 ou de 6 processus ; chaque étape mal placée affiche sa bonne position, puis l'ordre correct et le point à retenir.

### Atelier formules

Exercices générés aléatoirement, en nombre illimité, filtrables par type :

| Type | Calcul |
|---|---|
| Score PSM I | bonnes réponses ÷ 80 × 100 |
| Bonnes réponses minimales | arrondi supérieur de (nombre de questions × 0,85) |
| Gestion du temps | secondes restantes ÷ questions restantes (cible : 45 s) |
| Canaux de communication | n(n − 1) ÷ 2 |
| Prévision empirique | arrondi supérieur de (reste à faire ÷ débit moyen), avec fourchette |
| Loi de Little | temps de cycle = WIP ÷ débit |
| Timebox du Daily Scrum | jours ouvrés × 15 min |
| Capacité du Sprint | Developers × jours − absences |

Saisie avec virgule ou point décimal ; **Entrée** pour vérifier ; bouton **Voir la solution**. La correction détaille le calcul et le relie au Scrum Guide. La loi de Little et la vélocité relèvent de pratiques complémentaires, signalées comme telles.

### Associations éclair

6 termes anglais du glossaire à relier à leur traduction française. Cliquez un terme, puis sa traduction. Chrono au dixième de seconde, **5 secondes de pénalité** par erreur, record personnel. Le bilan rappelle les 6 définitions.

### Études de cas

8 scénarios, chacun en 3 décisions, avec justification après chaque choix et score conservé par cas.

| Cas | Lieu | Organisation | Thèmes |
|---|---|---|---|
| Le comité qui voulait être Product Owner | Abidjan | Banque, mobile money | Scrum Team, autogestion |
| Le Daily Scrum de 45 minutes | Dakar | Opérateur télécom | Events, facilitation |
| Presque terminé à la fin du Sprint | Lomé | Plateforme logistique portuaire | Done, Artifacts |
| Le directeur général et le Sprint Backlog | Bamako | Microfinance | Product Backlog, valeur |
| Une date ferme pour le guichet numérique | Cotonou | Services publics numériques | Prévision, parties prenantes |
| L'équipe qui attend les ordres | Ouagadougou | Startup agritech | Autogestion, coaching |
| La dette technique cachée | Conakry | Clinique | Empirisme, valeurs |
| La Retrospective monopolisée | Niamey | Assurance | Facilitation, events |

Les organisations sont fictives.

### Progression et objectifs

- **Objectif quotidien** : 10, 20, 40 ou 80 activités par jour. Une activité = une question, un exercice, un processus vérifié, une paire associée ou une décision de cas.
- **Jours de suite** : nombre de jours consécutifs où l'objectif est atteint.
- **Activité des 5 dernières semaines** : calendrier coloré de lundi à dimanche.
- **Historique des séances** : 25 dernières séances affichées (200 conservées), avec date, heure, module et résultat.
- **Code de sauvegarde** : bouton **Générer mon code**, puis **Copier le code** sur l'appareil d'origine. Sur le nouvel appareil, collez le code (il commence par `PSM1-`) et cliquez deux fois sur **Restaurer** pour confirmer. La restauration remplace la progression de l'appareil.

---

## 5. Répartition des questions par thème

| N° | Thème | Questions à l'examen (estimation) | Banque FR | Banque EN |
|---|---|---|---|---|
| 1 | Scrum Team | 10 | 14 | 14 |
| 2 | Events | 12 | 16 | 16 |
| 3 | Self-Managing Teams | 5 | 7 | 7 |
| 4 | Forecasting & Release Planning | 5 | 7 | 7 |
| 5 | Done (Definition of Done) | 6 | 8 | 8 |
| 6 | Stakeholders & Customers | 4 | 6 | 6 |
| 7 | Coaching | 5 | 7 | 7 |
| 8 | Empiricism | 7 | 9 | 9 |
| 9 | Artifacts | 8 | 11 | 11 |
| 10 | Facilitation | 4 | 6 | 6 |
| 11 | Scrum Values | 5 | 7 | 7 |
| 12 | Product Backlog Management | 5 | 7 | 7 |
| 13 | Product Value | 4 | 6 | 6 |
| | **Total** | **80** | **111** | **111** |

Quand plusieurs thèmes sont sélectionnés dans un quiz, les questions sont tirées **au prorata** de cette répartition.

**Les 5 priorités absolues :** Scrum Team, Events, Artifacts, Definition of Done, Empiricism.

---

## 6. Plan de révision sur 7 jours

| Jour | Contenu | Thèmes lancés par le bouton |
|---|---|---|
| J1 | Fondamentaux Scrum et accountabilities | 1, 8, 11 |
| J2 | Events | 2 |
| J3 | Artifacts et Definition of Done | 9, 5 |
| J4 | Product Backlog et Product Value | 12, 13, 4, 6 |
| J5 | Coaching, facilitation et autogestion | 7, 10, 3 |
| J6 | Examen blanc : 80 questions en 60 minutes | Simulateur |
| J7 | Correction des erreurs et révision finale | Carnet d'erreurs + cheat sheet |

Chaque jour se coche une fois terminé ; l'état est conservé dans le navigateur.

---

## 7. Mode d'emploi détaillé

### Lancer un quiz

1. Ouvrez **Quiz FR** ou **Quiz EN**.
2. Sélectionnez un ou plusieurs thèmes (ou **Tous**).
3. Choisissez le nombre de questions : 5, 10, 20, 40 ou 80.
4. Choisissez le mode **Apprentissage** ou **Examen**.
5. Cliquez sur **Lancer le quiz**.

### Répondre

1. Cliquez sur une réponse (ou deux pour un choix multiple).
2. Indiquez votre certitude : Sûr, Hésitant ou Au hasard.
3. Cliquez sur **Valider**.

### Après le quiz

- Score global et détail par thème
- Calibrage de la certitude
- Correction détaillée (les erreurs sont dépliées)
- Boutons : **Recommencer**, **Nouveau quiz**, **Rejouer mes erreurs**, **Ouvrir le carnet d'erreurs**

### Méthode conseillée

1. Lire la fiche REX du thème.
2. Faire le quiz FR en mode Apprentissage.
3. Refaire le thème en anglais.
4. Vider le carnet d'erreurs.
5. Passer un examen blanc en anglais jusqu'à dépasser 72/80 à deux reprises.

---

## 8. Raccourcis clavier

| Module | Touche | Action |
|---|---|---|
| Quiz et carnet | A, B, C, D | Sélectionner une réponse |
| Quiz et carnet | 1, 2, 3 | Certitude : Sûr, Hésitant, Au hasard |
| Quiz et carnet | Entrée | Valider ou passer à la suite |
| Simulateur | A, B, C, D | Sélectionner une réponse |
| Guide ou mythe ? | V ou T | Guide 2020 |
| Guide ou mythe ? | F ou M | Mythe |
| Guide ou mythe ? | Entrée | Affirmation suivante |
| Atelier formules | Entrée | Vérifier la réponse |

---

## 9. Données enregistrées et confidentialité

Toutes les données restent **dans le navigateur de l'utilisateur** (`localStorage`). Rien n'est envoyé sur Internet.

| Clé | Contenu |
|---|---|
| `psm:stat` | Réponses et réussites par thème (tableau de maîtrise) |
| `psm:box` | Boîtes de Leitner du carnet d'erreurs |
| `psm:best:fr:N` / `psm:best:en:N` | Meilleur score par thème et par langue |
| `psm:simhist` | Historique des examens blancs |
| `psm:simlang` | Langue choisie pour le simulateur |
| `psm:flashbest` | Record « Guide ou mythe ? » |
| `psm:plan` | Jours cochés du plan 7 jours |
| `psm:cfg:fr` / `psm:cfg:en` | Derniers réglages des quiz |
| `psm:fiche` | Dernière fiche consultée |
| `psm:days` | Nombre d'activités par jour (objectif, série, calendrier) |
| `psm:goal` | Objectif quotidien |
| `psm:sessions` | Historique des séances |
| `psm:ordrebest` | Record « Le bon ordre » |
| `psm:formstat` / `psm:ftype` | Réussite et filtre de l'atelier formules |
| `psm:assocbest` | Record « Associations éclair » |
| `psm:cas` | Meilleur score par étude de cas |

**Conséquences pratiques**

- Les progrès ne suivent pas automatiquement d'un appareil à l'autre : utilisez le **code de sauvegarde** de l'onglet Progression.
- La navigation privée efface tout à la fermeture.
- Effacer les données du site remet le portail à zéro.
- Remise à zéro ciblée : bouton **Remettre à zéro** (maîtrise) sur l'accueil et **Vider le carnet** dans le carnet d'erreurs.

---

## 10. Utilisation en formation

- **Diffusion :** le fichier peut être envoyé par e-mail ou WhatsApp, copié sur clé USB ou déposé sur un intranet ou un LMS.
- **Suivi individuel :** chaque stagiaire a ses propres scores, puisqu'ils sont stockés dans son navigateur.
- **Atelier collectif :** projeter « Guide ou mythe ? » et faire voter la salle avant de révéler la réponse.
- **Débrief :** utiliser le calibrage de certitude pour lancer une discussion sur les idées reçues.
- **Examen blanc collectif :** lancer le simulateur en même temps pour tout le groupe et comparer les scores par thème.

---

## 11. Architecture technique

- **Un seul fichier** HTML d'environ 220 Ko : styles, données et logique inclus
- **HTML, CSS et JavaScript natifs**, sans framework ni bibliothèque
- **Polices** chargées depuis Google Fonts avec repli sur les polices système : Bricolage Grotesque (titres), Source Sans 3 (texte), JetBrains Mono (chiffres et code)
- **Thème clair et sombre** automatique selon le réglage du système
- **Responsive** : ordinateur, tablette et téléphone

### Organisation du code

| Bloc | Rôle |
|---|---|
| `DATA[n].fr` / `DATA[n].en` | Banques de questions par thème |
| `META` | Thèmes : nom, nombre de questions à l'examen, notions, REX, état de l'art, bonnes pratiques, exam tips |
| `GLOSS` | Glossaire |
| `MYTHS` | Énoncés « Guide ou mythe ? » |
| `CHEAT` | Contenu HTML de la cheat sheet |
| `ORDRE` | Processus à remettre dans l'ordre |
| `FORM` | Générateurs d'exercices chiffrés |
| `CAS` | Études de cas |
| Application | Navigation, quiz, simulateur, carnet, statistiques |

---

## 12. Ajouter ou modifier des questions

Ouvrez le fichier HTML dans un éditeur de texte et cherchez `DATA[n]={fr:[` (français) ou `DATA[n].en=[` (anglais), où `n` est le numéro du thème.

### Format d'une question

```js
["Énoncé de la question",
 ["Bonne réponse","Distracteur 1","Distracteur 2","Distracteur 3"],
 "Explication fondée sur le Scrum Guide.",
 "REX : le piège à retenir.",
 k]   // optionnel : nombre de bonnes réponses
```

| Type | Règle |
|---|---|
| Choix unique | La **première** option est la bonne ; `k` omis. Les options sont mélangées à l'affichage. |
| Choix multiple | Les **k premières** options sont les bonnes ; ajouter `2` (ou `3`) en 5e élément. |
| Vrai/Faux | Remplacer la liste d'options par `[true]` ou `[false]`. |

### Exemples

```js
// Choix unique
["Qui peut annuler un Sprint ?",
 ["Le Product Owner","Le Scrum Master","Les Developers","Le management"],
 "Seul le PO peut annuler un Sprint, si le Sprint Goal devient obsolète.",
 "Les autres peuvent influencer le PO, il décide."],

// Choix multiple (2 bonnes réponses)
["Quelles sont des accountabilities des Developers ? (choisir 2)",
 ["Créer le Sprint Backlog","Instiller la qualité via la DoD","Ordonner le Product Backlog","Annuler le Sprint"],
 "Explication…", "REX…", 2],

// Vrai/Faux
["Vrai ou faux : Sprint 0 existe dans Scrum.",
 [false],
 "Faux. Sprint 0 n'existe pas.", "Pas de Sprint 0 ni de hardening."],
```

### Bonnes règles de rédaction

- Entourer les termes anglais de l'examen par `[[ ]]` pour les surligner : `[[Sprint Goal]]`.
- Éviter les guillemets droits `"` dans le texte ; utiliser « » ou les apostrophes.
- Garder quatre options pour les choix unique et multiple.
- Pour le simulateur, chaque thème doit contenir **au moins** autant de questions que son quota à l'examen.
- Après une modification, ouvrir le fichier et lancer un quiz du thème pour vérifier.

### Autres contenus

- **Glossaire** (`GLOSS`) : `["Term","Traduction","Définition",numéroThème]`
- **Guide ou mythe ?** (`MYTHS`) : `["Affirmation",true|false,"Justification"]`
- **Fiches** (`META[n]`) : listes `sub`, `rex`, `etat`, `bp`, `tips`
- **Le bon ordre** (`ORDRE`) : `["Titre",numéroThème,["Étape 1","Étape 2",…],"À retenir"]`, étapes dans le bon ordre
- **Études de cas** (`CAS`) : objet `{t,lieu,org,a,ctx,d}` où chaque décision de `d` vaut `["Question",["Bonne option","Option 2",…],"Justification"]`

---

## 13. Compatibilité

| Navigateur | Version minimale conseillée |
|---|---|
| Google Chrome / Microsoft Edge | 100 |
| Mozilla Firefox | 100 |
| Safari (macOS, iOS) | 15 |
| Chrome Android | 100 |

---

## 14. Dépannage

| Problème | Solution |
|---|---|
| Le fichier s'ouvre en texte brut | Faire clic droit, **Ouvrir avec**, puis choisir un navigateur |
| Le téléchargement échoue sur téléphone | Télécharger depuis un ordinateur ou ouvrir le lien de la page dans le navigateur |
| Les scores ont disparu | Navigation privée, autre navigateur ou données du site effacées |
| Les polices sont différentes | Pas de connexion Internet : comportement normal, le contenu est intact |
| Le code de sauvegarde est refusé | Vérifier qu'il commence par `PSM1-` et qu'il a été copié en entier |
| Le chronomètre semble figé | Revenir sur l'onglet Simulateur : le temps continue de s'écouler en arrière-plan |
| Le bouton Valider reste grisé | Choix multiple : sélectionner exactement le nombre de réponses demandé |

---

## 15. Ressources officielles

- Scrum Guide : <https://www.scrum.org/resources/scrum-guide>
- Scrum Open Assessment : <https://www.scrum.org/open-assessments/scrum-open>
- Certification PSM I : <https://www.scrum.org/assessments/professional-scrum-master-i-certification>
- Evidence-Based Management : <https://www.scrum.org/resources/evidence-based-management>

---

## 16. Avertissements

- Ce portail est un outil de préparation indépendant. Il n'est ni affilié à Scrum.org ni approuvé par Scrum.org.
- Les questions sont originales : elles ne reproduisent pas les questions de l'examen officiel.
- La répartition par thème est une estimation pédagogique.
- La référence est le **Scrum Guide 2020**. Vérifiez sur scrum.org la version en vigueur, le format et le prix de l'examen avant l'inscription.
- Professional Scrum Master™, PSM™ et Scrum.org™ sont des marques de Scrum.org.

---

> **Conseil final :** ne mémorisez pas seulement les définitions. Entraînez-vous sur des mises en situation et demandez-vous toujours : « Quelle est la meilleure réponse conforme au Scrum Guide ? »
