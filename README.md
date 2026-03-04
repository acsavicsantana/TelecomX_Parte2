# TelecomX_Parte2
Challenge_TelecomX – Previsão de Churn (Parte 2)
📖 Sobre o Projeto
Este projeto é a segunda etapa do desafio TelecomX , dando continuidade ao tratamento e à análise exploratória realizada na Parte 1.
Nesta fase, o foco foi a modelagem preditiva , com o objetivo de identificar clientes com maior risco de evasão ( churn ) e propor estratégias orientadas por dados para manutenção.

O projeto transforma insights descritivos da Parte 1 em soluções preditivas aplicáveis ​​ao negócio.

🎯 Objetivos
Construir modelos de Machine Learning para prevenir rotatividade
Comparar diferentes algoritmos de classificação
Avaliar desempenho com base em estatísticas detalhadas
identificar variáveis ​​mais relevantes para evasão
Propor estratégias de retenção baseadas em dados
1. Etapas do Projeto
2. Preparação dos Dados

Tratamento de valores inconsistentes
Codificação de variáveis ​​categóricas
Análise de relação
Divisão em treino e teste (80/20)

Modelagem Preditiva
Modelos desenvolvidos:

Regressão Logística
Floresta Aleatória
A normalização foi aplicada conforme necessário, considerando as características de cada algoritmo.

Avaliação dos Modelos
Métricos utilizados:

Precisão
Preferência
Lembrar
Pontuação F1
Matriz de confusão

Resultados:

Random Forest apresentou melhor desempenho, capturando padrões não lineares e maior generalização.
A Regressão Logística complementou a análise, permitindo interpretação direta dos coeficientes e influência das variáveis.

<h3>Principais Variáveis ​​Relacionadas ao Churn<h4></h4>
customer_tenure(tempo de Cá)
account_Charges_Total(valor total gasto)
account_Charges_Monthly(valor mensal)
Tipo de
Método de pagamento
(Clientes com menor tempo de contrato e contratos mensais apresentam maior probabilidade de rotatividade)

<h3>Recomendações Estratégicas<h4><h4>
- Implementar ações de prevenção nos primeiros meses de contrato
- Incentivar contratos de longo prazo
- Monitorar clientes com alto risco de predito
- Estimular métodos de pagamento automáticos
- Integrar o modelo como ferramenta de apoio à decisão

Tecnologias Utilizadas
* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* 
📌 Conclusão
Ao integrar análise exploratória e modelagem preditiva, foi possível transformar dados em insights estratégicos e propor ações concretas para redução da evasão.

Este projeto demonstra a aplicação prática de técnicas de Machine Learning para resolver problemas reais de negócio, com foco em retenção de clientes e tomada de decisão orientada por dados .
