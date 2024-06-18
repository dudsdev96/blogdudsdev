---
title: "Como instalar e configurar GIT"
date: 15/06/2024
draft: false
---

<head>

</head>

<body>

<h3>Instalação</h3>
<p>1 - Baixar e instalar o git do site oficial 64bits: <a href>https://www.git-scm.com/downloads</a href></p>

<p>2 - Comando para ver se está instalado no computador e versão: Abrir o terminal CMD e digitar: git --version</p>

<h3>Configuração</h3>

<p>3 - Configurar usuário e senha do Github no Git:

    git config --global user.name "seu-usuario-github"

	git config --global user.email seu-email@tipo.com

</p>

<p>4 - Inicializar uma pasta com git  (cria pasta oculta com comandos de configuração git) . OBS: Deixar essa pasta dentro da pasta do projeto

	cd "caminho da pasta"

	git init
</p>

<p>5 - Como pegar um repositório no GitHub e clonar no seu computador
	Entrar na pasta com o botão direito (gitBash) e digitar no terminal:
	git clone (link do repositório no github)
</p>

<p>6 - Mapeia se existem arquivos novos ou alterações feitas nos arquivos existentes

	git status
</p>

<h3>Como Fazer um Commit (Empacotar para envio)</h3>
<p>Adiciona arquivo para irem para o commit

	git add ./caminho.extensão (arquivo específico)
	git add . (para preparar todos os arquivos do repositório para commitar/enviar)

	* A cada alteração no arquivo é necessário adicionar o arquivo novamente o preparo do envio

</p>







</body>