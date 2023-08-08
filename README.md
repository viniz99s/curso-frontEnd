# curso-frontEnd
### EBAC
# Git
## Conceitos
 - Histórico
 - Controle de Versão
 - Quem alterou
 - O que alterou
 - Quando alterou
 - Todos os arquivos
 - Evolução Continua

 Arquivo A | Versão 1
 Arquivo B | Versão 1

 ## Clonar Projeto
 git clone https://github.com/viniz99s/curso-frontEnd.git
 # Commits
 Informação de Alteração
 - após testar todo o projeto
 - git add *
 - git commit -m "mensagem"
 - git push (enviar alterações para o repositório)

 ## GitFlow
 Fluxo do Git

 ### Branchs
 Versões ramificadas/paralelas

 - main/master
 - develop
 - DOD (Definition of Done)
 - versionamento 0,0,0 = (versões, atualizações, bugs fixet)

git branch -b 'nome da branch' (cria uma brench)
git branch 'nome da branch' (muda para a branch)

 ### Merge
 Talvez necessitará de resolver conflitos manualmente
 - Mescla de versões

 git merge 'nome da branch que quer mesclar coma atual'

 ### Pull Requests
 Mescla de branchs no repositório
 Permite code review
 O repositório resolve os conflitos automaticamente

 ### Configura o GitFlow
 git flow init
 git flow feature start 'nome da feature'
