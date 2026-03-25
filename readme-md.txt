# 🥟 Koncluí — Sistema Operacional Pastel da Camila

> Sistema de checklists inteligentes para gestão de turnos de franquias.  
> Desenvolvido para **Pastel da Camila** · Powered by **Koncluí**

[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://checklist-subgerencia.netlify.app)

---

## 🚀 Acesso

**URL de produção:** [checklist-subgerencia.netlify.app](https://checklist-subgerencia.netlify.app)

---

## 👤 Usuários e Acessos

| Login | Senha | Função | Acesso |
|-------|-------|--------|--------|
| `gabriela` | `2026` | Subgerente | Checklist operacional |
| `vitoria` | `2026` | Subgerente | Checklist operacional |
| `derik` | `2026` | Gerência | Checklist Gerência — Visão do Turno |
| `gerente` | `2026` | Gerente | Checklist + Painel |
| `bruna` | `2026` | Suporte | Gestão de usuários + Painel |
| `camila` | `2026` | CEO | Dashboard completo |

> ⚠️ Senhas podem ser alteradas pelo usuário **Suporte (Bruna)** via painel de gestão de usuários.

---

## 📋 Checklists Disponíveis

### 🔴 Checklist Operacional (Subgerentes)
Para os turnos **Manhã** e **Tarde/Noite**.  
Seções: Abertura · Produção · Operação · Passagem/Fechamento  
Configurável por contexto: delivery, novato, falta, troco.

### 🏢 Checklist Gerência — Visão do Turno (Derik)
**4 blocos · 17 itens**

| Bloco | Itens |
|-------|-------|
| 📊 Visão Geral do Turno | Caixa, metas, delivery, passagem |
| 👥 Equipe e Atendimento | Presença, uniforme, atendimento, reclamações |
| 🥟 Produção e Qualidade | Padrão, estoque, temperatura, descarte |
| 🏠 Estrutura e Organização | Equipamentos, limpeza, organização, segurança |

> **Regra crítica:** Marcar "Não" abre formulário obrigatório com 6 campos — não é possível enviar sem preencher tudo.

---

## 📊 Dashboard CEO (Camila)

Abas disponíveis:
- **📊 Geral** — KPIs, score por dia, status dos turnos
- **🏢 Gerência** — Relatórios do Derik, histórico, falhas por bloco
- **🏆 Ranking** — Score médio por subgerente
- **🚨 Alertas** — Itens críticos em aberto
- **📋 Turnos** — Histórico completo
- **📈 Tendência** — Evolução semanal

---

## 🛠️ Tecnologias

- **Frontend:** React 18 (via CDN) + Babel Standalone
- **Estilo:** CSS puro · Design System iFood-inspired
- **Storage:** localStorage (dados persistem no navegador)
- **Webhook:** Make.com (envio automático por e-mail)
- **Deploy:** Netlify (auto-deploy via GitHub)
- **Fonte:** Sora + Inter (Google Fonts)

---

## 📁 Estrutura do Repositório

```
checklist-subgerencia/
├── index.html              # App principal (single file)
├── netlify.toml            # Configuração Netlify
├── README.md               # Este arquivo
└── .gitignore
```

---

## 🔄 Como Atualizar

1. Edite o `index.html` no GitHub
2. Faça commit na branch `main`
3. Netlify detecta e faz deploy automático em ~30 segundos

---

## 📦 Versão

**v4.0** · Koncluí 2026  
Última atualização: Março 2026  
Inclui: Checklist Gerencial (Derik) + Dashboard CEO com aba Gerência

---

## 📬 Contato

E-mail operacional: `pasteldacamilasuporte@gmail.com`  
WhatsApp gestão: `+55 11 94036-6586`
