# 📚 Caderno Temático: Metodologias Ágeis (Scrum e Kanban)

Este repositório contém o resultado de um projeto prático desenvolvido como parte do desafio da **DIO (Digital Innovation One)**. O objetivo foi explorar o uso do **NotebookLM** como uma ferramenta de aprendizagem ativa, combinando curadoria de fontes técnicas, engenharia de prompts, análise crítica e organização do conhecimento em torno das **Metodologias Ágeis (Scrum e Kanban)**.

---

## 🎯 Contexto e Objetivos

* **Tema Escolhido:** Metodologias Ágeis e Frameworks de Trabalho (Scrum e Kanban).
* **Contexto:** No desenvolvimento moderno de software e na gestão de projetos de TI, abordagens tradicionais (como a gestão em cascata) enfrentam limitações em cenários de alta incerteza e mudanças rápidas. O uso de metodologias ágeis permite respostas rápidas, entregas incrementais e melhoria contínua dos processos.
* **Objetivos de Estudo:**
  - Compreender os fundamentos do Manifesto Ágil e como ele se contrapõe ao modelo em cascata.
  - Mapear e comparar o framework **Scrum** (pilares, papéis, compromissos) e o **Método Kanban** (sistema puxado, limites de WIP e cadências).
  - Identificar ferramentas de apoio que otimizam a produtividade de equipes ágeis.
  - Construir um miniguia prático de estudo e consulta com suporte da inteligência artificial.

---

## 🔎 Curadoria de Fontes

Para alimentar o caderno temático no NotebookLM, foram selecionadas **4 fontes abertas essenciais** abrangendo diretrizes oficiais, artigos conceituais e ferramentas:

1. **Guia Oficial:** *O Guia do Scrum: O Guia Definitivo para o Scrum (Ken Schwaber & Jeff Sutherland, 2020)*
   - *Link:* [Scrum Guide 2020 (PDF)](https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-Portuguese-European.pdf)
   - *Conteúdo:* Definição oficial do Scrum, empirismo, papéis (Scrum Master, Product Owner, Developers), eventos e os compromissos dos artefatos (Product Goal, Sprint Goal, Definition of Done).
2. **Guia Completo:** *Kanban: o que é, o Método Kanban, principais conceitos e como funciona no dia a dia (Alura)*
   - *Link:* [Artigo Kanban Alura](https://www.alura.com.br/artigos/metodo-kanban)
   - *Conteúdo:* Definições do Método Kanban (David J. Anderson), regras, princípios de gestão de mudança, métricas (Lead Time, Cycle Time, Throughput, Lei de Little) e cadências.
3. **Artigo Conceitual:** *O que é metodologia ágil? Entenda o conceito, onde usar e principais benefícios (Alura)*
   - *Link:* [Artigo Metodologia Ágil Alura](https://www.alura.com.br/artigos/o-que-e-metodologia-agil)
   - *Conteúdo:* Histórico das metodologias ágeis, 4 valores e 12 princípios do Manifesto Ágil, Framework Cynefin e comparações entre modelos (Cascata vs. Ágil).
5. **Guia de Ferramentas:** *Conheça as ferramentas de Scrum que vão garantir a produtividade da sua equipe!*
   - *Link:* [10 ferramentas de SCRUM](https://itsstecnologia.com.br/blogs/10-ferramentas-de-scrum-para-voce-conquistar-mais-produtividade/)
   - *Conteúdo:* Mapeamento de 10 ferramentas práticas para gestão de projetos, sprints e quadros ágeis (Trello, Asana, Slack, YouTrack, Bitrix24, Taiga, etc.).

---

## 🧪 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante o processo de curadoria e consulta no NotebookLM, foram testadas variações de prompts para extrair respostas precisas do material:

### 📌 Iteração 1: Restrição do Contexto Oficial (Scrum Guide)
* **Prompt Testado:** *"Quais são os papéis do Scrum e os entregáveis?"*
* **Resultado Obtido:** A IA trouxe o termo "Time de Desenvolvimento" e "Artefatos sem compromissos", baseando-se no padrão pré-2020.
* **Refinamento do Prompt:** *"Com base estritamente no Guia do Scrum 2020 carregado, quais são os papéis oficiais da Scrum Team e quais são os compromissos (commitments) atrelados a cada artefato?"*
* **Cicatriz / Aprendizado:** Especificar a versão das fontes atreladas ao prompt fez com que a IA atualizasse a resposta para a nomenclatura oficial (Developers) e incluísse o conceito mais recente de *Product Goal*.

### 📌 Iteração 2: Síntese Comparativa em Tabela (Kanban vs. Scrum)
* **Prompt Testado:** *"O Kanban substitui o Scrum?"*
* **Resultado Obtido:** Um texto longo que misturava quadros físicos com a filosofia do método.
* **Refinamento do Prompt:** *"Sintetize as diferenças estruturais entre o Framework Scrum e o Método Kanban em uma tabela focada em: Prescritividade, Ritmo de Entrega, Limites de Trabalho e Papéis."*
* **Cicatriz / Aprendizado:** Solicitar a saída em tabela com critérios bem definidos forçou o modelo a estruturar as ideias em forma de resumo executivo e fácil consulta.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados

#### 1. Fundamentos e Manifesto Ágil
* **Valores Principais:** Indivíduos e interações > processos e ferramentas; software em funcionamento > documentação abrangente; colaboração com cliente > negociação de contratos; resposta a mudanças > seguir um plano.
* **Modelo Cynefin:** Ambientes **complexos** exigem abordagens ágeis (empirismo: transparência, inspeção e adaptação), enquanto cenários **simples ou complicados** podem utilizar métodos tradicionais como Cascata.

#### 2. Framework Scrum (Visão Oficial 2020)
* **Essência:** Estrutura leve e intencionalmente incompleta para geração de valor em problemas complexos.
* **Scrum Team:** Composta por Product Owner (ordena o backlog), Scrum Master (promove a eficácia do Scrum) e Developers (criam o incremento).
* **Artefatos e Seus Compromissos:**
  - *Product Backlog* ➡️ Compromisso: **Product Goal** (objetivo de longo prazo do produto).
  - *Sprint Backlog* ➡️ Compromisso: **Sprint Goal** (objetivo da iteração).
  - *Incremento* ➡️ Compromisso: **Definition of Done** (critério de qualidade para conclusão).

#### 3. Método Kanban (Pensamento Lean)
* **Essência:** Estratégia de gestão evolutiva focada no trabalho de conhecimento e no sistema puxado.
* **Práticas Fundamentais:** Visualizar o fluxo, limitar o trabalho em progresso (**WIP - Work In Progress**), gerenciar o fluxo e tornar as políticas explícitas.
* **Métricas-Chave:** 
  - *Lead Time:* Tempo total desde a solicitação da demanda até a entrega final.
  - *Cycle Time:* Tempo em que a demanda esteve sendo trabalhada ativamente.
  - *Throughput (Vazão):* Quantidade de entregas concluídas em determinado período.

#### 4. Ecossistema de Ferramentas de Apoio
* Ferramentas como **Slack** auxiliam no pilar de comunicação e transparência; **Trello**, **Asana** e **Bitrix24** fornecem gestão visual via quadros Kanban; e **Jira** / **Azure DevOps** atendem projetos mais complexos que combinam Sprints e métricas avançadas.

---

### 📖 Glossário de Conceitos

| Termo | Definição Útil Baseada nas Fontes |
| :--- | :--- |
| **Product Goal** | Compromisso do Product Backlog que descreve um estado futuro do produto para servir de foco para a equipe. |
| **Definition of Done (DoD)** | Descrição formal do estado do Incremento quando este atinge as medidas de qualidade exigidas para o produto. |
| **Sistema Puxado** | Prática Lean/Kanban onde novas tarefas só são iniciadas conforme há capacidade disponível no fluxo, evitando sobrecarga. |
| **WIP (Work In Progress)** | Trabalho em andamento. Limitar o WIP é essencial para reduzir o ciclo de entrega ("Pare de começar, comece a terminar"). |
| **Cadências** | Reuniões e ciclos regulares de feedback no Método Kanban para alinhamento e revisão do fluxo de trabalho. |

---

### 🔄 Prompts Reutilizáveis para Revisão Futura

1. **Prompt para Simulação de Cenário:**
   > *"Atue como um Agile Coach. Com base no Scrum Guide e na fonte de Kanban carregados, quando um time deve optar por utilizar Scrum com quadros Kanban em relação a usar apenas o Método Kanban puro?"*
2. **Prompt para Fixação de Métricas:**
   > *"Com base no artigo sobre Método Kanban, explique de forma simples a relação entre Trabalho em Progresso (WIP), Vazão (Throughput) e a Lei de Little."*
3. **Prompt para Teste de Conhecimento:**
   > *"Gere um quiz de 5 perguntas de múltipla escolha focadas nas novidades do Guia do Scrum 2020 em comparação a modelos tradicionais, fornecendo o gabarito comentado ao final."*
