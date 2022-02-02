# SI_Site
Mon premier site pour déposer les comptes rendus de mes projets de SI

Ce site sera bientôt visible à l'adresse : https://github.com/NoeFlamanc/SI_Term.git

# TP Régulation Thermique
## Calculs des déperditions dans la nouvelle pièce

1.1. Rthlv = 0,2/0,041 = 4,878 m²*K/W

1.2. Rthpl = 0,013/0,46 = 0,03 m²*K/W

2. Surfaces en m² :

|  S1  |  S2  |  S3   |  S4   |
|----------|:-------------:|-----:|------:|
| 9,75 | 8,775 | 3,315 | 11,105 |

3.  U = 1 / Rth

U1 = U2 = U3 = 0,03 + 4,88 = 0,204 W/m²*K

U4 = 0,03 + 4,88 + 0,4 = 0,188 W/m²*K

4.  Coefficients de déperdition thermique en W/k (U*S) :

|  H1  |    H2    | H3 | H4 | Htotal |
|----------|:-------------:|-----:|-------:|------:|
| 1,99 | 1,79 | 0,68 | 2,09 | 9,02 |

## Etude de la régulation thermique Tout ou Rien

DJU = 2200 (hiver doux) :
| Consigne de Température (°C)   |   Température pièce (°C)    | Puissance elec moyenne (W) |  Energie moyenne (kWh)    |
|----------|:-------------:|-----:|-------:|
| 19 | 19 | 110 | 612,48  |
| 20 |   20  | 116 |  645,9  |
| 25 | 25 | 176  |  980   |

DJU = 3000 (hiver rude) : 
| Consigne de Température (°C)   |   Température pièce (°C)    | Puissance elec moyenne (W) |  Energie moyenne (kWh)    |
|----------|:-------------:|-----:|-------:|
| 19 | 19,015 | 142 | 790,7  |
| 20 |   20  | 150 |  835,2  |
| 25 | 25,015 | 203  |  1130,3   |

## Etude de la régulation thermique Proportionnelle Intégrale

DJU = 2200 (hiver doux) :
| Consigne de Température (°C)   |   Température pièce (°C)    | Puissance elec moyenne (W) |  Energie moyenne (kWh)    |
|----------|:-------------:|-----:|-------:|
| 19 |  |  |   |
| 20 |     |  |    |
| 25 |  |  |     |

DJU = 3000 (hiver rude) :
| Consigne de Température (°C)   |   Température pièce (°C)    | Puissance elec moyenne (W) |  Energie moyenne (kWh)    |
|----------|:-------------:|-----:|-------:|
| 19 | 19 | 127 | 707  |
| 20 |   20  | 136 |  757  |
| 25 | 25 | 180  |  1002  |
