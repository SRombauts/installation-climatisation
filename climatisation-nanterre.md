# Projet climatisation — maison Nanterre

> Notes de discussion / aide à la décision pour l'installation d'une climatisation réversible.
> Maison compacte 2 étages (~1997), moyennement isolée. Reste fraîche plusieurs jours
> si on aère la nuit, mais inefficace en canicule sans vent (nuits > 27 °C, intérieur ~29 °C
> le matin, > 31 °C en fin de journée).

## 1. Architecture retenue : multi-split

Pour une maison compacte 2 étages, un **multi-split** (1 groupe extérieur alimentant
2–3 unités intérieures murales) est préférable à plusieurs monoblocs portables.

- Les portables monoblocs sont à éviter (bruyants 50–65 dB en intérieur, compresseur dans
  la pièce, peu efficaces, tuyau par la fenêtre qui ruine l'isolation). Dépannage seulement.
- **Ne pas surdimensionner** : un appareil trop puissant fait des cycles courts → plus
  bruyant et déshumidifie mal.

Règle de dimensionnement (France) :
- ~2,5 kW pour 10–20 m²
- ~3,5 kW pour 20–35 m²
- ~5–7 kW pour un grand séjour 50–70 m²

## 2. Contraintes du site

- **Groupe extérieur : côté jardin uniquement**, au ras du sol, caché de la rue, de la
  copropriété et des voisins. Un seul groupe à dissimuler = un seul tri-split privilégié.
- **Impossible** de mettre un groupe extérieur côté rue/copro (où se trouve le bureau /
  chambre parentale).
- L'unité extérieure a besoin d'air libre : écran à lamelles OK, **coffrage fermé interdit**
  (recirculation d'air chaud). Dégagement ~30 cm à l'arrière, > 1 m devant le ventilateur.
- Bruit extérieur ~46–49 dB(A) : éloigner des limites de propriété et fenêtres voisines.
- **Permis** : un groupe visible depuis l'espace public peut nécessiter une *déclaration
  préalable de travaux* (mairie de Nanterre) ; vérifier aussi le **règlement de copropriété**.

## 3. Pièces à climatiser (côté garden + bureau)

Point clé compris en cours de discussion : **l'unité intérieure et le groupe extérieur
ne sont pas obligés d'être du même côté de la maison.** Seul le groupe extérieur est
contraint (côté jardin). Une unité intérieure peut donc être placée dans le bureau côté rue,
reliée par des tuyaux au groupe côté jardin.

### Configuration recommandée (tri-split, 1 groupe extérieur caché)

> Note : l'étude penche pour le **tri-split** (meilleur rapport confort/prix/bruit). Le
> dossier projet retient finalement le **quadri** par choix de confort (un split par
> chambre) — voir l'**arbitrage tri/quadri** dans [`AGENTS.md`](AGENTS.md) §3 et les
> **estimations chiffrées des deux** en §7 ci-dessous.

| Unité | Pièce | Puissance | Raison |
|---|---|---|---|
| 1 | Séjour ouvert RDC (~35 m²) | 3,5 kW (4,2–5,0 kW si grandes baies ensoleillées) | Pièce de vie principale |
| 2 | **Bureau / chambre parentale (~15 m²)**, côté rue | 2,0–2,5 kW | Poste de télétravail, refroidi + déshumidifié directement |
| 3 | Une chambre (12 m²) **sous combles** | 2,5 kW | Confort nuit (apport par la toiture → 2,5 plutôt que 2,0 kW) |

- La **chambre de 10 m²** est rafraîchie passivement la nuit (porte ouverte) — acceptable
  pour une petite pièce adjacente inoccupée en journée.
- Total intérieur nominal ≈ 7,5–9 kW → groupe extérieur ~6,8 kW (diversité : tout ne tourne
  pas à fond en même temps).

### ⚠️ Mise en garde sur le refroidissement passif

Refroidir le bureau **passivement par porte ouverte** depuis les chambres est le point
faible : l'air froid circule mal entre pièces séparées via un couloir, la **déshumidification
n'y arrive quasiment pas**, et le bureau resterait 2–4 °C plus chaud/moite. Comme c'est le
lieu de télétravail toute la journée → **lui mettre une unité dédiée** (d'où la config
ci-dessus qui remplace une chambre côté jardin par le bureau côté rue).

## 4. Cheminement des liaisons (bureau côté rue → groupe côté jardin)

Depuis l'unité du bureau, un seul goulot fin (~6–8 cm) ramène vers le groupe extérieur :
- 2 tuyaux cuivre (liquide + gaz)
- câble de commande
- évacuation des condensats

Trajet naturel pour une pièce **à l'étage, côté rue** : montée dans les **combles → traversée
vers le côté jardin → descente en goulotte le long de la façade jardin** jusqu'au groupe au sol.
Aucune tuyauterie côté rue. Dans les limites multi-split (~25 m par branche / ~60–70 m total,
~15 m de dénivelé).

## 5. Évacuation des condensats (peut être routée séparément)

Les condensats sont **indépendants des liaisons frigorifiques** : seuls les tuyaux cuivre +
câble doivent rejoindre le groupe extérieur. L'eau peut sortir au point le plus proche et en
contrebas → **pas besoin de revenir au groupe côté jardin**. Pour le bureau côté rue, sortir
le drain par le mur le plus proche est plus court, moins cher, et peut éviter une pompe.

**Règle dure : la gravité.** Pente continue ~1–2 % (≈1–2 cm/m) de l'unité au point de rejet.
Si l'évacuation la plus proche est de niveau ou plus haute → **pompe de relevage** (petit
bourdonnement ~20–25 dB(A) ; en choisir une silencieuse, loin du bureau).

Options de rejet, par ordre de préférence :
1. **Raccordement aux eaux usées** (drain SdB/cuisine ou colonne), via siphon/garde d'air
   anti-odeurs. Le plus propre, rien en façade.
2. **Sortie mur latéral discret** vers lit de gravier, puisard, ou descente d'eau pluviale.
3. **Sortie façade rue** — fonctionne mais **à éviter** : tuyau visible, **traces/coulures**
   sur l'enduit (condensats légèrement acides), risque de **nuisance** vers l'espace public.
   Débit non négligeable en canicule/déshumidification : **1–3+ L/jour**.

À ne pas faire : rejeter sur un passage, côté voisin, ou sur une maçonnerie visible.
Si raccordement eaux usées → **siphon obligatoire**.

## 6. Modèles recommandés (unités murales hautes perfs, silencieuses)

> ⚠️ **Les SEER/SCOP du tableau ci-dessous sont des valeurs MONO-SPLIT** (un groupe = une
> unité), là où elles sont les plus hautes. **En multi-split, on ne les atteint pas** : le
> groupe est partagé, les pertes augmentent. Référence réelle du groupe quadri retenu
> (**Daikin 4MXM80A**) : **SEER 8,32 / SCOP 4,55** (A++/A+), pas ~10,5 / 5,2. Important
> aussi pour le **CEE BAR-TH-129**, dont le montant dépend du SCOP (et reste modeste pour
> de l'air-air).

Valeurs pour la classe ~2,5 kW (9000 BTU) où le SEER/SCOP est le plus élevé. Tous R32, A+++,
Inverter, ~19 dB(A) en mode silence.

| Modèle (unité intérieure) | Froid nom. | SEER | SCOP | Bruit int. (silence) | Bruit ext. | Prix indicatif (mono-split, matériel) | Notes |
|---|---|---|---|---|---|---|---|
| **Mitsubishi MSZ-LN Kirigamine** | 2,5 kW | ~10,5 | 5,2 | 19 dB(A) | ~46 dB(A) | ~900–1100 € | SEER le plus élevé ; filtre Plasma Quad ; chauffe −25 °C |
| **Daikin Perfera FTXM-R** (gén. 2024) | 2,5 kW | 7,85 → jusqu'à 9,47 | 5,1 → 5,2 | 19 dB(A) | ~46 dB(A) | ~850–1050 € | Réseau SAV le plus dense en France |
| **Atlantic Takao M3** (Fujitsu rebadgé) | ~2,5 kW | ~9,1 | 5,3 | 19 dB(A) | 46 dB(A) | ~700–900 € | Meilleur rapport perf/prix |
| **Mitsubishi MSZ-AY / AP** | 2,5 kW | ~8,5 | ~4,6–4,9 | 19–21 dB(A) | ~46–49 dB(A) | ~700–850 € | Robuste, très silencieux |
| **Toshiba Haori / Shorai Edge** | 2,5 kW | ~8,6 | ~5,1 | 19 dB(A) | ~47 dB(A) | ~800–1000 € | Filtres autonettoyants |
| **Panasonic Etherea Z** | 2,5 kW | ~8,5 | ~5,1 | 19 dB(A) | ~46 dB(A) | ~800–1000 € | Purification nanoe-X |

**Plafond de perfs haut de gamme** : SEER jusqu'à ~9,5 (Daikin Perfera nouvelle gén.),
voire 10,5 sur petit MSZ-LN25 ; SCOP 5,2–5,5 ; plancher de bruit ~19 dB(A) intérieur ;
plage −15→−25 °C en chauffe, jusqu'à +46→+50 °C en froid.

**Choix orienté perfs/silence/coût (sans gadgets) :**
1. Meilleur rapport qualité-prix : **Atlantic Takao M3**.
2. Silence + efficacité : **Mitsubishi MSZ-AY** (workhorse) ou **MSZ-LN** (efficacité max).
3. Meilleur SAV : **Daikin Perfera**.
Éviter les gammes « premium design/connecté » (Emura, Haori déco) : plus chères pour
de l'esthétique/Wi-Fi sans gain d'efficacité.

### Groupes extérieurs multi-split (selon l'architecture)

Prix **groupe extérieur seul** (hors unités intérieures, hors pose), relevés chez des
revendeurs FR (juin 2026).

| Groupe extérieur | Sorties | Froid / Chaud | SEER / SCOP | Prix indicatif |
|---|---|---|---|---|
| **Daikin 4MXM80A** | 4 (quadri) | 7,4–8,0 / 9,6 kW | **8,32 / 4,55** (A++/A+) | ~2 725–2 899 € |
| **Mitsubishi MXZ-4F80VF** | 4 (quadri) | 8,0 / 9,0 kW | ~8,1 / 4,4 | ~2 629 € |
| **Daikin 3MXM68A** | 3 (tri) | 6,8 / 8,2 kW | ~8,6 / 4,6 | ~2 100–2 300 € |
| **Mitsubishi MXZ-3F68VF** | 3 (tri) | 6,8 / 8,6 kW | ~8,3 / 4,5 | ~2 000–2 200 € |
| **Daikin 2MXM50A** | 2 (bi) | ~5,0 / 5,6 kW | ~8,7 / 4,6 | ~1 400–1 600 € |

→ **À retenir** : un groupe **quadri 8 kW partagé entre 4 unités** ne délivre jamais sa
pleine puissance à toutes en même temps (foisonnement). Le séjour (plus gros besoin) est
le premier bridé lors d'un pic simultané (soir de canicule). D'où l'intérêt des
**protections solaires ouest** pour baisser le besoin de S1, et du chiffrage du **tri-split
en repli** (cf. §7).

## 7. Budget indicatif (Île-de-France, posé)

> Le budget initialement noté (5–8 k€) correspondait au **tri-split** ; il **sous-estime le
> quadri**. Estimations révisées ci-dessous, posé TTC par installateur RGE en IDF.

### Estimations détaillées par option

**Option Q — QUADRI-SPLIT (4 unités, 1 groupe) — confort max, archi retenue**

| Poste | Gamme perfs (Perfera/MSZ-LN) | Gamme éco (Takao/MSZ-AY) |
|---|---|---|
| Groupe ext. (4MXM80 / MXZ-4F80) | ~2 800 € | ~2 629 € |
| S1 séjour (FTXM50R / 5,0 kW) | ~1 000 € | ~700 € |
| S2 + S3 + S4 (3 × 2,5 kW) | ~2 250 € | ~1 650 € |
| **Sous-total matériel** | **~6 050 €** | **~4 980 €** |
| Fournitures (cuivre, goulottes, dalles, plots) | ~400–700 € | ~400–700 € |
| Ligne(s) élec. dédiée(s) + disjoncteurs | ~300–600 € | ~300–600 € |
| Pompe de relevage condensats (si besoin S4) | ~150–300 € | ~150–300 € |
| Main-d'œuvre (4 unités, liaison combles ~18 m) | ~3 000–4 500 € | ~2 800–4 000 € |
| **TOTAL POSÉ TTC** | **~9 500–11 500 €** | **~8 000–9 500 €** |

**Option T — TRI-SPLIT (3 unités, 1 groupe) — repli recommandé**
*(S1 séjour + S4 bureau + 1 chambre ; 2ᵉ petite chambre rafraîchie en passif porte ouverte)*

| Poste | Gamme perfs | Gamme éco |
|---|---|---|
| Groupe ext. (3MXM68 / MXZ-3F68) | ~2 200 € | ~2 100 € |
| S1 séjour (5,0 kW) | ~1 000 € | ~700 € |
| 2 × 2,5 kW (bureau + 1 chambre) | ~1 500 € | ~1 100 € |
| **Sous-total matériel** | **~4 700 €** | **~3 900 €** |
| Fournitures + élec. + pompe éventuelle | ~850–1 600 € | ~850–1 600 € |
| Main-d'œuvre (3 unités, liaison combles ~18 m) | ~2 500–3 800 € | ~2 300–3 200 € |
| **TOTAL POSÉ TTC** | **~8 000–9 500 €** | **~6 500–8 000 €** |

**Option B — BI-SPLIT (2 unités, 1 groupe) — minimaliste**
*(S1 séjour + S4 bureau seuls ; les 3 chambres en passif — à réserver si budget serré)*

| Poste | Gamme perfs | Gamme éco |
|---|---|---|
| Groupe ext. (2MXM50) | ~1 500 € | ~1 400 € |
| S1 (5,0 kW) + bureau (2,5 kW) | ~1 700 € | ~1 250 € |
| **Sous-total matériel** | **~3 200 €** | **~2 650 €** |
| Fournitures + élec. + pompe éventuelle | ~700–1 400 € | ~700–1 400 € |
| Main-d'œuvre (2 unités, liaison combles ~18 m) | ~2 000–3 000 € | ~1 800–2 600 € |
| **TOTAL POSÉ TTC** | **~6 000–7 500 €** | **~5 200–6 600 €** |

### Synthèse

| Option | Confort | Total posé TTC | Pour qui |
|---|---|---|---|
| **Quadri (Q)** | Maximal (chaque pièce pilotée) | **~8 000–11 500 €** | Si budget OK et confort prioritaire |
| **Tri (T)** — repli | Très bon (1 chambre passive) | **~6 500–9 500 €** | Meilleur rapport confort/prix/bruit |
| **Bi (B)** | Correct (chambres passives) | **~5 200–7 500 €** | Budget serré, besoin séjour + bureau |

### Cadre financier et aides

- IDF : main-d'œuvre **+15–25 %** vs province → **demander au moins 3 devis**.
- Pose par **installateur RGE QualiPAC obligatoire** (manipulation des fluides F-Gas), seul
  à débloquer la **TVA réduite sur la main-d'œuvre** et le **bonus CEE (fiche BAR-TH-129)**.
- **TVA (PAC air-air, logement > 2 ans)** : règle solidement établie = **20 % sur le
  matériel + 10 % sur la main-d'œuvre**. Un passage à **5,5 %** a été *annoncé* (loi de
  finances 2026) mais son entrée en vigueur effective est **contestée selon les sources**
  (juin 2026) et ne porterait, au mieux, **que sur la main-d'œuvre** (matériel toujours à
  20 %). **À vérifier** sur impots.gouv.fr et auprès de l'installateur avant signature.
- ⚠️ **Pas de MaPrimeRénov'** pour les PAC air-air (clim réversible).
- **CEE BAR-TH-129** : prime air-air **modeste** (souvent quelques dizaines à ~150 €,
  variable selon l'obligé et le SCOP) — à demander mais ne pas surévaluer.
- Entretien annuel ~80–150 € ; durée de vie 10–15 ans.

## 8. À mettre dans le cahier des charges pour les devis

- Liste des pièces + puissances cibles (cf. §3).
- Groupe extérieur **côté jardin, au sol, dissimulé** (écran ventilé, pas de coffrage fermé).
- Unité du **bureau côté rue sur liaison longue** vers le groupe côté jardin (via combles).
- **Condensats vers évacuation gravitaire la plus proche / eaux usées**, **pas** de retour au
  groupe, **pas de coulure visible en façade rue** ; pompe de relevage silencieuse si besoin.
- Pose **RGE QualiPAC** + **CEE BAR-TH-129** ; **TVA** : 20 % matériel + 10 % pose (5,5 % à
  confirmer, cf. §7) — exiger le détail des taux sur le devis.
- Possibilité de **programmation horaire** des unités (pré-refroidissement, cf. §9).

## 9. Stratégie passive et de pilotage (déjà en place / envisagée)

La maison fait **déjà l'essentiel du passif**, ce qui réduit le besoin de froid et donc le
dimensionnement (cf. §1, §3) :

- **Protections solaires fermées en chaleur** : volets bois (toutes fenêtres ouest) + volets
  roulants PVC (2 fenêtres est). C'est la mesure la plus efficace, déjà acquise.
- **Voile d'ombrage** au-dessus de la terrasse / porte-fenêtre séjour (éventuelle **pergola
  végétalisée** à terme).
- **Projet** : voile d'ombrage au-dessus de la fenêtre SàM → **ombre aussi l'unité
  extérieure** aux heures de soleil haut (tendue **haute et aérée**, pas un capotage) →
  condenseur plus frais = **meilleur rendement + moins de bruit**.
- **Ventilation nocturne** quand les nuits le permettent.

**Pilotage par plages horaires (pré-refroidissement)** — pertinent vu la bonne inertie :
1. aérer à la fraîche la nuit/au matin ;
2. clim le **matin** (avant l'ensoleillement ~14–15 h), air extérieur frais + unité à
   l'ombre = rendement max ;
3. **cœur d'après-midi** : volets fermés, clim **coupée ou consigne +2–3 °C** dans les
   pièces de vie/chambres (éviter de faire tourner le groupe en plein soleil / air chaud) ;
4. **soir (après ~19 h)** : unité à l'ombre de la maison → rallumer pour préparer la nuit.

⚠️ **Exception bureau (S4)** : occupé en journée → reste climatisé l'après-midi. Avantage :
s'il est **seul à tourner**, il dispose de **toute la capacité du groupe** (le « partage de
puissance » du multi-split ne pénalise pas). Préférer une **consigne relevée** à un arrêt
total (l'inverter aime la modulation continue ; meilleure déshumidification). Détails et
nuances : [`AGENTS.md`](AGENTS.md) §6ter.

## Sources

- [Mitsubishi vs Daikin comparatif 2025 — chauffage-et-climatisation.fr](https://www.chauffage-et-climatisation.fr/conseils-astuces/climatiseur-mitsubishi-ou-daikin-informations-essentielles/)
- [Meilleure clim réversible 2026 — laprimeenergie.fr](https://www.laprimeenergie.fr/les-travaux/la-pompe-a-chaleur/clim-reversible/meilleure)
- [Top 5 multi-split 2025 — chauffage-et-climatisation.fr](https://www.chauffage-et-climatisation.fr/guide-achat/top-5-de-meilleures-climatisations-multi-split/)
- [Classement climatiseurs silencieux par dB — maclim.fr](https://www.maclim.fr/meilleurs-climatiseurs-2025/)
- [Daikin Perfera FTXM-R product profile (PDF) — daikin.eu](https://www.daikin.eu/content/dam/document-library/catalogues/ac/split/ftxm-r/Perfera%20wall%20mounted%20unit_Product%20profile_ECPEN22-008_English.pdf)
- [Next-gen Perfera 2024 (SEER 9.47 / SCOP 5.20) — daikin-ce.com](https://www.daikin-ce.com/en_us/press-releases/2024/daikin-introduces-next-generation-perfera.html)
- [Mitsubishi MSZ-LN25 specs — climamania.com](https://www.climamania.com/en/air-conditioning-mitsubishi-msz-ln25vg-blanco-kirigamine-style.html)
- [Atlantic Takao M3 fiche — atlantic.fr](https://www.atlantic.fr/Climatiser-le-logement/Climatisation-reversible-pour-une-seule-piece/Climatisation-reversible-murale/Takao-M3-Unite-interieure)
- [Coût d'installation climatisation — chauffage-et-climatisation.fr](https://www.chauffage-et-climatisation.fr/guide-achat/quel-est-le-cout-dinstallation-dune-climatisation/)
- [Groupe quadri Daikin 4MXM80A (SEER 8,32 / SCOP 4,55) — clim-planete.com](https://www.clim-planete.com/1744-unite-exterieure-4mxm80-inverter-daikin.html)
- [Groupe quadri Mitsubishi MXZ-4F80VF — clim-planete.com](https://www.clim-planete.com/2433-unite-exterieure-mxz-4f80vf-mitsubishi-electric-4-sorties-climatisation-inverter-reversible-multi-split.html)
- [Daikin 4MXM80A prix/specs — toutelaclim.com](https://toutelaclim.com/produit/unite-exterieure-4mxm80n-daikin-4-sorties-climatisation-inverter-reversible-multi-split/)
- [TVA climatisation réversible 2026 — engie-homeservices.fr](https://www.engie-homeservices.fr/dossiers/tva-climatisation-reversible)
- [TVA chauffagiste 2026 (PAC, rénovation, neuf) — kelyseo.com](https://www.kelyseo.com/blog/tva-chauffagiste-travaux-taux)
- [TVA PAC air-air — effy.fr](https://www.effy.fr/aide-energetique/pac-air-air/tva)

---
*Discussion synthétisée le 2026-06-25. Analyse critique + estimations chiffrées ajoutées le 2026-06-25.*
