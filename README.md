# Summary-Git-Github
This is a summary that I did about some instructions for Git and Github.
# Summary-Git-Github
This is a summary that I did about some instructions for Git and Github.
Termos e especificações em TI

GIT/GITHUB

Git – Aplicativo onde é gerado os arquivos, coordenar o trabalho de várias pessoas em um repositório compartilhado.

Github – plataforma que salva os arquivos/ pastas. serviço baseado em nuvem que hospeda um sistema de controle de versão (VCS) chamado Git.

Branch – ramificação que você faz no projeto. Tipo: você vai adicionando códigos com funcionalidades em momentos difrentes. Ex: já temos um planejamento das funcionalidades principais, porém com ramificações, podemos ir adicionando testes, funcionalidades. Que podem ser resgatadas numa linha do tempo.

Obs: você pode fazer esses branchs na linha principal do projeto ou em ramificações para que não afetem o planejamento das funcionalidades previamente programadas para se ter no projeto.

 

Commit – cada salvamento das adições feita. Salva/ é preciso salvar, publicar, pois, ele não salva automaticamente.

Merge – junção do Branch ramificadas com a Branch principal

Push – Empurrar, Utilizado para colocar o comit da máquina no remont (no github) você precisa publicar e o push faz isso, se não ele não saíra da sua máquina para a plataforma onde o projeto é gerado. Acho que é isso!!??

Pull – Puxa o que está no github para a sua máquina. Quando você está trabalhando com mais pessoas é preciso para entender também o que seus colegas fizeram.



Como usar o Git
Ela recomendou baixar o VS code que é um visualizador de código (facilita o manuseio dos códigos).

No VS code criamos uma folha para adicionar o código e colocamos como nome “Readme.md” o md = markdown é uma linguagem de marcação que utilizamos para escrever os Readme.

Readme = toda instrução, porém que não vai ficar dentro do código do projeto. 
 
Após instalado iremos ver a versão (para ter certeza de que ele instalou direitinho)

Comando: 
Git --version 

É mostrado abaixo as informações da versão instalada.

Atalho
Ctrl+S = Salva o arquivo

Comando 
Git init = inicia um repositório vazio

Iniciamos, porém para começarmos a editar precisamos fazer o primeiro commit 

Comando 
Git Add = Comando que chama a função que queremos para ser acionado no momento certo. Algo assim...
•	Ao inserir esse comando nós precisamos dizer qual arquivos que nós queremos que seja inserido, nesse caso é o Readme.md 

Git Status = mostra status do projeto. Últimas modificações etc.

Git commit -m = Salvamento do projeto. Podemos colocar umas aspas e colocar uma mensagem no commit, como “primeiro commit” Enter. 
•	Pronto o arquivo é salvo na rede.


Criando o repositório no Github

1.	Go in your profile on the Github
2.	After go for Repository
3.	New (in your right)
4.	Give a name to the Project 
5.	And put a description about what’s that.
6.	below we have the option “create the repositor”.
7.	The site pull the commit made in your computer 
8.	We used the file “Redme” like example. And it appear on the site with your code

Ok on the site (Github) appear the code. Now we need to do one more Thing for push to the site. 

1. We take the code that appear on site after we make our first commit In the initial part of the text above in 

HTTPS:.......................................


Criando conexão do repositório local com o Github

1.	We need create a new folder on computer and take you way above and create a gitbash here on that.

2. Now we open the git best 

Command

Git remote add origin. 

In front of the command, we place the code generated on the website.


Ex: Git remote add origin https://github.com/EricSantosOliveira/Projeto-Git.git

Now we just make the connection 
the system with platform, but don’t 
send anything. 

It's done, but it was necessary to put the folder on a one drive, as I tried to do this process before and there was a problem.


Shortcut

Insert or Crtl+Shift+V

Understanding every word of the command

1 - Git remote add origin.

Git = Function of the github: The system understands that you want put a command in the next line.
remote = Combining a local repository with the cloud.
add = For addition the remote to git
origin = the name that we gave on the file on the GitHub and you link.


Remember that you still do not push anything on the system (Github) we need to do one more thing to stabilize the connection. Because the last command we made the connection with the system but do not finish the command for push information that we will work on the files.


Criando PUSH
Command 

2 - Git push -U origin main 

Origin = the name that we gave on the file on the GitHub and you link.
Main = The principal file we will work.
Enter

3 – Opened automatic one box of Github for Log in.

But it’s if you don’t access for anyone, if you do, it opens without of necessary make log in and anyone can add files in your repository.

 
Return for the site (Github) in project click on the we work. You will see one different  in you design.

 
Now your project is linked both in the system and in your location. You can see it on Github.

Finish.

4. Now we will use the VS code to make our project.

went wrong.
1. Open the file on the folder.

Shortcut
Ctrl+ - = - zoom
Ctrl+ + =+ zoom
Ctrl+ S = Save


Command Git best

Clear = clean the screen

Add = If we want to send all files of the project without put one by one we can put the command and put the “.” It’s mean that all files must be sends.

Git add . 

Command Git best

Now we find files of the committed on the machine, now we need to push it on the local after putting on the system (Github).

Git commit -m “criação do projeto” Enter

Now we need to put the commit on the system using the command push. This time does not need put the “-U”.

Git push origin main

Branch
We have the main work. Then we need to make one branch first for the system to understand that work is not on the main.

She figures out other functions on the main project for we understand how make a Branch.

Command Git best

Git checkout -b “novo-botao”
Pay attention to the writing.

It has done. Now all the things that we do are going to Branch and don’t to main project.

Checkout option: It serves to out of main branch for others.


Note that if you look on the main page of Git hub don’t appear our Branch developed. You need to open the Branch button. 

 

 
Appear on the way.
 


Change Which Branch you are working.

Command “Checkout”
1-	See which branch we are setting. 
1.1	Git bash 
2.	Look at the line above the one you're typing.
-	Ex: (novo-botao) are in blue.
 

•	Change Which Branch you are working.
1.	Git bash
2.	Put the command. 
Git checkout main
3.	Enter
It’s done.
4.	Now the branch exchanges for Main. Look at the Git bash.

 

 

Merge Join the elements (Main Branch with Branch secondary) 

1.	We need to exchange for the main branch.
-	Git checkout main
2.	Command Merge
Git merge novo-botao
3.	It’s done. The function has been added on the main branch.
4.	Now we need to push it on the platform.
5.	Command Push
Git push origin main

Taking of repository and putting in your local repository 

Ex: take the project of my cousin to my computer
1.	Enter in your profile on GITHUB.
2.	Enter your repositories.
 

3.	Click in some repository that is available for your.
4.	Click in “Code”.
5.	Him available a link that you will use for taking the repository for your computer.
6.	Copy
-	She available one link for teste.
7.	Create one folder for this project.
8.	With the folder opened click with right button and select “open with Git bash”.
9.	Command 
Git clone (link.git)
Git clone https://github.com/rafaballerini/GitTutorial.git
10.	Enter
11.	It’s done. If you look in, in his folder, another one with data appeared downloaded.
 
12.	Open with Visual code to see the Script that Rafaella made of this video.


Updating The files on the Branch in your local repository

1.	Git bash
2.	You need to enter the project.
3.	Command
cd GitTutorial
-	It’s the name of her project.
-	Cd is a function on Github for entering any folder.
-	Opened the project.
4.	Updating now
5.	Command 
Git pull
6.	If don’t there Changed close and open VS code.
7.	The change happened.


Put a repository of other people in you profile of GitHub.

Even if we are taking a link of other profile, we don’t have saved in our profile on the site. Only on the computer.
For to save on the site make it.
1.	Click on this repository where you have the link on Github.
2.	Above/ right you have some option.
 
3.	Click in Fork.
-	Open one box
4.	Click on create Fork.
5.	It’s been added to your profile.
 



Pull request: Send solicitation of change on this project.

You take one project of another guy, you made some changes, and you wish on the project. How you haven’t the access you send one solicitation for the responsible If he wants to do this change.

Ex: you added one button on this project. He didn’t solicit this process, but you saw an opportunity for improvement. But you don’t make part of the team, you need to request this change on the main project.

1.	She made one commentary in one project of your friend by Github. 
2.	Made one commit too below of the script on Github.
3.	You can see it on the screen. 
  
4.	Now going to the contribute.
-	One commentary it’s been. But it don’t enter the script, you need make a solicitation for the responsible.
5.	Contribute >> Open pull request.
6.	You need to fill some parts of this Pull request on page of GitHub.
 
7.	Create pull request.

Note: If appear that you can’t make a Pull is because you change the same line of the responsible. On the main Branch can be a conflict.

Note: Is interesting you communicate the responsible what you do on this project and why you make these changes. Because he can do some tests on these changes.


Accepting a Pull request: 
1.	Profile of GitHub.
2.	Repositories
3.	By clicking on the repository, you can see those solicitations that who make it.
 
-	For me don’t appear still because a haven’t any pull solicitation.
4.	Click on it.
5.	You can see the people that made some changes in your project.  And the descriptions what was make.
 


6.	If you like it just below and click on Merge pull request.

 

