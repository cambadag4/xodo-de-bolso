XODÓ DE BOLSO

   Nossa solução é um projeto de entretenimento educativo, com o objetivo de introduzir jovens à cultura do Manguebeat e incentivar o turismo em pontos relacionados ao movimento na cidade do Recife. O projeto é um aplicativo de pet (caranguejo) virtual alimentado com cultura, a qual é absorvida por meio da visita a pontos turísticos e escaneamento de QR Codes.  A medida que é alimentado evolui, conta a história do manguebeat, traz curiosidades e envolve o usuário na temática com mini jogos.

Configurações:

VERSÃO DO PYTHON: 3.10.3

BIBLIOTECAS NECESSÁRIAS: pip, geocoder.

VERSÕES:
pip - 22.0.4
geocoder - 1.38.1

COMO INSTALAR PIP E BIBLIOTECAS:

Para windows:
1. Abra o navegador e acesse o site oficial do Python em https://www.python.org/downloads/.
2. Na página de downloads, clique no botão "Download" na versão mais recente do Python para Windows.
3. Na próxima página, role para baixo e escolha a versão apropriada do instalador do Python para o seu sistema operacional (32 ou 64 bits).
4. Após o download, execute o instalador do Python.
5. Marque a opção "Add Python to PATH" (Adicionar o Python ao PATH) e clique em "Install Now" (Instalar agora).
6. Aguarde até que a instalação seja concluída. Certifique-se de marcar a opção "Disable path length limit" (Desabilitar limite de tamanho de caminho) se ela estiver disponível.
7. Após a instalação, abra o "Prompt de Comando" (CMD) ou o "Windows PowerShell".

8. Digite o seguinte comando e pressione Enter:

     python -m ensurepip --upgrade
   
9. Após a conclusão, digite o seguinte comando e pressione Enter:
   
   python -m pip install --upgrade pip
   

Para Mac:
1. Abra o Terminal, que pode ser encontrado em "Applications" (Aplicativos) -> "Utilities" (Utilitários).

2. Verifique se o Homebrew está instalado. Se não estiver, você pode instalá-lo digitando o seguinte comando no Terminal:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

   
3. Após a instalação do Homebrew, digite o seguinte comando no Terminal para instalar o Python:

   brew install python
   
4. Aguarde até que a instalação seja concluída.

5. Após a instalação, digite o seguinte comando no Terminal:
      
pip3 install --upgrade pip
   

Linux:

1. Abra o Terminal.

2. No Ubuntu e em outras distribuições baseadas no Debian, digite o seguinte comando para atualizar o gerenciador de pacotes:
  
   sudo apt-get update
   
3. Em seguida, digite o seguinte comando para instalar o pip:
   
   sudo apt-get install python3-pip
   
4. Após a instalação, digite o seguinte comando para atualizar o pip:
   
   pip3 install --upgrade pip
   

Após seguir esses passos, o pip deve estar instalado corretamente no seu sistema operacional.

 Você pode verificar se a instalação foi bem-sucedida digitando `pip --version` no Terminal ou Prompt de Comando.



Instalando a biblioteca geocoder:

1. Será necessário abrir o CMD e checar se de fato o pip está instalado utilizando o comando:
	pip -- version.
2. Caso o pip esteja instalado, utilize o comando "pip install geocoder".
3. Após terminar a instalação, feche o seu CMD e abra o programa pelo GIT.


Como Baixar o Projeto que está no GitHub?

1. Acesse a página do projeto no GitHub: vá para o repositório do projeto que deseja baixar. Normalmente, a URL será algo como "https://github.com/cambadag4/xodo-de-bolso".

2. Clone o repositório: na página do projeto no GitHub, clique no botão verde "Code" (ou "Código") e copie a URL do repositório.

3. Abra o terminal: Em sua máquina, abra o terminal ou prompt de comando. Certifique-se de ter o Git instalado e configurado corretamente em sua máquina.

Para verificar se você possui o git instalado, abra o terminal e digite o seguinte comando:

git --version

Se o Git estiver instalado, você verá a versão do Git como saída, caso contrário você terá que baixar o Git, tutorial de como instalar o git se encontra após o tópico 7.

4. Navegue para o diretório de destino: o diretório de destino é o local onde você deseja salvar o projeto em sua máquina. Por exemplo, se você deseja salvá-lo na pasta "Documentos", abra o terminal e navegue para essa pasta. Use o comando `cd` para navegar para o diretório onde deseja salvar o projeto.

5. Clone o repositório: no terminal, execute o seguinte comando para clonar o repositório em sua máquina:

git clone <https://github.com/cambadag4/xodo-de-bolso.git>

6. Acesse o diretório do projeto: use o comando `cd` para entrar no diretório do projeto clonado. 

7. Execute o projeto

 Como baixar o Git?

- Acesse o site oficial do Git https://git-scm.com/.

- Baixe o instalador: No site do Git, você encontrará um botão de download. Clique nele para baixar o instalador 	do Git. 

- Após o download do instalador, execute-o em sua máquina. O processo de instalação varia dependendo do sistema 	operacional que você está usando.

- Durante o processo de instalação, você será solicitado a fazer algumas escolhas. Geralmente, as configurações padrão são adequadas para a maioria dos usuários, então você pode simplesmente clicar em "Next" ou "Avançar" para 	prosseguir. 

- Após seguir as instruções de instalação, o Git será instalado em sua máquina. 

- Para verificar se o Git foi instalado corretamente, abra o terminal ou prompt de comando e digite o seguinte comando:

git --version


Tutorial: Xodó de Bolso - Jogo do Caranguejo Virtual

Bem-vindo ao tutorial do Simulador de Missões - Jogo do Caranguejo Virtual! Neste jogo, você terá a oportunidade de cuidar de um pet virtual em forma de caranguejo e realizar diversas missões emocionantes. Siga as instruções abaixo para começar a jogar:

Passo 0: Baixar todos os arquivos do projeto, salvá-los na mesma pasta e executar o main.py em alguma IDE.

Passo 1: Cadastro e Login
Ao iniciar o jogo, você será apresentado a um menu de opções. Digite "1" para realizar o cadastro como novo usuário ou "2" para fazer login caso já tenha uma conta.
Se escolher a opção 1, você será solicitado a fornecer um nome de usuário, senha e o nome do seu pet virtual. Essas informações serão salvas em um arquivo chamado "usuarios.txt".
Caso escolha a opção 2, digite seu nome de usuário e senha para fazer login no jogo.


Passo 2: Personalização do Caranguejo
Após o login bem-sucedido, você terá a oportunidade de personalizar o seu caranguejo virtual.
Escolha a espécie do caranguejo entre as opções disponíveis: Caranguejo-Ermitão, Caranguejo-Verde e Caranguejo-Vermelho.
Em seguida, escolha a cor da casca do caranguejo: Vermelha, Azul ou Verde.
Digite o nome do seu caranguejo.
Após essas escolhas, seu caranguejo virtual estará pronto para as missões!


Passo 3: Realização de Missões
No jogo, existem duas missões disponíveis: Missão Marco Zero e Missão Memorial.
Após personalizar o seu caranguejo, você será direcionado para um menu de missões.
Escolha uma das missões digitando o número correspondente à missão desejada.
Se você completar a missão com sucesso, receberá uma mensagem de parabéns. Caso contrário, será informado que a missão não foi cumprida.
Você pode sair do jogo a qualquer momento digitando "q" no menu de missões.


Passo 4: Cuidados com o Caranguejo
Durante o jogo, você precisa cuidar do seu caranguejo virtual.
O caranguejo possui duas necessidades principais: fome e sujeira.
Para alimentar o caranguejo, você poderá escolher entre três opções de alimentos: Cuscuz, Tapioca e Bolo de Rolo. Cada alimento tem um valor específico para diminuir a fome do caranguejo.
Da mesma forma, para limpar o caranguejo, você poderá escolher entre três opções de produtos: Sabonete, Shampoo e Condicionador. Cada produto tem um valor específico para diminuir a sujeira do caranguejo.
Lembre-se de alimentar e limpar o caranguejo regularmente para mantê-lo saudável. Caso a fome ou a sujeira atinjam o nível zero, seu caranguejo ficará doente.


Passo 5: Recompensas Especiais
Durante o jogo, há uma chance de você encontrar um item exclusivo ao realizar missões em determinadas localizações especiais.
Caso o seu caranguejo virtual tenha um item exclusivo, você receberá uma mensagem informando sobre essa conquista especial.


Passo 6: Minijogos
Além das missões, você também pode aproveitar dois minijogos disponíveis: Jogo da Forca e Jogo de Perguntas e Respostas.

Jogo da Forca:
Nesse minijogo, você terá que adivinhar a palavra secreta antes de ficar sem tentativas. Você terá 6 tentativas para acertar a palavra correta. A cada letra correta que você adivinhar, ela será exibida na palavra secreta. Caso acerte a palavra antes de usar todas as tentativas, você vence o jogo. Se ficar sem tentativas e não acertar a palavra, você perde o jogo.

Jogo de Perguntas e Respostas:
Nesse minijogo, você será desafiado com perguntas sobre o movimento Manguebeat. Leia atentamente cada pergunta e escolha a opção correta entre as alternativas disponíveis. Se você responder corretamente, ganhará pontos. No final do jogo, será exibida sua pontuação total.
Para acessar os minijogos, escolha a opção "C" no menu principal e siga as instruções exibidas na tela.


Agora você está pronto para começar a jogar Xodó de bolso - Jogo do Caranguejo Virtual! Divirta-se explorando as missões, cuidando do seu caranguejo virtual e coletando recompensas. Boa sorte e aproveite o jogo!
