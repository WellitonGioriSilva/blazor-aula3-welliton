O `FormProduto` cuida apenas da entrada e validação dos dados do produto.
Ele não altera diretamente a lista porque essa lista pertence à página `Produtos`.
Quem adiciona o produto é o método `AdicionarProduto`, na própria página.
O formulário avisa que deve chamá-lo por meio do `EventCallback` `AoAdicionar`.
