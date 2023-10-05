# Tratamento de Dados (Data Cleaning and Data Wrangling) para análise e modelagem
## Contexto ##
Uma empresa do ramo de e-commerce contratou você para levantar os indicadores de
recência, frequência e ticket médio (RFM) dos seus clientes.
* A saber RFM:
* R (Recency): Tempo que o cliente realizou a última compra (em dias)
* F (Frequency): Quantidade de compras realizadas pelo cliente
* M (Monetary): Valor do ticket médio gasto pelo cliente
onde ticket médio = média do total gasto por pedido para cada cliente.
para isso utilizei uma base de dados (arquivo csv) e construi um
código em Python que gera um output também csv.

  ## Sobre os dados ##

| Coluna | Descrição  |
| ------- | -------- |
| CustomerID | Código de identificação do cliente|
| Description | Descrição do Produto |
| InvoiceNo | Código da Fatura |
| StockCode | Código de Estoque do Produto |
| Quantity | Quantidade do produto |
| InvoiceDate | Data de Faturamento (Compra) |
| UnitPrice | Preço unitário do Produto |
