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
