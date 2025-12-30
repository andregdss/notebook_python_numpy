# Notebook Didático de Computação Numérica com NumPy

Este repositório apresenta uma exploração detalhada da biblioteca **NumPy (Numerical Python)**, pilar fundamental da computação científica e da análise de dados em Python.  
O conteúdo foi estruturado para atuar tanto como **guia de referência rápida** quanto como **material didático**, com foco na manipulação eficiente de matrizes multidimensionais (*ndarrays*).

## 1. Visão Geral

O NumPy é essencial no ecossistema de Ciência de Dados por oferecer estruturas de dados altamente eficientes, capazes de processar grandes volumes de informações com elevado desempenho computacional.  
Neste notebook, são abordados conceitos que vão desde a importação de dados externos até aplicações introdutórias de álgebra linear e geração de dados estocásticos.

## 2. Conteúdo do Notebook

### Fundamentos de Arrays

- **Diferenciação Semântica**
  - Comparação entre arrays NumPy e listas nativas do Python
  - Homogeneidade de tipos e eficiência no uso de memória
- **Atributos de Estrutura**
  - Inspeção de dados por meio dos atributos:
    - `.ndim` — número de dimensões
    - `.size` — total de elementos
    - `.shape` — formato da matriz

### Manipulação e Operações

- **Carregamento de Dados**
  - Importação de bases de dados via URL e arquivos locais
  - Uso de `np.loadtxt` com seleção de colunas e definição de delimitadores
- **Vetorização e Matemática**
  - Aplicação direta de operações estatísticas (média, soma)
  - Operações matemáticas vetorizadas (potenciação, raiz quadrada)
- **Álgebra Linear**
  - Introdução ao cálculo de normas entre arrays
  - Transformações matriciais, como transposição

### Geração de Dados e Aleatoriedade

- **Distribuições Numéricas**
  - Criação de sequências com `arange`
  - Geração de números aleatórios com distribuições uniformes e inteiras
- **Reprodutibilidade**
  - Utilização de sementes (`random.seed`) para replicação de experimentos computacionais

## 3. Aplicações Práticas (Exercícios)

O notebook inclui exercícios voltados à consolidação do aprendizado por meio de problemas aplicados:

- **Análise de Dados Reais**
  - Processamento do dataset `citrus.csv`
  - Comparação de métricas físicas (diâmetro e peso) entre espécies de frutas
- **Visualização Geométrica**
  - Uso integrado de NumPy e Matplotlib
  - Representação matemática de um círculo a partir de funções de raiz quadrada e intervalos numéricos

## 4. Tecnologias Utilizadas

- **Python 3**
- **NumPy**
  - Processamento numérico e computação científica
- **Pandas**
  - Suporte à manipulação de dados tabulares
- **Matplotlib**
  - Visualização gráfica de dados

## 🚀 Como Utilizar

Para executar o notebook, recomenda-se:

- Utilizar o **Google Colab**, ou
- Executar localmente em um ambiente **Jupyter Notebook**

Basta abrir o arquivo `.ipynb` e executar as células sequencialmente para acompanhar os exemplos e exercícios.
