<img width="1280" height="600" alt="google-workspace-logotipo" src="https://github.com/user-attachments/assets/8eedaba1-9511-4aba-bf1f-34a8167edc7a" />


# Projeto NotbookLM Help Center Gmail

Bem-vindo ao repositório do meu projeto de estudo prático focado em IA aplicada ao suporte técnico. Este projeto foi desenvolvido para o desafio de aprendizagem ativa, utilizando o **NotebookLM** para criar um assistente especializado em **Google Workspace (foco em Gmail)**.

---

## 🎯 Contexto e Objetivos
Como estagiária de Customer Success na [Qi Network], percebi a necessidade de centralizar e agilizar a consulta de procedimentos técnicos do Google Workspace. 

**Objetivos do projeto:**
* Criar uma base de conhecimento curada e confiável utilizando documentação oficial.
* Desenvolver um assistente de IA capaz de auxiliar na resolução de tickets de suporte relacionados ao Gmail.
* Demonstrar competência técnica na extração de informações de logs, configurações de DNS (SPF, DKIM, DMARC) e diretrizes de segurança.

---

## 📚 Curadoria de Fontes
Utilizei fontes oficiais do ecossistema Google para garantir que as respostas da IA sejam técnicas e seguras.

1. **[Troubleshoot problems receiving emails](https://knowledge.workspace.google.com/admin/support/troubleshooting/troubleshoot-problems-receiving-emails-in-gmail)** - Documentação técnica de diagnóstico.
2. **[Google Workspace Help Center](https://knowledge.workspace.google.com/admin/support/google-workspace-support-offerings?hl=pt-br)** - Base de conhecimento administrativa.
3. **[Entendendo registros SPF, DKIM e DMARC](https://knowledge.workspace.google.com/admin/security/about-authentication-methods?hl=pt-br)** - Documentação técnica oficial sobre segurança de e-mail.
4. **[Comunidade de Administradores GW](https://support.google.com/a/community)** - Estudos de caso reais de usuários.
5. **[Sobre a DLP para o Gmail](https://knowledge.workspace.google.com/admin/security/prevent-data-leaks-in-email-and-attachments-gmail-dlp?hl=pt-br)** - Prevenção contra perda de dados (DLP) para o Gmail documentação oficial do Google.

---

## 🧠 Engenharia de Prompts e "Cicatrizes"
*Documentação do aprendizado (Troubleshooting):*

| Problema | Prompt Utilizado | Resultado/Aprendizado |
| :--- | :--- | :--- |
| Erro de entrega | "Por que meu e-mail não chega?" (Vago) | Ajustado para: "Analise o log de erro X no ELS..." |
| Identificação de falha | "O usuário não loga" | Aprendi a pedir o passo a passo de verificação de navegador/cache primeiro. |

**Lições Aprendidas:** A qualidade da resposta depende diretamente da especificação do erro no prompt e da clareza técnica dos documentos de origem.

---

## 🛠️ Miniguia de Estudo (Entrega Final)

### Resumo Estruturado
* **Fluxo de E-mail:** O Gmail utiliza registros MX para recebimento e protocolos de segurança (SPF/DKIM) para validação.
* **Diagnóstico:** O **Email Log Search (ELS)** é a ferramenta primária de um administrador.

### Glossário de Conceitos
* **SPF (Sender Policy Framework):** Especifica quais servidores podem enviar e-mails em nome do seu domínio.
* **DKIM (DomainKeys Identified Mail):** Adiciona uma assinatura digital aos e-mails para garantir que não foram alterados.
* **DMARC:** Protocolo que utiliza SPF e DKIM para fornecer instruções ao servidor do destinatário sobre como lidar com e-mails não autenticados.

### Prompts Reutilizáveis
> "Atue como um Especialista em Workspace. Analise o cabeçalho de mensagem fornecido e identifique qual falha de autenticação (SPF/DKIM/DMARC) está ocorrendo e como corrigir no painel admin."

---
### Resultados
<img width="1906" height="797" alt="image" src="https://github.com/user-attachments/assets/035b98a5-92ad-4af9-8ea2-ea70cee3240a" />
<img width="1916" height="911" alt="image" src="https://github.com/user-attachments/assets/06f35c62-688d-4c89-8f1d-dba60123e375" />
<img width="1915" height="891" alt="image" src="https://github.com/user-attachments/assets/72f07775-7acc-444b-9771-300ee71cde83" />




## 🔗 Referências
* [NotebookLM](https://notebooklm.google.com/)
* [Central de Ajuda Google Workspace](https://support.google.com/a/)

---
*Desenvolvido por **Jessica Aparecida Bueno** | Customer Success Intern*
