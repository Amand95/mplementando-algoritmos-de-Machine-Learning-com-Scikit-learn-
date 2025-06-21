# Projeto: Classificação de Grãos de Trigo com Machine Learning 🌾

## 📋 Descrição do Projeto

Este projeto tem como objetivo automatizar a classificação de grãos de trigo utilizando técnicas de aprendizado de máquina. Em cooperativas agrícolas de pequeno porte, a classificação é feita manualmente por especialistas, um processo que pode ser demorado e sujeito a erros. Com o uso de modelos de machine learning, buscamos aumentar a eficiência e a precisão da classificação das variedades de grãos.

## 🎯 Objetivo

Aplicar a metodologia CRISP-DM para desenvolver modelos capazes de classificar corretamente três variedades de grãos de trigo (Kama, Rosa e Canadian) com base em suas características físicas.

## 📂 Conjunto de Dados

Utilizamos o "Seeds Dataset", disponível no UCI Machine Learning Repository, que contém medições de 210 amostras de grãos com as seguintes características:

| Atributo                   | Descrição                                    |
|----------------------------|----------------------------------------------|
| Área                       | Medida da área do grão                        |
| Perímetro                  | Comprimento do contorno do grão               |
| Compacidade                | Calculada como (área)/(perímetro²)           |
| Comprimento do Núcleo      | Comprimento do eixo principal da elipse do grão |
| Largura do Núcleo          | Comprimento do eixo secundário da elipse      |
| Coeficiente de Assimetria  | Medida da assimetria do grão                   |
| Comprimento do Sulco do Núcleo | Comprimento do sulco central do grão          |

## 🛠 Metodologia

Seguindo a metodologia CRISP-DM, as etapas realizadas foram:

1. **Análise e pré-processamento dos dados**  
   - Importação e inspeção inicial do dataset  
   - Tratamento de dados ausentes (não encontrados)  
   - Análise estatística descritiva (média, mediana, desvio padrão)  
   - Visualização das distribuições e correlações entre atributos  
   - Padronização (scaling) dos dados para modelos  

2. **Implementação e comparação de algoritmos de classificação**  
   - Divisão dos dados em treino (70%) e teste (30%)  
   - Teste de cinco algoritmos: KNN, SVM, Random Forest, Naive Bayes e Regressão Logística  
   - Avaliação por métricas: acurácia, precisão, recall, F1-score, matriz de confusão  

3. **Otimização dos modelos**  
   - Uso de GridSearchCV para ajuste dos hiperparâmetros do Random Forest  
   - Reavaliação do modelo otimizado  

4. **Interpretação dos resultados**  
   - Comparação dos desempenhos dos modelos  
   - Insights sobre os atributos mais relevantes para a classificação  
   - Relevância do pré-processamento e validação cruzada  

## 📊 Resultados

- Todos os modelos apresentaram boa acurácia, com o Random Forest otimizando o desempenho com os parâmetros ajustados.  
- As matrizes de confusão mostraram alta precisão na classificação das três variedades de grãos.  
- A padronização dos dados foi fundamental para melhorar o desempenho de alguns algoritmos, especialmente SVM e KNN.  

## 🚀 Como Executar

1. Clone este repositório  
2. Instale as dependências via:  
   ```bash
   pip install -r requirements.txt

## Como usar

1. Abra o notebook no Google Colab:  
[https://colab.research.google.com/drive/1CzPCl0eUkq5RmRuhZye0xcUmGLPJAqOx#scrollTo=-H_Ryr4vvJZy](https://colab.research.google.com/drive/1CzPCl0eUkq5RmRuhZye0xcUmGLPJAqOx#scrollTo=-H_Ryr4vvJZy)


