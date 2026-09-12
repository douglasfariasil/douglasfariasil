# Olá, eu sou o Douglas Faria 👋

**Desenvolvedor Python | Engenharia de Dados & Backend**
📍 São Paulo, SP | 📧 douglasfariasil@outlook.com

Desenvolvedor focado em Engenharia de Dados e Backend com Python. Construo pipelines ETL automatizados, APIs RESTful e infraestruturas conteinerizadas em Docker para solucionar desafios reais de negócios e análise de dados.

---

### 🚀 Principais Competências Técnicas

- **Linguagens:** Python (Estruturas avançadas, POO, Pandas), SQL
- **Bancos de Dados & Infra:** MySQL, PostgreSQL, Docker, Docker Compose
- **Backend & APIs:** FastAPI, REST APIs, ORMs (SQLAlchemy / SQLModel)
- **Engenharia & Dados:** Pipelines ETL, Automação de Relatórios (Excel/PDF), Power Query
- **Ferramentas:** Git, GitHub, VS Code, Linux

---

### 📂 Projetos em Destaque

- **[Projeto E-commerce SQL](https://github.com/douglasfariasil/projeto-ecommerce-sql):** Pipeline analítico completo de ponta a ponta. Infraestrutura MySQL 8.0 via Docker Compose, ingestão de dados e automação em Python/Pandas gerando relatórios corporativos multi-abas em Excel e PDF.
- **[Pizzaria API](https://github.com/douglasfariasil/Pizzaria_API):** API REST robusta desenvolvida com Python e FastAPI, conteinerizada em Docker para gerenciamento de pedidos e regras de negócio.

---

💼 **LinkedIn:** [linkedin.com/in/douglasfaria-dev](https://linkedin.com/in/douglasfaria-dev)
      
<!-- Copie e cole este código atualizado no seu README -->
![VariableBee GitHub stats](https://github-readme-stats-fast.vercel.app/api?username=douglasfariasil&show_icons=true&theme=gotham)

### 🛠️ Ferramentas & Tecnologias

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,postgres,mysql,docker,fastapi,pandas,vscode,git,github" alt="Minha Stack Técnica" />
</p>

- **Linguagens & Frameworks:** Python, FastAPI, Pandas
- **Bancos de Dados & Infra:** PostgreSQL, MySQL, Docker, Docker Compose
- **Análise & Ferramentas:** SQL, Power Query, Microsoft Excel, Git, VS Code

# 🛒 Pipeline Analítico de E-Commerce (MySQL + Docker + Python)

Projeto de automação de ETL e geração de relatórios corporativos a partir de uma base de dados de e-commerce com volumetria real.

## 📌 Tecnologias Utilizadas
- **Linguagem:** Python (Pandas)
- **Banco de Dados:** MySQL 8.0
- **Infraestrutura:** Docker & Docker Compose
- **Saídas:** Relatórios automatizados em Excel (multi-abas) e PDF

---

## 🚀 Como Executar o Projeto com Docker

### Pré-requisitos
- [Docker](https://www.docker.com/) instalado
- [Docker Compose](https://docs.docker.com/compose/) instalado

### Passo a Passo

1. **Clonar o repositório:**
```bash
   git clone [https://github.com/douglasfariasil/projeto-ecommerce-sql.git](https://github.com/douglasfariasil/projeto-ecommerce-sql.git)
   cd projeto-ecommerce-sql
```
--- 

Subir o ambiente e banco de dados via Docker:

docker compose up -d

Isso irá inicializar o contêiner do MySQL 8.0 na porta correta e popular o banco automaticamente.

Executar o script de automação ETL:

python gerar_relatorios.py

--- 

📊 Estrutura do Pipeline
Extração: Consulta SQL direta no banco MySQL rodando no Docker.

Transformação: Tratamento, segmentação e consolidação de dados via Pandas.

Carga/Saída: Exportação formatada para consumo direto da equipe de negócios.
