Uma análise exploratória de dados realizada para entender e extrair insights do conjunto de dados fornecido, que consiste em informações relevantes sobre aluguéis temporários na cidade de Nova York. 
Este trabalho é parte de um projeto mais amplo, focando especialmente na estratégia de precificação.

A análise exploratória de dados é uma etapa fundamental para compreender a estrutura e os padrões subjacentes nos dados, visando extrair insights que possam orientar estratégias de negócio. Neste contexto, o objetivo é desenvolver um modelo de previsão de preços com base nos dados disponíveis. Para isso,além do modelo de previsão é importante responder às seguintes perguntas de negócio:

a.	Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, onde seria mais indicada a compra?

b.	O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?

c. Modelos para previsão do preço.

# Bibliotecas Utilizadas

Para realizar essa análise, foram utilizadas as seguintes bibliotecas em Python:

- Pandas: Para manipulação e análise de dados tabulares.

- Numpy: Para operações numéricas eficientes.

- Matplotlib.pyplot: Para visualização de dados e criação de gráficos.

- Seaborn: Para aprimorar a visualização e interpretação dos padrões nos dados.

- Scipy.stats: Para análises estatísticas adicionais, se necessário.

- Statsmodels: Para a construção e avaliação de modelos preditivos.

  Base de Dados

O conjunto de dados da cidade de Nova York contém informações sobre listagens do Airbnb na cidade de Nova York.

### 4.1 - Dicionário dos dados

A base de dados de treinamento contém 16 colunas e pode ser encontrada no arquivo: "teste_indicium_precificacao.csv".

Logo abaixo está a lista e descrição das variáveis:

id – Atua como uma chave exclusiva para cada anúncio nos dados do aplicativo

nome - Representa o nome do anúncio

host_id - Representa o id do usuário que hospedou o anúncio

host_name – Contém o nome do usuário que hospedou o anúncio

bairro_group - Contém o nome do bairro onde o anúncio está localizado

bairro - Contém o nome da área onde o anúncio está localizado

latitude - Contém a latitude do local

longitude - Contém a longitude do local

room_type – Contém o tipo de espaço de cada anúncio

price - Contém o preço por noite em dólares listado pelo anfitrião

minimo_noites - Contém o número mínimo de noites que o usuário deve reservar

numero_de_reviews - Contém o número de comentários dados a cada listagem

ultima_review - Contém a data da última revisão dada à listagem

reviews_por_mes - Contém o número de avaliações fornecidas por mês

calculado_host_listings_count - Contém a quantidade de listagem por host

disponibilidade_365 - Contém o número de dias em que o anúncio está disponível para reserva
