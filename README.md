# Le Couvoir

Jeu mobile 3D en vue isométrique : survivre à son service au couvoir sans se faire repérer par le responsable.

## Prototype 0.1
- Décor 3D de couvoir avec couveuses, plateaux, tables et couloir.
- Personnage joueur et responsable en patrouille.
- Déplacement au joystick tactile ou au clavier (ZQSD / WASD).
- Trois avertissements avant le licenciement.
- Actions : se cacher près d'une couveuse, faire semblant de travailler, créer une distraction.
- Service de trois minutes, score et record local.
- Interface responsive pensée pour mobile.

## Lancer le jeu
Le projet utilise Three.js en module ES depuis jsDelivr. Il faut servir le dossier via HTTP(S), pas ouvrir index.html directement.
Pour tester localement : `npx serve .`
Puis ouvrir l'adresse indiquée.

## Prochaines étapes
1. Tester le déplacement et l'IA sur téléphone.
2. Ajouter les collisions et des cachettes réellement protégées par la géométrie.
3. Ajouter collègues, événements aléatoires, niveaux et progression.
4. Créer des modèles 3D plus détaillés, animations et sons d'ambiance.

Cette version est un prototype de départ, pas encore la version finale.