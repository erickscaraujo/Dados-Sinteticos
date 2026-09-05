# 📊 Dados Sintéticos

**Criação de dados sintéticos realistas** — aplicativo desktop.

Gere dados sintéticos realistas para testes, desenvolvimento e demonstrações, com qualidade mensurável,
distribuições estatísticas, regras de negócio em SQL, anonimização (LGPD) e exportação para qualquer destino.

![](tela.png)

## ✨ Recursos

| Área | Descrição |
|---|---|
| **Dashboard** | Visão geral, modelos salvos, ações rápidas |
| **Model Builder** | Editor visual de esquemas: tabelas, colunas, geradores, tipos, distribuições, nulidade, unicidade e regras SQL por coluna/tabela |
| **Cenários prontos** | Comércio Eletrônico, Bancário, Saúde, Logística e SaaS — com relacionamentos FK, distribuições e regras |
| **Data Generator** | Geração determinística (seed) com progresso, preview por tabela e análise por coluna |
| **Auto Profile** | Importa CSV/JSON/JSONL, infere tipos, distribuições estatísticas, cardinalidade e padrões (CPF, e-mail, cidade…) e gera um modelo equivalente |
| **AI Generator** | Geração de valores por LLM local via **Ollama** (`localhost:11434`) ou **LM Studio** (`localhost:1234`) — API OpenAI-compatível |
| **Visual Analytics** | Score de qualidade, histogramas, top valores, completude (heatmap), distribuição de scores |
| **Synthetic Data Quality Score** | 30% realismo das distribuições + 30% qualidade (completude/unicidade/validade) + 25% privacidade + 15% consistência FK |
| **Privacidade / Anonimização** | Pseudonimização, mascaramento, generalização, ruído, supressão, embaralhamento e substituição — com estimativa de risco de reidentificação e k-anonimato |
| **Relacionamentos** | FK, 1-para-muitos e join entre tabelas, com densidade configurável e integridade referencial verificada |
| **Distribuições** | 12 tipos: uniforme, normal, log-normal, exponencial, Poisson, binomial, gamma, Pareto, Zipf, Bernoulli, triangular |

## 📤 Exportação

CSV · JSON (ou JSON Lines) · **Parquet** · SQL Script (PostgreSQL/MySQL/SQLite/DW) · **PostgreSQL** · **MySQL** · **SQLite** (.db) · **Excel** (.xlsx) · **API REST** (POST/PUT) · **Kafka** (kafkajs) · **S3 / MinIO** (assinatura SigV4) · **Data Warehouse** (script SQL padrão).


## 📦 Instaladores

O instalador Windows é assistido (permitindo escolher o diretório), cria atalhos no
menu Iniciar e na área de trabalho, e inclui o desinstalador. Instalação silenciosa:
`Dados Sintéticos-1.0.0-Setup-x64.exe /S`.

---

© Erick de S.C. Araújo · Electron + Bun + React
