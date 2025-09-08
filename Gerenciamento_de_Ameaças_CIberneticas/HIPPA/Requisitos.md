# ✅ Requisitos Técnicos HIPAA – Segurança da Informação

## 1. Controle de Acesso
- Cada usuário (dentista, assistente, recepcionista) deve ter um **ID exclusivo** e senha segura.  
- Implementar **controle de acesso baseado em função (RBAC)** para limitar o acesso ao ePHI apenas ao necessário.  
- Utilizar **autenticação multifator (MFA)** para logins administrativos e sistemas críticos.  

## 2. Autenticação e Identificação de Usuário
- Procedimentos para verificar que uma pessoa acessando o sistema é quem diz ser.  
- Uso de **senhas fortes, biometria ou tokens de segurança**.  

## 3. Criptografia e Descriptografia
- **Criptografia de dados em repouso e em trânsito** (padrões AES-256, TLS 1.2/1.3).  
- **E-mails com ePHI** devem ser enviados com criptografia segura.  

## 4. Auditoria e Registro de Atividades (Audit Controls)
- Sistemas devem gerar e manter **logs de acesso e de alterações** feitas no ePHI.  
- Monitorar **tentativas de login, falhas de acesso e alterações** em registros.  
- Relatórios devem ser revisados periodicamente.  

## 5. Integridade dos Dados
- Mecanismos para garantir que o ePHI não seja **alterado ou destruído de forma não autorizada**.  
- Implementar **checksums, hashing e backups confiáveis** para validar integridade.  

## 6. Transmissão Segura (Transmission Security)
- Proteger ePHI transmitido por redes (**VPN para conexões remotas, HTTPS para sistemas web**).  
- Proibir o uso de **Wi-Fi público sem VPN** para acessar informações médicas.  

## 7. Dispositivos e Mídias Removíveis
- Políticas para uso de **pendrives, HDs externos e dispositivos móveis**.  
- Caso permitidos, devem estar **criptografados**.  
- Procedimentos para **descarte seguro (data wiping)**.  

## 8. Sessões e Tempo de Inatividade
- **Bloqueio automático** de estações de trabalho após período de inatividade.  
- **Reautenticação exigida** após tempo limite.  

## 9. Planos de Backup e Recuperação
- **Backups automáticos e regulares** de ePHI.  
- Backups **criptografados** e armazenados em local seguro (offsite ou cloud com HIPAA compliance).  
- **Testes periódicos de recuperação de desastres**.  

## 10. Monitoramento de Rede e Segurança Perimetral
- **Firewall devidamente configurado** para proteger contra acessos não autorizados.  
- **IDS/IPS** (sistemas de detecção/prevenção de intrusos).  
- **Antivírus/EDR atualizado** em todos os dispositivos.  
