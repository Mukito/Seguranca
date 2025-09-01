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





