# Predição de Tendências no Mercado Financeiro com Machine Learning

Repositório destinado ao projeto prático da disciplina de Inteligência Artificial (7º semestre) da Universidade Presbiteriana Mackenzie.

## 👥 Integrantes

| Nome | RA |
| :---------------- | :------ | 
Rafael Araujo Cabral Moreira | 10441919
Rute Willemann | 10436781

## 🎯 Sobre o Projeto
Este projeto visa aplicar conceitos de Inteligência Artificial para solucionar um problema prático na área de Negócios. 
**Opção Escolhida:** Opção Framework (uso da biblioteca scikit-learn para classificação/predição de negócio).

O objetivo é desenvolver um modelo preditivo capaz de analisar séries temporais e prever a tendência (alta ou baixa) do preço de fechamento de ações de grandes empresas listadas na bolsa brasileira (B3).

## 📊 Descrição do Dataset
O conjunto de dados é formado por dados originais financeiros extraídos diretamente do mercado de capitais.

* **Origem/Fonte:** Capturado via API oficial do Yahoo Finance (`yfinance`).
* **Conteúdo:** Histórico de negociações diárias dos últimos 2 anos das empresas Petrobras, Vale, Itaú, Bradesco e Ambev. As principais variáveis incluem Preço de Abertura (Open), Fechamento (Close), Máxima (High), Mínima (Low) e Volume de transações.
* **Anonimização:** Como são dados de mercado de capital aberto, não há dados pessoais sensíveis, eliminando riscos de vazamento de privacidade.

## 📂 Estrutura do Repositório (N1)
* `docs/`: Relatório do Projeto atualizado em PDF.
* `data/`: Arquivo `dataset_acoes_negocios.csv`.
* `notebooks/`: Códigos em Python da captura e da Análise Exploratória (EDA).
