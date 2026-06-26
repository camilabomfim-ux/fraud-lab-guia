<div align="center">

# 🔬 Fraud Lab — Guia de Monitoria

**Site educativo do Fraud Quality Team · Nubank**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-online-6B3FE4?style=flat-square&logo=github)](https://camilabomfim-ux.github.io/fraud-lab-guia/sobre.html)
[![Acesso](https://img.shields.io/badge/acesso-público-059669?style=flat-square)](#)

Ajuda analistas de Investigative Operations a entender o processo de monitoria de qualidade — de onde vêm os apontamentos, o que pode impactar a nota e como contestar.

**→ [Acessar o site](https://camilabomfim-ux.github.io/fraud-lab-guia/sobre.html)**

</div>

---

## 📄 Páginas

| Arquivo | Link | Descrição |
|---|---|---|
| **`sobre.html`** | **[🔗 Abrir](https://camilabomfim-ux.github.io/fraud-lab-guia/sobre.html)** | **Página principal — link compartilhado com os analistas** |
| `monitoria.html` | [🔗 Abrir](https://camilabomfim-ux.github.io/fraud-lab-guia/monitoria.html) | Espelho de `sobre.html` — mesmo conteúdo, uso interno |
| `index.html` | [🔗 Abrir](https://camilabomfim-ux.github.io/fraud-lab-guia/index.html) | Portal do Analista — scorecards por distrito, feedback e contestação |
| `quiz.html` | [🔗 Abrir](https://camilabomfim-ux.github.io/fraud-lab-guia/quiz.html) | Quiz avançado por distrito (mais questões que o quiz embutido) |

> **Link ativo com o time:** sempre `sobre.html`. O link não muda após atualizações — ele sempre reflete a versão mais recente.

---

## 📋 O que tem em `sobre.html`

Página com **6 abas**, pensada para o analista que quer entender como é avaliado:

| Aba | O que cobre |
|---|---|
| 📋 **Scorecard** | Fluxo de avaliação, cardteca, separação entre tipos que impactam a nota e os que geram apenas insights, e 3 níveis de criticidade (🔴 Crítico · 🟡 Médio · 🟢 Baixo) |
| **3 Tipos** | Catch & Release · Apontamentos Externos · Amostra Global Aleatória — com badge de impacto por tipo |
| **O time** | Grade completa de responsabilidades do Pack Quality (✅ é / ❌ não é) |
| **Exemplos** | Casos reais filtráveis por nível de criticidade |
| **Glossário** | 6 termos essenciais: Scorecard, Apontamento, Cardteca, SPOT, Grace Period, Fail Reason |
| 🎮 **Quiz** | 6 questões objetivas para fixar o conteúdo |

**Funcionalidades:**
- ☀️ / 🌙 Alternância entre tema claro e escuro — preferência salva no navegador
- Detecção automática do tema do sistema operacional na primeira visita
- Links diretos para [Cardteca](https://docs.google.com/document/d/1CI71QUlVb2iGZZpydH_r4RLkhL5vyfJ65Azv50IRibU/edit?tab=t.0#heading=h.9gjc525kgluv), [Dashboard](https://us-east-1.quicksight.aws.amazon.com/sn/account/nu-qs-prod/dashboards/d8eff447-81e4-411c-a510-b304f1cc980f/sheets/d8eff447-81e4-411c-a510-b304f1cc980f_f2a90d9c-4ba8-42fb-990b-aaaa37dadd9f) e [Jira de contestações](https://nubank.atlassian.net/servicedesk/customer/portal/350/group/8404/create/20552)

---

## ✅ É responsabilidade do Pack Quality

1. Realizar monitorias nos 3 tipos: Catch & Release, Apontamentos Externos e Amostra Global Aleatória
2. Aplicar o scorecard do distrito em cada revisão — sem desviar do que está definido
3. Verificar se o critério identificado está na cardteca antes de registrar qualquer apontamento
4. Registrar apontamentos e feedbacks no SPOT
5. Encaminhar feedbacks ao distrito para subsidiar melhorias de processo
6. Garantir consistência entre qualiters por meio de calibrações com especialistas do distrito
7. Manter dashboards e relatórios de qualidade atualizados
8. Assegurar que os próprios qualiters sigam o processo definido pelo distrito

## ❌ Não é responsabilidade do Pack Quality

1. Criar, atualizar ou fazer manutenção da cardteca — isso é do distrito
2. Definir quais critérios entram ou saem da cardteca
3. Comunicar mudanças de processo para a operação — isso vem do distrito
4. Elaborar planos de ação individuais ou realizar 1:1s de performance
5. Treinar ou reciclar a operação sobre processos específicos
6. Fazer a contestação em nome do analista — o analista contesta via Jira
7. Resolver dúvidas operacionais do dia a dia — procure a liderança direta

---

## 🛠️ Como atualizar

O site usa **GitHub Pages** (branch `main`, raiz do repositório) — qualquer commit atualiza automaticamente em ~1 minuto.

**Para editar uma página:**
1. Abra o arquivo desejado no GitHub
2. Clique em ✏️ **Edit** (canto superior direito do arquivo)
3. Faça as alterações e clique em **Commit changes**
4. Aguarde ~1 minuto e recarregue com `Ctrl+Shift+R` (Windows) ou `Cmd+Shift+R` (Mac)

**Para adicionar colaboradores ao repositório:**
`Settings → Collaborators → Add people`

---

## ⚠️ Pontos de atenção

- **`sobre.html` e `monitoria.html` têm o mesmo conteúdo.** Ao atualizar um, atualize o outro também para mantê-los sincronizados
- A cardteca referenciada no site é de responsabilidade do distrito — o time de qualidade não a mantém
- O site é público — qualquer pessoa com o link acessa, sem login

---

*Mantido por **Camila Bomfim** · Fraud Quality Team · Nubank · 2026*
