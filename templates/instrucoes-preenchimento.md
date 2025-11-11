# Instruções de Preenchimento dos Templates RDM

Este guia detalha como preencher adequadamente os templates de elaboração textual das práticas RDM.

## 📋 Estrutura do Template

Cada template possui as seguintes seções obrigatórias:

### 1. Identificação da Prática
- **Código**: Use o código oficial da prática (ex: RDM 1.1, RDM 2.1, etc.)
- **Nível**: Marque o nível CMMI correspondente (1 ou 2)
- **Responsável**: Nome do membro da equipe que está documentando/responsável

### 2. Objetivo da Prática
**Como preencher:**
- Descreva em 2-3 linhas o propósito principal
- Contextualize para o ambiente ágil
- Foque no VALOR que a prática entrega

**Exemplo bom:**
> "Garantir que os requisitos sejam devidamente registrados e compreendidos pelos stakeholders antes da priorização e implementação, estabelecendo uma visão compartilhada do produto."

**Exemplo ruim:**
> "Fazer reuniões." (muito vago e sem contexto)

### 3. Atividades Principais
**Como preencher:**
- Liste de 3 a 7 atividades principais
- Use verbos de ação no infinitivo
- Seja específico mas não detalhado demais
- Ordene cronologicamente quando possível

**Exemplo:**
1. Realizar workshops de descoberta com stakeholders
2. Documentar requisitos em formato de épicos
3. Validar entendimento com Product Owner
4. Registrar no backlog do produto

### 4. Papéis Envolvidos
**Como preencher:**
- Marque com ☑ os papéis que PARTICIPAM
- Deixe ☐ para papéis que NÃO participam
- Descreva a RESPONSABILIDADE ESPECÍFICA nesta prática

**Dica:** Consulte o diagrama de atividades para ver as swimlanes (raias)

### 5. Entradas
**Como preencher:**
- Liste artefatos/informações necessários ANTES de iniciar
- Seja específico sobre o formato/fonte
- Indique se é opcional ou obrigatório

**Exemplos:**
- "Product backlog da sprint anterior"
- "Atas de reuniões com stakeholders"
- "Documento de visão do produto (se existir)"

### 6. Saídas / Artefatos Gerados
**Como preencher:**
- Liste TODOS os artefatos produzidos
- Indique classificação: (essencial), (recomendado), (opcional)
- Referencie a localização/ferramenta (ex: GitHub Issues, Wiki, etc.)

**Formato sugerido:**
```
- **Nome do Artefato** (classificação) - breve descrição
```

**Exemplo:**
```
- **Product Backlog Priorizado** (essencial) - lista ordenada de user stories no GitHub Projects
- **Critérios de Priorização** (recomendado) - documento com regras de ordenação (MoSCoW, WSJF)
```

### 7. Observações / Notas
**Como preencher:**
- Use para informações complementares
- Riscos conhecidos
- Dependências com outras práticas
- Frequência de execução
- Ferramentas específicas

---

## ✅ Checklist Antes de Commitar

- [ ] Todas as seções obrigatórias estão preenchidas
- [ ] Objetivo está claro e contextualizado
- [ ] Atividades principais estão listadas
- [ ] Papéis estão marcados corretamente
- [ ] Entradas e Saídas estão documentadas
- [ ] Artefatos estão classificados (essencial/recomendado/opcional)
- [ ] Ortografia e gramática revisadas
- [ ] Data de atualização está correta
- [ ] Nome do responsável está preenchido

---

## 🔗 Referências

- [CMMI for Development V2.0](https://cmmiinstitute.com/)
- [Scrum Guide](https://scrumguides.org/)
- [Diagramas do Processo](../diagramas/)

---

## ❓ Dúvidas?

Consulte a equipe ou abra uma issue no repositório.
