# Relatórios

Abaixo serão descritos passo a passo das informações a serem passadas ao cliente durante o treinamento.

{% hint style="info" %}
#### **Exportação de relatórios**

Em qualquer momento na impressão de Relatórios que são exibidos na interface do sistema é possível exportá-los para diversos tipos de extensão, como em PDF e Excel (xls e xlsx).

**File -> Export Document -> Extensão desejada.**
{% endhint %}

<details>

<summary><mark style="color:red;">*</mark> RELATÓRIOS DE CLIENTES</summary>

1. **Lista de clientes**: toda a base cadastral de clientes.
2. **Vendas por cliente**: detalhes das compras realizadas pelos clientes.
3. **Vendas parceladas**: informações das compras de convênio (próprio ou empresa) realizadas pelos clientes.
4. **Recebimentos**: informações dos recebimentos de convênio (próprio ou empresa).
5. **Sem compras**: listagem de clientes sem compras.
6. **Aniversariantes**: relação dos clientes aniversariantes no período informado.
7. **Carta de cobrança**: relatório em formato de carta para a realização de cobrança individual dos débitos do cliente.

</details>

<details>

<summary>GERENCIAMENTO DE CONVÊNIO</summary>

1. Este módulo serve para gerenciar os convênios do tipo empresa, mas é possível ver o itens vendidos dos convênios próprios.
2. Nele é possível:
   * Consultar valores;
   * Fechar faturamento;
   * Confirmar recebimento.
3. É possível fazer o fechamento parcial do faturamento, para isto, basta fechar a fatura ainda dentro do ciclo corrente. Caso passe o ciclo de faturamento, o fechamento será integral.
   * <mark style="color:blue;">A partir do fechamento parcial, já é possível emitir uma NF referente ao faturamento.</mark>
   * <mark style="color:blue;">Só pode ser efetuado apenas um fechamento por dia do mesmo convênio.</mark>
4. Efetuado o fechamento parcial, as demais vendas para este convênio serão lançados no mesmo ciclo até o fechamento previsto.

</details>

<details>

<summary><mark style="color:red;">*</mark> MOVIMENTAÇÃO PERIÓDICA</summary>

1. Este módulo server para verificar as movimentações de vendas e notas fiscais emitidas e também como as tributações das vendas.
2. No campo **Loja**, serve para selecionar outra loja caso você tiver uma filial vinculada no sistema.
3. Você coloca período em **Data Inicial** e **Data Final** das movimentações que você deseja ver. Se você colocar apenas as datas e clicar em **Ver**, o sistema mostrará toda movimentação do período.
4. Dessas vendas você ainda pode filtrar por **Classe**, **Fabricante**, **Tipo de Movimentação**, **Tributação**, **Código** (Produto), **Nº Venda**, **Nº Caixa**, **Atendente**, **Turno**.
5. Você ainda pode habilitar **Visualizar Detalhes** para mostrar mais dados no relatório.
6. Habilitar o parâmetro **Exibir entregas efetivadas deste período**, caso aconteça da entrega ter sido realizada em um dia, mas efetivada em outro.
7. Aqui na apresentação tem a opção **Impressora;** com essa opção o sistema apresentará os dados em arquivo e com isso você poderá salvar no computador como PDF, Excel ou imprimir.
8. E a opção **Gráfico**, é para mostrar os dados em forma de Gráfico, o que veremos já no próximo módulo.
9. Outras opções de filtros:
   * A opção **Saídas P/Classes Sintético** mostra o resumo de vendas por classes.
   * Em **Tributação** é possível emitir os relatórios conforme o tipo de tributação. Geralmente esse é emitido a pedido da contabilidade.
10. E na parte inferior em Resumo da Movimentação do Período mostra os totais conforme o filtro que você colocar.

</details>

<details>

<summary>MOVIMENTAÇÃO POR GRÁFICOS</summary>

1. Neste módulo mostra as informações por gráficos com foco em picos de movimentação.
   * Aqui mostra por quantidades ou em valores totais .

</details>

<details>

<summary><mark style="color:red;">*</mark> DASHBOARD DE VENDAS</summary>

1. Este módulo tem o objetivo de mostrar uma visão geral do negócio em relação às vendas.
2. Aqui é possível visualizar as métricas de um determinado período e comparar com período anterior através de gráficos com valores totais.

</details>

<details>

<summary>FLUXO DE CAIXA / DRE</summary>

1. Este módulo serve para visualizar as receitas (vendas) e despesas lançadas no sistema no módulo #contas-a-pagar.
2. Então, se você quiser gerenciar toda a movimentação da loja, tudo que entra e sai, desde a venda até a folha de pagamentos e compras de insumos para uso da loja, é aqui que você verá, de forma macro, os valores mensais de tudo que foi realizado e o previsto para o resto do ano.
   * **Saldo Inicial**: esse valor é o saldo inicial que a sua empresa tem em caixa disponível para iniciar as atividades do ano ou deste momento para frente.
     * É o valor total que a empresa tem disponível para comprar produtos, contratar funcionários, adquirir móveis etc.

</details>

<details>

<summary><mark style="color:red;">*</mark> VENDAS</summary>

1. <mark style="color:red;">**\***</mark>**POR ATENDENTE**
   * Este módulo serve para visualizar as vendas por atendente.
   * Basta você selecionar o atendente e o período e adicionar os demais critérios que precisar para visualizar.
   * E no campo Loja, você informa a loja caso haja uma filial vinculada.
     * <mark style="color:blue;">Nas vendas de convênio à prazo (próprio e empresa), é possível definir para pagar a comissão somente após o recebimento do pagamento do convênio</mark>
     * <mark style="color:blue;">No relatório de comissão o parâmetro de "</mark><mark style="color:blue;">**Calcular Comissões de Vendas a Prazo no Ato da Venda**</mark><mark style="color:blue;">" é considerado no momento de registrar as vendas do movimento.</mark>
     * <mark style="color:blue;">Através do relatório de</mark> <mark style="color:blue;">**CMV**</mark> <mark style="color:blue;">é possível analisar os indicadores de lucratividade dos atendentes.</mark>
2. **VENDAS COM CARTÃO OU CHEQUE**
   * Este refere-se as vendas de cartão ou cheque de forma resumida para ver as que foram baixadas ou em aberto.

</details>

<details>

<summary><mark style="color:red;">*</mark> REGISTRO DE EVENTOS</summary>

1. Neste módulo você verifica todas as alterações realizadas no sistema. Como se fosse um diário de bordo de quase tudo que é alterado e registrado.
   * Basta informar o período. No relatório informa, a data, o horário do evento, o usuário que fez e o que ele fez.
   * Também é possível filtrar o Tipo de Evento.

</details>

<details>

<summary>CONTAS A PAGAR</summary>

1. Neste módulo informa todas as Contas a Pagar que deu entrada no sistema.
   * Por exemplo: as NF que dão entrada e que já veem configuradas para informar a forma de pagamento, o sistema capta a informação e inclui no **Contas a Pagar**.
2. ​​​​​​​Todas as despesas incluídas em **Operacional > Contas a Pagar** irão aparecer nesse relatório podendo ser filtrado por Período, Fornecedor e Tipo​​​​​​​ de Despesa.\\

</details>

<details>

<summary><mark style="color:red;">*</mark> ESTOQUE</summary>

1. Neste módulo você verifica como está seu estoque atual. Nele, é possível tirar relatórios de:
   * **Estoque Geral**: mostra o estoque atual.
   * Parâmetros para criar **pré-pedido**:
     * **Estoque Crítico:** informa os produtos que precisam de reposição mesmo que não esteja zerado, de acordo com a demanda.
     * **Estoque Zerado:** estes informa os itens que estão com estoque zerado.
     * **Itens vendidos**: quantidade de cada produto vendido. Neste dá para ver os mais vendidos no período selecionado.
   * **Curva ABC**: mostra os produtos com a maior, menor e intermediária parcela de lucros da loja.
   * **Ajuste no Estoque**: mostra a quantidade de entrada e saída dos produtos conforme período selecionado.
   * **Kits de Produtos**: mostra a relação de kits simples e misto no sistema.​​​​​​​
   * **Promoções**: mostra os produtos em promoção.
   * **Limite de Validade**: mostra a relação de validade de produtos no período selecionado.
   * **Sem movimentação**: mostra a relação de produtos sem movimentação no período selecionado.
   * **Perdas**: listagem de produtos que tiveram ajuste de estoque de perda.
   * **Transferências**: listagem das transferência de produtos.
   * **Ind Tec Produção:** é utilizado para visualizar os insumos e a qual produto principal o mesmo pertence.​

2) _Os campos mais abaixo são preenchidos automaticamente conforme você selecionar o produto no grid:_
   * _​​​​​​​Informações do produto;_
   * _Estoque de filiais;_
   * _Últimas compras._

</details>

<details>

<summary><mark style="color:red;">*</mark> HISTÓRICO DE PRODUTOS</summary>

1. Neste módulo, será gerado um relatório com histórico de movimentações de entrada e saída dos produtos.
   * Data Limite: estoque inicial conforme a ultima contagem no inventário ou do cadastro do produto.
2. ​​​​​​​Informações do Relatório:
   * _Na saída (S), mostra os dados da venda ou de Ajuste por saída._
   * _Na entrada (E), mostra nº da NF e o fornecedor ou de Ajuste por Entrada._

</details>

<details>

<summary>FICHA DE PRODUTOS</summary>

1. Mostra a relação de NF que deram entrada naquele produto.
   * De exemplo, pode carregar uma nota que já tenha dado entrada.
     * Ou buscar um produto dessa nota que deu entrada.

</details>

<details>

<summary><mark style="color:red;">*</mark> MANUTENÇÃO DE PEDIDOS</summary>

1. Serve para o gerenciamento de pedidos de acordo com estoque, faltas e encomendas.
2. Os pré-pedidos criados no **Relatório de Estoque**, irão aparecer aqui para serem convertidos em pedido e selecionar o tipo de saída.

</details>
