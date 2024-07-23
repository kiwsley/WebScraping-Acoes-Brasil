# Projeto de Análise de Indicadores Fundamentalistas

Este projeto foi criado utilizando como referência o vídeo do YouTube: https://www.youtube.com/watch?v=gJ7ZQxfP_dA

# Descrição
Utilizei o Selenium para buscar as informações referentes aos indicadores fundamentalistas no portal do Fundamentus.

Em seguida, o carregamento e tratamento dos dados foi realizado com a biblioteca Pandas, onde fizemos a filtragem das ações utilizando as seguintes métricas:

P/L: Maior que 5 e menor que 20
P/VP: Menor que 3
Yield: Entre 5% e 16%
EV/EBIT: Menor que 10
ROIC: Maior que a SELIC
Dívida Bruta / Patrimônio Líquido: Menor que 3
Crescimento nos últimos 5 anos: Maior que 10%
Liquidez dos últimos 2 meses: Maior que 1.000.000

# Colunas do DataFrame

As colunas do DataFrame são:

P/L
P/VP
Yield
EV/EBIT
ROIC
Dívida Bruta / Patrimônio Líquido
Crescimento nos últimos 5 anos
Liquidez dos últimos 2 meses

# Requisitos
Python 3.11.4
Selenium
Pandas
Webdriver do Selenium (compatível com o navegador em uso)

# Referências
How to Use Selenium with Python
Fundamentus ("https://www.fundamentus.com.br/resultado.php")

# AVISO:

# Os resultados obtidos neste projeto não constituem recomendações de investimento. No entanto, podem servir como um ponto de partida útil para quem deseja estudar e entender melhor o mercado de ações. Este projeto é uma demonstração de como utilizar o Selenium e o Pandas para realizar a análise de indicadores fundamentalistas de ações.
