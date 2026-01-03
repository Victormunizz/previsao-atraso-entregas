# 🚚 Previsão de Atraso em Entregas Logísticas com Machine Learning

## 📌 Descrição do Projeto

O presente projeto tem como objetivo utilizar **análise de dados e técnicas de Machine Learning** para prever **atrasos em entregas logísticas**, um problema recorrente em empresas de transporte e e-commerce.

A falta de previsibilidade em atrasos impacta diretamente a **satisfação do cliente**, gera **custos adicionais** e prejudica a **imagem da empresa**. A partir de dados históricos, este projeto busca identificar padrões que indiquem maior probabilidade de atraso, auxiliando na **tomada de decisão preventiva**.

---

## 🎯 Objetivo

Construir um modelo de **classificação supervisionada** capaz de prever se uma entrega será:
- `0` → Entregue no prazo  
- `1` → Entregue com atraso  

com base em variáveis logísticas como distância, tempo estimado, condições climáticas e dia da semana.

---

## 🗂️ Coleta de Dados

Os dados utilizados neste projeto são provenientes de um **conjunto de dados público**, que simula informações de entregas logísticas.

### Principais variáveis:
- `distancia_km`: distância da entrega em quilômetros  
- `tempo_estimado`: tempo estimado de entrega (minutos)  
- `tempo_real`: tempo real de entrega (minutos)  
- `clima`: condição climática no momento da entrega  
- `dia_semana`: dia da semana da entrega  

A variável alvo `atraso` foi criada com base na comparação entre o tempo real e o tempo estimado de entrega.

---

## 🔍 Análise Exploratória de Dados

Foi realizada uma análise exploratória para compreender o comportamento dos dados, incluindo:
- Distribuição de entregas no prazo e atrasadas
- Relação entre distância e atraso
- Identificação de possíveis padrões associados ao clima e dia da semana

As visualizações auxiliaram na compreensão do problema e na escolha do modelo de Machine Learning.

---

## 🧠 Modelagem

O modelo escolhido foi a **Árvore de Decisão**, por apresentar:
- Fácil interpretação
- Bom desempenho em problemas de classificação
- Clareza na explicação dos resultados

### Etapas da modelagem:
1. Tratamento e codificação das variáveis categóricas
2. Separação dos dados em treino e teste (70% / 30%)
3. Treinamento do modelo
4. Realização das previsões

---

## 📏 Avaliação do Modelo

O modelo foi avaliado utilizando as seguintes métricas:
- **Acurácia**
- **Matriz de confusão**
- **Precision, Recall e F1-score**

Essas métricas permitiram avaliar a capacidade do modelo em identificar corretamente entregas atrasadas e entregas no prazo.

---

## 📊 Visualização dos Resultados

Foram gerados gráficos para:
- Distribuição de atrasos
- Relação entre distância e atraso
- Matriz de confusão do modelo

As visualizações encontram-se disponíveis na pasta `images/`.

---

## 📁 Estrutura do Projeto


