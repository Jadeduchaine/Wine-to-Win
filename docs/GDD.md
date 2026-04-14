# 🎮 Game Design Document - Wineyard Tycoon

## 1. Vue d'Ensemble

**Titre** : Wineyard Tycoon
**Genre** : Simulation / Gestion / Éducation
**Plateforme** : Mobile (iOS/Android)
**Public Cible** : 18+
**Inspiration** : Wylde Flowers (gameplay, design, fluidité)

## 2. Concept Principal

Le joueur incarne un vigneron débutant qui construit son empire viticole français. À travers des vendanges, de la vinification et des ventes, il améliore progressivement son domaine. Le jeu combine **mécanique de simulation réaliste** avec **éducation viticole progressive**.

## 3. Boucle de Jeu Principale

```
Plantage → Croissance (3-4 mois) → Vendanges Manuelles → Vinification
→ Mise en Bouteille → Vente → Revenus → Investissement → Retour Vignes
```

**Durée d'un cycle** : 20-30 minutes de jeu actif

## 4. Personnalisation du Joueur

Le joueur crée son avatar immédiatement après l'écran d'accueil :

### Options de Personnalisation
- **Sexe** : Homme / Femme / Autre
- **Couleur de Peau** : 6 variations
- **Prénom** : Champ texte libre
- **Visage** : 8 options différentes
- **Cheveux** : Couleur + Style (8 combos)
- **Vêtements** : Tenue de travail personnalisée

### Persistance
Le personnage est sauvegardé et réutilisable pour les nouvelles régions

## 5. Sélection de Région

Après création du personnage :

1. **Choix entre 3 régions** (1ère partie du jeu) :
   - Bordeaux (Maritime, assemblages)
   - Bourgogne (Continental, terroir)
   - Rhône Nord (Pentes, Syrah)

2. **Déblocage progressif** :
   - Débloquer les autres régions seulement après complétion Niveaux 1-5
   - Nécessite un domaine "remarquable" (critères spécifiques)

3. **Sélection AOC** :
   Après la région, choisir parmi 3-4 AOCs (exemple pour Bordeaux : Pauillac, Margaux, Saint-Julien)

4. **Nom du Domaine** :
   Nommer son château/domaine

## 6. Progression par Niveaux

### Niveau 1 : Les Fondamentaux

**Objectif** : Apprendre plantation → vendanges → vinification basique

**Mécaniques** :
- ✅ Plantation manuelle (guides + explications)
- ✅ Observation croissance (4 stades visuels)
- ✅ Vendanges manuelles (cagettes 10kg)
- ✅ Chai rudimentaire (cuve béton + fût chêne)
- ✅ Mise en bouteille manuelle
- ✅ Vente caveau (10-20 bouteilles)

**Restrictions** :
- Pas de machines
- Pas de main d'œuvre
- 1 cépage seulement

**Revenus** : ~500-1000 crédits

---

### Niveaux 2-5 : Développement

**Nouvelles mécaniques** :
- 🤖 Achat de machines (vendangeuse, fouleur, pressurage)
- 👷 Embauche de main d'œuvre
- 🍇 Diversification cépages
- 🏭 Amélioration chai (cuves inox, fûts multiples)
- 📊 Gestion rendement

**Revenus progressifs** : 1000 → 5000 crédits

---

### Niveaux 6+ : Expertise

- 🌍 Accès à nouvelles régions
- 🍷 Assemblages complexes
- 🎯 Marchés premium
- 💰 Gestion financière avancée

## 7. Mécanique de Plantation

### Étapes
1. **Choix parcelle** : Cliquer sur zone du vignoble
2. **Choix cépage** : Menu popup avec 1-3 options
3. **Animation plantation** : Personnage plante les pieds
4. **Temps de croissance** : 3-4 mois de jeu (accéléré)

### Visuel de Croissance
- **Stade 1** : Jeunes plants (2 semaines)
- **Stade 2** : Feuilles développées (4-6 semaines)
- **Stade 3** : Premières grappes (6-8 semaines)
- **Stade 4** : Raisins mûrs prêts vendanges (final)

### Facteurs de Succès
- ☀️ Exposition (automatique par région)
- 💧 Eau (selon météo)
- 🌡️ Température (selon région/saison)

## 8. Vendanges

### Mécanique
- Joueur guide son personnage à travers vignes
- Contrôle : Pad/Joystick virtuel
- Cagettes de 10kg à remplir
- Temps requis : 10-15 min selon rendement

### Progression
- Niveau 1 : Manuel à 100%
- Niveaux 2+ : Option vendangeuse mécanique

### Rendement
Exemple :
- 100m² vignes = 500-800kg raisins
- 1 cagette = 10kg
- Durée manuelle : ~15 min pour tout

## 9. Vinification

### Processus Simplifié (Niveau 1)

**Étape 1 : Réception**
- Apport raisins au chai
- Contrôle état sanitaire

**Étape 2 : Foulage**
- Écrasement grappes (1-2 min animation)

**Étape 3 : Macération en Cuve**
- Durée : 7-15 jours (accéléré)
- Gestion température : 18-28°C
- Infos progressives :
  - "Tannins s'extraient à 25°C"
  - "Arômes se développent lentement à 20°C"

**Étape 4 : Élevage en Fût**
- Durée : 6-12 mois (accéléré)
- Fût chêne français
- Infos : "Vanille, épices se développent"

**Étape 5 : Assemblage** (futurs niveaux)
- Mélanger plusieurs lots
- Ajustements finaux

### Interface Vinification

**Panneau de contrôle** :
```
Cuve 1 : Pinot Noir
├─ Température : 22°C ⭐
├─ Jour 5/15 macération
├─ Arômes détectés : Fruits rouges, fleurs
└─ Qualité : 78%
```

Ajustements possibles :
- Augmenter/baisser température
- Ajouter SO₂ (conservation)
- Remontage (oxygénation)

## 10. Mise en Bouteille

### Processus
1. Préparation bouteilles
2. Remplissage (animation)
3. Étiquetage
4. Bouchage

### Automatisation
- Niveau 1 : Manuel 100%
- Niveaux 2+ : Machine semi-auto

## 11. Système Économique

### Revenus
- Vente caveau : 5-10€ bouteille
- Vente en ligne : 8-15€ bouteille
- Vente restaurants : 15-25€ bouteille (niveaux avancés)

### Dépenses
- Machines : 1000-5000 crédits
- Main d'œuvre : 10-50 crédits/jour
- Fournitures : 2-5 crédits/bouteille
- Maintenance chai : 100 crédits/mois

### Exemple Niveau 1
```
Revenu vendanges : 800kg × 1.5€/kg = 1200€
Coût fournitures : 80 bouteilles × 2€ = 160€
PROFIT : 1040€
```

## 12. Système d'Information Éducative

### Principe : **Délicate & Progressive**

Ne pas surcharger le joueur, mais l'informer constamment.

### Canaux d'Information

1. **Pop-ups contextuels** (Priorité haute)
   - Apparaissent au moment critique
   - Disparaissent après 5 secondes
   - Exemple : "La température monte trop ! Aérez la cuve"

2. **Glossaire interactif**
   - Appuyer sur "?" pour explications
   - Définitions courtes (2-3 lignes)

3. **Panneaux bas écran**
   - Non-bloquants
   - Information continue
   - Exemple : "Jour 7/15 : Tannins en extraction"

4. **Animations subtiles**
   - Pulsation légère pour attirer attention
   - Couleurs de highlight discret

### Exemples d'Infos Progressives

**Plantation** :
"🌱 La vigne a besoin de chaleur, lumière, eau et nutriments"

**Croissance** :
"📈 Les raisins accumulent du sucre et développent des arômes"

**Vendanges** :
"⏰ Plus on attend, plus les raisins sont sucrés (mais risque pouriture)"

**Fermentation** :
"🌡️ À 22°C, les levures fermentent activement → alcool + CO₂"

**Élevage** :
"🛢️ Le contact avec le bois apporte vanille et épices"

## 13. Régions

### Bordeaux
- **Climat** : Maritime modéré
- **Risques** : Pluie, dilution, pourriture
- **Force** : Assemblages de cépages
- **Cépages** : Cabernet, Merlot, Cabernet Franc

### Bourgogne
- **Climat** : Continental froid
- **Risques** : Gel, mauvaise maturation
- **Force** : Expression du terroir
- **Cépages** : Pinot Noir, Chardonnay

### Rhône Nord
- **Climat** : Continental modéré
- **Risques** : Vent (Mistral), difficulté maturation
- **Force** : Vins puissants
- **Cépages** : Syrah, Viognier

### Rhône Sud
- **Climat** : Méditerranéen chaud
- **Risques** : Sécheresse, vent, chaleur
- **Force** : Assemblages complexes
- **Cépages** : Grenache, Syrah, Mourvèdre

## 14. Système de Sauvegarde

### Auto-save
- Chaque action importante sauvegardée
- Cloud sync (optionnel)

### Données Persistantes
- État vignes
- Chai equipment
- Finances
- Progression niveaux
- Domaine customs

## 15. Interface Utilisateur

### HUD Principal
```
[Finances] [Calendrier] [Objectifs] [Menu]
     ↑           ↑           ↑         ↑
  Crédits   Jour/Saison    TODO    Settings
```

### Zones Principales
- **Vignoble** : Vue isométrique, contrôle personnage
- **Chai** : Interface statique, gestion procédés
- **Caveau** : Vente, historique

## 16. Courbe de Difficulté

```
Niveau 1 : Tutorial (facile)
Niveau 2 : Premiers choix (facile-moyen)
Niveaux 3-5 : Gestion ressources (moyen)
Niveaux 6+ : Optimisation (moyen-difficile)
```

## 17. Métriques de Succès

- **Playability** : Boucle claire et addictive
- **Éducation** : Joueur apprend viticulture naturellement
- **Lonévité** : 20-30h minimum de gameplay
- **Accessibilité** : Compréhensible par débutants

## 18. Prochaines Phases

**Phase 2** : Multiplayer (compétition domaines)
**Phase 3** : Contrats restaurants
**Phase 3** : Système météo dynamique avancé
