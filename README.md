<a href="https://postimg.cc/FYtnXpJw">
  <img src="https://github.com/GeorgeTelles/georgetelles/blob/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo" width="300">
  <img src="https://github.com/GeorgeTelles/georgetelles/blob/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo" width="300">
</a>

# CAPM - Capital Asset Pricing Model

O **Capital Asset Pricing Model (CAPM)** é um modelo fundamental na análise de investimentos, usado para estimar o retorno esperado de um ativo com base em seu risco sistemático relativo ao mercado. A fórmula do CAPM é:

\[ R_i = R_f + \beta_i (R_m - R_f) \]

onde:
- \( R_i \) é o retorno esperado do ativo,
- \( R_f \) é a taxa livre de risco,
- \( \beta_i \) é a sensibilidade do ativo em relação às flutuações do mercado,
- \( R_m \) é o retorno esperado do mercado.

## Funcionalidades do Projeto

Este projeto fornece uma implementação do modelo CAPM usando Python. Ele realiza as seguintes etapas:

1. **Recolhimento de Dados**: Os dados históricos de preços das ações e do índice de mercado são obtidos usando a biblioteca `yfinance`.
2. **Cálculo de Retornos**: Calcula-se o retorno diário e acumulado das ações e do índice do mercado.
3. **Análise e Regressão Linear**: Executa-se uma regressão linear para estimar o beta e o alpha do modelo CAPM e calcular o \( R^2 \), p-valor e erro padrão.
4. **Visualização**: Gera gráficos para visualizar o retorno acumulado e o gráfico de dispersão dos retornos diários.

## Outputs do Algoritmo

O algoritmo fornece os seguintes outputs:

- **Retorno Acumulado**: Gráficos comparativos dos retornos acumulados das ações e do índice de mercado.
- **Gráfico de Dispersão**: Visualização da relação entre os retornos diários das ações e do mercado.
- **Parâmetros da Regressão**:
  - **Beta**: Medida da sensibilidade do ativo às variações do mercado.
  - **Alpha**: Valor do intercepto na regressão, representando o retorno adicional do ativo.
  - **\( R^2 \)**: Coeficiente de determinação, indicando a proporção da variação dos retornos do ativo explicada pelo modelo.
  - **P-valor**: Testa a significância estatística dos parâmetros.
  - **Erro Padrão**: Mede a precisão dos parâmetros estimados.

Os gráficos e parâmetros ajudam a analisar o risco e o retorno esperado de um ativo em comparação com o mercado, facilitando decisões de investimento mais informadas.
