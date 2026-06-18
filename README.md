# Desafio de Projeto: Caderno Temático com NotebookLM (DIO)

## 🎯 Contexto e Objetivos
O assunto escolhido para este caderno temático é a **Engenharia de Dados Moderna**. O objetivo deste material é construir uma base conceitual e prática robusta, cobrindo desde os fundamentos do ciclo de vida dos dados até ferramentas de transformação (dbt) e arquiteturas modernas de armazenamento (Lakehouse), servindo como guia de consulta rápida e portfólio de estudos.

## 📚 Curadoria de Fontes (Ancoragem no NotebookLM)
Foram selecionadas 4 fontes estratégicas e abertas para alimentar a inteligência artificial sem alucinações:
1. **Livro: Fundamentals of Data Engineering** (Joe Reis & Matt Housley) - Guia agnóstico sobre o ciclo de vida dos dados.
2. **Documentação Oficial do dbt (Introduction, Models & Tests)** - Padrão de mercado para transformações SQL estruturadas.
3. **Artigo Técnico Databricks (What is a Data Lakehouse?)** - Base para entendimento da arquitetura de medalhão.
4. **The Data Engineering Cookbook (Andreas Kretz)** - Princípios práticos de engenharia de software aplicados a dados.

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

### Prompt de Estruturação Principal Testado:
> *"Atue como um Arquiteto de Dados Sênior e Mentor. Com base em todas as fontes do meu caderno, crie um roteiro de estudos de 4 semanas focado em me levar do zero até a capacidade de desenhar um pipeline de dados moderno. Para cada semana, defina o conceito teórico principal que devo dominar e qual ferramenta prática devo focar."*
*   **Resultado:** A IA cruzou perfeitamente os capítulos teóricos do livro do Joe Reis com os módulos práticos da documentação do dbt, gerando o cronograma contido neste guia.

### 🩹 Cicatrizes e Desafios Encontrados (Troubleshooting):
*   **O Problema:** Inicialmente, a intenção era utilizar o link direto do curso gratuito *dbt Fundamentals*. No entanto, o NotebookLM não consegue ler dados atrás de telas de login ou registros (Paywalls).
*   **A Solução:** Para contornar a limitação de acesso da IA, foi realizada uma curadoria substituta apontando diretamente para os links públicos da documentação técnica do dbt (`docs.getdbt.com`), garantindo a mesma qualidade técnica de dados para o modelo, ou utilizando a técnica de "Copied Text" para trechos específicos extraídos manualmente das aulas.

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
