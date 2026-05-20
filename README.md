# TripleTen Sprint 4: Análise Estatística de Dados da Megaline 📞📊

Este repositório contém o projeto final da quarta sprint do curso de Análise de Dados da TripleTen. O objetivo principal foi realizar uma **Análise Estatística de Dados** para a empresa de telecomunicações Megaline, determinando qual de seus planos pré-pagos (Surf ou Ultimate) gera mais receita.

## 📋 Contexto do Negócio
A Megaline oferece dois planos aos seus clientes e precisa entender o comportamento de consumo (chamadas, mensagens e internet) para ajustar seu orçamento de publicidade. O projeto foca em analisar os dados de 500 clientes durante o ano de 2018 para identificar padrões de uso e rentabilidade.

## 🛠️ Tecnologias e Ferramentas
*   **Python 3.x**
*   **Pandas:** Manipulação, limpeza e agregação de dados de múltiplas fontes.
*   **SciPy (stats):** Realização de testes de hipóteses estatísticas.
*   **Matplotlib:** Criação de visualizações para análise de distribuição e comportamento.
*   **Math:** Cálculos auxiliares de arredondamento e conversão de unidades (MB para GB).

## 🚀 Desafios Técnicos Superados
Este projeto exigiu um rigor técnico elevado em análise de dados e estatística:
*   **Agregação Complexa de Dados:** Consolidação de cinco tabelas diferentes (chamadas, internet, mensagens, planos e usuários) em um único DataFrame mensal por usuário.
*   **Cálculo de Receita:** Desenvolvimento de lógica personalizada para calcular a receita mensal, considerando limites dos planos e taxas por uso excedente.
*   **Análise de Distribuição:** Estudo das médias, variâncias e desvios padrão do consumo de minutos, mensagens e volume de dados para cada plano.
*   **Testes de Hipóteses (Inferência Estatística):**
    *   Aplicação do **Teste t de Student** para comparar se a receita média dos planos Surf e Ultimate é diferente.
    *   Teste estatístico para verificar se a receita média dos usuários da região de NY-NJ difere das outras regiões.

## 📊 Principais Insights
*   Determinação de qual plano é estatisticamente mais lucrativo para a empresa.
*   Identificação de comportamentos de consumo distintos entre os usuários de cada plano.
*   Validação de hipóteses sobre a influência geográfica na receita gerada.

## 📁 Estrutura do Repositório
*   `notebook.ipynb`: O notebook Jupyter com o ciclo completo de análise: carregamento, preparação, análise exploratória e testes estatísticos.
*   `README.md`: Este arquivo com a apresentação do projeto.

---
*Este projeto faz parte da minha formação como Analista de Dados na TripleTen Brasil.*
