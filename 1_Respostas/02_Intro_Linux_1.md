1. Por que o Linux recebeu esse nome?\
  O sistema operacional aberto foi desenvolvido pelo finlandês Linus Torvalds. 

2. O que são daemons?\
  São programas de computadores que realizam processos em sistemas operacionais multitarefa em segundo plano.

3. O que é o shell?\
  É a interface de usuário. Em geral, há dois tipos: ILC (interface de linha de comando) e GUI (Guide User Interface). É denominada de Shell pois é a camada mais externa do núcleo de um sistema operacional, aquela que interage com o usuário.

4. Por que é importante evitar executar o terminal como super-usuário?\
  O super-usuário, root, possui acesso, podendo editar, inclusive, às configurações do sistema, configurar interfaces de rede, manipular usuários e grupos, alémd e alterar prioridade de processos.\
  Com tamanha liberdade, por segurança não é recomendado utilizar esse usuário por conta de erros ou de outras pessoas utilizarem esse super usuário.

5. Qual botão do teclado completa o que o usuário escreve no terminal, de acordo com o contexto?\
  A tecla Tab

6. Quais botões do teclado apresentam instruções escritas anteriormente?\
  1º Seta para cima\
  2º Control + "E"
  
7. Apresente os respectivos comandos no terminal para:

  (a) Obter mais informações sobre um comando.\
      - man + "comando": apresenta informações sobre o comando\
      - man man: apresenta informações sobre o funcionamento do manual do linux através do terminal
   
  (b) Apresentar uma lista com os arquivos dentro de uma pasta.\
      - ls + diretório: lista os arquivos dentro de uma pasta\
      - ls + diretório + -lh: lista os arquivos junto com os seus tamanhos
  
  (c) Apresentar o caminho completo da pasta.\
    - pwd : O terminal informará o caminho completo do diretório no qual você se encontra
  
  (d) Trocar de pasta.\
    - cd diretório/diretório/diretório\
    - cd .. : volta um diretório acima ao invés de digitar o diretório completo sem o atual\
    - cd - : volta ao diretório anterior\
    cd ../../.. : volta a vários níveis acima do diretório atual em função da quantidade de ../
  
  (e) Criar uma pasta.\
    mkdir nome_da_pasta : cria um diretório dentro do atual em que você está com o nome que você colocar no comando
    
  (f) Apagar arquivos definitivamente.\
    rm "nome_do_arquivo" : Apaga definitivamente o arquivo
    
  (g) Apagar pastas definitivamente.\
    rm -r "nome do diretório" : Apaga permanentemente o diretório selecionado
    
  (g) Apagar pastas definitivamente.\
    rm -r "nome do diretório" : Apaga permanentemente o diretório selecionado
    
  (h) Copiar arquivos.\
    cp "nome_do_arquivo_de_origem" "nome_do_arquivo_de_destino" ou "nome_do_destinatário_de_destino"
     
  (i) Copiar pastas.\
    cp -r "nome_do_destinatário_de_origem" "nome_do_arquivo_de_destino" ou "nome_do_destinatário_de_destino"
    
  (j) Mover arquivos.\
    mv "nome_do_arquivo_de_origem" ou "nome_do_destinatário_de_destino" "nome_do_arquivo_de_destino" ou "nome_do_destinatário_de_destino"\
    arquivo pode ser movido para pasta e para outro arquivo caso você queira renomear\
    destinatário pode ser movido para outro destinatário ou pode ter nome alterado inserindo um nome de destinatário não existente
    
  (k) Mover pastas.\
   mv "nome_do_destinatário_de_origem" "nome_do_destinatário_de_destino"
  
  (l) Renomear pastas.\
   mv "nome_do_destinatário_de_origem" "nome_do_destinatário_de_destino"
    
  (m) Apresentar o conteúdo de um arquivo.\
   more "nome_do_arquivo"
  
  (n) Apresentar o tipo de um arquivo.\
   file "nome_do_arquivo"
   
  (o) Limpar a tela do terminal.\
   clear
   
  (p) Encontrar ocorrências de palavras-chave em um arquivo-texto.\
  grep "nome_do_arquivo"
  
  (p) Encontrar ocorrências de palavras-chave em um arquivo-texto.\
  grep -c "palavra_a_ser_procurada" "nome_do_arquivo" : ocorrências da palavra a ser procurada em uma linha. Com o -c, só será procurado se a palavra a ser procurada for uma palavra inteira.\
  grep -w "palavra_a_ser_procurada" "nome_do_arquivo" : ocorrências da palavra a ser procurada em uma linha. Com o -w, será procurada a palavra caso ela seja parte de outra, por exemplo, procurar a palavra "be" em "become"\
  
  (q) Ordenar informações em um arquivo-texto.\
   sort "nome_do_arquivo": ordena as informações em ordem alfabética\
   sort -n "nome_do_arquivo" : ordena as informações em ordem numérica
  
  (r) Substituir ocorrências de palavras-chave em um arquivo-texto.\
   sed -i 's/original/nova/g' "arquivo" 

  (s) Conferir se dois arquivos são iguais.\
  diff [opções] "arquivo_1" "arquivo_2"
  
  (t) Escrever algo na tela.
