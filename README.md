# *Pesquisa Windows* 🖥🖱
### Pesquisa sobre a evolução dos sistemas operacionais, com foco no Windows, seus marcos, versões, novidades e muito mais. 
## O que é um sistema operacional?
O sistema operacional (SO) é um software que pode ser utilizado como base para qualquer computador ou celular, são responsáveis por todo o funcionamento do dispositivo, tanto como a interface entre o usuário e os dispositivos quanto os comandos de processamento, alguns exemplos famosos são o SO da Apple, o *iOS* e *macOS* e o do Google, utilizado em Chromebooks, o ChromeOS. 

![Sistemas operacionais](https://t.ctcdn.com.br/LGHPK1cFeIscJlztZ0zmCgy_-vs=/640x360/smart/i627624.jpeg)
## A evolução dos sistemas operacionais
### O início de tudo
Durante a 2° Guerra Mundial, os programadores se comunicavam com seus computadores utilizando apenas os números 0 e 1. A partir da década de 1950, o termo *sistema operacional*  começou a surgir por causa do computador IBM 704, o primeiro monitor que permitia a execução de outros programas nele. Esse sistema também evoluiu em meados dos anos 60, mudando de um sistema operacional para outro, permitindo que diversos usuários utilizem, ao mesmo tempo, os recursos do computador, também durante essa década, em 1969, houve a chegada do *UNIX*, criado por Ken Thompson, Dennis Ritchie e Rudd Canaday, que permitia os usuários da época a multitarefa e o multiusuário, onde teve um grande impacto na sociedade e no desenvolvimento dos sistemas operacionais, atualmente, o *Linux* utiliza do sistema operacional Unix.

![Código da Unix](https://upload.wikimedia.org/wikipedia/commons/0/06/Man-man.png)
### Criação dos Sistemas Operacionais mais famosos
#### Linux
Criado em 1991 por Linus Torvalds, quando decidiu desenvolver um sistema mais poderoso que o Unix, então ele divulgou sua ideia no Usenet(um antecessor da Internet), no mesmo ano lançou a versão 0.02 do Linux e continuou melhorando até 1994, o ano em que disponibilizou a versão 1.0 do Linux, e devido a boa aceitação da sociedade ao sistema, temos as versões que conhecemos hoje em dia, como a Linux 10. O Linux é um sistema operacional de código aberto, um sistema livre e aberto à modificações.

![Versões do Linux](https://consult.red/wp-content/uploads/2021/01/logo-linux.png.webp)
#### Windows
Criado pelos estudantes Bill Gates e Paul Allen, em um computador PDP-10 da Digital Equipment Corporation no ano de 1975, surgiu o Windows. Depois de um tempo, apareceu o *MS-MOD*, sua arquitetura mudou um pouco com as melhorias, a partir disso, suas vendas começaram a crescer muito, dando origem a novas versões que nós conhecemos hoje em dia, como o Windows 10. O Windows é um sistema operacional proprietário, onde o código não é aberto à modificação de todos.

![Versões do Windows](https://extremehd.com.br/wp-content/uploads/2023/10/2023-10-10_23h35_02.png)
## As 5 versões mais importantes do Windows
- __Windows 10__
  - __Lançamento__: 29 de julho de 2015 
  - __Novidades__: O Windows 10 deixará de ser atualizado no dia 14 de outubro de 2025 para versões Home e Pro, porém antes de dar adeus, a versão recebeu algumas melhorias, como a previsão do tempo pelo calendário e um novo design ao Outlook.   
- __Windows 11__
  - __Lançamento__: 5 de outubro de 2021
  - __Novidades__: Sistema novo de organização de janelas e aplicativos, *Snap Groups*, uma melhor resolução dos jogos, Auto HDR e um suporte multitelas. 
- __Windows 7__
  - __Lançamento__: 22 de outubro de 2009
  - __Novidades__: DirectAcess, simplificando a configuração de redes, AppLocker, protege contra malware e bloqueia aplicativos indesejados e uma melhoria na busca de arquivos e pastas, Windows Search.
- __Windows 8.1__
  - __Lançamento__: 17 de outubro de 2013 
  - __Novidades__: Melhorias na usabilidade, sistema mais fácil para customização, busca mais eficiente e um SkyDrive gerenciável sem precisar instalar outro programa.
- __Windows 8__
  - __Lançamento__: 26 de outubro de 2012 
  - __Novidades__: Interface Metro, interação parecida com o iOS, onde todos os aplicativos ficam organizados em mosaicos na tela "Start", interface Ribbon e um novo visual no painel de controle.

![Windows](https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/MSFT-Windows-Update-RW1cJTH?scl=1&fmt=png-alpha)
## Arquitetura do Windows
O sistema operacional combina o Kernel NT, núcleo do software, com várias APIs, Interface de Programação de Aplicações, e também os serviços no Modo Usuário, além de poder ter diferentes tecnologias gráficas e drivers nos aparelhos. A arquitetura do Windows permite uma segurança, estabilidade e compatibilidade, desde o hardware até os componentes do software, o programa segue um modelo em camadas em sua arquitetura, dividido em componentes.
### Hardware
- A parte física é formada por circuitos elétricos, que permitem o funcionamento do sistema operacional e dos softwares, realizando a execução dos programas e processamento de dados, ele roda em diversas arquiteturas de processadores, como x86 (32 bits), x86-64 (64 bits) e ARM.
### Kernel NT
- Ou Windows NT, o núcleo do Windows é híbrido, combinando características de núcleos monolíticos(códigos de suporte do SO no mesmo espaço de memória) e de microkernels(usa o mínimo de espaço do sistema), se comunica com drivers de dispositivos e separa uma parte do hardware para os níveis superiores, o núcleo inclui:
  - __Gerenciador de tarefas__: Permite que um usuário visualize o desempenho do sistema, contém exibições que mostram o desempenho geral e o desempenho por Processo ou Pacote, também mostra os Usuários e Serviços atualmente conectados do computador e podem ser controlados por um administrador.
  - __Gerenciador de memória__: Implementa um modelo de memória virtual, fornece um conjunto principal de serviços, como arquivos mapeados em memória, memória de cópia na gravação, suporte de memória grande e suporte subjacente para o gerenciador de cache.
  - __Gerenciador de objetos__: Gerencia arquivos, dispositivos, mecanismos de sincronização, chaves do registro, todos sendo representados como objetos no Kernel NT, onde cada objeto tem um cabeçalho (seu nome, tipo e local) e um corpo (dados em um formato determinado por cada tipo de objeto).
  - __Gerenciador de E/S(I/O Manager)__: Gerencia a comunicação entre os aplicativos e as interfaces fornecidas pelos drivers de dispositivo, é feita por meio de IRPs(pacotes de solicitação de E/S, entrada e saída), são passados do sistema operacional para drivers específicos e de um driver para outro.
  - __Monitor de Referência de Segurança(SRM)__: O Windows usa uma ACL(lista de controle de acesso) para determinar quais objetos têm qual segurança e o monitor de referência de segurança  fornece rotinas para que o driver trabalhe com o controle de acesso. 
### Modo Usuário
- É o modo de operação responsável por executar programas e processos de usuário, limitando o acesso a recursos do sistema, é utilizado para resolver os problemas de design com interfaces fáceis, instalação e desinstalação, acima do Kernel, o Windows possui camadas para rodar aplicações e serviços:
  - __Subsistema de Ambiente__: Ou Windows API, cria e usa janelas para exibir a saída, solicita a entrada do usuário, executa as outras tarefas que oferecem suporte à interação com o usuário e  permite a execução de diferentes tipos de aplicativos, como:
    - __Win32 API__: O API tradicional do Windows, é a plataforma original para aplicativos nativos do Windows em C/C++ que exigem acesso direto ao Windows e ao hardware, fornecendo uma experiência de desenvolvimento de primeira classe sem depender de um ambiente de runtime, onde um programa é executado, gerenciado como o .NET e o WinRT.
    - __Plataforma Universal do Windows(UWP)__: É uma opção para criar aplicativos que são executados em dispositivos Windows 10/11 e podem ser combinados com outras plataformas, sendo um framework para aplicativos modernos.
    - __Subsistema do Windows para Linux(WSL)__: É um recurso que permite que os desenvolvedores instalem uma distribuição do Linux, como Arch Linux, usem aplicativos e ferramentas de linha de comando bash, permitindo que o usuário execute comandos e crie scripts, do Linux no Windows, sem modificação, sem a sobrecarga de uma máquina virtual tradicional ou configuração dualboot, onde dois sistemas operacionais dividirão a capacidade de armazenamento do disco e o usuário escolherá qual deseja iniciar ao ligar o computador.
  - __Subsistema de Serviços__: É um aplicativo que gerencia os serviços que rodam em segundo plano no sistema, como gerenciamento de rede e atualização do sistema. 
### Drivers e Camada de Abstração de Hardware(HAL)
- Permite que o sistema operacional rode em diferentes arquiteturas sem precisar modificar diretamente o Kernel, esses drivers fazem a comunicação entre o sistema operacional e os dispositivos de hardware e o HAL, separa os detalhes de hardware de baixo nível dos drivers e do sistema operacional. 
### Interface Gráfica
- A interface gráfica utilizada pelo sistema operacional é o Windows Shell, uma interface gráfica de usuário(GUI), funcionando como uma interação com o computador através de elementos visuais, como botões, ícones, janelas e menus, a interface inclui componentes como: 
  - __Shell__: É um recurso que permite que o usuário execute comandos, programas e serviços, como a Área de Trabalho, Alternador de Tarefas e a Reprodução Automática.  
  - __Explorer.exe__: É um gerenciador de arquivos e programas que oferece a interface gráfica a interação com a maioria das funcionalidades do Windows, como o Menu Iniciar, Barra de Tarefas e Área de Notificação.
  - __Interface de Dispositivo Gráfico(GDI)__: Permite que os aplicativos usem elementos gráficos e texto formatado na exibição de vídeo e na impressora, os aplicativos desenvolvidos para o Windows não acessam o hardware gráfico diretamente, é a GDI que interage com os drivers de dispositivo em nome de aplicativos.
  - __DirectX__: É um conjunto de componentes permitindo que o software, principalmente em jogos, funcione diretamente com seu hardware de vídeo e áudio, os jogos que usam o DirectX podem usar recursos de acelerador multimídia integrados ao hardware com mais eficiência, melhorando sua experiência multimídia geral. 
  - __Compositor de Janelas(DWM)__: Gerencia a sessão entre um aplicativo e o processo de compositor do sistema, é responsável por compor a área de trabalho, permitindo efeitos visuais, animações e suporte a alta resolução.
 
![Hardware Windows](https://onsign.tv/media/hardware.png)
## Comandos e suas respectivas funções

![Teclado](https://files.tecnoblog.net/wp-content/uploads/2022/01/teclado-iluminado-windows-escuro-pc-notebook-700x394.jpg)
## Curiosidades
- Bill Gates já quis chamar a Microsoft de "Interface Manager".
- Aproximadamente 78% das pessoas no mundo usam o Windows.
- O Windows 10 tem uma "tela verde da morte" para os testadores do sistema.
- O resposável pela criação da música de inicialização do Windows, Brian Eno, recebeu U$ 35 mil pelo trabalho.
- O papel de parede como céu azul, nuvens e um pasto verde é uma foto real, tirada por Charles O'Rear, em 1996.

![Tela encerrar Windows](https://s2-techtudo.glbimg.com/kv3qI4GR_BuZodi7w4WcUYeor9U=/0x0:695x290/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2021/L/I/qiHWgHRAOnOzNI1dVIUg/2015-04-07-encerrando-windows.png)
