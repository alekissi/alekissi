https://www.atlassian.com/br/git/tutorials/saving-changes

Comandos b�sicos GIT

cria o branch

Pull Request (PR) valida��o das altera��es por terceiros

faz o merge do PR (Atualiza o main/master)

**************************

diretorio criado do git baixando para a maquina local

-C�pia o endereco SSH no git
-git clone endereco

inicio dos trabalhos

entrar no repositorio/diretorio do projeto

-cd nomeDoRepositorio

-git remote get-url origin (verifica a url de onde o projeto foi clonado)

para criar uma nova branc

git branch nomeNovaBranch

git branch (lista os branchs locais)
git branch -r (lista os branchs remotos)
git branch -a (lista os branchs remotos e locais)

para criar uma branch e j� entrar na nova branch

git checkout -b ?new-branch?

entrar em uma branch j� existente

git checkout nomeBranch

atualiza o projeto

git pull

git add nomeDoArquivo (Adiciona os novos arquivos ao ao vercionamento localmente)

git commit (salva as altera��es no repositorio local)

git push (semelhante ao git commit, mas salva as altera��es no repositorio/diretorio remoto)
git push origin nomeBranch(master/main)

**********************************************

iniciando um novo repositorio local

entra na pasta do projeto e abre o git here

-git init

(cria os arquivos que desejar)

git status (verifica a branch, os commits e o status dos arquivos (work directory(n�o vercionado), stage index(vercionado local), repositorio remoto))

git add nomeDoArquivo (adiciona os arquivo no vercionamento local)

git commit -m "observa��o da altera��o" (envia as altera��es para o repositorio remoto)

para consolidar as altera��o no diretorio remoto

vai para o diretorio principal

git checkout master/main

git merge nomeBranch

RESTAURANDO PARA UM STATUS ANTERIOR

git log (exibe os commits )

git revert identificador (identificador recuperado com o git log mantendo o hist�rico) 
aceita as altera��es necessarias

git commit -am "revert para o commit ********"

-----------

git reset identificador (volta o repositorio(work directory) para esse identificador e limpa o historico a partir do identificador informado)








