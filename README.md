
# Mod Minecraft : Mon Premier Bloc

Ce mod ajoute un nouveau bloc personnalisé à Minecraft. C'est un projet simple pour apprendre les bases du développement de mods avec Minecraft Forge.

## Fonctionnalités

- Ajoute un nouveau bloc avec une texture personnalisée.
- Le bloc peut être placé et cassé dans le monde de Minecraft.

## Prérequis

- Minecraft Forge installé pour la version de Minecraft correspondante.
- Java Development Kit (JDK) installé.

## Installation

1. **Télécharger le Mod** :
   - Téléchargez le fichier `.jar` du mod depuis la section des [releases](#).

2. **Installer le Mod** :
   - Placez le fichier `.jar` dans le dossier `mods` de votre installation Minecraft.

3. **Lancer Minecraft** :
   - Lancez Minecraft avec le profil Forge pour charger le mod.

## Utilisation

1. **Créer un Nouveau Monde ou Charger un Monde Existant** :
   - Le nouveau bloc sera disponible dans l'inventaire créatif sous l'onglet "Décorations" ou un autre onglet personnalisé.

2. **Placer le Bloc** :
   - Sélectionnez le bloc dans votre inventaire et placez-le dans le monde comme n'importe quel autre bloc.

## Personnalisation

- **Texture** : Vous pouvez modifier la texture du bloc en remplaçant le fichier `my_first_block.png` dans le dossier `src/main/resources/assets/mymod/textures/blocks/`.
- **Propriétés** : Ajustez les propriétés du bloc (dureté, résistance, etc.) dans le fichier `MyFirstBlock.java`.

## Développement

### Préparer l'Environnement de Développement

1. **Installer Java Development Kit (JDK)** :
   - Assurez-vous d'avoir installé le JDK sur votre machine.

2. **Configurer Minecraft Forge** :
   - Téléchargez et installez Minecraft Forge MDK (Mod Development Kit) pour la version de Minecraft souhaitée.

3. **Configurer l'IDE** :
   - Utilisez IntelliJ IDEA ou Eclipse pour importer le projet Forge.

### Construire le Mod

1. **Générer le Projet** :
   - Utilisez Gradle pour configurer le projet :
     ```bash
     gradlew setupDecompWorkspace eclipse  # Pour Eclipse
     gradlew setupDecompWorkspace idea    # Pour IntelliJ IDEA
     ```

2. **Construire le Mod** :
   - Utilisez Gradle pour construire le mod :
     ```bash
     gradlew build
     ```

3. **Tester le Mod** :
   - Lancez Minecraft depuis votre IDE pour tester le mod.

## Contribuer

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez le projet.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/nouvelle-fonctionnalite`).
3. Commitez vos modifications (`git commit -m 'Ajouter une nouvelle fonctionnalité'`).
4. Poussez vers la branche (`git push origin feature/nouvelle-fonctionnalite`).
5. Ouvrez une Pull Request.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.


