# 🏋️ Análise de Churn e Segmentação de Clientes — Model Fitness

## 📌 Sobre o Projeto

Este projeto analisa o comportamento dos clientes da rede de academias Model Fitness, com foco na identificação de fatores associados à rotatividade (churn) e na criação de estratégias para aumentar a retenção de clientes.

Foram utilizados modelos de classificação e técnicas de clusterização para identificar clientes com maior probabilidade de churn e diferentes perfis de comportamento.

## 🎯 Objetivos
- Analisar o perfil dos clientes e os fatores associados ao churn;
- Identificar clientes com maior probabilidade de saída;
- Comparar modelos de previsão de churn;
- Criar grupos de clientes com características semelhantes;
- Identificar grupos mais propensos à rotatividade;
- Desenvolver recomendações para melhorar a retenção.

## 🛠️ Ferramentas e Tecnologias
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

## 🔎 Análises Realizadas
- Análise exploratória dos dados;
- Comparação entre clientes que permaneceram e clientes que saíram;
- Análise de correlação entre as variáveis;
- Regressão logística e floresta aleatória para previsão de churn;
- Clusterização hierárquica e K-Means;
- Identificação e análise de 5 grupos de clientes;
- Avaliação da taxa de churn por cluster;
- Criação de perfis de clientes e recomendações de retenção.

## 📈 Principais Resultados
- Foram analisados 4.000 clientes e 14 variáveis;
- A taxa geral de churn foi de aproximadamente 26,5%;
- Clientes que permaneceram apresentaram maior frequência de visitas, contratos mais longos, maior tempo de permanência e maior participação em sessões de grupo;
- Clientes que permaneceram frequentaram a academia, em média, 2,03 vezes por semana no mês atual, contra 1,04 vez entre os clientes que saíram;
- O lifetime médio foi de 4,71 meses entre os clientes que permaneceram, contra 0,99 mês entre os que saíram;
- A regressão logística apresentou melhor desempenho que a floresta aleatória, com acurácia de 91,9%, precisão de 86,6% e sensibilidade de 81,2%;
- O K-Means identificou 5 clusters com diferentes perfis de clientes e taxas de churn;
- Os clusters apresentaram diferenças relevantes de comportamento, permitindo identificar grupos mais vulneráveis à saída e grupos mais leais;
- Características como frequência de visitas, duração do relacionamento, período de contrato e participação em atividades de grupo mostraram-se importantes para diferenciar clientes com maior e menor risco de churn.

## 💡 Conclusão

Os resultados indicam que o engajamento e a frequência de utilização da academia estão fortemente associados à retenção dos clientes. Clientes com contratos mais longos, maior frequência de visitas, maior lifetime e participação em atividades de grupo apresentam um perfil mais leal.

A estratégia de retenção deve priorizar os clientes com baixa frequência de visitas, contratos curtos e pouco tempo de relacionamento, utilizando os clusters identificados para direcionar ações específicas de engajamento e fidelização.

## 📓 Notebook

A análise completa pode ser consultada no notebook:

[👉 Acessar o notebook do projeto](notebook.ipynb)
