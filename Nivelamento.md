# Mód 1: Introdução à Segurança da Informação

Níveis de Proteção: particular, corporativo e governamental. 
Dados: classificados como online (@) e offline (nome completo), são elementos cruciais na identificação de usuários. Prioridades de proteção, via de regra.

Hacking: ato de comprometer dispositivos e redes sem autorização, possui diferentes categorias:
- Hacker: Especialista com alto conhecimento.
- Cracker: Cibercriminoso, realiza atividades maliciosas.

Além das categorias, existes as diferentes divisões:
- Black Hat: Atividades não éticas e criminosas.
- White Hat: Práticas éticas e autorizadas.
- Gray Hat: Ética moderada, muitas vezes desafiando limites éticos para fins específicos.
Script Kiddies: Amadores que utilizam scripts prontos.
Hacktivistas: Utilizam hacking para causas políticas ou sociais, muitas vezes associados aos black hats.

### Ética
- A ética na segurança da informação é guiada por um código moral. Lei Geral de Proteção de Dados (LGPD) estabelece princípios e diretrizes para garantir práticas éticas no tratamento de informações pessoais (no Brasil)

- Princípios Éticos: **Confidencialidade, Integridade e Disponibilidade**

### Tipos de Sistemas de Segurança de Rede

- IDS (Intrusion Detection System): Monitora e identifica atividades suspeitas na rede.
- IPS (Intrusion Prevention System): Além de detectar, também previne atividades suspeitas.

### Malwares

- Virus de Macros: Malware que explora macros em documentos para realizar ações maliciosas.
- Payload: Componente malicioso de um malware, responsável por realizar a ação indesejada.
- Trojan: Malware que se disfarça como algo legítimo para enganar o usuário.
- Botnets: Redes de computadores contaminados controlados remotamente para atividades maliciosas.

# Mód 2: Identificar Componentes de Hardware de Computador

**Grandezas Computacionais:** diferentes sistemas numéricos.

- Boole: Criador da álgebra booleana, base para lógica binária em portas lógicas.
- Máquina de Turing: Modelo teórico de computação.
- ENIAC: Primeiro computador eletrônico digital de grande escala, precursor da era da computação digital.

**Unidades de Medida:**

- Bit (b): A menor unidade de informação, representando 0 ou 1.
- Byte (B): Conjunto de 8 bits, fundamental para representação e armazenamento de dados.

**Grandezas Elétricas:**

- Hz: Hertz, unidade de medida de frequência (processadores).
- V: Voltagem, medida de voltagem elétrica.
- A: Ampere, medida de corrente elétrica.
- W: Watt, unidade de potência.

**Grandezas Gráficas:**

- Pixel: Menor elemento em uma imagem digital.
- DPI (Dot Per Inch): Medida de resolução em imagens, representando a quantidade de pontos por polegada.

**Bases Numéricas:**

- Base 10: Sistema decimal, amplamente utilizado na matemática convencional.
- Base 2: Sistema binário, fundamental para representação digital de informações.
- Base 16 (Hexadecimal): Sistema frequentemente utilizado em programação e representação compacta de dados binários.


## Componentes:
- Computadores são formados por conjunto de peças ao redor de um microprocessador, sendo composta pelo processador, placa-mãe, cooler, memória RAM, HD/SSD, fonte e placas off board.

**Processador** 

- CPU: Central processinng unit, processa dados e transforma em informaçãos (componente, e não gabinete)

- Possui frequência (velocidade, clock) medida em heartz. Mais heartz: mais processamentos.  Determina velocidade
- Nucleos: singlecore, dualcore, etc. Determina velocidade
- Cache: memória auxiliar de rápido acesso

- Arquitetura: x86 (32 bits) da CISC, com limite de 4RAM, x64 (64 bits) da CISC, e ARM da RISC (CISC possui instruções mais complexas, com operações complexas em uma única instrução; enquanto o RISC possui instruções mais simples, com conjunto de instruções reduzido, onde cada instrução executa uma única operação)


- Fabricantes: AMD (Ryzen), Intel (Core) e Apple (M), cada uma com diferentes séries e gerações

- Cooler: refrigera processador, consdierar potência do processador x placa-mãe e cooler

**Placa mãe:**
- Facilita  comunicação entre componentes, integra e cordena hardware (diferentes sockets, número de pinos diverge)
- tamanhos de placa: ATX, mATX e ITX
- Dispostivos podem ser internos (onboards) ou externos (offboard)

- Chipseat: "segundo processador". Mais linhas = mais placas. SATA e possibilidade de Overclock

**Memórias:**
- Não Voláteis (não perde informação quando desligado): ROM (programmable, erasable, electrically erasable), flashdrive, SSD, HD; ou voláteis (perde informação quando desligado): RAM, Cache, Video.
- HD, de forma lenta, trasnfere informação para a RAM, que de forma rápida, passa a informação para o processador.
- Sodimm = memória de notebook, memória de vídeo.

**BIOS/UEFI:**
- BIOS (basic input output system, chip na placa-mãe, verifica componentes) x UEFI (unified extensible firmware interface, bios mais moderna).
- Ao ligar máquina, CPU executa ações para inicializar, acessa memória ROM onde está BIOS/UEFI e o executa. Faz um POST se estiver tudo correto, e BIOS/UEFI carrega o OS na RAM.
    - Durante o POST, verifica-se processador, memória, placa de vídeo, USBs conectadas, discos, relógio e se houve alguma alteração.
- Para que o computador funcione precisa-se do OS (software), e os dados gerados e utilizados por esses softwares são armazenados em dispositivos como HDs, CDs, DVDs, blu-rays, Pendrives, Cartões de Memória, SSDs, etc..
    - Pendrives, Cartões SD e micro SD = utilizam memória flash.

- **HD:** disco mecânico, com motor e cabeças de leitura, com gravação magnética. Maior longevidade e custo por GB mais baixo. Menor resistência e velocidade de leitura/gravação
- **Conexão SATA:** (substitui PATA), SATA III 6gb/s.

- **CD:** capacidade de 700MG, associado a música.
- **DVD:** capacidade de 4,7gb, , associado a filmes.
- **Blue-ray:** capacidade de 25gb, associado a filmes/jogos.
    - Normal, High speed, UHS-I e UHS-II
-**SSD:**  solid State drive, armazena de forma eletrónica (NAND FLASH), logo, mais rápido que um HD mecânico, com subtípos (SATA)

## Fonte
- Componente que recebe a energia da tomada e à converte para tensão de funcionamento do computador, transforma corrente alternada em corrente contínua. 

- Padrão ATX (principal), sou SFX e TFX
- Fontes não modulares, semi modular e full modular  (desconectável)
- Conectores floppy, SATA, 6x2 PCLe, 4X4 cpou, 16-pin 12vHPWR, 24 pinos ATX mother board
- Critérios para escolher fonte: CPU, GPU, quantidade de memória e de discos. Calculadora da outervision
- Certificações 80 plus: padrão de eficiência energética, 80% da energia deve ser considerada carga útil
- PFC (Correção do Fator de Potência) melhora o fator de potência do dispositivo, otimizando a eficiência do consumo de energia e diminui dispersão de energia. Pode ser ativo (com componentes eletrónicos) ou passivo. PFC ideal = 1

- Placas offboard: maior desempenho, mais recursos e possível substituição de componentes com defeito. Dispositivos separados que lidam com o processamento gráfico em um computador. 
- GPU (Graphical Processing Unit – podendo ser da intel (arc), da AMD (rx), NVIDIA (rt)), placas de rede, placas de som, Captura de vídeo; Adaptadores, Processadores de IA ou mineração de criptomoedas

**Gabinetes:**
- Tamanho full Tower, Mid Tower e Mini Tower, podendo ser customizados (casemods)

## Instalação de SO:
- Gera-se pendrive bootavel (via Rufus ou Ventoy) com ISO (imagem do sistema operacional), e uma vez no inserida nos dispostivo, acessa-se BIOS/UEFI, e altera-se sequência de boot ou seleciona-se partição de boot rápido.
- Exemplos usado em aula: windows, ubuntu e proxmox (plataforma de virtualização de código aberto que combina virtualização de servidores com base no Kernel-based Virtual Machine (KVM) para máquinas virtuais (VMs) e contêineres com base no Linux Container.)

## Virtualização:
- Máquinas virtuais utiliza melhor todos recursos do hardware

- Através de software, cria-se uma "camada" sobre o hardware
- Hardware ->  OS ->  aplicativos. 
- Dentro da OS, existe interface e Kernel (interpreta e comunica com hardware)

- Tipo 1: Tipo Bare metal, simula o hardware com o Hypervisor, podendo emprestar recursos de maneira mais eficaz, EX: Proxmox, Hyper-V, KVM e ESXi
    - Hardware -> Hypervisor -> VM1 / VM2 / VM3 (diferente particionamentos)
    - Usada para servidores (SQL, WWW, etc), junta servidores em uma única máquina, economizando hardware, energia e  espaço em datacenters,

- Tipo 2 ():
    - Hardware -> OS -> Hypervisor -> vm
    - usa OS, e não hardware, economizando o hardware e tendo maior facilinade, EX: VirtualBox, VMware, e QEMU

- Container: visa virtualizar o S.O (diferente de virtualizar hardware, onde separa-se aplicativos) 

# Mód 3: Internet e camadas de acesso a rede

## História da internet

- Criação ainda na década de 1960. Desenvolvida por agências e financiada pelo *Departamento de Defesa dos Estados Unidos*, visando utilização militar ou acadêmica. A disseminação ocorreu apenas em 1980, com o surgimento da World Wide Web. Popularizou-se em 1990, com o surgimento dos primeiros navegadores e atualmente, é utilizada além do propósito original.
- Primeira geração (1945-1955) composta pelo ENIAC, o primeiro computador eletrónico, em 1945, ainda sem SO.
- Segunda geração (1955 à 1965), com SO, tendo o Unix lançado em 1969, tendo código distribuido em 1970. Sistema operacionais divididos entre livres e proprietários (linux e windows/mac)

- Necessidade militar, teme ataque soviético, departamento de defesa cria ARPA para comunincar informações, via rede descentralizada (previne ataques físicos). Teoria de comunicar pacotes (1961), posteriormente conceito de internet (1962)
- ARPAnet, em 68, com 4 "nós" de comunicação, que funcionam entre sí de forma "independente"
- TCP/IP - 1974 - protocolo usado até hj
- Internet global - 1985
- World Wide web: sistema de distrubição em hipertexto (HTTP), via Tim Berners-Lee 
- 1990: Inicio dos computadores pessoais, e inicio dos buscadores de site (google lançado em 1997)
- RNP surge (Rede Nacional de Pesquisa) em 1989, e comercialização surge no Brasil via EMBRATEL

## Tipos de conexão
- Para acessar internet, provedor é necessário visando acesso externo. Para conexão com internet, é necessário meio físico (ar ou cabo) e tipo de contratação
- Dial Moldem; xDSL; Cabo; PLC; Fibra óptica; Rádio; e Satélite      
- Bytes: Capacidade de armazenamento
- HZ: frequência (quantidade de eventos que ocorre em um determinado tempo)
- Largura de banda: quantidade de dados que a rede suporta, medida em bits por segundo (velocidade da internet, de mofo informal)

**Modem** (internet discada)
- Velocidade de 56 kbits/s. Utilizava linha telefónica, onde era necessário placa de modem para comunicar computador e telefone; e discador de provedor. Conexão instável e de baixa qualidade, com cobrança por tempo (Dialing Progress)

    - Etjermet = 10 Mbit/s
    - Wireless 802.11g = 54Mbits/s
    - Fast Ethernet 100Mbit/s
    - Giga Ethernet 1000Mbit/s
        - **K = 10^3, M = 10^6**

**DSL**
- Digital Subscriver Line, tecnologia utilizada para transmissão de dados via rede relefonica, (evolução do serviço dial-up, da internet discada), linha telefonica fica livre para ser utilizada junto a internet, ondeusa-se parte não utilizada, via FDM ou Echo Cancellation
    - FDM: utiliza-se o espectro livre, onde envio de dados é chamado de **upstream** e o recebimento de dados é chamado de **downstream**.
    - Echo Cancellation: método que sobrepõe upstream e dowstream, mas são separados via calculos de subtração.

- Conversão de sinal pode ser feita via **CAP** ou **DMT**
    - CAP divide linha telefónica em 3 pares, sendo eles: chamada de voz (entre 0Khz e 4Khz); envio de dados(entre 15Khz e 160Khz); e recebimento de dados(240Khz e 1550Khz).
    - DMT faz o mesmo, com diferente faixa de frequência, canal 1 para voz, canal 6 ao 31 para envio de dados, e 32 até 255 para recebinmento de dados. Possui melhor desempelnho e melhor resistência a ruidos.

**Tipos de conexões - xDSL**
- ADSL2 e ADSL2+: melhoria de modulação e eficiência
- HDSL: 1980, transmissão de dados via duas linhas telefónicas,
- SDSL: utiliza um par de dados, com distância menor. Não usa vós e dados ao mesmo tempo
- SHDSL: Maior largura da banda, não usa vós e dados ao mesmo tempo
- VDSL2: Maior largura de banda 

**Internet a cabo**
- Cabo coxial, sofre menos interferência e percorre longas distâncias, apesar da velocidade baixa (10Mbit/s)
- PLC (power line communication) utiliza transmissão via cabo de energia. Um equipamente envia sinal via rede elétrica, e outro recebe. Equipamentos importados (HomePlug), logo, maior custo. Possui rápida distribuição, mas velocidade de conexão relativamente baixa

**Fibra óptica**
- 20 milhões de lares brasileiros, com melhor plano de velocidade, estabilidade, confiabilidade e qualidade, apenas com dificuldade de instalação. 
- Conexão sem fio, feita via protocolos, radio ou satélite. Ondas de radio frequência com antenas recebe e moldem captura sinal para utilização. Necessário receptor de satélite

## LAN_WAN topologias
- Quando se tem mais de um computador se comunicando, forma-se uma rede de computadores, que poder ter diferentes características, podendo ser LAN, MAN, WAN, SAN, PAN, WLAN, WMAN e WWAAN sendo as duas mais utilizadas a LAN (rede local) e a WAN (rede de área ampla)
    - LAN: Local Area Network, compartilha recursos e controla acesso atraves da relação clientes/servidores. Em rede doméstica, via roteador conectado a um moldem; e em rede empresarial, via Switch
        - Para construir uma rede LAN, é necessário levantar a quantidade de computadores; a quantidade de switch; a distância entre os computadores; a quantidade de notebooks; definir acesso sem fio; e ligar o switch em outros dispostivos (configuração dinâmica, via servidor de IP)
    - **MAN:** Metropolitan Area Network, malha de comunicação que cobra uma grande área geográfica (entre 5km à 50km), podendo ser de uso empresarial ou não. A interligação é geralmente feita via fibra óptica, que pode ser alugada ou própria, o que garante uma grande largura de banda. Entretanto, possui maior dificuldade de instalação, operação, e manutenção.
    - **CAN:** Campus Area Network, maior que a LAN mas menor que MAN, possui implementação mais barata, tendo como vantagem o gerenciamento centralizado
    - **WAN:** Wide Area Network, rede de longa distância via internet, ligação é feia via VPN (Virtual Private Network, usada para simular uma mesma rede com acesso criptografado). Necessíta muitos equipamentos.
    - SAN: Storage Area Network, visa armazenamento para grandes equipamentos, conectados geralmente via fibras, e é usado para melhorar disponibilidade e desempenho. Garante **flexibidade, disponibilidade e escalabilidade**
    - PAN: Personal Area Network, visa uso pessoal descentralizado para curta distância (USB e FireWire; ou protocolos como Bluetooth, WiFi, Irda [Infrared Data Association] e Zigbee [Uso industrail])
    - BAN: Body Area Network, dispositivos pequenos ou médios sem fio, podendo ser incorporados ou anexados no corpo, visando fins médicos, militares ou de segurança. Dificuldade de qualidade de dados, sensor, segurança e custo.

**Redes sem fio**
- WLAN (Wirelless Local Area Network): Conexão em área límitada, uso residencial, criação simples (cabo de dados até moldem, moldem para roteador, distribui internet via ar utilizando protocolo 802.11). Melhoras em largura de banda, taxa de simultaniedade, baixa latência e baixo consumo.
- WMAN (Wirelles Metropolitan Area Network): Acesso fora de rede doméstica, uso de APs (Acess Points), via cabo, AP convete
- WPAN (Wireless Personal Area Network): Rede pessoal sem fio (bluetooth, viva-voz). Conecta-se a protocolos, zomo Zigbee. Associado a IOT
- WWAN (Wireless Wide Area Network): Redes de tecnologias de celular, visa aplicações telefónicas. Tem como principa uso o acesso a internet (Via torres). 

**Topologias de rede**
- Formato como a rede é definida, diferentes tipos.
    - Point to point (ponto a ponto): Rede com computadores interligados via meio. Ex: Cabo crossover. Compartilham informações entre eles
    - Bus (Barramento): Rede antiga e mais barata, iniciada com cabo no inicio até o fim da rede, via cabo coxial e divisores de sinal. Caso um nó pare, todos parem (Rede continua)
    - Ring (Anel): Computador com placas de rede se conectam a outros computadores. Imune a falhas ao nós parem de se comunicar (outra direção, a menos que dois ou mais nós sejam danificados). Rede mais cara, geralmente utilizada em fibra óptica
    - Estrela (Star): Mais utilizado, rede central gerencia, falha em um nó prejudica apenas um dispositivo . Custo aceitável, mas se o nó central parar, toda rede para.
    - Árvore (tree): Facilidade para adicionar novo dispositivo, possibilidade de erro no dispositivo de distribuição
    - Mash (Malha): Ring + Star, todos dispostivios se comunicam. Quase imune a falhas, alta disponibilidade. Díficil aplicação e alto custo
    - Hybrid (Híbrida): Combinação das anteriores

**Intranet/extranet**
    - Cada um com um sistema de segurança diferente;
    - Internet: Visa navegar por conteúdos externos, devido rede global de computadores
    - Intranet: Rede local privada, onde somente pessoas autorizadas podem acessar. Usada para compartilhar dados empresarialmente, via de regra. Acesso controlado via email, senha ou IP.
    - Extranet: Rede privada interna que pode ser acessada de forma remota, pode ser usada para segurança de rede. Entre a internet e a extranet.
        MFA = Multiplo fator de autentificação, visa segurança na Extranet, para o acesso remoto. 
**Ativos de rede**
- Ativos: Equipamentos responsáveis por converter sinais elétricos e ópticos em dados. Gerenciam tráfego (Hubs, Switches, Roteadores, Placas deRede, Firewall, etc)
    - **Hub:** Interliga equipamentos, faz broadcast (ao enviar dado, todas máquinas recebem). Pode ser passivo ou ativo. Ativo regenera e repete o sinal (+100m), enquanto pássivo não. Muitos hubs levam a colisão de pacotes. prejudicando a rede.
    - **Switches:** Um dos principais componentes, similar ao hub, trabalha com mais portas (24 ou 48 portas). Trabalha com MAC Adress. Modelos não gerencíaveis não possuem regras de acesso, enquanto gerencíaveis possuem funcionalidades mais avançadas, permitindo configurações de segmentação de refe (Divisão virtual de rede). Diferente do hub, switch gerencia quais informações devem ser enviados para máquinas específicos (Tabela MAC)
    - **Roteadores:** Com ou sem fio, ncaminha dado em camadas diferentes, e conecta diferentes redes. Trabalha com IP e serve para encaminhar os dados entre redes. Possuem slots para expansão. Similar a Switch, mas *interliga mais de uma rede*.
    - **Placa de rede**: Dispositivo que interliga equipamentos desktop aos demais equipamentos, pode ser fixa na motherboard ou via usb. Para conexão de rede, placa deve ter IP (Internet Protocol), podendo ele ser fíxo (colocado manualmente) ou dinámico (servidor de **DHCS**). Pode ser verificado via terminal através do PING (ICMP), se houver resposta, máquina está ativa. 
        - Firewall: Hardware / Software que separa rede interna de rede externa, tendo como objetivo proteger as ameaças externas para proteger a interna.
            - Filtragem de pacote: Trata  os pacotes de entrada e saída, onde examina e testa cada pacote (via regra definida pelos admins via protocolos, portas, e endereço de destino). Caso não atenda os requisitos, ele é descartado.
                - Filtragem de pacote estático: Definição de regras fixas e manuais. Define-se portas, lista de acesso, e endereços de IPs. Pouco utilizado.
                - Filtragem de pacote dinámico: Configurações via tempo de serviço aberto, após tempo, se fecha.
                - Filtragem de pacote estável: Conexão via extensões modernas ativas, ao reconhecer entrada, identifica melhor tráfico convencional e malicioso.
            - Firewall de aplicação: Desenvoldio para atacar diretamente aplicações específicas, geralmente WEB (Web Aplication File). Visa manter aplicação segura. Escalabilidade
                - Firewall de aplicação de rede
                - Firewall de aplicação host (baixo custo, alta complexidade, cada computador)
                - Firewall de aplicação em nuvem: Gerenciado pelo provedor
            - Inspeção de estado: Inspeciona dados, procurando padrões baseados nas regras.

**Conectividade:**
- 



