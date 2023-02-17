# dataframe-assignment
Files required to complete the dataframe assignment

# assignment-intro
As questões a seguir devem ser entregues em um repositório do github contendo, para cada questão, uma pasta com a respectiva solução em .js, além do resultado exportado como .csv.

A ideia não é subir tudo de uma vez. Faça um commit por exercício realizado.

No final, responda esse tópico com o link do repositório.

# questions
- 1.0 - Quantos pedidos foram feitos por cada cliente?
Obs: Nesse primeiro exercício a ideia é aprender a usar o groupBy e o select, não sendo necessário os nomes dos clientes. Entregue somente um dataframe com duas colunas: cliente (id do cliente) e pedidos (número de pedidos).

- 1.1 - Agora, faça o mesmo exercício anterior, mas incluindo o nome do cliente. 
Obs: para fazer esta operação, você precisará fazer um join entre o dataframe que você encontrou no exercício anterior e o dataframe de clientes. Para isso, você precisará de uma chave que ligue os dois dataframes entre si. Abra as duas tabelas e procure por uma coluna que possua valores presentes nas duas tabelas. Essa coluna é a chave que você precisa para fazer o join.

- 1.2 Por fim, ordene o dataframe que você encontrou no exercício anterior pelo número de pedidos, do maior para o menor. Assim, teremos uma lista de clientes onde o primeiro cliente é o que mais fez pedidos. Utilize o método orderBy.

- 2.0 - Quantos pedidos foram feitos por cada vendedor? Indique o nome dos  vendedores.

- 2.1 - Ordene o dataframe que você encontrou no exercício anterior pelo número de pedidos, do maior para o menor. Assim, teremos uma lista de vendedores onde o primeiro vendedor é o que mais fez pedidos. Utilize o método orderBy.

- 3.0 - Faça um ranking com os produtos mais vendidos, do mais vendido para o menos vendido. Indique o nome do produto e quantas vendas foram feitas.
PS: não se esqueça de que um pedido pode conter uma quantidade de produtos diferente de 1.

- 3.1 - Agora, com o ranking que você fez no exercício anterior, adicione uma coluna chamada "valor" que indique o valor total que o produto gerou em vendas. Qual o produto mais vendido?

- 3.2 Agora, com base no resultado do exercício anterior, reordene o ranking pelo valor total de vendas, do maior para o menor. Utilize o método orderBy. Qual o produto mais rentável? (O que gerou mais dinheiro para a empresa?) Qual o produto menos rentável? (O que gerou menos dinheiro para a empresa?)

- 3.3 Com base no produto mais vendido, qual o cliente que mais comprou esse produto? Indique o nome do cliente e quantas vezes ele comprou o produto.

- 3.4 Com base no produto mais vendido, qual o vendedor que mais vendeu esse produto? Indique o nome do vendedor e quantas vezes ele vendeu o produto.

- 4.0 - Qual o cliente que mais gastou? Indique o nome do cliente e o valor total gasto.

- 4.1 - Qual o vendedor que mais vendeu? Indique o nome do vendedor e o valor total de vendas.

- 5.0 - Qual o cliente que mais gastou em um único pedido? Indique o nome do cliente e o valor gasto.

- 5.1 - Qual o vendedor que mais vendeu em um único pedido? Indique o nome do vendedor e o valor gasto.

- 6.0 - Qual o país que mais comprou? Indique o nome do país, a quantidade total de pedidos e o valor total de vendas.

- 7.0 - Qual o produto mais comprado por país? Indique o nome do produto, o nome do país e a quantidade comprada, além do valor total de vendas.

- 8.0 - Faça um ranking de valor de vendas por ano. Indique o ano e o valor total de vendas.

- 8.1 - Faça um relação de valor de vendas por mês e ano. Indique o ano, o mês e o valor total de vendas.

- 9.0 - Faça uma tabela que indique a média da quantidade de produtos vendidos por vendedor por ano. Indique o nome do vendedor, o ano e a média de produtos vendidos.

- 9.1 - Faça uma tabela que indique a média da quantidade de produtos vendidos por vendedor por mês e ano. Indique o nome do vendedor, o ano, o mês e a média de produtos vendidos.

- 9.2 - Com base na tabelas anterior, indique cinco vendedores que devem ser demitidos por terem as cinco menores médias de vendas, por ano.

- 10.0 - Faça um ranking com os cinco clientes de cada país que mais gastaram em compras por ano. Indique o ano, o país, o nome do comprador e o valor gasto.
