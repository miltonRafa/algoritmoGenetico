# Algoritmo Genetico

Implementacao de algoritmo genetico para resolver o Problema do Caixeiro Viajante (TSP - Traveling Salesman Problem).

## Descricao

Sistema que utiliza tecnicas de computacao evolutiva para encontrar rotas otimizadas no problema do caixeiro viajante. Implementa mutacao por inversao com hill climbing, elitismo adaptativo e estrategia de intensificacao. Gera visualizacao grafica automatica das 10 melhores rotas encontradas.

## Tecnologias

- Python 3
- matplotlib (visualizacao de graficos)

## Funcionalidades

- Definicao de cidade inicial fixa
- Geracao de populacao inicial de rotas aleatorias
- Selecao por torneio
- Crossover de ordem (OX)
- Mutacao por inversao com hill climbing
- Elitismo adaptativo (25% inicial, 50% apos primeira geracao)
- Reducao populacional para intensificacao
- Criterio de convergencia (20 geracoes sem melhoria)
- Visualizacao grafica das 10 melhores rotas

## Como executar

### Pre-requisitos

```bash
pip install matplotlib
```

### Executar algoritmo

```bash
python3 caixeiro_viajante.py
```

### Entrada de dados

O programa solicitara:
- Nome da cidade inicial
- Coordenadas da cidade inicial (formato: x,y)

Exemplo:
```
Digite o nome da cidade inicial: Itba
Digite as coordenadas da cidade inicial no formato x,y: 0,0
```

## Estrutura

```
algoritmo_genetico/
├── caixeiro_viajante.py
├── README.md
├── README_CAIXEIRO_VIAJANTE.md
├── screenshots/
└── venv/
```
