# Padrões de Segurança HIPAA: Salvaguardas Técnicas
### O que é a Série de Segurança?

A série de documentos sobre segurança fornece orientações dos Centros de Serviços Medicare e Medicaid (CMS) sobre a regra 
"Padrões de Segurança para a Proteção de Informações Eletrônicas de Saúde Protegidas", encontrada em 45 CFR Parte 160 e Parte 164, Subpartes A e C, 
conhecida como a Regra de Segurança. A Regra de Segurança foi adotada para implementar as disposições da Lei de Portabilidade e Responsabilidade de Seguro de Saúde de 1996 (HIPAA). 
A série de sete documentos, que cobrem os tópicos listados à esquerda, foi elaborada para dar às entidades cobertas pela HIPAA uma visão da Regra de Segurança e assistência na implementação dos padrões de segurança.



Este documento, o quarto da série, é dedicado aos padrões de Salvaguardas Técnicas e suas especificações de implementação, 
e pressupõe que o leitor tenha uma compreensão básica da Regra de Segurança.

### Prazos de Conformidade

O prazo de conformidade era 20 de abril de 2005 para todas as entidades cobertas, exceto para pequenos planos de saúde, que tinham até 20 de abril de 2006 para se adequar.

### O que são Salvaguardas Técnicas?

A Regra de Segurança define salvaguardas técnicas como "a tecnologia e a política e procedimentos para seu uso que protegem as informações eletrônicas de saúde protegidas 
e controlam o acesso a elas". A implementação das Salvaguardas Técnicas é considerada uma boa prática de negócio para a tecnologia e as políticas e procedimentos técnicos associados dentro de uma entidade coberta.


A Regra de Segurança é baseada em flexibilidade, escalabilidade e neutralidade tecnológica, o que significa que ela não especifica requisitos para tipos específicos 
de tecnologia a serem implementados. As entidades cobertas podem usar quaisquer medidas de segurança que lhes permitam implementar os padrões e especificações de implementação de forma razoável e apropriada. 
A seleção das medidas de segurança deve levar em conta o tamanho, a complexidade e as capacidades da entidade, bem como os resultados da análise e gestão de riscos.

As Salvaguardas Técnicas incluem os seguintes padrões:

* **Controle de Acesso**
  * **Identificação Única de Usuário (Obrigatório)**: Cada membro da força de trabalho deve ter um nome e/ou número único para identificar e rastrear a identidade do usuário.
    Isso permite que a entidade rastreie a atividade do usuário e os responsabilize pelas funções realizadas em sistemas com EPHI.
  * **Procedimento de Acesso de Emergência (Obrigatório)**: A entidade coberta deve estabelecer procedimentos para obter o acesso
    necessário às informações eletrônicas de saúde protegidas durante uma emergência.
  * **Logoff Automático (Endereçável)**: A entidade deve implementar procedimentos eletrônicos que encerrem uma sessão eletrônica após um tempo predeterminado de inatividade.
  * **Criptografia e Descriptografia (Endereçável)**: A entidade deve implementar um mecanismo para criptografar e descriptografar informações eletrônicas de saúde protegidas.
    A criptografia converte o texto normal em texto codificado para proteger o EPHI do acesso de usuários não autorizados.

* **Controles de Auditoria**
   * A entidade deve implementar mecanismos de hardware, software e/ou procedimentos que registrem e examinem a atividade em sistemas de informação que contenham ou usem
     informações eletrônicas de saúde protegidas. A Regra de Segurança não especifica quais dados devem ser coletados ou com que frequência os relatórios de auditoria devem ser revisados.

* **Integridade**
   * A entidade deve implementar políticas e procedimentos para proteger as informações eletrônicas de saúde protegidas de alteração ou destruição indevida.
     A integridade dos dados pode ser comprometida por fontes técnicas e não técnicas, como alterações acidentais ou intencionais ou falhas de mídia eletrônica.
   * **Mecanismo para Autenticar Informações Eletrônicas de Saúde Protegidas (Endereçável)**: A entidade deve implementar mecanismos eletrônicos para corroborar que o EPHI não foi alterado
     ou destruído de forma não autorizada.

* **Autenticação de Pessoa ou Entidade**
   * A entidade deve implementar procedimentos para verificar se uma pessoa ou entidade que busca acesso a informações eletrônicas de saúde protegidas é quem ela diz ser.
     A autenticação pode ser realizada exigindo algo conhecido apenas pelo indivíduo (por exemplo, uma senha), algo que o indivíduo possui (por exemplo, um cartão inteligente)
     ou algo único para o indivíduo (por exemplo, biometria).

* **Segurança de Transmissão**
   * A entidade deve implementar medidas de segurança técnicas para proteger contra o acesso não autorizado a informações eletrônicas de saúde protegidas que estão sendo transmitidas
     por uma rede de comunicações eletrônicas.

   * **Controles de Integridade (Endereçável)**: A entidade deve implementar medidas de segurança para garantir que o EPHI transmitido eletronicamente não seja modificado indevidamente sem detecção.
   * **Criptografia (Endereçável)**: A entidade deve implementar um mecanismo para criptografar o EPHI sempre que considerado apropriado.

### Em Resumo
As Salvaguardas Técnicas da Regra de Segurança são a tecnologia e as políticas e procedimentos relacionados que protegem o EPHI e controlam o acesso a ele. 
A regra exige que uma entidade coberta cumpra os padrões de Salvaguardas Técnicas, mas oferece a flexibilidade para que as entidades determinem quais medidas de segurança técnica serão implementadas. 
A implementação bem-sucedida das Salvaguardas Técnicas, juntamente com as Salvaguardas Administrativas e Físicas, ajudará a garantir a confidencialidade, integridade e disponibilidade do EPHI.

-----------------------------------------------------

### Normas de Salvaguardas Técnicas e Informações de Saúde Protegidas Eletrônicas (EPHI)
O documento "HIPAA Security" esclarece as normas de segurança técnica do HIPAA (Lei de Portabilidade e Responsabilidade do Seguro de Saúde). 
As salvaguardas técnicas são a tecnologia, as políticas e os procedimentos associados para proteger e controlar o acesso às informações eletrônicas de saúde protegidas (EPHI). 
A implementação dessas salvaguardas representa boas práticas de negócios.

### O documento aborda as seguintes normas de salvaguardas técnicas:

* **Controle de Acesso (§ 164.312(a)(1))**: Esta norma exige que as entidades cubertas implementem políticas e procedimentos técnicos para sistemas de informação eletrônica que permitam o acesso apenas a pessoas ou programas de software com direitos de acesso concedidos. O documento descreve quatro especificações de implementação para o controle de acesso:

  * **Identificação Única de Usuário (Obrigatório)**: Um nome ou número único para identificar e rastrear a identidade do usuário. Isso permite que a entidade cuberta rastreie a atividade do usuário e o responsabilize     pelas funções realizadas em sistemas de informação com EPHI.
  * **Procedimento de Acesso de Emergência (Obrigatório)**: Procedimentos para obter o EPHI necessário durante uma emergência.
  * **Logoff Automático (Endereçável)**: A implementação de procedimentos eletrônicos que encerram uma sessão após um tempo de inatividade predeterminado.
  * **Criptografia e Descriptografia (Endereçável)**: A implementação de um mecanismo para criptografar e descriptografar o EPHI. A criptografia converte um texto normal em texto codificado.

* **Controles de Auditoria (§ 164.312(b))**: Esta norma exige que a entidade cuberta implemente mecanismos de hardware, software e/ou procedimentos para registrar e examinar a atividade em sistemas de informação que contenham ou usem EPHI. Esta norma não tem especificações de implementação.

* **Integridade (§ 164.312(c)(1))**: A integridade, definida como a propriedade de que os dados não foram alterados ou destruídos de forma não autorizada, é um objetivo principal da Regra de Segurança. A norma exige políticas e procedimentos para proteger o EPHI de alteração ou destruição impróprias. Uma especificação de implementação endereçável, um mecanismo para autenticar o EPHI, é discutida.

* **Autenticação de Pessoa ou Entidade (§ 164.312(d))**: Esta norma não possui especificações de implementação e exige que a entidade cuberta implemente procedimentos para verificar se uma pessoa ou entidade que busca acesso ao EPHI é quem ela diz ser. A autenticação pode ser realizada através de algo que o indivíduo saiba (como uma senha), algo que o indivíduo possua (como um token) ou algo único para o indivíduo (como biometria).

* **Segurança de Transmissão (§ 164.312(e)(1))**: A norma final exige que a entidade cuberta implemente medidas de segurança técnicas para proteger contra o acesso não autorizado ao EPHI que está sendo transmitido em uma rede de comunicação eletrônica. Esta norma possui duas especificações de implementação endereçáveis:

   * **Controles de Integridade (Endereçável)**: Requer medidas de segurança para garantir que o EPHI transmitido eletronicamente não seja modificado indevidamente sem detecção.
   * **Criptografia (Endereçável)**: Requer um mecanismo para criptografar o EPHI quando considerado apropriado.


---------------------------------------------


Recomendar soluções de conformidade.


<img width="1029" height="737" alt="image" src="https://github.com/user-attachments/assets/7a8b6575-c109-485e-b4de-7ead2d23f943" />
<img width="1031" height="355" alt="image" src="https://github.com/user-attachments/assets/583deee7-3dfc-4f3a-aca8-f6193c2dc103" />

----------------------------------------------


Questões para Reflexão
1.Há muitas estruturas de conformidade que impõem requisitos à segurança da rede. A relevância dessas estruturas depende do tipo de negócio e das atividades empresariais que são conduzidas. 
O PCI-DSS é uma estrutura de conformidade para empresas que aceitam cartões de crédito para pagamento. Pesquise na Web os objetivos de controle do PCI-DSS. Cada objetivo tem um ou mais requisitos. 
Em suas pesquisas, preencha a tabela abaixo:

<img width="1024" height="618" alt="image" src="https://github.com/user-attachments/assets/cb2545e3-e773-4154-b1d9-c33e3dd0c882" />


