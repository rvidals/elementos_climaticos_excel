# Geração de gráficos em planilhas excel de dados climáticos obtidos pela base de dados do INMET

Este projeto, desenvolvido em Jupyter Notebook, realiza uma análise simples dos dados climáticos da estação Brasília do Instituto Nacional de Meteorologia (INMET), com dados de 1961 a 2023. O objetivo principal é gerar gráficos e salvar os valores médios de precipitação, umidade, temperatura máxima e mínima em uma planilha Excel.

## Informações da Estação

<div align="center">

| Nome       | Codigo Estacao | Latitude     | Longitude     | Altitude | Situacao | Data Inicial |
|------------|----------------|--------------|---------------|----------|----------|--------------|
| BRASILIA   | 83377          | -15.78972221 | -47.92583332  | 1161.42  | Operante | 1961-09-11   |

</div>

Essa análise foi motivada pela atualização do Atlas do Distrito Federal, lançado em 2020 pela Companhia de Planejamento do Distrito Federal (Codeplan).

## Instalação

Para rodar este projeto, você precisa ter o Python instalado em sua máquina. Em seguida, instale as dependências necessárias:

```bash
pip install pandas xlsxwriter plotly
```

## Estrutura do Código

O código está estruturado em funções Python organizadas em um arquivo separado, chamado utilidades.py. Essas funções possuem regras de negócios específicas para o tratamento e análise dos dados climáticos.

Além disso, o script facilita a exportação dos dados processados para um arquivo Excel, organizando as informações de precipitação, umidade, temperatura máxima e mínima em abas separadas, juntamente com os gráficos gerados para cada variável.

## Bibliotecas Utilizadas

As bibliotecas usadas no desenvolvimento desse script são amplamente utilizadas na análise e ciência de dados, utilizando python: 

  - [os](https://docs.python.org/3/library/os.html)
  - [Pandas](https://pandas.pydata.org/)
  - [XlsxWriter](https://xlsxwriter.readthedocs.io/)
  - [Plotly](https://plotly.com/python/)

# Autor
Rogerio Vidal de Siqueira

<a href="https://www.linkedin.com/in/rogerio-vidal-de-siqueira-9478aa136/" target="_blank" rel="noopener noreferrer">Meu Linkdin</a>
