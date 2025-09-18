# Ferramentas de teste de rede

As ferramentas de software que podem ser usadas para realizar testes de rede incluem:

  * **Nmap / zenmap** - é usado para descobrir computadores e seus serviços em uma rede, criando, portanto, um mapa da rede.
  * **SuperScan**- Este software de varredura de porta é projetado para detectar as portas Abrir TCP e UDP, determine quais serviços estão sendo executados nessas portas e execute consultas, como pesquisas Whois, Ping, Traceroute e HostName.
  * **Siem (gerenciamento de eventos de informação de segurança)** - Esta é uma tecnologia usada em organizações corporativas para fornecer relatórios em tempo real e análise de longo prazo de eventos de segurança.
  * **GFI Languard** - Este é um scanner de rede e segurança que detecta vulnerabilidades.
  * **TripWire**- Esta ferramenta avalia e valida configurações de TI contra políticas internas, padrões de conformidade e as melhores práticas de segurança.
  * **Nessus** - Este é um software de varredura de vulnerabilidade, com foco em acesso remoto, miscigurações e DOS contra a pilha TCP / IP.
  * **L0phtcrack**- Este é um aplicativo de auditoria e recuperação de senha.
  * **Metaploit**- Esta ferramenta fornece informações sobre vulnerabilidades e ajuda em testes de penetração e desenvolvimento de assinaturas de IDs.<br><br>
**Nota**: As ferramentas de teste de rede evoluem em um ritmo rápido. A lista anterior inclui ferramentas legadas e sua intenção é fornecer uma consciência dos diferentes tipos de ferramentas disponíveis.

-----------------------------------------------

## Nmap e Zenmap
Nmap é um scanner de baixo nível comumente usado que está disponível para o público. Possui uma variedade de excelentes recursos que podem ser usados para mapeamento de rede e reconhecimento.

A funcionalidade básica do Nmap permite ao usuário realizar várias tarefas, como segue:

  * **Clássico TCP e UDP Port Scanning** - isso procura por diferentes serviços em um host.
  * **Clássico TCP e UDP Port Sweeping** - Isto procura o mesmo serviço em vários hosts.
  * **Varreduras furtivas de portas TCP e UDP** - Semelhante às varreduras clássicas, mas mais difíceis de detectar pelo host de destino ou IPS.
  * **Identificação do sistema operacional remoto** - isso também é conhecido como impressões digitais do sistema operacional.
As características avançadas do Nmap incluem a varredura de protocolo, conhecida como varredura de porta da camada 3. Este recurso identifica o suporte ao protocolo da Camada 3 em um host. Exemplos de protocolos que podem ser identificados incluem GRE e OSPF.

Embora o Nmap possa ser usado para testes de segurança, ele também pode ser usado para fins maliciosos. O Nmap tem um recurso adicional que permite usar hosts falsos na mesma LAN do host de destino, para mascarar a origem da varredura.

O Nmap não possui recursos de camada de aplicativo e é executado em UNIX, Linux, Windows e OS X. As versões de console e gráfica estão disponíveis. O programa Nmap e Zenmap GUI podem ser baixados da internet.

---------------------------------------------------

## SuperScan
SuperScan é uma ferramenta de digitalização de portas do Microsoft Windows. Ele é executado na maioria das versões do Windows e requer privilégios de administrador.

SuperScan versão 4 tem uma série de recursos úteis:

  * Velocidade de digitalização ajustável
  * Suporte para intervalos de IP ilimitados
  * Detecção de host aprimorada usando vários métodos ICMP
  * Digitalização TCP SYN
  * Varredura UDP (dois métodos)
  * Geração de relatórios HTML simples
  * Verificação da porta de origem
  * Resolução rápida de nome de host
  * Extensas capacidades de agarrar banner
  * Banco de dados maciço incorporado da descrição da
  * Randomização de ordem de varredura de IP e porta
  * Uma seleção de ferramentas úteis, como ping, traceroute e whois
  * Amplo recurso de enumeração de host do Windows <br><br>
  Ferramentas, como Nmap e SuperScan, podem fornecer testes de penetração eficazes em uma rede e determinar vulnerabilidades de rede, ajudando a antecipar possíveis mecanismos de ataque. No entanto, o teste de rede não pode preparar um administrador de rede para todos os problemas de segurança.

-------------------------------------------------------

## SIEM
O SIEM (Security Information Event Management) é uma tecnologia usada em organizações empresariais para fornecer relatórios em tempo real e análise de longo prazo de eventos de segurança. 
O SIEM evoluiu de dois produtos anteriormente separados: Security Information Management (SIM) e Security Event Management (SEM). 
O SIEM pode ser implementado como software, integrado ao Cisco Identity Services Engine (ISE) ou como um serviço gerenciado.

SIEM combina as funções essenciais de SIM e SEM para fornecer:

  * **Correlação** - Examina logs e eventos de sistemas ou aplicativos diferentes, acelerando a detecção e reação às ameaças de segurança.
  * **Agregação** - A agregação reduz o volume de dados de eventos consolidando registros de eventos duplicados.
  * **Análise Forense** - A capacidade de pesquisar logs e registros de eventos de fontes em toda a organização fornece informações mais completas para análise forense.
  * **Retenção** - O relatório apresenta os dados de eventos correlacionados e agregados em monitoramento em tempo real e resumos de longo prazo.<br>

Siem fornece detalhes sobre a fonte de atividade suspeita, incluindo:

  * Informações do usuário (nome, status de autenticação, local, grupo de autorização, status de quarentena)
  * Informações do dispositivo (fabricante, modelo, versão do sistema operacional, endereço MAC, método de conexão de rede, localização)
  * Informações de postura (conformidade do dispositivo com a política de segurança corporativa, versão antivírus, patches do sistema operacional, conformidade com a política de gerenciamento de dispositivos móveis)
Usando essas informações, os engenheiros de segurança de rede podem avaliar rapidamente e precisar avaliar a importância de qualquer evento de segurança e responder às perguntas críticas:

  * Quem está associado a este evento?
  * É um usuário importante com acesso à propriedade intelectual ou informações confidenciais?
  * O usuário está autorizado a acessar esse recurso?
  * O usuário tem acesso a outros recursos confidenciais?
  * Que tipo de dispositivo está sendo usado?
  * Esse evento representa um problema de conformidade em potencial?

---------------------------------------------------------

