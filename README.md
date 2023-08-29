# Tempo Médio de Recompra - Retenção de Clientes
Projeto executado em Python, com objetivo de responder algumas perguntas de negócio de retenção de clientes da base de clientes de E-commerce.

# Estratégias usadas para Solução do Problema:
Passo 1: Importação de pacotes no Jupyter Notebook



Passo 2: Carregando dataset de vendas no Pandas ecom = pd.read_excel('dataset_tratado.xlsx')

Passo 3: Análise exploratória dos dados ecom.shape ecom.isnull().sum()

Passo 4: Limpeza dos dados 

Passo 5: Desconsiderando pedidos aonde foram cancelados 

Passo 6: Separando coluna da data da venda para colunas de data e hora 

Passo 7: Excluindo linhas duplicatas e mantendo apenas a primeira linha do dataset
*Pois a cada realização da compra de mais de um produto no dataset, o sistema de vendas cria uma linha adicional para cada produto sem o seu valor, assim apenas a primeira linha de pedido é que importa.

Passo 8: Excluindo linhas de vendas de upsell no dataset compras_upsell = []

Passo 9: Criando uma cópia do Dataset sem valores duplicados e de vendas de upsell

Passo 10: Calculando a quantidade clientes que realizaram a recompras no dataset

Passo 11: Calculando o tempo médio entre as recompras histórica 

Passo 12: Verificando estatísticas referente ao tempo médio entre as recompras histórica

Passo 13: Gráfico de tempo de relação entre recompra e quantidade de dias

FIM
