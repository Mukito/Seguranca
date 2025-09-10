# Scanners de vulnerabilidade

Um scanner de vulnerabilidades avalia computadores, sistemas de computador, redes ou aplicações, em busca de pontos fracos. 
Os scanners de vulnerabilidades ajudam a automatizar a auditoria de segurança ao buscar riscos de segurança na rede e produzir uma lista priorizada para abordar as vulnerabilidades.

### Um scanner de vulnerabilidades procura os seguintes tipos de vulnerabilidades:

* Uso de senhas padrão ou senhas comuns
* Patches não instalados
* Portas abertas
* Erro de configuração de software e de sistemas operacionais
* Endereços IP ativos, incluindo dispositivos inesperados conectados

### A verificação de vulnerabilidades é essencial para identificar vulnerabilidades, 
configurações incorretas e a falta de controles de segurança para empresas com redes que incluem segmentos, roteadores, firewalls, servidores e outros dispositivos.

### Os scanners de vulnerabilidade mais usados 
no mercado incluem **Nessus, Retina, Core Impact e GFI LanGuard**.

As funções incluem:

* Executar a auditoria de conformidade.
* Proporcionar patches e atualizações.
* Identificar configurações erradas
* Suportar dispositivos móveis e sem fio.
* Rastrear malware.
* Identificar dados confidenciais.

## Tipo de Varreduras
Ao avaliar um scanner de vulnerabilidades, analise como ele é classificado com relação a precisão, confiabilidade, escalabilidade e geração de relatórios. 
Você pode escolher um verificador de vulnerabilidades no software ou na nuvem.

### CATEGORIAS
**Os scanners de vulnerabilidade se enquadram em uma das várias categorias**:
* Os scanners de rede sondam os hosts em busca de portas abertas, enumeram informações sobre usuários e grupos e buscam vulnerabilidades conhecidas na rede.
* Os scanners de aplicativos acessam o código-fonte do aplicativo para testar uma aplicação de dentro para fora (eles não executam a aplicação).
* Os verificadores de aplicativos da Web identificam vulnerabilidades em aplicativos da web.

### VARREDURAS INVASIVAS E CREDENCIADAS
As verificações invasivas tentam explorar vulnerabilidades e podem até travar o alvo, enquanto uma verificação não invasiva tentará não causar danos ao alvo.
Em uma verificação credenciada, nomes de usuário e senhas fornecem acesso autorizado a um sistema, permitindo que o scanner colete mais informações. 
As verificações sem credenciais são menos invasivas e oferecem o ponto de vista de quem está de fora.
No entanto, todos os tipos de verificador podem identificar por engano uma vulnerabilidade que não existe. Isso é conhecido como falso positivo, 
mas não identificar uma vulnerabilidade atual é falso negativo. As verificações credenciadas retornam menos falsos positivos e menos falsos negativos.
Você precisa analisar todos os logs e configurações para cuidar de todas as vulnerabilidades que exigem atenção.


# Utilitários de diagnóstico de linha de comando
Há várias ferramentas de linha de comando que podem ser usadas para avaliar a posição de segurança de uma empresa como a @Apollo.

  * **ipconfig** exibe as configurações de TCP / IP (endereço IP, máscara de sub-rede, gateway padrão, informações de DNS e MAC (*ifconfig* é o equivalente em Mac / Linux).
  * **o ping** testa a conectividade de rede enviando uma solicitação de ICMP (Internet Control Message Protocol) para um host e determina se uma rota está disponível para um host.
  * **O arp** fornece uma tabela que mapeia endereços MAC conhecidos para o endereço IP associado e é uma maneira rápida de encontrar o endereço MAC de um dispositivo final.
  * **O tracert** rastreia a rota que um pacote leva até um destino e registra os saltos ao longo do caminho, ajudando a localizar onde um pacote está sendo desligado (traceroute é o equivalente em Mac / Linux).
  * **O nslookup** consulta um servidor DNS para ajudar a solucionar um banco de dados DNS (dig é o equivalente em Mac / Linux).
  * **O netstat** exibe todas as portas que um computador está ouvindo e pode determinar as conexões ativas.
  * **O nbtstat** ajuda a solucionar problemas de resolução de nomes do NetBIOS em um sistema Windows.
  * **O nmap** é usado na auditoria de segurança. Ele localiza hosts de rede, detecta sistemas operacionais e identifica serviços.
  * **O netcat** coleta informações de conexões de rede TCP e UDP e pode ser usado para varredura de portas, monitoramento, captura de banner e cópia de arquivos.
  * **A hping** monta e analisa pacotes e é usada para varredura de portas, descoberta de caminho, impressão digital do SO e testes de firewall.


## Automação de segurança
Vejamos agora algumas informações sobre as abordagens automatizadas de Security Information and Event Management (SIEM) e Security Orchestration Automation and Response (SOAR).
### SIEM
Os sistemas de Security Information and Event Management (SIEM) usam coletores de log para agregar dados de log de fontes como dispositivos de segurança, dispositivos de rede, 
servidores e aplicações. Os logs podem gerar muitos eventos em um dia, então os sistemas SIEM ajudam a reduzir o volume de eventos combinando eventos semelhantes para reduzir 
a carga de dados do evento. O SIEM identifica desvios da norma e, em seguida, executa a ação apropriada.

Os objetivos de um sistema SIEM para monitoramento de segurança são:

  * Ameaças internas e externas
  * Monitorar a atividade e o uso de recursos
  * Realizar relatórios de conformidade para auditorias
  * resposta a incidentes
    
Quando o sistema SIEM detecta um possível problema, ele pode registrar informações adicionais, gerar um alerta e instruir outros controles de segurança para interromper
o progresso de uma atividade. Os sistemas avançados de SIEM incluem análises de comportamento de usuários e entidades que buscam padrões que dependem do sentimento humano
para reconhecer uma ameaça antes que ela se torne uma ameaça.

A quantidade de dados registrados de sistemas essenciais é uma consideração importante ao implementar um sistema SIEM, pois você precisa revisar os relatórios gerados. 
Os sistemas SIEM são caros para compra e manutenção e são econômicos se a empresa tiver milhões de eventos gerados em um dia.

### SOAR
As ferramentas de automação e resposta da orquestração (SOAR) permitem que uma empresa colete dados sobre ameaças à segurança de várias fontes e responda 
a eventos de nível inferior sem intervenção humana. O SOAR tem três recursos importantes:

  * Gerenciamento de ameaças e vulnerabilidades
  * Operações de segurança e resposta a incidentes
  * Operação de segurança
Uma empresa pode integrar o SOAR em sua solução SIEM.


# Vídeo PT - use comandos de diagnóstico
Neste Packet Tracer, você aprenderá como:

  * Coletar as configurações do dispositivo do usuário final.
  * Coletar informações sobre a rede e os dispositivos
  * Diagnosticar problemas de conectividade.

