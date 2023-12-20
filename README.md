# forecast_of_the_value_of_Petrobras_shares
Trata-se de um projeto de análise dos dados e predição de valores das ações da Petrobrás em determinado período de tempo.

### Instalação

Este projeto requer **Python 3.7** e as seguintes bibliotecas Python instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)
- [plotly]
- [datetime]
- [yfinance]



Você também precisará ter software instalado para rodar e executar um [iPython Notebook](http://ipython.org/notebook.html)

### Código

O código é fornecido no arquivo notebook `Projeto_de_dados_de_finanças_Petrobras.ipynb`.  

### Execução

Em um terminal ou janela de comando, navegue até o diretório raiz de projeto 'Projeto_de_dados_de_finanças_Petrobras.ipynb.ipynb'/` (que contém este README) e execute os seguintes comandos:

```bash
ipython notebook Projeto_de_dados_de_finanças_Petrobras.ipynb.ipynb
```  
ou
```bash
jupyter notebook Projeto_de_dados_de_finanças_Petrobras.ipynb.ipynb
```

Isso abrirá o o software e arquivo de projeto iPython Notebook em seu navegador.

### Dados

O conjunto de dados é um dataset oriundo da plataforma do Yahoo por meio da biblioteca yfinance sendo que o dataset possui sete colunas, sendo que a coluna data também é a coluna de índice.

**Atributos**

As colunas referem-se aos preços das ações na abertura, alta, baixa, fechamento, fechamento ajustado e volume.


**Objetivo**
- Neste projeto de dados, faremos uma análise técnica acerca do comportamento das ações da Petrobrás em determinado intervalo de tempo.
Assim, num primerio momento, nos concentraremos na análise de dados exploratória dos preços das ações da Petrobrás ao longo do tempo (desde 01/01/2020 até 18/12/2023). Serão abordados temas como a evoução dos preços ao longo do tempo, taxa de retorno, etc.
Após, faremos previsões de preço com o uso de rede neurais recorrentes.
Linguagem: Python.
Principais bibliotecas utilizadas: Pandas, Numpy, Matplotlib, Seaborn e PyTorch.
Obs. Este projeto foi realizado a partir de uma adaptação de projetos dos cursos Python para Data Science e Machine Learning (Udemy), Python para Finanças: Análise de Dados e Machine Learning (IA Expert Academy) e Deep Learning de A a Z com PyTorch e Python (IA Expert Academy).
