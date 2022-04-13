# Git

Inicializa o repositório
```sh
git init
```

Visualiza o status dos arquivos
```sh
git status
```

Adiciona o arquivo
```sh
git add <arquivo>
```

Adiciona todos os arquivos
```sh
git add .
```

Remove um arquivo
```sh
git rm <arquivo>
```

Commita todos os arquivos
```sh
git commit -m "Primeiro commit"
```

Commita apenas um arquivo
```sh
git commit <arquivo> -m "Commit de um arquivo"
```

Commita vários arquivos
```sh
git commit <arquivo> -a -m "Commit de vários arquivos"
```

Cria uma branch
```sh
git branch -M <nome>
```

Adiciona a origem (passo de sincronização)
```sh
git remote add origin git@github.com:<usuário>/<repositório>.git
```

Envia as alterações para o repositório remoto
```sh
git push
```

Envia as alterações para a main do repositório remoto
```sh
git push -u origin main
```

Recebe as alterações do repositório remoto para o local
```sh
git pull
```

Clona um repositório remoto para o local
```sh
git clone https://github.com/<usuário>/<repositório>.git
```

Acessar log de modificações
```sh
git log
```

Renomear um arquivo
```sh
git mv <arquivo> <novo arquivo>
```

Desfaz as alterações em um arquivo
```sh
git checkout <arquivo>
```

Resetar as mudanaças feitas
```sh
git reset --hard origin/main
```

Listar todas as branches
```sh
git branch
```

Cria uma nova branch
```sh
git branch <nome>
```

Remove uma branch
```sh
git branch -d <nome>
```

Muda de branch
```sh
git checkout <nome>
```

Cria uma nova branch e muda pra ela
```sh
git checkout -b <nome>
```

Une a branch atual à outra
```sh
git merge -b <nome>
```

Descarta as alterações e salva o código em outro lugar
```sh
git stash
```

Lista as stashes do Git
```sh
git stash list
```

Recupera as alterações
```sh
git stash apply <id>
```

Mostra as alterações da stash selecionada
```sh
git stash show -p <id>
```

Remove todas staches de uma branch

```sh
git stach clear
```

Remove uma stash específica
```sh
git stach drop <id>
```

Cria uma tag em uma branch
```sh
git tag -a <nome> -m "<msg>"
```

Muda de tag
```sh
git checkout <nome>
```

Envia uma tag para o repositório remoto
```sh
git push origin <nome>
```

Envia todas as tags para o repositório remoto
```sh
git push origin --tags
```

Mapeia todas as branches remotas para o local
```sh
git fetch
```

Adicionar ou remover o repositório local para um remoto
```sh
git remote / git remote rm origin / git remote add origin <link>
```

Verifica os submódulos
```sh
git submodule
```

Adiciona uma dependência no projeto atual
```sh
git submodule add <repo>
```

Atualiza o submódulo
```sh
git push --recurse-submodules=on-demand
```

Exibe informações da branch/tag
```sh
git show / git show <tag>
```

Exibe as diferenças entre branches / arquivos
```sh
git diff / git diff <arquivo 1> <arquivo 2>
```

Exibe log resumido do projeto
```sh
git shortlog
```

Limpa arquivos que não estão sendo trackeados
```sh
git clean
```

Remove arquivos desnecessários e otimiza o repositório
```sh
git gc
```

Verifica a integridade dos arquivos e sua conectividade
```sh
git fsck
```

Mapeia todos seus passos no repositório (espiração padrão de 30 dias)
```sh
git reflog
```

Tranforma o repositório em um arquivo compactado (backup rápido)
```sh
git archive --format zip --output master_files.zip
```

Faz um rebase doss commits feitos em outra branch (private branch)
```sh
git rebase <branch 1> <branch 2> -i
```
