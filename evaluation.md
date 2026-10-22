# 📊 Évaluation automatique — Semaine 13 (JavaScript)

> Générée le 2026-10-22 07:12 UTC · commit `326f919` · évaluation déterministe basée uniquement sur le cahier d'exercices et le barème.

## Note finale : **6 / 15**

Exercices : **70 / 95** · Parfaits : 5 / 19 · Non rendus : 0

## 1. Résultat par exercice

| Exercice | Note /5 | Statut | Tests | Recherche /3 | Commit | Feedback |
|---|:-:|---|:-:|:-:|:-:|---|
| **F1** — Ma carte d'apprenant | **3** | 🟠 Résultat incorrect | 4/5 | 0 | ❌ | Ta fiche ne correspond pas au résultat attendu : vérifie la phrase et les 6 typeof (n'oublie pas que typeof null renvoie « object »).<br>• La phrase « Je m'appelle …, j'ai … ans et j'habite à … » n'est pas affichée.<br>• Justifie en commentaire le choix de `const` ou `let` pour tes variables.<br>📚 Recherche non rédigée. |
| **F2** — Le convertisseur de saisie | **4** | 🟡 Règles non respectées | 3/3 | 0 | ❌ | Résultat correct, mais il manque une notion imposée : Number() ou tes explications/prédictions en commentaire.<br>• Explique en commentaire pourquoi le résultat est faux et note tes prédictions avant de tester.<br>📚 Recherche non rédigée. |
| **F3** — Pair ou impair : le tirage des tickets | **4** | 🟡 Règles non respectées | 3/3 | 0 | ❌ | Le tirage fonctionne, mais respecte les consignes : modulo `%`, comparaison `===`, `if / else` et gabarit littéral.<br>• Mot-clé `function` utilisé (`verifierTicket` l.24) : écris une fonction fléchée.<br>📚 Recherche non rédigée. |
| **F4** — Le contrôleur du bus | **5** | ✅ Parfait | 5/5 | 0 | ❌ | Parfait ! Ternaire simple et conditions à trois branches corrects, bornes respectées.<br>📚 Recherche non rédigée. |
| **F5** — Ma première fonction fléchée | **5** | ✅ Parfait | 4/4 | 0 | ❌ | Parfait ! Fonctions fléchées concises avec retour implicite et gabarit littéral.<br>📚 Recherche non rédigée. |
| **F6** — Le compte à rebours | **2** | 🟠 Résultat incorrect | 0/2 | 0 | ❌ | La séquence affichée est fausse : vérifie le départ (10), la condition (>= 1), le pas et le saut du 5.<br>• On attend 10, 9, 8, 7, 6, 4, 3, 2, 1, Décollage ! (le 5 est sauté).<br>• La version qui affiche seulement les pairs (10, 8, 6, 4, 2) est absente.<br>• Message construit avec `+` (ligne 25, 25) : utilise un gabarit littéral `...${x}...`.<br>• Mot-clé `function` utilisé (`saluerClassique` l.24) : écris une fonction fléchée.<br>📚 Recherche non rédigée. |
| **M1** — FizzBuzz kinois | **4** | 🟡 Règles non respectées | 3/3 | 0 | ❌ | Le FizzBuzz est juste, mais respecte les consignes : boucle for, %, === et explication de l'ordre en commentaire.<br>• Explique en commentaire pourquoi l'ordre de tes conditions est important.<br>📚 Recherche non rédigée. |
| **M2** — Le distributeur automatique (DAB) | **5** | ✅ Parfait | 9/9 | 0 | ❌ | Parfait ! Règles vérifiées dans le bon ordre, cas limites gérés, la fonction renvoie son message.<br>📚 Recherche non rédigée. |
| **M3** — Le détecteur de champs vides (Truthy / Falsy) | **4** | 🟡 Règles non respectées | 11/11 | 0 | ❌ | `estRempli` donne les bons résultats, mais elle doit être fléchée, utiliser un ternaire et aucune comparaison.<br>• Note tes prédictions en commentaire avant de tester.<br>📚 Recherche non rédigée. |
| **M4** — Le score par défaut : \|\| contre ?? | **4** | 🟡 Règles non respectées | 5/5 | 0 | ❌ | Les résultats sont justes, mais montre la version `\|\|`, corrige avec `??` et explique le bug en commentaire.<br>• Explique en commentaire pourquoi 0 donne « aucun » avec `\|\|`.<br>📚 Recherche non rédigée. |
| **M5** — La vitre teintée (portée de bloc) | **1** | ❌ Erreur d'exécution | — | 0 | ❌ | Le programme s'arrête encore sur une erreur : une variable déclarée avec const dans un bloc { } n'existe pas en dehors. Une ReferenceError stoppe tout le script, c'est pour ça que afficher() ne s'exécutait jamais.<br>• ReferenceError: commune is not defined<br>📚 Recherche non rédigée. |
| **M6** — Le détective du return | **2** | 🟠 Résultat incorrect | 0/5 | 0 | ❌ | Au moins une fonction renvoie encore undefined : avec des accolades il faut un return, console.log n'est pas un return, et `return` suivi d'un saut de ligne renvoie undefined (ASI).<br>• `doubler(4)` renvoie undefined au lieu de 8.<br>• `calculerTva(1000)` renvoie undefined au lieu de 160.<br>• total vaut null au lieu de 660 : calculerTva doit RENVOYER la TVA.<br>• `saluer('Ney')` renvoie undefined au lieu de Mbote Ney.<br>📚 Recherche non rédigée. |
| **M7** — La tirelire numérique | **5** | ✅ Parfait | 3/3 | 0 | ❌ | Parfait ! Accumulateur bien initialisé, 12 tours exacts et bonus toutes les 4 semaines : 27000 FC.<br>📚 Recherche non rédigée. |
| **M8** — La batterie qui se décharge | **5** | ✅ Parfait | 3/3 | 0 | ❌ | Parfait ! Boucle while avec condition d'arrêt sûre et compteur : 6 h, 10 %.<br>📚 Recherche non rédigée. |
| **A1** — Kadea Express v2 : le calculateur de livraison | **4** | 🟡 Règles non respectées | 9/9 | 0 | ❌ | Les tarifs sont justes, mais respecte les consignes : fonction fléchée, `estUrgent = false` par défaut, Math.round() et if / else if / else.<br>• Mot-clé `function` utilisé (`calculerLivraison` l.26) : écris une fonction fléchée.<br>• `calculerLivraison` doit être une fonction fléchée.<br>📚 Recherche non rédigée. |
| **A2** — Le moteur de paie v2 | **4** | 🟡 Règles non respectées | 7/7 | 0 | ❌ | Les résultats sont justes, mais utilise .forEach(), une boucle for, une fonction fléchée avec `tauxHoraire = 2500` et des gabarits littéraux.<br>• Mot-clé `function` utilisé (`calculerSalaire` l.34) : écris une fonction fléchée.<br>• `calculerSalaire` doit être une fonction fléchée.<br>📚 Recherche non rédigée. |
| **A3** — L'inventaire en console | **1** | ❌ Erreur d'exécution | — | 0 | ❌ | Ton code s'arrête sur une erreur : lis le message, corrige la ligne indiquée et relance ton fichier avec node.<br>• SyntaxError: Unexpected token (ligne 33)<br>📚 Recherche non rédigée. |
| **A4** — Le classement de la promo | **4** | 🟡 Règles non respectées | 9/9 | 0 | ❌ | Les résultats sont justes, mais respecte les consignes : boucle dans calculerMoyenne, .map(), .filter(), .find() avec return, if / else if / else.<br>• Mot-clé `function` utilisé (`calculerMoyenne` l.35) : écris une fonction fléchée.<br>• `calculerMoyenne` doit être une fonction fléchée.<br>📚 Recherche non rédigée. |
| **A5** — Le nombre mystère | **4** | 🟡 Règles non respectées | 4/4 | 0 | ❌ | Le jeu fonctionne, mais respecte les consignes : while, Math.random() + Math.floor(), prompt() + Number(), détection de NaN, gabarits littéraux.<br>• Détecte une saisie invalide avec `Number.isNaN()` (ou `isNaN()`).<br>📚 Recherche non rédigée. |

## 2. Barème officiel (/15)

| Critère | Niveau | Points /3 | Feedback |
|---|---|:-:|---|
| Fondations : variables, types primitifs et conversions | En développement : À améliorer (59 %) | **1** | let utilisé partout par réflexe, ou confusion entre null et undefined. Conversion oubliée : des calculs donnent '2500500' ou NaN sans que ce soit remarqué.<br>_Preuves : F1, F2, M3_ |
| Logique conditionnelle et opérateurs | Compétent : Satisfaisant (70 %) | **2** | if / else if / else corrects, égalité stricte === systématique, modulo maîtrisé (pair / impair, multiples). Ternaire simple fonctionnel.<br>_Preuves : F3, F4, M1, M2, M4_ |
| Fonctions, return et portée | En développement : À améliorer (52 %) | **1** | Confusion entre return et console.log() qui produit des undefined ou des NaN en chaîne. Fonctions appelées sans () ou avec les arguments dans le désordre.<br>_Preuves : F5, M2, M5, M6_ |
| Boucles, accumulateurs et méthodes de tableau | Compétent : Satisfaisant (80 %) | **2** | Boucle for correcte (départ, condition, pas), accumulateur initialisé avant la boucle, while avec une condition d'arrêt sûre. Résultats attendus exacts (27000 FC pour M7, 6 h pour M8).<br>_Preuves : F6, M1, M7, M8 ; niveau Avancé : A2, A3, A4, A5_ |
| Recherche, qualité du code et restitution | Débutant : Insuffisant (16 %) | **0** | Pas de RECHERCHES.md ou aucune source. Code non poussé sur GitHub.<br>_Recherches 0 % · commits par exercice 0 % · règles de code 63 %_ |
| **Total** | | **6 / 15** | |

## Comment lire cette évaluation

| Statut | Signification | Note /5 |
|---|---|:-:|
| ⬜ Non rendu | Fichier absent ou zone de travail vide / non modifiée | 0 |
| ❌ Erreur d'exécution | SyntaxError, ReferenceError, exception ou boucle infinie (> 2 s) | 1 |
| 🟠 Résultat incorrect | Au moins un résultat attendu du cahier n'est pas obtenu | 2 (3 si au moins la moitié des tests passe) |
| 🟡 Règles non respectées | Résultats justes, mais var, ==, concaténation, `function`, `let` inutile ou notion imposée absente | 4 |
| ✅ Parfait | Résultats justes et toutes les règles respectées | 5 |

Recherche /3 : 1 point pour une réponse rédigée (≥ 120 caractères), 1 point pour un test exécuté, 1 point pour un lien source précis. Commit : un commit dont le message cite l'exercice (ex. `feat: M2 dab`).

> ℹ️ L'explication orale de ton code reste évaluée par ton coach. Corrige, commit, merge sur `develop` et push : l'évaluation est relancée automatiquement.
