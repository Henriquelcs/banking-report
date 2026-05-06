# 📊 Report Mensal Banking — Stone Co.

Report mensal automatizado de chamados de atendimento do time de **Product Ops Banking**.

## 🔗 Acesso

**[→ Acessar o Report](https://henriquelcs.github.io/banking-report/)**

## 📋 Sobre

Este repositório hospeda o report mensal de chamados RC Banking, gerado automaticamente todo dia 1 do mês via Google Apps Script.

O report cobre **15 produtos** da prateleira Banking (Pix, Cartão, Extrato, Guardar, Integrar e outros), com visão macro de evolução por marca e visão micro por produto, incluindo narrativas analíticas geradas pelo Claude (Anthropic).

## ⚙️ Stack

| Componente | Tecnologia |
|---|---|
| Coleta de dados | BigQuery — `banking_conciliacao.productops_dashboard_relatorio_final` |
| Geração de narrativas | Claude API (Anthropic) — `claude-sonnet-4` |
| Automação | Google Apps Script |
| Publicação | GitHub Pages |
| Notificação | Slack — `#productops-baas-alerts` |

## 🗂️ Estrutura

```
banking-report/
└── index.html   ← report do mês corrente (atualizado automaticamente)
```

## 👤 Responsável

**Henrique Silva** · Product Ops / Banking Processes · Stone Co.

---

*Gerado automaticamente todo dia 1 do mês às 08:00 · Product Ops Banking*
