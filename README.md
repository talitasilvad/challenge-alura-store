# Challenge Alura Store
### 📊 Desafio Alura Store: Análise Estratégica de Vendas

### 📝 Sobre o Projeto

Projeto realizado durante o programa ONE(Oracle Next Education) em parceria com a Alura. O objetivo principal foi atuar como um Analista de Dados para auxiliar o proprietário da rede fictícia Alura Store em uma tomada de decisão estratégica baseada em dados.

O desafio consistiu em limpar, processar e analisar dados de vendas de 4 lojas diferentes para identificar padrões, ineficiências e oportunidades.

### 💼 O Problema de Negócio

O Sr. João, dono da rede, precisa vender uma de suas filiais para investir em um novo empreendimento. Ele solicitou uma análise detalhada para identificar a loja com menor eficiência e apresentar uma recomendação final baseada nos dados.

### 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido inteiramente em Python utilizando o Google Colab. As principais bibliotecas utilizadas foram:

Pandas: Para manipulação, limpeza e agregação dos dados.

Matplotlib e Seaborn: Para criação de visualizações estáticas e análises estatísticas gráficas.

### 📂 Estrutura dos Dados

A base de dados consistia em 4 arquivos .csv (um para cada loja), contendo informações importantes como:

Loja: Identificação da unidade.

Produto: Nome do item vendido.

Categoria do Produto: Classificação (Livros, Eletrodomésticos, etc.).

Preço: Valor da venda.

Frete: Custo de envio.

Avaliação da compra: Nota dada pelo cliente (1 a 5).

### 🔍 Metodologia e Análises Realizadas

Tratamento de Dados:

Unificação dos 4 arquivos em um único DataFrame.

Análise Exploratória

Cálculo de faturamento total por loja.

Identificação das categorias e produtos mais vendidos

Investigação de Outliers (Logística)

Identificação de distorções na média de frete.

Uso de Boxplots para descobrir que vendas de TVs 4K estavam elevando artificialmente a média de frete da Loja 1.

### 📊 Principais Insights e Visualizações

Durante a análise, foram gerados gráficos para suportar a decisão.

Gráfico de Barras: Demonstrou que a Loja 1 lidera o faturamento, enquanto a Loja 4 tem o pior desempenho financeiro.

Gráfico de Pizza: Revelou que Móveis representam 20.0% do volume de vendas da rede em seguinda de Eletrônicos com 18.8%.

Scatter Plot (Dispersão): Comprovou a correlação entre produtos de alto ticket (TVs) e fretes elevados (acima de R$ 200), isolando os outliers.

Boxplot: Evidenciou que as Lojas 1 e 4 possuem as avaliações mais baixas e inconsistentes.

### 🚀 Conclusão e Recomendação

Com base nos dados, a recomendação final ao Sr. João foi a VENDA DA LOJA 4.

Justificativa:
A Loja 4 apresenta um cenário de ineficiência dupla:

Menor Faturamento: É a unidade que compara às outras, é a que menos gera dinheiro.

Baixa Satisfação: Possui índices de avaliação ruins, detraindo a marca.

Nota Estratégica: A Loja 1, apesar de também ter avaliações ruins e custos logísticos altos, é a líder de receita e deve passar por reestruturação, não venda. A Loja 1 apresenta o maior faturamento acumulado da rede, aproximadamente **R\$ 1.53 mi**, se consolidando como a principal fonte de receita, já a Loja 4, possui o pior desempenho financeiro, aproximadamente **R$ 1.38 mi**, com uma diferença significaiva de quase **R$ 150.000,00** a menos que a líder.

