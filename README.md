# 📊 Desafio de Inferência da [TERA](https://somostera.com/)

Este desafio é parte da minha formação na pós graduação de [Data Science & Machine Learning](https://somostera.com/cursos/data-science-machine-learning) da TERA.

## 🧑🏼‍🔬 Sobre o Desafio.

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

## 🗂️ Sobre as fontes dos dados.

### National Health and Nutrition Examination Survey (NHANES).
- É uma pesquisa anual para avaliar a saúde e nutrição de adultos e crianças nos EUA.
- Possui dados demográficos, socioeconômicos, dietétivos, de saúde e exames.
- São entrevistados 5 mil pessoas por anos, uma amostragem complexa, da população civil não institucionalizada dos EUA, mas que para este desafio vamos assumir que seja uma amostragem aleatória

### Patient Health Questionnaire-9 (PHQ-9).
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
- Todas essas perguntas geram um *score*.
  - (5-9): "sintomas leves".
  - (10-14): "moderados".
  - (15-19): "moderadamente severos".
  - (>= 20): "severos de depressão".
  
### Healthy Eating Index - (HEI).
- É uma medida de qualidade da dieta baseada nas orientações dietéticas do governo federal americano.
- O *score* varia de 0 a 100.
  - Quanto maior o valor (mais próximo de 100), mais próximo das dietas recomendadas.
- O índice é composto por 13 componentes.

### Physical Activity Guidelines for Americans (PAGA).
- É emitido pelo Departamento de Saúde e Serviços Humanos e possue recomendações de atividades físicas.
- Utilizado em conjunto com as orientações dietéticas.
- Recomendação de 150 minutos de ativdades aeróbicas moderadas semanalmente ou 75 minuyos de atividades aeróbicas vigorosas semanalmente.

Portanto nossas fontes de dados são:
- NHANES: saúde e nutrição de adultos.
- PHQ-9: depressão em pacientes.
- HEI: qualidade da dieta (recomendação).
- PAGA: recomendação de atividades físicas.

## 🎯 Objetivo do estudo

Encontrar correlações entre as variáveis, levantar hipóteses e testá-las utilizando ferramentas estatísticas aplicadas em Python.
É importante ressaltar que correlação não é causalidade, partindo de um estudo observacional, o objetivo deste trabalho está relacionado ao aprendizado e aplicação de ferramentas de programação em ciência de dados, e não deve ser utilizado para fins de orientação por pessoas que possuam sintomas descritos no estudo.
