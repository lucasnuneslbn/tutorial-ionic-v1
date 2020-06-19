# Configuração de ambiente de desenvolvimento ionic-v1 no windows 10
## 1 - Faça download e instale o  npm (node.js) : 
https://nodejs.org/en/
## 2 - Faça download e instale o git : 
https://git-scm.com/download/win 
## 3 - Adicione o diretório dos executáveis do  git na variável de ambiente PATH.
===> Clique com o botão direito em "Meu computador" e depois "Propriedades"  
===> Clique em "Configurações avançadas do sistema"  
===> Selecione a Aba "Avançado" e clique no botão "Variáveis de Ambiente"  
===> No bloco "Variáveis do Sistema", localize a Variável "PATH" e dê 2 cliques  
===> clique em novo e adicione o diretorio dos arquivos executáveis do git  
===> O diretório padrão é: c:\Program Files\Git\bin\
## 4 - Abra o prompt de linha de comando e baixe o ionic através do npm:
===> (CMD) npm install -g @ionic/cli  
## 5 - Ainda no prompt, instale o Cordova:
===> (CMD) npm install -g cordova
