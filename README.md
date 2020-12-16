# php-store
Trabalho trimestral de programação web.

* BD com usuários, produtos, etc... (com SGBD MySQL) </br>
* Sistema de login, caixa de busca, menu de categorias de produtos (pelo menos 2 categorias cadastradas em banco) e listagem inicial de produtos em destaque (pode ter um campo 'destaque' na tabela ou usar outro critério à sua escolha)</br>
* Tela de cadastro de usuário</br>
* Fale conosco (formulário de contato, deve enviar e-mail via PHP)</br>
* Tela específica para detalhar apenas 1 produto clicado (deve funcionar para todos produtos dinamicamente, apenas 1 PHP para todos). Deve possuir um botão de compra que manda para a tela do carrinho.</br>
* Tela do carrinho de compras. Ao finalizar a compra, mande um e-mail para o usuário com o "recibo" da compra e limpe o carrinho. O carrinho deve permitir mudar a quantidade de cada produto e também removê-los. O valor total da compra também deve ser mostrado e atualizado conforme as quantidades forem alteradas. Use $_SESSION para fazer o carrinho (quando compra um produto, adiciona um item ao session com id e quantidade).</br>
