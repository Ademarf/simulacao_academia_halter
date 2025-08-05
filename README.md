
# Simulação de Academia com Halteres

Este projeto simula o uso de halteres em uma academia, com diferentes tipos de usuários que influenciam na organização do ambiente. A ideia é medir o **nível de desorganização (caos)** causado por usuários normais e bagunceiros ao longo de vários dias.

> A simulação utiliza o método de **Monte Carlo** para repetir cenários aleatórios e observar a distribuição dos resultados.

## Objetivo

- Praticar programação orientada a objetos (POO) em Python
- Simular o uso compartilhado de recursos (halteres)
- Visualizar o impacto do comportamento dos usuários
- Gerar um gráfico com a distribuição do caos usando Seaborn

##  Como funciona

- Os halteres vão de 10 kg a 34 kg (pares).
- Cada posição correta é identificada pelo seu peso.
- Usuários:
  - **Normais**: tentam devolver o haltere no lugar certo.
  - **Bagunceiros**: devolvem em qualquer lugar livre.
- O código calcula o **nível de caos**, que é a porcentagem de halteres fora do lugar correto.
- O gráfico final mostra a variação do caos ao longo de 50 dias.

## Exemplo de visualização

O gráfico mostra a frequência do nível de desorganização causado ao longo das simulações.

## Requisitos

- Python 3
- Bibliotecas:
  - `random` 
  - `matplotlib`
  - `seaborn`

No Colab, basta rodar as células que tudo funciona!

  
Projeto feito como prática de simulação e visualização de dados em Python.
