# Laboratório - Desenvolver Políticas e procedimentos de segurança cibernética

### Introdução
As políticas de segurança da informação fornecem uma estrutura para as empresas gerenciarem e protegerem seus recursos, e uma proteção que as empresas utilizam para reduzir riscos. 
Os alunos deverão comparar políticas de segurança da informação para determinar as diferenças entre políticas, padrões, diretrizes e procedimentos. 
Os alunos desenvolverão uma política de segurança da informação para lidar com as vulnerabilidades atuais identificadas por uma auditoria interna.

Por exemplo, uma política de senha estabelece o padrão para criar senhas fortes e proteger senhas. Uma diretriz de construção de senha define como criar uma senha forte e fornece recomendações de melhores práticas. 
O procedimento de senha fornece instruções sobre como implementar o requisito de senha forte. As empresas não atualizam políticas com a mesma frequência que atualizam procedimentos dentro da estrutura de política 
de segurança da informação.


### Requisitos
Você precisará de acesso à Internet para os seguintes sites, vídeos e documentos:

  ●  Projeto de política de segurança do SANS https://www.sans.org/security-resources/policies/ <br>
  ●  Política de segurança da informação (vídeo) https://youtu.be/ZlKgMUOpMf8 <br>
  ●  Principais vulnerabilidades de segurança do computador https://www.n-able.com/features/computer-security-vulnerabilities <br>
  ●  Política de segurança da informação - Um guia de desenvolvimento para grandes e pequenas empresas (pdf) https://www.sans.org/reading-room/whitepapers/policyissues/information-security-policy-development-guide-large-small-companies- 1331 <br>
  ●  Escrita técnica para políticas de segurança de TI em cinco etapas fáceis https://www.sans.org/reading-room/whitepapers/policyissues/technical-writing-security-policies-easy-steps-492 <br>

### Cenário
ACME Healthcare é uma empresa de serviços de saúde que opera mais de 25 instalações médicas, incluindo atendimento ao paciente, 
diagnóstico, atendimento ambulatorial e atendimento de emergência. A empresa sofreu várias violações de dados nos últimos cinco anos. 
Essas violações de dados custaram à empresa financeiramente e prejudicaram sua reputação.

A equipe de liderança executiva contratou recentemente um novo diretor executivo de segurança da informação (CISO). 
O novo CISO reuniu uma das principais equipes de penetração de segurança digital para realizar uma auditoria de segurança completa em toda a empresa. 
Esse contratado independente realizou a auditoria e encontrou as seguintes vulnerabilidades:

1)   Várias contas foram identificadas para funcionários que não estão mais empregados pela ACME. <br>
2)   Várias contas de usuário permitiram privilégios não autorizados e escalados. Essas contas acessavam sistemas e informações sem autorização formal. <br>
3)   Vários dispositivos e sistemas permitiram acesso remoto não seguro. <br>
4)   Quarenta por cento de todas as senhas da empresa auditadas foram decifradas em 6 horas. <br>
5)   A expiração de senha não foi padronizada. <br>
6)   Arquivos confidenciais foram encontrados sem criptografia nos dispositivos dos usuários. <br>
7)   Vários hotspots sem fio usaram WEP para criptografia e autenticação. <br>
8)   As evidências indicam que o e-mail confidencial foi enviado de e para residências de funcionários e dispositivos móveis sem criptografia. <br>
9)   Os logs de detecção de invasão eram raramente revisados e analisados. <br>
10)   Dispositivos com dados confidenciais da empresa foram usados pelos funcionários para uso privado. <br>
11)   Os dispositivos dos funcionários não foram atendidos e os funcionários não fizeram logout da rede e dos sistemas de dados da empresa. <br>
12)   Configurações e atualizações de dispositivos inconsistentes foram realizadas. <br>
13)  Várias regras de firewall foram definidas para permitir todo o tráfego, a menos que sejam negadas especificamente. <br>
14)   Os servidores da empresa não foram atualizados com as correções mais recentes. <br>
15)   O servidor Web da intranet permitiu que os usuários alterassem informações pessoais, inclusive informações de contato. <br>

### Instruções Parte 1
: Revisão do cenário
Leia o cenário acima. Assista ao vídeo da Política de segurança da informação. Faça anotações para ajudá-lo a diferenciar os vários níveis e tipos de políticas.

### Parte 2: Revisar e priorizar descobertas de auditoria
**a**.  Pesquise os tipos de vulnerabilidades listados para determinar quais delas representam a maior ameaça.   Ir para o alto de vulnerabilidades de segurança do computador para saber mais. <br>
**b**.  Com base em sua pesquisa, liste as cinco principais descobertas de auditoria de segurança que a ACME deve abordar, começando pela maior vulnerabilidade.<br>
**c**.  Registre sua classificação em uma tabela de classificação de vulnerabilidades, como a mostrada abaixo. Ele lista as vulnerabilidades, a política recomendada para atenuar essa vulnerabilidade e sua justificativa para a classificação que você determinou.<br>


Tabela de Classificação


| **Vulnerabilidade**                                              | **Política recomendada**                                           | **Justificativa**                                                                                                        |
| ---------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| Senhas fracas (40% quebradas em 6h; sem expiração padronizada)   | Política de senha forte + autenticação multifator (MFA)            | A quebra massiva de senhas mostra falha grave. Sem MFA, qualquer invasor pode acessar sistemas críticos.                 |
| Contas de ex-funcionários e privilégios indevidos                | Política de gerenciamento de identidades e acessos (IAM)           | Contas órfãs e privilégios não autorizados são uma das maiores causas de ataques internos e externos.                    |
| Dados confidenciais sem criptografia (em dispositivos e e-mails) | Política de criptografia de dados em repouso e em trânsito         | Dados médicos sem criptografia expõem pacientes e aumentam riscos de multas regulatórias (HIPAA/LGPD).                   |
| Firewall aberto e servidores sem patch                           | Política de gerenciamento de patches e configuração segura de rede | Firewalls permissivos e servidores desatualizados permitem ataques externos e exploração de vulnerabilidades conhecidas. |
| Acesso remoto inseguro (WEP, sem VPN)                            | Política de acesso remoto seguro                                   | Conexões inseguras permitem invasores entrar na rede sem barreiras, especialmente em hotspots e dispositivos móveis.     |


### Parte 3: Desenvolver documentos de políticas
**Etapa 1:** Criar uma política de segurança da informação
a.    Escolha uma vulnerabilidade na tabela para a qual desenvolver uma política de segurança.
b.    Use os modelos de política de segurança de informação para desenvolver uma política de segurança específica para serviços de saúde ACME que aborda a vulnerabilidade escolhida.
Observação: siga o modelo como uma diretriz. Abordar todos os elementos de política atuais. Nenhuma política deve exceder duas páginas.

----------------------------------------------------------

# Política de Senhas e Autenticação – ACME Healthcare
### 1. Propósito

Estabelecer requisitos obrigatórios para a criação, o uso e a proteção de senhas e credenciais de acesso dentro da ACME Healthcare. 
Esta política visa proteger informações sensíveis de saúde, dados de pacientes e sistemas críticos contra acessos não autorizados, 
reduzindo riscos de violação de dados e garantindo conformidade com legislações aplicáveis (HIPAA, LGPD).

### 2. Escopo

Esta política se aplica a:
 * Todos os colaboradores, médicos, prestadores de serviço, parceiros e terceiros com acesso aos sistemas da ACME Healthcare;
 * Todos os dispositivos corporativos e pessoais autorizados a acessar sistemas e dados da empresa (BYOD – Bring Your Own Device, quando autorizado);
 * Todos os sistemas de informação, redes, aplicativos, servidores, dispositivos móveis e serviços de nuvem corporativos.

### 3. Política
**3.1. Requisitos de Senha**
 * Senhas devem ter no mínimo 12 caracteres;
 * Devem incluir obrigatoriamente letras maiúsculas, minúsculas, números e caracteres especiais;
 * É proibido o uso de informações pessoais (nome, data de nascimento, número de documento, nome de familiares, etc.);
 * Senhas não podem ser reutilizadas nas últimas 10 trocas.

**3.2. Expiração e Renovação**
 * Senhas devem ser alteradas a cada 90 dias;
 * Troca imediata de senha em caso de suspeita de comprometimento;
 * Contas inativas por mais de 30 dias devem ser bloqueadas automaticamente.

**3.3. Autenticação Multifator (MFA)**
 * Obrigatória para todos os acessos a sistemas que contenham informações de pacientes, dados financeiros ou informações de saúde protegidas (PHI);
 * A MFA deve ser implementada via aplicativo autenticador, token físico ou SMS criptografado.

**3.4. Proteção e Armazenamento**
* Todas as senhas devem ser armazenadas de forma criptograficamente segura (ex.: bcrypt, Argon2, PBKDF2);
* É proibido armazenar senhas em arquivos de texto, planilhas ou transmiti-las por e-mail/mensagens não seguras;
* A ACME fornecerá um cofre de senhas corporativo para credenciais de uso compartilhado quando necessário.

**3.5. Tentativas de Login e Bloqueio**
* Após 5 tentativas falhas, a conta será bloqueada automaticamente;
* O desbloqueio exigirá contato com o Service Desk de TI e autenticação adicional.

### 4. Responsabilidades
  * **Usuários**:
    * Criar e manter senhas seguras;
    * Não compartilhar credenciais com terceiros;
    * Reportar imediatamente incidentes de segurança relacionados a senhas.
  * **Equipe de TI e Segurança da Informação (SI)**:
    * Implementar e monitorar o cumprimento da política;
    * Configurar expiração, complexidade e MFA em todos os sistemas;
    * Auditar logs de autenticação regularmente.
  * **Gestores**:
    * Garantir que suas equipes estejam em conformidade;
    * Apoiar treinamentos e conscientização sobre segurança de credenciais.

### 5. Conformidade e Consequências
O não cumprimento desta política poderá resultar em:

 * Suspensão ou revogação imediata de acesso;
 * Ações disciplinares internas, incluindo desligamento;
 * Responsabilidade civil e/ou criminal em casos de negligência que levem a vazamento de dados de pacientes.

### 6. Revisão e Atualização
Esta política será revisada anualmente pelo **CISO da ACME Healthcare** ou sempre que houver mudanças regulatórias, tecnológicas ou incidentes relevantes.

----------------------------------------------------------

### Etapa 2: Criar um procedimento
a.    Crie um conjunto de instruções passo a passo que ofereça suporte à sua política de segurança da informação. Acesse a Política de segurança da informação - Guia de desenvolvimento e redação técnica de Políticas de segurança de TI em cinco etapas fáceis para obter instruções e orientações.
Observação: todos os links acima também serão úteis na Parte 4 deste laboratório. Mantenha-os abertos e marque-os como favoritos.
b.    Inclua todas as informações de que um usuário precisa para configurar ou concluir a tarefa corretamente de acordo com a política de segurança.

### Parte 4: Desenvolva um plano para disseminar e avaliar políticas
### Etapa 1: Crie um plano de implementação e disseminação de política de segurança da informação.
a.    Documente as informações necessárias para criar um plano de implementação e disseminação de política de segurança de informações.
b.    Inclua tarefas e eventos específicos que os serviços de saúde da ACME usarão para garantir que todos os funcionários envolvidos estejam cientes das políticas de segurança das informações que lhes dizem respeito.
c.    Inclua todos os departamentos específicos que precisam ser envolvidos. Os serviços de saúde da ACME também devem ser capazes de avaliar se os indivíduos têm o conhecimento adequado das políticas que dizem respeito a suas responsabilidades profissionais.

Conclusão

As políticas de segurança da informação fornecem uma estrutura de como uma empresa protege seus ativos e são uma proteção que a empresa utiliza para reduzir riscos. Este projeto examinou por que uma empresa desenvolve políticas de segurança da informação e as diferenças entre políticas, padrões, diretrizes e procedimentos de segurança da informação. Este projeto também explorou como uma empresa divulga e avalia políticas de segurança da informação.



