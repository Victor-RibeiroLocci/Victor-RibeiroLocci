# Victor Nathan Batista Ribeiro

### Engenharia de IA aplicada · agentes com LLM em operação real

Graduando em **Tecnologia em Agentes Inteligentes (FIAP)** e desenvolvedor de soluções, processos, automações, com foco em escalabilidade e GenAI. Conecto negócio e tecnologia: entendo o processo na operação, desenho a solução e entrego o sistema funcionando. Meu foco é **AI Engineering**: agentes baseados em engenharia, GenAI, tool calling, data vector, rag , avaliação semântica, arquitetura transformers, tokenização, fine tuning de modelos, guardrails e avaliação de comportamento.

`Python` · `LLMs por API (Claude, Gemini)` · `Tool use / function calling` · `Prompt e context engineering` · `Guardrails` · `FastAPI` · `SQL` · `Go` Tokenização

## O que eu construo

- **Agentes com LLM** que consultam dados por ferramentas em vez de inventar respostas.
- **Arquiteturas em que o modelo conversa e o código decide**, com revisão humana onde há risco.
- **Automações e pipelines de dados** de ponta a ponta, integrados a sistemas corporativos (SAP, WMS), com testes e tratamento de falha.

## Experiência: supply chain, como desenvolvedor de soluções

Atuo no planejamento de um centro de distribuição. Ali identifico os gargalos do processo e desenvolvo as soluções que a operação usa no dia a dia:

| Solução | Problema de negócio | Resultado |
|---|---|---|
| [Planning Controller](https://github.com/Victor-RibeiroLocci/planning-controller) | Gestão dependia de uma planilha de ~50 MB alimentada por cinco relatórios de dois sistemas | Base relacional única, painel executivo e **agente LLM com 7 ferramentas** que responde sobre a operação |
| [WMS Produtividade](https://github.com/Victor-RibeiroLocci/wms-produtividade) | Produtividade da separação só era conhecida depois do turno | Pipeline automático a cada hora, painel com metas e relatório de fim de turno enviado à liderança |
| [Automação de Consumo](https://github.com/Victor-RibeiroLocci/automacao-consumo-sap) | Lançamento manual de notas fiscais no controle e no SAP | Tarefa de **até 5 h concluída em até 15 min**, sem digitação |

Os links levam ao estudo de caso de cada solução; o código-fonte fica em repositórios privados e pode ser demonstrado em entrevista.

O que essa vivência acrescenta ao meu trabalho com IA: leitura de processo e de regra de negócio, integração com sistemas corporativos sem API, dados reais com suas imperfeições e usuários que dependem do que eu entrego.

## Formação

**Tecnologia em Agentes Inteligentes · FIAP** (*AI Agents Engineering & Autonomous Architectures*) · graduação tecnológica de 2 anos, iniciada em agosto de 2026.

O curso forma profissionais para projetar agentes baseados em LLM que integram APIs, bancos de dados e sistemas corporativos, com orquestração, memória, segurança e monitoramento. Perfis de saída: AI Agent Developer, LLM Engineer e AI Solutions Engineer.

| Competência da grade | Onde aparece no meu portfólio |
|---|---|
| Fundamentos de agentes de IA e LLMs | NexoIA, DesconfIA |
| Prompt engineering e context engineering | NexoIA: 8 versões de prompt, cada mudança justificada por teste |
| APIs, integração e tool calling | Planning Controller (7 ferramentas), NexoIA (function calling com contrato Pydantic), DesconfIA (cadastro público de CNPJ) |
| Programação aplicada a agentes com Python | RIA (FastAPI, 31 testes), NexoIA (Streamlit) |
| Automação inteligente e workflows autônomos | WMS Produtividade, Automação de Consumo |
| Integração com sistemas corporativos (ERP, CRM, SaaS) | SAP e WMS nos três projetos de supply chain |
| Segurança e governança de agentes | Guardrails no RIA, no NexoIA e no DesconfIA; trilha de auditoria no RIA |
| Avaliação e qualidade de agentes (evals) | Testes de comportamento com critério definido antes da execução (NexoIA, RIA) |
| Multi-agent systems e orquestração | AISAC Team: arquitetura com 4 agentes e orquestração durável |
| RAG systems e vector databases | AISAC Team: arquitetura com base vetorial e citação obrigatória · implementação em formação |
| Memória, planejamento e decisão de agentes | AISAC Team: memória em quatro camadas (arquitetura) |
| Impacto social e ética da IA | DesconfIA (proteção contra golpes), RIA (minimização de dados e decisão humana) |
| Cloud, deploy e escalabilidade | Em formação |
| Performance e otimização (custo, latência, tokens) | Em formação |
| Agentic UX e produto baseado em agentes | Em formação |

## Projetos

### IA generativa e agentes

| Projeto | O que é | Destaques técnicos |
|---|---|---|
| [Planning Controller](https://github.com/Victor-RibeiroLocci/planning-controller) | Painel gerencial de supply chain com agente que responde sobre a operação | Agente com 7 ferramentas (tool use), modo de contingência offline, SQLite, 19 testes |
| [RIA](https://github.com/Victor-RibeiroLocci/ria) | Agente de pré-triagem de recrutamento | FastAPI, guardrails de dados sensíveis, score explicável, decisão humana, 31 testes |
| [NexoIA](https://github.com/Victor-RibeiroLocci/nexoia) | Agente que estrutura intenções de comunicação | 8 versões de prompt testadas, guardrails, function calling com contrato Pydantic |
| [DesconfIA](https://github.com/Victor-RibeiroLocci/desconfia) | Agente que confere cobranças antes do pagamento | Extração estruturada com LLM, regras determinísticas, cadastro público de CNPJ |
| [AISAC Team](https://github.com/Victor-RibeiroLocci/aisac-team) | Arquitetura multiagente para pós-venda automotivo | 4 agentes, RAG com citação, orquestração durável, evals no CI |

### Automação e dados

| Projeto | O que é | Destaques técnicos |
|---|---|---|
| [WMS Produtividade](https://github.com/Victor-RibeiroLocci/wms-produtividade) | Pipeline horário de produtividade com painel e envio ao Teams | Go, automação de navegador, painel executivo, Power Automate |
| [Automação de Consumo](https://github.com/Victor-RibeiroLocci/automacao-consumo-sap) | NF-e por e-mail → controle → SAP | Python, VBA, SAP GUI Scripting |

## Tecnologias

### Aplicadas em projetos

- **IA:** LLMs por API (Claude, Gemini) · modelo local (Ollama) · tool use e function calling · engenharia de prompt · saídas estruturadas (JSON Schema, Pydantic) · guardrails · testes de comportamento
- **Linguagens:** Python · Go · SQL · JavaScript · VBA
- **Backend e dados:** FastAPI · Streamlit · SQLite · APIs REST · pytest e unittest
- **Automação e integração:** SAP GUI Scripting · automação de navegador (chromedp) · Outlook e Excel (COM) · Power Automate
- **Versionamento:** Git e GitHub

### Na grade do curso (em formação)

- **Modelos e plataformas:** OpenAI API · Azure OpenAI · Google Vertex AI · AWS Bedrock
- **Frameworks de agentes:** LangChain · LlamaIndex · Semantic Kernel
- **RAG e bases vetoriais:** Pinecone · Weaviate · FAISS
- **Infraestrutura e automação:** Docker · n8n
- **Plataformas de agentes:** Microsoft Copilot Studio · Google Agent Builder
- **Desenvolvimento assistido:** GitHub Copilot

## Contato

- LinkedIn: [victor-nathan-batista-ribeiro](https://www.linkedin.com/in/victor-nathan-batista-ribeiro-a03943252)
- E-mail: [vicnathan13@gmail.com](mailto:vicnathan13@gmail.com)
