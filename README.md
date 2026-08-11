# Trois sujets de bac générés par IA — et ce qu'il a fallu pour qu'ils tiennent debout

Expérience menée avec **Claude Opus 5**. Point de départ : deux clips YouTube.
Résultat : trois épreuves complètes, chacune avec son corrigé et son barème, au format
officiel de sa discipline.

Ce dépôt archive les six PDF produits et la séquence minimale de prompts permettant de
reproduire l'expérience.

> **Ces sujets sont fictifs.** Ils portent tous un filigrane « épreuve fictive — sujet
> pédagogique, sans valeur d'examen ». Ils n'émanent d'aucune académie et n'ont jamais été
> soumis à des candidats.

---

## Le corpus de départ

Deux documents, choisis sans arrière-pensée pédagogique :

- Jamiroquai, *Virtual Insanity* (1996) — https://www.youtube.com/watch?v=4JkIs37a2JE
- Alliance Ethnik, *Honesty et Jalousie* (1995) — https://www.youtube.com/watch?v=kmfTq6aQP_k

Le troisième document a été choisi par le modèle, différemment pour chaque épreuve :

| Épreuve | Troisième document | Axe retenu |
|---|---|---|
| Musique | Mark Ronson feat. Bruno Mars, *Uptown Funk* (2014) | Prélever ou rejouer : deux façons d'hériter du funk |
| Histoire des arts | Stanley Donen, *Royal Wedding* (1951) | Montrer sans montrer : l'effet et son dispositif |
| Anglais | H. G. Wells, *The Time Machine* (1895) | Elsewhere in time : parler du présent depuis un autre temps |

---

## Contenu du dépôt

| Fichier | Épreuve | Format |
|---|---|---|
| `Sujet_bac_L_specialite_musique_Le-groove-en-heritage.pdf` | Spécialité musique | Écrit 3 h 30, coef. 6 |
| `Corrige_et_bareme_bac_L_specialite_musique.pdf` | — | Corrigé + copie-type rédigée |
| `Sujet_bac_L_histoire_des_arts_Montrer-sans-montrer.pdf` | Spécialité histoire des arts | Écrit 3 h 30, coef. 6 |
| `Corrige_et_bareme_bac_L_histoire_des_arts.pdf` | — | Corrigé des deux sujets au choix |
| `Sujet_bac_L_anglais_LV1_Elsewhere-in-Time.pdf` | Anglais LV1 | Écrit 3 h, coef. 4 |
| `Corrige_et_bareme_bac_L_anglais_LV1.pdf` | — | Corrigé + copie-type en anglais |

---

## La séquence minimale de prompts

Sept prompts suffisent. Les deux prompts en gras sont ceux sans lesquels l'expérience ne
vaut rien.

### 1 — Générer

```
Peux-tu me créer un sujet de bac spécialité musique au bac L en t'appuyant sur ces deux
documents, et un troisième que tu choisiras toi-même :
https://www.youtube.com/watch?v=4JkIs37a2JE
https://www.youtube.com/watch?v=kmfTq6aQP_k
```

Le modèle pose alors des questions de cadrage (structure de l'épreuve, corrigé ou non,
format de sortie). Y répondre prend trente secondes et détermine tout le reste.

### 2 — Protéger

```
Peux-tu mettre en filigrane en arrière des documents que l'épreuve est fictive ?
```

À faire tôt, pas à la fin : un sujet d'examen qui circule sans mention explicite est un
problème.

### 3 — **Auditer** ⭐

```
L'épreuve est-elle cohérente en termes de longueur, de format, d'exercices proposés
et de documents soumis ?
```

**C'est le prompt décisif.** Sans lui, on garde un sujet qui paraît irréprochable à la
lecture. Avec lui, quatre défauts réels sont apparus : une partie sous-dimensionnée pour
sa durée, des diffusions programmées trop tard pour laisser le temps d'écrire, un document
sonore en trop par rapport au format officiel, et une question portant sur un extrait
entendu deux heures plus tôt.

Variante utile pour d'autres disciplines : *« Un élève peut-il traiter ce sujet dans le
temps imparti ? Détaille ta réponse question par question. »*

### 4 — Corriger

```
Applique les corrections. [préciser les arbitrages restants]
```

Le modèle propose un rééquilibrage ; il reste à trancher ce qui relève du choix
pédagogique, pas de la conformité.

### 5 — **Exiger un corrigé rédigé** ⭐

```
Pour le commentaire comparé, propose aussi dans le corrigé une réponse rédigée
intégralement.
```

Un barème par critères ne prouve rien. Une copie-type entièrement rédigée révèle
immédiatement si le sujet est traitable — et donne un modèle distribuable aux élèves.

### 6 — Élargir

```
Dans quelles autres épreuves du bac ces documents auraient-ils pu être proposés ?
```

Fait apparaître les transpositions possibles, avec leurs contraintes propres.

### 7 — Transposer

```
Fais la même chose pour l'histoire des arts et pour l'anglais. Tu pourras resélectionner
un troisième document pour chaque cas, il ne sera pas identique au précédent.
```

C'est ici que le gain de temps devient massif : le corpus est déjà documenté, seul le
format d'épreuve change.

---

## Ce qu'il faut vérifier avant tout usage en classe

Rien de ce qui suit n'est un défaut du modèle : ce sont les limites structurelles de
l'exercice.

1. **Les minutages.** Le modèle n'écoute pas les documents. Les repères temporels des
   corrigés sont des estimations à confirmer par une écoute de contrôle.
2. **Les textes fournis en annexe.** Les trois textes anglais et les notices du dossier
   d'histoire des arts ont été **rédigés pour l'épreuve**, ce qui est indiqué sous chacun
   d'eux. Cela évite de reproduire des paroles de chansons et des articles protégés, et
   permet de calibrer la longueur et le niveau de langue. Chaque corrigé indique par quel
   texte authentique les remplacer.
3. **Le programme limitatif.** Les œuvres dites « du programme » sont désignées par
   convention. À permuter selon le programme de l'année.
4. **Les aménagements assumés.** Le sujet de musique diffuse un troisième extrait sonore,
   ce que le format officiel ne prévoit pas. La note au professeur donne la reformulation
   d'une ligne qui rend le sujet strictement conforme.
5. **La série L n'existe plus** depuis la réforme du lycée (dernière session : 2020). Ces
   sujets sont des sujets types, transposables aux enseignements de spécialité actuels ou
   à un devoir commun.

---

## Ce que l'expérience montre

L'IA absorbe le travail coûteux : rédiger les questions, tenir un barème au quart de point,
documenter un corpus, produire une copie-type, mettre en page. Elle ne peut ni écouter les
documents, ni savoir ce qu'un élève écrit vraiment en une heure, ni connaître la classe, ni
assumer la responsabilité de l'évaluation.

Umberto Eco distinguait trois labyrinthes : le grec, où l'on ne peut pas s'égarer ; le
rhizome, sans centre ni sortie ; et entre les deux le maniériste, avec ses impasses, ses
choix et son fil. Un sujet d'examen doit être le troisième. L'IA dessine les trois avec la
même aisance — elle ne sait pas lequel elle vient de dessiner.

La compétence n'est pas remplacée. Elle se déplace de l'écriture vers la spécification et
le contrôle.

---

## Licence et réutilisation

Les PDF sont partagés à des fins pédagogiques et de documentation. Ils citent des œuvres
protégées à titre de références bibliographiques et n'en reproduisent ni les paroles ni les
enregistrements. Toute réutilisation en classe suppose les vérifications listées ci-dessus.
