# 🤝 Contribuer à Wineyard Tycoon

Merci de votre intérêt pour contribuer à ce projet ! Voici les directives.

## 📋 Avant de Commencer

1. Fork le repository
2. Clonez votre fork localement
3. Créez une branche pour votre feature : `git checkout -b feature/ma-feature`

## 💻 Standards de Code

### TypeScript
- Utilisez TypeScript strict
- Respectez les conventions de nommage camelCase
- Documentez les fonctions avec JSDoc

### Organisation
```typescript
// Exemple de structure de classe
export class VineCycle {
  private vineState: VineState;
  private growthStage: number;

  /**
   * Avance le cycle de croissance de la vigne
   * @param deltaTime - Temps écoulé en heures
   */
  public update(deltaTime: number): void {
    // Implémentation
  }
}
```

## 📊 Structure des Commits

```
[TYPE] Description courte

Description détaillée si nécessaire

- Point 1
- Point 2
```

Types de commit :
- `feat:` Nouvelle fonctionnalité
- `fix:` Correction de bug
- `docs:` Documentation
- `refactor:` Refactorisation
- `test:` Tests
- `style:` Formatage

Exemple :
```
feat: Ajouter le système de fermentation

- Implémentation des courbes de température
- Gestion des arômes développés
- UI interactive pour la fermentation
```

## 🧪 Tests

Avant de soumettre :
```bash
npm test
npm run build
```

## 📝 Pull Request

1. Décrivez clairement vos changements
2. Référencez les issues pertinentes
3. Mettez à jour la documentation si nécessaire
4. Assurez-vous que les tests passent

## 📚 Documentation

Mettez à jour les fichiers pertinents dans `/docs` :
- GDD.md pour les changements de gameplay
- TECHNICAL_ARCHITECTURE.md pour les changements architecturaux

## 🎨 Style Visuel

Consultez [VISUAL_IDENTITY.md](docs/VISUAL_IDENTITY.md) pour :
- Palette de couleurs
- Proportions des éléments
- Animations et transitions

## ❓ Questions ?

Ouvrez une issue pour discuter de vos idées avant de commencer le développement !

Merci ! 🍷
