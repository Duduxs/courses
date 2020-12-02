# Curso do professor Welington de Hardware Básico <https://www.youtube.com/channel/UCh7v1laqx7bZodFvIL1Q42g/>

<h1>Tópico 01 - Principais componentes de um PC e Notebook</h1>
<hr>
<h2>Placa-mãe ou Motherboard</h2>

É nela que conectamos todos os outros componentes, e é ela que gerencia todos os dados que são transmitido nos dispositivos de hardware do *PC* (Personal Computer).

<h2>Processador ou CPU</h2>

O CPU é o componente de hardware responsável por todo processamento lógico aritmético que é feito em um computador. Portanto, quando abrimos um programa no computador é o processor que é responsável pelos resultados obtidos no monitor.

<h2>Memória RAM ou Memória Principal</h2>

É nela que o processador procura por dados quando vai executar alguma ação, ou seja, executar alguma instrução como abrir algum programa. A memória RAM é uma memória **muito mais rápida do que o HD, que é uma memória de armazenamento em massa**. Por ser a mais rápida, ela faz a busca no HD e envia para o processador quando alguma instrução ou programa precisa ser executado.

<h2>Memória de armazenamento em massa ou HD (Hard Disk)</h2>

Todos os arquivos pessoais do SO são guardados nele, diferente de uma memória RAM que **perde os dados quando o pc é desligado**, no HD os arquivos são permanentes, mesmo se não houver energia.

<h2>SSD ou Solid-State Drive</h2>

É uma tecnologia de armazenamento considerada a evolução do HD. São dispositivos de memória flash, eles não possuem discos rigidos como o HD. O HD é mais lento devido a leitura dos discos.

<h2>Placa de vídeo</h2>

Componente responsável por exibir os resultados do que é feito pelo computador no monitor, tendo dois tipos de placas:

1. Offboard  -> Placas expansíveis que podemos instalar através de uma placa de expansão, sendo as melhores, pois tem um processamento em memória própria, independente do processador e/ou memória.
2. Onboard   -> Placas que por padrão já vem soldada na placa mãe. Precisam ter o processamento feito pelo computador, por isso são mais lentas.

<h2>Fonte de alimentação</h2>

Responsável por fornecer energia para o computador. A fonte deve fornecer energia suficiente para todos os componentes de um computador, para que funcione corretamente e não danifique. Ela também fornece energia para as ventoinhas do PC, existem testes também testes para determinar qual fonte você vai precisar dentro do seu computador, mas já avisando de antemão que quanto mais é melhor.

<h2>Placa de rede</h2>

É um componente indispensável para o pc funcionar, por padrão qualquer placa mãe virá com uma conexão de rede *Ethernet* (internet cabeada), mas também temos placa de rede *wireless* (sem fio)

<h2>Gabinete</h2>

É a peça do computador desktop onde é colocado todos os componentes físicos. 

<h2>Periféricos de entrada e saída de dados</h2>

Responsável para que haja interação entre nós seres humanos e o pc. Existem três tipos de periféricos, os de entrada, saída e os de entrada e saída. Veja alguns exemplos abaixo.

✔️ Periféricos de entrada: Teclado, mouse & webcam.
✔️ Periféricos de saída: Monitor & impressora.
✔️ Periféricos de entrada e saída de dados: Monitores touch screen.

<h1>Tópico 02 - O que é a Motherboard</h1>
<hr>

Ela é o **componente principal de um computador**, pois é justamente na placa mãe que é conectado todos os outros periféricos do computador. Na imagem abaixo você verá os principais componentes abordados em aula sem aprofundamento, pois nós veremos mais para frente.

<img src="https://miro.medium.com/max/1972/1*IWQdop1gOO2NIell2ssivw.png" alt="Componentes da placa mãe">

<h1>Tópico 03 - O que é o Processador</h1>
<hr>

Quando ligamos o computador, os arquivos do sistema estão sendo carregados para a RAM, arquivos esses que já estão no HD. E da memória RAM ele é passado para o processador que assume todos os cálculos necessários que precisa fazer para executar uma determinada tarefa. O processador nunca acessa diretamente o HD para poder pegar dados para ser processado. Ele vai primeiro na RAM e a RAM vai no HD buscar os dados que ele precisa.

Dentro do processador temos alguns componentes tais como: 

✔️ ULA (Unidade de lógica e aritmética): É nela que os processamentos lógicos e aritméticos são feitos (Decisões lógicas, cálculos, ...).

✔️ UC (Unidade de Controle): Os dados sempre são trafegados em uma determinada tarefa, é ele que determina se um dado vai se deslocar de um lugar para outro e quais dados serão deslocados.

✔️ Registradores: São memória ultra rápidas que auxiliam o processador nesses poderes de decisão e controle do computador.

✔️ Memórias caches: Memórias mais lentas que o registrador, porém também muito rápida, tendo três níveis L1, L2 & L3.


💣 Cuidado

Na hora de colocar um novo processador na sua máquina, sempre veja o socket da placa mãe, isso é se ela tem compatibilidade com esse processador ou não. Esses sockets servem como porta de entrada para instalar o processador na motherboard. 

<h1>Tópico 04 - O que é a Memória RAM</h1>
<hr>

Conhecida como **memória principal**, quando ligamos o computador os arquivos do SO são carregados do HD ou do SSD direto para a RAM, e depois que são carregados na RAM ele são passados para serem processados. O tempo todo os dados que estão na memória RAM são trocados por dados novos que precisam ser processados em tela no momento. 

💡 Curiosidade

Quando desligamos o computador toda a RAM é apagada, ao ligarmos o mesmo novamente ela ser recolocada. É por isso que quando estamos com algo no nosso CTRL C e desligamos o pc não vamos poder mais colar, pois os dados foram perdidos, só estão lá em tempo de execução.

<h1>Tópico 05 - Qual a diferença entre HD e SSD</h1>
<hr>

Ambos são memórias de armazenamento em massa, ou seja, posso salvar arquivos muito grandes do pc neles. 

**HD (Hard Disk)** => É formado por um disco magnético, sendo gravado de forma magnética. Quanto mais RPM (Rotações por minutos) tiver o disco, mais rápido será a gravação e a leitura do dado no HD. Existem discos com velocidades maiores com mais de 10 mil rotações por minuto que são muitos utilizados em servidores, se você for ter uma boa velocidade de gravação do disco tenha certeza de que a refrigeração do seu pc seja boa também.

**SSD (Solid State Drive)** => Não tem discos magnéticos. Ele é formado por chips, memórias flashs iguais ao dos pendrives. São nesses chips que os dados são gravados e são lidos, consequentemente o SSD é muito mais rápido que o HD, e por esse motivo ele é bem mais caro. 

<h1>Tópico 06 - Chipset Ponte Norte e Ponte Sul</h1>
<hr>

Na placa mãe existem dois chips que são chamados de chipsets, um é o Ponto Norte e o outro Ponte Sul. Mas, quais são as funcionalidades desses chipsets?

Imagine que temos uma cidade que tem as ruas na qual trafegam carros entre outros veículos, imagine que também tem alguém que organiza esse transito, como por um semáforo. Ele que vai dizer quem vai passar após o sinal e quem não vai.

O chipset é mais ou menos isso, pois é ele quem controla o trafégo de dados dos componentes do computador.

**Chipset norte** => É responsável pelo controle dos dados de componentes mais potentes, tais como Processador, Placa de Vídeo, Memória RAM & etc. </br>
**Chipset sul** => É responsável pelos periféricos mais lentos, tais como Dispositivos conectados na entrada PCI, Periféricos de entrada e saida de dados onboard (Parafusados na placa mãe), HD & etc.

<h1>Tópico 07 - Coolers</h1>
<hr>

Uma peça muito fundamental, pois o computador esquenta demais durante o seu processamento, fazendo com o que o mesmo trave, com o cooler é possível diminuir ou sumir com esse problema.

Temos o dissipador de calor (Cooler AA) que é uma peça que pode ser de aluminio ou de cobre, sendo o de cobre sendo o mais eficiente. A função básica desse dissipador é retirar o calor e passar para a chapa, esse calor por sua vez será passado para a ventoinha de cima que assoprará o calor para longe, consequentemente ajudando na refrigeração da CPU.

<img src="https://images-na.ssl-images-amazon.com/images/I/61Gn5x54MhL._AC_SX466_.jpg" alt="Cooler dissipador de calor">

O Water cooler também é uma boa alternativa para ser colocado no processador, o dissipador dela é instalada em cima do processador onde faz a refrigeração do aparelho e passa o liquido quente pra bombinha onde lá é resfriado. 

<img src="https://http2.mlstatic.com/cooler-dagua-corsair-h55-quiet-cw-9060010-ww-D_NQ_NP_811999-MLB29734488960_032019-F.jpg" alt="Cooler d'agua dissipador de calor">

<h1>Tópico 10 - Conectores de vídeo</h1>
<hr>

**VGA** bem conhecida e bem antiga que é com conexão analógica.

<img src="https://www.dhresource.com/0x0/f2/albu/g10/M01/A0/BB/rBVaWV11LG2AMgcjAAWipy6Ppwk797.jpg/20pc-lot-vga-cable-computer-monitor-video.jpg" alt="Cabos VGA">

**DVI** no qual tem três tipos -> DVI-A, DVI-I, DVI-D:

✔️ DVI-A: Mais antiga com conexão analógica </br>
✔️ DVI-I: Conexão analógica e digital </br>
✔️ DVI-D: Apenas conexão digital </br>

DVI-A e DVI-I podem usar adaptador para VGA.

<img src="https://cirilocabos.vteximg.com.br/arquivos/ids/167084/242090-Cabo-DVI----Modelo-DVI-D-Cirilo-Cabos-1.jpg?v=635521775776630000" alt="Cabos DVI">

**HDMI** é o padrão mais utilizado atualmente, conseguindo transmitir áudio digital além de vídeo digital pelo mesmo cabo. Pode ser convertido o sinal entre DVI-I e DVI-D,

<img src="https://img.kalunga.com.br/fotosdeprodutos/162256z.jpg" alt="Cabos HDMI">


<h2 align="center">📰 Informações</h2>

<h3>📝 Meta</h3>

Eduardo José - [Meu Portfólio](https://duduxs.github.io/portfolio/) 

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

[https://github.com/Duduxs/courses](https://github.com/Duduxs/)

