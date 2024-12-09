# Dio.me---Suzano---An-lise-de-Dados-com-Power-BI
Publicar os desafios de Projetos do curso Suzano - Análise de Dados com Power BI, ofertado pela DIO.

Nesse primeiro projeto foi criado um Modelo Entidade-Relacionamento Extendido para um E-Commerce.

Foi criado uma entidade "Cliente" que permite que seja cadastrado Cartões de Crédito e Débito. Também foi criado duas especializações para "Cliente": "ClientePF" e "ClientePJ".

O E-Commerce tem dois tipos de colaboradores: "Fornecedores" que fornecem produtos para serem vendidos na plataforma e "Terceiro-vendedor" que pode usar a plataforma
para vender seus próprios produtos mediante uma comissão quando realizam uma venda.

O E-commerce tem vários "Estoque" que tem como atributos o endereço do estoque (necessário para o cálculo do frete) e a localização do produto dentro do estoque, para que seja possível seu rápido envio para o consumidor.

Cada "Produto" tem sua categoria e descrição.

A entidade com mais atributos é "Pedido": StatusDoPedido: indicando se o produto já foi pago, se está a caminho, etc.
                                          Frete: exibe o valor do frete.
                                          FormaDePagamento: escolher entre cartão de crédito, cartão de débito, boleto e pix.
                                          DataDaCompra: indica quando o pedido foi feito.
                                          DataDeConfirmaçãoDoPgto: indica quando o pagamento foi realizado.
                                          DataDePrevisãoDaEntrega: previsão de data de entrega do(s) produto(s) ao cliente.
                                          DataDaEntrega: Data em que o(s) produto(s) foram efetivamente entreges.
                                          DiasParaDevolução: Quantos dias, a partir da DataDaEntrega, o cliente tem o direito de devolver o(s) produto(s) e serem ressarcidos.
                                          ValorTotalDaCompra: A soma dos valores dos produtos + Frete.
                                          CódigoDeRastreamento: Código para que o cliente possa acompanhar seu pedido pelo site da transportadora.![ModeloEER - ECommerce](https://github.com/user-attachments/assets/2f0be0f2-6e26-4463-afb4-f5871d91ce56)
