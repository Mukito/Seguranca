# ✅ HIPAA Security Rule – Checklist Técnico

## 🔐 Controle de Acesso
- [ ] Cada usuário possui **ID único** e senha forte  
- [ ] Implementado **controle de acesso baseado em funções (RBAC)**  
- [ ] Ativado **MFA (autenticação multifator)** para acessos críticos  

## 👤 Identificação e Autenticação de Usuários
- [ ] Procedimentos garantem que apenas usuários autorizados acessem o sistema  
- [ ] Senhas seguem regras fortes (mínimo de caracteres, complexidade, expiração)  
- [ ] Opções de autenticação biométrica ou tokens configuradas  

## 🔒 Criptografia
- [ ] Dados armazenados (em repouso) estão criptografados (AES-256 ou equivalente)  
- [ ] Dados transmitidos usam **TLS 1.2+** (HTTPS, VPN)  
- [ ] E-mails com ePHI são enviados com criptografia segura  

## 📜 Auditoria e Logs
- [ ] Sistema registra **quem acessou, quando e o que fez** no ePHI  
- [ ] Logs são armazenados de forma segura e revisados regularmente  
- [ ] Alertas para tentativas de acesso indevido estão configurados  

## 🛡️ Integridade dos Dados
- [ ] Mecanismos de **hash/checksum** ou controles semelhantes implementados  
- [ ] Rotina de backups valida a integridade dos arquivos  

## 🌐 Transmissão Segura
- [ ] VPN configurada para conexões remotas  
- [ ] Wi-Fi do consultório é protegido (WPA3, senha forte, rede separada para visitantes)  
- [ ] Proibido uso de Wi-Fi público sem VPN para acessar ePHI  

## 💽 Mídias e Dispositivos
- [ ] Pendrives/HDs externos só usados se **criptografados**  
- [ ] Procedimento de descarte seguro de mídias (wipe ou destruição física)  
- [ ] Dispositivos móveis com acesso a ePHI usam senha, criptografia e bloqueio automático  

## ⏲️ Sessões e Inatividade
- [ ] Computadores bloqueiam automaticamente após X minutos de inatividade  
- [ ] Reautenticação exigida para retomar a sessão  

## 📂 Backup e Recuperação
- [ ] Backups automáticos e regulares configurados  
- [ ] Backups armazenados em local seguro (cloud compatível com HIPAA ou offsite)  
- [ ] Testes periódicos de **recuperação de desastres** realizados  

## 🔍 Segurança de Rede
- [ ] Firewall ativo e configurado corretamente  
- [ ] IDS/IPS implementado para detectar/prevenir invasões  
- [ ] Antivírus/EDR atualizado em todos os dispositivos  
