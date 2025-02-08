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
- Windows 10
  - Lançamento: 29 de julho de 2015 
  - Novidades: O Windows 10 deixará de ser atualizado no dia 14 de outubro de 2025 para versões Home e Pro, porém antes de dar adeus, a versão recebeu algumas melhorias, como a previsão do tempo pelo calendário e um novo design ao Outlook.   
- Windows 11
  - Lançamento: 5 de outubro de 2021
  - Novidades: Sistema novo de organização de janelas e aplicativos, *Snap Groups*, uma melhor resolução dos jogos, Auto HDR e um suporte multitelas. 
- Windows 7
  - Lançamento: 22 de outubro de 2009
  - Novidades: DirectAcess, simplificando a configuração de redes, AppLocker, protege contra malware e bloqueia aplicativos indesejados e uma melhoria na busca de arquivos e pastas, Windows Search.
- Windows 8.1
  - Lançamento: 17 de outubro de 2013 
  - Novidades: Melhorias na usabilidade, sistema mais fácil para customização, busca mais eficiente e um SkyDrive gerenciável sem precisar instalar outro programa.
- Windows 8
  - Lançamento: 26 de outubro de 2012 
  - Novidades: Interface Metro, interação parecida com o iOS, onde todos os aplicativos ficam organizados em mosaicos na tela "Start", interface Ribbon e um novo visual no painel de controle.

![Windows](https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/MSFT-Visualization-screen-desktop-layers-Windows11-device-1920x720:VP2-859x540)
## Arquitetura do Windows
O sistema operacional combina o Kernel NT, núcleo do software, com várias APIs, Interface de Programação de Aplicações, e também os serviços no Modo Usuário, além de poder ter diferentes tecnologias gráficas e drivers nos aparelhos. A arquitetura do Windows permite uma segurança, estabilidade e compatibilidade, desde o hardware até os componentes do software, o programa segue um modelo em camadas em sua arquitetura, dividido em componentes.
### Hardware
- A parte física é formada por circuitos elétricos, que permitem o funcionamento do sistema operacional e dos softwares, realizando a execução dos programas e processamento de dados, ele roda em diversas arquiteturas de processadores, como x86 (32 bits), x86-64 (64 bits) e ARM.
### Kernel NT
- Ou Windows NT, o núcleo do Windows é híbrido, combinando características de núcleos monolíticos(códigos de suporte do SO no mesmo espaço de memória) e de microkernels(usa o mínimo de espaço do sistema), se comunica com drivers de dispositivos e separa uma parte do hardware para os níveis superiores, o núcleo inclui:
  - Gerenciador de tarefas: Permite que um usuário visualize o desempenho do sistema, contém exibições que mostram o desempenho geral e o desempenho por Processo ou Pacote, também mostra os Usuários e Serviços atualmente conectados do computador e podem ser controlados por um administrador.
  - Gerenciador de memória: Implementa um modelo de memória virtual, fornece um conjunto principal de serviços, como arquivos mapeados em memória, memória de cópia na gravação, suporte de memória grande e suporte subjacente para o gerenciador de cache.
  - Gerenciador de objetos: Gerencia arquivos, dispositivos, mecanismos de sincronização, chaves do registro, todos sendo representados como objetos no Kernel NT, onde cada objeto tem um cabeçalho (seu nome, tipo e local) e um corpo (dados em um formato determinado por cada tipo de objeto).
  - Gerenciador de E/S(I/O Manager): Gerencia a comunicação entre os aplicativos e as interfaces fornecidas pelos drivers de dispositivo, é feita por meio de IRPs(pacotes de solicitação de E/S, entrada e saída), são passados do sistema operacional para drivers específicos e de um driver para outro.
  - Monitor de Referência de Segurança(SRM): O Windows usa uma ACL(lista de controle de acesso) para determinar quais objetos têm qual segurança e o monitor de referência de segurança  fornece rotinas para que o driver trabalhe com o controle de acesso. 
### Modo Usuário
### Drivers e Camada de Abstração de Hardware(HAL)
- Permite que o sistema operacional rode em diferentes arquiteturas sem precisar modificar diretamente o Kernel, esses drivers fazem a comunicação entre o sistema operacional e os dispositivos de hardware e o HAL, separa os detalhes de hardware de baixo nível dos drivers e do sistema operacional. 
### Interface Gráfica e Shell
## Comandos e suas respectivas funções

## Curiosidades
- Bill Gates já quis chamar a Microsoft de "Interface Manager".
- Aproximadamente 78% das pessoas no mundo usam o Windows.
- O Windows 10 tem uma "tela verde da morte" para os testadores do sistema.
- O resposável pela criação da música de inicialização do Windows, Brian Eno, recebeu U$ 35 mil pelo trabalho.
- O papel de parede como céu azul, nuvens e um pasto verde e livre é uma foto real, tirada por Charles O'Rear, em 1996.

![Papel de parede do Windows](https://www.hardware.com.br/wp-content/uploads/static/wp/2022/07/06/4.jpg)
