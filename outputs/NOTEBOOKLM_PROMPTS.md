# NOTEBOOKLM_PROMPTS.md — v5.0
> 6 oraux · 21 jours · 11 prompts premium
> Copier-coller dans NotebookLM Studio (outils marqués ▶ Studio) ou Chat (outils marqués 💬 Chat)

---

## CARTOGRAPHIE DES PROMPTS

| # | Outil | Où | Moment idéal | Durée output |
|---|-------|----|--------------|-------------|
| 1 | Slide Deck | ▶ Studio | J1, après chaque oral | 15 slides |
| 2 | Audio Overview | ▶ Studio | Trajet · veilles Tier 1 | 20-25 min |
| 3 | Study Guide | ▶ Studio | J4, J9, J16 | 20 Q&R |
| 4 | Briefing Doc J-1 | ▶ Studio | Soir avant chaque oral | 1 page |
| 5 | FAQ Attaques | ▶ Studio | J5, J13, J16 | 10 Q&R offensifs |
| 6 | Flashcards | 💬 Chat | Quotidien 10 min | 25 paires |
| 7 | Quiz Jury | 💬 Chat | J-2 chaque oral | 10 questions |
| 8 | Mindmap | 💬 Chat | J1, J9 (transitions) | Structure text |
| 9 | Infographic | 💬 Chat | J2, J5, J12 | Brief visuel |
| 10 | Video Script | 💬 Chat | J5, J11, J16 | Script 3 min |
| 11 | Timeline | 💬 Chat | J1 | Chronologie 21J |
| 12 | English Mock Interview Audio | ▶ Studio | J-3 à J-1 SKEMA + ESSEC · boucle quotidienne | 18 min listen & repeat |

---

## PROMPT 1 — Slide Deck ▶ Studio
> NotebookLM → Studio → Customize Slide Deck

```
Create a 15-slide presentation for multi-school oral exam preparation — 6 schools, 3 tiers.
Language: French throughout.
Audience: Gabriel, Terminale, preparing 6 business school entry interviews (ESCE, emlyon, NEOMA, SKEMA, ESSEC, KEDGE).
Tone: professional, confident, coach-level — never generic.
Design: dark background, large stat numbers, source labels on every data point, minimal text per slide.

SLIDE 1 — COVER
Title: "6 oraux · 21 jours · 3 tiers"
Subtitle: "De ESCE à ESSEC — stratégie, pas chance"
Hook stat: WEF 92M/170M — anchors the entire preparation in documented reality
Key visual: timeline 27 avril → 15 mai with 6 milestones

SLIDE 2 — LA STRATÉGIE (vue d'ensemble)
Title: "Ce n'est pas le même oral partout"
Content: 3-tier table
- Tier 1 (ESSEC/emlyon): Opinion défendue · personnalité · "Pourquoi toi ?"
- Tier 2 (SKEMA/NEOMA/KEDGE): Cohérence · projet clair · énergie
- Tier 3 (ESCE): Motivation · connaissance école · projection
Key insight: "Adapter le fond selon le jury — le candidat standard est recalé partout"

SLIDE 3 — TGM INSEAD : L'histoire de l'énergie
Title: "Toute l'histoire humaine est une quête d'énergie"
Content: 5-row table — Feu / Cognitive / Agriculture / Industrielle / Numérique
For each: what it unlocked + business implication
Source: TGM INSEAD
Key insight: "Le capitalisme organise cette énergie. La finance en est le système nerveux."

SLIDE 4 — Matrice Us/Future
Title: "Le seul quadrant durable"
Content: 2x2 grid
- Me/Now (red) · Me/Future (amber) · Us/Now (blue) · Us/Future (green highlighted)
Key insight: "Former des changemakers = opérateurs Us/Future — pas des idéalistes"

SLIDE 5 — Les 5 fonctions universelles (Kaufman)
Title: "Ce qu'est vraiment une entreprise"
Content: 5 functions table — Création valeur / Marketing / Vente / Livraison / Finance
Source: Personal MBA, Kaufman 2010
Key insight: "Startup tech, boulangerie artisanale, Fortune 500 — aucune exception. Segway l'a appris à ses dépens."

SLIDE 6 — RONIC > OCC
Title: "Créer de la valeur, pas juste en mesurer"
Content:
- Formula: RONIC > OCC → NPV positive → Création de valeur
- Quote: "The more uncertain the environment, the MORE we should invest. Think VC, not banker."
- Segway counter-example: 23 000 unités / 50 000 visées
Source: TGM INSEAD

SLIDE 7 — WEF 2025 : 6 chiffres à citer naturellement
Title: "Pas réciter — intégrer dans un raisonnement"
Content: 6 big-number stats
- 92M / 170M · 44% · 39% · $2T · 6/9 · 83%
Each with: chiffre en grand + source + phrase orale calibrée
Design: monospace font, source label below each stat

SLIDE 8 — Les 5 mégatendances
Title: "5 forces qui redessinent les métiers"
Content: 5 items
① IA & automatisation cognitive — rupture des emplois d'entrée
② Transition climatique — $2T investis, ESG comme avantage compétitif
③ Recomposition géopolitique — fin mondialisation linéaire, friendshoring
④ Révolution des données — management hybride valorisé
⑤ Quête de sens Gen Z — 39% confiance institutions effondrée

SLIDE 9 — Red → Blue World
Title: "Le leadership a muté"
Content: two-column comparison
RED WORLD: top-down · ego · command & control · autorité par grade
BLUE WORLD: collaboratif · distribué · authenticité · co-construction
Key stat: 39% confiance institutions → "Le Red World ne fonctionne plus"
Source: TGM INSEAD + WEF

SLIDE 10 — Ce que l'IA ne remplace pas
Title: "Être celui qui décide ce que l'algorithme fait"
Content: 3 columns — Jugement / Créativité / Confiance
Sub-items: WEF 5 compétences 2030 (Intelligence émotionnelle · Foresight · Leadership authentique · Diplomatie corporative · Agilité)
Source: WEF Future of Jobs 2025

SLIDE 11 — Pourquoi une grande école ? 3 arguments solides
Title: "Mon choix — trois arguments documentés"
Content: 3 numbered points adaptés au tier de l'école cible
① Learning-by-doing + Junior-Entreprise dès L1 (Kaufman)
② Réseau activable = compétences × confiance (WEF)
③ MSc / spécialisation → profil hybride valorisé en 2030
Key insight: "Pas 'j'aime le business'. Un raisonnement."

SLIDE 12 — Structure universelle de réponse
Title: "La formule qui marque un jury"
Content: 3-step formula (large visual)
① IDÉE PRINCIPALE — 1 phrase claire
② EXEMPLE CONCRET — situation réelle, pas abstraite
③ LIEN AVEC L'ÉCOLE — pourquoi ça compte ici
Key insight: "90% des candidats ratent l'étape 3"

SLIDE 13 — Méthode document iconographique
Title: "8 minutes · 3 niveaux · 0 improvisation"
Content: 3-level method timeline
Niveau 1 (1 min): Ce que je vois — factuel
Niveau 2 (3 min): Ce que ça signifie — mécanisme économique
Niveau 3 (4 min): Ce que ça m'inspire — WEF + opinion + lien école
Key technique: "Toujours finir Niveau 3 avec une opinion défendable"

SLIDE 14 — Checklist J-1 universelle
Title: "La veille de chaque oral — 5 vérifications"
Content: checklist format
① Je connais 1 programme / asso spécifique à cette école
② J'ai 2 questions préparées pour le jury
③ Mon pitch 90 sec est fluide (pas récité)
④ Je connais le trajet · Arrive 15 min en avance
⑤ J'ai relu mon dernier feedback d'oral

SLIDE 15 — CONCLUSION
Title: "Je suis prêt à le prendre au sérieux"
Content:
- Chiffre d'ouverture: 92M/170M — "La disruption touche en premier les emplois d'entrée"
- "Je comprends ce que je choisis et pourquoi."
- Three commitments:
  ① Pratiquer les 5 fonctions dès L1 (Junior-Entreprise)
  ② Penser Us/Future — créer de la valeur durable
  ③ Construire le réseau qui transforme les compétences en impact
- Final quote: "[Cette école] est la première étape sérieuse de ce chemin."
```

---

## PROMPT 2 — Audio Overview ▶ Studio
> NotebookLM → Studio → Customize Audio Overview

```
Create a full French coaching audio episode for multi-school oral exam preparation — 6 schools, 3 tiers, 21 days.

Context: Gabriel is in Terminale, preparing entry interviews for ESCE (April 27), emlyon (May 2), NEOMA (May 8), SKEMA (May 9), ESSEC (May 11), KEDGE (May 15). Tier 1 priority: ESSEC + emlyon. Oral anglais may be tested at Tier 1 schools.

Format: two hosts (coach + challenger). Coach guides, challenger plays jury and pushes back hard on Tier 1 questions. French throughout. High energy, no filler. Approximately 22 minutes.

PART 1 — Hook stratégique (2 min)
Coach opens: "Le WEF documente : 92 millions de postes déplacés, 170 millions créés. La disruption touche en premier les emplois d'entrée de gamme. C'est le contexte dans lequel Gabriel passe 6 oraux en 21 jours."
Challenger: "Pourquoi passer 6 oraux au lieu de se concentrer sur 1 ?"
Coach explains: stratégie tier — maximiser les chances sans disperser l'énergie. 50% énergie sur Tier 1.

PART 2 — La différence entre les jurys (2 min)
Coach walks through the 3-tier differentiation
Challenger: "Concrètement, qu'est-ce qui change entre un jury ESSEC et un jury NEOMA ?"
Coach answers: ESSEC = opinion sous pression · emlyon = "Pourquoi toi ?" · Tier 2 = cohérence + projet
Key takeaway: "Le candidat standard est recalé partout. Adapter n'est pas tricher — c'est comprendre."

PART 3 — TGM + Kaufman stress test (2 min)
Coach recites: 5 révolutions énergétiques + Us/Future + 5 fonctions Kaufman
Challenger jury role: "Startup tech et boulangerie — ces 5 fonctions s'appliquent vraiment aux deux ?"
Coach models with Segway: 23 000 unités / 50 000 visées — "Le marché n'existait pas."

PART 4 — WEF challenge — jury sceptique (2 min)
Challenger: "Vous citez le WEF — c'est du macro, ça ne prouve rien."
Coach models the answer: "Je les cite comme points d'ancrage, pas comme vérités absolues. 44% des compétences perturbées en 5 ans. Ce sont des données."
Drill: 6 stats en 90 secondes avec phrase calibrée chacune

PART 5 — Document iconographique — 2 exemples en live (3 min)
Coach explains: méthode 3 niveaux (1 min / 3 min / 4 min)
Challenger gives: "Image d'un datacenter avec racks de serveurs."
Coach models 3-level live answer
Challenger gives: "Carte du monde avec flux commerciaux interrompus."
Coach models: friendshoring → 83% G7 = Chine+Inde → "Un manager de 2030 pense en blocs."
Key: "Toujours finir Niveau 3 avec une opinion défendable et un lien avec l'école."

PART 6 — Questions spécifiques Tier 1 (3 min)
Coach: "Ces questions sont réservées aux jurys ESSEC et emlyon. Les autres candidats ne les préparent pas."
Challenger plays hard jury — ESSEC style:
Q: "Convaincez-moi en 2 minutes que vous méritez une place ESSEC."
Coach models: argument solide + exemple authentique + vision 10 ans (pas CV récité)
Challenger: "Pourquoi toi et pas un autre très bon candidat ?" — emlyon style
Coach models: réponse unique, pas générique. "Ce qui me différencie, c'est la façon dont je pense."
Key: "Ne jamais être consensuel chez Tier 1. Avoir une opinion. La défendre calmement."

PART 7 — Oral anglais Tier 1 (2 min)
Coach: "ESSEC et emlyon peuvent tester l'anglais en profondeur. Voici les 3 moments."
① Self-presentation 5 min — structure: stat WEF → pourquoi école → vision
② Thème économique — "AI and the future of work" · "The green transition as competitive advantage"
③ Vision 10 ans: "At the intersection of management and digital transformation..."
Challenger tests en anglais: "What makes you different from other candidates with the same grades?"
Coach models answer in English: confident, structured, WEF-anchored

PART 8 — Rapid fire — 10 chiffres + règle d'or finale (2 min)
Challenger calls numbers 1-10 in random order
Coach answers each: chiffre + phrase calibrée (pas juste le chiffre)
Closing rule: "Structure mémorisée, mots improvisés. Un chiffre cité naturellement vaut 10 chiffres récités."
Final coaching: "Tu n'as pas à être parfait. Tu as à être toi-même — préparé, ancré, défendable."
```

---

## PROMPT 3 — Study Guide ▶ Studio
> NotebookLM → Studio → Customize Study Guide

```
Create a structured study guide for oral exam preparation across 6 business schools (ESCE, emlyon, NEOMA, SKEMA, ESSEC, KEDGE).
Language: French. Format: 20 Q&R grouped in 4 blocks.

BLOC 1 — FRAMEWORKS FONDAMENTAUX (5 Q&R)
Test mastery of TGM INSEAD + Kaufman + WEF. Each question requires a structured answer of 3-5 sentences maximum.
Include questions on:
- Les 5 révolutions énergétiques TGM et leur implication business
- La matrice Us/Future et son application aux oraux
- Les 5 fonctions universelles Kaufman avec exemple concret (pas Segway uniquement)
- RONIC > OCC expliqué sans jargon en 30 secondes
- Red→Blue World : ce que ça change pour le leadership aujourd'hui

BLOC 2 — CHIFFRES WEF ET MÉGATENDANCES (5 Q&R)
Test ability to cite stats with calibrated oral phrases (not just numbers).
Include:
- Les 6 stats WEF avec source ET phrase orale pour chacune
- La mégatendance la plus pertinente pour justifier une école de commerce
- Ce que l'IA ne remplace pas (WEF + TGM)
- Le paradoxe énergie propre : urgence + rentabilité
- Recomposition géopolitique : friendshoring + basculement G7

BLOC 3 — QUESTIONS JURY PAR TIER (5 Q&R)
Test differentiation between school tiers in actual answers.
Include:
- "Pourquoi cette école ?" pour ESSEC vs emlyon vs NEOMA (réponses différentes)
- "Pourquoi toi ?" — comment répondre à emlyon sans être générique
- "Votre projet pro est vague" — réponse Tier 1 vs réponse Tier 2
- "L'école de commerce ne sert plus à rien avec l'IA" — réfutation structurée
- Questions pour le jury : 2 exemples par école, spécifiques et préparés

BLOC 4 — DOCUMENT ICONOGRAPHIQUE ET ORAL ANGLAIS (5 Q&R)
Include:
- Structure des 3 niveaux avec timing (1/3/4 min)
- Modélisation complète pour un visuel IA / datacenter
- Modélisation complète pour un visuel géopolitique / carte du monde
- Self-presentation 5 min en anglais : structure et mots-clés
- "What's your 10-year vision?" — réponse anglais ancrée WEF + école

Format each Q&R as:
QUESTION : [question posée par le jury]
RÉPONSE ATTENDUE : [réponse modèle en 3-5 phrases]
FRAMEWORK UTILISÉ : [TGM / WEF / Kaufman / Tier 1 spécifique]
PIÈGE À ÉVITER : [erreur classique des candidats]
```

---

## PROMPT 4 — Briefing Doc J-1 ▶ Studio
> NotebookLM → Studio → Customize Briefing Doc

```
Create 6 separate one-page briefing documents — one per school — for last-evening review before each oral exam.
Language: French. Format: dense but readable in 10 minutes. No fluff.

Each briefing doc must contain exactly these 6 sections:

SECTION 1 — PITCH D'OUVERTURE (30 secondes)
The exact opening sentence with WEF stat + transition to school choice.
Calibrated for [SCHOOL NAME] jury style.

SECTION 2 — 3 RAISONS PRÉCISES ET DIFFÉRENTES DE CHOISIR CETTE ÉCOLE
Specific to this school only — not copy-pasted from other schools.
Tier 1 (ESSEC/emlyon): deeper, more personal, connected to identity
Tier 2 (NEOMA/SKEMA/KEDGE): coherence + project + concrete engagement
Tier 3 (ESCE): motivation + concrete projection + knowledge of school life

SECTION 3 — 3 STATS WEF À CITER NATURELLEMENT POUR CE JURY
Choose the 3 most relevant stats for this school's values and jury profile.
Include the calibrated oral phrase for each.

SECTION 4 — 2 QUESTIONS À POSER AU JURY
Specific to this school — shows genuine research and reflection.
Not "How do you see the school evolving?" (too generic).
Examples: MSc pathway / specific program / alumni trajectory / junior enterprise missions.

SECTION 5 — L'ATTAQUE LA PLUS PROBABLE + RÉPONSE CALIBRÉE
The most likely tough question for THIS school's jury.
Tier 1: "Pourquoi toi ?" or "Convaincez-moi en 2 minutes"
Tier 2: "Votre projet pro est vague" or "Pourquoi pas une autre école ?"
Tier 3: "Pourquoi choisir l'ESCE ?" with genuine knowledge required

SECTION 6 — 1 PHRASE DE CLÔTURE MÉMORISÉE
The closing sentence that connects the interview to the school's mission.
Tier 1 version: assertive, vision-driven
Tier 2 version: clear and committed
Tier 3 version: warm and projected

Generate briefing docs for: ESCE · emlyon · NEOMA · SKEMA · ESSEC · KEDGE
Label each doc clearly with the school name and date.
```

---

## PROMPT 5 — FAQ Attaques ▶ Studio
> NotebookLM → Studio → Customize FAQ

```
Create a FAQ focused exclusively on difficult, destabilizing, and trap questions from business school juries.
Language: French. Format: 10 Q offensive/defensive — grouped by difficulty level.
Audience: Gabriel, Terminale, preparing for Tier 1 (ESSEC/emlyon) and Tier 2 (NEOMA/SKEMA/KEDGE) juries.

NIVEAU 1 — Questions standard creusées (3 Q&R)
These look easy but most candidates answer poorly.
Include:
Q: "Quelles sont vos 3 qualités ?"
→ Wrong answer: "je suis curieux, j'aime le challenge, je suis travailleur"
→ Right answer: [specific, personal, supported by example]

Q: "Quel est votre projet professionnel ?"
→ Wrong answer: vague / "je veux travailler en finance"
→ Right answer: [precise on skills, open on sector, anchored in WEF 2030]

Q: "Pourquoi cette école et pas une autre ?"
→ Wrong answer: "votre réputation, votre réseau"
→ Right answer: [3 specific reasons differentiated from other schools]

NIVEAU 2 — Questions déstabilisantes standard (4 Q&R)
Designed to test resilience and authenticity.
Include:
Q: "L'école de commerce ne sert plus à rien avec l'IA"
Q: "Vous n'avez aucune expérience professionnelle réelle"
Q: "Votre projet pro est trop vague — c'est flou"
Q: "Pourquoi pas une licence d'économie, c'est plus rigoureux ?"

For each: wrong answer pattern + calibrated answer + framework used

NIVEAU 3 — Questions exclusives Tier 1 (3 Q&R)
Questions only ESSEC and emlyon jurys ask. Most candidates are not prepared.
Include:
Q ESSEC: "Convaincez-moi en 2 minutes que vous méritez une place ici."
→ Trap: reciting CV
→ Answer: one strong argument + authentic example + 10-year vision

Q emlyon: "Pourquoi toi et pas un autre très bon candidat ?"
→ Trap: generic qualities
→ Answer: what makes Gabriel's thinking unique (not his grades)

Q emlyon: "Qu'est-ce qui vous a vraiment changé cette année ?"
→ Trap: schoolwork-related answer
→ Answer: authentic personal story, specific, with lesson learned

Format: for each Q&R include
QUESTION JURY : [exact wording]
ERREUR CLASSIQUE : [what 90% of candidates say]
RÉPONSE CALIBRÉE : [model answer in 4-6 sentences]
FRAMEWORK : [TGM / WEF / Kaufman / Tier 1 specific]
SIGNAL QUI MARQUE LE JURY : [what makes the difference]
```

---

## PROMPT 6 — Flashcards 💬 Chat
> Coller dans le Chat NotebookLM

```
Génère 25 flashcards pour mémorisation active — préparation oraux 2026.
Format : RECTO | VERSO pour chaque carte. Groupées en 3 decks.

DECK A — Chiffres WEF (10 cartes)
Format recto : Chiffre seul (ex: "92M / 170M")
Format verso : Source + phrase orale calibrée complète

Cartes :
1 | 92M / 170M → WEF FoJ 2025 | "Le solde est positif mais la disruption est massive — et elle touche en premier les emplois d'entrée"
2 | 44% → WEF FoJ 2025 | "En 5 ans, 44% des compétences actuelles seront perturbées — la formation doit être agile"
3 | 39% → OCDE/WEF | "Seulement 39% de confiance dans les institutions — le leadership authentique est un premium"
4 | $2T → WEF Energy 2025 | "2 000 milliards investis en énergie propre en 2024 — la transition verte est maintenant rentable"
5 | 6/9 → WEF Risks 2025 | "6 des 9 limites planétaires franchies — l'urgence est documentée, pas militante"
6 | 83% → WEF Futures 2030 | "Le PIB Chine+Inde représente 83% du G7 en 2021 — le centre de gravité a basculé"
7 | RONIC > OCC → TGM INSEAD | "Quand le rendement dépasse le coût du capital, on crée de la valeur — pas juste de la croissance"
8 | 70/20/10 → TGM INSEAD | "70% du développement professionnel se fait sur le terrain — pas en cours"
9 | 5 fonctions → Kaufman PMBA | "Présentes dans chaque entreprise sans exception — startup, boulangerie ou Fortune 500"
10 | Us/Future → TGM INSEAD | "Le seul quadrant durable par conception — la mission d'une grande école"

DECK B — Questions jury × réponse-clé (10 cartes)
Format recto : Question jury exacte
Format verso : Framework à utiliser + première phrase de réponse

Inclure : Q1 Pourquoi cette école · Q2 Autres orientations · Q6 3 points forts · Q7 Avenir pro · Q8 Actualité · Q10 Rôle en groupe · Q11 RSE · Q12 Situation difficile · Q13 Changemaker · Attaque IA vs école de commerce

DECK C — Différenciateurs par école (5 cartes)
Format recto : Nom de l'école
Format verso :
① Ce que le jury cherche vraiment
② 1 argument spécifique irremplaçable
③ 1 question à leur poser

Cartes : ESSEC · emlyon · NEOMA · SKEMA · KEDGE

Consigne d'utilisation : Timer 2 min par carte · Répondre à voix haute · Ne pas regarder le verso avant d'avoir répondu.
```

---

## PROMPT 7 — Quiz Jury 💬 Chat
> Coller dans le Chat NotebookLM — relancer autant de fois que nécessaire

```
Lance une simulation de jury d'oral d'école de commerce.
Tu joues le rôle d'un jury composé de : 1 professeur + 1 alumni + 1 professionnel.
Gabriel est le candidat (Terminale, préparant ses oraux).
Langue : français. Durée simulée : 20 minutes.

CONSIGNES DU JURY :
- Poser 8 à 10 questions dans cet ordre : présentation → motivations → frameworks → actualité → questions déstabilisantes → questions pour nous
- Après chaque réponse : donner un feedback court (1-2 lignes) sur ce qui a bien fonctionné et ce qui manque
- Creuser TOUT ce que Gabriel mentionne (effet mock interview officiel)
- Niveau de jury : [choisir selon le jour]
  → TIER 3 (ESCE) : bienveillant, cherche la motivation et la projection
  → TIER 2 (NEOMA/SKEMA/KEDGE) : sérieux, cherche cohérence et clarté
  → TIER 1 EMLYON : exigeant, cherche "Pourquoi toi ?" et maker spirit
  → TIER 1 ESSEC : très exigeant, cherche opinion défendue sous pression

DÉBUT DE SIMULATION :
"Bonjour Gabriel. Commencez par vous présenter en 90 secondes."

Après la simulation complète :
- Score global sur 20 (critères : structure / authenticité / maîtrise frameworks / WEF cités / cohérence avec l'école / présence)
- Top 3 points forts
- Top 3 points à travailler avant l'oral réel
- 1 question surprise que le jury aurait pu poser et que Gabriel n'a pas anticipée
```

---

## PROMPT 8 — Mindmap 💬 Chat
> Coller dans le Chat NotebookLM

```
Génère une carte mentale textuelle structurée — préparation oraux 2026.
Format : indentation hiérarchique (nœud central → branches → sous-branches).
Langue : français.

NŒUD CENTRAL : "Prépa Oraux 2026 — Gabriel"

BRANCHE 1 — 6 ORAUX
├── Tier 1 (50% énergie)
│   ├── ESSEC Cergy · 11 mai · Opinion défendue sous pression
│   └── emlyon Paris · 2 mai · "Pourquoi toi ?" · Maker spirit
├── Tier 2 (30% énergie)
│   ├── NEOMA Paris · 8 mai · Cohérence + projet clair
│   ├── SKEMA Paris · 9 mai · International + digital
│   └── KEDGE Paris · 15 mai · Management responsable
└── Tier 3 (20% énergie)
    └── ESCE Paris · 27 avril · Motivation + projection

BRANCHE 2 — FRAMEWORKS FONDAMENTAUX
├── TGM INSEAD
│   ├── 5 révolutions énergétiques
│   ├── Matrice Us/Future (seul quadrant durable)
│   └── Red→Blue World (leadership muté)
├── Personal MBA (Kaufman)
│   ├── 5 fonctions universelles
│   ├── Iron Law of Market
│   └── Segway contre-exemple
└── WEF 2024-2025
    ├── Future of Jobs 2025 (92M/170M · 44%)
    ├── Global Risks 2025 (6/9 limites)
    └── Global Economic Futures (83% G7)

BRANCHE 3 — STRUCTURE RÉPONSE
├── ① Idée principale (1 phrase)
├── ② Exemple concret (situation réelle)
└── ③ Lien avec l'école (pourquoi ici)

BRANCHE 4 — DOCUMENT ICONOGRAPHIQUE
├── Niveau 1 : Ce que je vois (1 min)
├── Niveau 2 : Ce que ça signifie (3 min)
└── Niveau 3 : Ce que ça m'inspire (4 min → opinion + école)

BRANCHE 5 — ORAL ANGLAIS (Tier 1)
├── Self-presentation 5 min
├── Thème économique 10 min
└── Vision 10 ans en anglais

BRANCHE 6 — ERREURS À ÉVITER
├── Être le même candidat partout
├── Réponses scolaires / consensuelles
├── Réciter les chiffres sans phrase calibrée
└── Oublier de lier à l'école en fin de réponse

Rends la carte mentale utilisable pour une révision de 10 minutes en J1 et J9.
```

---

## PROMPT 9 — Infographic · Document Iconographique Drill 💬 Chat
> Coller dans le Chat NotebookLM — exercice répété avec visuel différent à chaque fois

```
Lance un exercice de préparation au document iconographique.
Tu joues le rôle du jury IÉSEG (ou école Tier 1).
Gabriel a 8 minutes de préparation puis 12 minutes de présentation.

ÉTAPE 1 : Choisis un visuel parmi ces 5 catégories (en décrire un aléatoirement) :
- IA / robot / datacenter
- Forêt brûlée / dégradation climatique
- Carte du monde / flux géopolitiques
- Publicité / consommation / marque
- Manifestation / foule / institution

ÉTAPE 2 : Décris le visuel choisi en 3 lignes (comme si tu le montrais à l'oral).

ÉTAPE 3 : Gabriel prépare sa présentation 3 niveaux :
→ Niveau 1 (1 min) : Ce que je vois — purement factuel
→ Niveau 2 (3 min) : Ce que ça signifie — mécanisme économique / social / géopolitique
→ Niveau 3 (4 min) : Ce que ça m'inspire — mégatendance WEF + chiffre + opinion + lien école

ÉTAPE 4 : Feedback du jury sur :
- Est-ce que le Niveau 1 était trop long ? (erreur classique)
- Est-ce que le Niveau 3 était assez personnel et défendable ?
- Est-ce que la stat WEF était citée naturellement ou récitée ?
- Score sur 10 · 1 point d'amélioration prioritaire

Relancer avec un nouveau visuel autant de fois que nécessaire.
Objectif : 5 visuels traités = Gabriel est prêt pour l'exercice iconographique.
```

---

## PROMPT 10 — Video Script · Auto-enregistrement 💬 Chat
> Coller dans le Chat NotebookLM — pour générer un script à filmer

```
Génère un script de 3 minutes pour auto-enregistrement vidéo — préparation orale école de commerce.
Langue : français. Ton : naturel, confiant, pas récité. Niveau : candidat Terminale préparant Tier 1.

OBJECTIF : Gabriel se filme, se réécoute, corrige ton et posture avant les oraux ESSEC / emlyon.

STRUCTURE DU SCRIPT (3 minutes exactement — rythme naturel) :

SEGMENT 1 — Ouverture (30 sec)
Phrase d'accroche WEF + transition naturelle vers la motivation école de commerce.
"Le WEF documente précisément : 92 millions de postes vont disparaître d'ici 2030, mais 170 millions vont être créés. Ce n'est pas une crise — c'est une transformation. Et c'est exactement pour ça que j'ai décidé de..."

SEGMENT 2 — Pourquoi une grande école (45 sec)
3 arguments structurés (Kaufman 5 fonctions + learning-by-doing + réseau activable)
Citer naturellement : "Ce que Kaufman appelle les 5 fonctions universelles..."
Terminer par : "Ce n'est pas une formation générale. C'est un système qui construit le profil que le marché de 2030 recrute."

SEGMENT 3 — Pourquoi CETTE école (45 sec — [adapter au nom de l'école])
Version ESSEC : opinion + ambition crédible + différenciation
Version emlyon : maker spirit + action dès L1 + "Pourquoi moi ?"
Version NEOMA/SKEMA/KEDGE : cohérence + projet + connaissance école

SEGMENT 4 — Vision 10 ans (30 sec)
Ancrage WEF compétences 2030 : intelligence émotionnelle + foresight + agilité
"Dans 10 ans, je me vois à l'intersection du management et de la transformation numérique..."

SEGMENT 5 — Clôture (30 sec)
Phrase de conclusion mémorisée — lien avec la mission de l'école
"[Cette école] est la première étape sérieuse de ce chemin."

INSTRUCTIONS DE TOURNAGE :
- Filmer debout ou assis droit — pas avachi
- Regarder la caméra (pas les notes)
- Si tu hésites sur un mot : continuer — ne pas recommencer
- Visionner le lendemain à froid · noter : rythme / regard / mains / tics de langage

Adapte le script pour chacune des 6 écoles (6 versions légèrement différentes).
```

---

## PROMPT 11 — Timeline 💬 Chat
> Coller dans le Chat NotebookLM — vue d'ensemble chronologique

```
Génère une timeline textuelle du plan de préparation 21 jours — 6 oraux.
Format : chronologie jour par jour avec focus, outil NotebookLM recommandé, et niveau d'intensité.
Langue : français.

PÉRIODE : 25 avril → 15 mai 2026

Pour chaque jour, indiquer :
- Date + jour de la semaine
- Focus principal (1 ligne)
- Outil NotebookLM recommandé (Slides / Audio / Study Guide / Briefing / FAQ / Flashcards / Quiz / Mindmap / Infographic / Video)
- Intensité : 🟢 légère / 🟡 modérée / 🔴 intensive / 🏫 ORAL

Exemple format :
SAM 25 AVR · J1 | Fondations : pitch 90 sec + 3 points forts | Slides + Mindmap | 🟡

Générer la timeline complète du J1 au J21 avec :
- Oraux marqués clairement avec l'école + tier
- Jours de récupération identifiés (J12, J18)
- Jours de simulation intensive (J2, J5, J11, J16)
- Jours J-1 toujours en 🟢 (pas surcharger avant un oral)
- Oral anglais Tier 1 intégré (J5, J7, J10, J16)

À la fin : 3 règles d'or du planning
① Ne jamais simuler à fond le jour J-1 — révision légère uniquement
② Feedback écrit dans les 2h après chaque oral — le plus précieux des outils
③ Audio Overview pendant les trajets — apprentissage passif gratuit
```

---

## PROMPT 12 — English Mock Interview Audio ▶ Studio
> NotebookLM → Studio → Customize Audio Overview
> Moment idéal : trajets · veilles SKEMA (9 mai) · veille ESSEC (10 mai) · répétition possible en boucle

```
Create an English-language audio coaching session for a French student preparing business school oral exams.

FORMAT — "Listen & Repeat" Mock Interview
Two voices:
- INTERVIEWER: native English-speaking jury member from a top business school
- COACH: English accent coach who plays the model candidate AND highlights key phrases to repeat

Structure the audio in 3 parts — total target duration: 18 minutes.

---

PART 1 — SELF-PRESENTATION (4 min)
Interviewer asks: "Could you introduce yourself in English?"
Coach delivers a model 90-second answer, then says:
"Pause. Repeat these 3 phrases after me — slowly:"
① "The World Economic Forum documents 92 million jobs displaced by 2030 — but 170 million new ones created."
② "I don't want to study management. I want to practice it from day one."
③ "I'm here because disruption hits entry-level jobs first — and I want to be on the right side of that shift."
After each phrase: pause 4 seconds for the listener to repeat.

Then interviewer asks: "Why this business school specifically?"
Coach gives a 45-second model answer (school-agnostic, adaptable), then extracts 2 key phrases to repeat:
① "What draws me to this program is [the maker spirit / the international multicampus / the responsible management focus] — not just its reputation."
② "I chose to apply here because I want to build something, not just learn about it."
Pause 4 seconds after each phrase.

---

PART 2 — CORE QUESTIONS (8 min)
Run through 6 questions. For each: interviewer asks → coach gives model answer (45-60 sec) → coach extracts 1 KEY PHRASE to repeat (pause 4 sec).

Q1: "What is your professional project in 5 to 10 years?"
KEY PHRASE: "I see myself at the intersection of management and digital transformation — where the WEF identifies the highest demand for new skills by 2030."

Q2: "What makes you different from other strong candidates?"
KEY PHRASE: "I don't have a different résumé. I have a different way of seeing problems — and I can show you that, not just tell you."

Q3: "What is your greatest weakness?"
KEY PHRASE: "My weakness is impatience — I move fast and sometimes outpace the people around me. I'm actively working on it by [example]. It's a work in progress, not a blind spot."

Q4: "Tell me about a challenge you overcame."
KEY PHRASE: "The lesson wasn't that I succeeded. It was that I stayed when it was uncomfortable — and that's when I actually learned something."

Q5: "What do you think about artificial intelligence and the future of work?"
KEY PHRASE: "AI doesn't replace ambition. It replaces repetition. The question is whether you're building skills that machines can't automate — and business school is exactly where I want to answer that question."

Q6 (SKEMA specific): "Please comment on this image." [Coach simulates an image description]
Coach models the structure: describe → interpret → connect to business → personal angle
KEY PHRASE: "The first thing I notice is [X]. What this suggests to me, from a business perspective, is [Y]. And personally, this connects to [Z]."
Pause 4 seconds.

---

PART 3 — ADVANCED PHRASES BANK (6 min)
Coach presents 10 high-impact English phrases for French candidates. For each:
- Say the phrase naturally at normal speed
- Explain why it works (10 seconds)
- Repeat it slowly for the listener to echo
- Pause 4 seconds

PHRASES TO INCLUDE:
① "I'd like to take a moment to structure my answer." [when you need thinking time — sounds composed, not lost]
② "That's a fair challenge — let me push back slightly." [when defending a position under jury pressure]
③ "The data actually supports a different conclusion here." [to cite WEF stats with confidence]
④ "What I find compelling about this school specifically is..." [personalised answer opener]
⑤ "I've been reflecting on this question, and my honest answer is..." [for weakness / failure questions]
⑥ "Rather than tell you, let me give you a concrete example." [to avoid abstract answers]
⑦ "This connects directly to why I'm sitting in front of you today." [to link any answer back to motivation]
⑧ "I hold that view — and I'm happy to defend it." [ESSEC: signal you won't be destabilised]
⑨ "In 10 years, I want to be the kind of manager who..." [open a vision answer with personality]
⑩ "Thank you — that question made me think." [elegant response to a difficult or unexpected question]

End with coach's closing: "Listen to this session daily for 3 days before each English oral. Don't memorise the answers — memorise the structure and the key phrases. Confidence in English comes from having a toolkit, not a script."

---

LANGUAGE: 100% English throughout — no French.
TONE: Warm but demanding. The coach is encouraging AND rigorous.
PACING: Slightly slower than natural speech — French learner friendly.
KEY CONSTRAINT: Every "repeat after me" moment must be followed by exactly 4 seconds of silence.
```

---

*NOTEBOOKLM_PROMPTS.md v5.0 · 8 oraux · 21 jours · 12 prompts premium*
*▶ Studio : Prompts 1-5 + 12 · 💬 Chat : Prompts 6-11*
*Sources : TGM INSEAD · Personal MBA (Kaufman) · WEF Strategic Library 2024-2025*
