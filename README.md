# Análise de dados financeiros e de crédito bancário
## Esse projeto tem como objetivo analisar e investigar dados financeiros de um banco fictício, para fazer recomendações de acordo com os insights gerados.

Esse dataset é **totalmente fictício**, tirado do site [kaggle](https://www.kaggle.com/). Os dados foram gerados de forma aleatória, tornando a análise e a geração de insights menos consistente, também possuindo alguns outliers e dados faltosos, onde foram devidamente tratados. 
O dataset possui informações sobre clientes e cartões de uma instituição bancária abrangendo a década de 2010.

## Estrutura do Dataset
Esse dataset consiste em duas tabelas com as informações dos clientes e dos cartões pertencentes aos clientes.

<img width="560" alt="image" src="https://github.com/user-attachments/assets/d908adfb-e301-4f9c-bcef-0d59794edf82">

## Insights
#### Para analisar os dados bancários de comportamento financeiro, nós focamos nas seguintes métricas:
- **Análise Demográfica e de Comportamento Financeiro**: avalia o perfil demográfico (idade, renda) e comportamento financeiro (endividamento) dos clientes.
- **Análise de Carteira de Crédito e Gênero**: examina a carteira de crédito (bandeiras de cartão, limites), disparidades de gênero e padrões de renovação.

#### Análise Demográfica e de Comportamento Financeiro
- 78% dos clientes tem menos de 60 anos de idade.
- 80% dos clientes estão na faixa que ganham em média entre $20 mil e $60 mil anuais.
- Clientes a partir de 60 anos têm o menor salário médio anual (~ $40 mil).
- O endividamento dos clientes cresce dos 18 aos 50 anos, apresenta um leve declínio a partir dos 51 anos, e cai significativamente após os 60 anos.
  
#### Análise de Carteira de Crédito e Gênero
- Mastercard (52.21%) e Visa (37.85%) dominam a base de clientes, com ambos possuindo limites médios de crédito mais altos (~ $14 mil).
- Amex (6.54%) e Discover (3.40%) possuem a menor parcela dos clientes, com também os menores limites ($11 mil e $10 mil), respectivamente.
- 82% dos cartões possuem data de vencimento a partir do ano de 2020.
- 51% dos clientes são do gênero feminino. Também possuem um limite de crédito médio ligeiramente maior que os clientes do gênero masculino (~ $80).

## Recomendações
- **Segmentação por Idade e Perfil Financeiro**: para clientes com idade inferior a 60 anos, oferecer produtos de crédito com prazos mais longos e taxas mais competitivas, como empréstimos para casa própria ou investimentos. Também é interessante promover mais serviços digitais para engajar o público que tende a ter mais facilidade a se adaptar à tecnologia; para clientes com a idade superior a 60 anos, é interessante desenvolver produtos focados na aposentadoria, previdência privada, seguros de vida, etc. Criar pacotes de serviços com menores taxas, considerando que essa faixa etária possui uma renda menor que as demais.
- **Gestão do Endividamento por Faixa Etária**: para os clientes da faixa de 18 até 50 anos (alta utilização de crédito), oferecer linhas de crédito com limites mais parelhos à renda, para evitar sobre-endividamento, criação de programas de educação financeira para esse público, como gestão de dívidas; para os clientes com a idade superior a 50 anos, focar na renegociação de dívidas para os clientes com histórico de pagamentos; já para os clientes a cima de 60 anos, a queda de endividamento faz sentido, provavelmente pelo tempo de pagamento das dívidas, aposentadorias, entre outros fatores, a criação e mudança de estratégia para oferecer crédito para essa faixa de idade, para mante-los engajados ao banco é interessante. 
- **Estratégias para a Maioria dos Clientes**: contas digitais sem tarifa para os clientes que ganham até $60 mil, oferecer empréstimos com taxas diferenciadas, pacotes de serviços com descontos, assim aumentado a fidelização desse público.
- **Estratégia por Bandeira do Cartão**: para Mastercard/Visa, como representam aproximadamente 90% dos clientes, é interessante oferecer benefícios exclusivos para clientes com altos limites e bom histórico de pagamento; para os clientes Amex/Discover, oferecer limites progressivos, para os clientes com bom comportamento de crédito, e incentivar a migração para as outras bandeiras, com algum tipo de oferta bônus, como, por exemplo, milhas aéreas.
- **Renovação de Cartões e Engajamento**: oferecer renovação automática com benefícios para os clientes com cartões próximos à data de vencimento, para os clientes com cartões vencidos antes de 2020, entrar em contato para reativa-los com ofertas personalizadas. É interessante também revisar os limites de crédito durante a renovação, de acordo com o comportamento do cliente, para evitar endividamentos.

## Dashboard
O dashboard pode ser achado no Power BI Web neste [link](https://app.powerbi.com/view?r=eyJrIjoiZTNmMmJkNGQtMWZjYi00NjNiLThmOGUtMTgxOWY4ZTg4MDJhIiwidCI6ImQwYzY5OGQ0LWU0ZWEtNGVlOS1hNzlkLWYyZDdhNzgzOTljOCJ9). O dashboard permite usuários de filtrar, analisar tendencias, valores e métricas nos dados apresentados.

<img width="850" alt="image" src="https://github.com/user-attachments/assets/04a41ef5-89b0-4ea2-a962-bb27a05ef2c6">



