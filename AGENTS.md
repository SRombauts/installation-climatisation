# Projet — Installation de climatisation (maison à Nanterre)

> Document de travail destiné à préparer le projet d'installation de climatisation,
> et à pouvoir être **partagé avec les voisins et la copropriété** (rédigé en français).
> Les sections marquées **[À COMPLÉTER]** attendent vos précisions.

---

## 1. Objectif du projet

Rafraîchir et déshumidifier la maison pendant les épisodes de forte chaleur / canicule.

**Objectifs annexes :**
- Documenter le projet en **français** pour pouvoir le **partager avec les voisins et la
  copropriété**.
- **Publier ce dossier en ligne (HTML) via GitHub Pages avec Jekyll**, pour un partage
  facile (lien web) avec les voisins. Le plan ASCII ([`plan.md`](plan.md)) et ce document
  doivent rester lisibles une fois publiés. **[À METTRE EN PLACE]**

**Contexte déclencheur (juin 2026)** : épisode caniculaire avec nuits > 27 °C, absence de
brise, impossibilité de rafraîchir la nuit en ouvrant les fenêtres. La maison stagne
à ~29 °C le matin et dépasse 31 °C en fin de journée.

**Comportement thermique habituel de la maison** : le rez-de-chaussée peut être maintenu
relativement frais pendant plusieurs jours **à condition** de pouvoir ouvrir toutes les
fenêtres la nuit (ventilation nocturne). La stratégie actuelle ne tient plus quand les
nuits sont trop chaudes et sans vent.

---

## 2. Présentation de la maison

- **Localisation** : Nanterre (92), France.
- **Année de construction** : ~1997.
- **Type** : maison compacte, **R+1 + combles aménagés** (2 étages + combles).
- **Isolation** : moyenne (« moyennement bien isolée »).
- **Inertie** : bonne capacité à garder le frais au RDC si ventilation nocturne possible.

### Niveaux et pièces

| Niveau | Pièce | Surface approx. | Côté | À climatiser ? |
|---|---|---|---|---|
| RDC | Espace de vie ouvert (séjour/cuisine) | ~35 m² | Jardin | **Oui** |
| R+1 | Petite chambre 1 | ~10 m² | Jardin | **Oui** |
| R+1 | Petite chambre 2 | ~12 m² | Jardin | **Oui** |
| R+1 | Chambre parentale + bureau télétravail (+ couloirs) | ~15 m² | [À COMPLÉTER] | Indirectement (portes ouvertes) |
| Combles | Espace aménagé | >30 m² au sol, mais <8 m² à h ≥ 1,80 m (pentes de toit) | [À COMPLÉTER] | **Non** (probablement pas pertinent) |

**Combles** : très chaud en plein été, très froid en plein hiver. Vu la faible surface
réellement habitable sous plafond (pentes), il n'est *a priori* pas pertinent d'y installer
de la climatisation. À reconsidérer seulement si c'est un espace de couchage/travail régulier.

---

## 3. Périmètre de rafraîchissement souhaité

Pièces à climatiser **directement** (un split par pièce) :

1. **RDC** — espace de vie ouvert (séjour / cuisine / salle à manger) ~35 m².
2. **R+1** — chambre nord-ouest (au-dessus du séjour) ~10–12 m².
3. **R+1** — chambre sud-ouest (au-dessus de la salle à manger) ~10–12 m².
4. **R+1** — **chambre parentale / bureau de télétravail** ~15 m², côté **est** (vers la rue).

> ⚠️ **Décision clé (issue de l'étude) : le bureau parental doit avoir son PROPRE split.**
> Le rafraîchir **passivement** (portes ouvertes depuis les chambres) est le point faible :
> l'air froid circule mal via un couloir et **la déshumidification n'y arrive quasiment
> pas** → le bureau resterait 2–4 °C plus chaud/moite. Comme c'est le **poste de
> télétravail occupé toute la journée**, il faut une unité dédiée.
> (cf. [`climatisation-nanterre.md`](climatisation-nanterre.md) §3)

### Décision d'architecture ✔ (pré-étude théorique)

**Configuration retenue : quadri-split (4 unités intérieures) sur 1 seul groupe extérieur**
unique, au sol côté jardin (§4). Un split dans **chacune des 3 chambres de l'étage** + un
au **RDC**.

- S1 (séjour RDC) + S2 (chambre SO) + S3 (chambre NO) + S4 (chambre parentale / bureau).
- Choix orienté **confort** : chaque chambre pilotée indépendamment, et le bureau de
  télétravail rafraîchi/déshumidifié **directement** (pas de passif).
- *(Variante tri-split — 3 unités, une chambre en passif — écartée : on préfère un split
  par chambre. L'option « 2 groupes extérieurs » a aussi été écartée pour rester sur un
  seul boîtier à dissimuler.)*

> **Insight important** : l'unité intérieure et le groupe extérieur **ne sont pas obligés
> d'être du même côté** de la maison ; seul le **groupe** est contraint (côté jardin). Le
> bureau côté rue peut donc être relié au groupe côté jardin **via les combles** (§6bis).

### Unités intérieures retenues (quadri-split)

| Split | Pièce | Niveau | Puissance indicative | Position |
|---|---|---|---|---|
| **S1** | Séjour / cuisine / SàM ouverts (~35 m²) | RDC | 3,5 kW (4,2–5 kW si baies très ensoleillées) | mur **sud** |
| **S2** | Chambre sud-ouest (au-dessus SàM) | R+1 | ~2,0 kW | mur à préciser |
| **S3** | Chambre nord-ouest (au-dessus séjour) | R+1 | ~2,0–2,5 kW | mur à préciser |
| **S4** | **Chambre parentale / bureau** (~15 m², côté est/rue) | R+1 | 2,0–2,5 kW | liaison **via combles** |

- **Règle de dimensionnement (France)** : ~2,5 kW pour 10–20 m² ; ~3,5 kW pour 20–35 m² ;
  ~5–7 kW pour un grand séjour 50–70 m². **Ne pas surdimensionner** (cycles courts = plus
  de bruit + mauvaise déshumidification).
- **Total intérieur nominal ≈ 9,5–10,5 kW (4 unités) → groupe extérieur ~7,5–8 kW**
  (diversité : tout ne tourne pas à fond en même temps). À confirmer par bilan thermique.
- **Unité extérieure** : au sol, **au pied du mur ouest de la salle à manger** (Option A,
  §4/§5), soufflant vers le fond du jardin. Voir le plan : [`plan.md`](plan.md).

---

## 4. Contraintes d'implantation (IMPORTANTES)

L'unité (ou les unités) **extérieure(s)** :
- **Uniquement côté jardin** (jamais côté rue, ni visible des parties communes / voisins).
- **Au sol** (pose proche du sol, pas en hauteur, pas sur façade visible).
- **Cachée(s)** visuellement.
- **Niveau sonore le plus faible possible** (priorité forte — voisinage proche).

### Contrainte copropriété
- Bien situé dans une **copropriété horizontale de 13 lots** : 4 maisons mitoyennes
  + 5 maisons individuelles. *(Note : 4 + 5 = 9 → vérifier la composition des 13 lots.)* **[À COMPLÉTER]**
- **Tout doit être rédigé en français** pour pouvoir être partagé avec les voisins.
- **À retrouver** : le **libellé exact voté en AG** (assemblée générale) concernant
  l'installation de climatisations / modifications d'aspect extérieur. **[À COMPLÉTER]**
  - Existe-t-il une autorisation préalable nécessaire ? Une charte esthétique ?
    Des règles sur le bruit, l'emplacement, la couleur, le cache ?

---

## 5. Description du jardin (zone d'implantation)

- **Surface** : ~60 m² de jardin + ~15 m² de terrasse (backyard).
- **Forme** : en **L**, emprise ~9 × 9 m.
- **Limites** :
  - **Fond** : mur en **béton blanc**.
  - **Un côté** : clôture **bois, 2 m de haut**.
  - **Autre côté (nord)** : **haie de lierre**, derrière laquelle se trouve le **jardin
    d'une autre maison de la même copropriété**. → Le bruit de l'unité extérieure
    concerne directement ce voisin de copro (argument de plus pour le silence + Option A
    plutôt que l'Option B côté haie). ✔

### Orientation ✔
- Le **pignon aveugle** de la maison est orienté **quasi plein sud (~15° vers l'ouest)**.
- En conséquence, le **jardin des 5 maisons individuelles est orienté quasi plein ouest
  (~15° nord)**.
- Conséquence pratique : le jardin et les façades concernées prennent **le fort soleil
  d'après-midi/soir d'été** (ouest + sud) → enjeu pour le choix d'emplacement de l'unité
  extérieure (chaleur, rendement, bruit).

### Emplacements candidats pour l'unité extérieure (au sol)

**Option A — Angle du L, sous la fenêtre de la salle à manger** *(préféré visuellement)*
- Avantage : **ne donne pas directement sur la terrasse**, bien caché, et souffle à
  l'opposé de la haie nord (voisin de copro).
- Inconvénient majeur : **endroit le plus chaud du jardin**, coincé entre un **mur orienté
  ouest** et un **mur sud** → forte chaleur rayonnée, risque de baisse de rendement et
  d'inconfort sonore/thermique. À étudier (ombrage, dégagement, ventilation).
- **Cotes de la zone** : recoin en L de **130 × 220 cm**, à l'angle salle à manger /
  salon / terrasse.
  - **Fenêtre de 130 cm** dans l'angle, le long du **grand côté (220 cm)**.
  - Reste **~90 cm** de mur plein avant l'angle de la maison **côté pignon sud**.
  - **Hauteur de mur plein sous la fenêtre : ~1 m** (allège) → permet de poser l'unité
    au sol **sous l'appui de fenêtre** sans la masquer. ✔
  - ⚠️ **Trappe d'accès de maintenance à l'évacuation des eaux** : il en existe une **dans
    ce coin de la maison**, **emplacement exact à retrouver** (à creuser / à demander aux
    voisins qui l'auraient localisée). **NE PAS couler de dalle ni poser l'unité dessus** —
    il faut préserver l'accès. **[À LOCALISER]**
  - → Une unité extérieure de multi-split fait typiquement ~80–95 cm de large × ~30–35 cm
    de profondeur ; ça **peut rentrer** le long du grand côté, mais il faut **respecter
    les dégagements** (entrée d'air arrière, soufflage avant, accès maintenance) et
    veiller à **ne pas souffler vers/sous la fenêtre**. À valider avec le modèle exact.

**Option B — Coin de la terrasse, le long de la haie nord — ❌ ÉLIMINÉE**
- ~1,10 m seulement entre volets ouverts et grillage : **pas de dégagement latéral**, et
  le **soufflage irait vers la terrasse ou vers la haie** (= **vers la limite de propriété
  et la voisine de copro**) → bruit/gêne inacceptables.
- Implantation **non discrète** (au milieu de la terrasse).
- **Décision : abandonnée.** Seule l'**Option A** est retenue.

**Autres points à préciser** :
- Distance entre l'Option A et chaque pièce à climatiser (longueur de liaisons frigorifiques). **[À COMPLÉTER]**
- Présence d'une évacuation pour les condensats. **[À COMPLÉTER]**
- Accès pour la maintenance. **[À COMPLÉTER]**
- **Sens de soufflage** de l'unité en Option A : ✔ **vers l'ouest-nord-ouest, vers le
  fond du jardin (zone de pelouse)**, **parallèlement à la terrasse** (et **non vers la
  terrasse**). L'unité est posée au sol **sous la fenêtre / sous le volet ouvert**, le
  long de la **section de mur de 2,20 m orientée ouest-nord-ouest (≈ 15° nord)**.
  → Côtés disponibles pour les treillis : voir §plan. Voir le plan : [`plan.md`](plan.md).

### Intégration paysagère : cache visuel + ombrage (treillis)
Objectif : **cacher** l'unité (depuis le jardin/terrasse) et l'**ombrer** (soleil ouest/sud),
sans bloquer la circulation d'air.
- **Treillis verticaux** avec plante grimpante persistante, posés **côté ouest et/ou sud**
  (et jamais **devant la face de soufflage**), à **30–50 cm minimum** de l'unité.
- **Plante** : éviter le **lierre** directement sur l'appareil (crampons envahissants +
  débris dans les ailettes). Préférer une grimpante persistante palissée sur treillis
  indépendant : **jasmin étoilé (Trachelospermum jasminoides)** ou **Clematis armandii**.
  Prévoir un **nettoyage périodique** (feuilles).
- **Treillis ajouré = cache seulement** (n'atténue pas le bruit). Un **panneau plein**
  atténuerait un peu, mais **uniquement de côté** et à distance — jamais devant le soufflage.
- ❌ **Casquette horizontale à ~90 cm déconseillée** : trop près du sommet de l'unité
  (~80–90 cm), piège l'air chaud (recyclage) et peu efficace contre le soleil rasant
  d'ouest. Préférer l'**ombrage vertical** ci-dessus.

---

## 6. Aspects techniques à instruire

- **Tableau électrique** : situé sur le **mur du fond / coin du garage**. ✔
  - **Gaine technique** passant **quasiment au centre de la maison** → atout pour le
    cheminement vertical des câbles/liaisons entre niveaux. ✔
  - **Alimentation : monophasé, 12 kVA.** ✔
  - **Tableau à 4 rangées** : les **2 rangées du bas sont pleines** ; les **2 rangées du
    haut** ne contiennent qu'**un disjoncteur** et **une redirection vers le tableau des
    combles** (respectivement) → il reste *a priori* **de la place pour ajouter des
    disjoncteurs** (lignes dédiées clim). À confirmer par un électricien. ✔
  - **Gaine technique** : monte bien vers le plafond mais **non moderne**, **aboutissement
    inconnu à l'étage** → l'ajout de lignes vers l'étage **n'est pas garanti**. À
    inspecter (où débouche-t-elle, sections disponibles). **[À VÉRIFIER]**
- **Type de système** : mono-split / multi-split / gainable ? (préférence : discret + silencieux)
- **Apports solaires (ouest)** : le séjour (porte-fenêtre 3 vantaux) et la salle à manger
  (fenêtre 2 battants) sont **vitrés plein ouest** → fort soleil d'après-midi/soir en été.
  À **prendre en compte pour le dimensionnement de S1** et à coupler avec des **protections
  solaires** (volets/stores) pour ne pas surdimensionner la clim. Voir [`plan.md`](plan.md).
- **Réversibilité** : **système réversible souhaité (PAC air-air, chaud en hiver)**. ✔
- **Passage des liaisons** frigorifiques : voir **§6bis** (notamment bureau côté rue via combles).
- **Évacuation des condensats** : voir **§6bis** (gravité / pompe / point de rejet).
- **Niveau sonore** : exiger les dB(A) de l'unité extérieure (mode nuit / silencieux).
  Repère : groupe extérieur ~**46–49 dB(A)** ; unités intérieures haut de gamme ~**19 dB(A)**
  en mode silence. **Écran à lamelles OK, coffrage fermé INTERDIT** (recirculation d'air chaud).
- **Modèles** (R32, A+++, Inverter, ~19 dB(A) silence) : Mitsubishi MSZ-LN / MSZ-AY,
  Daikin Perfera (meilleur SAV FR), Atlantic Takao M3 (meilleur rapport perf/prix),
  Toshiba Haori, Panasonic Etherea Z. Détails/prix : [`climatisation-nanterre.md`](climatisation-nanterre.md) §6.
- **Entretien** : accessibilité, contrat d'entretien (~80–150 €/an ; durée de vie 10–15 ans).

### Dimensions de référence d'une unité extérieure (ordres de grandeur)

| Type | Largeur | Hauteur | Profondeur | Poids | Puissance |
|---|---|---|---|---|---|
| Mono-split | 66–85 cm | 55–63 cm | 28–30 cm | 25–40 kg | 2,5–5 kW |
| Bi-split | 78–85 cm | 55–60 cm | 28–30 cm | 35–45 kg | ~4–5 kW |
| Tri-split | 80–95 cm | 67–80 cm | 30–37 cm | 45–60 kg | ~5,5–7,5 kW |
| Quadri/penta | 90–95 cm | 70–90 cm | 33–37 cm | 55–75 kg | 8–10 kW |

- Air aspiré **à l'arrière/côtés**, rejeté **à l'avant** (ventilateur).
- Dégagements typiques : côtés ~5–10 cm, arrière ~10–30 cm, **avant 50 cm à ~2 m**.
- Pose au sol sur **plots antivibratiles** ou **équerres** ; léger dévers pour les condensats.

### Préparation du support (auto-réalisation retenue) ✔
- **Solution retenue : support démontable** — **lit de gravier compacté et nivelé** +
  **dalles béton préfabriquées** (type 40×40 ou 50×50 cm) + **plots antivibratiles** sous
  l'unité. **Plutôt qu'une dalle béton coulée.**
- Avantages : **démontable** (préserve l'accès à la trappe d'évacuation, §5), **surélève**
  l'unité (eau/feuilles/ruissellement), **amortit les vibrations** (priorité bruit), pose
  réalisable **soi-même** pour réduire le coût.
- ⚠️ Coordination impérative avec la **trappe d'évacuation des eaux** non localisée (§5) :
  **ne rien couler dessus**, garder l'accès.
- **Ordre des opérations** : (1) connaître le modèle/l'emprise exacte via l'installateur,
  (2) localiser la trappe, (3) **seulement ensuite** préparer le support.

### 6bis. Cheminement des liaisons & évacuation des condensats

**Liaisons frigorifiques (bureau côté rue → groupe côté jardin)** :
- Un seul goulot fin (~6–8 cm) par unité : 2 tuyaux cuivre (liquide + gaz), câble de
  commande, et l'évacuation des condensats.
- Trajet naturel pour le **bureau (étage, côté rue)** : montée dans les **combles →
  traversée vers le côté jardin → descente en goulotte le long de la façade jardin**
  jusqu'au groupe au sol. **Aucune tuyauterie côté rue.**
- Limites multi-split à respecter : ~25 m par branche, ~60–70 m total, ~15 m de dénivelé.

**Condensats (peuvent être routés séparément des liaisons)** :
- **Règle dure : la gravité** — pente continue ~1–2 % (≈ 1–2 cm/m) de l'unité au point de
  rejet. Sinon → **pompe de relevage** (à choisir silencieuse, loin du bureau).
- L'eau peut sortir **au point le plus proche en contrebas** : pas besoin de revenir au
  groupe côté jardin. Débit non négligeable en canicule : **1–3+ L/jour**.
- Rejet, par ordre de préférence : (1) **raccordement aux eaux usées** (siphon obligatoire,
  anti-odeurs) ; (2) sortie mur latéral discret (gravier / puisard / descente EP) ;
  (3) sortie façade rue **à éviter** (tuyau visible, coulures sur l'enduit, nuisance).
- Détails : [`climatisation-nanterre.md`](climatisation-nanterre.md) §4–§5.

---

## 7. Contraintes administratives / réglementaires

- **AG de copropriété** : autorisation + libellé exact voté. **[À COMPLÉTER]**
- **Aspect extérieur** : la maison est-elle en zone soumise à des règles d'urbanisme
  particulières (ex. proximité d'un monument, PLU de Nanterre) ? **[À COMPLÉTER]**
- **Déclaration préalable de travaux** en mairie si modification de l'aspect extérieur ?
  Un groupe **visible depuis l'espace public** peut l'exiger ; ici il est **caché côté
  jardin**, donc *a priori* moins exposé — **à vérifier** auprès de la mairie de Nanterre,
  en plus de l'autorisation de copropriété. **[À VÉRIFIER]**

---

## 8. Budget et calendrier

- **Budget cible** : **5 000 – 8 000 €** (matériel + pose). ✔
- **Échéance souhaitée** : **pas pressé** — projet à instruire posément (AG, devis,
  concertation voisins, comparaisons). Installation possible hors saison. ✔
- **Cadre financier / aides** :
  - Pose par **installateur RGE QualiPAC obligatoire** (manipulation des fluides) — seul à
    débloquer la **TVA 5,5 %** et le **bonus CEE (fiche BAR-TH-129)**.
  - ⚠️ **Pas de MaPrimeRénov'** pour les PAC air-air (clim réversible).
  - **Demander au moins 3 devis** (main-d'œuvre IDF +15–25 % vs province).
  - Entretien annuel ~**80–150 €** ; durée de vie **10–15 ans**.
- **Repère budget posé (IDF)** : **tri-split ~5–8 k€** ; solution à 2 groupes ~5,5–9 k€ ;
  liaison longue vers le bureau **+ quelques centaines €** (+ pompe condensats éventuelle).
- Détails et modèles : [`climatisation-nanterre.md`](climatisation-nanterre.md).

---

## 9. Documents et plans

- **Plan ASCII éditable** : [`plan.md`](plan.md) (jardin + implantation de l'unité + R+1). ✔
- **Étude / aide à la décision** : [`climatisation-nanterre.md`](climatisation-nanterre.md)
  (architecture multi-split, dimensionnement, liaisons, condensats, modèles, budget, aides). ✔
- **Plans officiels de la maison** : à fournir (image). Les plans sont quasiment
  identiques pour toutes les maisons de la copropriété, **avec des symétries miroir**
  d'une maison à l'autre. **[À AJOUTER]**
- **PV / règlement de copropriété** (extrait sur la clim). **[À AJOUTER]**

---

## 10. Questions ouvertes (à compléter ensemble)

Voir la liste de questions ci-dessous, discutée avec l'occupant.

---

## 11. Workflow (méthode de travail)

- Le projet avance par **étapes / itérations** (recueil d'infos, plan, choix techniques,
  démarches copro, devis, etc.).
- **À la fin de chaque étape/itération, les modifications peuvent être committées**
  (git), avec un message clair décrivant ce qui a été fait. Inutile de demander à chaque
  petite modification : on commite une fois l'étape cohérente et terminée.
- Documents versionnés : `AGENTS.md` (dossier de projet) et `plan.md` (plan ASCII éditable).
- Objectif de publication : voir §1 (GitHub Pages / Jekyll).
