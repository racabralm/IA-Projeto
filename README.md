# Predição de Tendências no Mercado Financeiro com Machine Learning

Repositório destinado ao projeto prático da disciplina de Inteligência Artificial (7º semestre) da Universidade Presbiteriana Mackenzie.

## 👥 Integrantes

| Nome | RA |
| :---------------- | :------ | 
| Rafael Araujo Cabral Moreira | 10441919 |
| Rute Willemann | 10436781 |

## 🎯 Sobre o Projeto
Este projeto visa aplicar conceitos de Inteligência Artificial para solucionar um problema prático na área de Negócios. 
**Opção Escolhida:** Opção Framework (uso da biblioteca `scikit-learn` para classificação/predição de negócio).

O objetivo é desenvolver, treinar e avaliar modelos preditivos (Regressão Logística e *Random Forest*) capazes de analisar séries temporais e prever a tendência diária (alta ou baixa) do preço de fechamento de ações de grandes empresas listadas na bolsa brasileira (B3).

## 📊 Descrição do Dataset
O conjunto de dados é formado por dados originais financeiros extraídos diretamente do mercado de capitais.

* **Origem/Fonte:** Capturado via API oficial do Yahoo Finance (`yfinance`).
* **Conteúdo:** Histórico de negociações diárias dos últimos 2 anos das empresas Petrobras, Vale, Itaú, Bradesco e Ambev. As principais variáveis incluem Preço de Abertura (Open), Fechamento (Close), Máxima (High), Mínima (Low) e Volume de transações.
* **Anonimização:** Como são dados de mercado de capital aberto, não há dados pessoais sensíveis, eliminando riscos de vazamento de privacidade.

## 📂 Estrutura do Repositório (Fase N2)
* `docs/`: Relatório do Projeto atualizado (N2) em PDF.
* `data/`: Arquivo `dataset_acoes_negocios.csv`.
* `notebooks/`: 
  * `Projeto_IA_Dados.ipynb`: Código em Python para a captura de dados via API.
  * `Projeto_IA_Gráficos.ipynb`: Código para Análise Exploratória (EDA) e visualização de dados.
  * `Projeto_IA_Modelagem.ipynb`: Treinamento, engenharia de recursos e avaliação de métricas dos modelos de *Machine Learning*.

## 🎥 Apresentação em Vídeo
Assista à demonstração da plataforma e explicação técnica da solução de IA aplicada:
**[Link do Vídeo no YouTube - cola aqui]**
