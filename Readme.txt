Primeira linha do arquivo"

Passo a passo da Tarefa da disciplina UC7 - Versionamento, postada após Encontro 01, em 16/11/2021:

 1 - Considerando o DVCS Git instalado na minha máquina de trabalho, para o MS Windows, foram realizadas as seguintes
     configurações iniciais: 
	1.1 - Emular o terminal <prompt> do Git, dentro da pasta 
              C:\Users\josec\OneDrive\Documentos\MeusProjetos\_git\Tarefa-Encontro-01 (que escolhi para meu repositório
              local
        1.2 - Considerando que já fiz a configuração global com <git config> fornecendo o nome do usuário e um endereço de
              e-mail, no <prompt> do Git Bash, com esses comandos <git config --global user.name "meu nome" e 
              <git config --global user.email "coloquei o meu e-mail">. Esses dois passos, atualizarão minhas informações
              de usuário e cada alteração feita, manterá minha identidade como autor.
 2 - Realizar todas as configurações e demais ações necessárias para a prática de monitoramento e gerenciamento de 
     alterações no código. Usei as seguintes:
	2.1 - Considerando que já criei a pasta chamada Tarefa-Encontro-01 (que escolhi para meu repositório
              local), conforme 1.1, e onde serão feitos o rastreamento de minhas atividades, a criação de arquivos), fiz:
              2.1.1 -  Criei um Repositório Git Local (é um armazenamento virtual, para o projeto, no qual serão gravadas
                       as versões do código e de acesso a qualquer momento). Ele será a pasta/diretório da minha máquina
                       com o meu projeto.
                       Para criar esse Repositório Git, dentro da pasta Tarefa-Encontro-01, criada anteriormente, dei um
                       duplo clique com o botão direito do mouse e inicializei o Git Bash, clicando em "Git Bash Here".
		       O <prompt> abriu e nele comecei a digitar os comandos necessários para completar esse desafio.
	      2.1.2 - Iniciei o Repositório Local, digitando na linha de comando o comando <git init>. Quandofoi executado
                      criou uma pasta .git (pode vê-la, ao configurar todos os "itens visiveis"). Se não configurar, ela
                      não ficará visível. Com isso ela transforma o diretório local em um repositório para o Git. 
              2.1.3 - Criei, também, um documento".txt" de nome "Readme", onde ficarão registrados caminhos e comandos
                      utilizados para completar essa tarefa.
              2.1.4 - Rastreei, pela primeira vez, o Repositório Local, com o comando <git status>
	      2.1.5 - Adicionei o arquivo "Readme" ao histórico do projeto com o comando <git add Readme.txt>. Isso 
                      registrou uma alteração. Ou seja, historicamente, ele existe mas como não houve nenhuma alteração
                      ainda, ele está vazio. Como o Git está monitorando, ele acabou de saber dessa existência; porém, 
		      como cada alteração deve ser salva isso deve ser feito; então o próximo passo é salvar. Poderiamos
                      dizer que essa é a "versão zero" ou  "V0" do meu Readme.txt.
	      2.1.6 - Antes de salvar, rastreei, pela segunda vez, o Repositório Local, com o comando <git status> para  se estava
                      verificar se a operação acima foi processada corretamente. 
 	      2.1.7 - Salvei a última alteração no meu repositório, sob os olhares do Git, com o comando <git commit>,
                      com a sintaxe completa ficou assim: <git commit -m "iniciando a tarefa do Encontro de 16/11/2021">. 
                      O comentário é para alertar que foi salva  a versão mais atual do meu repositório. Poderíamos 
                      chamar de "versão 1" ou "V1" do meu Readme.txt. Históricamente, o Git, tem as V0 e V1 (versões).
              2.1.8 - Visualizei as alterações feitas com o comando <git log" para verificar se estava tudo certo.
                      Lembrei que o <git log> é um relatório de tudo que ocorreu e o <git status> mostra dados do
                      registro de cada ocorrência/alteração.
              2.1.9 - Pelo adiantado da hora, não poderei detalhar o que fiz com o Github
	      2.1.10 - Criei um diretorio no Repositório <tarefa-UC7>
	      2.1.11 - Tentei inicialmente usar no prompt o comando < git remote add origin com uma URL de um colega>, 
                       Objetivo: com isso trabalharia no projeto de um dos  colegas para pequenas alterações em dois 
                       arquivos.
              2.1.12 - Aí, tentei o <git clone URL> Os arquivos foram para o meu repositório local
              2.1.13 - Criei uma branch tarefa <git branch tarefa>
              2.1.14 - Troquei a raiz master para trabalhar no ramo tarefa <git checkout master>
	      2.1.15 - Na pasta Readme.text do projeto que clonei fiz pequenas alterações
              2.1.16 - <git status>; <git commit -m "Visitando seu Projeto"
              2.1.17 - Voltei para fazer outra pequena alteração em outro arquivo
              2.1.18 - <git status>; <git commit -m "Continuo Visitando seu Projeto" 
              2.1.19 - A partir desse ponto, as dúvidas aumentaram
	      2.1.20 - Troquei a raiz tarefa para master  <git checkout tarefa> pensei de usar o <merge>
              2.1.21 - Fiz o merge, mas quando subi para o meu repositório pedia a chave da URL do colega.
              2.1.22 - Não conseguindo acriar, resolvi criar um novo repositório online para mostrar
                       esse passo a passo. 
              2.1.23 - Deletei o outro repositório e criei "tarefa-UC37"
              2.1.24 - git remote add origin https://github.com/jose-ro/tarefa-UC37.git
              2.1.25 - git remove -v
              2.1.26 - autorizei o usuário no github
              2.1.27 - git add Readme.text
              2.2.29 - git status 
              2.1.30 - git commit -m "Acrescentado o passo a passo"
              2.1.31 - git pull
