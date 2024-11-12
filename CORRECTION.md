# Correction de l'exercice : Ajouter votre nom dans le fichier `index.html`

## Objectif
L'objectif de cet exercice est de vous familiariser avec les commandes Git de base, y compris le fork, le clonage, la création de branches, la modification de fichiers et la soumission de Pull Requests.

### **Correction détaillée des étapes**

---

### 1. **Forker le repository**

**Ce que vous devez faire :**
   - Allez sur la page du repository du projet sur GitHub.
   - Cliquez sur le bouton **Fork** en haut à droite de la page pour créer une copie du repository sous votre propre compte GitHub.

**Correction :**
   - Après avoir forké le repository, vous aurez une copie de celui-ci dans votre propre compte GitHub. C'est à partir de ce fork que vous allez travailler.

---

### 2. **Cloner votre repository forké**

**Ce que vous devez faire :**
   - Une fois le fork effectué, copiez l'URL de votre repository forké depuis GitHub.
   - Ouvrez votre terminal et clonez le repository sur votre machine locale avec la commande suivante (remplacez `votre-username` par votre nom d'utilisateur GitHub) :
     ```bash
     git clone https://github.com/votre-username/nom-du-repository.git
     cd nom-du-repository
     ```

**Correction :**
   - Vous avez maintenant une copie locale du repository.
   - `git clone` télécharge tout le contenu du repository dans un dossier local sur votre ordinateur, prêt à être modifié.

---

### 3. **Créer une nouvelle branche**

**Ce que vous devez faire :**
   - Créez une branche spécifique pour vos modifications. Utilisez un nom de branche distinct qui vous identifiera, comme par exemple votre prénom ou un identifiant unique :
     ```bash
     git checkout -b prenom-nom
     ```

**Correction :**
   - Il est essentiel de travailler sur une branche distincte de `main` pour éviter les conflits et pour garder la branche `main` stable.
   - L'utilisation de noms de branches uniques (par exemple `prenom-nom`) aide à identifier facilement la contribution de chaque étudiant.

---

### 4. **Modifier le fichier `index.html`**

**Ce que vous devez faire :**
   - Ouvrez le fichier `index.html` dans un éditeur de texte ou un IDE.
   - Ajoutez votre nom dans une section appropriée du fichier. Par exemple, vous pouvez ajouter un élément `<h1>` contenant votre nom :
     ```html
     <h1>Bienvenue sur le site de [votre prénom et nom]</h1>
     ```

**Correction :**
   - Cette modification permet d'ajouter votre nom dans le fichier HTML, en contribuant ainsi au projet de manière simple.
   - Assurez-vous de ne pas supprimer ou modifier d'autres parties du fichier.

---

### 5. **Commiter vos modifications**

**Ce que vous devez faire :**
   - Après avoir effectué les modifications dans `index.html`, vous devez les enregistrer avec un commit. Cela permet de sauvegarder vos changements localement avant de les envoyer sur GitHub.
   - Exécutez les commandes suivantes pour ajouter et committer vos modifications :
     ```bash
     git add index.html
     git commit -m "Ajout de mon nom dans le fichier index.html"
     ```

**Correction :**
   - `git add` ajoute les modifications que vous avez effectuées à l'index (prépare le fichier pour le commit).
   - `git commit` enregistre définitivement ces modifications dans l'historique local de votre branche.

---

### 6. **Pousser vos modifications sur GitHub**

**Ce que vous devez faire :**
   - Après avoir commité vos modifications, vous devez les envoyer (pousser) sur votre fork GitHub avec la commande suivante :
     ```bash
     git push origin prenom-nom
     ```

**Correction :**
   - Cette commande envoie vos modifications sur la branche de votre fork GitHub, où elles peuvent être consultées et fusionnées dans le projet principal.

---

### 7. **Créer une Pull Request**

**Ce que vous devez faire :**
   - Allez sur votre repository forké sur GitHub.
   - Cliquez sur l'onglet **Pull Requests** puis sur le bouton **New Pull Request**.
   - Sélectionnez votre branche (par exemple `prenom-nom`) et comparez-la avec la branche `main` du repository original.
   - Cliquez sur **Create Pull Request** et ajoutez une description de vos modifications (par exemple : "Ajout de mon nom dans le fichier index.html").

**Correction :**
   - Une Pull Request (PR) est une demande pour que vos modifications soient fusionnées dans la branche principale du repository.
   - Assurez-vous que votre PR décrit clairement les changements effectués pour que le mainteneur du projet puisse les examiner facilement.

---

## Vérification et fusion des Pull Requests

1. **Passer en revue la Pull Request** : Une fois votre PR soumise, le mainteneur du projet (vous ou quelqu'un d'autre) vérifie les modifications.
2. **Fusionner la Pull Request** : Si tout est correct, la PR sera fusionnée dans la branche `main` du repository original.
3. **Mettre à jour votre fork** : Une fois que la PR est fusionnée, vous pouvez mettre à jour votre fork pour rester à jour avec la branche `main` du projet original.

---

## Remarques finales

- **Conventions de nommage** : Assurez-vous d'utiliser un nom de branche unique pour éviter toute confusion avec d'autres étudiants.
- **Modifications limitées** : N'oubliez pas de ne modifier que le fichier `index.html` et de ne pas toucher aux autres fichiers du repository.
- **Demandez de l'aide** : Si vous rencontrez des problèmes ou avez des questions sur l'exercice, n'hésitez pas à me contacter.

Bonne chance, et félicitations pour avoir complété cet exercice ! 🎉
