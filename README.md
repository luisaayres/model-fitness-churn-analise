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
- A taxa geral de churn foi de aproximadamente 26,5%, indicando uma parcela relevante de clientes em risco de saída.
- Clientes que permaneceram apresentaram maior frequência de visitas, maior tempo de relacionamento, contratos mais longos e maior participação em sessões de grupo.
- A frequência média de visitas no mês atual foi de 2,03 vezes por semana entre clientes que permaneceram, contra 1,04 vez entre os que saíram.
- O lifetime médio foi de 4,71 meses entre clientes que permaneceram, contra 0,99 mês entre os clientes que saíram.
- A Regressão Logística apresentou o melhor desempenho preditivo, com 91,9% de acurácia, 86,6% de precisão e 81,2% de sensibilidade.
- A segmentação por K-Means identificou 5 grupos de clientes, com diferenças relevantes de comportamento e taxas de churn.
- Os grupos com maior risco de churn são caracterizados principalmente por menor frequência de visitas, menor tempo de relacionamento e contratos mais curtos.
- Os resultados indicam que estratégias de retenção devem priorizar clientes com baixo engajamento e maior risco de churn, utilizando ações de incentivo à frequência, participação em atividades e fidelização.

## 💡 Conclusão

A análise dos agrupamentos mostrou que os clientes possuem perfis e níveis de risco de saída diferentes. Portanto, uma estratégia de retenção segmentada é mais adequada.

- Priorizar os clusters 3 e 2: apresentam as maiores taxas de churn e devem receber campanhas específicas de retenção, incentivos de frequência, benefícios e ações de renovação.
- Trabalhar preventivamente com o cluster 1: com churn intermediário de 26,75%, esse grupo deve ser monitorado para identificar sinais de redução de frequência e evitar o aumento do risco de saída.
- Estimular clientes pouco engajados: ações como desafios de frequência, notificações, recompensas por visitas e incentivos à renovação podem aumentar o engajamento.
- Fidelizar os clusters 0 e 4: por apresentarem baixa rotatividade, esses clientes podem receber benefícios exclusivos, programas de fidelidade e incentivos para indicação e consumo de serviços adicionais.
- Personalizar as estratégias: os diferentes perfis identificados indicam que uma única abordagem para todos os clientes não seria a mais adequada.

Em resumo, a prioridade deve ser reduzir a rotatividade dos clusters 3 e 2, enquanto os clusters 0 e 4 devem receber ações de fidelização e aumento de receita. A segmentação permite direcionar os esforços de retenção para os clientes com maior risco e fortalecer o relacionamento com os clientes mais leais.

## 📓 Notebook

A análise completa pode ser consultada no notebook:

[👉 Acessar o notebook do projeto](notebook.ipynb)
