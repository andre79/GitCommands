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
    <b>[ADD] Adicionado.</b>
    <b>[REN] Renomeado.</b>
    <b>[UPD] Atualizado.</b>
    <b>[FIX] Corrigido.</b>
    
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
    Repositório de GitIgnore: https://github.com/github/gitignore

# Clonando Projetos/Arquivos mantendo históriocos
    - git clone <nome_pasta_origin>/ <nome_pasta_destino>
    - git clone https://github.com/andre79/GitCommands.git

# GitHub - Ao criar um <b>GitHub</b>.
    - Também demos acesso ao (Público e Privado), podemos escolher um .gitIgnore nos campos de criação do repositório. A Licença do MIT é a mais comum, caso voc queira deixar publico o código.

# Funcionalidades do Repositório
    - Edição
    - Incluisão de arquivo (commit e  pull e push)
    - git pull origin main

# Comandos <b>Stars</b>, <b>Fork</b>, <b>Pull</b> e Request.
    <b>Stars:</b> São itens para favoritas projetos e acompanhá-los.
    <b>Watch:</b> Serve para vocês ser notificado dos andamento de todos os projeto que você deseja acompanhar.
    <b>Fork:</b> Faz um clone para o seu perfil, agora você pode contribuir com o código.
    1. "<b>Forka</b>" o proketo para o seu perfil.
    2. Clona o projeto na sua maquina.
    3. Faz as alterações, "<b>commita</b>" e "<b>pusha</b>".
    4. Criando um "pull request". Verifica se o projeto origin e o projeto destino não possuem conflitos
    4.1 Verifica se o ststus no github está "Able to Merge".
    4.2 Cria o título do pull request, coloca o comentário no corpo da descrição é clica em Create pull request.
    4.3 Você pode criar um pull request, ou um rascunho.
    5. No lado da pessoa. que Recebe o Pull Request. 
    5.1 Pode enviar mensagem quem solicitou enviou pull request. Negociar e refletir sobre as mudançae e incluir no projeto principal.

# 