+++
title = 'Como instalar e configurar o seu projeto com HUGO Sites'
date = 2024-07-20T16:48:58-03:00
draft = false
+++

## Instalação

1.1 - Existem várias formas de instalar o Hugo em diversos sistemas operacionais, como: Windows, MAC e Linux, neste artigo estarei    explicando como instalar no Windows. A forma mais prática é através de um gerenciador de pacotes chamado Winget. 


1.2 - Aperte a tecla do Windows para abrir o Menu Iniciar e digita CMD, clique com o botão direito em cima dele e depois clique na opção: "Executar como Administrador". Note que abrirá o Prompt de Comando, uma tela preta. O caminho mostrado no Prompt de Comando está descrita a pasta System32, que é o que estamos buscando, isso vai facilitar usar os comandos no CMD/Prompt de Comando

Agora digite no CMD o comando para instalação do HUGO através do Winget:
"winget install Hugo.Hugo.Extended". Aguarde até o fim da instalação, com o HUGO instalado vamos montar a estrutura de pastas e arquivos do site:

1.3 - Para criar uma estrutura de site novo crie uma pasta no local desejado, nessa pasta ficará todos os arquivos referente ao seu site. Digite o comando: hugo new site nome-do-site.com.br

Pronto, a estrutura de pastas do seu site HUGO está montada. Vamos configurar o tema para o nosso site.

1.4 - Vamos usar em nosso projeto o tema PaperMod e agora que estamos com as estruturas de pastas prontas é hora de baixá-lo e configurá-lo.

* Clique no link para ir para a página de Documentação e Instalação do tema: https://github.com/adityatelange/hugo-PaperMod/wiki/Installation

* Agora em Get Started vamos seguir a opção 2 (**OBS: Para todos os projetos basta seguir o item 1.3 e criar a pasta do seu site, mas esse é diferente, vamos precisar trabalhar com o arquivo de configuração do Tema em formato .YAML em vez de .TOML**) 

Então se você já criou a pasta do seu site com o HUGO como no item 1.3 você pode sair dela e apagá-la, vamos precisar criar ela novamente devido ao tema PaperMOD. 

1.5 - Digite este comando na pasta onde quer criar o seu projeto para criar a pasta do projeto com o arquivo de configuração em formato YAML:

hugo new site meusite.com.br --format yaml

Descendo agora vamos encontrar a opção: **Installing/Updating PaperMod**, note que existem vários métodos para instalar, vamos utilizar o Método 2 que é o recomendado. Vamos criar uma pasta separada para o tema (porém dentro da pasta do seu projeto) através do comando:

git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod

* Agora a pasta do seu tema vai ficar dentro da pasta Themes que está na raiz do projeto. Dentro da pasta PaperMod vai ficar todos os arquivos de configuração do tema

1.6 - Agora basta ir na Raiz do site HUGO e procurar o arquivo "hugo.yaml", clique com o botão direito e selecione a opção Abrir com Visual Studio Code (Ou com o seu editor de código que você usa)

Abaixo da última linha escreva depois salve o arquivo:

theme: PaperMod

Pronto! Agora acesse o seu prompt de comando (CMD) e entre na pasta do seu site:

cd caminho-do-meu-site

* Agora dentro da pasta do seu site digite o comando para o servidor do HUGO renderizar o seu site no navegador:

hugo server

* Abra seu navegador favorito e digite: 

localhost:1313 

Seu site já está funcionando no seu computador de forma local, agora basta criar os artigos em formato .md (Markdown) que abordaremos no próximo artigo


