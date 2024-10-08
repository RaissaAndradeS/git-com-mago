##  <center> Git e GitHub </center>

O git é mais um software, como qualquer um outro que roda no seu computador, mas com foco em versionamento de arquivo de texto. <br>

O Git foi criado pelo mesmo desenvolvedor do Linux, Linus Torvalds. Como a proposta do Linux é permitir contribuições de pessoas de todo o mundo sem problemas de versão, o Git foi desenvolvido para distribuir o Linux de maneira mais consistente e estável. <br>

O Git é open-source e roda em qualquer sistema operacional. <br>

O git é como um checkpoint do estado do seu projeto. Pense como um jogo e tire uma foto de um momento do jogo e ai salva essa imagem, e quando a gente tira uma foto, temos o estado do jogo salvo, com o git é a mesma coisa. E ai chega um momento no jogo que você tem que tomar uma decisão, e a partir dessa decisão, você tem que seguir a história a partir dela. E o Git "salva" os checkpoints e podemos voltar e tomar outras decisões. <br>

## <center> Comandos Bash </center>

- **PWD** - Mostra onde você está.
- **LS** - Mostra o que você tem dentro do seu diretório.
- **CLEAR** - Limpa a tela.
- **CD** - Para mover. CD Area de trabalho (tab completa).

## <center> Versionamento </center>

Para versionar um arquivo: ```git init . ``` e ai vai ser uma pasta oculta e para visualizar, o comando é: ```ls -a```. <br>
Para visualizar o status do projeto, ```git status```. <br>
Para adicionar um arquivo é: ```git add nome do arquivo```. <br>
Para ver o histórico é: ```git log```. <br>
Para adicionar tudo ao mesmo tempo: ```git add .``` <br>
Para resetar é: ```git reset```. <br>
Para ver as versões é: ```git log```. <br>
Para retornar o pós commit é: ```git reser idCommit```. <br>    
Isso é um checkpoint, um ciclo de vida de um desenvolvimento. 

## <center> Branch </center>

A branch é uma ramificação do projeto, a branch principal que é a main ou a master e posso fazer ramificações para não mexer na branch principal. 

Comando de branch : ```git branch ```. <br>
Para mudar para uma outra/ nova branch é ```git checkout -b nome```. <br>

## <center> Merge </center>

Para fazer o Merge:
- um git checkout;
- um git branch;
- um git merge nova;

Para deletar a branch: git branch -D nome

*É uma boa prática deletar a branch após o merge.*
