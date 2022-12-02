# 📊 Desafio de Inferência da [TERA](https://somostera.com/)

Este desafio é parte da minha formação na pós graduação de [Data Science & Machine Learning](https://somostera.com/cursos/data-science-machine-learning) da TERA.

## 🍽️ Sobre o Desafio

### Problema:
Entender a relação entre depressão e hábitos saudáveis.

### Etapas do desafio:
- Tratamento e manipulação do banco de dados.
  - Combinar os 2 bancos de dados.
- Análise exploratória univariada.
  - Entender as variáveis.
- Análise exploratória bi-variada.
  - levantar as hipóteses.
- Teste de hipóteses.
- Perguntas TERA.

## 🍽️ Sobre as fontes dos dados.

### National Health and Nutrition Examination Survey (NHANES)
- É uma pesquisa anual para avaliar a saúde e nutrição de adultos e crianças nos EUA.
- Possui dados demográficos, socioeconômicos, dietétivos, de saúde e exames.
- São entrevistados 5 mil pessoas por anos, uma amostragem complexa, da população civil não institucionalizada dos EUA, mas que para este desafio vamos assumir que seja uma amostragem aleatória

### Patient Health Questionnaire-9 (PHQ-9)
- É o instrumento utilizado para avaliar o grau de depressão em pacientes.
- Questionário de 9 itens.
- Respostas de 0 a 3.
  - 0: "nenhuma vez".
  - 1: "menos de uma semana".
  - 2: "uma semana ou mais".
  - 3: "quase todos os dias".
- Perguntas sobre as 2 últimas semanas.
  - 1) Pouco interesse ou pouco prazer em fazer as coisas.
  - 2) Se sentiu para baixo, deprimido ou sem perspectiva.
  - 3) Dificuldade para pegar no sono/permanecer dormindo ou dormir muito.
  - 4) Se sentiu cansado ou com pouca energia.
  - 5) Falta de apetite ou comeu demais.
  - 6) Se sentiu mal consigo mesmo ou achou que é um fracasso ou que decepcionou sua família ou você mesmo.
  - 7) Dificuldade para se concentrar nas coisas.
  - 8) Lentidão para se movimentar ou falar, ou o contrário, muito agitado.
  - 9) Pensou em se ferrir de alguma maneira ou que seria melhor estar morto.
- Todas essas perguntas geram um "escore".
  - (5-9): "sintomas leves".
  - (10-14): "moderados".
  - (15-19): "moderadamente severos".
  - (>= 20): "severos de depressão".
  
### 

## 🎯 Objetivo do estudo

O objetivo deste trabalho é desenvolver um sistema de calcule as características mais comuns em paciêntes diagnosticados com câncer de pulmão, calculando o percentual de paciêntes diagnosticados para cada característica apresentada no data set. 

No final do trabalho, o objetivo é aprensetam uma lista ordena com as características com maior percentual presente nos casos diagnosticados, como também uma lista ordenada pela quantidade em que essas características apareceram nestes pacientes.
