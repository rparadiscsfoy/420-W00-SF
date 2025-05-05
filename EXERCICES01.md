# Exercice 1 - Premiers exercices sur Git et Visual Studio

## Objectif

L'objectif de ce module est de vous familiariser avec l'utilisation de Git et GitHub - "version de base".

## Pré-requis

- Avoir installé Git sur votre ordinateur
- Avoir configuré votre client Git sur votre ordinateur
- Avoir installé Visual Studio sur votre ordinateur

## Exercice 1.1 - Accepter votre premier devoir distribué sur GitHub classroom

- Accédez au site à l'URL suivant : [https://classroom.github.com/a/UR43Pm_T](https://classroom.github.com/a/kCTy37AX)
- À votre première connexion, GitHub Classroom va vous demander l'autorisation d'accéder à votre compte GitHub : cliquez sur "Authorize GitHub Classroom". Si vous n'étiez pas authentifié, il faudra préalablement vous connecter à votre compte GitHub.

![Authoriser GitHub Classroom à utiliser votre compte GitHub](img/autoriser_auth_github_githubclassroom.png)

- Acceptez le premier travail en cliquant sur "Accept this assignment"

![Accepter le premier travail](img/accepter_premier_travail.png)

- Une fois accepté, GitHub Classroom va créer votre dépôt de travail qui est en réalité un dépôt GitHub (Cliquez sur le bouton rafraîchir du navigateur - encadré en rouge sur l'image).

![Attente création de ](img/attente_creation_depot.png)

- Une fois rafraîchie, la page affichera le lien vers votre dépôt

![Lien vers votre dépôt](img/attente_depot_cree.png)

## Exercice 1.2 - Ouvrir le travail dans Visual Studio

- Naviguez l'URL de votre dépôt de travail

![Dépôt avant modification](img/github_depot_etudiant_avant_modification.png)

- Copiez le lien de votre dépôt : cliquez le bouton "Code" puis sur les deux carrés à côté du lien

![Copie du lien de votre dépot personnel](./img/adresse_depot.png)

- Lancez "Visual Studio 2022" en cliquant sur le bouton infini mauve/violet (pas le bleu !)

![Visual Studio](./img/icon_VS2022.png)

- Si Visual Studio vous demande de vous identifier, [suivez les instructions de ce lien](CONNEXTION_VS.md)
- Cliquez sur le "Clone un dépôt"

![Ouverture d'un dépôt Git](img/vs_clone_depot_01.png)

- Collez le lien de votre dépôt dans la zone de texte "URL du dépôt" et cliquez sur "Cloner" (si vous avez perdu le lien, vous pouvez le récupérer en retournant sur le site web de Git Hub et en sélectionnant votre dépôt)

![Entrez l'URL du cépôt à cloner](img/vs_clone_travail1.png)

- La première fois que vous allez cloner un dépôt sur GitHub, Visual Studio va vous demander de vous identifier. Cliquez sur le bouton "Sign in with your browser"

![Authentification à GitHub à partir de Visual Studio 2022](img/vs_clone_travail1_authentification.png)

- À partir de la page qui vient de s'ouvrir, cliquez sur le bouton "Authorize GitCredentialManager" qui va autoriser (déléguer) GitCredentialManager (logiciel installé sur votre ordinateur) à accéder à votre compte

![Autoriser GitCredentialManager à accéder à votre compte](img/vs_clone_travail1_authentification_autorisation.png)

- La page suivante va s'afficher pour confirmer que tout s'est bien passé pour la délégation de droits

![Succès de la délégation de droit](img/vs_clone_travail1_authentification_autorisation_succes.png)

- Retournez sur le logiciel Visual Studio. À droite, vous devriez voir le dépôt que vous avez cloné :

![Dossier contenant le clone](img/vs_clone_travail1_ouverture_dossier_racine.png)

- Faites un double clic sur le dossier affiché. Le contenu va s'afficher :

![Contenu du dépôt](img/vs_premier_exercice_avant_modifications_explorateur_solution.png)

- Ouvrez le fichier "README.md" en double cliquant dessus

![Contenu du fichier README.md](img/vs_premier_exercice_avant_modifications.png)

- Modifiez le contenu du fichier en suivant les instructions. Une fois modifié, vous allez enregistrer le fichier avec la combinaisons de touches "Ctrl + S". Vous allez pouvoir observer que le symbole de cadenas est enlevé et est remplacé par un symbole de rouge.

![Exemple de modifications](img/vs_premier_exercice_apres_modifications_plus_explorateur_solution.png)

- Une fois les modifications réalisées cliquez sur l'onglet "Modifications Git" qui se trouve en bas en droite de l'écran.
- Entrez un commentaire de modification et cliquez sur "Valider tout et synchroniser"

![Commit / push](img/vs_premier_exercice_commit_pull_push.png)

- Une fois validée et synchronisée, un message va vous indiquer que ça s'est terminé avec succès

![Commit / push succès](img/vs_premier_exercice_commit_pull_push_apres.png)

- Vous pouvez retourner sur GitHub, rafraichir la page et voir que vos modifications ont bien été enregistrées :

![Rafraîchissement de la page](img/github_depot_etudiant_apres_modification.png)

**Si vous êtes arrivé ici, bravo ! Vous avez fait votre première modification sur votre dépôt de travail et vous les avez transmises en ligne ! Vous pouvez lever la main pour valider et vérifier avec l'enseignant que tout fonctionne bien !**

Sans le savoir vous avez réalisé plusieurs actions dans Git : clone, add, commit, pull, push qui seront détaillées durant votre parcours de formation.

[Retour à la page principale](README.md)
