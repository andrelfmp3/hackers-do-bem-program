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
- Transição do analógico para o digital
    - Analógicos: mais simples, apenas entre dispostivos do mesmo tipo (radio analógico transmite apenas voz)
    - Digital: mais complexo, dobro de capacidade, e transmite mais que apenas a voz. Melhor bateria, qualidade de transmissão, e segurança (criptografia)

- O processo de comunicação digital envolve a conversão de informações analógicas em dados digitais por meio de amostragem e quantização, seguida pela modulação dos sinais digitais em uma forma de onda adequada para transmissão, codificação no canal para detecção e correção de erros durante a transmissão e, por fim, demodulação para recuperar os dados originais no receptor. 

Transmissão de dados: transferência de bit de informação de um ponto a outro, seja local ou global.
    - Tranmissão: de onde sai a informação;
    - Receptor: onde chega a informação;
    - Canal: meio de transmissão da informação;
    - Protocolo: regra para que comunicação seja estabelecida;
    - Código e contexto importam;

- Tipos de transmissão:
    - Serial: um bit de cada vez
        - Síncrona: baseada no tempo de transmissão. Ao vivo, com equipamentos conectados ao mesmo tempo (programa ao vivo televisão)
        - Assíncrona: baseada na velocidade de transmissão. Gravada, com equipamentos não necessariamente conectados (filme na televisão)
    - Paralela: envia mais bits (mais rápido), onde é necessário mais cabos (mais cabos = maior interferência eletromagnética)

- Conectividade: três tipos de modos de transmissão
    - Simplex: fluxo único, relação emissor e receptor (unidireciona, ex: televisão)
    - Half Duplex: fluxo duplo (multidirecional) não simultaneo;
    - Full Duplex: o mais rápido. fluxo duplo e simultâneo

- Comunicação ponto a ponto
    - Duas antes que fazer a comunicação direta apenas entre sí (diferente da multiponto)
        - Protocolo PPP (point point protocol), camada dois de enlace de dados. Autentificado via PAP e CHAP. PPPOE e PPPOA
    - Verificador de erros:VRC, LRC, CRC e Checksum.

- Portar lógicas: sistemas binários, analisa bits e retorna saída baseado na porta lógica
    Portas: AND, OR e NOT; NAND e NOR; e XOR (entradas diferentes == true) e XNOR (entradas iguais == true)

- Verificador de erros usa porta XOR por padrão
    - VRC (Verificador de Redundância de Paridade):
        - Adiciona-se um bit adicional para cada conjunto de dados enviado.
            - Verificação Par: Adiciona-se 0 se o número de "1" no conjunto de dados for par.
            - Verificação Ímpar: Adiciona-se 1 se o número de "1" no conjunto de dados for ímpar.

    - LRC (Longitudinal Redundancy Check):
        - Um único bit de paridade é adicionado aos dados.
            - O bit de paridade é calculado com base na soma dos bits de dados.
            - Exemplo: Para um conjunto de dados de 4 bits (1010), a soma dos bits de dados (1 + 0 + 1 + 0 = 2) determina o bit de paridade.
            - Se a soma for par, o bit de paridade será 0; se for ímpar, será 1.

    - CRC (Cyclic Redundancy Check):
        - Dividida em etapas de envio, divisão e cálculo do valor final.
            - Utiliza um polinômio gerador para calcular um valor de verificação de redundância cíclica.
            - Altamente eficaz na detecção de erros em transmissões de dados.

    - Checksum:
        - Baseia-se na soma dos dados, considerada mais confiável.
            - Lado Emissor: Gera o checksum através da soma dos dados em blocos.
            - Receptor: Verifica os dados considerando o checksum, que é o valor final da soma da informação em blocos.

**Par metálico**
- Placa de rede (network interface card) recebe cabo de rede, fazendo conexão. Endereço de IP e MAC necessários. Possui velocidade variável e diversos tipos de conexão diferentes (PCI, PCI Express, USB, para aqueles sem placas de rede; e Thunderbold, para melhor velocidade da USB etc)
    - Cabo coaxial: Usado em TV a cabo e em rede de relecomunicações. Voltado para video e audios. Cabo de cobre com isolante, para ser imune a interferências eletromagnéticas. Possui conectores específicos.  
    - Cabo de par trançado: Cabo mais utilizado em redes de computadores (barato, flexível, fácil manutenção e maior taxa de transferência de arquivos), mas possui comprimento máximo de 100 metros e alta sensíbilidade a interferências.
        - Cat 1: Redes telefonicas e redes antigas, não mais reconhecidas
        - Cat 2: Redes telefonicas e redes antigas, não mais reconhecidas
        - Cat 3: Específico para redes, até 16Hmhz
        - Cat 4: Transmissão de dados a 20Mhz, não mais reconhecida
        - Cat 5: Substitui categoria 4, qualquer placa de rede se conecta
        - Cat 5e: Reconhecida pela TIA, suporta 125Mhz
        - Cat 6: Alcance de 155m, com dados até 250Mhz
        - Cat 6a: Até 100m, suporta 500MHz
        - Cat 7: Ainda em desenvolvimento, visa 100Gbits em cabos de 15m

**Fibra**
- Alta largura de banda, utilizado no meio industrial e medicinal, mas com alto valor de instalação (reflexão total interna da luz). Segura e de longa distância. A manutenção preventiva inclui inspeção visual, limpeza, teste de qualidade e gestão de cabos. Já a manutenção da fibra óptica envolve preparação, alinhamento e fusão.
- Possui núcleo e revestimento, diâmetro, índice de refração, flexibilidade e imunidade à interferência.
    - Monomodo: apenas um modo (ou caminho) de luz viaja através do núcleo da fibra. feixes de luz se propagam em linha reta pelo centro da fibra, sem sofrer dispersão. Voltada para longas distâncias e alta velocidade, pois oferece baixa atenuação e baixa dispersão, permitindo que os sinais sejam transmitidos por maiores distâncias com menos perda de sinal. Geralmente é mais cara de implantar.
    - Multimodo: Na fibra óptica multimodo, vários modos de luz viajam através do núcleo da fibra, refletindo-se internamente nas paredes do núcleo, resultado em uma dispersão modal e causando um alargamento no pulso óptico. A fibra multimodo é usada principalmente em distâncias curtas e redes locais devido à sua maior dispersão e atenuação em comparação com a fibra monomodo. Geralmente é mais econômica.

Em resumo, a fibra óptica monomodo é usada para transmissões de longa distância e alta velocidade, enquanto a fibra multimodo é mais comum em distâncias curtas e redes locais. A escolha entre os dois tipos de fibra depende das necessidades específicas de uma aplicação, incluindo distância, largura de banda e custo.
- Fusão de fibra: feita quando a fibra se rompe.

**Redes sem fio**
- Sem conexão física, normalmente utilizando ondas de radio. Mobilidade e facilidade de instalação
    - Wi-fi: Utilizado em redes locais. Possui padrão de internet 802.11, com alto alcance, segurança e conexão de múltiplos dispositivos. 
        - Padrão 802.11 define características, sendo o primeiro padrão lançado. Possue outras versões, como a 802.11a; 802.11b; 802.11g; 802.11n e 802.11ac.
    - Bluetooth: Conectividade de curto alcance para dispostivios pessoaais. Utiliza sinais de rádio de curto alcance (2,4Ghz). Podem operar em diferentes canais de comunicação e possui curto alcance (100m, para versão 5.0 em condições ideias)
    - 3g, 4g e 5g: Dispositivos moveis com alta velocidade de conexão, cada uma com características técnicas diferentes.

# Acesso a rede e camada de internet (IP)

**Camada de acesso**
- Processo da comunicação tem 5 elementos: emissor, receptor, mensagem, canal, e código. Conceito é valido para comunicação entre dispostivos de redes, onde o protocolo é o processo padrão (ex: tcp/ip).
    - Aplicações: mesmo em dispostivos diferentes, a aplicação não deve-se alterar (funciona em diferentes dispositivos)
    - Transporte: tcp e udp, por exemplo, tem diferentes formas de trabalhar.
    - Internet: Conectividade, com protocolos de rede.
    - Acesso à rede: Permite comunicação eficaz.

- Modelo TCP/IP e modelo OSI (camada 1 e 2)
    - Modelo OSI possui interação entre camadas.

- Os padrões da canada de acesso são diferentes no Modelo OSI e no Modelo TCP/IP. Esses padrões são determinados por algumas entidades e organizações, que se baseiam se os modelos são físicos ou não. Possuem padrões de camada de acesso a rede padronizados.
    - IEEE divide enlace em Controle de enlace lógico e controle de acesso ao meio 
- Na camada física (camada 1 modelo OSI), trata-se os bits, transmissão de dados, e meios de transmissão. Lida com taxa de trsnferência, largura de bbanda e latência.
- Na camada de enlace (camada 2 do modelo OSI) trata da interação da rede e do hardware, detecção e correção de erros de tranmissão, comunicação dos nós de redes (enlace)
- PDU (Protocol Data Unit) é alterado conforme é processado pelo protocolo
    - Na cama de enlace e física define-se o padrão ethernet (como os dados são transmitidos no padrão de comunicação através do cabo de rede)
- Dependendo da camada, dispostivos diferentes operam. 


**Endereço MAC e tráfego de Dados**
- Endereço MAC (Media Access Control): identificador exclusivo, associado à interface de rede de um dispositivo. Funciona com um número de série de 48 bits e pode identificar um dispositivo de rede Ethernet ou Wi-fi. è uma sequência alfabunéria com formato específico (geralmente seis pares de caracteres hexadecimais; sendo três o identificador único do fabricante, e os outros três o número de série do dispositivo)
- MAC Address é utilizado na camada de enlace no modelo OSI (camada 2) para encaminhar as informações 
- Comunicação não funciona em rede se MAC Address for igual
    - Comunicação Unicast (1 para 1), enlace associa endereço do  disposiivo de saída com endereço do dispositivo de chegada, e switch direciona.
    - Comunicação  Broadcast (1 para todos), envia para todos, não especificando endereço do dispositivo  de chegada.

Comunicação de ativos na camada 1 e 2 (hub e switch)
- Camada 2 usa MAC Address, e camada um apenas bit
    - Switch lê quadros  e seleciona redes (via MAC Address, enquanto hub não seleciona)
    - Switch desencapsula, Lê, e se informação estiver, encaminha corretamente.

**Protocolo ARP** (funcionamento baseado no modelo OSI)
- ARP (Address Resolution Protocol) mapeia endereços IP para Endereços Mac em redes locais, conectando um ip em constante mudança a um endereço físico
- Modelo OSI possui diversos tipos de endereço em diferentes tipos de camada
- Dispositivo gera frame, e compara com todos dispositivos de destino, até algum deles responder a requisição, devolvendo seu MAC address

**Endereçamento IPV4**
- Acesso a internet requer conexão física e lógica
- IPV$ é composto por 4 octetos separados por pontos, onde cada octeto é composto por 8 bits e varia de 0 a 255 (256 em decimal fornece 9bits)
- Número padronizado via IETF, IEE e IANA
- Um endereço IP dinâmico é atribuído temporariamente a um dispositivo em uma rede e pode mudar ao longo do tempo, enquanto um endereço IP estático é fixo e permanente para um dispositivo específico.
- Máscara de rede: determina como os bits em um endereço IP são dividios entre a identificação da rede e a identificação do host. Critérios do endereço IP seguem válidos
- Endereço Ip + máscara de rede determinam em qual rede o dispositivo pertence
- Divisão de endereçamentos: de A a E, sendo D e E reservados, sendo D reservados apenas para multicast.
- Endereços de rede final 255 é usado para broadcast, e 0 é endereço de rede (varia conforme máscara começa / termina )
- Ex: endereço /24, (três primeiros octetos ligados, )

**IP público, privado, e NAT**
- LAN: Endereço privado, IPs podem ser iguais, 3 ranges (inicio 10, 172, e 192)
- WAN: Endereço público (provedor de internet), IPs exclusivos (pode esgotar)

- NAT (Network Address Translation): converte/traduzi IPs

**Sub-redes**
- Isolar enderaçamento das redes sem segmentação física
- Prática de subdividir rede em duas redes, ao invés de rede principal + uma rede dividida
- 256 (2⁸) segmentado, vira duas redes de 128 (2⁷) (128 - 2 = 126)
- Máscara determina onde começa e onde termina
- Não é possível criar três sub-redes, apenas 4 (precisa ser múltiplo de 2, onde 2¹ é 2 redes, e 2² é 4 redes, ficando com 64 hosts em cada)

**Super-redes**
- Ao invés de dividir, aglomera e combina, tendo maior capacidade para mais dispositivos
- Rede é limitada por 254 IPs válidos (e 2 inválidos), devido a 2⁸
- Usasse 9 bits para ampliar (dobro de dispositivos), chegando a 522 hosts, usando bit de outro octeto. Ex: 255.255.254.0 
    - Broadcast (ip final) se altera, devido a quantidade/limite de IPs válidos se alterar

# Compreender IPV6 e camada de transporte
- IPs são usados para rotear dados entre os dispositivos, permitindo que pacotes de informação encontrem seu caminho correto. Também usados para identificar a localização aproximada de um dispostivo na rede.
- Fundamental que todas redes locais sejam identificadas numéricamente com o "endereço IP"
- Para acesso a internet, necessita-se
    - Acesso a rede mundial
    - Endereço de rede (IP)
- IPv6 vem substituido o IPv4 (versão mais comum)
    - IPv4 é composta por quatro conjuntos de números decimais, variado de 255 (8bytes), esgotados em aproximadamente 2011
    - IPv6 mais moderno, tendo suas técnicas básicas desenvolvidas na decada de 90 no IETF
- IANA cordena endereçamento (entidade global), tanto IPs quantos sites que se traduzes para IPs, distribuindo blocos de endereço para regiões (registros regionais de internet, o Brasil, LACNIC)
- Para acesso a internet, o provedor disponibiliza um IP público (estão acabando, IPs privados são repetiçãos dos IPs públicos)
- IPv6 suporta 128bits, conectando múltiplos aparelhos simultaneamente. Além disso, possui expansão das capacidades de dereçamento, autentificação e privacidade, autoconfiguração, e simplificação do cabeçalho
- Composto por 8 hexadecatetos, com 16 bits cada hexadecateto (4 algarismos tem 16 bits)

**Cabeçalho IPv6**
- Cabeçalho IP é uma informação apresentada no início de um pacote de protocolo de internet.
- Comunicação em modelos de camada (OSI) 
- Cabeçalho = bits, dados com binários (aumentos do quem tem que ser transmitido)
- Em cada salto na rede os cabeçalhos são acrescentados e retirados
    - Salto: Cada vez que um pacote é encaminhado de um roteador para outro
- Cabeçalho IPv6 tem 8 campos fixos, 40 Bytes de tamanho 
- Possui versão do protocolo
- Mais simples, mais flexível e mais eficiente

**Tipos de endereço**
- Métodos de comunicação entre IPv4 e IPv6: unicast; anycast; broadcast e multicast
    - Unicast: um para um, é um enderaçmento para um pacote feito a um único destino, sem interação com otro dispositivo
    - Anycast: Feita de uma interface para muitas outras (**na mesma região**). Cada dispositivo anuncia o mesmo endereço de rede.
    - Multicast: Dispositivo se comunica com alguns receptores, é o método de transmissão de pacote de dados para múltiplos utilizado pelo IPv6
    - Broadcast: Método de transmissão simultanea para diversos receptores, usado especificamente no IPv4, transmissão criteriosa
- Tipos de endereços em IPv6:
    - link local: 1 para 1, endereço configurado automaticamente 

    - global unicast address: exclusivo, similar ao IPv4 público
    - multicast: roteador manda informação para grupo de roteadores
    - loopback: abre o próprio ip, próprio emdereço (ping == autoteste)

    IPv6 na prática
    - Cabos de energia (geralmente pretos), de rede (geralmente vermelhos), e de console (geralmente azul) 
        - link local IPv6 é atribuido dinamicamente e configurado manualmente (cada ponta)

**Abreviações do endereço IPv6**
- Visando ter mais possibilidades, IPv6 complica gerencialmento por ser um número muito grande, abreviação é necessário
    - Grande quantidade de zeros pode ser omitidas por ::
        - Some ou "de um lado" ou "de outro"
    -0099 vira 99 (corta-se zeros)

**Sub-redes IPv6** 
- prefixo /64 identifica (comprimento do prefixo da sub-rede), onde os primeiros 64bits são para rede, e o resto para hosts (64 é apenas exemplo)
- Segmenta-se ultimo hexadecadeto dos dedicados para rede (no exemplo de /64, o quarto grupo de 16 bits)
- Para quebrar o /64 em dois /65.
    - Usa-se um caractere "emprestado" da parte de host (64 bits + 1 bit emprestado), e divide-se o /65 em 2 (/64 dividida foge dos padrões)
        - Divide-se de 0000 até 7fff, e de 8000 até ffff
- Com um bit emprestado, as redes pulam de 8 em 8; com dois bits, pula de 4 em 4; e o padrão se mantem

**Camada de transporte**
- Responsável pela transferência de dados entre máquinas, independentemente da configuração de rede utilizada
- Firewall barra camada de transporte, via portas
- Segmenta dados das camadas superiores
- Mentem e monitora várias comunicações entre aplicações
- Serviços usam porta padrão (ftp, ssh, telnet, smtp, dns, tftp, https, snmt)

**Protocolo TDP**
- Transport Control Protocol
- Confirma e retransmite dados, garantindo que a informação de um dispositivo chegue no outro dispostivo
- Depende do IP para se comunicar. TCP é usado quando se necessita de confiabilidade.
- Remonta segmentos no destino na ordem correta
- Estabelecimento de conexão em 3 vias (pergunta, recebe, envia)
- Faz controle de fluxo para não sobrecarregar o sistema (janelamento)
    - Capacidade do TCP de controlar o fluxo de dados entre remetente e receptor.

**Protocolo UDP**
- User Datagram Protocol
- O protocolo UDP foi projetado para facilitar e fornecer comunicação rápida entre dispositivos em redes IP.
- Não realiza controle de fluxo (não tenta ajustar a taxa de transferência com base na capacidade da rede) 
- O UDP é um protocolo de transporte rápido e eficiente, adequado para aplicativos em que a velocidade e a baixa latência são mais importantes do que a garantia absoluta de entrega de dados. 

# Compreender camada de aplicação / serviços de rede

**Email**
- Serviço da camada de aplicação pupular, projeto que iniciou modelo OSI e internet (projeto ARPANET)
- Serviço de hospedagem de emails (email -> provedor -> servidor -> destinatário)
- Suporta protocolos via SMTP (envia email), POP3 e IMAP (recebe emai)
    - SMTP: Simple Mail Transfer Protocol, exige cabeçalho, utiliza-se porta 25. Armazena mensagens a ser enviadas, em fila, se não for entregue, a mensagem é devolvida ao remetente.
    - POP3: envia do servidor para cliente, e exclui. Usa-se porta 995 (antes 110, mas 995 possui criptografia), solita conexão TCP com servidor.
    - IMAP: envia do servidor para cliente, e se mantem até serem excluidas manualmente. Ideal para backup. Hierarquia de arquivos possível. Permite acesso de diferentes dispositivos

    **Web**
- HTML, WWW e HTTP
- Navegador, na camada de aplicação visando usa comum, URL estabelece conexão com servidor web, que está em execução em um servidor que utiliza o protocolo HTTP
    - Navegador interprete o protocolo (HTTP), o nome do servidor (www.exemplo.com), e depois o nome do arquivo solicitado (index.html)
        - DNS mapeia o nome de domínio para endereços IP
    - Navegador verifica no servidor de nomes, para converter o nome do servidor para um IP válido
    - Em resposta, servidor envia o código HTML
    - NAvegador decifra o HTML e formata a página
- HTTP é um protocolo de requisição e resposta (específica mensagens usadas na convesação), podendo utilizar get, post e put
    - GET: solicita dados feitos pelo cliente
    - POST: carrega arquivod de dados de um servidor web (dados)
    - PUT: carrega recursos ou conteúdos (imagens, videos)
- HTTPS = HTTP + security, com fluxo de dados criptografado com SSL, utilizando portas 443 ou 8448, ao invés de 80 ou 8080. HTTP é menos seguro, mas mais flexível










