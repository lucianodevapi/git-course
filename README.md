# Primeiro curso de git que está valendo a pena.
## Tópico Um

## Commands Config

### git config --global user.name ""
### git config --global user.email ""

## Commands 

### config - Altera as configurações na máquina
### init - Inicializa o projeto / repositório
### branch - Informações sobre a branch
### checkout - Navega nas branchs
### status - Checa o que há de novo / mudar
### clone - Baixa um repositório remoto para um repositório local
### add - Rastrear e adicionar arquivos e mudanças em relação ao que já hávia registrado antes  (stage)
### commit - Salva alterações em arquivos no repositório local
### push - Faz upload a partir do repositório local enviando ao repositório remoto
### pull - Faz o download de alterações a partir do repositório remoto até o repositório local
### merge - Mesclar distintos em um único
### diff - Visualiza diferença entre códigos-fonte
### log - Visualiza o histórico de publicações
### log --pretty=oneline - Log em uma linha
### stash - Rever alterações recentes momentaneamente e armazena tais alterações em memória para recuperação das alterações posteriormente
### restore --staged README.md - Retira do commit
### git branch -M main - Altera a branch
### git remote add origin https://github.com/lucianodevapi/git-course.git - Configura o repositório local com o repositório remoto
### git push -u origin main - Efetua o commit remoto
### git push --set-upstream origin main - Efetua o commit remoto
### git blame README.md - Exibe informações sobre as ultimas alterações no arquivo.

### git stash - Guarda as alterações
### git stash pop -  Retorna as alterações
### git push -d origin outra-feture - Exclui uma branch

# Git Revert
### git revert - Cria um novo commit sem as alterações
### git revert HEAD --no-edit - Desfaz o commit da ultima alteração

# Git Reset
### git reset - Exclui o comiit


# Extentions
## - git grapth
## - git history

# branchs

### git checkout -b "nova -feture" - Cria uma nova branch
* criar um novo arquivo e o adicione na nova branch.
* commit o novo arquivo

# Resolver conflitos na prática

### git branch main - Altera para a branch principal
### git merge novo-fix - Efetua o merge da branch novo-fix com a branch principal
### git push -d origin novo-fix - Deleta uma branch








