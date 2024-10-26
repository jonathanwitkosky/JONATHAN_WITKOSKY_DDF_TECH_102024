# JONATHAN_WITKOSKY_DDF_TECH_102024

Extração dos dados:

Foi utilizado o dataset "Online Retail" do Kaggle onde o dataset possui 541910 linhas em formato CSV

Modelagem dos dados:

o dataset foi modelado utilizando a linguagem Python, seguindo os princípios de Kimball, num modelo Star Schema para essa análise. A modelagem proposta ficou o seguinte:

![Modelagem](image.png)

Todo o passo a passo das transformações está no arquivo [onlineRetail](onlineRetail.ipynb) na seção "Transformações"

Análises:

Foram realizadas análises em SQL e posteriomente criado gráficos utilizando as bibliotecas Matplotlib e seaborn para criar a visualização dessas análises. Onde respondemos as seguintes perguntas:

- Análise de Receita por Produto

- Quais foram os produtos mais vendidos?
- Qual a receita gerada por produto ao longo do tempo?

- Análise de Cliente

- Quem são os clientes que mais gastam?
- Qual a frequência de compras de clientes específicos ao longo do tempo?

- Análise Temporal

- Quais são os meses ou trimestres com maior volume de vendas? 
*Em meses e Trimestres

- Análise Geográfica

- Quais países geram mais receita?
- Relação entre o país do cliente e os produtos

- Análise de pedidos

- Quantidade de pedidos cancelados
