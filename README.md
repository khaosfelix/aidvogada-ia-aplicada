# A|DVOGADA — Legal AI aplicada ao Contencioso

Projeto autoral de **IA aplicada ao Direito, Legal Operations e automação jurídica**, desenvolvido para apoiar rotinas de contencioso trabalhista, previdenciário e administrativo.

A A|DVOGADA atua como agente jurídico especializado em **análise processual, identificação de pedidos, mapeamento probatório, estruturação de teses, impugnação documental, organização de conhecimento jurídico e apoio à redação de peças processuais**.

O projeto combina experiência jurídica prática, engenharia de prompts, governança de IA generativa, análise documental e padronização de fluxos jurídicos.

---

## Problema

Rotinas jurídicas envolvem grande volume de documentos, prazos, teses, provas, fundamentos, decisões estratégicas e informações dispersas.

Em contencioso, parte relevante do risco está na ausência de organização entre:

- fatos alegados;
- pedidos expressos;
- documentos disponíveis;
- provas efetivamente produzidas;
- lacunas probatórias;
- fundamentos legais;
- jurisprudências aplicáveis;
- riscos processuais;
- linguagem adequada da peça.

Quando essas informações ficam dispersas entre autos, modelos, planilhas, anotações internas e documentos soltos, há aumento de retrabalho, inconsistências argumentativas e perda de eficiência na gestão do conhecimento jurídico.

---

## Solução proposta

A A|DVOGADA estrutura um fluxo jurídico assistido por IA, com curadoria humana especializada, para apoiar a rotina contenciosa.

O projeto busca organizar:

- análise integral dos autos;
- identificação de pedidos expressos;
- separação entre pedidos e alegações sem pedido autônomo;
- mapeamento de documentos e provas;
- identificação de fatos incontroversos e controvertidos;
- identificação de lacunas probatórias;
- construção de teses jurídicas;
- impugnação documental;
- análise de mídias digitais;
- padronização de modelos e checklists;
- revisão de fundamentos legais e jurisprudenciais;
- apoio à redação estratégica de peças processuais;
- gestão do conhecimento jurídico.

A proposta não é substituir o raciocínio jurídico humano, mas apoiar etapas repetitivas, analíticas e documentais com método, rastreabilidade e curadoria técnica.

---

## Evolução do Projeto

| Versão inicial | Versão aprimorada |
|---|---|
| Projeto apresentado como IA aplicada ao Direito e Legal Ops. | Projeto posicionado como agente jurídico especializado em contencioso trabalhista, previdenciário e administrativo. |
| Foco em análise processual, revisão estratégica e organização de teses. | Fluxo completo com análise de autos, identificação de pedidos, mapa de provas, teses, lacunas, riscos, estrutura e redação assistida. |
| Funcionalidades descritas como em desenvolvimento. | Funcionalidades organizadas como módulos operacionais do agente jurídico. |
| Organização de prompts e conhecimento jurídico. | Governança de IA com travas contra alucinação jurídica, controle de artigos, jurisprudências e fatos sem prova. |
| Apoio à revisão de peças processuais. | Redação tópico por tópico, condicionada à validação prévia da estrutura e das teses. |
| Checklist de documentos e inconsistências. | Checklist jurídico completo: pedidos, provas, documentos, mídias, fundamentos, riscos, linguagem e coerência final. |
| Análise documental geral. | Impugnação documental individualizada com análise de ID, autenticidade, integralidade, contexto, metadados, origem e força probatória. |
| Uso responsável de IA como diretriz geral. | Uso responsável transformado em regra operacional: IA como apoio, sem substituir análise jurídica humana, com revisão técnica obrigatória. |

---

## Funcionalidades

- Análise inicial de casos jurídicos.
- Leitura e organização de autos processuais.
- Extração de pontos relevantes de documentos.
- Identificação de pedidos expressos.
- Separação entre pedidos, alegações e contexto fático.
- Mapeamento de fatos, provas, lacunas e riscos.
- Organização de argumentos e teses jurídicas.
- Estruturação de peças processuais.
- Apoio à redação de contestações, recursos e manifestações.
- Impugnação individualizada de documentos.
- Análise de prints, áudios e vídeos.
- Padronização de modelos e checklists.
- Organização de conhecimento jurídico.
- Revisão de linguagem jurídica.
- Revisão de artigos legais e jurisprudências.
- Checklist final de qualidade.

---

## Fluxo operacional

```mermaid
flowchart TD
    A[Recebimento dos autos] --> B[Análise da inicial e documentos]
    B --> C[Identificação dos pedidos expressos]
    C --> D[Separação de alegações sem pedido autônomo]
    D --> E[Mapeamento de provas]
    E --> F[Identificação de lacunas e riscos]
    F --> G[Definição de teses aplicáveis]
    G --> H[Estruturação da peça]
    H --> I[Validação humana]
    I --> J[Redação tópico por tópico]
    J --> K[Revisão de fundamentos]
    K --> L[Revisão de linguagem e coerência probatória]
    L --> M[Check final]
```

## Módulos do agente

### 1. Análise de autos

O agente foi estruturado para apoiar a análise de petição inicial, documentos, certidões, decisões, IDs, mídias e anexos relevantes, organizando os principais elementos do caso.

Essa etapa permite transformar um conjunto disperso de informações processuais em uma leitura organizada, com separação entre fatos alegados, documentos disponíveis, pontos controvertidos, lacunas e riscos.

### 2. Revisão de pedidos

Antes da redação de qualquer peça, o agente separa:

- pedidos expressos;
- alegações sem pedido autônomo;
- fatos contextuais;
- temas que não devem virar tópico autônomo.

Essa etapa reduz o risco de combater pedidos inexistentes e ajuda a manter a peça aderente ao que foi efetivamente formulado no processo.

### 3. Mapa de provas

O agente organiza os elementos probatórios do caso, identificando:

- documentos disponíveis;
- fatos que cada documento comprova;
- fatos que o documento não comprova;
- lacunas probatórias;
- contradições;
- riscos processuais;
- pontos que exigem complementação.

O objetivo é vincular a argumentação jurídica ao conjunto probatório, evitando afirmações genéricas ou desconectadas dos autos.

### 4. Estruturação de teses

A construção argumentativa é feita a partir dos pedidos, da causa de pedir, dos documentos disponíveis e dos riscos identificados.

O agente apoia a organização de teses jurídicas, preliminares, argumentos de mérito e linhas defensivas ou recursais, sempre com foco em aderência ao caso concreto.

### 5. Impugnação documental

O agente pode apoiar a análise individualizada de documentos, considerando:

- ID do documento;
- conteúdo;
- autenticidade;
- integralidade;
- contexto;
- origem;
- data e hora;
- metadados;
- cadeia de custódia;
- contradições;
- limites probatórios;
- necessidade de valoração restrita.

Essa funcionalidade é especialmente útil em contestações, manifestações sobre documentos e impugnações probatórias.

### 6. Análise de mídias

O projeto contempla protocolo específico para análise de mídias digitais, como:

- prints;
- conversas;
- áudios;
- vídeos.

A análise considera interlocutores, data, hora, contexto anterior e posterior, cortes, origem, pertinência e força probatória.

Quando não for possível analisar a mídia com segurança, o agente sinaliza a necessidade de transcrição, complementação ou revisão humana.

### 7. Redação assistida

A redação é realizada por etapas, após análise dos autos, organização das provas e validação da estrutura.

O agente apoia a elaboração de peças como:

- contestações;
- recursos;
- manifestações;
- impugnações;
- requerimentos;
- tópicos jurídicos específicos.

A proposta é produzir textos mais organizados, técnicos, coerentes e conectados ao conjunto probatório.

### 8. Revisão de fundamentos

O agente possui controle específico para artigos legais, súmulas, orientações jurisprudenciais e julgados.

A lógica do projeto é evitar a criação artificial de fundamentos jurídicos. Quando não houver fonte segura ou texto literal disponível, o agente deve sinalizar a necessidade de inserção ou conferência posterior.

Essa etapa contribui para reduzir riscos de alucinação jurídica e aumentar a confiabilidade do material produzido.

### 9. Governança de linguagem

O agente foi configurado para evitar linguagem interna, informal ou inadequada em peças jurídicas.

A redação prioriza expressões compatíveis com a prática forense, como:

- a prova documental demonstra;
- os registros funcionais evidenciam;
- o conjunto probatório confirma;
- os documentos rescisórios comprovam;
- os controles de jornada revelam;
- o extrato fundiário evidencia.

Essa camada de governança ajuda a manter a consistência técnica e profissional dos textos.

### 10. Check final

Antes da conclusão da peça ou análise, o agente executa revisão de:

- pedidos;
- provas;
- documentos;
- mídias;
- artigos legais;
- jurisprudências;
- linguagem;
- riscos;
- coerência entre tese, documento e pedido;
- ausência de fatos sem prova;
- ausência de combate a pedido inexistente.

O objetivo é entregar uma análise ou minuta com maior consistência, rastreabilidade e segurança técnica.

---

## Comandos operacionais

| Comando | Finalidade |
|---|---|
| `ANALISAR AUTOS` | Inicia a análise integral do processo. |
| `REVISAR PEDIDOS` | Separa pedidos expressos de alegações sem pedido autônomo. |
| `MAPA DE PROVAS` | Organiza documentos, fatos provados, lacunas e riscos. |
| `GERAR ESTRUTURA DA PEÇA` | Propõe a estrutura da peça antes da redação. |
| `INICIAR PEÇA [tipo]` | Inicia a redação da peça validada. |
| `PRÓXIMO` | Avança para o próximo tópico da peça. |
| `IMPUGNAR DOCUMENTOS` | Apoia a impugnação documental individualizada. |
| `ANALISAR MÍDIAS` | Analisa prints, áudios e vídeos. |
| `REVISAR LINGUAGEM` | Revisa linguagem jurídica e padronização textual. |
| `REVISAR ARTIGOS E JURISPRUDÊNCIAS` | Verifica fundamentos legais e jurisprudenciais. |
| `CHECK DE RISCO` | Aponta riscos processuais, probatórios e argumentativos. |
| `CHECAR PEÇA` | Executa revisão final da peça. |

---

## Tecnologias e conceitos

- Inteligência Artificial generativa
- Engenharia de Prompts
- Legal Operations
- Gestão do conhecimento jurídico
- Automação de processos
- Python
- OpenAI API
- Análise documental
- Estruturação de fluxos jurídicos
- Uso responsável de IA
- Governança de IA generativa
- Mitigação de alucinação
- Padronização de rotinas jurídicas

---

## Diferencial

O diferencial do projeto é unir experiência jurídica prática com tecnologia aplicada, criando um fluxo de apoio ao contencioso que prioriza método, prova, rastreabilidade e revisão humana.

A A|DVOGADA não foi desenhada apenas para gerar texto. O objetivo é organizar o raciocínio jurídico, estruturar provas, identificar riscos, controlar fundamentos e apoiar a elaboração de peças mais consistentes.

---

## Possíveis aplicações

A A|DVOGADA pode ser aplicada em rotinas como:

- triagem inicial de casos;
- organização de documentos e provas;
- identificação de pontos controvertidos;
- revisão de petições iniciais;
- apoio à elaboração de contestações;
- apoio à elaboração de recursos;
- estruturação de teses defensivas;
- impugnação documental;
- análise de mídias digitais;
- padronização de modelos internos;
- criação de checklists jurídicos;
- gestão do conhecimento jurídico;
- apoio à controladoria jurídica;
- melhoria de fluxos em escritórios e departamentos jurídicos.

---

## Estrutura sugerida do repositório

```text
aidvogada-ia-aplicada/
├── README.md
├── docs/
│   ├── fluxo-de-analise.md
│   ├── checklist-contestacao.md
│   ├── checklist-ia-responsavel.md
│   ├── protocolo-midias.md
│   └── estrutura-base-conhecimento.md
├── examples/
│   └── caso-ficticio-trabalhista.md
├── prompts/
│   ├── prompt-analise-autos.md
│   ├── prompt-revisao-pedidos.md
│   ├── prompt-mapa-provas.md
│   ├── prompt-impugnacao-documental.md
│   └── prompt-check-final.md
└── assets/
    └── fluxo-aidvogada.png
```

---

## Roadmap

- [ ] Criar exemplo fictício de análise processual.
- [ ] Estruturar fluxo demonstrativo de contestação trabalhista.
- [ ] Documentar prompts e critérios de revisão humana.
- [ ] Criar checklist de uso responsável de IA no jurídico.
- [ ] Criar fluxograma visual do funcionamento do agente.
- [ ] Organizar base demonstrativa de teses, documentos e modelos.
- [ ] Desenvolver interface simples em Streamlit.
- [ ] Criar módulo de checklist documental.
- [ ] Criar módulo de análise de risco por pedido.
- [ ] Criar módulo de revisão final de peça.

---

## Uso responsável de IA

O projeto parte da premissa de que IA deve ser utilizada como ferramenta de apoio, e não como substituta da análise jurídica humana.

Toda saída gerada por IA deve ser revisada por profissional habilitado, com atenção a:

- sigilo profissional;
- proteção de dados;
- aderência ao caso concreto;
- conferência de fatos e documentos;
- atualização normativa e jurisprudencial;
- riscos de alucinação;
- responsabilidade técnica;
- limites éticos do uso de IA no Direito.

---

## Status

Projeto em desenvolvimento contínuo.

---

## Autora

**Brunna Leite Felix**  
Legal Ops | Legal AI | Dados e Automação | Direito + Tecnologia

LinkedIn: https://linkedin.com/in/brunnalfelix

GitHub: https://github.com/khaosfelix
