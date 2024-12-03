# Grupo 32

Abigail Cruz dos Santos

Vinícius Amorim Santos Rozario



# Classificação de Imagens com Redes Neurais Convolucionais

Este projeto implementa uma Rede Neural Convolucional (CNN) para realizar a classificação de imagens utilizando o dataset **CUHK Face Sketch Database (CUFS)**. 

## Objetivo
Desenvolver uma abordagem de aprendizado profundo para classificação de imagens que combina eficiência computacional com alta precisão.

## Funcionalidades
- **Pré-processamento de imagens:** Realiza listagem e preparação dos dados.
- **Modelo de aprendizado profundo:** Construído com TensorFlow e Keras.
- **Métricas de avaliação:** Inclui F1-score, AUC, e relatório de classificação.

## Estrutura do Projeto
1. **Importação de Bibliotecas:** Ferramentas necessárias para manipulação de dados e modelagem.
2. **Carregamento do Dataset:** Download automático do Kaggle.
3. **Construção do Modelo:** Configuração de camadas convolucionais e fully connected.
4. **Treinamento e Avaliação:** Utiliza métricas como curva ROC e matriz de confusão.

## Dataset
- **Nome:** CUHK Face Sketch Database (CUFS)
- **Fonte:** [Kaggle](https://www.kaggle.com/datasets/arbazkhan971/cuhk-face-sketch-database-cufs)
- **Descrição:** Conjunto de imagens contendo esboços de rostos e fotografias correspondentes.

## Requisitos
- Python 3.7+
- Bibliotecas:
  - TensorFlow
  - NumPy
  - Matplotlib
  - Seaborn
  - PIL (Python Imaging Library)
  - Scikit-learn

## Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/abigailcruz29/projeto-cnn-unidade-10.git
