
# Definition

## 1. Dépôt (Repository)
Espace où tout le code et les fichiers du projet sont stockés et versionnés.  
**Exemple :** dépôt `football-analysis` sur GitHub pour tout le projet d’analyse des trois championnats.

## 2. Commit
Enregistrement d’un état des fichiers avec un message décrivant la modification.  
**Exemple :** commit "Ajouter fichier premier_league_login.php" pour suivre les changements du module EPL.

## 3. Branche (Branch)
Version parallèle du projet pour travailler sans affecter la branche principale (`main`).  
**Exemple :** `feature/premier-league-analysis` utilisée pour développer l’analyse de la Premier League.

## 4. Merge
Fusion d’une branche dans une autre après révision.  
**Exemple :** fusion de `feature/premier-league-analysis` dans `main` après validation par un collègue.

## 5. Pull Request (PR)
Demande d’intégrer les changements d’une branche dans une autre, souvent avec révision.  
**Exemple :** PR pour intégrer la branche `feature/liga-analysis` dans `main` après que le module Liga est prêt.

## 6. README.md
Fichier principal expliquant le projet, comment l’installer et l’utiliser.  
**Exemple :** README.md décrit la structure du dépôt et la manière de lancer les scripts d’analyse EPL, Liga et Serie A.

## 7. gitignore
Fichier indiquant à Git quels fichiers ou dossiers ne doivent pas être suivis.  
**Exemple :** `.gitignore` inclut `config/credentials_template.env` pour ne pas exposer les clés API.

## 8. Repository visibility (Public / Private)
Indique si le dépôt est visible par tous (public) ou seulement par les collaborateurs autorisés (private).  
**Exemple :** dépôt public pour permettre au professeur de vérifier le projet.

## 9. PAT (Personal Access Token)
Clé de sécurité GitHub permettant d’accéder au dépôt via Git sans utiliser le mot de passe.  
**Exemple :** PAT utilisé pour pousser des modifications depuis `feature/serie-a-analysis` vers GitHub.

## 10. Protection de branche (Branch Protection)
Règles appliquées sur une branche pour contrôler les modifications : exiger des PR, des validations ou empêcher les push directs.  
**Exemple :** protection activée sur `main` pour que toutes les modifications passent par une PR et soient validées avant fusion.
