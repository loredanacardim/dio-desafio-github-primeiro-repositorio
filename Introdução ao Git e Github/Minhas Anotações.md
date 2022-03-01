# Minhas Anotações :woman_student:

#### GIT

* CLS -> Limpa

* TAB -> Completa a frase

* mkdir -> cria pasta

* cd .. -> Volta para pasta anterior

* del -> não deleta repositório, só arquivos

* rmdir ... /S /Q -> remove todo repositório e os arquivos.

#### GitHub

* Chave SSH -> settings -> SSH and GPG keys

* Token -> Developer settings -> Personal access token

* Iniciar um repositório -> git init

* Mover arquvios -> git add

* Capturar o estado de um projeto naquele momento -> git commit

  ##### Empurrar o repositório da máquina para o github

  *  git remove add origin (colocar o link que fica no github quando cria um repositório)
  * git push origin master (vai pedir a autenticação)

  ##### Resolvendo Conflitos

  Quando fizer uma alteração em um arquivo que já está no github é preciso colocar novamente:

  * git pull origin master (corrigir o que precisa)
  * git add *
  * git commit -m "Resolve conflitos"
  * git push origin master

