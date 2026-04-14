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

**Reve**

