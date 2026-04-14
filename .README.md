# 🍇 Wineyard Tycoon

Un jeu mobile de simulation viticole éducatif et engageant, inspiré de Wylde Flowers.

## 🎮 À Propos

Wineyard Tycoon vous met à la place d'un vigneron débutant qui doit construire son empire viticole. Commencez en bas de l'échelle avec une petite parcelle, gérez vos vendanges, vinifiez votre vin et vendez-le pour progresser.

### Caractéristiques Principales
- 🌍 **4 régions françaises** : Bordeaux, Bourgogne, Rhône Nord, Rhône Sud
- 👤 **Personnage entièrement personnalisable** : sexe, couleur de peau, vêtements, visage, prénom
- 🍷 **Cycle complet de vinification** : plantation → vendanges → fermentation → mise en bouteille → vente
- 📚 **Éducation viticole progressive** : Apprenez les secrets du vin sans être submergé d'informations
- 🎨 **Style visuel unique** : Flat-art 3D inspiré de Wylde Flowers

## 🚀 Démarrage Rapide

```bash
# Installation
npm install

# Développement
npm run dev

# Build
npm run build
```

## 📁 Structure du Projet

```
wineyard-tycoon/
├── docs/               # Documentation complète
├── src/
│   ├── game/          # Code du jeu
│   ├── data/          # Données (régions, cépages, etc.)
│   ├── assets/        # Ressources graphiques et audio
│   └── config/        # Configuration du jeu
├── tests/             # Tests unitaires
└── package.json
```

## 📚 Documentation

- [GDD.md](docs/GDD.md) - Game Design Document
- [VITICULTURE_INFO.md](docs/VITICULTURE_INFO.md) - Base éducative
- [REGIONS.md](docs/REGIONS.md) - Spécifications régionales
- [VISUAL_IDENTITY.md](docs/VISUAL_IDENTITY.md) - Guide d'art

## 🎯 Niveaux de Progression

**Niveau 1 (Tutorial)** : Apprentissage des bases
- Plantation manuelle des vignes
- Observation du cycle de croissance
- Vendanges à la main
- Vinification simple
- Première vente

**Niveaux 2-5** : Développement
- Acquisition de machines et équipement
- Main d'œuvre
- Nouveaux cépages
- Amélioration du chai

**Niveaux 6+** : Expertise
- Déverrouillage de nouvelles régions
- Marchés premium
- Assemblages complexes

## 🛠️ Tech Stack

- **Moteur** : Phaser 3
- **Langage** : TypeScript
- **Build** : Webpack
- **Tests** : Jest

## 📝 Licence

MIT - Voir [LICENSE](LICENSE)

## 🤝 Contribution

Les contributions sont bienvenues ! Consultez [CONTRIBUTING.md](CONTRIBUTING.md) pour plus de détails.
