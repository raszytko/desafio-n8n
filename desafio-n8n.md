# Desafio Criativo: Planejando Automações com N8N

## 🎯 Prompt Final Estruturado

```text
Atue como um especialista em N8N.

Crie uma automação para registrar automaticamente leads recebidos por formulário.

Público:
Equipe comercial.

Ferramentas envolvidas:
Typeform, Google Sheets, Slack e n8n.

Fluxo:
1. Receber uma nova resposta de formulário preenchida no Typeform (Webhook).
2. Filtrar e formatar os dados do lead (capitalizar nome e validar formato do e-mail).
3. Verificar na planilha do Google Sheets se o e-mail do lead já existe para evitar duplicidade.
4. Inserir uma nova linha no Google Sheets caso o lead seja inédito.
5. Enviar uma notificação estruturada em um canal específico do Slack avisando a equipe comercial sobre o novo lead.

Regras:
- Se o e-mail do lead já existir na planilha, interromper o fluxo principal e salvar o registro em uma aba separada chamada "Duplicados".
- Ignorar e não processar respostas se os campos obrigatórios "Nome" ou "E-mail" estiverem vazios.
- Garantir que o número de telefone seja salvo com o código do país (+55) antes de registrar na planilha.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.
```
