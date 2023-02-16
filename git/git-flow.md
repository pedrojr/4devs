## GitFlow

Branch develop
```
git flow init
ou
git checkout -b develop
```

Criando uma feature
```
git flow feature start name-feature
ou
git checkout develop
git checkout -b name-feature
```

Finalizando uma feature
```
git flow feature finish name-feature
ou
git checkout develop
git merge name-feature
```

Criando uma hotfix
```
git flow hotfix start name-hotfix
ou
git checkout master
git checkout -b name-hotfix
```

Finalizando uma hotfix
```
git flow hotfix finish name-hotfix
ou
git checkout master
git merge name-hotfix
git checkout develop
git merge name-hotfix
git tag name-hotfix
```

Criando uma release
```
git flow release start 1.0.0
ou
git checkout develop
git checkout -b release/1.0.0
```

Finalizando uma release
```
git flow release finish 1.0.0
ou
git checkout master
git merge release/1.0.0
git checkout develop
git merge release/1.0.0
git tag 1.0.0
```
