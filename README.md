# Projeto: Classificação de Grãos de Trigo com Machine Learning 🌾

## Descrição
Automatização da classificação de variedades de grãos de trigo (Kama, Rosa e Canadian) usando aprendizado de máquina, com o dataset Seeds do UCI.

## Metodologia
- Análise exploratória dos dados 📊
- Pré-processamento e padronização
- Treinamento de modelos: KNN, SVM, Random Forest, Naive Bayes e Regressão Logística
- Otimização do Random Forest com GridSearchCV ⚙️
- Avaliação dos modelos com métricas de desempenho

## Resultados
- Melhora na acurácia após otimização do Random Forest
- Alta precisão na classificação das variedades

## Tecnologias
- Python, pandas, numpy, matplotlib, seaborn
- Scikit-learn
- Google Colab

## Como usar
1. No Google Colab, baixe o arquivo `seeds_dataset.txt` diretamente do GitHub executando a célula abaixo:

```python
!wget https://raw.githubusercontent.com/Amand95/mplementando-algoritmos-de-Machine-Learning-com-Scikit-learn-/main/seeds_dataset.txt

