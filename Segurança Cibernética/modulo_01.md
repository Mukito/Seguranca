
## 1.1 Por que é importante realizar a Gestão Contínua de Vulnerabilidades?
Muitas vezes, encontrar e corrigir todas as vulnerabilidades não é uma atividade trivial ou viável 
é importante identificar e priorizar quais são as vulnerabilidades mais impactantes para a organização e determinar, 
além de quais, com qual atenção e brevidade devem ser tratadas.

<br>

*“Compreender e gerenciar vulnerabilidades é uma atividade contínua, que requer foco de tempo, atenção e recursos” (CIS, 2021).*

Um termo utilizado pelos profissionais de segurança para descrever os padrões de atividades usadas pelos agentes maliciosos ao se prepararem para os ataques cibernéticos se chama **TTPs (Táticas, Técnicas e Procedimentos).**


link OSINT Framework

https://osintframework.com/


priorização do tratamento das vulnerabilidades deve ser orientada por dois pontos: <br>
  I) dados que a organização dispõe para evidenciar vulnerabilidade; <br>
  II) táticas e técnicas mais adotadas pelos invasores. <br>
      - governo federal dos EUA, criou o MITRE ATT&CK. https://attack.mitre.org/


para saber sobre o uso do MITRE pelo CIS - Guia Community Defense Model <br>
https://www.cisecurity.org/insights/white-papers/cis-community-defense-model-2-0


<br>
Outro framework que também atua na identificação das fases de um ataque cibernético é o Cyber Kill Chain, desenvolvido pela empresa de tecnologia Lockheed Martin. Esse framework compõe um ataque cibernético em 7 fases.

https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html

<br>

*“As empresas que não avaliam sua infraestrutura em busca de vulnerabilidades e corrigem prontamente as falhas descobertas possuem uma probabilidade significativa de ter seus ativos corporativos comprometidos” (CIS, 2021).*


## 1.2 Quais os Procedimentos Gerais e Técnicas que a Gestão de Vulnerabilidades deve Compreender? 

o gerenciamento de vulnerabilidades passa a ter um ciclo de vida contínuo
você nunca eliminará completamente todas as vulnerabilidades, mas pode efetivamente priorizar quais corrigir.
é importante entender o significado dos termos ameaça, vulnerabilidade e risco, assim como a correlação entre eles.


**De acordo com o Glossário de Segurança nº 93 do GSI/PR (GSI, 2021).**

### Ameaça 

Conjunto de fatores externos com o potencial de causar em dano para um sistema ou organização.

### Vulnerabilidade

Condição que, quando explorada por um criminoso cibernético, pode resultar em uma violação de segurança 
cibernética dos sistemas computacionais ou redes de computadores, e consiste na 
interseção de três fatores: suscetibilidade ou falha do sistema, acesso possível à falha e capacidade de explorar essa falha.

### Risco

No sentido amplo, trata-se da possibilidade de ocorrência de um evento que pode impactar o cumprimento dos objetivos. Pode ser mensurado em termos de impacto e de probabilidade.

**Para que você possa compreender a relação entre esses três termos, veja a definição da ISO 27000 para o risco de segurança (ISO 27000, 2018):** <br>

https://www-iso-org.translate.goog/standard/iso-iec-27000-family?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc

*“O risco de segurança da informação está associado ao potencial de que as ameaças explorem vulnerabilidades de um ativo de informação ou grupo de ativos de informação e, assim, causar danos a uma organização”.*




### Sequência de sete passos de alto nível para exemplificar a implementação das medidas:

1. Identifique os ativos corporativos e de software que precisam ser incluídos no processo de gestão de vulnerabilidades. Importante reforçar que cada organização irá definir esses ativos com base em seu negócio e na sua missão.
2. Procure entender, para cada ativo selecionado, quais são as possíveis ameaças.
3. Descubra as vulnerabilidades existentes em cada ativo.
     * A **MITRE Corporation** criou um programa que visa identificar, definir e catalogar vulnerabilidades de segurança cibernética divulgadas publicamente.
     * Esse programa se chama **CVE (Common Vulnerabilities and Exposures)** e é formado por registros, contendo, para cada número de identificação, uma descrição e pelo menos uma referência pública para vulnerabilidades de segurança cibernética publicamente conhecidas.
       https://cve.mitre.org/ 
     * Existem duas técnicas utilizadas para a identificação de vulnerabilidades
       1. Varredura não Autenticada
          -  Não usam credenciais e atuam a partir de informações já conhecidas ou publicamente disponíveis. O resultado desse tipo de varredura é a mesma visualizada por um atacante caso consiga também realizar a varredura.
       3. Varredura Autenticada
          - Fazem uso de credenciais válidas para se autenticarem em serviços e aplicações, executando testes no mesmo nível de privilégio das credenciais utilizadas, relatando as possíveis vulnerabilidades expostas aos usuários que poderiam estar ocultas ou inacessíveis pelas varreduras não autenticadas.

-------------------------------------------------------------

* Uma das técnicas mais empregadas na identificação de vulnerabilidades é o teste de penetração (ou teste de intrusão ou Pentest), que pode ser descrito como um ataque simulado aos sistemas e aplicativos de TI de uma organização para identificar vulnerabilidades que um invasor poderia explorar.
* Os testes de penetração são normalmente realizados por um ator externo (uma equipe de testes não atrelada à área de desenvolvimento de software ou uma fábrica de testes) e podem fornecer informações valiosas sobre a eficácia dos controles de segurança de uma organização.
* O Centro Integrado de Segurança Cibernética do Governo Digital (CISC gov.br) oferece o serviço de teste de intrusão aos órgãos do Sistema Integrado de Segurança Pública (SISP)  https://www.gov.br/cisc/pt-br

4. Analise e priorize as vulnerabilidades com base em critérios de risco, por exemplo, na sua gravidade, impacto potencial no negócio e probabilidade de exploração.
   * Vários produtos e serviços de segurança cibernética executam a descoberta das vulnerabilidades, identificam o registro **CVE** e já retornam as recomendações de priorizações baseadas em métodos disponíveis no mercado.
   * O **Common Vulnerability Scoring System (CVSS)**, mantido pelo **National Institute of Standards and Technology (NIST)** em sua base de dados chamada de **NVD (National Vulnerability Database)**,
   * É um dos métodos usados que ***fornece uma medida qualitativa de gravidade*** e está sincronizado com os registros de CVE da MITRE Corporation https://nvd.nist.gov/vuln-metrics/cvss

#### Atenção! O CVSS não é um critério de risco.

O **CVE** e **NVD** são patrocinados pela **Agência de Segurança Cibernética e de Infraestrutura (CISA)** e disponíveis ao público de forma gratuita.
A CISA também desenvolveu a sua própria metodologia de análise de vulnerabilidades, chamada de **SSVC (Stakeholder-Specific Vulnerability Categorization)**
que leva em conta o status de exploração de uma vulnerabilidade, os impactos à segurança e a prevalência do produto afetado em um determinado sistema
https://www.cisa.gov/stakeholder-specific-vulnerability-categorization-ssvc

5. Reporte as vulnerabilidades descobertas junto aos envolvidos e partes interessadas para que tenham visibilidade e ciência dessas vulnerabilidades, assim como das análises realizadas.
6. Faça a correção das vulnerabilidades identificadas nos ativos conforme a priorização e a brevidade necessárias. Caso a correção não seja possível dentro do prazo recomendável e/ou planejado, procure implementar medidas de segurança alternativas que possam ajudar a reduzir os riscos de exploração dessas vulnerabilidades.  Não deixe de verificar posteriormente se as vulnerabilidades foram realmente corrigidas.
7. Procure estabelecer indicadores e métricas que possam ajudar no acompanhamento e no entendimento da maturidade da organização nesse processo.

 ***Atenção!** O processo de gestão de vulnerabilidades é contínuo, então não deixe de estipular a rotina de monitoração periódica dos seus ativos. Novas vulnerabilidades podem aparecer.*


Gerenciamento de Ameaças
https://www.gartner.com/en/articles/how-to-manage-cybersecurity-threats-not-episodes

*“Até 2026, as organizações que priorizarem os seus investimentos em segurança com base em um programa de Gerenciamento de Exposição contínua terão 3x menos chances de sofrer uma violação” (Gartner, 2023, tradução nossa).*


## 1.2.1. Quais as Medidas de Segurança?

* Realizar varreduras automatizadas de vulnerabilidade em ativos corporativos expostos interna e externamente,
  de forma autenticada e não autenticada, conforme medidas de segurança 7.5 e 7.6 do CIS Controls.
  Aqui o CIS já recomenda o uso de ferramentas de varredura de vulnerabilidade compatíveis com o SCAP (Security Content Automation Protocol) buscando,
  por exemplo, a automatização, padronização, simplificação e uma melhor visibilidade.  Conforme também mencionado no Controle 2,
  o SCAP não é uma ferramenta, e sim um protocolo que pode ser utilizado livremente pelos fabricantes de ferramentas para verificação
  de conformidades de segurança. A própria ferramenta CIS-CAT Lite, disponibilizada pelo CIS, é compatível com o SCAP.
