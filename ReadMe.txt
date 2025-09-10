====================================================
ReadMe - Laboratoire 1 : Gestion de version (Git/GitHub)
====================================================

Résumé de mes apprentissages :
------------------------------
- J’ai appris à initialiser un dépôt local, à le publier sur GitHub et à le synchroniser.
- J’ai simulé la collaboration entre deux membres (moi et Elvis) en utilisant soit des branches, soit des clones séparés.
- J’ai compris l’importance des issues pour décrire un problème et du revert pour corriger sans casser l’historique.

Ma Git cheat-sheet (personnelle) :
----------------------------------
- git init : Initialiser un dépôt local
- git clone <url> : Cloner un dépôt distant
- git status : Voir l’état du répertoire de travail
- git add -A : Ajouter toutes les modifications à l’index
- git commit -m "message" : Enregistrer les changements localement
- git branch -M main : Renommer la branche courante en main
- git checkout -b nom : Créer et basculer sur une nouvelle branche
- git push -u origin main : Pousser la branche main sur le serveur
- git pull: Récupère tout l'historique du dépôt  nommé et incorpore les modifications
- git pull --rebase origin main : Récupérer les modifications du serveur et les appliquer proprement
- git log --oneline --graph --all : Voir l’historique simplifié
- git revert <hash> : Annuler un commit fautif sans écraser l’historique
- git config --global user.name "[nom]"
- git config --global user.email "[adresse email]"
- git diff : montre les modifications de fichier qui ne sont pas encore indexées
- git reset --hard[commit]: supprime tout l'historique et les modifications effectuées après le commit spécifié
- git fetch [nom-de-depot]: Récupère tout l'historique du dépôt nommé

Retour d’expérience sur les issues :
------------------------------------
- Une bonne issue doit contenir :
  * Un titre clair décrivant le problème.
  * Le contexte (dans quel fichier, quelle partie du projet).
  * Les étapes pour reproduire le problème.
  * Le résultat observé et le résultat attendu.
  * Les références (hash du commit fautif, dernier commit fonctionnel).
- Une issue bien structurée facilite la communication et accélère la correction.

====================================================
Membre A : Guilavogui Siba
Membre B : Elvis
Session : Automne 2025
====================================================
