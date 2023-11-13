# GIT
## Configuração de informações do usuário
```
git config --global user.name username
git config --global user.email email
git config --global init.defaultBranch main
```

## Comandos git
>git init
  - Inicia o repositório git
> git clone
  - Clona um repositório git para um repositório local
> git commit
  -  Grava as alterações no repositório
  -  -m --> Parametro para definir a msg do commit
> git pull
  - "puxa" as alterações de um repositório remoto para um local e mescla
> git push
  - "empurra" as alterações do repositório local para o remoto
>git add ?file
  - Adiciona o(s) arquivo(s)/conteudo que deseja adicionar no commit
>git reset
  - Desfaz o último commit
>git remote add origin
  - Direcionar para o diretorio remoto
>git checkout -b branch
  - Troca a branch que estamos apontando
>git merge branch
  - Mescla a branch passada com a principal
>git branch -d branch
  - Esclui a branch passada
>git fetch branch1 branch2
  - Verifica as diferenças entre as branchs sem mesclá-las
>git diff branch1 branch2
  - Mostra as diferenças das branchs
