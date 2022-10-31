# Sugestão de Carteira de Investimento

Este código em python tem por objetivo fazer uma proposta de composição de carteira de investimento que sejam mais adequadas para os seguintes períodos:

· Investimentos de até 6 meses

· Investimentos de até 2 anos

· Investimentos de até 5 anos

[Apresentação](https://docs.google.com/presentation/d/1IP8UQWQCqIyyO-268HsZK2sBy7mZ0JsT/edit?usp=sharing&ouid=105469954340612395457&rtpof=true&sd=true)

## Pacotes utilizados

* [pyfolio](https://pyfolio.ml4trading.io/)
* [yfinance](https://acervolima.com/obtenha-dados-financeiros-do-yahoo-finance-com-python/)
* [sklearn-cluster](https://scikit-learn.org/stable/)
* [tkinter](https://docs.python.org/3/library/tkinter.html)
* [pandas]([pandas - Python Data Analysis Library (pydata.org)](https://pandas.pydata.org/))
* [matplotlib](https://matplotlib.org/stable/index.html)
* [request](https://realpython.com/python-requests/)

## Funções

- def montaFormulario(): Define o lay-out do formulário das questões
- def exibeLabel(): Define estilo do questionário no formulário
- def questionar(): Exibe as perguntas para categorização do perfil do investidos
- def confirmaPerfil(): Confirma as respostas informadas no questionário
- def buscaAtivos(): Define o repositório dos Ativos (yubb.com.br e fundamentos.com.br)
- def  buscaAtivosRendaFixa(): Busca os Ativos de Renda Fixa para o perfil identificado
- def buscaAtivosRendaVariavel(): Busca os Ativos de Renda Variável para o perfil identificado
- def sugestoesDeAtivos: Sugere Ativos de Renda Variável com base no perfil identificado
- def sugestaoAtivoRF(): Sugere Ativos de Renda Fixa
- def analiseExploratoriaRF(): Efetua análise descritiva/exploratória com os dados dos Ativos de Renda Fixa
- def analiseSugestao(): Disponibiliza dados e gráficos para basear a escolha
- def analiseSugestaoBovespa(): Compara desempenho dos últimos dois anos dos Ativos sugeridos com o Bovespa
- def analiseDiasMediaMovel(): Demonstra a média móvel em 21 e 200 dias dos Ativos sugeridos 
-  def confirmaEscolhaCarteira(): Possibilita a escolha dos Ativos sugeridos
- def exibeCarteira(): Exibe a carteira escolhida pelo investidor
