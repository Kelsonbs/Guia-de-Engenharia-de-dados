## 🗺️ Trilha de Aprendizado & Fontes Ancoradas

O plano de estudos está ancorado nos pilares fundamentais da engenharia moderna, utilizando literatura de ponta e documentações oficiais:

### 1. Fundamentos e Ciclo de Vida dos Dados
*   **Referência:** *Fundamentals of Data Engineering* (Joe Reis & Matt Housley).
*   **Foco:** Entendimento agnóstico de tecnologia sobre ingestão, armazenamento, transformação e servir dados, além dos subtextos de segurança, governança e engenharia de software.

### 2. Modelagem de Dados e Arquitetura
*   **Clássica (Kimball):** Técnicas de Modelagem Dimensional, Tabelas Fato, Tabelas Dimensão e tratamento de dimensões que mudam lentamente (SCD Tipo 2).
*   **Moderna (Lakehouse):** Arquitetura de Medalhão (Camadas *Bronze*, *Silver* e *Gold*) unindo a confiabilidade do Data Warehouse à flexibilidade do Data Lake.

### 3. Transformação e Engenharia de Software Aplicada
*   **Transformação Moderna (dbt):** Modelagem analítica utilizando SQL estruturado sob controle de versão, testes automatizados de qualidade e documentação nativa.
*   **Princípios Práticos:** Idempotência em pipelines de dados, conteinerização com Docker e isolamento de ambientes.

---

## 🚀 Roteiro Sugerido (Foco de 4 Semanas)

*   **Semana 1: Fundamentos & Modelagem Dimensional** (Diferença de OLTP vs. OLAP, Fatos e Dimensões).
*   **Semana 2: Arquitetura de Armazenamento** (Data Lakes, Lakehouses e Armazenamento Colunar como Parquet).
*   **Semana 3: O Pipeline na Prática (ELT)** (Ingestão de dados, uso de Docker e introdução ao ecossistema dbt).
*   **Semana 4: Governança, Qualidade e Produção** (Testes de dados, Idempotência, Orquestração de workflows e documentação).

---

## 🛠️ Como Utilizar este Material no NotebookLM

1. **Geração de Flashcards:** Utilize o chat integrado para testar conceitos cruciais de modelagem ou comandos dbt.
2. **Audio Overview:** Utilize a funcionalidade de sumário em áudio para fixar conceitos de arquitetura macro de forma passiva.
3. **Validação de Projetos:** Ao desenhar um pipeline prático pessoal, suba o escopo e pergunte à IA se a arquitetura respeita os princípios de idempotência e separação de camadas das fontes oficiais.

---
*Manual estruturado para guiar a transição da teoria sólida para a excelência em engenharia de dados de produção.*
"""

with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme_content)
