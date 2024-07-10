+++
title = 'Como instalar e configurar o HUGO Sites'
date = 2024-07-04T22:35:09-03:00
draft = false
+++

## Instalação

<p> 1.1 - Existem várias formas de instalar o Hugo em diversos sistemas operacionais, como: Windows, MAC e Linux, neste artigo estarei    explicando como instalar no Windows. A forma mais prática é através de um gerenciador de pacotes chamado Winget. 
</p>

<p>1.2 - Aperte a tecla do Windows para abrir o Menu Iniciar e digita CMD, clique com o botão direito em cima dele e depois clique na opção: "Executar como Administrador". Note que abrirá o Prompt de Comando, uma tela preta. O caminho mostrado no Prompt de Comando está descrita a pasta System32, que é o que estamos buscando, isso vai facilitar usar os comandos no CMD/Prompt de Comando</p>

<p>Agora digite no CMD o comando para instalação do HUGO através do Winget:
"winget install Hugo.Hugo.Extended". Aguarde até o fim da instalação, com o HUGO instalado vamos montar a estrutura de pastas e arquivos do site:</p>

<p>1.3 - Para criar uma estrutura de site novo crie uma pasta no local desejado, nessa pasta ficará todos os arquivos referente ao seu site. Digite o comando: hugo new site nome-do-site.com.br</p>
