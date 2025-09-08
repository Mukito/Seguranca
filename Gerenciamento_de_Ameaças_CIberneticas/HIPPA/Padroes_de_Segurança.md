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
