# projeto2-aind109
Projeto 2 do Nanodegree de Fundamentos de AI &amp; Machine Learning.
# Conteúdo: Modelo de avaliação e validação
## Projeto: Prevendo o preço de imóveis de Boston

## Visão geral do projeto
Neste projeto, você aplicará conceitos básicos de Machine Learning em dados coletados de preços de casas em Boston, em Massachusetts, para prever o preço de venda de uma casa nova. Primeiro, você irá explorar os dados para obter atributos importantes  e estatísticas descritivas sobre o conjunto de dados. Depois, dividirá adequadamente os dados entre dois subconjuntos, o de testes e o de treinamento, e determinará uma métrica adequada para esse problema. Você, então, analisará o desempenho de um algoritmo de aprendizagem com parâmetros variados e tamanho do conjunto de treinamento. Isso permitirá que você escolha o modelo ótimo que melhor generaliza os dados desconhecidos. Por último, você testará o modelo ótimo em uma nova amostra e comparará os preços de venda previstos com as suas estatísticas.

## Destaques do projeto
Este projeto foi projetado para que você se familiarize em trabalhar com conjuntos de dados em Python e aplicar técnicas básicas de Machine Learning utilizando NumPy e Scikit-Learn. Antes de saber usar muitos dos algoritmos disponíveis na biblioteca sklearn, será de grande ajuda, primeiro, praticar análise e interpretação do desempenho de seu modelo.

O que você aprenderá ao concluir este projeto:

- Como utilizar o NumPy para investigar os features latentes de um conjunto de dados.
- Como analisar vários gráficos de desempenho de aprendizagem para variância e viés.
- Como determinar o modelo que faz as melhores estimativas para dados desconhecidos.
- Como avaliar o desempenho do modelo em dados desconhecidos utilizando dados anteriores.

## Descrição
O mercado imobiliário de Boston é altamente competitivo e você quer ser o melhor corretor de imóveis da região. Para competir com seus colegas, você decidiu elencar alguns conceitos básicos de Machine Learning para ajudar você e seu cliente a acharem o melhor preço de venda para a casa dele. Com sorte, você se deparou com o conjunto de dados de habitação de Boston, que contém dados agregados de várias características para casas das comunidades da Grande Boston, incluindo o valor médio das casas para cada uma das regiões. Sua tarefa é construir um modelo ótimo baseado na análise das estatísticas com as ferramentas disponíveis. Esse modelo será, então, usado para estimar o melhor preço de venda para a casa de seus clientes.

## Software e bibliotecas
Este projeto usará o seguinte software e bibliotecas de Python:

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
- [Jupyter Notebook](http://ipython.org/notebook.html)

Caso você não tenha o Python instalado ainda, é altamente recomendado que instale a distribuição [Anaconda](http://continuum.io/downloads) de Python, que já tem os pacotes acima inclusos, além de outros. Certifique-se de que você selecionou o instalador do Python 2.7, e não o instalador do Python 3.x.

## Começando o projeto
Para essa tarefa, você encontrará o arquivo `boston_housing.zip`, que contém os arquivos necessários do projeto para download na seção Recursos. *Você também pode visitar nosso [GitHub de projetos de Machine Learning](https://github.com/udacity/br-machine-learning) para ter acesso a todos os projetos disponíveis para este Nanodegree.*

Este projeto contém três arquivos:

- `boston_housing_PT.ipynb`: esse é o arquivo principal, em que você irá executar seu projeto.
- `housing.csv`: o conjunto de dados do projeto. Você vai carregar esses dados no Notebook.
- `visuals.py`: esse script de Python contém funções auxiliares que criarão as visualizações necessárias.

No Terminal ou no prompt de comando, navegue até a pasta que contém os arquivos do projeto e, então, utilize o comando `jupyter notebook boston_housing_PT.ipynb` para abrir uma nova janela ou aba do navegador para trabalhar com seu Notebook. Outra alternativa é utilizar o comando `jupyter notebook` ou `ipython notebook` e navegar até o arquivo do Notebook na janela do navegador que se abrir. Siga as instruções no Notebook e responda a cada uma das perguntas apresentadas para concluir o projeto com sucesso. O arquivo **README** também foi incluído e contém informações necessárias adicionais ou instruções para o projeto.
