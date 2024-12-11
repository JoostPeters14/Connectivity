# Overzicht van Inputs en Outputs

## Digitale Inputs (Ingangen)
| *Naam*                             | *Kleur*        | *Beschrijving*                              |
|--------------------------------------|------------------|----------------------------------------------|
| Werkstuk aan begin van de transportband | Grijs-roze (I0)  | Detecteert een werkstuk aan het begin van de transportband. |
| Werkstuk in het midden van de transportband | Rood-blauw (I1)  | Detecteert een werkstuk in het midden van de transportband. |
| Werkstuk aan het einde van de transportband | Wit-groen (I2)   | Detecteert een werkstuk aan het einde van de transportband. |
| Voedingscilinder in uitgangspositie  | Wit-geel (I4)    | Controleert of de voedingscilinder in de uitgangspositie staat. |
| Oprichtcilinder in uitgangspositie   | Bruin-geel (I5)  | Controleert of de oprichtcilinder in de uitgangspositie staat. |
| Vouwmechanisme in uitgangspositie    | Wit-grijs (I6)   | Controleert of het vouwmechanisme in de uitgangspositie staat. |
| Magazijn leeg                        | Grijs-bruin (I7) | Geeft aan dat het magazijn leeg is. |

---

## Digitale Outputs (Uitgangen)
| *Naam*                             | *Kleur*        | *Beschrijving*                              |
|--------------------------------------|------------------|----------------------------------------------|
| Transportband vooruit                | Wit (Q0)         | Start de transportband in de voorwaartse richting. |
| Transportband achteruit              | Bruin (Q1)       | Start de transportband in de achterwaartse richting. |
| Stopper inschuiven                   | Groen (Q2)       | Laat de stopper inschuiven.                  |
| Voedingscilinder uitschuiven         | Grijs (Q4)       | Laat de voedingscilinder uitschuiven.        |
| Oprichtcilinder uitschuiven          | Roze (Q5)        | Laat de oprichtcilinder uitschuiven.         |
| Arreteercilinder uitschuiven         | Blauw (Q6)       | Laat de arreteercilinder uitschuiven.        |
| Start vouwmechanisme                 | Rood (Q7)        | Start het vouwmechanisme.                    |

---

## Specificaties
| *Parameter*          | *Waarde*                 |
|------------------------|---------------------------|
| Aansluitingen          | 2 x 24-polige IEEE-488 stekker (SysLink) |
| Spanningsvereisten     | 24 V DC, maximaal 4,5 A  |
| Drukluchtverbruik      | 10 l/min bij 600 kPa      |
| Pneumatische aansluitingen | Kunststofslangen van 6 mm buitendiameter |

---

## Functies
- *Detectie*: Ingangen detecteren de aanwezigheid en positie van werkstukken en controleert de status van cilinders en mechanische onderdelen.
- *Besturing*: Uitgangen sturen actuatoren aan, zoals transportbanden, cilinders en vouwmechanismen.
- *Automatisering*: De station kan werkstukken volledig geautomatiseerd verpakken en transporteren.

## Toepassing
De inputs en outputs maken deel uit van het MPS-verpakkingsstation, ontworpen voor gebruik in een leeromgeving om vaardigheden in automatisering en mechatronica te oefenen.

---