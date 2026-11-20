# 📊 NutriBio — Quadro Kanban Ágil & Backlog

**Papel:** Full-Stack Lead, UX/UI & Product Owner (PO)  
**Metodologia:** Kanban Contínuo (Prioridades flexíveis e dinâmicas)  
**Design System:** Botanical Vitality  
**Última Atualização:** 19/11/2026  

---

## 🧭 Quadro Kanban

```
┌─────────────────┬─────────────────┬─────────────────┬─────────────────┬─────────────────┐
│   📥 BACKLOG    │    🎯 TO DO     │  ⚡ IN PROGRESS │   🔍 REVIEW/QA  │     ✅ DONE     │
│   (Idéias/Fut)  │  (Priorizado)   │  (Desenvolvendo)│ (Validar c/User)│   (Entregue)    │
└─────────────────┴─────────────────┴─────────────────┴─────────────────┴─────────────────┘
```

---

### ⚡ IN PROGRESS (Em Andamento)
> *Itens sendo executados neste exato momento.*

*(Nenhum item em execução no momento — aguardando você definir a próxima puxada!)*

---

### 🔍 REVIEW / QA (Aguardando Validação)
> *Entregues recentemente para o usuário testar e aprovar.*

- **[NB-004] [Full-Stack & UX/UI] Menu do Perfil com Detalhes e Troca de Senha**
  - **O que foi feito:** Menu ao clicar no avatar, modal de detalhes do perfil com metas e modal de alteração de senha persistida em `localStorage`.
  - **Arquivos:** [index.html](file:///c:/Users/dayan/OneDrive/Documentos/Área%20de%20Trabalho/Projetos%20Copiloto/index.html)

---

### 🎯 TO DO (Priorizado — Pronto para Iniciar)
> *Próximas demandas ordenadas por valor de produto. Pode ser reordenado a qualquer momento por você.*

1. **[P1] [NB-005] [Full-Stack & UX/UI] Adicionar Refeições (Botão "Adicionar Jantar" / "+")**
   - **UX/UI:** Modal limpo para registrar prato, escolher tipo (Café, Almoço, Lanche, Jantar) e informar calorias/macros.
   - **Frontend:** Atualização em tempo real do anel SVG de calorias e barras de macronutrientes.
   - **Backend/Data:** Persistência no histórico diário do usuário ativo.
2. **[P1] [NB-006] [Backend & Segurança] Estruturação da Camada de API / Backend Local**
   - **Backend:** Criação de servidor Node.js/Express ou Python/FastAPI para servir rotas `/api/auth`, `/api/meals`, `/api/nutrients` e banco SQLite/JSON.
3. **[P2] [NB-007] [Frontend & UX/UI] Tela / Aba de Micronutrientes (Micros)**
   - **UX/UI:** Detalhar lista completa de vitaminas (A, B complex, C, D) e minerais essenciais com barras de status.
4. **[P2] [NB-008] [Frontend & UX/UI] Tela / Aba de Relatórios Semanais**
   - **UX/UI:** Gráficos de tendências e médias calóricas dos últimos 7 a 30 dias.

---

### 📥 BACKLOG (Idéias & Futuras Demandas)
> *Banco de ideias e melhorias sugeridas para priorização sob demanda.*

- **[P3] [NB-009] [UX/UI] Upload de Foto Real de Perfil:** Permitir carregar imagem local para o avatar.
- **[P3] [NB-010] [Frontend] Histórico por Calendário:** Navegar por dias anteriores clicando em "Hoje, 24 de Maio".
- **[P3] [NB-011] [Backend] Leitor / Scanner de Código de Barras de Alimentos:** Integração de API de tabela nutricional (ex: Open Food Facts).
- **[P4] [NB-012] [Full-Stack] Modo Escuro (Dark Mode):** Alternância com base no design token do Stitch.

---

### ✅ DONE (Concluído & Entregue)

- [x] **[NB-001] [Setup] Exportação Stitch & Assets Locais:** Download do projeto Stitch, design tokens e criação do logotipo SVG nativo.
- [x] **[NB-002] [Full-Stack & UX/UI] Tela de Login & Gestão de Sessão:** [login.html](file:///c:/Users/dayan/OneDrive/Documentos/Área%20de%20Trabalho/Projetos%20Copiloto/login.html) com acesso rápido, 3 usuários teste e cadastro.
- [x] **[NB-003] [Frontend & UX/UI] Dashboard Diário Responsivo:** [index.html](file:///c:/Users/dayan/OneDrive/Documentos/Área%20de%20Trabalho/Projetos%20Copiloto/index.html) com anel de calorias SVG animado, macros e rastreador de hidratação (+250ml).
- [x] **[NB-004] [Frontend & UX/UI] Governança Full-Stack, UX/UI & Kanban:** Estruturação dos arquivos `AGENTS.md`, `.agents/agents/nutribio-po.md` e `BACKLOG.md`.
- [x] **[NB-005] [DevOps & Git] Repositório Criado e Código Versionado no GitHub:** Repositório `dayanel/nutribio` criado com upload de todos os arquivos de layout, assets e regras.

---

## ⚡ Regras do Nosso Kanban
- **Flexibilidade Total:** Se você decidir mudar de foco no meio de um desenvolvimento, basta dizer e nós pivotamos imediatamente.
- **Transparência:** Toda entrega é acompanhada de link direto para os arquivos e instruções rápidas de teste.
- **Full-Stack & Design:** Todas as tarefas passam pelo crivo de UX/UI, frontend e backend/persistência.
