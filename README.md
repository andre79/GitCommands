# GitCommands

# GitCommands

# Iniciar Repositório
    - git init

# Status do Arquivo
    - git status

# Inclusão de Arquivo
    - git add <file_name> (arquivo específico)
    - git add --all
    - git add -A
    - git add .

# Comitando Arquivos
    Descrições no comite.
    [ADD] Adicionado.
    [REN] Renomeado.
    [UPD] Atualizado.
    [FIX] Corrigido.
    
    - git commit -m "[XXX] Texto da atividade"

# Working Directory
    Untracked --> (git add) --> Staged --> (git commit).

# Working Directory x Commited
    Diferenças na área de preparação
    - git diff
    - git diff --cached
    - git diff --staged

# Visualizando Histórico do GIT LOG
    - git log
    - git log --oneline
    - log log -n
    - git log -p
    - git log --stat
    - git log --shortstat
    - git log --name-only
    - git log --name-status
    - git log --abbrev-commit
    - git log --relative-date
    - git log --graph

# Formato --pretty=format no Log    
    - git log --pretty=format:"%h - %p: Feito por %an"
    - git log --pretty=format:"%h: %ar - (%ae) %an"
    - git log --pretty=format:"%h %s"

# Listando/Mudando de Branch
    - git branch
    - git checkout <sha> (detached head)| <branch>

# Desfazendo Alterações Específicas
    - git checkout <nome do arquivo> (Irá voltar para versão comitada)
    - git reset --hard
    - git reset (lista arquivos que serão resetados)
    * Não funciona em arquivos não ratreados

    - git clean -f (remove arquivos não rastreados)

# Criando um .gitignore
    - .<extensao>
    - .<tipo>
    - *.bmp
    - procurar o arquivo .gitignore no GitHub (modelo projeto).