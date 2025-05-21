# Cálculo Numérico

Este repositório reúne códigos e aplicações desenvolvidas ao longo da disciplina de **Cálculo Numérico**.  
Cada notebook explora conceitos fundamentais por meio de algoritmos e visualizações, promovendo uma abordagem prática e interativa.

## Executar online

Para executar algum notebook online, abra o ambiente interativo clicando no botão abaixo:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/YannLeao/Numerical-Calculus/main)

> Após carregar, selecione o notebook desejado e vá em: `Run > Run All Cells`.

<!--
COLOCAR O GIF!!
<div align="center">
  <img width="50%" src="assets/gif-como-executar.gif" alt="Gif de como executar">
</div>
-->

## Conteúdo

### 1. [Precisão de Máquina](notebooks/precisao_de_maquina.ipynb)
Análise da menor variação reconhecível em ponto flutuante (erro de arredondamento), usando `float`, `numpy`, `decimal`, e comparando diferentes precisões numéricas.  
Inclui gráfico final com os resultados comparativos.

### 2. [Zeros de Funções Reais](notebooks/zeros_de_funcoes_reais.ipynb)
Estudo das técnicas numéricas para determinar as raízes de funções reais.  
Apresenta métodos como Bissecção, Posição Falsa, Ponto Fixo, Newton e Secante, comparando suas eficiências por meio de iterações e gráficos.

### 3. [Matriz de Hilbert e Eliminação Gaussiana](notebooks/hilbert_eliminacao_gaussiana.ipynb)
Resolução de sistemas lineares com matriz de Hilbert usando Eliminação Gaussiana.  
Inclui análise dos resultados para diferentes dimensões $n = 3$, $n = 10$, $n = 100$ e cálculo do determinante a partir da matriz escalonada.

### 4. [Interpolação Polinomial de Newton](notebooks/interpolacao_polinomial.ipynb)
Aplicação da interpolação polinomial de Newton para estimar o calor específico da água, com base em uma tabela de valores experimentais.  
O notebook também obtém um polinômio interpolador de grau 3 e, a partir dele, resolve numericamente a equação $p(x) = 0{,}99837$ usando o método da secante, para determinar a temperatura correspondente.  
Inclui visualizações do polinômio ajustado e análise da convergência do método.
