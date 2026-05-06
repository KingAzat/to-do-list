# 📝 To-Do List

Une application de liste de tâches simple et efficace permettant d'organiser vos activités quotidiennes.

## 🚀 Fonctionnalités

- **Ajout de tâches** : Saisissez une tâche et appuyez sur "Entrée" ou cliquez sur le bouton d'ajout.
- **Marquage des tâches** : Cliquez sur une tâche pour la marquer comme terminée (barrée).
- **Suppression** : Supprimez facilement les tâches accomplies ou inutiles via l'icône de suppression.
- **Persistance des données** : Vos tâches sont sauvegardées localement dans votre navigateur grâce au `localStorage`, elles ne disparaissent pas après le rafraîchissement de la page.

## 🛠️ Technologies utilisées

- **HTML5** : Structure de l'application.
- **CSS3** : Mise en forme et design.
- **JavaScript (ES6)** : Logique interactive et gestion du stockage local.

## 📦 Installation

1. Clonez le dépôt ou téléchargez les fichiers.
2. Ouvrez le fichier `index.html` dans votre navigateur préféré.

## 📖 Comment ça marche ?

L'application utilise le DOM pour créer dynamiquement des éléments de liste (`<li>`). La fonction `saveData()` enregistre le contenu HTML de la liste dans le `localStorage`, et `showTask()` le récupère au chargement de la page.
