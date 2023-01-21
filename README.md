# Hello git!

```git
git config --global user.name "liamperfil"
git config --global user.email "jeancarlos.ramos@live.com"
```

```git
git init
git status
```

```git
git add index.html
git add -all
```

```git
git branch -M main
```

```git
git stage -A
git commit -m "message"
git commit -a -m "message"
```

```git
git remote add origin https://github.com/liamperfil/deletar.git
git push --set-upstream origin master
```

```git
git log --oneline
```

reset é o comando para mover o repositório de volta para um commit anterior, 
descartando qualquer log depois disso.
```git
git reset e56ba1f
```

revert é o comando que usamos quando queremos pegar um commit anterior 
e adicioná-lo como um novo commit, mantendo o log intacto.
```git
git reset e56ba1f
```
