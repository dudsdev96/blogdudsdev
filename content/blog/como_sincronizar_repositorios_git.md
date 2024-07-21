+++
title = 'Porque sincronizar os repositórios GIT no GitHub'
date = 2024-07-20T16:32:03-03:00
draft = false
+++


### Diferença entre os repositórios
O repositório remoto é a pasta com os arquivos do projeto que estão fisicamente em seu computador (local).

Então você vai encontrar na sua frente **2 cenários:**

* Você tem arquivos que estão somente em seu computador (localmente), ou:
* Você criou o repositório pelo site do GitHub mas ele está vazio, então 
você quer por arquivos nele para que possa controlar as versões do seu projeto. 

**Porém existe um problema!**

Ou os arquivos vão estar localmente no seu computador somente, ou vão estar somente 
no servidor remoto do GitHub

### Como resolver este problema? Simples! Sincronizando os dois!

Crie o repositório local no seu computador primeiro e coloque os arquivos que desejar dentro dele.

Primeiro Inicie o seu repositório local, abra o CMD em modo administrador e através do comando **cd** 
você vai acessar a sua pasta do repositório local. Então digite: cd caminho-da-pasta no CMD e aperte Enter

Agora você está dentro da pasta do projeto e vai precisar iniciá-lo, digite o comando:

**git init**

Neste momento você já pode utilizar outros comandos git dentro do seu repositório local.

* Muita atenção agora, estes comandos abaixo que vão Sincronizar os dois repositórios (local e remoto).
 Digite estes comandos no terminal para que o repositório local (pasta que onde você está acessado dentro do CMD):

git remote add origin https://github.com/seu-usuario-github/nome-do-repositório.git
git branch -M main
git push -u origin main

O comando git branch informa que o galho (branch) que será usado agora será o principal/padrão (main).
E o git push está informando que os arquivos enviados através do comando push irão pelo galho (branch) Main.

Agora quando você fizer um commit+ push (empacotar e enviar) seus arquivos do repositório local para o 
repositório remoto não vai dar erro pois estarão sincronizados.