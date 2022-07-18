# Comandos Básicos git
### Git Config
define o nome de usuário e email
 - git config --global user.name "nickname"
 - git config --global user.email usuário@example.com
 
##### desfazendo configurações de usuário

 - git config --global --unset user.name "nickname"
 - git config --global --unset user.email "email"
 
### Git Init
inicializa um projeto

### git Clone
Clona um repositório com git clone [url]. Por exemplo, caso você queria clonar a biblioteca Git do Ruby chamada Grit, você pode fazê-lo da seguinte forma:
 - git clone git://github.com/schacon/grit.git
 
### Git Add
adiciona atualizações

 - git add "arquivo"
 - git add * (insere todos os arquivos unstaged)
 
### Git Status
verifica o status dos arquivos

### Git Commit

adiciona um novo commit junto com uma mensagem explicando as alterações
 
  - git commit -m "mensagem"
  
### Git Pull

Incorpora as alterações de um repositório remoto no branch atual.
 - git pull origin develop
 
### git push

envia pro reposiório remoto

 - git push origin develop
