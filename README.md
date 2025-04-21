# obsidian-dotfiles
Ce dépôt contient ma configuration personnelle d'Obsidian, incluant thèmes, plugins et paramètres personnalisés. Suivez les instructions ci-dessous pour configurer votre Obsidian de la même manière.

## ⚠️ Précautions importantes

- **Faites une sauvegarde** de votre configuration `.obsidian` actuelle avant d'installer celle-ci
- Cette configuration a été testée avec **Obsidian v1.8.9** (dernière version stable)
- Certains chemins ou paramètres peuvent nécessiter des ajustements selon votre système

## 📋 Prérequis

- [Obsidian](https://obsidian.md/) installé sur votre système
- Un vault Obsidian existant (ou créez-en un nouveau)
- Git installé pour cloner ce dépôt (optionnel)


## 💻 Installation rapide (copie directe)

Vous pouvez directement copier le dossier de configuration et le coller ensuite:

0. Révéler les fichiers cachés (`cmd + shift + .` sur mac)

1. Téléchargez ce dépôt (bouton Code > Download ZIP ou clone via git)
   ```bash
   git clone https://github.com/Gauthier13/obsidian-dotfiles.git
   ```

2. Sauvegardez d'abord votre configuration actuelle (fortement recommandé)
   ```bash
   # Remplacez par le chemin vers votre vault Obsidian
   cp -r "/chemin/vers/votre/Vault/.obsidian" "/chemin/vers/votre/Vault/.obsidian.backup"
   ```

3. Copiez simplement le dossier `.obsidian` de ce dépôt dans votre vault Obsidian
   ```bash
   cp -r obsidian-dotfiles/.obsidian "/chemin/vers/votre/Vault/"
   ```

4. Redémarrez Obsidian pour appliquer la nouvelle configuration

⚠️ **Note importante** : Bien que cette méthode copie tous les paramètres et configurations, vous devrez tout de même activer les plugins communautaires listés ci-dessous via l'interface d'Obsidian.


## 🚀 Installation

1. Clonez ce dépôt sur votre ordinateur
   ```bash
   git clone https://github.com/votre-username/obsidian-dotfiles.git
   ```

2. Sauvegardez votre configuration actuelle (si applicable)
   ```bash
   # Remplacez par le chemin vers votre vault
   mv "/chemin/vers/votre/Vault/.obsidian" "/chemin/vers/votre/Vault/.obsidian.backup"
   ```

3. Copiez la configuration dans votre vault
   ```bash
   cp -r obsidian-dotfiles/.obsidian "/chemin/vers/votre/Vault/"
   ```

4. Redémarrez Obsidian et ouvrez votre vault


## 🧩 Plugins communautaires inclus

Les plugins suivants sont configurés mais doivent être installés manuellement via l'interface d'Obsidian :

- Code Styler
- Excalidraw 
- File Color
- File Explorer Note Count
- Iconize
- Omnisearch
- Paste Link
- Style Settings

Pour les installer, allez dans `Paramètres > Plugins communautaires > Parcourir` et recherchez le nom du plugin.

## 🎨 Thème utilisé

Cette configuration utilise le thème Minimal. Vous pouvez l'installer via `Paramètres > Apparence > Thèmes`.
Ou
`Options > Appearance > Themes`

## 📸 Aperçu

<img width="760" alt="image" src="https://github.com/user-attachments/assets/2f5eb742-07fb-4ec7-9415-0a84c2b8009b" />
