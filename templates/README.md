# Templates de Elaboração Textual - Processo RDM (CMMI 2.0)

Este diretório contém templates textuais para documentação das práticas RDM do CMMI 2.0 (até Nível 2) em contexto ágil.

## 🎯 Estrutura v2 - Orientada à Modelagem Visual

A estrutura v2 foi projetada para **facilitar a geração de diagramas visuais** (PlantUML, BPMN, etc.) a partir da documentação textual.

### Filosofia
- **Texto serve ao Diagrama**: cada seção mapeia elementos visuais específicos
- **Atividades** = Elipses/Retângulos no diagrama
- **Procedimentos/Decisões** = Losangos (pontos de decisão)
- **Papéis** = Swimlanes (raias) que organizam o fluxo
- **Artefatos** = Anotações/Notas anexadas às atividades
- **Recursos** = Ferramentas/tecnologias usadas (opcional no diagrama)

## 📁 Estrutura

```
templates/
├── README.md                           (este arquivo)
├── template-base.md                    (template v2 - 11 seções)
├── instrucoes-preenchimento.md         (guia detalhado v2 - 397 linhas)
├── rdm-1.1-requisitos-stakeholders.md  (exemplo completo v2)
├── rdm-2.1-elicitar-user-stories.md    (a preencher com v2)
├── rdm-2.2-backlog-refinement.md       (a preencher com v2)
├── rdm-2.3-analisar-validar.md         (a preencher com v2)
├── rdm-2.4-sprint-planning.md          (a preencher com v2)
├── rdm-2.5-desenvolvimento.md          (a preencher com v2)
└── rdm-2.6-garantir-consistencia.md    (a preencher com v2)
```

## 🧩 Seções do Template v2

| # | Seção | Emoji | Mapeia no Diagrama |
|---|-------|-------|-------------------|
| 1 | Identificação | 🧱 | Título do diagrama |
| 2 | Objetivo | 🎯 | Descrição geral |
| 3 | Atividades | ⚙️ | **Elipses/Retângulos** (executáveis) |
| 4 | Procedimentos/Decisões | 🔁 | **Losangos** (decisões) |
| 5 | Artefatos | 📦 | Notas/Anotações por atividade |
| 6 | Papéis e Responsabilidades | 👥 | **Swimlanes** (raias) |
| 7 | Recursos/Ferramentas | 🧰 | Opcional (legendas) |
| 8 | Entradas | 🔗 | Setas de entrada |
| 9 | Saídas | 📤 | Setas de saída |
| 10 | Relação com Outras Práticas | 🧩 | Conectores entre diagramas |
| 11 | Notas para Modelador | 🧭 | Instruções técnicas (loops, sync) |

## 🎯 Como Usar

1. **Leia** `instrucoes-preenchimento.md` (guia completo com 397 linhas)
2. **Consulte** `rdm-1.1-requisitos-stakeholders.md` (exemplo preenchido)
3. **Copie** `template-base.md` para criar nova prática
4. **Renomeie** seguindo padrão: `rdm-X.X-nome-descritivo.md`
5. **Preencha** as 11 seções orientando-se pelos emojis
6. **Revise** com a equipe antes de considerar completo
7. **Modele** o diagrama visual usando as informações estruturadas
8. **Commite** quando aprovado

## 👥 Distribuição de Trabalho Sugerida

| Prática | Responsável | Status |
|---------|-------------|--------|
| RDM 1.1 | [Nome] | ✅ Exemplo preenchido |
| RDM 2.1 | [Nome] | ⏳ A preencher |
| RDM 2.2 | [Nome] | ⏳ A preencher |
| RDM 2.3 | [Nome] | ⏳ A preencher |
| RDM 2.4 | [Nome] | ⏳ A preencher |
| RDM 2.5 | [Nome] | ⏳ A preencher |
| RDM 2.6 | [Nome] | ⏳ A preencher |

## 🔗 Referências
- [Diagrama Parcial (até RDM 2.3)](../diagramas/RDM_Agil_Compacto_Parcial.png)
- [Diagrama Completo](../diagramas/RDM_Agil_Compacto_Parcial_Completa.png)

## 📝 Observações
- Cada template segue a estrutura padrão definida pela equipe
- Artefatos marcados como "essencial" ou "recomendado" conforme diagramas
- Templates podem ser adaptados conforme necessidade do projeto
