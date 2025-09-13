# Teste de penetração

O teste de penetração (pen testing) é um método de testar áreas de fraquezas em sistemas usando várias técnicas maliciosas. Um teste de penetração simula os métodos que um invasor usaria para obter acesso não autorizado a uma rede e comprometer os sistemas, além de permitir que uma empresa entenda como toleraria um ataque real.

É importante observar que o pen testing não é o mesmo que teste de vulnerabilidade, que apenas identifica possíveis problemas. O teste de caneta envolve invadir um site, rede ou servidor com a permissão de uma empresa para tentar obter acesso a recursos usando vários métodos que os hackers black-hat da vida real usariam.

Um dos motivos principais por que uma empresa usa o pen testing é encontrar e corrigir todas as vulnerabilidades, antes dos criminosos virtuais. Testes de penetração são também conhecidos como ataque ético de hacker.


### Níveis de pen testing

  * **O teste de caixa preta** é o menos demorado e mais barato.
      * Ao realizar o teste de caixa preta, o especialista não tem conhecimento do funcionamento interno do sistema e tenta atacá-lo do ponto de vista de um usuário regular.
  * **O teste de caixa cinza** é uma combinação de caixa preta e teste de caixa branca.
      * O especialista terá algum conhecimento limitado sobre o sistema, então é um ambiente parcialmente conhecido, o que dá alguma vantagem a essas tentativas de invasão.
  * **O teste de white box** é o mais demorado e mais caro, porque é realizado por um especialista com conhecimento de como o sistema funciona.
      * É, portanto, um ambiente conhecido quando eles tentam invadi-lo, emulando um ataque mal-intencionado por alguém de dentro ou por alguém que tenha conseguido obter essas informações antecipadamente, na fase de reconhecimento.


# Fase de penetração

### Há quatro fases que compõem um teste de penetração.

**Fase 1**: Planejamento
Estabelece as regras de compromisso para a realização do teste.

**Fase 2**: Descoberta
Realização de reconhecimento sobre o alvo para obter informações. Isso pode incluir:
  -  Técnicas passivas, que não exigem engajamento ativo com o sistema de destino e são conhecidas como footprinting, por exemplo, você pode consultar o site da empresa ou outras fontes públicas para obter informações.
  -  Reconhecimento ativo, como varredura de porta, que requer o envolvimento ativo com o alvo.

**Fase 3**: Ataque
Nessa fase, você procura obter acesso ou penetrar no sistema usando as informações coletadas na fase anterior. O testador tenta obter privilégios escalados e talvez se aprofundar na rede por meio de movimento lateral. Para se mover lateralmente pela rede, o testador deve girar em vários sistemas. O testador pode tentar instalar ferramentas adicionais ou plantar uma backdoor 
  - Esse processo é conhecido como persistência. O testador limpará o sistema, removendo as placas deixadas para trás.

**Fase 4**: Geração de relatórios
Nessa fase, o testador entrega à empresa documentação detalhada que inclui as vulnerabilidades identificadas, as ações tomadas e os resultados.


-----------------------------------------------------------------------------------

## Tipos de exercícios
Algumas empresas criam equipes concorrentes para realizar exercícios de penetração mais longos do que um teste de penetração.

Por exemplo, nesse cenário, podem haver três ou quatro equipes:

  * O time vermelho é o adversário, tentando atacar o sistema sem passar despercebido.
  * Os membros da equipe azul são os defensores e eles tentam frustrar os esforços da equipe vermelha.
  * A equipe branca é uma equipe neutra que define os objetivos e as regras e supervisiona o exercício. Os membros da equipe branca são menos técnicos, mas possuem conhecimento sobre governança e conformidade. A equipe branca é o árbitro deste exercício.
  * Às vezes, há também uma equipe roxa, na qual os membros da equipe vermelha e azul trabalham juntos para identificar vulnerabilidades e explorar maneiras de melhorar os controles.


### Analisador de pacotes
Os packet analyzers (ou analisadores de pacotes) interceptam e registram o tráfego de rede. Eles executam as funções abaixo - para fins legítimos, como solução de problemas, ou fins ilegítimos, como comprometer dados:

  * Análise de problemas de rede
  * Detecção de tentativas de invasão da rede
  * Isolamento do sistema explorado
  * Log de tráfego
  * Detecção de uso indevido da rede


<img width="555" height="485" alt="image" src="https://github.com/user-attachments/assets/bbb9916d-d541-40a5-8820-b6a7936e0512" />


### Saída do analisador de protocolo

Sniffing é semelhante a espionar alguém.

Eles ocorrem quando os invasores examinam todo o tráfego de rede à medida que passa pela placa de rede, independentemente de se o tráfego é endereçado a eles ou não. Os criminosos conseguem fazer sniffing de rede com um software, hardware ou uma combinação dos dois.

Como mostrado na figura, o sniffing visualiza todo o tráfego de rede ou atinge um protocolo específico, serviço ou até mesmo uma sequência de caracteres, como um login ou senha. Alguns sniffers de rede observam todo o tráfego e modificam o tráfego parcial ou totalmente.

A segurança física é importante para evitar a entrada de sniffers na rede interna mas sniffing não é somente usado com objetivos maliciosos. Os administradores de rede também podem usar sniffers para analisar o tráfego de rede, identificar problemas de largura de banda e solucionar outros problemas de rede.


## Vídeo de laboratório - Use o Wireshark para comparar o tráfego Telnet e SSH

  * Usar o Wireshark para capturar o tráfego do navegador da Web.
  * Usar o Wireshark para capturar o tráfego Telnet.
  * Usar o Wireshark para capturar o tráfego SSH.

  * -------------------------------------------------------------------------------------------+
    

## Usar o Wireshark para capturar o tráfego do navegador da Web.
Usar o Wireshark para capturar o tráfego Telnet.
Usar o Wireshark para capturar o tráfego SSH.

### Avaliações de Segurança

Um scanner de vulnerabilidades é utilizado para avaliar computadores, sistemas, redes ou aplicações em busca de pontos fracos. Entre os mais usados no mercado estão: Nessus, Retina, Core Impact e GFI LanGuard.

Esses scanners podem ser de rede, de aplicação ou de web. Em alguns casos, realizam varreduras invasivas que tentam explorar vulnerabilidades e até bloquear o alvo.
Nas verificações credenciais, nomes de usuário e senhas autorizados fornecem acesso ao sistema, permitindo ao scanner coletar informações mais detalhadas.

Ferramentas de linha de comando que também podem auxiliar na avaliação de vulnerabilidades incluem:
ipconfig, ping, arp, tracert, nslookup, netstat, nbtstat, nmap, netcat e hping.

Já os sistemas SIEM coletam e agregam dados de log vindos de diversas fontes, como dispositivos de segurança, servidores, aplicações e elementos da rede.
Além disso, ferramentas SOAR possibilitam que empresas automatizem a coleta de informações sobre ameaças, permitindo responder a eventos de menor impacto sem necessidade de intervenção humana.


### Técnicas de teste de segurança de rede

A segurança das operações se preocupa com as práticas diárias necessárias para primeiro implantar e depois manter um sistema seguro. A segurança das operações começa com o processo de planejamento e implementação de uma rede. Normalmente, os testes de segurança da rede são conduzidos durante os estágios de implementação e operacional, após o sistema ter sido desenvolvido, instalado e integrado. Ele é executado em uma rede para garantir que todas as implementações de segurança estejam operando conforme o esperado. Um ST&E é um exame das medidas de proteção que são colocadas em uma rede operacional. Os tipos de testes de rede incluem: penetração, varredura de rede, varredura de vulnerabilidade, quebra de senha, revisão de log, verificadores de integridade e detecção de vírus.

### Ferramentas de teste de segurança de rede

As ferramentas de software que podem ser usadas para realizar testes de rede incluem: Nmap / Zenmap, SuperScan, SIEM, GFI LANguard, Tripwire, Nessus, L0phtCrack e Metasploit. O Nmap oferece varredura e varredura de porta TCP e UDP clássica, varreduras e varreduras de porta Stealth TCP e UDP e ID de sistema operacional remoto. SuperScan é uma ferramenta de digitalização de portas do Microsoft Windows. Ele é executado na maioria das versões do Windows e requer privilégios de administrador. Os SIEMs fornecem correlação, agregação, análise forense e retenção.


### Teste de penetração

O teste de penetração (pen testing) é um método de testar áreas de fraquezas em sistemas usando várias técnicas maliciosas. Um teste de penetração simula os métodos que um invasor usaria para obter acesso não autorizado a uma rede e comprometer os sistemas, além de permitir que uma empresa entenda como toleraria um ataque real. Há quatro fases que compõem um teste de penetração: 1 Planejamento, 2. Descoberta, 3. Ataque, e 4. Relatórios. Algumas empresas criam equipes concorrentes para realizar exercícios de penetração mais longos do que um teste de penetração. Normalmente, há um time vermelho (tentando atacar o sistema) e um time azul (tentando defender o sistema). Os packet analyzers (ou analisadores de pacotes) interceptam e registram o tráfego de rede. Farejar não é usado apenas para fins mal-intencionados. Os administradores de rede também podem usar sniffers para analisar o tráfego de rede, identificar problemas de largura de banda e solucionar outros problemas de rede.
