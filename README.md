# Geração de gráficos em planilhas excel de dados climáticos obtidos pela base de dados do INMET

Esse projeto, em jupyter notebook, traz uma análise de dados simples no intuito de gerar e salvar gráficos dos valores médios de precipitação, umidade e temperatura (max e min) para a estação Brasília do Instituto Nacional de Meteriologia (INMET) presente no Distrito Federal, para os anos de 1961 a 2023.

<div align="center">

| Nome       | Codigo Estacao | Latitude     | Longitude     | Altitude | Situacao | Data Inicial |
|------------|----------------|--------------|---------------|----------|----------|--------------|
| BRASILIA   | 83377          | -15.78972221 | -47.92583332  | 1161.42  | Operante | 1961-09-11   |

</div>

Essa motivação se deu a partir da atualização do Atlas do Distrito Federal que foi alançado em 2020 pela Companhia de Planejamento do Distrito Federal - Codeplan

O código está estruturado em algumas funções que possuem regras de negócios específicas para o tratamento dos dados. Essas funções estão separadas no jupyter notebook em um arquivo python denominado utilidades. 

Um outro ponto importante no código é a praticidade de salvar os os dados processados (precipitação, umidade, temperatura max e min) em abas separadas no excel juntamente com seus gráficos. 

As bibliotecas usadas no desenvolvimento desse script são amplamente utilizadas na análise e ciência de dados, utilizando python: 

  - [os](https://docs.python.org/3/library/os.html)
  - [Pandas](https://pandas.pydata.org/)
  - [XlsxWriter](https://xlsxwriter.readthedocs.io/)
  - [Plotly](https://plotly.com/python/)

# Autor
Rogerio Vidal de Siqueira

<a href="https://www.linkedin.com/in/rogerio-vidal-de-siqueira-9478aa136/" target="_blank" rel="noopener noreferrer">Meu Linkdin</a>
