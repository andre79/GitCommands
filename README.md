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