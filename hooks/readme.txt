Pour utiliser le hook pre-commit :

1. Copier le fichier hooks/pre-commit vers .git/hooks/pre-commit
2. Le rendre exécutable : chmod +x .git/hooks/pre-commit
3. À chaque commit, il demandera si vous voulez vérifier le commit.
4. Si oui (y), il crée suivi/commitInfo.txt avec la date et l'ajoute au commit.