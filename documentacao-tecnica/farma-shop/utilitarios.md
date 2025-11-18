---
description: Neste menu contém os utilitários que serão utilizados pelo estabelecimento.
---

# Utilitários

**Etiquetas**

{% tabs %}
{% tab title="Etiquetas" %}
Módulo utilizado para realizar impressão de etiquetas de preço de produto.

<figure><img src="../../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

Neste módulo, é possível realizar a impressão de etiquetas do seguintes modelos:

* **Produto com preço e sem preço:** etiquetas geralmente brancas, com código interno, nome e preço do produto;
* **Gôndola 10x3, 6x4 e 8x4:** etiqueta geralmente amarela, com nome, código de barras ou código interno e preço do produto ;
* **Label:** etiquetas geralmente de roupas, com nome, preço e código de barras do produto.

#### Etiquetas por NF <a href="#etiquetas-por-nf" id="etiquetas-por-nf"></a>

É possível realizar impressão de etiqueta de produtos de determinada nota de entrada. Para isso, é necessário pesquisar a mesma, inserindo seu número no campo Nº da NF e clicando em localizar. Após o processo anterior, aparecerá no campo fornecedor, os demais dados da nota, onde deverá ser selecionado para que os produtos sejam carregados. Para a pesquisa, ainda é possível utilizar o parâmetro **exibir apenas os produtos que tiveram alteração do preço de venda / promoção.** Caso ele seja marcado, apenas serão exibidos no grid, produtos que pertencem a nota pesquisada com alteração de preço. Se desmarcado, serão exibidos todos os produtos que pertencem a nota pesquisada.

<figure><img src="../../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

Após selecionar o fornecedor, os produtos da nota serão carregados no grid, para que seja realizado o processo de impressão das etiquetas.

<figure><img src="../../../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>

Para realizar a impressão, é necessário selecionar o tipo de etiqueta e clicar em imprimir.&#x20;

<mark style="color:red;">**Observação:**</mark> para etiquetas de preço, devem ser informados os campos linha e coluna, de acordo com a folha de etiqueta.



#### Etiquetas avulsas <a href="#etiquetas-avulsas" id="etiquetas-avulsas"></a>

Outra forma para realizar impressão de etiquetas, é por produto, ou seja, lançando um a um. Para isso, é necessário pesquisar o produto no campo código, e ao selecionar o mesmo, as informações de descrição e fabricante serão preenchidas automaticamente, sendo necessário inserir apenas a quantidade, que refere-se a quantidade de etiquetas que serão impressas.

<figure><img src="../../../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

Após realizar os processos anteriores, clicar em ok e o produto será lançado no grid. Repetir o processo para cada produto que deverá ser impressa etiqueta.

<figure><img src="../../../.gitbook/assets/image (64).png" alt=""><figcaption></figcaption></figure>

Para realizar a impressão das etiquetas, é necessário selecionar o tipo de etiqueta. Para etiquetas de preço, é necessário configurar linha e coluna para impressão.

Após realizar as configurações necessárias, clicar em imprimir e as etiquetas serão impressas na impressora configurada no sistema.

#### Excluir produto <a href="#excluir-produto" id="excluir-produto"></a>

<figure><img src="../../../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure>

Para excluir um produto do grid, é necessário desmarcar o mesmo, utilizando a tecla \[ - ] e clicar em Excluir.

Ao marcar o tipo Etiqueta de gôndola, é possível realizar algumas configurações a mais:

1. **Etiqueta de gôndola unitário:** ao utilizar este parâmetro é lançado no grid, por padrão, apenas uma quantidade para impressão de etiqueta. Ao desmarcar o parâmetro, no momento do lançamento do produto, deve ser inserida quantidade de etiquetas para impressão;
2. **Alterar descrição UN:** parâmetro utilizado para alterar a descrição UN do produto, ou seja, caso o produto seja caixa, é possível alterar para CX. Por padrão, com a opção desmarcada, a informação é buscada do cadastro do produto;
3. **Exibir código interno:** parâmetro utilizado para imprimir código interno do produto. Por padrão, a impressão realizada é o código de barras.
{% endtab %}
{% endtabs %}

**Programação de ofertas**

{% tabs %}
{% tab title="Programação de ofertas" %}
Módulo utilizado para criar ofertas de produtos com data definida de início e término.

<figure><img src="../../../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure>

**Incluindo nova programação**

Para criar uma oferta, é preciso pesquisar o produto no campo código, inserir a porcentagem de desconto ou preço de promoção, definir uma data de início e término da oferta e clicar em ok. <mark style="color:red;">**\*Este passo deve ser realizado para cada produto a ser lançado.**</mark>

<figure><img src="../../../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>

Após o passo anterior, o produto será lançado no grid, sendo necessário apenas clicar em gravar e a oferta será criada.

<figure><img src="../../../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

Caso o início da oferta seja no dia corrente, o sistema deve ser reiniciado para que a alteração seja concluída.

<figure><img src="../../../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

Ao abrir o sistema na data de início da oferta, é apresentada uma mensagem de aviso informando sobre a mesma. Se clicar em sim, a oferta iniciará naquele momento, clicando em não o produto continuará fora da oferta.

<figure><img src="../../../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

Ao abrir o sistema no dia de término da oferta, é exibida uma mensagem para confirmar o término ou adiar o término da oferta, sendo a escolha do usuário. Em caso de adiar o término, deve ser acessado o módulo de programação de ofertas novamente e fazer o processo de prorrogar término da oferta.

**Exclusão de ofertas**

Para realizar a exclusão de uma oferta, é necessário marcar o registro utilizando a tecla \[ + ] e clicar em excluir.

<figure><img src="../../../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

É possível prorrogar o término da oferta. Para isso, é necessário marcar o registro do produto utilizando a tecla \[ + ], inserir a data do término e utilizar a tecla F2 para concluir.

<figure><img src="../../../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

Se marcado o parâmetro manter desconto atual no final do período na criação da oferta, ao expirar ou excluí-la, o desconto atual se mantém, ou seja, caso o produto já tenha um preço com desconto cadastrado, esse irá se manter.

<figure><img src="../../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

**Manutenção de produtos**

{% tabs %}
{% tab title="Manutenção de produtos" %}
Módulo utilizado para realizar alterações de preço, comissão e status em vários produtos simultaneamente, utilizando filtros.

<figure><img src="../../../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

Neste módulo, é possível pesquisar o produto por descrição, código interno, código de barras ou código Abcfarma, através do campo. Pode ser realizado o filtro por Situação, Classe/Sub-Classe e Fabricante.

<figure><img src="../../../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure>

Após pesquisar o produto, é necessário clicar em localizar e o mesmo será lançado no grid. Com o produto lançado, agora é possível realizar alterações utilizando as funções do módulo.

As formas de alteração de preço do produto são por reajuste positivo, ou negativo e até mesmo inserindo preço de promoção. Para realizar as alterações, é necessário alguns passos. Esses serão explicados a seguir.

<figure><img src="../../../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

O reajuste positivo é utilizado para aumentar o preço de venda do produto. Para isso, é necessário inserir um valor em porcentagem, selecionar o parâmetro \[%], marcar o parâmetro reajuste positivo, clicar em aplicar e o preço do produto será alterado.&#x20;

<mark style="color:red;">**Observação:**</mark> <mark style="color:red;"></mark><mark style="color:red;">o processo de reajuste é utilizado apenas com valor em porcentagem.</mark>

<figure><img src="../../../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

O reajuste negativo é utilizado para diminuir o preço de venda do produto. Para isso, é necessário inserir um valor em porcentagem, selecionar o parâmetro \[%], marcar o parâmetro reajuste negativo, clicar em aplicar e o preço do produto será alterado.&#x20;

<mark style="color:red;">**Observação:**</mark> <mark style="color:red;"></mark><mark style="color:red;">o processo de reajuste é utilizado apenas com valor em porcentagem.</mark>

<figure><img src="../../../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>



É possível realizar alteração na porcentagem de comissão do produto. Para isso, é necessário inserir um valor em porcentagem, selecionar o parâmetro \[%], marcar o parâmetro comissão, clicar em aplicar e a porcentagem de comissão será aplicada no cadastro do produto. Para retirar o valor de comissão, é necessário informar o valor 0.

<figure><img src="../../../.gitbook/assets/image (82).png" alt=""><figcaption></figcaption></figure>

A alteração de preço também pode ser realizada inserindo valor em real. Desta maneira é possível apenas aumentar o preço do produto ou inserir preço de promoção. Para realizar as alterações, é necessário alguns passos. Esses serão explicados a seguir.

A alteração de preço é utilizada para ajustar o preço de venda do produto, positiva ou negativamente. Para isso, é necessário inserir um valor em real, selecionar o parâmetro \[$], marcar o parâmetro alteração de preço, clicar em aplicar e o preço do produto será alterado.

<figure><img src="../../../.gitbook/assets/image (83).png" alt=""><figcaption></figcaption></figure>

O preço de promoção pode ser alterado inserindo valor em real ou porcentagem. Para realizar essa alteração, é necessário alguns passos. Esses serão explicados a seguir.

O preço de promoção é utilizado para inserir ou zerar o valor de promoção do produto. Para isso, é necessário inserir um valor em real ou em porcentagem, selecionar o parâmetro \[%] ou \[$], marcar o parâmetro promoção, clicar em aplicar e o preço de promoção do produto será alterado.

<figure><img src="../../../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

Com o produto lançado no grid, é possível visualizar as informações do mesmo. São elas:

1. Descrição;
2. Fabricante;
3. Classe;
4. Sub-Classe;
5. Preço de venda;
6. Preço de promoção;
7. Preço de farmácia popular;
8. Estoque atual.

<figure><img src="../../../.gitbook/assets/image (85).png" alt=""><figcaption></figcaption></figure>

Neste módulo, também é possível ativar ou inativar produtos. Com o produto lançado no grid, é necessário selecionar o mesmo, clicando sobre ele e utilizar a tecla F5. Caso o produto esteja ativo o processo irá inativá-lo e vice versa. Ao clicar sobre o produto, selecionando o mesmo serão mostradas algumas informações. São elas: código interno e custo médio do produto.

<figure><img src="../../../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

Ao realizar busca de produtos ou utilizar filtros, os produtos mostrados no grid, são apenas os ativos no sistema. Para realizar a busca de todos os produtos é necessário utilizar o parâmetro consulta geral, para que sejam mostrados os produtos ativos e inativos.

É possível realizar alteração de preço de venda, promoção e preço de farmácia popular clicando sobre os campos e inserindo o valor manualmente. Para isso, é necessário duplo click no campo desejado e o mesmo ficará editável, sendo possível inserir o valor.

<figure><img src="../../../.gitbook/assets/image (87).png" alt=""><figcaption></figcaption></figure>

Todas as alterações realizadas neste módulo, são aplicadas a todos os produtos que são exibidos no grid no momento da pesquisa.
{% endtab %}
{% endtabs %}



***

**Inventário**

{% tabs %}
{% tab title="Inventário" %}
Módulo utilizado para realizar contagem de estoque dos produtos do estabelecimento.

<figure><img src="../../../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

Na tela inicial do módulo, é possível visualizar as informações de tipo de inventário, situação do inventário, aberto por, data de abertura, finalizado por, data de finalização. Essas informações serão explicadas a seguir.

<figure><img src="../../../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure>



#### Tipos de inventário <a href="#tipos-de-inventario" id="tipos-de-inventario"></a>

* **Geral:** esse tipo de inventário é utilizado quando será realizada a contagem de todos os produtos do estabelecimento;
* **Parcial:** esse tipo de inventário é utilizado para a contagem parcial do estabelecimento, ou seja, apenas alguns produtos serão contados;
* **Por classe:** esse tipo de inventário é utilizado para a contagem por classe, ou seja, o usuário irá definir qual classe de produtos irá realizar a contagem.

#### Situação do inventário <a href="#situacao-do-inventario" id="situacao-do-inventario"></a>

* **Novo inventário:** ainda não possui nenhum inventário iniciado e/ou cancelado;
* **Inventário em andamento:** existe um inventário iniciado, mas ainda não foi finalizado e/ou cancelado;
* **Cancelado:** existe um inventário anterior cancelado.

**Aberto por:** código e nome do usuário que iniciou o inventário;

**Data de abertura:** data e hora que o inventário foi iniciado;

**Finalizado por:** código e nome do usuário que finalizou o inventário;

**Data da finalização:** data e hora que o inventário foi finalizado.

#### Abertura de inventário <a href="#abertura-de-inventario" id="abertura-de-inventario"></a>

* Durante a contagem do inventário, a entrada e venda de produtos pode ser realizada normalmente, pois na finalização o sistema irá ajustar o estoque de acordo com a contagem, entradas e saídas;
* Caso o cliente possua SNGPC integrado, os produtos de SNGPC não precisam ser contados no inventário;
* A contagem de estoque pode ser realizada por vários usuários, porém a finalização deve ser realizada apenas por um usuário.

Para iniciar um novo inventário, é necessário selecionar o tipo: geral, parcial ou por classe. Após selecionar o tipo, clicar em iniciar o inventário.&#x20;

<mark style="color:red;">**Observação:**</mark> <mark style="color:red;"></mark><mark style="color:red;">caso o tipo de inventário seja por classe, é necessário selecionar a(s) classe(s) desejada(s) em classe/subclasse;</mark>

Após clicar em iniciar o inventário, será aberta um nova tela, onde serão lançados os produtos e sua respectiva quantidade de estoque.

<figure><img src="../../../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

Para lançar um produto, é necessário utilizar o código interno, código de barras ou descrição do mesmo. Para isso, é utilizado o campo código. Ao selecionar o produto, algumas informações são preenchidas automaticamente, são elas:

* **Descrição:** refere-se a descrição do produto (informação contida no cadastro do mesmo);
* **Fabricante:** refere-se ao fabricante do produto (informação contida no cadastro do mesmo);
* **Último inventário:** data de finalização do último inventário que o produto foi contado.

Com todas as informações do produto carregadas, é preciso informar a quantidade do estoque. Para isso, é necessário preencher o campo quantidade ou frações. O campo frações deve ser preenchido apenas se o produto em questão for fracionado. Após informada a quantidade correta de estoque do produto, clicar em ok.

Após clicar em ok, o item será lançado no grid com as seguintes informações:

* Informações cadastrais do produto (código interno, descrição e fabricante);
* Quantidade de estoque informada pelo usuário.

<figure><img src="../../../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

#### Exclusão de item <a href="#exclusao-de-item" id="exclusao-de-item"></a>

Para excluir um produto do inventário, é necessário selecionar o mesmo e utilizar a tecla Del. Será apresentada uma mensagem de confirmação, sendo necessário apenas clicar em sim e o produto será excluído do inventário.

<figure><img src="../../../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

#### Localizar produto lançado <a href="#localizar-produto-lancado" id="localizar-produto-lancado"></a>

Caso tenha muitos produtos lançados no inventário e seja necessário localizar um deles, é possível utilizar a tecla F2. Na tela aberta, inserir a descrição do produto, utilizar a tecla enter ou clicar em ok e o produto será selecionado.

<figure><img src="../../../.gitbook/assets/image (94).png" alt=""><figcaption></figcaption></figure>

#### Finalização do inventário <a href="#finalizacao-do-inventario" id="finalizacao-do-inventario"></a>

Com todos os produtos lançados corretamente, é necessário realizar a finalização do inventário, ou seja, atualizar o estoque dos produtos contados, de acordo com o que foi lançado no inventário.

<mark style="color:red;">**Observações:**</mark>

* A finalização do inventário deve ser realizada no terminal administrador;
* Para realizar o processo de finalização, não pode haver nenhuma movimentação no sistema, ou seja, caso a contagem seja finalizada em um dia que houve movimentações no sistema, a finalização do inventário deve ser realizada no dia seguinte;
* Para finalizar o inventário não pode haver pré-venda pendente, ou seja, todas as pré-vendas devem estar efetivadas.

Para realizar a finalização, é preciso utilizar o botão finalização do inventário. Ao clicar no botão, serão mostradas algumas mensagens de confirmação e alerta para o usuário, que serão explicadas a seguir.

A mensagem abaixo informa que o sistema está com o parâmetro de vender quantidade maior que estoque disponível habilitado. Para desabilitar, deve ser acessado o módulo de configurações gerais do sistema.

<figure><img src="../../../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

A próxima mensagem é um alerta para que o usuário feche o sistema em outros computadores que estejam em uso.

<figure><img src="../../../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

A última mensagem de alerta é a confirmação para que a finalização do inventário seja concluída.

<figure><img src="../../../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

Após todas as mensagens anteriores, agora será necessário definir o que acontecerá com o estoque dos produtos não contados:

<figure><img src="../../../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>

* **Manter o estoque atual:** será mantido o estoque atual de todos os produtos que não foram contados no inventário;
* **Zerar o estoque atual:** será zerado o estoque de todos os produtos que não foram contados no inventário e os produtos serão inativados.

<mark style="color:red;">**Observações:**</mark>

* Geralmente, os produtos não contados são aqueles que possuem cadastro no sistema, mas não contém estoque físico na loja, ou seja, não foram lançados no inventário.
* Esta janela é aberta apenas para contagem de inventário geral e por classe.

Após definir sobre o estoque dos produtos não contados, o inventário é finalizado e o estoque dos produtos atualizado. Agora, o sistema pode ser aberto em todos os computadores e utilizado normalmente.&#x20;

<mark style="color:red;">**Observação:**</mark> Após a finalização do inventário, são salvos na área de trabalho do terminal administrador os relatórios:

• **Produtos não contados:** itens que não foram lançados no inventário;

• **Divergência de estoque:** itens que tiveram divergência de estoque entre o estoque atual e o estoque contado;

• **Itens contados:** itens que foram contados no inventário.

#### Cancelamento de inventário <a href="#cancelamento-de-inventario" id="cancelamento-de-inventario"></a>

Caso seja necessário cancelar um inventário, é necessário clicar no botão cancelar inventário, na tela inicial do módulo. Com isso, o estoque atual de todos os produtos será mantido.

<figure><img src="../../../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

Após o cancelamento, a situação do inventário será alterada para CANCELADO e os campos finalizado por e data da finalização serão alterados para cancelado por e data do cancelamento, como mostrado abaixo.

<figure><img src="../../../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>

#### Produto já lançado <a href="#produto-ja-lancado" id="produto-ja-lancado"></a>

Caso um usuário tente lançar um produto que já foi contado por outra pessoa, o sistema apresentará uma mensagem de alerta, como mostrado abaixo.

<figure><img src="../../../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>

Se for lançado um produto que já tenha sido lançado por aquele usuário, o sistema irá apresentar a mensagem ao lado, informando qual a quantidade contada anteriormente, qual a quantidade a ser somada e qual o saldo final. Ao confirmar a mensagem, a quantidade será atualizada no inventário.

<figure><img src="../../../.gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure>

Caso o usuário tenha realizado a contagem incorreta e o estoque do produto ficar negativo após a finalização do inventário, o sistema apresentará uma mensagem de alerta e irá gerar um relatório com os produtos, para que o usuário realize a correção do estoque destes produtos. Para corrigir, é necessário excluir o produto do inventário e lançar novamente com a quantidade de estoque correta.

<figure><img src="../../../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

É possível gerar alguns relatórios antes da finalização do inventário, são eles: itens lançados no inventário e produtos não contados, onde cada um será explicado separadamente a seguir.

* **Itens do inventário:** o relatório de itens lançados no inventário possui duas opções:

<figure><img src="../../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

**Produtos contados:** é gerado um relatório de todos os produtos lançados no inventário;

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FaMMBUL488im8M32omVUI%252FRelatorio%2520produtos%2520contados.png%3Falt%3Dmedia%26token%3D83b3a50f-fcbe-4f25-8fb8-6898d0339b09&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=c38c2967&#x26;sv=2" alt=""><figcaption></figcaption></figure>

**Apenas divergências:** é gerado um relatório apenas dos produtos com divergência entre o estoque atual e o estoque contado;

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FgbhgwDYq5zuXx8IuFuBU%252FRelatorio%2520divergencia.png%3Falt%3Dmedia%26token%3D0c34d976-0842-40e2-a08f-c10a2d87a159&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=9f38f621&#x26;sv=2" alt=""><figcaption></figcaption></figure>

*   **Produtos não contados:** esse relatório é gerado com todos os produtos que não foram contados no inventário.



    <figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fxv00PswZg2cIePPB1faq%252FRelatorio%2520nao%2520contados.png%3Falt%3Dmedia%26token%3D1fd74136-cca6-48fc-9531-ad8b5b847386&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b8e6cfda&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**Observação:**</mark> quando um inventário está em andamento, ao iniciar o sistema, é exibida a mensagem abaixo:

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FGCKrpG7ciCDjCAu7Ktot%252FProdutos%2520em%2520processo%2520de%2520inventario.png%3Falt%3Dmedia%26token%3D75bb1d95-6f9d-4b96-bfb0-e72cfaa9d978&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=3bb6aa94&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

**Atualizar - Versão do sistema**

{% tabs %}
{% tab title="Versão do sistema" %}
Este módulo poderá ser utilizado para atualizar a versão do sistema sempre que houver uma atualização pendente de ser executada.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FhYSEDMwfJH4NRjUKaP50%252Fatualizar%2520inicial.png%3Falt%3Dmedia%26token%3D9482feb0-e32b-491e-8df3-f4f9f675e909&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=54d42bc7&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao clicar na opção versão do sistema, é apresentada a mensagem abaixo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FgmuipgLoPGMlvTNjg9M4%252FVerificando%2520atualiza%25C3%25A7%25C3%25B5es.png%3Falt%3Dmedia%26token%3Df8f9c165-2a8c-4759-a665-a0a2f3f75e29&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=f69cdde1&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Caso o sistema já esteja atualizado, é apresentada uma segunda mensagem contendo a informação que o sistema já está atualizado.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F0XgpLI1Msnt2lTn9Swva%252FVersao%2520ja%2520atualizada.png%3Falt%3Dmedia%26token%3D4cb3abdc-4be7-4bd2-acb4-a6e6cf93bf77&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=4f00d252&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Caso o sistema ainda não esteja na última versão disponível, o mesmo irá apresentar a mensagem de atualização pendente, sendo necessário clicar em sim para atualizar. Ao clicar em sim, o sistema será reiniciado e uma nova mensagem de atualização irá aparecer. Logo após, o sistema estará atualizado.&#x20;

<mark style="color:red;">**Observação:**</mark> a atualização do sistema deve ser realizada obrigatoriamente no Terminal Administrador.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FavsKXH59adFpaV5vlKAm%252FNova%2520versao.png%3Falt%3Dmedia%26token%3D01a31c0c-e563-419a-8a2f-856d01cd6a75&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=dca8152e&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F3TlQODT4q7VXcI1HSZSZ%252FAtualizando.png%3Falt%3Dmedia%26token%3D63052ab3-d9a3-42df-998b-131fdde3d075&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=796d9839&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Atualizar - Produtos e-Pharma <a href="#atualizar-produtos-e-pharma" id="atualizar-produtos-e-pharma"></a>

{% tabs %}
{% tab title="Produtos e-Pharma" %}
Módulo utilizado para gerar a tabela de preços do PBM E-Pharma.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Ft6Me2I3V91Ws0aTNn2Ep%252Finicial.png%3Falt%3Dmedia%26token%3D98acb43f-3d9e-4df1-ad24-3fa2e51835a4&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=ac5982ed&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao clicar no menu anterior, é aberta a mensagem de confirmação para que seja gerado o arquivo de tabela de preços. Para confirmar, é necessário clicar em sim e o mesmo será criado na pasta MBHSist. **Observação:** o arquivo é salvo com o nome TabPrecos.txt.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FQqtRKMfeFeaYdjilv6lB%252FGeracao%2520de%2520tabela%2520de%2520preco.png%3Falt%3Dmedia%26token%3Dc1096c88-e6d6-4617-8296-b53fb79eb11e&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=33b77988&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

**Atualizar - Base Cote fácil**

{% tabs %}
{% tab title="Base Cote fácil" %}
Cote Fácil é um empresa de cotações de produtos e o sistema realiza o processo de gerar um arquivo para que o usuário possa enviá-lo para essa empresa.

A seguir, será explicado o processo para exportação do arquivo pelo sistema DMASTER.

O módulo é utilizado para exportar toda a base de produtos para envio ao Cote Fáci&#x6C;**.**

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FLpJ7NsQ4l5drCCshf3Wf%252FInicial.png%3Falt%3Dmedia%26token%3Dd37e937f-7ea9-49f6-869b-3c679bc1b5dd&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=6ef48f9c&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao acessar o módulo, será gerada a mensagem de exportação, sendo necessário clicar em si&#x6D;**.**

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FBYlRVtPqz4JF7pTe3YGn%252Fconfirmacao.PNG%3Falt%3Dmedia%26token%3D851b6f4c-8c88-4e3b-9583-2588e4886885&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=eac784e5&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Após a exportação, o arquivo será gerado na pasta **MBHSist > Cote Fácil.**

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FqCdTDJ1ot4M0uZMHN6N1%252FPasta%2520cote%2520facil.png%3Falt%3Dmedia%26token%3Ddc54ecff-52bd-48c4-9439-92ba66f6d622&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=c5b59315&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

### Atualizar - Tabela IBPTax <a href="#atualizar-tabela-ibptax" id="atualizar-tabela-ibptax"></a>

{% tabs %}
{% tab title="Tabela IBPTax" %}
Módulo utilizado para importar a tabela IBPTax, onde contém as informações de imposto dos produtos de acordo com NCM.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F5cKXMEd01ws5NCnYAua9%252FInicial.png%3Falt%3Dmedia%26token%3D9d0285b4-e37c-4bcd-8ea4-de3ca42c0ec8&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=89b9bdcd&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao acessar o módulo, é gerada uma mensagem de confirmação, sendo necessário clicar em Sim e a tabela será importada. Essa tabela tem o objetivo de importar para o sistema a informação de valores de imposto de acordo com o NCM. Dessa forma, caso haja produtos que possuem NCM no cadastro do produto, mas os valores de Imposto União e Imposto Estado estão sem informação, é necessário importar a tabela para que a informação seja atualizada.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FxVmrBLpU2YKkVockAlbY%252FConfirmacao%2520importacao%2520tabela.png%3Falt%3Dmedia%26token%3Daeab5555-f126-4523-aa16-f06b2128bab3&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=679699e9&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após a confirmação na tela acima, serão geradas as mensagens, como mostrado abaixo:

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fl0g0KrpXHe38p7exn2Yt%252FAtualizando%2520cadastro.png%3Falt%3Dmedia%26token%3Dcdc7115a-7891-4b09-8e50-8accf2cacded&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=d89d5d9e&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FKa6VFebpOnWQZUlVhVZP%252FImportando%2520tabela.png%3Falt%3Dmedia%26token%3D662f8f86-e872-4b9f-b036-c0d976d4f5b2&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=e6c63d0d&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

### Atualizar - Produtos PBM's <a href="#atualizar-produtos-pbms" id="atualizar-produtos-pbms"></a>

{% tabs %}
{% tab title="Produtos PBM's" %}
Módulo utilizado para importar a tabela de produtos de PBM para o sistema.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FPciIwdo1cCoZCzDSVDos%252FInicial.png%3Falt%3Dmedia%26token%3Dd921f4e2-2508-459a-b845-36e29f81e023&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=ab764cc7&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao acessar o módulo, é gerada uma mensagem de confirmação, sendo necessário clicar em sim. Em seguida, será aberta a tela para selecionar a tabela dos produtos que se encontra na pasta MBHSist e clicar em abrir. Após os processos acima, a importação da tabela será realizada.

\


<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FXN5e3uQpEC41ROrL67fG%252FArquivo%2520PBm.png%3Falt%3Dmedia%26token%3D1efc2bfe-7dd1-4542-a0bd-841d276c6e87&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b529fd12&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FQbJKcxfqyPSOvNjmoTKP%252FConfirmacao%2520importacao.png%3Falt%3Dmedia%26token%3D03c5515d-985b-4a40-9603-3d5fb45c97f7&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=6a593981&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

### Atualizar - Terminal Busca Preço G2 <a href="#atualizar-terminal-busca-preco-g2" id="atualizar-terminal-busca-preco-g2"></a>

{% tabs %}
{% tab title="Term. Busca Preço G2" %}
O terminal de consulta de preço é um equipamento que fica na loja, conectado a rede interna da loja e comunicando com o Servidor através do IP. O processo de configuração e utilização serão explicados a seguir e são utilizados apenas para o **terminal busca preço G2**.

**Observação:** para realizar as configurações do aplicativo, o Java precisa estar instalado no computador.

#### Configuração do equipamento <a href="#configuracao-do-equipamento" id="configuracao-do-equipamento"></a>

A configuração do equipamento deve ser realizada para que o mesmo comunique com o servidor da loja através do IP. Dessa forma, o IP do servidor deve estar fixo.

**Observação:** a configuração no equipamento deve ser realizada pela empresa em que o cliente adquiriu o mesmo. É orientado configurar o equipamento em uma faixa de IP mais alta, por exemplo: 192.168.1.222, para que não ocorra conflito com os demais computadores da rede.

#### Exportação de arquivo <a href="#exportacao-de-arquivo" id="exportacao-de-arquivo"></a>

Para utilização do terminal de consulta de preço, deve ser exportado um arquivo no sistema, contendo todos os produtos cadastrados. A exportação é realizada neste módulo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FXvM8uLTEuZDWCv1AdEJT%252FExportar%2520produto.png%3Falt%3Dmedia%26token%3Da200f0fb-cc60-4f65-8aa9-d951833bfa25&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=e47fe2b8&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Na próxima tela, será exibido o nome do terminal de consulta, sendo necessário apenas clicar em ok para escolher onde o arquivo será salvo. **Observação:** o arquivo é salvo com o nome **BUSCAPRECOG2.txt.**

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Ft4PqgYEGU1YY8Eh8hIQo%252FExporta%2520arquivo.PNG%3Falt%3Dmedia%26token%3Dba2620a6-df97-4aba-9396-8da1758efecf&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=9b31c86e&#x26;sv=1" alt=""><figcaption></figcaption></figure>

#### Configuração do aplicativo <a href="#configuracao-do-aplicativo" id="configuracao-do-aplicativo"></a>

O primeiro passo é copiar a pasta **BuscaPreço do Servidor Dmaster**, no caminho **\\\arquivos\Suporte\07. Utilitarios de Sistema** para **C: do servidor do cliente**.

Após a cópia da pasta, executar o arquivo **tc-server-2.4.9.jar**.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FTMMu6oeuogbzo8rcCYLd%252Faplicativo%2520tcserver.PNG%3Falt%3Dmedia%26token%3D8daaa814-b409-4b2f-9d31-c695568af490&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=7d7bdb13&#x26;sv=1" alt=""><figcaption></figcaption></figure>

**Observação:** o aplicativo tc-server-2.4.9 deve ser inserido na pasta iniciar do Windows.

Na tela inicial do aplicativo, clicar em **produtos** e logo após clicar em **Configurações do banco de dados**.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FvgIVRVxC6gEVcxPvdgYG%252FTC%2520Server%2520inicial.PNG%3Falt%3Dmedia%26token%3D79d53f7d-237e-488f-a454-28154c8ab942&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=7db7bf19&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Na próxima tela, na seção **gerenciamento de base de dados**, selecionar a opção **Externo (arquivo de texto).** Logo abaixo, na seção **Externo (arquivo de texto)**, clicar em pesquisar para buscar o arquivo que é gerado pelo sistema DMASTER.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F8U2Lp2h4KWE2zgi3DTn1%252FPesquisa%2520arquivo.PNG%3Falt%3Dmedia%26token%3D7b9190cd-43ca-4bf4-bffe-2ec82af11961&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=3d1b56a9&#x26;sv=1" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fg4rnshmzZ2Sz2e7kzxW5%252FConfig1.PNG%3Falt%3Dmedia%26token%3D0e6e7397-5054-4236-9600-fd6b251a0b71&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=6c99ebbd&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Ainda é possível configurar o **intervalo** de atualização, ou seja, o tempo que o aplicativo irá ler o arquivo de texto. O tempo mínimo é 10 minutos, dessa forma, o aplicativo irá ler o arquivo de 10 em 10 minutos.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FYR9JQadsCsszic8gAoUH%252FConfig%2520intervalo.png%3Falt%3Dmedia%26token%3D51210192-e9e4-4461-94ff-70343a1a4985&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=580e611&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Após toda a configuração, clicar em **ok** para salvar.

Ao fim da configuração, serão mostrados todos os produtos na tela inicial do aplicativo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FQo99Lw2ZTs260LfUlakq%252FConfig%2520final.PNG%3Falt%3Dmedia%26token%3D9b738aee-dca4-4a0c-a206-94844fbc0ef8&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=284d9f49&#x26;sv=1" alt=""><figcaption></figcaption></figure>

**Observação:** ao final dos processos, o aplicativo deve ser apenas **minimizado**. Assim, ele ficará carregado próximo ao relógio.

Após a configuração do aplicativo, a cada alteração que houver no sistema, deve ser realizada a exportação do arquivo, de acordo compara que o aplicativo realize a atualização para o equipamento.
{% endtab %}
{% endtabs %}

### Atualização de preços <a href="#atualizacao-de-precos" id="atualizacao-de-precos"></a>

{% tabs %}
{% tab title="Atualização de preços" %}
A atualização de preços de medicamentos é disponibilizada pela Câmara de Regulação do Mercado de Medicamentos (CMED), que é o órgão responsável pela regulação econômica do mercado de medicamentos no Brasil. ​

Esse órgão é responsável por disponibilizar a lista de preço dos medicamentos. A partir dessa lista, algumas empresas, por exemplo ABCFarma, também a disponibilizam para seus assinantes.

O reajuste anual de preços ocorre em Abril, porém mensalmente ocorrem atualizações, que podem ser de preço, fabricante, código de barras, entre outras informações. Com isso, as atualizações podem ser realizadas mensalmente pelo sistema.​

Para realizar a atualização de preços no sistema Dmaster é utilizado o módulo **Utilitários > Atualização de preços** e o processo deve ser realizado no terminal administrador.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FOEuQPCqVyvLpWkhVDc8t%252FMenu%2520atualizacao%2520de%2520precos.png%3Falt%3Dmedia%26token%3D1f900a9c-eb02-479c-8472-287f70e60732&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=c8e3549b&#x26;sv=2" alt=""><figcaption></figcaption></figure>

### Tipos de atualização <a href="#tipos-de-atualizacao" id="tipos-de-atualizacao"></a>

**Lista geral de preços:** para esse tipo de atualização, a Dmaster disponibiliza a lista de preços de acordo com a lista disponibilizada pelo órgão responsável (CMED);​

**Assinantes ABCFarma:** esse tipo de atualização é utilizado para clientes que são assinantes da ABCFarma. Sendo assim, ao realizar o processo, a comunicação é realizada direto com a ABCFarma;​

**Distribuidora Santa Cruz:** nesse tipo de atualização é utilizado o arquivo disponibilizado pela Distribuidora Santa cruz.​

### Lista geral de preços <a href="#lista-geral-de-precos" id="lista-geral-de-precos"></a>

**Observação:** a atualização de preços da ABCFarma é realizada de acordo com o código da ABCFarma do produto, de acordo com o cadastro, ou seja, apenas produto que possuem código ABCFarma no cadastro serão atualizados.

Esta opção é utilizada para realizar atualização de preço geral. Ao clicar na opção, é aberta a tela abaixo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FI8afM7aRcZFWJOaU1YzT%252FTela%2520inicial%2520atualizacao%2520de%2520precos.PNG%3Falt%3Dmedia%26token%3D79f30214-db3f-49de-8feb-e6ab937db4d1&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=8ede775d&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Nesta tela, é necessário apenas clicar em Atualizar. No rodapé da tela, é exibida a data e hora da última atualização realizada, ou seja, quando foi realizada a última atualização de preços.

Existem produtos que não possuem PMC definido, são definidos como liberados. Com isso, é preciso definir um percentual para ser somado ao preço de custo para gerar o preço de venda dos produtos. O percentual padrão do mercado é 45%, mas este, pode ser ajustado de acordo com a necessidade do cliente. Se houver classes sem informação de percentual de liberados, será exibida a mensagem abaixo. Se a mensagem for confirmada, o sistema irá inserir o percentual naquela classe automaticamente. Se a mensagem for negada, o processo será interrompido, até que o usuário ajuste a informação do percentual de liberados.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FgTEaYqaz736nfDpWxaxG%252FLiberados.PNG%3Falt%3Dmedia%26token%3D550945ed-0edc-442e-96b6-92f46537269d&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=e0dac7ab&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao clicar em atualizar, caso as classes estejam todas configuradas corretamente com o percentual de liberados, a tela abaixo será aberta.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FWPKHMOwyQJPgvTpXiXzt%252FChecagem%2520classes.png%3Falt%3Dmedia%26token%3D6fb0b964-e2fd-46e2-a809-bb54f90e60d1&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=621122fb&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Na tela de configuração de classes, é necessário verificar os parâmetros de atualização de preços de todas as classes. Caso seja necessário ajustar os parâmetros de atualização, deve clicar no botão ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FF6dicsg9EDK5emWoBIKC%252FBotao%2520marcar.png%3Falt%3Dmedia%26token%3D19a1d018-754e-4dee-ab59-25ce9d340fbe\&width=300\&dpr=4\&quality=100\&sign=cdec15e3\&sv=2) e o cadastro de classes será aberto. Na tela de cadastro de classes, devem ser marcados (para atualizar) ou desmarcados (para não atualizar) os parâmetros **Atualizar Preço Custo** e **Atualizar Preço Venda** de acordo com a necessidade do cliente. Após o ajuste, clicar em gravar.

**Observação:** a atualização de preço de custo não é muito recomenda, pois o preço de fábrica definido pelo órgão responsável, pode ser diferente do preço que o cliente está acostumado a comprar os medicamentos. Além disso, caso seja atualizado o preço de custo, o valor de custo médio será alterado, fazendo com que o cliente fique sem o controle do real custo dos produtos.​&#x20;

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FGZtPcW9hQ5qgOlERIqgu%252FClasses.PNG%3Falt%3Dmedia%26token%3D54796a52-8966-4135-ada3-b7ec1ad8e78d&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=720472cc&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após a configuração das classes, o processo de atualização pode seguir.

**Observação:** caso o cliente queira apenas que sejam incluídos os novos produtos, sem realizar nenhuma atualização de preço dos produtos já existentes, os parâmetros de atualização das classes devem estar desmarcados e o processo deve seguir normalmente.​

Abaixo serão explicados os campos utilizados na tela de configurações de classes no processo de atualização.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FSO5kd1XxO80lBXDmC0YQ%252FConfiguracoes%2520de%2520classes.png%3Falt%3Dmedia%26token%3D6a8aae79-10d9-4e9e-9a98-1d317f4ab27f&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=895c0dba&#x26;sv=2" alt=""><figcaption></figcaption></figure>

1. Nome da classe;
2. Parâmetro atualiza preço de custo: apenas as classes que este campo estiver com a informação SIM, vai atualizar;
3. Parâmetro atualiza preço de venda: apenas as classes que este campo estiver com a informação SIM, vai atualizar;
4. Porcentagem de liberados da classe;
5. Botão para acessar o cadastro da classe;
6. Botão de checagem da classe.

Após verificar a configuração de atualização de preço de todas as classes, todas elas devem ser checadas. para isso, deve utilizar a tecla **\[ + ]** no campo ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FVVACMg7AUnpSYQwBmJ0Y%252FBotao%2520desmarcar.png%3Falt%3Dmedia%26token%3Dc0da6df1-2dca-43a4-b894-9a18c0556c10\&width=300\&dpr=4\&quality=100\&sign=386a4ab6\&sv=2). Após a checagem, o campo ficará da seguinte forma: ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FXURNIWpWuInZVSoqp4Xf%252Fbotao%2520marcado.png%3Falt%3Dmedia%26token%3Df3f11fb1-1a0d-4e94-a6e0-3f136d1ae8a5\&width=300\&dpr=4\&quality=100\&sign=d98f174b\&sv=2).

Com todas as classes configuradas e marcadas, clicar em ok e será exibida a mensagem de alerta abaixo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FTvNu8rgvFX4TvgTnqSks%252Fmensagem%2520confirmacao%2520atualizacao.PNG%3Falt%3Dmedia%26token%3D88718cea-ec2c-4fbf-a0e3-78cefc9a5327&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=4c29c1c1&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao clicar em sim, será exibida a mensagem de confirmação de início do processo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FYWbug6CclfkV3AsrH5BJ%252FConfirmacao%2520do%2520inicio%2520do%2520processo.PNG%3Falt%3Dmedia%26token%3D87a7b698-d101-4718-9081-0d0b08a39d7d&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=d4d2b72d&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Antes de iniciar, de fato a atualização de preços, o sistema realiza um backup dos produtos que serão atualizados, para que seja possível cancelar a última atualização, se necessário.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FrdHhfHaR621O0tdd9DO0%252FBackup%2520atualizacao.PNG%3Falt%3Dmedia%26token%3De07d5358-0862-4b3c-90f5-e319fc537838&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=ada88613&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após iniciar a atualização, os campos Produtos Novos Incluídos e Produtos Desvinculados serão preenchidos com a quantidade de produtos para seu respectivo status. A barra de progresso irá mostrar a porcentagem do processo de atualização.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F9v63yTuNtPjjWfTgO8SQ%252FAtualizando%2520produtos.PNG%3Falt%3Dmedia%26token%3D7733a082-bf63-485b-8c42-32565011a938&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=ecb9b32d&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao finalizar da atualização, será apresentada na tela a mensagem de atualização concluída e os preços já estarão atualizados.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FdyypQZIU5Lp3aeWgjTQE%252FProcesso%2520concluido.PNG%3Falt%3Dmedia%26token%3Dd7feeed6-ad73-4b99-b859-32b0e050f01b&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=927b066e&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após todo o processo, serão gerados alguns relatórios na pasta MBHSist do Terminal Administrador, que serão explicados a seguir.

• **Excluidos\_Att:** relatório dos produtos que foram excluídos da ABCFarma;

• **Produtos\_Novos:** produtos que foram incluídos na ABCFarma;

• **Mudanca\_CodAt:** produtos que tiveram alteração de código da ABCFarma;

• **Produtos-Descontos-Removidos:** produtos que houveram preço com desconto removido. Isso acontece quando o preço com desconto cadastrado no sistema fica menor que o preço de venda do produto ao final da atualização de preços.

***

**Assinantes ABCFarma**

Esta opção é utilizada apenas para clientes que possuem assinatura com a ABCFarma, nesse caso eles devem possuir um usuário e senha que realizam o acesso ao portal da ABCFarma.

A atualização utilizando esta opção é igual a atualização da lista geral, diferenciando apenas o modo de busca do arquivo de atualização, que dessa forma, será diretamente da ABCFarma.

Ao acessar o módulo, será aberta a tela, como mostrada abaixo, sendo necessário clicar em atualizar.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FOqIrkcSbGQ6QIJQHhTuk%252FTela%2520inicial.PNG%3Falt%3Dmedia%26token%3Df5f48726-c26e-4d37-b304-720621c995e7&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=fe0a3643&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Na próxima tela, deve ser inserido o CNPJ e senha do estabelecimento de acesso ao Portal da ABCFarma e clicar em Processar.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F2kLciXS9dbTiCHbBnIte%252FAssinante.PNG%3Falt%3Dmedia%26token%3D9a7e0dff-b311-42ca-9b1e-644ecaf37e54&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=472f0035&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após os passos anteriores, a atualização será realizada normalmente, assim como, a atualização geral de preços.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FvUEcTg9WaK07R18j2ySy%252FAtualizando%2520produtos.PNG%3Falt%3Dmedia%26token%3D711f2362-64b6-4515-b729-bce4f8bd1756&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=77a92207&#x26;sv=2" alt=""><figcaption></figcaption></figure>

***

### Distribuidora Santa Cruz <a href="#distribuidora-santa-cruz" id="distribuidora-santa-cruz"></a>

Esta opção é utilizada para realizar atualização de preços dos produtos da ABCFarma disponibilizada pela Distribuidora Santa Cruz. Nesse caso, essa atualização será apenas dos produtos pertencentes a Distribuidora Santa Cruz e não é a atualização oficial da ABCFarma, ou seja, posteriormente, a atualização da ABCFarma deve ser realizada normalmente.

**Observação:** a atualização de preços da Santa Cruz é realizada de acordo com o código de barras do produto, de acordo com o cadastro, ou seja, apenas produto que possuem código de barras válido no cadastro serão atualizados.

Ao clicar no menu Distribuidora Santa Cruz, é aberta a tela abaixo, sendo necessário clicar em atualizar para iniciar o processo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F72YfvaoQ4wvJGicYpbit%252FTela%2520inicial.PNG%3Falt%3Dmedia%26token%3Db978ff5a-bc96-4bbe-ab1e-a4717c0c8852&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=44dfb765&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após clicar em atualizar, será aberta uma nova tela para selecionar o arquivo de atualização. Após selecionar o arquivo, clicar em Abrir para iniciar o processo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F7yXOcFp6fJqjepWMEAj6%252FSelecionar%2520arquivo.PNG%3Falt%3Dmedia%26token%3D6d320fe3-800a-46cb-803f-1a5cce621e7d&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=bf0ed583&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao finalizar da atualização, será apresentada na tela a mensagem de atualização concluída e os preços já estarão atualizados.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fdx5pRrrqCDO1mwsm5De7%252FAtualizacao%2520concluida.PNG%3Falt%3Dmedia%26token%3Dff659932-e006-4000-aec6-3611b0558798&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=800cbf8f&#x26;sv=2" alt=""><figcaption></figcaption></figure>

***

### Cancelamento de última atualização de preços <a href="#cancelamento-de-ultima-atualizacao-de-precos" id="cancelamento-de-ultima-atualizacao-de-precos"></a>

A opção de cancelamento de última atualização pode ser utilizada em todos os modos de atualização de preços explicadas anteriormente.

Para realizar o cancelamento, é utilizada a tecla **F2** na tela inicial de cada opção e será aberta a tela, como mostrado abaixo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fprep4SB56HAElCc2haKs%252FTela%2520inicial%2520cancelamento.PNG%3Falt%3Dmedia%26token%3De26feb26-c91b-417c-9770-53b5720c0b7d&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=bcfc0f1b&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Para iniciar o processo é preciso buscar um dos produto que foi realizada a atualização incorretamente e clicar em verificar.

**Observações:**

* A busca do produto pode ser por código interno ou descrição;
* A busca pelo produto é apenas um parâmetro para verificar a atualização anterior, mas o cancelamento será de todos os produtos atualizados anteriormente.

Após buscar o produto, serão exibidas as informações de data e hora da atualização e preço de custo, venda e desconto do produto antes da atualização. Caso as informações estejam corretas, clicar em cancelar atualização e será gerada uma mensagem que deverá ser confirmada.

&#x20; Após a confirmação da mensagem, aguardar o processamento e ao final será gerada uma mensagem de conclusão.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FKObLVvP7GD2TiKSz95RG%252FMensagem%2520confirmacao.PNG%3Falt%3Dmedia%26token%3D44999bbc-2441-4860-9941-b07f23f00f5f&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=f5025026&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FwprGqfNl8lgcmduhrU22%252FProduto%2520cancelamento.PNG%3Falt%3Dmedia%26token%3Deea76123-5966-44ec-af27-fbc034acf472&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=26b12b2e&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F3V3Jo9dkj4VIMTjLl9vO%252FConcluido.PNG%3Falt%3Dmedia%26token%3D94a57e23-a418-44f9-8564-bd5f86c50287&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=c60d0848&#x26;sv=2" alt=""><figcaption></figcaption></figure>

O cancelamento de atualização ainda gera um log que poderá ser visualizado no relatório de registro de eventos.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FETWni2mRpPCGAc7QT7vP%252FRegistro%2520de%2520eventos.PNG%3Falt%3Dmedia%26token%3D9cb273f9-14ed-4ae7-a97d-182dd52caec5&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=302fdf64&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

### Alternar entre Filiais <a href="#alternar-entre-filiais" id="alternar-entre-filiais"></a>

{% tabs %}
{% tab title="Alternar entre Filiais" %}
Este módulo é utilizado para acessar Filiais em lojas que são integradas e/ou possuem acesso online.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FsJL5auUoEnAJe4zNtPBB%252Finicial.png%3Falt%3Dmedia%26token%3D6d84669e-6697-4539-b545-7aad16c7c3a0&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=a4538c89&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Para acessar uma loja, é necessário selecionar a mesma e logo após clicar em ok. O sistema tentará estabelecer conexão com a loja e caso esteja tudo certo, a alternância será concluída.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FpD0RQCiUSQwdYBRoYf3d%252FAlternar.png%3Falt%3Dmedia%26token%3Dcdbf045e-cd2f-4dca-a099-9a1dab53a39c&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=ce457ec4&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após alternar para outra loja, o símbolo ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FGCJBpe3OKyCDu52orPYo%252FSimbolo%2520alternar.png%3Falt%3Dmedia%26token%3Dfa3a1926-3b34-493e-b1dd-15153b06fec2\&width=40\&dpr=4\&quality=100\&sign=a78b1a61\&sv=2) é adicionado e o nome da loja é alterado no rodapé do sistema, para identificar que o processo de alternância entre lojas foi concluído.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FBKpxkjhjT4xnSCwItv2j%252FAlternado.png%3Falt%3Dmedia%26token%3Dcb51d67b-7e0a-46eb-a33c-2ca13d595337&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=790cdf3f&#x26;sv=2" alt=""><figcaption></figcaption></figure>

No processo de alternar entre filiais, alguns módulos ficam inativos, ou seja, não é possível realizar o processo utilizando a alternância entre lojas. São eles:

• Suporte técnico

• Pré-vendas

• Parcelamento de clientes

• Transferência entre lojas

• Inventário

• Atualizar

• Parâmetros Filiais

• Digitalizar Documentos
{% endtab %}
{% endtabs %}

**Parâmetros Filiais - Acesso Remoto**

{% tabs %}
{% tab title=" Acesso Remoto" %}
Esta opção é utilizada em casos em que o sistema é instalado em um computador remoto, ou seja, um computador fora da loja que irá acessar o sistema da mesma. Neste módulo é possível autorizar e excluir um terminal remoto.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FeRX5lE7yze5QYarTloS2%252FAcesso%2520remoto.png%3Falt%3Dmedia%26token%3D665e025e-2c16-4416-9b30-f151c39dacd5&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b5143b2e&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao acessar o módulo, aparecerá todos os terminais remotos cadastrados. Para autorizar o terminal de acesso externo é necessário pressionar a tecla F2 e confirmar a mensagem seguinte. **Observações:**

* A autorização deverá ser feita por um atendente da loja;
* A quantidade máxima permitida de terminais remotos são 4 por loja.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FghaSDNfLAPTnXEZ85h7z%252FConfirmacao%2520de%2520autorizacao.png%3Falt%3Dmedia%26token%3D98748d33-a6a1-4e43-b0f7-4bd4a305f3c4&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=54270fa0&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FlT2GZ1GcHHSXamr7TdEw%252FAutorizar%2520terminal.png%3Falt%3Dmedia%26token%3D62738090-5c39-43fd-a16d-5743a670ba94&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b8141d66&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após o terminal ser autorizado, o nome do atendente que realizou o processo é incluído no grid.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FEFyQ7UnIvYeCepqCxHOt%252FTerminal%2520autorizado.png%3Falt%3Dmedia%26token%3D1f3c7c40-5d34-46f6-b4de-423f74092701&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=e83797da&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Para excluir um terminal remoto, é necessário selecionar o mesmo e utilizar a tecla Del.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F1NMEdbWmpPQmWHqojp4m%252FExcluir%2520terminal.png%3Falt%3Dmedia%26token%3D9b6bf181-081a-4005-8eef-dd0c933e6747&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=4b0bed50&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Parâmetros Filiais - Cadastro Filiais <a href="#parametros-filiais-cadastro-filiais" id="parametros-filiais-cadastro-filiais"></a>

{% tabs %}
{% tab title="Cadastro Filiais" %}
Módulo utilizado para cadastrar todas as lojas integradas que pertencem a mesma rede.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FMNboYhaSxLUA9GyMGuQn%252Finicial.png%3Falt%3Dmedia%26token%3Dae9c1d22-5fae-40d7-bcba-24cbd7dc95d8&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=1898fc4&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Cadastro de Matriz <a href="#cadastro-de-matriz" id="cadastro-de-matriz"></a>

Para realizar o cadastro da Matriz, é necessário que o parâmetro Estab. Administrador esteja marcado, ou seja, a matriz irá administrar todo o cadastro de produto. O campo código deve ser preenchido com o número 1. O campo Nome do estabelecimento deve ser preenchido com o nome da loja. O Endereço do Host, deve ser preenchido com LOCAL. O campo Cpf/Cnpj deve ser preenchido com o CNPJ da loja. Com todas as informações preenchidas, clicar em Gravar para que as informações sejam salvas.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FO4fWk9FtNo8FFJGntntK%252FCadastro%2520matriz.png%3Falt%3Dmedia%26token%3D2e5de9c9-7525-44e7-b029-261fe5cf23d4&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=8eb27434&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Cadastro de Filial <a href="#cadastro-de-filial" id="cadastro-de-filial"></a>

Para realizar o cadastro de Filiais, o parâmetro Estab. Administrador ficará desmarcado. O campo código deverá ser preenchido com o número sequencial ao número da matriz. O campo nome do estabelecimento deve ser preenchido com o nome da loja. O endereço do host é preenchido com o IP do servidor da loja. O campo Cpf/Cnpj (5) deve ser preenchido com o CNPJ da loja. Com todas as informações preenchidas, clicar em gravar para que as informações sejam salvas.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fjms97xQaEfwO874m7BoW%252FCadastro%2520Filial.png%3Falt%3Dmedia%26token%3D8bcc4bc6-ad05-4f7e-8b5d-94656627a7d4&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=518e1969&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Exclusão de registro <a href="#exclusao-de-registro" id="exclusao-de-registro"></a>

Caso seja necessário excluir um registro, é necessário pesquisar a loja pelo código, obrigatoriamente, e clicar em Excluir.\

{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

### Parâmetros Filiais - Sincronizar cadastro Filiais <a href="#parametros-filiais-sincronizar-cadastro-filiais" id="parametros-filiais-sincronizar-cadastro-filiais"></a>

{% tabs %}
{% tab title="Tab 1" %}
Módulo utilizado para sincronizar as informação das lojas cadastradas no módulo de integração no controle interno DMASTER. Ao utilizar este módulo, as informações que estão no módulo de integração no cadastro do cliente no controle interno DMASTER serão exportadas para o sistema do estabelecimento, sendo assim, as informações das lojas pertencentes a rede ficarão iguais no controle DMASTER e no sistema da loja.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FTA89sw9V3SWLmuhWLS6X%252FInicial.png%3Falt%3Dmedia%26token%3D86745994-cf02-4b72-97ba-1d1598cae206&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=cf67a848&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após a conclusão do processo, será exibida a mensagem abaixo.

\


<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FaDevSYdzcWgekqWHUUiH%252FSincronizacao%2520realizada.png%3Falt%3Dmedia%26token%3D6e770fea-0e53-4e44-9ddc-7ed6a38f5c4b&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=88c76749&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

### Empresa - Atualizar Dados <a href="#parametros-filiais-cadastro-filiais" id="parametros-filiais-cadastro-filiais"></a>

{% tabs %}
{% tab title="Atualizar Dados" %}
Esta opção é utilizada para atualizar os dados cadastrais do cliente de acordo com o controle interno DMASTER. Caso o cliente precise atualizar alguma informação cadastral para que seja alterada no sistema, o ajuste é realizado no controle interno DMASTER e ao utilizar esta opção, a informação alterada será importada para o sistema.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Ft3GeYN5j0O5LrzCU78ZD%252FAtualizar%2520dados.png%3Falt%3Dmedia%26token%3Dbe196a48-feae-43c8-9fa1-57d4a9adf209&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=e53c41c0&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

### Empresa - Visualizar Dados <a href="#empresa-visualizar-dados" id="empresa-visualizar-dados"></a>

{% tabs %}
{% tab title="Visualizar Dados" %}
Esta opção é utilizada visualizar os dados cadastrais do cliente de acordo com o controle interno DMASTER.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FSF1KaYpyvDw62iFi3bfM%252FVisualizar%2520dados.png%3Falt%3Dmedia%26token%3De90f5ef0-cbb0-469a-8c2c-7d1e323b624b&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=fc98a301&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Ao clicar na opção, é exibida a tela com todos os dados cadastrais do estabelecimento, sem possibilidade de alteração.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fj4ec6uGoDQYmKDZO7yUt%252FTela%2520visualizar%2520dados.png%3Falt%3Dmedia%26token%3D11568a13-a669-40f3-a7dd-336433269f2f&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=46f93f3a&#x26;sv=1" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Empresa - Certificado Digital & NFCe <a href="#parametros-filiais-cadastro-filiais" id="parametros-filiais-cadastro-filiais"></a>

{% tabs %}
{% tab title="Certificado Digital & NFCe" %}
Esta opção é utilizada para visualizar ou importar informações relacionadas ao Certificado Digital e NFCe.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FCpiqdnFm4CjJicvYSXHC%252FCertificado%2520digital%2520e%2520nfce.png%3Falt%3Dmedia%26token%3Df4bdd7e3-0eec-453a-b78c-03419eba36fa&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=abb1808b&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Nesse módulo, será possível inserir as informações de ID Token e código CSC e importar o certificado digital do estabelecimento utilizados para o sistema NFCe.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fv8tlyF5HsgPAxLyG8o6B%252Finformacoes%2520certificado.png%3Falt%3Dmedia%26token%3Df78968cc-afa9-45bf-9eb4-88f07b709676&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b3d8fdbe&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Para importar o certificado digital modelo A1, o arquivo já deve estar no computador. Clicar no botão ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FnonQY5fno8fJ90G0dGZx%252Fbotao%2520importar%2520certificado.png%3Falt%3Dmedia%26token%3Da90e0d7e-bd38-4c20-abeb-de2763312e64\&width=300\&dpr=4\&quality=100\&sign=96e6483f\&sv=1) , e na próxima tela, buscar o arquivo e clicar em Abrir.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fhhx3F3LR49d5MnmNaKqo%252FProcurar%2520arquivo.png%3Falt%3Dmedia%26token%3D2bbd6cb5-c1f9-497b-a03a-acfc7f567e10&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=15fc218a&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Após buscar o certificado digital, inserir a senha do mesmo e clicar em carregar, para que as demais informações sejam preenchidas automaticamente. Com todas as informações preenchidas corretamente, clicar em gravar e aguardar o processo ser concluído.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FIdiQtOatlwm2OiUt8gN3%252FInformacoes.png%3Falt%3Dmedia%26token%3Daf5a2bc3-28a4-4454-bfc4-2141d66569dc&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=2676ad21&#x26;sv=1" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**Observação:**</mark> o processo de gravação pode ser demorado, pois o sistema precisará enviar os dados da loja para a DMASTER e para o Portal Invoisys. Esse processo depende da conexão do estabelecimento.\

{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

### Digitalizar documentos <a href="#digitalizar-documentos" id="digitalizar-documentos"></a>

{% tabs %}
{% tab title="Digitalizar documentos" %}
Módulo utilizado para auxiliar no arquivamento de documentos digitalizados de forma organizada referente às vendas de Farmácia Popular. Será usado juntamente com o processo de venda de Farmácia Popular, com o objetivo de arquivar e consultar documentos, receitas e cupons vinculados necessários em caso de auditorias do DATASUS, evitando que estes documentos tenham que ser impressos e arquivados fisicamente na loja.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FVY5m1fkOixdUw1PkzY2a%252Finicial.png%3Falt%3Dmedia%26token%3Dc77b2720-6b48-41b1-9a85-460c7c6620c7&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=82e3eb01&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Informações <a href="#informacoes" id="informacoes"></a>

* O cliente já deve possuir a impressora para escanear os documentos, e a mesma já deve estar instalada no computador;
* A extensão da imagem escaneada deve ser (.JPG);
* Para utilizar o módulo de digitalização, o documento já deve estar digitalizado e salvo em uma pasta compartilhada;
* Ao selecionar uma imagem e associar ao cliente, a mesma será excluída da pasta em que foi digitalizada e ficará salva como arquivo PDF em **C:\MBHSist\DMReceitas (essa informação não deve ser passada para o cliente)**.
* O módulo de digitalização de documentos pode ser acessado por duas formas: pelo menu **utilitários** e no módulo de venda de Fármacia Popular.

#### Configuração <a href="#configuracao" id="configuracao"></a>

Para configurar a digitalização de documentos, deve acessar o **DMConfigurações** e clicar na opção **Scanner Receitas**.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FUXQpWDxFte4bI40KJQm2%252FConfiguracao.png%3Falt%3Dmedia%26token%3Deb4e4d93-5dde-4adc-bfeb-96f640ec22e2&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=985900bc&#x26;sv=1" alt=""><figcaption></figcaption></figure>

Após o passo anterior, deve inserir o caminho da pasta onde as imagens serão salvas após a digitalização.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fcd8dz46qJiN1oIqrU7uu%252FPath.png%3Falt%3Dmedia%26token%3Daf2d844c-915a-46c0-8272-5e58e2e4e784&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=ec01d7c7&#x26;sv=1" alt=""><figcaption></figcaption></figure>

#### Utilização <a href="#utilizacao" id="utilizacao"></a>

Na aba de digitalização, é possível associar receita, documento ou cupom ao cadastro de um cliente. Para isso, é necessário: pesquisar o cliente através do CPF e utilizar a tecla Enter ou clicar em pesquisar. Com os dados do cliente preenchidos, selecionar o tipo de digitalização: receita, documento ou cupom. Se o tipo de digitalização for documento ou cupom apenas marcar a opção desejada e clicar em gravar. Se o tipo de digitalização for receita é necessário inserir o CRM ou RMS, selecionar UF, inserir a data de emissão da receita, marcar a opção anticoncepcional, se for o caso da receita e clicar em gravar.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FLkVpnsVsbmfXcPTGtVui%252FAba%2520digitalizacao.png%3Falt%3Dmedia%26token%3Dc3167ceb-f962-4328-8603-10df45c3a0e9&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=978800c9&#x26;sv=2" alt=""><figcaption></figcaption></figure>

A imagem que aparece ao lado é a que será associada ao cadastro. Caso queira selecionar outra imagem, é necessário utilizar os botões e para voltar ou avançar as imagens. Caso seja necessário excluir uma imagem, é necessário utilizar o botão ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FFxSHPu8ZNohlKKLn6jG1%252FExcluir.png%3Falt%3Dmedia%26token%3D8719262f-38e3-47d2-bb4a-ff813cd81b9b\&width=88\&dpr=4\&quality=100\&sign=e0f78537\&sv=2). Lembrando que este botão apenas exclui o arquivo digitalizado da pasta e não exclui arquivo já associado ao cadastro do cliente.&#x20;

<mark style="color:red;">**Observação:**</mark> ao associar um arquivo ao cadastro de um cliente, a imagem não irá aparecer na tela de digitalização, apenas na pesquisa do cadastro do cliente.

A aba de Pesquisa, é utilizada para verificar os arquivos digitalizados para o cliente. Para isso, é necessário digitar o CPF do cliente, utilizar a tecla Enter e o nome será preenchido. Após o processo anterior, todos os arquivos associados ao cliente serão mostrados no grid. Caso a tela seja aberta ao fazer uma venda de Farmácia Popular, é necessário clicar sobre o registro de receita e clicar em selecionar.

\


<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FubL4ZemDzLvz4WLw0RV6%252FPesquisa.png%3Falt%3Dmedia%26token%3Dd743aefc-36d9-4822-8b84-183eac91aec7&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=a7a1d2cf&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

### Assinatura do sistema <a href="#assinatura-do-sistema" id="assinatura-do-sistema"></a>

{% tabs %}
{% tab title="Assinatura do sistema" %}
Módulo utilizado para retirar boleto de assinatura do sistema, mensalmente.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FEZ5W2x02mJB63q5KIdxv%252Finicial.png%3Falt%3Dmedia%26token%3Db834747a-cc92-44b8-9af9-938779b4c61f&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=a65c869e&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao acessar o módulo é gerada uma mensagem de confirmação, sendo necessário clicar em Sim.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FsaaBAFc3AD9vaUGdy59S%252FConfirmacao.png%3Falt%3Dmedia%26token%3Db77a79dc-3102-4ff7-a1d9-e4d628898f87&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=efbfb42b&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Caso o cliente não tenha nenhum boleto em aberto é gerada a seguinte mensagem.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FlO40vjOobmNT2vG4CHYb%252FNenhum%2520boleto%2520em%2520aberto.png%3Falt%3Dmedia%26token%3D5c325d7d-ef4c-4bd1-844b-c89872cec126&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=9af267f3&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Caso o cliente tenha boleto em aberto, o mesmo é aberto no leitor de PDF ou no navegador de internet.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FG6Ys0bqi49B3Kbn2Emns%252FBoleto.png%3Falt%3Dmedia%26token%3Da64ff5a9-7c71-4b3b-9ae5-71b9e288ef11&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=af7d026b&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

***

### Informações Importantes <a href="#informacoes-importantes" id="informacoes-importantes"></a>

{% tabs %}
{% tab title="Informações Importantes" %}
Módulo utilizado para visualizar as informações e/ou avisos disponíveis pela DMASTER através de banners.



<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F0jgxfaOgF0Q3QGAJU6V8%252FInicial.png%3Falt%3Dmedia%26token%3D612d6279-5569-42f6-b587-9f189e5a4ab3&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=2000b490&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Ao clicar no módulo, caso exista banner disponível, o mesmo poderá ser visualizado.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FkN1c0AACDnV51uErtGFm%252FBanner.png%3Falt%3Dmedia%26token%3D157d966a-f6e4-467d-9d06-8639e8b3c832&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=8153db81&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}







