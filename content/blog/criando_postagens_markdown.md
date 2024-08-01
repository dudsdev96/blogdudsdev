+++
title = 'Criando postagens em Markdown com HUGO Sites'
date = 2024-07-28T11:31:23-03:00
draft = false
+++

Para criar uma arquivo de postagem para seu site abra a pasta do seu site HUGO, copie o caminho dela e abra o CMD
 como administrador, digite o comando `cd` e clique com o botão direito para colar o caminho copiado e aperte enter.

* Você agora está dentro da pasta do seu projeto HUGO, o comando de criação de novas postagens devem ser 
digitados sempre na pasta raiz do seu Site. Já no CMD digite: 

`hugo new content/criando_postagens_hugo.md`

Pronto! O seu arquivo que se tornará um artigo já foi criado e possui pré configurações HUGO dentro dele, porém
está em branco, sem conteúdo.

Para preenchê-lo você pode digitar normalmente assim como estou digitando agora, e o texto vai aparecer no seu site,
não tem segredo. Mas se você quer deixar o texto mais bonito, mais formatado acesse este site com todos os comandos
da linguagem Markdown para formatar o seu artigo: https://www.markdownguide.org/ 


## Troquei de tema agora minhas postagens antigas não funcionam com o tema novo

Se você for trocar de tema no HUGO será necessário recriar os arquivos markdown (arquivos de postagens do site) 
para que o seu site reconheça as postagens. Nesse caso salve os arquivos .md (markdown) antigos (do tema anterior) 
em uma pasta como backup, recrie os arquivos markdown já com o tema novo trocado (vou ensinar abaixo) e cole o 
conteúdo dos markdowns antigos no arquivo novo já criado após a troca de tema. 


