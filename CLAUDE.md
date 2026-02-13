# Landing Page Ventilateurs Pro — Fan Boutique

## Contexte projet
- **Client** : Fan Boutique (ventilateurs-plafond.com)
- **Objectif** : Campagne Google Ads B2B ciblant les professionnels (hôtels, restaurants, industrie, commerces, bureaux, terrasses)
- **Landing page** : Page dédiée aux pros sur ventilateurs-plafond.com avec formulaire de devis (pas d'achat direct)
- **Site B2B existant** : klassfan.com (même entreprise, autre domaine)
- **Page Notion** : https://www.notion.so/306fa815888b8121a519d14563e339cd

## Design de la landing page
- **Couleurs** : Orange `#ff750e` (CTA), bleu marine `#1a1a2e` (header, hero, section devis), hover `#f36800`
- **Boutons** : border-radius: 4px (comme les CTA du site original)
- **Police** : Inter (Google Fonts)
- **Logo** : texte blanc → header doit rester sombre
- **Téléphone** : 01 79 73 23 00

## Structure de la landing page (index.html)
1. **Header sticky** — Logo + nav interne + téléphone (fond bleu marine)
2. **Hero** — Titre + sous-titre + double CTA + formulaire de devis rapide à droite
3. **Barre stats** — 2000+ réf, 15 ans, 24h réponse, -50% conso clim
4. **6 cas d'usage** — Hôtellerie, Restauration, Commerce, Industrie, Bureaux, Terrasses
5. **6 avantages pro** — Devis 24h, TVA récupérable, Livraison chantier, Conseil expert, 2000+ réf, Double usage été/hiver
6. **4 produits phares** — HVLS 180cm, Plafond haut 152cm, IP44 terrasse, Design hôtellerie
7. **Formulaire devis complet** — Fond sombre + checklist à gauche + formulaire à droite
8. **Réassurance** — Experts, catalogue, livraison, SAV, avis
9. **Footer** — Téléphone, liens, copyright

---

## Recherche mots-clés B2B (Google Ads Keyword Planner)

Volume = moyenne juin-juillet-août 2025 (pic saison été)

### INDUSTRIEL (5 mots-clés — ~2 006 vol. été)
| # | Mot-clé | Vol. été | CPC haut | Conc. | Commentaire |
|---|---------|:--------:|:--------:|:-----:|-------------|
| 1 | ventilateur plafond industriel | 923 | 1,57 € | HIGH | Plus gros volume B2B. Part de B2C "style indus" à filtrer |
| 2 | grand ventilateur plafond industriel | 413 | 1,30 € | HIGH | Très qualifié B2B - "grand" = pas un salon |
| 3 | ventilateur de plafond industriel | 203 | 1,35 € | HIGH | Variante avec "de" |
| 4 | brasseur air industriel | 427 | - | HIGH | 100% B2B |
| 5 | brasseur d air plafond industriel | 40 | - | HIGH | Niche ultra-qualifié |

### PROFESSIONNEL (3 mots-clés — ~480 vol. été)
| # | Mot-clé | Vol. été | CPC haut | Conc. | Commentaire |
|---|---------|:--------:|:--------:|:-----:|-------------|
| 6 | ventilateur plafond professionnel | 250 | 1,37 € | HIGH | Intention pro explicite |
| 7 | brasseur d air professionnel | 157 | 2,60 € | HIGH | CPC le plus cher = forte valeur |
| 8 | ventilateur de plafond professionnel | 73 | 1,08 € | HIGH | Variante |

### LIEUX PROFESSIONNELS (10 mots-clés — ~404 vol. été)
| # | Mot-clé | Vol. été | CPC haut | Conc. | Commentaire |
|---|---------|:--------:|:--------:|:-----:|-------------|
| 9 | ventilateur plafond magasin | 110 | - | HIGH | Commerce de détail |
| 10 | ventilateur plafond atelier | 87 | 1,05 € | HIGH | Artisans, production |
| 11 | ventilateur plafond pergola | 60 | - | HIGH | Terrasses restaurants |
| 12 | ventilateur plafond grande surface | 47 | - | HIGH | GMS ou grande pièce |
| 13 | ventilateur plafond restaurant | 30 | - | HIGH | 100% B2B, ultra-ciblé |
| 14 | ventilateur plafond garage | 27 | - | HIGH | Garage pro / mécanique |
| 15 | ventilateur plafond hangar | 17 | - | HIGH | 100% B2B, logistique |
| 16 | ventilateur plafond bureau | 13 | - | HIGH | Bureaux / open space |
| 17 | ventilateur plafond salle de sport | 10 | - | HIGH | 100% B2B |
| 18 | ventilateur plafond commercial | 3 | - | - | Très faible mais pertinent |

### GRANDE DIMENSION (14 mots-clés — ~2 489 vol. été)
| # | Mot-clé | Vol. été | CPC haut | Conc. | Commentaire |
|---|---------|:--------:|:--------:|:-----:|-------------|
| 19 | grand ventilateur plafond | 650 | 1,40 € | HIGH | Particulier rarement "grand" |
| 20 | ventilateur plafond grande taille | 287 | 0,69 € | HIGH | Grandes pales = pro |
| 21 | ventilateur plafond grande hauteur | 263 | 1,32 € | HIGH | Plafond haut = bâtiment pro |
| 22 | big ass fan | 250 | - | LOW | Marque B2B leader. Concurrence LOW ! |
| 23 | ventilateur pour plafond haut | 243 | 0,72 € | HIGH | Signal pro fort |
| 24 | ventilateur plafond puissant | 253 | 0,51 € | HIGH | Puissance = grands espaces |
| 25 | grand ventilateur de plafond | 293 | 0,60 € | HIGH | Variante de #19 |
| 26 | ventilateur plafond grande pale | 140 | 0,84 € | HIGH | Grandes pales = pro |
| 27 | ventilateur plafond grand diametre | 117 | - | HIGH | Acheteur averti |
| 28 | ventilateur de plafond grande taille | 97 | 0,52 € | HIGH | Variante de #20 |
| 29 | ventilateur plafond grand volume | 73 | 0,76 € | HIGH | Terme pro |
| 30 | ventilateur plafond grand format | 60 | - | HIGH | Idem |
| 31 | très grand ventilateur de plafond | 33 | - | HIGH | Pas un appart |
| 32 | ventilateur hvls | 33 | - | HIGH | 100% B2B (High Volume Low Speed) |

### TAILLE SPÉCIFIQUE (3 mots-clés — ~354 vol. été)
| # | Mot-clé | Vol. été | CPC haut | Conc. | Commentaire |
|---|---------|:--------:|:--------:|:-----:|-------------|
| 33 | ventilateur plafond 180 cm | 100 | 0,80 € | HIGH | Hors norme résidentiel |
| 34 | ventilateur plafond 150 cm | 157 | 0,86 € | HIGH | Mixte, >132cm = signal pro |
| 35 | ventilateur plafond 120 cm | 97 | 1,18 € | HIGH | Plus mixte, 120cm existe en résidentiel |

### EXTÉRIEUR / TERRASSE PRO (6 mots-clés — ~1 187 vol. été)
| # | Mot-clé | Vol. été | CPC haut | Conc. | Commentaire |
|---|---------|:--------:|:--------:|:-----:|-------------|
| 36 | ventilateur plafond extérieur terrasse | 450 | 0,49 € | HIGH | Terrasses CHR + particuliers |
| 37 | ventilateur plafond extérieur ip44 | 257 | 1,22 € | HIGH | IP44 = acheteur pro |
| 38 | ventilateur plafond terrasse | 190 | 0,66 € | HIGH | Souvent CHR |
| 39 | ventilateur plafond longue tige | 140 | 0,67 € | HIGH | Plafond haut = pro |
| 40 | ventilateur plafond ip44 | 113 | - | HIGH | Acheteur averti/pro |
| 41 | ventilateur plafond tige longue | 37 | 0,37 € | HIGH | Variante #39 |

### RÉSUMÉ
| Thématique | Nb KW | Vol. été cumulé | Fiabilité B2B |
|------------|:-----:|:--------------:|:-------------:|
| Industriel | 5 | ~2 006 | Forte |
| Professionnel | 3 | ~480 | Très forte |
| Lieux professionnels | 10 | ~404 | Très forte |
| Grande dimension | 14 | ~2 489 | Forte |
| Taille spécifique | 3 | ~354 | Moyenne |
| Extérieur / terrasse pro | 6 | ~1 187 | Moyenne |
| **TOTAL** | **41** | **~6 920** | |

---

## Stratégie campagne Google Ads B2B

### Structure ad groups recommandée
1. **"Industriel/Professionnel"** — mots-clés 1-8
2. **"Grande dimension/Plafond haut"** — mots-clés 19-35
3. **"Terrasse extérieur pro"** — mots-clés 36-41
4. **"Lieux professionnels"** — mots-clés 9-18

### Ciblage par appareil
- Desktop : enchères +15 à +20%
- Mobile : enchères -20%
- Tablette : enchères -30%

### Programmation horaire
- Lun-Ven 8h-18h : enchères normales ou +20%
- Soir 18h-22h + Samedi : -30%
- Dimanche + nuit : -50% ou pause

### Mots-clés négatifs anti-B2C
- **Pièces maison** : maison, chambre, salon, appartement, cuisine, séjour
- **Enseignes B2C** : amazon, cdiscount, leroy merlin, castorama, brico depot, darty, conforama
- **Déco / style** : style industriel, déco, design, bohème, scandinave
- **Prix / promo** : pas cher, promo, soldes, bon plan, discount, occasion
- **Comparatif B2C** : avis, comparatif, test, meilleur (optionnel)

### Extensions d'annonces pro
- **Titres** : "Ventilateurs Plafond Pro", "Pour Professionnels", "Devis en 24h"
- **Sitelinks** : "Devis gratuit", "Livraison chantier", "Installateur agréé", "Catalogue pro"
- **Accroches** : "Sur facture pro", "TVA récupérable", "Volume > 10 unités", "Pose disponible"
- **Extraits de site** : Types : Hôtellerie, Restauration, Industrie, Commerce, Bureaux

---

## Analyse landing page existante

### Espace Pro actuel (ventilateurs-plafond.com/content/8-professionnel)
- Cible les **revendeurs/distributeurs**, PAS les acheteurs pro finaux
- Formulaire orienté partenariat (SIRET, forme juridique, profil distributeur)
- Pas adapté pour un hôtelier ou restaurateur

### klassfan.com (site B2B séparé)
- Pages par secteur : Hôtellerie, Restauration, Industrie, Bureaux
- Configurateur produit (10 000+ possibilités)
- Bonne structure B2B mais domaine différent → mauvais Quality Score si campagne sur ventilateurs-plafond.com

### Conclusion
Il faut créer une landing page dédiée sur ventilateurs-plafond.com pour l'**acheteur pro final** (hôtelier, restaurateur, responsable d'entrepôt) avec un formulaire de devis simplifié (pas le formulaire "distributeur" actuel).
