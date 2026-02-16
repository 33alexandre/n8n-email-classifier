# n8n Email Classifier

![n8n](https://img.shields.io/badge/n8n-workflow-blue)
![GitHub](https://img.shields.io/badge/GitHub-repo-black)

Workflow n8n para classificar e-mails como **URGENTE** ou **NORMAL** usando IA e regras simples.

---

## Repositório

Projeto disponível em:  
[https://github.com/33alexandre/n8n-email-classifier.git](https://github.com/33alexandre/n8n-email-classifier.git)

---

## Como usar

1. Abra o n8n → **Workflows → Import**.  
2. Selecione o arquivo `fluxo_email.json`.  
3. Configure:  
   - **Gmail Trigger** com sua conta  
   - Labels **URGENTE** e **NORMAL** no Gmail  
4. Salve e ative o workflow.

---

## Testes rápidos

| Assunto | Resultado esperado |
|---------|------------------|
| Redefinição de senha do cartão | URGENTE |
| Pagamento vencendo hoje | URGENTE |
| Newsletter semanal | NORMAL |
| Confirmação de reunião futura | NORMAL |

---

## Observação

O arquivo JSON **não contém credenciais** e é seguro subir no GitHub.
