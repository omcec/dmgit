# Operacional

Abaixo serão descritos passo a passo das informações a serem passadas ao cliente durante o treinamento.

<details>

<summary><mark style="color:red;">*</mark> PRÉ-VENDAS</summary>

1. Neste módulo é onde faz o registro prévio das vendas para depois ser efetivado no **Terminal Caixa**. Mas também é possível fazer a venda direto no Caixa, direto no **DMaster ECF**, o que veremos mais para frente.
2. Você vai ter um Terminal balcão e um Terminal caixa?
   * _Este questionamento é válido para saber se devemos já explicar tudo iniciando no pré-vendas ou já partir para a tela do ECF, já que parte das funções são semelhantes,_&#x200B;​​​​​​ _pois no caso de um Treinamento Geral, podemos pular o pré-vendas._
3. Pois, no caso de quem vai trabalhar apenas com uma máquina, pode fazer a venda direto no ECF.
   * ​​​​​​​Salvo algumas exceções que devem ser realizadas no pré-vendas:
     * Venda de entrega.
4. Então você criando a pré-venda aqui ela já fica disponível para efetivar no caixa.
5. Ao **adicionar um produto** no grid, o **estoque já diminui** para não dar conflito, caso outro atendente esteja vendendo o mesmo produto de estoque baixo.
6. **Primeiro: vamos inserir um produto para fazer o processo mais simples de venda**:
7. Pode inserir informando o código do produto, ou código de barras (usando o leitor ou digitando) ou digitando o nome do produto.
8. **F2**: seleciona a forma de pagamento em dinheiro. Com isso você deve selecionar o atendente e depois só dando OK até confirmar a pré-venda.
9. Cada atendente deve saber seu código de cadastro, pois esse campo não dá para pesquisar pelo nome.
10. Inserir outro produto.
11. Fazer um venda para mostrar a aplicação dos descontos direto na linha do produto no grid ou na venda inteira com o **F6** na tela de pagamentos.
12. Verificar se eles pretendem gerenciar a entrega pelo sistema. Caso não, pular o próximo passo.
    * Caso a venda seja de entrega, com o cursor no campo Atendente, é nesse momento que você deve utilizar a tecla F6 para inserir o cliente da venda e valor que será recebido.
    * <mark style="color:blue;">Entrega e descontos no final da venda: para realizar a venda de entrega e aplicar descontos no final da venda, é necessário primeiro informar a forma de pagamento, depois definir a venda como entrega (</mark><mark style="color:blue;">**F6**</mark><mark style="color:blue;">) e por ultimo aplicar os descontos no final (</mark><mark style="color:blue;">**F11**</mark><mark style="color:blue;">).</mark>
    * Lembrando que se for registrar a entrega pelo sistema cobrando taxa de entrega (usando o produto **888888 - Frete**), por esta funcionalidade, o cadastro do cliente deverá estar com CPF, pois é uma exigência da SEFAZ.
    * Pode incluir uma **observação** para sair no cupom vinculado que sai junto com o cupom fiscal.
    * Nisso volta para a tela anterior. Basta selecionar o atendente e teclando OK até confirmar a pré-venda.
13. Já foi cadastrado algum cliente vinculado a algum convênio para vendas no crediário a prazo?
    *   **F3 - Convênio**: selecione a forma de pagamento pelo convênio. No campo código você seleciona o cliente (pode buscar pelo nome ou telefone colocando o hífen antes dos quatro ultimo números).

        _<mark style="color:blue;">Caso seja selecionado um Convênio à Vista, ainda será necessário informar a forma de pagamento (dinheiro, cartão, pix)</mark>_.
14. **F4 - Crédito, débito, PIX**: nessas modalidades de pagamentos você vai selecionar o cartão ou o PIX. O campo Nº do Documento referente ao número do comprovante da maquininha do cartão, não é obrigatório. E no campo **Parcelas**, quantidade da parcela. ​​​​​​​
15. **F9 - Clientes**: serve para simplesmente consultar ou selecionar o cliente antes de iniciar a venda.
    * Você pode simplesmente pesquisar digitando o nome no campo código ou pelo número do telefone (no formato XXXX<mark style="color:red;">**-**</mark>XXXX).
    * **F5**: permite para você cadastrar um cliente na hora.
    * **F9**: você pode verificar o histórico de compras de cliente após selecioná-lo.
    * A partir do momento que o cliente estiver cadastrado, você já pode clicar no Selecionar para informar o cliente na venda.
16. **F10** - acesso a itens: ao teclar F10 ou clicar no item mostra a porcentagem do desconto aplicado e o valor mínimo do item.
17. **F11**: aplicação de desconto após selecionar a forma de pagamento. Caso a venda seja de entrega, primeiro você informa o desconto e depois informa a entrega no F6.
18. **F12**: **sem nenhum produto lançado**, serve para ver todas as pré-vendas lançadas, os produtos da pré-venda e a possibilidade de excluir a pré-venda ou um item da pré-venda.
19. **F12**: na hora do fechamento da pré-venda, serve para **emitir NFe** em vez de Cupom fiscal. Caso precise, pode abrir um chamado, pois o processo é finalizado em outra aplicação.
20. **Shift+F12** - Manutenção de pedidos: para montar um pedido com os produtos que estão em falta ou até mesmo para encomendar um produto. Os pedidos por falta ou por encomenda podem ser criados aqui e vistos em **Relatório > Manutenção de Pedidos**.
21. É possível também incluir um produto em uma pré-venda existente.
    * A condição é a pré-venda tem que ser do mesmo dia e ser da mesma forma de pagamento (tipo de venda).
    * Nessas condições basta inserir o número da pré-venda existente no campo pré-venda na tela de fechamento após escolher o atendente. Para pesquisar as pré-vendas criadas, antes de inserir um produto, basta teclar F12.
22. **F1**: aqui você vê o resumo dos comandos desse módulo.

</details>

<details>

<summary><mark style="color:red;">*</mark> DEVOLUÇÕES</summary>

1. Esse módulo serve para devolver a quantidade do produto ao estoque.
2. A devolução só pode ser feita de forma integral caso tenha mais itens, se necessário a venda deverá ser refeita.
3. A venda pode ser pesquisada com número do cupom no campo "nº do Doc" ou com o número da venda.
4. Clica em Localizar, selecione a venda em Registros de Venda, digitar a mesma quantidade a devolver na coluna "**Qt Dev**" e depois clica em Gravar.
5. **Cupom de crédito - Convênio:**
   * Ao realizar uma devolução, o sistema irá solicitar os dados do nome do cliente para gerar um cupom de crédito, que posteriormente será efetivado no frente de caixa. Este cupom de crédito é gerado, pois o sistema não subtrai o valor do caixa automaticamente quando é realizada uma devolução, ficando a cargo do estabelecimento entregar aquele cupom como crédito para o cliente final para ser usado ao realizar uma nova venda para o cliente ou devolver o valor de acordo a forma de pagamento da venda e realizar os devidos ajustes no frente de caixa para não haver divergências no fechamento de caixa.

</details>

<details>

<summary>ORÇAMENTOS</summary>

1. Este módulo serve para montar orçamentos para cliente.
   * Esse recurso é indicado para cenários em que o cliente está pesquisando preços com interesse de compra. É possível manter um histórico de orçamentos e depois efetivar transformando em uma venda comum com impressão de cupom fiscal ou com emissão de uma NFe de venda.
2. No campo **Código**, você puxa os dados do cliente (que já deve estar previamente cadastrado);
3. Mais abaixo é o nome do **Atendente** que está operando;
4. Na área **Lançamento de Produtos**, esse segundo campo **Código**, você pesquisa e inclui os produtos;
5. No campo **Desc%** é para aplicar um desconto para o produto;
6. E o campo **Quant** é a quantidade de produtos que o cliente precisa;
7. Depois que incluir todos os produtos, você tem a opção de:
   * **F2 - Gravar Orçamento**, com isso vai ser gerado um número que posteriormente você poderá consultar o histórico de orçamentos, em **F3 - Buscar Orçamento**, para poder editar, efetivar ou excluir;
   * **F5 - Imprimir**: para imprimir, você deve primeiro **Gravar o Orçamento**. Com isso, você busca o orçamento no **F3** e para carregar na tela novamente e aí sim poder imprimir;
   * **F6 - Para visualizar o custo de cada produto:** é necessário selecionar o produto e teclar **F6** para ver o valor do custo;
   *   **F8 - Efetivar o orçamento:**

       * Ao Efetivar o orçamento, o sistema irá colocar os produtos no Pré-Vendas e a partir daí, você poderá enviar para emissão de Cupom fiscal no ECF ou para emissão de Nota fiscal no NFe;
       * Antes de Efetivar a Pré-Venda, o cliente deve ser selecionado.

       <mark style="color:red;">**ATENÇÃO:**</mark> se você abandonar a pré-venda, o orçamento será perdido. Então somente efetive o orçamento se realmente for finalizar como venda de cupom ou com emissão de NFe.
8. **F3 - Buscar Orçamento:** utilizado para buscar um orçamento que foi criado anteriormente;
9. **F4 - Excluir Orçamento;**
10. **Del:** utilizado para excluir item do orçamento.

</details>

<details>

<summary><mark style="color:red;">*</mark> MOVIMENTAÇÃO DO CAIXA</summary>

1. Neste módulo é possível consultar todos os fechamentos de caixa e os lançamentos manuais de **Sangria** e **Suprimento** efetuados anteriormente.
2. **Campo Loja**: é para selecionar a Loja Filial, caso haja;
3. **Em Data**: seleciona o dia da movimentação;
4. **Em Caixa**: informe o número do caixa, se tiver apenas um caixa, basta colocar **1**;
5. **Em Turno**: informe o número do turno. (cada vez que você abre um caixa, gera um turno);
6. **Em Operador**: mostra o usuário que operou o caixa nesse turno;
7. Aqui também mostra a Data e horário de abertura e fechamento;
8. O primeiro campo de valores, mostra os valores inseridos no momento do fechamento e abaixo a comparação com o que o sistema contou conforme os registros das vendas.
9. **Totalização**: mais abaixo tem o comparativo total para informar se o valor bateu ou se está faltando ou passando.
10. Em **Consultar Lançamentos**: serve apenas para ver os lançamentos manuais no caixa de **Suprimento** (entrada, como troco) e **Sangria** (saída, lanche).
    * O botão **Imprimir** só está disponível para esse parâmetro.
11. **F1**: para inserir uma observação, caso necessário
    * <mark style="color:blue;">Caso o cliente precise reimprimir o fechamento, a função está disponível somente no DMaster ECF onde também é possível efetuar consultas de fechamentos anteriores.</mark>

</details>

<details>

<summary>ROMANEIO DE ENTREGAS</summary>

<mark style="color:red;">**Se o cliente não for gerenciar as entregas pelo sistema, este módulo não precisa ser aprofundado.**</mark>

1. Este módulo serve para consultar as **entregas em andamento** e nela é possível **alterar o entregador**, caso você tenha mais de um e queira gerenciar pelo sistema.
2. Para **saber o endereço da entrega**, basta selecionar a venda que no rodapé aparece o endereço de entrega.
3. Caso tenha muitas entregas em andamento, é possível **filtrar pelo entregador** apenas selecionando ele no campo **Entregador**.

</details>

<details>

<summary><mark style="color:red;">​</mark>​​​​​​<mark style="color:red;">*</mark> PARCELAMENTO DE CLIENTE</summary>

<mark style="color:red;">**Se o cliente não for trabalhar com convênios, este módulo não precisa ser aprofundado.**</mark>

1. Este módulo serve para verificar:
   * Todas contas dos clientes de convênios próprio que estejam em aberto ou fechado;
   * Verificar os itens das vendas;
   * Dados da parcela;
   * Suprimir juros em caso de contas em atraso;
     * <mark style="color:blue;">Suprimir Juros: função é realizada apenas para contas em aberto e para todas as parcelas em aberto na conta. Estes dados são alterados apenas enquanto estiverem sendo exibidos, caso não sejam registrados daquela maneira eles voltarão com os valores originais na próxima consulta.</mark>
   * Estorno de pagamento.
2. É possível filtrar os valores por data, cliente, matrícula no campo **Cód Aux** (caso tenha) e status **Em Aberto** ou **Baixados**.
3. Com a lista de valores no Grid, é possível dar baixa nos valores que estão em aberto. Para isso basta selecionar o valor a baixar e clicar no botão Baixar.
4. Caso seja um pagamento parcial de uma conta, além de selecionar a conta, deve também informar o valor no campo Valor e clicar em Baixar.
5. Caso não seja selecionado nenhuma conta, o valor digitado será abatido das contas mais antigas.
   * _<mark style="color:blue;">Lembrando que todas as contas baixadas devem ser efetivadas no caixa para contar no fechamento.</mark>_
6. No rodapé tem as funções para ver Detalhes do Pgto ou fazer o Estorno (somente se o registro já estiver sido baixado no caixa), ver **Detalhes da Venda**, **Dados das** **Parcelas**, **Suprimir Juros**.
   * <mark style="color:blue;">**Dados da Parcela**</mark><mark style="color:blue;">: para acesso aos dados da parcela é necessário ter a liberação de</mark> <mark style="color:blue;">**Alteração dos dados da conta**</mark> <mark style="color:blue;">do módulo</mark> <mark style="color:blue;">**USUÁRIOS & ACESSOS**</mark><mark style="color:blue;">, pois é possível alterar o valor da parcela.</mark>

</details>

<details>

<summary><mark style="color:red;">*</mark> CONTAS A PAGAR</summary>

1. Este módulo é responsável pelo auxílio financeiro, ou seja, quanto ao pagamento de contas da sua loja. Aqui é possível baixar, excluir e incluir novas contas, além de alterar valor e vencimento de conta.
2. Inclusive, na entrada de notas fiscais, caso o faturamento esteja informado na nota fiscal, o registro de contas a pagar é lançado automaticamente. Caso não tenha a informação de faturamento na nota, você deve inserir as informações manualmente.
3. Quando houve alguma conta em aberto, o sistema carrega todos os vencimentos pendentes, mas é possível filtrar pela data, situação, tipo de despesa.
4. Aqui também tem a opção de incluir, baixar ou excluir uma conta.
5. Todas as despesas da loja é possível incluir aqui, não apenas com fornecedores, mas também de funcionário, de agua, energia, internet, telefone, etc.
   * Para realizar a inclusão de uma nova conta a pagar é necessário ter o fornecedor e o tipo de despesa cadastrado.
   * A inserção dessas informações contribui para o relatório do **Fluxo de Caixa DRE**, o que veremos mais a frente, e com isso ter um acompanhamento mais próximo do faturamento e lucro da loja.
6. Caso alguma conta tenha sido baixada indevidamente, é possível estornar. Basta fazer a pesquisa dos baixados, selecionar a conta e clicar em estornar no X vermelho.

</details>

<details>

<summary><mark style="color:red;">*</mark> NOTAS FISCAIS</summary>

<mark style="color:red;">**\***</mark>**ENTRADA DE NF**

* Esse treinamento já foi passado no Treinamento Inicial, mas verifique se o cliente possui alguma dúvida.

**PRÉ-ENTRADA**

1. Este módulo serve para dar entrada parcial de uma nota. Caso você tenha recebido uma nota com muitos itens, mas precisar registrar pelo menos um dos itens da nota para poder vender, este recurso é o ideal.
2. Você lança a nota de forma parcial, quantos itens precisar, e quando você for lançar a NF em **Entrada de NF**, o sistema já irá descontar os produtos lançados automaticamente.
3. Basta inserir os dados conforme solicitado, começando pelo:
   * CNPJ do fornecedor;
   * Número da NF
   * No campo **código** dá para pesquisar o produto pelo código do produto, código de barras e descrição.
   * **Qt. NF**: informar a quantidade da nota.
   * O campo **Lote** e **Validade** são opcionais.
4. Ao clicar em OK o produto é adicionado ao GRID. Ao final, basta Gravar para incluir o produto no estoque.
5. **Del**: para excluir um item do GRID;
6. **F2**: verificar todas as pré-entradas;
7. **F10**: cancelar Pré-entradas.

<mark style="color:red;">**\***</mark>**NFs LANÇADAS**

1. Esse módulo serve para devolução parcial/total da nota para o fornecedor ou até mesmo a exclusão se alguma nota foi inserida de forma equívoca.
2. Após a exclusão, é possível entrar com a nota novamente, se necessário.
3. E após devolução, também é possível fazer o estorno da mesma. Caso você devolva a nota errada.
4. Ao realizar exclusão da nota ou devolução, a quantidade do produto e os valores da nota retornam ao que eram antes.
   * **DEVOLUÇÃO**
     * Para realizar a devolução para o fornecedor de um ou mais itens, basta informar o CNPJ, o número da NF e clicar em Localizar.
     * Após carregar os itens, selecione o produto desejado, clique em Devolver, caso a nota tenha mais de um item, deve ser informado a quantidade a ser devolvida e depois Confirmar na última janela.
   * **ESTORNO DE DEVOLUÇÃO**
     * Para isso, Após carregar os dados da nota, basta selecionar o item devolvido e teclar em F3 - Detalhes da Devolução, selecionar o produto e teclar em Del.
   * **EXCLUSÃO DE NF**
     * Após carregar os itens da nota, basta clicar em Excluir NF. Após esse processo será necessário excluir o registro do boleto em **Operacional > Contas a pagar**.

<mark style="color:red;">**\***</mark>**AUDITORIA DE NF**

1. Serve para corrigir os preços das notas que já entraram.
   * No sistema é possível você autorizar um usuário a dar entrada da NF, mas sem alterar o preço. Com isso, você consegue carregar os itens dessa nota e alterar os valores.
2. Para carregar as notas, basta informar o número da NF ou selecionar o período da entrada da nota.
3. Clicar no + para ver os produtos da nota.
4. Clicar no + novamente para ver os preços e alterá-los se necessário.
5. Após alterar todos preços, clique em Confirmar. Ao retornar para a tela das notas, a mesma estará com status em **Verde**.

</details>

<details>

<summary><mark style="color:red;">*</mark> AJUSTE DE ESTOQUE</summary>

1. Este módulo serve para registrar a entrada ou saída do estoque de forma manual e informando o motivo.
2. Basta selecionar o Evento.
3. Inserir o produto no campo código.
4. Informar a quantidade de Unidades ou de Frações.
5. Outra função é, para aqueles que possui o modo **Vender Quantidade Maior Que o Estoque Disponível**​​​​​​​ ativo, poderá fazer o ajuste de zerar todos os produtos que estiverem com estoque negativo, inclusive também poderá desativar.

</details>

<details>

<summary>TRANSFERÊNCIAS ENTRE LOJAS</summary>

1. Este módulo serve para efetuar as **transferências de produtos** entre lojas vinculadas. As lojas vinculadas não precisam ser necessariamente matriz e filial.
2. ​​​​​​​Para todo processo de transferência, é necessário:
   * Informar o Estabelecimento de Destino.
   * Tipo de Transferência.
   * O produto pode ser incluído utilizando o código interno ou código de barras.
   * A Quantidade de Unidades.
   * Após todos os produtos inseridos no GRID, clicar em Gravar e depois em Enviar.

**TIPOS DE TRANSFERÊNCIAS**

1. **Transferência Online**: é gerada uma chave, bastando informar o mesmo no estabelecimento de destino. Para isto, basta selecionar o Tipo de Transferência Online, clicar em Receber e digitar o número do documento e clicar em Ok. Os itens serão carregados no Grid bastando clicar em Gravar.
2. **Transferência Offline**: é gerado um arquivo XML que deverá ser enviado para o estabelecimento de destino, por e-mail ou pendriver, por exemplo. Para receber, basta selecionar o Tipo de Transferência, clicar em Receber, selecionar o arquivo XML. Com os itens carregados no Grid, basta Gravar.
3. **Transferência por Nota Fiscal**: é gerado um NFe nesse tipo de transferência. Após informar os itens da transferência, a nota deverá ser emitida no NFe. Para receber, o mesmo deve ser feito no módulo de Entrada de NFe.
   * <mark style="color:blue;">Somente as transferências por NFe tem valor fiscal.</mark>
   * <mark style="color:blue;">Só é permitido realizar a transferência por nota fiscal entre lojas que são filiais no CNPJ.</mark>
4. **Transferência Integrada**: nesse tipo de transferência, os produtos serão enviados direto para a loja de destino. A transferência poderá ser recebida acessando o módulo de transferência entre lojas.

</details>

<details>

<summary>CONTROLE DE CARTÕES</summary>

1. Este módulo serve para dar baixa nos pagamentos feito pelos cartões e PIX.
   * <mark style="color:blue;">No caso de cartões, como geralmente a transferência pode ocorrer dias depois, é possível você gerenciar pelo sistema os pagamentos recebidos da operadora de cartão.</mark>
2. Para dar baixa, basta selecionar as vendas, marcando com o sinal de **+** do teclado e depois clicar em **Gravar**.
3. É possível pesquisar por vencimento ou vendas já baixadas e pelo tipo de pagamento.

</details>

<details>

<summary>CONTROLE DE CHEQUES</summary>

Este módulo serve para dar baixa nos pagamentos feito por cheques. É possível você gerenciar pelo sistema os pagamentos recebidos.

</details>
