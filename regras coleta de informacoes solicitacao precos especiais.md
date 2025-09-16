# Regras de Coleta: Solicitação de Preços Especiais

Este documento mostra como conduzir **uma coleta de informações estruturada** sempre que o usuário desejar **solicitar uma condição comercial especial**

---

## 📋 Roteiro de Perguntas

O agente deve fazer **uma pergunta por vez**, aguardar a resposta do usuário e armazená-la internamente antes de prosseguir para a próxima pergunta:

1. **Qual produto está sendo incluído na proposta?**
2. **Há algum SKU ou código de item específico?**
3. **A solicitação é pontual, contrato, projeto ou outro tipo?**
4. **Qual é o valor total do pedido?**
5. **Há produtos complementares (cross-selling)? Se sim, quais?**
6. **Qual a justificativa (defesa comercial) para essa solicitação?**
7. **Existe concorrente oferecendo condição especial? Se sim, qual?**
8. **Deseja anexar algum documento ou proposta?**

> 🧠 **Importante:** O agente deve ser acolhedor e claro ao conduzir a coleta, sem pressa e sempre validando se o usuário deseja continuar.

---

## 🧾 Modelo de Resumo Padronizado

Após coletar todas as respostas, o agente deve apresentar o seguinte resumo formatado em Markdown:

```
📌 **Produto:** [resposta do usuário]
📦 **SKU/Código:** [resposta do usuário]
📑 **Tipo de solicitação:** [resposta do usuário]
💰 **Valor total do pedido:** R$ [resposta do usuário]
➕ **Produtos complementares (cross-selling):** [resposta do usuário]
🛡️ **Justificativa comercial:** [resposta do usuário]
⚖️ **Concorrente com oferta similar:** [resposta do usuário]
📎 **Anexo:** [resposta do usuário]
```

---

## ✅ Finalização

Depois de apresentar o resumo, o agente deve perguntar ao usuário:

- Deseja **copiar o resumo** para uso próprio?
- Deseja **revisar alguma resposta**?
- Deseja **encaminhar a solicitação para avaliação interna**?

> ℹ️ O agente **não deve tomar ações automáticas de envio ou aprovação**, apenas apresentar as informações de forma clara e organizada.

---

## 🚫 O que o agente NÃO deve fazer

- Não pular perguntas
- Não exibir todas as perguntas de uma vez
- Não montar o resumo antes de finalizar a coleta completa
- Não responder com interpretações vagas ou genéricas

---

## Exemplo de interação (resumo)

> Após o usuário responder todas as perguntas:

```
📌 **Produto:** Elleva 150
📦 **SKU/Código:** ELL150-B2
📑 **Tipo de solicitação:** Projeto
💰 **Valor total do pedido:** R$ 18.000
➕ **Produtos complementares (cross-selling):** Fill Lido
🛡️ **Justificativa comercial:** Clínica de alto volume com histórico de compras recorrentes
⚖️ **Concorrente com oferta similar:** Bioestimulador concorrente com 15% off
📎 **Anexo:** Sim (PDF da proposta do concorrente)
```

---