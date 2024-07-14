+++
title = 'Como instalar e configurar o GIT'
date = 2024-07-13T16:45:42-03:00
draft = false
+++




### Instalação 
1 - Baixar e instalar o git do site oficial 64bits: https://www.git-scm.com/downloads

2 - Comando para ver se está instalado no computador e versão: Abrir o terminal CMD e digitar: git --version

### Configuração

3 - Configurar usuário e senha do Github no Git:

* git config --global user.name "seu-usuario-github"

* git config --global user.email seu-email@tipo.com



4 - Inicializar uma pasta com git  (cria pasta oculta com comandos de configuração git) . OBS: Deixar essa pasta dentro da pasta do projeto

* cd "caminho da pasta no computador"
 
* git init


5 - Como pegar um repositório no GitHub e clonar no seu computador
	Entrar na pasta com o botão direito (gitBash) e digitar no terminal:

* git clone (link do repositório no github)


6 - Mapeia se existem arquivos novos ou alterações feitas nos arquivos existentes

* git status


7 - Como Fazer um Commit (Empacotar para envio)
Adiciona arquivo para irem para o commit

* git add ./caminho.extensão (arquivo específico)
* git add . (para preparar todos os arquivos do repositório para commitar/enviar)

**OBSERVAÇÃO:** 
* A cada alteração no seu código é necessário adicionar o arquivo novamente o preparo do
envio (commit), sempre se lembre de usar o -m como argumento após o **commit** para deixar
 uma mensagem e melhor identificar aquele commit.


8 - Comando para de fato Enviar os arquivos: git push origin main
	
* O origin main é por qual galho (branch) o Envio vai subir para o servidor remoto do
GitHub, nesse caso o branch Main (principal). Se você não criou mais nenhum esse
será o único galho (branch) existente os envios sempre irão para ele.

