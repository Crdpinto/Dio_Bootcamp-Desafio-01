Tabelas:<br><br>
<b>1.	Terceiro-Vendedor:</b><br>
Colunas: idTerceiro-Vendedor (INT), Razão Social (VARCHAR(45)), Local (VARCHAR(45))

<b>2.	Produtos por vendedor (terceiro):</b><br>
Colunas: Terceiro-Vendedor_idTerceiro-Vendedor (INT), Produto_idProduto (INT), Quantidade (INT)

<b>3.	Fornecedor:</b><br>
Colunas: idFornecedor (INT), Razão Social (VARCHAR(45)), CNPJ (VARCHAR(45))

<b>4.	Disponibilizando um Produto:</b><br>
Colunas: Fornecedor_idFornecedor (INT), Produto_idProduto (INT)

<b>5.	Estoque:</b><br>
Colunas: idEstoque (INT), Local (VARCHAR(45))

<b>6.	Produto_has_Estoque:</b><br>
Colunas: Produto_idProduto (INT), Estoque_idEstoque (INT), Quantidade (INT)

<b>7.	Produto:</b><br>
Colunas: idProduto (INT), Categoria (VARCHAR(45)), Nome do Produto (VARCHAR(45)), Descrição (VARCHAR(45)), Valor (VARCHAR(45))

<b>8.	Relação Produto/Pedido:</b><br>
Colunas: Produto_idProduto (INT), Pedido_idPedido (INT), Quantidade (INT)

<b>9.	Pedido:</b><br>
Colunas: idPedido (INT), Status do Pedido (VARCHAR(45)), Descrição (VARCHAR(45)), Cliente_idCliente (INT), Frete (FLOAT), Valor Total (FLOAT), Status (VARCHAR(45))

<b>10.	Entrega:</b><br>
Colunas: idEntrega (INT), Código de Rastreio (VARCHAR(45)), Status da Entrega (VARCHAR(45)), Pedido_idPedido (INT), Pedido_Cliente_idCliente (INT)

<b>11.	Cliente:</b><br>
Colunas: idCliente (INT), Nome (VARCHAR(45)), Identificação (VARCHAR(45)), CPF_CNPJ (BIGINT(14)), Endereço (VARCHAR(45)), Telefone (VARCHAR(45)), E-mail (VARCHAR(45))

<b>12.	Formas de Pagamento:</b><br>
Colunas: idFormas_Pagamento (INT), Boleto (VARCHAR(45)), Cartão (VARCHAR(45)), Pix (VARCHAR(45))

<b>13.	Cliente_has_Formas_Pagamento:</b><br>
Colunas: Cliente_idCliente (INT), Formas_Pagamento_idFormas_Pagamento (INT)

<b>14.	Cartão de Crédito:</b><br>
Colunas: idCartão_de_Crédito (INT), Número do Cartão (BIGINT(16)), Nome no Cartão (VARCHAR(45)), Validade (VARCHAR(45))

<b>15.	Cartão de Crédito_has_Formas_Pagamento:</b><br>
Colunas: Cartão_de_Crédito_idCartão_de_Crédito (INT), Formas_Pagamento_idFormas_Pagamento (INT)


![e-commerce](https://github.com/user-attachments/assets/377262aa-09d0-4d4c-acd3-98b6aea2e4f7)
