# Guia para a Flash Class

## Objetivos

Transmissão de conceitos e não própriamente que saibam os comandos

* verificar se todos têm Git instalado


### Repositórios locais vs Remote

* Pedir que criem uma diretoria com dois ou trẽs ficheiros


      git init

* verificar os ficheiros presentes na pasta

      ls -la

* a diretoria ```.git``` - a "base de dados"

* verificar o estado

      git status

      ...

      git add file.xyz

      git status


* explicar o staging ...
  * alterar um ficheiro
  * gravar

        git checkout file.xyz

* explicar diferença entre ```staging``` e ```commit```
  * voltar a alterar o ficheiro

        git add file.xyz
        git commit -m "mensagem"
        git log

* explicar o que é um branch
  * criar um branch

        git checkout -b new-branch

  * alterar um ficheiro

        git add file.xyz
        git status
        git commit -m "new stufff!!"

* conceito de merge
  * regressar ao branch master

        git checkout master

  * demonstrar como os ficheiros voltaram ao original

        git merge new-branch

  * ver autoria de uma alteração

        git blame
