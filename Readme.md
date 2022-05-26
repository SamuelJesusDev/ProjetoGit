Usando o Git<br>
(Git) - um sistema versionamento de arquivo
<br>
(banch) - ramificaçoes no codigo <br>
(Merge) - junção da banch alternativa com a banch principal<br>
(remote) - conexão do nosso repositorio local com o github<br>
(push) - colocar o commit que foi feito na maquina pro remote <br>
(pull) - é ao contrario do push vc puxa o que que esta no repositorio do github pra sua maquina<br>
---------------------------------------------<br>
1- git init- iniciar um repositorio vazio<br>
2- git add . ou (nome do arquivo)- para adicionar os projetos no stade.<br>
3- git status- ver os arquivos que estão no stade.<br>
4- git commit -m "primeiro" - comitar - postei as alterações <br>
5- git branch -M "main" ou ("master")<br>
<br>
----------------------remote------------------<br>
6- git remote add origin <link.git><br>
7- git push -u origin main ou (master)<br>
<br>
---------baixar para sua marquina-------------<br>
8- git clone <link.git><br>
<br>
---------baixar atualização do github--------- <br>
9- git pull<br>
<br>
--------------------versionamento-------------<br>
-git add .<br>
-git status
-git commit -m "nome projeto"<br>
-git push origin main (sem -u)<br>
<br>
------------criando nova branch---------------<br>
checout ja estou saindo da branch anterior e entrando na nova<br>
-git checkout -b "novo-botao"<br>
-git checout -d  novo-botao - remover branch <br>
------novo commit-----------------------------<br>
-git add .<br>
-git status<br>
-git commit -m "nome projeto"<br>
-git push origin novo-botao<br>
<br>
------mudar de branch-----------------------------<br>
-git checkout nome-branch<br>
<br>
-----juntar as branch--------------------------<br>
-git merge novo-botao<br>
<br>
-------- listar usuarios--------------------------<br>
-git config --list<br>
<br>
----------------------------------------------<br>
-git rm arquivo> -remover arquivo<br>
-git diff - mostra o que foi modificado<br>
-git log and git log --oneline - mostra todos os que commits q foram feitos desde o inicio<br>
-git commit -m "nome commit" --amend - emendar o commit <br>
-git reset --hard <nome commit> - remover commit anterior<br>