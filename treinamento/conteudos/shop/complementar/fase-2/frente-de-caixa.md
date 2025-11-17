# Frente de caixa

<details>

<summary>ECF - ANTES DE ABRIR!</summary>

* **Toda abertura** de Caixa gera um **turno diferente** se reaberto no mesmo dia. Então sempre que o Caixa for aberto pela primeira vez, o turno será identificado como Turno 1, quando for aberto pela segunda vez no mesmo dia, será Turno 2 e assim sucessivamente.
* **Atendente do caixa:** Se o caixa for aberto por um atendente, não é possível trocar, apenas se fechar o turno.

</details>

<details>

<summary><mark style="color:red;">*</mark> VENDAS</summary>

1. O ECF é onde você **efetiva as Vendas**, ou seja, **realiza a impressão do cupom fiscal**. Mas você também tem a opção de criar uma venda direto daqui ou pegar uma das pré-vendas para efetivar.
   * ​​​​​​​Salvo algumas exceções que devem ser realizadas no pré-vendas:
     * Venda de entrega.
2. Aqui também tem a tecla **F1** para ver os **principais atalhos**. Caso tenha esquecido algum comando, você poderá consultar aqui.
3. **Pesquisa por código interno:** ao digitar algum número no campo **Código** o sistema de frente de caixa identifica como o **número da pré-venda**. Caso precise buscar pelo **código interno do produto** é necessário utilizar a tecla **F3 antes de digitar** o número, assim o sistema altera a busca para código interno.
   * <mark style="color:blue;">Só é possível excluir item do grid se for lançado direto no ECF, item de pré-venda não é possível excluir.</mark>
4. Ao teclar **F12** para carregar uma pré-venda, na parte de cima são as pré-vendas e a abaixo são os itens da pré-venda selecionada.
5. Aqui também é possível cancelar a pré-venda antes de efetivá-la em caso de desistência do cliente. Basta marcar na coluna **Selec** e teclar **F10**. O sistema solicitará a senha para confirmação para cancelar.
6. Para **efetivar a pré-venda**, basta selecionar a pré-venda, teclar **Enter** uma vez que será carregado primeiro o código da pré-venda (se você já souber o código da pré-venda, já pode digitar direto) e na segunda vez os itens da venda serão carregados.
7. Com os itens em tela, ao teclar **Enter** novamente, a forma de pagamento e o atendente já serão carregados na tela de fechamento.
8. O campo **À Vista** é para o caso o cliente queira dar uma parte em dinheiro em caso de venda de cartão, convênio ou cheque.
9. O **número do documento** é o número do comprovante da maquininha do cartão, caso você queira gerenciar pelo sistema através de relatórios, mas não é obrigatório.
10. E em **Parcelas** é para compras no crédito ou convênio parcelado.
11. Com isso, basta ir teclando **Enter** até a confirmação do fechamento da venda.
12. Para incluir mais de um item, basta digitar a quantidade seguido de **\*** e teclar **Enter**, e depois incluir o produto.
13. Com produto tela o campo **Valor Total** refere-se ao valor total dos produtos e o campo **Valor Unitário**, refere-se ao valor do último item caso tenha produtos diferentes.
14. É possível aplicar um desconto no valor total da venda. Após escolher a forma de pagamento, basta teclar **F11** e incluir a porcentagem ou o valor final da venda.
15. Lembrando que, se o desconto for superior ao permitido, o sistema vai solicitar uma senha para quem tiver autorização para liberar o desconto.
16. **F6**: não é utilizado.
17. **F7**: **Recebimentos & Consultas**:
    * **Efetivação de Contas Pagas**: essa opção é utilizada quando é realizado o recebimento do valor de um convênio (próprio ou empresa). Esse recebimento precisa ser efetivado, para que o valor conste no caixa.
    * **Devoluções de Crédito**: _esta opção é utilizada para efetivar estorno de recebimentos de vendas, ou seja, todo cliente de convênio terá um limite de gasto que você configura no cadastro e esse valor de estorno é creditado na conta do cliente novamente._ Além disso, é possível efetivar a devolução de venda. Isso não altera do valor no Caixa, mas imprime um comprovante, caso precise. Mas se você quiser registrar uma saída para que você não precise contar o cupom da venda cancelada, deverá fazer uma sangria no valor da venda.
    * **Recebimentos Diversos**: para recebimentos não fiscais, como recarga de celular.
    * Para não precisar sair da tela de vendas, possui um atalho para #efetivacao-de-entregas.
    * **Pré-Consulta de Clientes**: serve para visualizar as informações financeiras do cliente de convênio da loja.
18. **F9 - Sangria e Suprimentos**: esta função serve para registrar qualquer retirada ou entrada de dinheiro de forma manual. Por exemplo, para iniciar o dia e incluir o valor para o troco, você poderá registrar a entrada como Suprimento, informar o valor, o motivo e depois em Gravar e sairá um comprovante. Assim como se precisar fazer qualquer retirada do caixa para alguma emergência, basta marcar como sangria.

</details>

<details>

<summary>CANC. ÚLTIMO CUPOM</summary>

Usado somente para o sistema fiscal antigo com impressora de memória fiscal.

</details>

<details>

<summary>REDUÇÃO Z</summary>

Usado somente para o sistema fiscal antigo com impressora de memória fiscal.

</details>

<details>

<summary>RECEBIMENTOS</summary>

Atalho para **Parcelamento de Clientes.**

</details>

<details>

<summary>EFETIVAÇÃO DE ENTREGAS</summary>

Antes de iniciar, questione se o cliente pretende gerenciar as entregas pelo sistema.

* **CÓDIGO**: você consegue buscar a venda selecionando o cliente pelo nome.
* **DOC**: número da venda.
* Após carregar a venda de entrega no grid, basta clicar em **Efetivar** e a partir deste momento o valor vai contar para a movimentação do caixa.
  * Ressaltar com o cliente que o valor das vendas de entregas, serão contabilizados para o caixa e turno em que elas forem efetivadas.

</details>

<details>

<summary><mark style="color:red;">*</mark> FECHAMENTO DE TURNO</summary>

* Aqui é onde é feito o fechamento de caixa
* Você deve preencher os valores conforme os registros das vendas.
* **F1**: serve para você colocar o montante de cada tipo de moeda e nota para quem tem o costume de separar os montantes.
* Os demais campos podem ser configurados para serem preenchidos automaticamente.
* Aqui também é possível efetuar consultas dos caixas que já foram fechados e reimprimir o fechamento.

</details>

<details>

<summary>ATUALIZAR SISTEMA</summary>

* Atualização do Sistema.

</details>
