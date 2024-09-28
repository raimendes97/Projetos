# Projeto de Análise de Vendas

## Descrição

Este projeto é uma análise de dados de vendas de uma empresa que atua em diversas regiões. O objetivo é extrair, tratar e apresentar informações relevantes das vendas e devoluções, organizadas em tabelas e, por fim, em um gráfico de barras criado no Python.

## Estrutura do Projeto

- **Importação de Bibliotecas**: As bibliotecas `os` e `pandas` são usadas para manipulação de arquivos e dados, enquanto `plotly.express` é utilizado para a visualização gráfica.
- **Leitura dos Arquivos de Vendas**: Leitura dos arquivos de vendas de diferentes regiões e consolidação em um único DataFrame.
- **Análise de Produtos Vendidos**: Agrupamento dos dados por produto para analisar a quantidade vendida.
- **Cálculo de Faturamento**: Cálculo do faturamento total de cada produto multiplicando a quantidade vendida pelo preço unitário.
- **Análise por Loja**: Agrupamento dos dados por loja para calcular o faturamento total de cada uma.
- **Visualização Gráfica**: Criação de um gráfico de barras para visualizar o faturamento por loja.

