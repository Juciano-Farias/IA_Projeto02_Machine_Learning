# Inteligência Artificial

<h2 align="center">
  Machine Learning
</h2>

<h4 align="center"> 
	🚧  🚀 Concluido  🚧
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-tecnologias">Tecnologias</a> • 
</p>

# [Link do GitHub do projeto](https://github.com/Juciano-Farias/IA_Projeto02_Machine_Learning)

## 💻 Sobre o projeto

Analisar o crescimento populacional das cidades entre 2022 e 2023, classificando-as em categorias de crescimento (baixo, moderado, alto) para identificar padrões significativos e auxiliar no planeamento urbano e políticas públicas.

## Algoritmos Escolhidos

Para a tarefa de classificação, foram selecionados dois algoritmos:

- Random Forest e Decision Tree Classifier.
- O Random Forest foi configurado com 100 árvores e profundidade máxima de 5
- Decision Tree Classifier foi utilizado com profundidade máxima de 5

## Critérios de Seleção de Dados

Os dados foram selecionados com base na disponibilidade de informações sobre a população das cidades ao de 2 anos, garantindo representatividade global e abrangendo um período significativo para análise de tendências.

## Preparação dos Dados

- Os dados foram preparados através dos seguintes passos:

- Conversão da coluna 'city' para formato numérico usando LabelEncoder.

- Cálculo da taxa de crescimento percentual da população de 2022 para 2023.

- Categorização da taxa de crescimento em três classes: baixo, moderado e alto.
  Tratamento de valores ausentes e seleção de características relevantes ('population_in_2022', 'population_growthRate', 'city').

## Aplicação dos Algoritmos de ML e Avaliação dos Modelos

- Os modelos foram treinados usando os conjuntos de treino e teste. A performance foi avaliada através de:

- Matriz de confusão.

- Pontuação de precisão.

- Relatório de classificação, incluindo métricas como precisão, recall e F1-score.
