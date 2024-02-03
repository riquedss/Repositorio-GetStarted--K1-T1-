# (K1-T1) Versionamento de Código

## Conceitos GIT
Software capaz de gerenciar versões de qualquer tipo de arquivo

Mais usando durante desenvolvimento de Software

### Tipos de controle de versão:
- Centralizado: Servidor contém todo o histórico.
- Distribuido: Servidores e clientes possuem o histórico.

### Comandos:
- git config --global user.name "Seu nome"
  - Cadastra o nome que será usado no uso do git.
- git config --global user.email "Seu email"
  - Cadastra o email que será usado no uso do git.
- git init
  - Cria um novo repositório git.
- git clone
  - Clona um repositório existente.
- git add <file>
  - Prepara um arquivo novo ou modificado para usar o commit.
- git add .
  - Prepara todos arquivos novo ou modificado para usar o commit.
- git pull
  - Busca as alterações no repositório configurado como remoto para o seu repositório local.
- git push
  - Envia as alterações do seu repositório local para o seu repostório configurado como remoto.
- git restore <file>
  - Retira o arquivo da área de preparação. (inverso do git add)
- git diff
  - Verifica as alterações realizadas nos arquivos do repositório local
- git commit -m "commit initial"
  - Commita os arquivos que estão na área de preparação.
- git log
  - Mostra os commits e as informações dos commits no servidor.
- git log -l 2
  - Mostra os commits e as informações dos commits no servidor, só que os dois últimos commits.
- git checkout <file>
  - Vai para última versão comitada do arquivo.
- git brach
  - Lista as branchs locais.
- git branch (nome_nova_branch)
  - Cria uma nova branch a partir da atual.
- git checkout (nome_branch)
  - Muda de branch.
- git checkout -b (nome_branch)
  - Cria branch e muda para ela automaticamente.
- git branch -D (nome_branch)
  - Apaga a branch.
- git branch -m (nome_branch_atual) (nome_branch_nova)
  - Altera nome da brach.
- git log (nome_branch)
  - Mostra os commits e as informações dos commits no servidor de uma branch qualquer.
- git revert (ids_commit)
  - Volta em um commit conservando os commits pós ele.
- git reset --hard (ids_commit)
  - Volta em um commit não conservando os commits pós ele, ou seja, apagando a linha do tempo dos commits.
