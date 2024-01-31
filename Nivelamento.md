# Introdução à Segurança da Informação

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

# Identificar Componentes de Hardware de Computador

Grandezas Computacionais: Diferentes sistemas Numéricos

- Boole: Criador da álgebra booleana, base para lógica binária em portas lógicas.
- Máquina de Turing: Modelo teórico de computação.
- ENIAC: Primeiro computador eletrônico digital de grande escala, precursor da era da computação digital.

Unidades de Medida:

- Bit (b): A menor unidade de informação, representando 0 ou 1.
- Byte (B): Conjunto de 8 bits, fundamental para representação e armazenamento de dados.

Grandezas Elétricas:

- Hz: Hertz, unidade de medida de frequência (processadores)
- V: Voltagem, medida de voltagem elétrica.
- A: Ampere, medida de corrente elétrica.
- W: Watt, unidade de potência.

Grandezas Gráficas

- Pixel: Menor elemento em uma imagem digital.
- DPI (Dot Per Inch): Medida de resolução em imagens, representando a quantidade de pontos por polegada.

Bases Numéricas

- Base 10: Sistema decimal, amplamente utilizado na matemática convencional.
- Base 2: Sistema binário, fundamental para representação digital de informações.
- Base 16 (Hexadecimal): Sistema frequentemente utilizado em programação e representação compacta de dados binários.

Computadores são formados por conjunto de peças ao redor de um microprocessador, sendo composta pelo processador, placa-mãe, cooler, memória RAM, HD/SSD, fonte e placas off board

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

**Memórias**
- Não Voláteis (não perde informação quando desligado): ROM (programmable, erasable, electrically erasable), flashdrive, SSD, HD; ou voláteis (perde informação quando desligado): RAM, Cache, Video
- HD, de forma lenta, trasnfere informação para a RAM, que de forma rápida, passa a informação para o processador.
- Sodimm = memória de notebook, memória de vídeo.

**BIOS/UEFI**
- BIOS (basic input output system, chip na placa-mãe, verifica componentes) x UEFI (unified extensible firmware interface, bios mais moderna)
- Ao ligar máquina, CPU executa ações para inicializar, acessa memória ROM onde está BIOS/UEFI e o executa. Faz um POST se estiver tudo correto, e BIOS/UEFI carrega o OS na RAM 
    - Durante o POST, verifica-se processador, memória, placa de vídeo, USBs conectadas, discos, relógio e se houve alguma alteração
- Para que o computador funcione precisa-se do OS (software), e os dados gerados e utilizados por esses softwares são armazenados em dispositivos como HDs, CDs, DVDs, blu-rays, Pendrives, Cartões de Memória, SSDs, etc

- HD: disco mecânico, com motor e cabeças de leitura, com gravação magnética. Maior longevidade e custo por GB mais baixo. Menor resistência e velocidade de leitura/gravação
- Conexão SATA (substitui PATA), SATA III 6gb/s

- CD: capacidade de 700MG, associado a música
- DVD: capacidade de 4,7gb, , associado a filmes
- Blue-ray: capacidade de 25gb, associado a filmes/jogos

Pendrives, Cartões SD e micro SD = utilizam memória flash
- Normal, High speed, UHS-I e UHS-II
-SSD:  solid State drive, armazena de forma eletrónica (NAND FLASH), logo, mais rápido que um HD mecânico, com subtípos (SATA)

- M Key - NVMe
- B + M Key - SATA

Fonte: componente que recebe a energia da tomada e à converte para tensão de funcionamento do computador, transforma corrente alternada em corrente contínua. 

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

**Instalação de SO**
- Gera pendrive bootavel (rufus ou ventoy) com ISO (imagem do sistema operacional),  inserir no dispostivo,acessar BIOS/UEFI, e alterar sequência de boot/selecionar partição de boot rápido
- Exemplos usado em aula: windows, ubuntu e proxmox (plataforma de virtualização de código aberto que combina virtualização de servidores com base no Kernel-based Virtual Machine (KVM) para máquinas virtuais (VMs) e contêineres com base no Linux Container.)

*Virtualização*
- Máquinas virtuais utiliza melhor todos recursos do hardware

- Através de software, cria-se uma "camada" sobre o hardware
- Hardware ->  OS ->  aplicativos. 
- Dentro da OS, existe interface e Kernel (interpreta e comunica com hardware)

Tipo 1: Tipo Bare metal, simula o hardware com o Hypervisor, podendo emprestar recursos de maneira mais eficaz, EX: Proxmox, Hyper-V, KVM e ESXi
- Hardware -> Hypervisor -> VM1 / VM2 / VM3 (diferente particionamentos)
- Usada para servidores (SQL, WWW, etc), junta servidores em uma única máquina, economizando hardware, energia e  espaço em datacenters,

Tipo 2 ():
- Hardware -> OS -> Hypervisor -> vm
- usa OS, e não hardware, economizando o hardware e tendo maior facilinade, EX: VirtualBox, VMware, e QEMU

- Container: virtualiza S.O (diferente de virtualizar hardware, separa aplicativos) 

# Internet e camadas de acesso a rede

## História da internet

- Criação ainda na década de 1960. Desenvolvida por agências e financiada pelo *Departamento de Defesa dos Estados Unidos*, visando utilização militar ou acadêmica. A disseminação ocorreu apenas em 1980, com o surgimento da World Wide Web. Popularizou-se em 1990, com o surgimento dos primeiros navegadores. 
- Atualmente, é utilizada além do propósito original
- ENIAC - primeiro computador eletrónico - 1945, primeira geração (1945-1955), sem SO
- Segunda geração (1955 à 1965), com SO
- Unix lançado em 1969, tendo código distribuido em 1970

- Sistema operacionais divididos entre livres e proprietários (linux e windows/mac)

- Necessidade militar, teme ataque soviético, departamento de defesa cria ARPA para comunincar informações, via rede descentralizada (previne ataques físicos). Teoria de comunicar pacotes (1961), posteriormente conceito de internet (1962)
- ARPAnet, em 68, com 4 "nós" de comunicação, que funcionam entre sí de forma "independente"
- TCP/IP - 1974 - protocolo usado até hj
- Internet global - 1985
- World Wide web = sistema de distrubição em hipertexto (HTTP), via Tim Berners-Lee 
- 1990 = computadores pessoais, buscadores de site (google lançado em 1997), em 1989 RNP surge (Rede Nacional de Pesquisa). Comercialização via EMBRATEL

## Tipos de conexão

