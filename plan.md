---
title: Plan du jardin et implantation de la climatisation
---

# Plan simplifié — jardin et implantation de l'unité extérieure

> Schéma **non à l'échelle**, destiné à être **édité à la main** pour préciser la
> géométrie. Voir le contexte complet dans [`AGENTS.md`](AGENTS.md).
>
> **Comment éditer** : modifiez directement les caractères dans le bloc `texte` ci-dessous
> (police à chasse fixe). Conservez le bloc entre les balises ``` pour qu'il s'affiche
> correctement (terminal + GitHub Pages/Jekyll).

## Orientation (confirmée)

- **Nord réel** ≈ vers le haut, mais l'ensemble est **pivoté d'environ 15°**.
- **Pignon aveugle** de la maison = **plein SUD** (≈ 15° vers l'ouest).
- **Terrasse au NORD** (en haut), le long de la haie. ✔
- **Fond du jardin (mur béton blanc) à l'OUEST** (= à gauche). ✔
- **Haie de lierre au NORD** (voisin copro). ✔  **Clôture bois (2 m) au SUD** (voisin copro). ✔
- L'**unité extérieure** est au sol **au pied du mur ouest de la salle à manger** et
  souffle **vers l'ouest / le fond du jardin** (flèches `<<<`), **parallèlement à la
  terrasse**, **pas** vers la terrasse.

## Plan — rez-de-chaussée

```text
                              N (Nord réel ≈ pivoté +15°)
                              ^
                  O <---------+---------> E
                              v
                              S

  +-- haie (limite NORD - voisin copro) --+---------------------------------+
  |                     .                 |                                 |
  |                     .                 |                                 |
  M                     .                 H                                 |
  U                     .                 H                       CUISINE   |
  R                     .    TERRASSE     H  SEJOUR                         |
  |                     .     ~16 m2      H                                 |
  F                     .                 |                               |
  O                     .                 |                                 |
  N                     .                 |                 +---------------+
  D                     ..................+-----+           |               |
  |                                             F  SALLE A  |               |
  O                                             F  MANGER   |    GARAGE     |
  U                                             F  [S1]     |               |
  E                <<<<< soufflage clim [UNITE] |           |               |
  S                                             +--mur sud--+---------------+
  T        JARDIN                                           |
  |     pelouse (~60 m2)                                    |
  |                                                         |
  |                                                         |
  +-- cloture bois (2 m, limite SUD - voisin copro)---------+

  LEGENDE
  [UNITE] .... unite exterieure de climatisation (au sol, pied du mur ouest de la SaM)
  [S1] ....... split interieur n.1 : SALLE A MANGER, le long du mur SUD (RDC)
  <<<<<      sens de soufflage du ventilateur (ouest = vers le fond du jardin)
  MUR gauche  mur beton blanc = limite OUEST (fond du jardin, limite de copro / autre lotissement)
  haie       limite NORD (jardin d'un voisin de la meme copropriete)
  cloture    cloture bois 2 m = limite SUD (jardin d'un voisin de la meme copropriete)
  .......    délimitation terrasse

  FENETRES (ouvertures vitrees, toutes orientees OUEST -> fort soleil d'apres-midi/soir)
  H .......... porte-fenetre 3 vantaux du SEJOUR (mur ouest, donne sur la terrasse)
  F .......... fenetre 2 battants de la SALLE A MANGER (mur ouest, ~130 cm,
               juste au-dessus de l'unite exterieure)
  -> Apports solaires importants cote ouest : prevoir protections (volets/stores)
     et en tenir compte pour le dimensionnement de S1.
  -> L'unite ext. souffle vers l'OUEST (a l'oppose), elle ne renvoie pas d'air
     chaud vers la fenetre F : OK, a confirmer avec les degagements.

  ETAGE (R+1) - unites interieures (au-dessus du RDC, non representees ci-dessus)
  [S2] ....... split interieur n.2 : CHAMBRE au-dessus de la SALLE A MANGER
  [S3] ....... split interieur n.3 : CHAMBRE au-dessus du SEJOUR
  -> Les 3 splits sont regroupes du cote ouest/sud, proches de l'unite exterieure
     (liaisons frigorifiques courtes).

  COTES DU RECOIN EN L (Option A retenue)
  - Recoin : 130 x 220 cm (au pied du mur ouest de la salle a manger)
  - Fenetre : 130 cm (2 battants) le long du grand cote (220 cm)
  - ~90 cm de mur plein avant l'angle cote pignon SUD
  - ~1 m de mur plein (allege) sous la fenetre -> pose au sol possible
  - ATTENTION : trappe d'acces a l'evacuation des eaux quelque part dans ce coin
    (emplacement a localiser ; ne rien couler dessus)

  TREILLIS (cache + ombrage) : cotes OUEST et/ou SUD, JAMAIS devant le soufflage,
  a 30-50 cm mini de l'unite.
```

## Plan — premier étage (R+1)

> **Mêmes dimensions extérieures que le RDC** (murs extérieurs uniquement, sans jardin
> ni terrasse). Agencement intérieur **dessiné par l'occupant** — proportions
> **approximatives, non à l'échelle**. Orientation identique au RDC.

```text
                              N (orientation identique au RDC ; +15°)
                              ^
                  O <---------+---------> E
                              v
                              S

  +--------------+---------+------+----------+
  |              |         |      |          |
  | CHAMBRE Nord |   ESC.  |      |  S.D.B   |       
  | (au-dessus   |         |      |          |
  |    sejour)   +--+      +------+----+     |
  |    [S3]                |      | Dressing |
  |                        |      |          |
  +-----------------+      +------+----+    -+
  |                                          |
  |  CHAMBRE Sud                             |
  | (au-dessus de   +---   +    CHAMBRE      |    
  | salle a manger) |      |   PARENTALE     |
  |    [S2]         |Douche|                 |
  |                 |      |                 |
  +-----------------+------+-----------------+

  LEGENDE (R+1) - proportions approximatives, non a l'echelle
  OUEST (gauche) = 2 chambres climatisees :
    [S3] ... CHAMBRE Nord (au-dessus du sejour)             ~10-12 m2
    [S2] ... CHAMBRE Sud  (au-dessus de la salle a manger)  ~10-12 m2
  ESC. ... escalier (acces a l'etage)
  EST (droite) = SUITE PARENTALE :
    - CHAMBRE PARENTALE (sert aussi de bureau de teletravail, ~15 m2)
    - S.D.B (salle de bain) + Douche
    - Dressing
  -> SUITE PARENTALE : pas de split dedie ; rafraichie INDIRECTEMENT
     (portes ouvertes + circulation depuis les chambres climatisees).
  -> Les liaisons de S2/S3 rejoignent l'unite exterieure cote ouest/sud (courtes).
```

## Récapitulatif des unités intérieures

| Split | Pièce | Niveau | Position |
|---|---|---|---|
| S1 | Salle à manger (espace ouvert RDC ~35 m²) | RDC | mur **sud** |
| S2 | Chambre **sud-ouest** (au-dessus de la salle à manger) | R+1 | mur à préciser |
| S3 | Chambre **nord-ouest** (au-dessus du séjour) | R+1 | mur à préciser |

## Ouvertures (fenêtres / portes-fenêtres)

| Repère | Pièce | Type | Mur / orientation |
|---|---|---|---|
| H | Séjour | Porte-fenêtre **3 vantaux** | mur **ouest**, donne sur la terrasse |
| F | Salle à manger | Fenêtre **2 battants** (~130 cm) | mur **ouest**, au-dessus de l'unité ext. |

## Notes / à corriger par l'occupant

- [x] Orientation confirmée : terrasse au **nord**, fond du jardin à l'**ouest**,
      haie au **nord**, clôture bois au **sud**.
- [x] Fenêtres ajoutées : porte-fenêtre 3 vantaux (séjour) + fenêtre 2 battants (SàM),
      les deux côté **ouest**.
- [ ] Préciser la forme exacte du **L** (où s'arrêtent terrasse et pelouse).
- [ ] Emplacement (une fois connu) de la **trappe d'évacuation des eaux**.
- [ ] Mur exact pour **S2** et **S3** à l'étage, et leurs fenêtres.
- [ ] Autres ouvertures (cuisine, garage) si pertinent.
- [ ] Distances entre l'unité extérieure et les **3 splits** (longueur des liaisons).
