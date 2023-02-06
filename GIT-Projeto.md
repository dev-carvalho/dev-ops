# Projeto já existente no repositório
```bash
# download do repositório do GitHub para sua maquina
# Replace `owner/repo` with the owner and name of the repository to clone
git clone https://github.com/owner/repo.git

# navegue para o diretório `repo`
cd repo

# crie uma nova branch para armazenar qualquer nova mudança 
git branch my-branch

# troque para a sua branch (desenvolvimento)
git checkout my-branch

# make changes, for example, edit `file1.md` and `file2.md` using the text editor

# stage the changed files
git add file1.md file2.md

# take a snapshot of the staging area (anything that's been added)
git commit -m "my snapshot"

# push changes to github
git push --set-upstream origin my-branch
```
