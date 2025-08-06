# challenge_telecomx_II

Este projeto foi desenvolvido como parte de um desafio de programação oferecido pelo curso TelecomX II da plataforma Alura. O objetivo é aplicar técnicas de pré-processamento, modelagem e análise de dados em um dataset real de telecomunicações.

Inclui:  
- Preparação e balanceamento do dataset  
- Normalização dos dados  
- Treinamento e avaliação de modelos: KNN, Árvore de Decisão e Floresta Aleatória  
- Visualização do desempenho dos modelos e matrizes de confusão

## Requisitos

- Python 3.x  
- scikit-learn  
- imblearn  
- pandas  
- matplotlib  
- seaborn

## Estrutura de pastas

- **Dados**  
  Contém os arquivos do dataset e scripts para processamento dos dados:  
  - `Processamento.ipynb`: notebook para preparação e limpeza dos dados.  
  - `TelecomX_Data.json`, `TelecomX_tratado.pickle`, `Telecom_Data_to_ML.pickle`: arquivos com os dados em diferentes formatos para facilitar o carregamento.

- **Análises Estatísticas**  
  Contém análise exploratória e estatística dos dados:  
  - `Análise.ipynb`: notebook com visualizações e estudos estatísticos para entender o comportamento dos dados.

- **Teste de Modelos**  
  Contém os experimentos de modelagem e avaliação:  
  - `Modelos.ipynb`: notebook com os treinamentos e avaliações dos modelos (KNN, Árvore de Decisão, Floresta Aleatória).
