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

| Unité | Pièce | Puissance | Raison |
|---|---|---|---|
| 1 | Séjour ouvert RDC (~35 m²) | 3,5 kW (4,2–5,0 kW si grandes baies ensoleillées) | Pièce de vie principale |
| 2 | **Bureau / chambre parentale (~15 m²)**, côté rue | 2,0–2,5 kW | Poste de télétravail, refroidi + déshumidifié directement |
| 3 | Une chambre (12 m²) | 2,0 kW | Confort nuit |

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

## 7. Budget indicatif (Île-de-France, posé)

| Option | Matériel seul | Posé en IDF | Notes |
|---|---|---|---|
| **Tri-split (1 groupe)** — recommandé | ~2 500–3 500 € | **~5 000–8 000 €** | Liaisons verticales vers l'étage |
| Mono (RDC) + Bi-split (étage) — 2 groupes | ~2 800–4 000 € | ~5 500–9 000 € | Plus efficace mais 2 boîtiers à cacher |

- Liaison plus longue vers le bureau côté rue : **+ quelques centaines €** (+ pompe condensats
  éventuelle).
- IDF : main-d'œuvre +15–25 % vs province → **demander au moins 3 devis**.
- Pose par **installateur RGE QualiPAC** obligatoire (manipulation des fluides), seul à
  débloquer **TVA 5,5 %** + **bonus CEE (fiche BAR-TH-129)**.
- ⚠️ **Pas de MaPrimeRénov'** pour les PAC air-air (clim réversible).
- Entretien annuel ~80–150 € ; durée de vie 10–15 ans.

## 8. À mettre dans le cahier des charges pour les devis

- Liste des pièces + puissances cibles (cf. §3).
- Groupe extérieur **côté jardin, au sol, dissimulé** (écran ventilé, pas de coffrage fermé).
- Unité du **bureau côté rue sur liaison longue** vers le groupe côté jardin (via combles).
- **Condensats vers évacuation gravitaire la plus proche / eaux usées**, **pas** de retour au
  groupe, **pas de coulure visible en façade rue** ; pompe de relevage silencieuse si besoin.
- Tout en **RGE / TVA 5,5 % / CEE**.

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

---
*Discussion synthétisée le 2026-06-25.*
