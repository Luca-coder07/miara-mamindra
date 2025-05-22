# Miara-mamindra 🇲🇬

Ho fanampiana ireo rehetra izay vao hi-contribuer amin'ny projet OpenSource. 📖

Rehefa hi-contribuer amin'ny projet iray ianao dia :

### 1 - Manaova fork an'ilay projet.
Mandehana ao amin'ny repository anao dia ho hitanao ao ilay projet nataonao fork.

### 2 - Cloneo ilay projet no-forkenao ao amin'ny repository anao
```
$ git clone <ilay_url_ao_amin_repo_anao>
```

### 3 - Midira ao amin'ilay projet en local anao rehefa vao-clone ilay izy.
```
$ cd <ilay_repo>
```

### 4 - Apetraho ao amin'ilay repository local anao ilay **url** an'ilay projet source mba ho à jour foana ny local anao
```
$ git remote add upstream <ilay_url_original_an_ilay_projet_noforkena>
```

### 5 - Raiso ny modification rehetra avy any amin'ny upstream
```
$ git fetch upstream
```

### 6 - Mergeo ao amin'ilay master en local anao ilay upstream raha misy modification
```
$ git merge upstream/master
```

### 7 - Mi-creeva branche hafa raha hanampy zavatra na hanohy hiasa ao amin'ilay projet ianao
```
$ git checkout -b "brancheko_vaovao"
```

### 8 - Ataovy ny installation rehetra, rehefa misy tsy mety dia anontanio ny maintainer (tompony) an'ilay projet.
```
$ node, composer, ...
```

### 9 - Rehefa izay dia tohizanao ny zavatra ataonao ao amin'ny local anao , rehefa afa-po ianao ao amin'ny local ianao dia pushenao ny modification nataonao , alohan'ny hi-pushena anefa dia manaova fetch an'ilay upstream foana aloha ( satria mety ho betsaka ny contributeur ary misy mikitika foana ilay repository ).
```
$ git fetch upstream
```

### 10 - Raha nisy modification dia mergeo ao amin'ny master anao indray.
```
$ git merge upstream/brancheko_vaovao
```

### 11 - Rehefa izay dia hakaro amin'izay ilay modification anao.
```
$ git add <fichier_no_modifier_nao>
$ git commit -m "message commit anao"
$ git push -u origin <brancheko_vaovao>
```

### 12 - Vita izay dia manaova pull request avy amin'ilay branche no-creenao.

Misaotra anao namaky 😉


# Marcher Ensemble 🇫🇷

Aide pour tout ce qui veulent contribuer à des projets OpenSource 📖

Si tu veux contribuer à un projet :

### 1 - Fork le projet en question.
Verifie dans votre repository que le projet est bien présent.

### 2 - Clone le projet fork-er en local
```
$ git clone <repo_url>
```

### 3 - Après le clonage, entre dans le projet en local
```
$ cd <repo_name>
```

### 4 - Pose l'url du projet source dans votre repository local pour que votre local soit tenu à jour
```
$ git remote add upstream <url_du_projet_source>
```

### 5 - Prend le modification depuis upstream
```
$ git fetch upstream
```

### 6 - S'il existe des modifications, merge-le dans le master en local
```
$ git merge upstream/master
```

### 7 - Crée une nouvelle branche si tu veux ajouter ou continuer à travailler sur le projet
```
$ git checkout -b "new_branch"
``` 

### 8 - Installe toutes les dépendances du projet. S'il y a des problèmes, questionne le mainteneur du projet
```
$ node, composer, ...
```

### 9 - Après, continue ce que tu fait dans ton local. Si tu es satisfait, push tes modifications. Mais avant de pusher, fetch toujours le upstream ( car il est possible que d'autres contributeurs ont fait des modifications dans le projet ). 
```
$ git fetch upstream
```

### 10 - Si des modifications existent, merge encore une fois.
```
$ git merge upstream/new_branch_name
```

### 11 - Après, remonte tes modifications.
```
$ git add <fichier_modifier>
$ git commit -m "Message de ton commit"
$ git push -u origin <new_branch>
```

### 12 - Si tout est fini, fait des pull requests via le branche que t'a créé.

Merci de votre lecture. 😉
