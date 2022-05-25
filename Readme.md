Usando o Git
(Git) - um sistema versionamento de arquivo

(banch) - ramificaçoes no codigo
(Merge) - junção da banch alternativa com a banch principal
(remote) - conexão do nosso repositorio local com o github
(push) - colocar o commit que foi feito na maquina pro remote 
(pull) - é ao contrario do push vc puxa o que que esta no repositorio do github pra sua maquina
---------------------------------------------
1- git init- iniciar um repositorio vazio
2- git add . ou (nome do arquivo)- para adicionar os projetos no stade.
3- git status- ver os arquivos que estão no stade.
4- git commit -m "primeiro" - comitar - postei as alterações 
5- git branch -M "main" ou ("master")

----------------------remote------------------
6- git remote add origin <link.git>
7- git push -u origin main ou (master)

---------baixar para sua marquina-------------
8- git clone <link.git>

---------baixar atualização do github--------- 
9- git pull

--------------------versionamento-------------
-git add .
-git status
-git commit -m "nome projeto"
-git push origin main (sem -u)

------------criando nova branch---------------
checout ja estou saindo da branch anterior e entrando na nova
-git checkout -b "novo-botao"
------novo commit-----------------------------
-git add .
-git status
-git commit -m "nome projeto"
-git push origin novo-botao

------mudar branch-----------------------------
-git checkout nome-branch

-----juntar as branch--------------------------
-git merge novo-botao

