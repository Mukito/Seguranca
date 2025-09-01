# Compreendendo a Defesa

## Introdução 

### Por que devo fazer este módulo?

Proteger nossas redes sempre será um desafio, 
O gerenciamento de operações de segurança cibernética abrange todas as configurações necessárias para executar uma rede
O gerenciamento de configuração refere-se à identificação, controle e auditoria da implementação e de quaisquer alterações feitas à linha de base estabelecida de um sistema.


--------------------


| Titulo do Tópico | Objetivo do Tópico |
|------------------|--------------------|
| Defesa em Profundidade |  Explicar com a estatégia de Defesa de Profundidade é usada para proteger as redes. |
| Gerenciamento de operações de segurança cibernética | explique como uma empresa monitora ameaças de segurança digital. | 
| Politicas de Segurança, regulamentações e Padrões | Explicar as políticas de segurança, as regulamentações e os padrões. | 




### Defesa de Profundidade

  * Analistas de segurança cibernética devem se preparar para qualquer tipo de ataque.
É seu trabalho proteger os ativos da rede da organização.
Para fazer isso, os analistas de segurança cibernética devem primeiro identificar:

 - **Ativos** - Protege servidores, dispositivos de infraestrutura, dispositivos finais e o maior ativo, dados.
 - **Vunerabilidades** - Uma fraqueza em um sistema ou agente de ameaça.
 - **Ameaças** - Qual perigo para um ativo.


### ATIVOS
    São todos os elementos de valor para a organização que precisam ser protegidos. 
    Exemplos: dados sensíveis, sistemas, servidores, redes, aplicativos, reputação da marca, até mesmo pessoas com conhecimento crítico.



### Classificação de Ativos

    - Determinar a categoria de identificação de ativos adequada:
        * Ativos de informações
        * Ativos de Software
        * Ativos Fisicos
        * Serviços

    - Estabeleça a responsabilização, identificando o proprietário de todos os ativos de informações e de software de aplicativos:
        * Identificar o proprietário de todos os ativos de informações
        * Identificar o proprietário de todos o software de aplicação

    - Determinar os critérios de classificação 
        * Confidencialidade
        * Valor
        * Direitos de acesso
        * Destruição
        
    - Implemente um esquema de classificação:
        * Adotar uma maneira uniforme de identificação de informações para assegurar a proteção uniforme


-----------------------------------------------------------------


## Ciclo de Vida dos Ativos

Para especialistas em segurança digital, parte do trabalho é gerenciar ativos de informação e sistemas relacionados durante todo o ciclo de vida do ativo.

**Aquisição** - A Empresa compra os ativos de acordo com as necessidades, o ativo e adicionado ao inventario da empresa
**Implantação** -  O Ativo é montado e inspecionado para verificar se há falhas ou problemas, realiza-se testes e instala tags ou códigos de barras - Sai do inventario para o uso
**Utilização** - Fase mais longa Desempenho do ativo - Atualização, correção de patchs compras de novas licenças. 
**Manutenção** - Ajuda a prolongar a vida do ativo - Modificar ou atualizar o recurso.
**Eliminação** - Fim da vida produtiva do ativo, descartado. Dados apagados - Descarte pode incluir, Desmontagem  



### Defesa em profundidade
**Roteador de borda** - A primeira linha de defesa é conhecida como um roteador de borda (R1 na figura). <br>
O roteador de borda tem um conjunto de regras especificando qual tráfego ele permite ou nega. 
Ele passa todas as conexões que se destinam à LAN interna para o firewall.<br>
**Firewall** - A segunda linha de defesa é o firewall. O firewall é um dispositivo de ponto de verificação 
que executa filtragem adicional e rastreia o estado das conexões. Ele nega o início de conexões de redes externas 
(não confiáveis) para a rede interna (confiável), enquanto permite que usuários internos estabeleçam conexões bidirecionais
com as redes não confiáveis. Ele também pode executar autenticação de usuário (proxy de autenticação) 
para conceder aos usuários remotos externos acesso a recursos de rede interna.<br>
**Roteador interno** - Outra linha de defesa é o roteador interno (R2 na figura). 
Ele pode aplicar regras de filtragem finais no tráfego antes de ser encaminhado para seu destino.
Os roteadores e firewalls não são os únicos dispositivos que são usados em uma abordagem de defesa profunda. 
Outros dispositivos de segurança incluem IPS (Intrusion Prevention Systems), Proteção Avançada contra Malware (AMP), 
sistemas de segurança de conteúdo da Web e de e-mail, serviços de identidade, controles de acesso à rede e muito mais.<br>

Na abordagem de segurança em camadas de defesa profunda, as diferentes camadas trabalham juntas para criar uma arquitetura de segurança na qual a falha de uma salvaguarda não afeta a eficácia das outras salvaguardas.

### Alcachofra da segurança
Existem duas analogias comuns que são usadas para descrever uma abordagem de defesa em profundidade.
 - **Cebola de segurança** - Uma analogia comum usada para descrever uma abordagem de defesa em profundidade é chamada de “cebola de segurança”. Como ilustrado na figura, um ator de ameaça teria que descascar as defesas de uma rede camada por camada de uma maneira semelhante a descascar uma cebola. Somente depois de penetrar cada camada, o ator da ameaça alcançaria os dados ou o sistema de destino.

Observação: A Security Onion descrita nesta página é uma forma de visualizar a defesa em profundidade. Isso não deve ser confundido com o conjunto Security Onion de ferramentas de segurança de rede.
A figura de cebola de segurança mostra uma cebola com várias camadas dentro dela. A cebola é rotulada como ativos. À direita estão palavras e setas apontando para as diferentes camadas: dispositivos reforçados; autenticação, autorização e contabilidade (A A); filtragem de conteúdo; sistemas de prevenção de intrusões (I P S); firewall.


  - **Alcachofra de segurança** - os atores da ameaça não precisam mais descascar cada camada. Eles só precisam remover certas “folhas de alcachofra”. O bônus é que cada “folha” da rede pode revelar dados confidenciais que não estão bem protegidos.

### Estratégias de Defesa em Produndidade

**Sobreposição** - A defesa em profundidade não fornecerá um escudo cibernético impenetrável, mas ajudará a empresa a minimizar riscos, mantendo-se um passo à frente dos criminosos virtuais.
**Limitação** - Uma empresa deve ter as ferramentas e as configurações certas, como permissões de arquivo, para limitar o acesso, bem como as medidas processuais certas, que definem etapas específicas para fazer qualquer coisa que possa afetar a segurança. Por exemplo, um procedimento de limitação que exige que os funcionários sempre consultem documentos confidenciais em uma sala com CCTV garante que eles nunca removam esses documentos das instalações.
**Diversidade** - Para atingir o objetivo de diversidade nas defesas, as empresas podem usar produtos de segurança de diferentes empresas como diferentes fatores de autenticação, como um cartão de furto de uma empresa e um leitor de impressão digital fabricado por uma empresa diferente, bem como medidas de segurança variadas, como bloqueio de tempo nos armários e supervisão por um membro da equipe de segurança ao desbloqueá-lo.

**Ofuscação** - A ofuscação de informações também pode proteger dados e informações. Uma empresa não deve revelar informações que os criminosos virtuais podem usar para descobrir a versão do sistema operacional em execução em um servidor ou o tipo de equipamento que ele usa

**Simplicidade** - A complexidade não garante, necessariamente, a segurança. Se uma empresa implementar sistemas complexos que são difíceis de entender e de solucionar problemas, o “tiro pode sair pela culatra”. Se os funcionários não entenderem como configurar uma solução complexa corretamente, pode ser tão fácil quando em uma solução mais simples para os criminosos virtuais comprometerem esses sistemas.
 

