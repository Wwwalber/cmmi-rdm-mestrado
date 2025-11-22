# Instruções de Preenchimento dos Templates RDM (Estrutura v2)

Este guia detalha como preencher adequadamente os templates de elaboração textual das práticas RDM, alinhados com a estrutura do Prof. Sandro (atividades, procedimentos, artefatos e recursos) para facilitar a diagramação visual.

---

## 🎯 Objetivo do Template

O template serve como **roteiro textual para diagramação**. Cada seção tem um propósito específico na modelagem visual do processo.

---

## 📋 Estrutura do Template v2

### **🧱 1. Identificação da Prática**

**Como preencher:**
- **Código**: Use o código oficial da prática (ex: RDM 1.1, RDM 2.1, etc.)
- **Nível**: Marque ✅ no nível CMMI correspondente (1 ou 2)
- **Responsável**: Nome do membro da equipe que está documentando

**Exemplo:**
```markdown
* **Código:** RDM 2.1
* **Nível:**   ☐ 1   ✅ 2 
* **Responsável:** João Silva
```

---

### **🎯 2. Objetivo da Prática**

**Como preencher:**
- Descreva em 2-3 linhas o propósito principal dentro do processo RDM
- Foque no VALOR que a prática entrega
- Contextualize para o ambiente ágil

**Exemplo bom:**
> "Registrar de forma organizada os requisitos coletados junto aos stakeholders, servindo de base para priorização e rastreabilidade durante todo o ciclo de desenvolvimento."

**Exemplo ruim:**
> "Fazer reuniões." (muito vago e sem contexto)

**Dica:** Responda "Por que esta prática existe?" e "Que problema ela resolve?"

---

### **⚙️ 3. Atividades (sequência lógica para o diagrama)**

**Como preencher:**
- Liste de 5 a 10 atividades em **sequência cronológica** (como uma receita de bolo)
- Use verbos de ação no infinitivo
- Cada item será uma **elipse (atividade)** no diagrama
- Seja específico mas conciso

**Exemplo:**
```markdown
1. Reunir para levantar requisitos.
2. Registrar as necessidades no backlog.
3. Validar entendimento coletivo.
4. Armazenar o registro final.
```

**Importante:** 
- Ordene pela sequência real de execução
- Evite atividades muito genéricas ("fazer análise")
- Prefira ações concretas ("revisar critérios de aceitação com o time")

**Dica visual:** No diagrama, essas atividades aparecerão como elipses conectadas por setas.

---

### **🔁 4. Procedimentos e Decisões (condicionais do fluxo)**

**Como preencher:**
- Descreva **decisões ou ramificações** que podem ocorrer durante as atividades
- Serão representadas como **losangos (decisão)** no diagrama
- Use formato: "(na atividade X) Pergunta? (Sim → ação / Não → ação)"

**Exemplo:**
```markdown
- (na atividade 3) O requisito foi compreendido? 
  (Sim → registrar / Não → retornar à etapa de esclarecimento)
  
- (na atividade 5) É necessário criar personas? 
  (Sim → executar atividade 6 / Não → pular para atividade 7)
```

**Importante:**
- Cada decisão precisa ter **duas saídas** (Sim/Não, Aprovado/Rejeitado, etc.)
- Indique qual atividade vem em cada caminho
- Se não houver decisões, escreva "Não há decisões condicionais nesta prática"

**Dica visual:** No diagrama, aparecem como losangos com duas setas de saída.

---

### **📦 5. Artefatos / Produtos de Trabalho**

**Como preencher:**
- Liste artefatos **por atividade** (entrada/saída)
- Formato: **"Atividade X - Entrada: ... / Saída: ..."**
- Indique classificação: (essencial), (recomendado), (opcional)

**Exemplo:**
```markdown
- **Atividade 1** - Saída: Ata com requisitos coletados
- **Atividade 2** - Entrada: User stories / Saída: Product Backlog
- **Atividade 3** - Entrada: Product Backlog / Saída: Acordo de validação
- **Atividade 4** - Saída: Product Backlog digital (essencial), Planilha de rastreabilidade (recomendado)
```

**Importante:**
- Nem toda atividade precisa ter entrada E saída
- Artefatos essenciais são obrigatórios para o processo
- Use nomes específicos, não genéricos ("Documento X" vs "Documentação")

**Dica visual:** No diagrama, aparecem como retângulos ou notas anexadas às atividades.

---

### **👥 6. Papéis Envolvidos (Raias / Swimlanes)**

**Como preencher:**
- Marque ✅ ou ☐ para cada papel
- Na coluna "Ação", especifique se: **executa / valida / apoia**
- Use verbos de ação

**Exemplo:**
```markdown
| Papel | Participa? | Ação (executa / valida / apoia) |
| ----- | :---: | ----- |
| 🧑‍💼 Product Owner | ✅ | Executa: conduz workshops, documenta visão |
| 👥 Time de Desenvolvimento | ✅ | Apoia: participa de validações técnicas |
| 🧑‍🔧 Scrum Master | ☐ | - |
```

**Importante:**
- Papéis marcados determinam as **swimlanes** (raias) do diagrama
- Seja específico sobre o que cada papel FAZ nesta prática
- Se um papel não participa, deixe ☐ e hífen (-)

**Dica visual:** No diagrama, cada papel marcado terá uma raia horizontal.

---

### **🧰 7. Recursos Utilizados (Humanos e Não Humanos)**

**Como preencher:**
- Liste **pessoas, ferramentas, softwares e documentos** usados
- Separe em categorias

**Exemplo:**
```markdown
- **Humanos:** Stakeholders, Product Owner, usuários finais
- **Ferramentas:** Jira, Miro, Confluence
- **Documentos:** Template de visão, formulários de coleta
- **Outros:** Sala de reunião, quadro branco, post-its
```

**Importante:**
- Recursos humanos ≠ Papéis (recursos são QUEM ajuda, papéis são RESPONSABILIDADES)
- Seja específico com nomes de ferramentas
- Inclua recursos físicos se relevantes

---

### **🔗 8. Entradas (início do fluxo)**

**Como preencher:**
- Liste **o que é necessário ANTES** de iniciar as atividades
- São os gatilhos ou pré-requisitos
- Pense: "O que preciso ter para começar?"

**Exemplo:**
```markdown
- Objetivos estratégicos do negócio
- Mapa de stakeholders
- Solicitação formal de novo produto/feature
- Backlog de produtos anteriores (se existir)
```

**Importante:**
- Diferentes de artefatos gerados (que são saídas)
- Podem vir de outras práticas RDM ou externos
- Se não houver entradas específicas, escreva "Demanda de stakeholders" ou similar

**Dica visual:** No diagrama, aparecem como símbolos de início ou documentos de entrada.

---

### **📤 9. Saídas (final do fluxo)**

**Como preencher:**
- Liste **o que é produzido AO FINAL** de todas as atividades
- São os entregáveis consolidados
- Pense: "O que entrego quando termino?"

**Exemplo:**
```markdown
- Visão do Produto aprovada e documentada (essencial)
- Épicos de alto nível registrados no GitHub (essencial)
- User Story Map criado e compartilhado (recomendado)
- Validação formal dos stakeholders
```

**Importante:**
- Saídas são o resultado COMPLETO da prática
- Incluem artefatos essenciais e recomendados
- Serão entradas para outras práticas RDM

**Dica visual:** No diagrama, aparecem como símbolos de fim ou documentos de saída.

---

### **🧩 10. Relação com Outras Práticas RDM**

**Como preencher:**
- Indique de onde recebe entrada e para onde envia saída
- Formato: **"Entrada de: ..."** e **"Fornece saída para: ..."**
- Adicione observações sobre revisitações

**Exemplo:**
```markdown
- **Entrada de:** RDM 1.1 (Requisitos dos Stakeholders)
- **Fornece saída para:** RDM 2.2 (Backlog Refinement)
- **Pode ser revisitada por:** Mudanças de escopo, feedback de Sprint Review
```

**Importante:**
- Ajuda a conectar subprocessos no diagrama geral
- Mostra o fluxo entre práticas RDM
- Identifica loops e revisitações

**Dica visual:** No diagrama, aparecem como conectores entre subprocessos.

---

### **🧭 11. Notas e Observações para o Modelador Visual**

**Como preencher:**
- Inclua **dicas específicas** para quem vai criar o diagrama
- Indique: loops, sincronizações, fluxos alternativos, frequência
- Use bullet points

**Exemplo:**
```markdown
- **Frequência:** Executada no início do projeto (Sprint 0)
- **Loop de validação:** Da atividade 7, se não validado, retornar à atividade 1
- **Fluxo alternativo:** Se já existe visão documentada, pular atividade 3
- **Sincronização:** Barra de sincronização após atividade 6 antes de arquivar
- **Swimlanes principais:** Product Owner coordena, Stakeholders fornecem input
```

**Importante:**
- Esta seção é CRUCIAL para diagramação correta
- Inclua tudo que não cabe nas outras seções mas é importante visualmente
- Pense em quem vai modelar: o que ele precisa saber?

---

## ✅ Checklist Antes de Considerar Completo

- [ ] Todas as 11 seções estão preenchidas
- [ ] Objetivo está claro e contextualizado (2-3 linhas)
- [ ] Atividades estão em sequência lógica (5-10 itens)
- [ ] Decisões condicionais estão mapeadas (se houver)
- [ ] Artefatos estão organizados por atividade (entrada/saída)
- [ ] Papéis estão marcados com ações específicas
- [ ] Recursos listados (humanos, ferramentas, documentos)
- [ ] Entradas do fluxo estão definidas
- [ ] Saídas do fluxo estão definidas
- [ ] Relação com outras práticas RDM está clara
- [ ] Notas para diagramação estão completas
- [ ] Data de atualização e responsável preenchidos
- [ ] Ortografia e gramática revisadas

---

## 🎨 Dicas Gerais para Preenchimento

### ✍️ Escrita Clara
- Use frases curtas e objetivas
- Prefira verbos de ação
- Evite jargões desnecessários
- Seja consistente com a terminologia

### 📐 Pensamento Visual
- Ao preencher, imagine o diagrama sendo desenhado
- Atividades = elipses conectadas
- Decisões = losangos com bifurcações
- Papéis = raias horizontais
- Artefatos = retângulos ou notas

### � Iteração
- Primeira versão não precisa ser perfeita
- Revise após preencher todas as seções
- Peça feedback da equipe
- Ajuste conforme necessário

### 🤝 Colaboração
- Preencha em conjunto com quem executa a prática
- Valide com Product Owner e Scrum Master
- Teste o preenchimento fazendo um rascunho de diagrama

---

## 🔗 Referências

- [Template Base v2](template-base.md)
- [Exemplo Completo: RDM 1.1](rdm-1.1-requisitos-stakeholders.md)
- [Diagramas do Processo](../diagramas/)
- Estrutura baseada em: Prof. Sandro (atividades, procedimentos, artefatos, recursos)

---

## ❓ Dúvidas Frequentes

**P: Posso pular alguma seção?**
R: Não. Todas as 11 seções são obrigatórias. Se algo não se aplica, escreva "Não aplicável" ou "Não há".

**P: Quantas atividades devo listar?**
R: Entre 5 e 10 é ideal. Menos que 5 pode estar muito genérico, mais que 10 pode estar muito detalhado.

**P: E se não houver decisões condicionais?**
R: Escreva "Não há decisões condicionais nesta prática. Fluxo linear."

**P: Como sei se um artefato é essencial ou recomendado?**
R: Essencial = sem ele, a prática não cumpre seu objetivo. Recomendado = melhora qualidade mas não é obrigatório.

**P: Preciso ser muito técnico?**
R: Não. O template deve ser compreensível para toda a equipe, incluindo stakeholders não-técnicos.

---

**Última atualização**: 12/Nov/2025  
**Versão**: 2.0 (orientada à diagramação)
