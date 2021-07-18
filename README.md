# **Comandos Git**

***[Comandos Git - Aprenda Git do básico ao avançado]***

***[(https://comandosgit.github.io/)]***

**1 -** Após a instalação, definir nome de usuário e endereço de e-mail. Importante, pois todos os commits no **Git** utilizaram essas informações, e estará, sem possibilidades de mudanças, unidos aos commits que nos utilizarmos.

***git config --global user.name "Seu nome"***

***git config --global user.email seuemail@email.com***

<hr>
**2 -** Inicializando um repositório em um diretório existente.

***git init***

<hr>

**3 -** Monitorando um novo arquivo

**git add nome_do_arquivo.extensao**

<hr>

**4 - ** Principal ferramenta utilizada para determinar quais arquivos estão em quais estados.

**git status**

<hr>

**5 -** Armazena o conteúdo atual do índice em um novo commit, juntamente com uma mensagem de registro do usuário que descreve as mudanças.

__git commit -m "Mensagem"__



<hr>

*Meu primeiro sistema no GIT*
*Segunda alteração no README*
*Alteração feita no branch master*

 Você quer saber exatamente o que você alterou, não apenas quais arquivos foram alterados?
*GIT DIFF*
*GIT DIFF --CACHED*

*Redefinir HEAD atual para um estado específico*
**git reset <--soft><--head><--mixed><HEAD~1>** 

Desfazendo alterações em um arquivo específico.

*GIT CHECKOUT HEAD -- nome_arquivo.extensao*

*Criando branch*
**git branch nome_branch**

*Listando branch**
**git branch --list**

*Mudar de branch*
**git checkout nome_branch**

*Deletar branch*
**git branch -D nome_branch**

































































