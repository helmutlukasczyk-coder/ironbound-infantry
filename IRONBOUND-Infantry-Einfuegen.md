# IRONBOUND — Infantry: Einfügeblöcke

Diese sechs Profile sind ausdrücklich eigene IRONBOUND-Hausprofile, keine aus dem DFA Card Builder übernommenen Profile. Die Regeln für Verlustzeilen und Angriffe folgen IRONBOUND und Override v5.3r1, Seite 15–16. Bewegung, Schaden, Transportmassen und EV sind die hier festgelegten Hauswerte. EV ist ein Startwert für Spieltests und kein berechneter offizieller BV2.

## 1. Hauptregelwerk: Versorgung und Ersatz

In **Company Infantry** unmittelbar nach diesem bestehenden Absatz einfügen:

> Its operating rate includes the platoon's ordinary personnel costs. Do not add another vehicle-crew or MechWarrior wage.

Der neue Block steht vor `### Transport to the Planet`:

```md
### Standard Infantry Packages

The six standard conventional infantry profiles in **IRONBOUND — Unit Records** are IRONBOUND house profiles. They use four squad rows of seven troopers, standard equipment, and Gunnery 4. Only the SRM Jump Platoon has Anti-Mech capability, with Anti-Mech 5.

Recruitment costs **25,000 C-bills** for one fully equipped, fully supplied platoon of 28 troopers. Daily operating costs are **1,000 C-bills**, including ordinary personnel costs. Transport remains a separate requirement.

### Infantry Supply

Do not count individual rifle rounds, machine-gun ammunition, or SRM shots during a standard mission. Laser infantry does not track operating heat or power charges.

A newly recruited platoon starts supplied. After each mission in which it deployed, mark its supply as expended, even if it did not attack. Before its next deployment, resupply the platoon for **1,000 C-bills** and **one campaign day** at a settlement or company base providing ordinary military supplies. This represents ammunition, power packs, and expendable equipment.

The same fixed resupply package applies to all six profiles and to reduced-strength platoons. Daily operating costs continue during that day. A platoon may retain unused supplies if it did not deploy. An unsupplied company platoon cannot deploy again until resupplied.

A mission may expressly impose a different supply restriction. Enemy platoons normally begin supplied. No ammunition-bin explosions or individual weapon-loss checks apply to these abstract infantry packages.

### Replacement Troopers

After resolving support casualties under Chapter 10, retain every lost troop pip. At an eligible market offering the same infantry package, replacement personnel and their standard equipment cost **1,000 C-bills per lost trooper**.

One replacement batch takes **one campaign day**, regardless of its size, and cannot raise the platoon above 28 troopers. Restore the ordered troop track to its new surviving total; retain the same four rows of seven. Replacements use the platoon's standard skills and equipment and grant no new ability.

For example, replacing eight troopers costs **8,000 C-bills** and one day. Resupply and replacement may occur during the same day if both services are available; pay both charges and the normal daily operating cost.

A neutralized platoon cannot be rebuilt through this replacement procedure. Recruit a new complete package for **25,000 C-bills**. Casualties never reset automatically.

### Infantry Encounter Value

Use each profile's printed baseline EV at Gunnery 4. These six values are provisional IRONBOUND balancing values, not official BV2 conversions. Use the full printed value when budgeting a deployed platoon; do not reduce EV for casualties.

| Experience | Gunnery | EV factor |
|:--|--:|--:|
| Green | 5 | ×0.80 |
| Regular | 4 | ×1.00 |
| Veteran | 3 | ×1.30 |
| Elite | 2 | ×1.60 |

Round adjusted EV up to a whole point. Infantry has no Piloting skill. For the Anti-Mech-capable SRM Jump Platoon only, use Anti-Mech 6 / 5 / 4 / 3 respectively. Other profiles remain incapable of Anti-Mech attacks at every experience level.

Transport mass remains the printed **2 tons for foot infantry** or **3 tons for jump infantry**, including equipment, even after casualties. Declare the actual base footprint before play; the standard infantry silhouette remains 0.5″ high.
```

## 2. Hauptregelwerk: kompakter Katalog

In **Appendix A → Additional Unit Catalogues** als eigene Seite einfügen, nach den Ground-Vehicle-Seiten und vor dem Aerospace-Katalog. Falls bereits ein Platzhalter `## Conventional Infantry Catalogue` vorhanden ist, dessen gesamte Seite durch diesen Block ersetzen. Den führenden Seitenwechsel nur verwenden, wenn dort noch keiner steht.

```md
\page

{{pageNumber,auto}}
{{footnote APPENDIX A | CONVENTIONAL INFANTRY}}

## Conventional Infantry Catalogue
<span id="conventional-infantry-catalogue"></span>

These six standard Inner Sphere configurations are IRONBOUND house profiles for conventional foot and jump infantry. Battle Armor is not included.

They use standard pre-Clan equipment and have no separate historical model introduction date. Apply campaign-year, market, faction, and mission restrictions normally.

{{wide
| Profile | Configuration | Troopers | Transport | Role | EV | Recruitment |
|:--|:--|--:|--:|:--|--:|--:|
| Laser Foot Platoon | Standard laser | 28 | 2 t | Fire Support | 400 | 25,000 |
| Machine Gun Foot Platoon | Standard MG; AI | 28 | 2 t | Defense | 350 | 25,000 |
| Rifle Foot Platoon | Standard ballistic rifle | 28 | 2 t | Security | 300 | 25,000 |
| Rifle Jump Platoon | Standard ballistic rifle; jump | 28 | 3 t | Scout | 400 | 25,000 |
| SRM Foot Platoon | Standard SRM | 28 | 2 t | Fire Support | 450 | 25,000 |
| SRM Jump Platoon | Standard SRM; jump; Anti-Mech | 28 | 3 t | Assault | 600 | 25,000 |
}}

Recruitment prices are in C-bills and include the complete standard personnel and equipment package. They are not equipment-only resale or salvage values.

**Operating cost:** 1,000 C-bills per campaign day, including personnel.

**Resupply:** 1,000 C-bills and one day after each deployment.

**Replacement:** 1,000 C-bills per trooper and one day per batch; a neutralized platoon requires a new package.

**EV:** Gunnery 4 baseline; provisional house balance values. Apply the Infantry experience factors once.

Complete combat profiles appear in **IRONBOUND — Unit Records, Conventional Infantry**. Company and enemy deployment require the Infantry module and the mission's explicit permissions. Vehicles and infantry share the applicable ground-support allowance.
```

## 3. Unit Records: Einleitung und sechs Kartenseiten

Im inzwischen erweiterten Unit-Records-Buch **nach der letzten Aerospace-Card (Thunderbird TRB-D36), vor der nächsten vorhandenen Kapiteleinleitung** einfügen. Auf Grundlage der bisherigen Reihenfolge (Vehicles Kapitel 5, Aerospace Kapitel 6) wird Infanterie Kapitel 7. Die angehängte ältere Unit-Records-Version (3) enthält die später eingefügten Vehicles/Aerospace-Seiten noch nicht; deshalb hier nach dem Kartennamen suchen.

Den vorhandenen Seitenwechsel nach Thunderbird verwenden; keinen zweiten davor ergänzen. Der folgende Block beginnt direkt auf der neuen Seite. Nach der letzten Karte genau einen Seitenwechsel zum folgenden Kapitel verwenden.

```md
<span id="conventional-infantry"></span>

# Chapter 7: Conventional Infantry

## Foot and Jump Platoons
### Hold Ground, Secure Objectives, Support the Lance

Conventional infantry brings capabilities that a BattleMech lance cannot provide alone. Platoons secure positions, contest permitted objectives, and support the company through close-range fire and coordinated movement.

Foot platoons favour deliberate positioning. Rifle units provide simple security, machine guns counter enemy infantry, lasers extend useful reach, and SRMs threaten exposed armored targets. Jump platoons exchange greater transport requirements for mobility across difficult ground.

Each record represents one platoon of 28 troopers in four squad rows. Mark casualties across each row, then down. Only the first active row supplies the entire platoon's damage; never add the damage values of different rows. Semicolons separate damage groups within one attack.

These six records are IRONBOUND house profiles using the main rulebook's Infantry procedures. Their printed EV values are starting points for balance testing. Battle Armor, motorized infantry, and mechanized infantry are outside this collection.

{{pageNumber,auto}}
{{footnote PART VII | CONVENTIONAL INFANTRY}}

\page

{{unitRecordPage
![Rifle Foot Platoon](https://raw.githubusercontent.com/helmutlukasczyk-coder/ironbound-infantry/main/IRONBOUND-Rifle-Foot-Platoon.svg)
}}

\page

{{unitRecordPage
![Machine Gun Foot Platoon](https://raw.githubusercontent.com/helmutlukasczyk-coder/ironbound-infantry/main/IRONBOUND-Machine-Gun-Foot-Platoon.svg)
}}

\page

{{unitRecordPage
![Laser Foot Platoon](https://raw.githubusercontent.com/helmutlukasczyk-coder/ironbound-infantry/main/IRONBOUND-Laser-Foot-Platoon.svg)
}}

\page

{{unitRecordPage
![SRM Foot Platoon](https://raw.githubusercontent.com/helmutlukasczyk-coder/ironbound-infantry/main/IRONBOUND-SRM-Foot-Platoon.svg)
}}

\page

{{unitRecordPage
![Rifle Jump Platoon](https://raw.githubusercontent.com/helmutlukasczyk-coder/ironbound-infantry/main/IRONBOUND-Rifle-Jump-Platoon.svg)
}}

\page

{{unitRecordPage
![SRM Jump Platoon](https://raw.githubusercontent.com/helmutlukasczyk-coder/ironbound-infantry/main/IRONBOUND-SRM-Jump-Platoon.svg)
}}

```

Die vorhandene CSS-Klasse `unitRecordPage` bleibt unverändert. Die Karten haben wie die bisherigen Records ein Querformat von 277 × 183 mm.
