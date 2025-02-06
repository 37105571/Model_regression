# Model_regression

#Premissa:
Uma empresa está investindo mensalmente em plataformas de publicidade online, como Youtube, Facebook e Newspaper, para a prospecção de leads. A fim de acompanhar o desempenho desses investimentos, a empresa registra todos os gastos com publicidade, todos os retornos de vendas gerados a partir desses investimentos e estimar um retorno de vendas a partir de um valor x de investimento.

#Etapas de desenvolvimento:
•	Análise Descritiva.
•	Análise Exploratória.
•	Moldagem.
•	Calculo de Predição.

#Descrição:
Ao início foi necessário a importação das bibliotecas: Pandas, Seaborn e Sklearn. Durante a Análise Descritiva, utilize funções como: head (), info () e describe (), para analisar como está distribuído o dataset. Durante a etapa de Análise Exploratória, utilize funções como: sns.pairplot (), data.corr () e sns.heatmap (), para análise das variáveis, identificar relações e padrões relevantes entre elas e o que será fundamental para a modelagem da análise que no casso foi definir as variáveis x e y, treinando e testando utilizando a função: model = LinearRegression (), para identificar ajustes necessários, assegurando previsões precisas solicitadas pela empresa. E por fim, o cálculo do coeficiente de determinação (r²), para realizar previsões quantitativas sobre o retorno de vendas, com base em ‘x’ investimentos em publicidade.
