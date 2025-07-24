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

### 5. [Método dos Mínimos Quadrados](notebooks/metodo_minimos_quadrados.ipynb)
Utilização do Método dos Mínimos Quadrados (MMQ) para obter uma função $\varphi(x)$ que relaciona o preço de fechamento da B3 de um ativo com o tempo, visando prever o preço de fechamento para o próximo dia.  
Além disso, são calculados o erro quadrático e o intervalo de confiança da previsão.

### 6. [Integração Numérica](notebooks/integracao_numerica.ipynb)
Aplicação de métodos de integração numérica para aproximar o valor da integral:

$$
\int_{0}^{1} e^{-x^2} \, dx
$$

Foram utilizados os métodos da **Regra dos Trapézios** e da **Regra de 1/3 de Simpson**, com o cálculo de $n$ mínimo necessário para atender a uma precisão previamente estabelecida.  

### 7. [Modelo SIR - Epidemias com Runge-Kutta](notebooks/modelo_sir.ipynb)
Simulação da propagação de uma epidemia utilizando o modelo SIR (Suscetíveis, Infectados, Recuperados) resolvido numericamente com o método de **Runge-Kutta de ordem 4 (RK4)**.  
São plotadas as curvas $S(t)$, $I(t)$ e $R(t)$ ao longo de 60 dias com passo $h = 0{,}1$, permitindo visualizar o comportamento da epidemia.

O notebook também identifica:
- O **dia do pico** de infectados
- Quando a epidemia pode ser considerada **controlada**

Inclui gráfico e interpretação dos resultados.

