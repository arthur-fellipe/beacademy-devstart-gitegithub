# Lista de Comandos Git

Esta é uma lista com alguns do principais comandos utilizáveis no Git, cuja criação foi proposta durante o programa DevStart Paylivre.


## Comandos de identificação do usuário

- git config --global user.name "*nome*" --> Inclui nome de usuário

- git config --global user.email "*email*" --> Inclui email de usuário

## Comandos iniciais para registro de alterações do projeto

- git init --> Inicia repositório vazio

- git status --> Mostra o status do git

- git add *arquivo* --> Move uma alteração de untracked para staged, pronta para ser registrada em um commit

- git add . --> Move todas as alterações de untracked para staged, prontas para para serem registradas em um commit

- git rm --cached *arquivo* --> Remove uma alteração de staged para untracked

- git commit -m "*comentário*" --> Registra a alteração na forma de commit

- git log --> Mostra informações sobre os commits criados

## Comandos de versionamento do projeto

- git branch --> Mostra as versões existentes

- git branch *nome da branch* --> Cria uma versão

- git checkout *nome da branch* --> Navega entre versões

- git checkout -b *nome da branch* --> Cria uma versão e navega para ela

- git branch -d *nome da branch* --> Deleta uma versão

- git merge *nome da branch a ser importada* --> Unifica as versões

## Comandos de interação com repositório remoto

- git clone *chave SSH* --> Clona um repositório remoto para a sua máquina

- git remote -v --> Mostra repositório de origem

- git push --> Envia as alterações para o repositório remoto

- git push -u *repositório remoto* *branch* --> Seleciona o repositório remoto indicado como principal

- git pull --> Atualiza a versão local de um repositório a partir de uma versão remota

## Comandos para salvar sem registro em commit

- git stash –include-untracked --> Salva alterações sem commit

- git stash pop --> Restaura alterações salvas

- git stash pop stash@{posição na lista} --> Aplica stash específico

- git stash list --> Lista stashes

## Comandos para reversão de registros

- git revert *4 primeiros dígitos do hash do commit* --> Inverte as mudanças de um commit e gera um novo commit com o conteúdo invertido

- git reset --> Reseta as alterações registradas por commit

### Autor

- [@arthur-fellipe](https://www.github.com/arthur-fellipe)
