# Momentum Trading Project

Este repositório contém um notebook Python utilizado em uma aula da Udacity sobre momentum trading. O objetivo deste projeto é implementar e testar uma estratégia de trading baseada em momentum, utilizando dados históricos de fechamento ajustado de ações do S&P 500.

## Descrição

Neste projeto, você irá:

1. **Carregar e visualizar dados de mercado**
2. **Reamostrar preços ajustados**
3. **Calcular retornos logarítmicos**
4. **Deslocar retornos no tempo**
5. **Gerar sinais de trading**
6. **Calcular retornos projetados do portfólio**
7. **Realizar testes estatísticos**

## Estrutura do Projeto

- `project_1_trading_with_momentum.ipynb`: Notebook principal com a implementação passo a passo do projeto.
- `requirements.txt`: Lista de dependências necessárias para executar o notebook.
- `data/`: Diretório contendo os dados de mercado utilizados no projeto.

## Dependências

As principais bibliotecas utilizadas neste projeto incluem:

- Pandas
- Numpy
- Scipy
- Matplotlib
- helper (módulo personalizado)
- project_helper (módulo personalizado)
- project_tests (módulo personalizado)

Para instalar as dependências, execute o seguinte comando:

```bash
!{sys.executable} -m pip install -r requirements.txt
