#Github

** Aula básica de Git and Github

* Saiba mais vendo meu github profile [Matheusbp](https://github.com/Matheusbp)

1. Primeiro modifica os arquivos:

start notepad++
start notepad++ <filename>
alias np='start notepad++'
np <filename>

2. ai usa np Readme.md for example

3. após isso é preciso dar

git add Readme.md

4. e então commit com mensagem (-m)

git commit -m "Add Readme.md" 

commit -am é adicionar a modificação commitando direto sem adicionar pelo que entendi git commit -am "edit readme again com lixo"

ai eu dou commit -am é adicionar a modificação commitando direto sem adicionar pelo que entendi

""""""""""""""""""""""""""""""""""""
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Readme.md

no changes added to commit (use "git add" and/or "git commit -a")
""""""""""""""""""""""""""""""""""""
#isso mesmo o -m é mensagem e o -a é paara mandar direto sem precisar add

git commit -am "edit readme again com lixo"


Vale lembrar que o curso que fiz de R, é preciso então ver os files que estão staged,
aí então dou commit que faz com que eu atualize a versão localmente e então eu dou push que envia para o github
