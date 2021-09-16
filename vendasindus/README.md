## Dashboard de vendas de uma industria metalmecânica

Este relatório no formato de dashboard tem como objetivo apresentar os principais indicadores de vendas de uma indústria de usinagem de precisão, na qual trabalhei como Analista em melhoria contínua.

Os nomes e demais dados confidenciais foram maquiados, as vendas e o faturamento foi mantido.

### Objetivo
____________
O objetivo de negócio que originou tal projeto foi a necessidade de renovação da empresa durante a pandemia, onde surgiu uma possibilidade da criação de joint-venture com nosso principal cliente.
A partir dessa necessidade criei esse relatório com o balanço de vendas realizadas de 2018 a 2021, dessa forma foi possível negociar com clareza a criação da nova empresa.

A escolha de se fazer o relatório no Power BI veio da premissa de termos algo prático e intuítivo, de fácil visualização e entendimento, para ser apresentado em reunião de negócios.

### Coleta dos dados
____________
Os dados foram adquiridos atráves do sistema ERP que utilizavamos na empresa, que no caso, fui responsável pela implementação e gerência.
Controlavamos quase todos os aspectos gerenciais da empresa pelo ERP, com certos controles feitos por Excel. Tratando dos pedidos dos clientes, estoque, produção e financeiro pelo sistema.
Assim, pode-se afirmar que tinhamos uma variedade de dados armazenados.

### Tratamento dos dados
____________
O tratamento dos dados em si, não foi trivial, pois da forma em que o sistema os exportava, como, dados sujos e cheios de vazios e nulidades.
Os dados foram tanto tratados no Excel e posteriormente no Power Query dentro do BI.

### Dashboard
____________
No  dashboard em si, que foi dividido em duas páginas - para melhor visualização - temos:

* Filtros para cada ano e mês, possibilitando uma análise mais criteriosa.

* Um gráfico de linha, mostrando o faturamento total em cada mês de 2018 a 2021. Podemos claramente ver a queda de faturamento devido a pandemia, já no início de 2020.

* Um gráfico de colunas, contendo o faturamento de cada produto, revelando a hierarquia de importância - lei de pareto - tanto do produto em si, como do cliente do produto.

* Um gráfico de barras, com o montante de vendas dos produtos, assim podemos ver claramente que nem sempre o que mais vende, é aquilo que nos traz maior retorno financeiro.

Já na segunda página do dashboard temos uma visão voltadas aos clientes, onde temos:

* Um filtro de seleção por cliente, onde podemos analisar a particularidade de cada um dentro do negócio.

* O faturamento total, que muda de acordo com a seleção do cliente.

* Uma 'tabela dinâmica' com os valores mais explícitos do faturamento, por cliente e ano.

* Um grafíco de colunas do faturamento por cliente, aqui realmente podemos inquirir a grandeza dos Johnson's para a empresa.

* Outro gráfico de colunas do faturamento anual, além de uma linha mostrando a quantidade de produtos vendidos em cada ano.

____________

### Neste caso, deixo apenas o link do Dashboard, por segurança extra com os dados - mesmo que modificados - sensíveis.

Link para o [Dashboard de Vendas Indústria](https://app.powerbi.com/view?r=eyJrIjoiMGUxMmEyMWItZmI4MS00ZGU2LWExZjQtMThkNzZmMzI5MmM2IiwidCI6ImIzNzA1YzRmLWRkODItNDNlNC1iZWMwLWJkMDA2ZGEwM2E1YyJ9)
