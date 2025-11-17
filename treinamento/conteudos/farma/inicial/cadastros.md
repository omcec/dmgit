# Cadastros

## Cadastros

<details>

<summary><mark style="color:red;">*</mark> USUÁRIOS &#x26; ACESSOS</summary>

**Esse módulo é para cadastrar todos os usuários que usarão o sistema. Aqui, você também consegue alterar e inativar um usuário existente caso ele não faça mais parte do quadro de funcionários.**

1. Fazer o cadastro do cliente como usuário.
2. Verificar o parâmetro **Marcar Todos**.
3. Caso o cliente for usar **Farmácia Popular**: informar sobre o campo da **Senha F. Popular** e a obrigatoriedade do **CPF** para esses casos.
4. Questionar se o cliente **irá gerenciar as entregas pelo sistema**, em caso positivo, explicar o **parâmetro Entregador**: já existe um cadastro para representar todos os entregadores. Ou ele pode cadastrar cada entregador para uma gestão melhor das entregas.
5. Explicar o parâmetro **Inativo** e botão **Marcar todos**.
6. Aconselhar a **inativar o usuário Atendente**, ou pelo menos trocar a senha por estar com uma senha padrão para todos os clientes.
7. Informar que cadastrar um **usuário sem marcar nenhuma opção** na aba **Controle de Acessos** é ideal para um **atendente** que vai ficar apenas no **caixa** e para o perfil de **entregador**.
8. Logo em seguida sair do sistema e logar com o usuário dele.
9. Questionar se quer cadastrar outro usuário.
10. Informar ao cliente sobre os parâmetros de **Controle de Acesos** e fazendo analogia de que a coluna da Seção equivale aos módulos do sistema para o cliente ter noção.

</details>

<details>

<summary><mark style="color:red;">*</mark> CLASSES</summary>

A classe serve para definir a que grupo pertence um determinado tipo de medicamentos/produtos. Inclusive, quando você cadastra um produto manualmente pelo módulo de **Cadastro** de **Produto**, é obrigatório escolher a qual classe ele deverá pertencer.

1. O sistema já possui algumas **classes cadastradas** (lembrar de fazer a pesquisa com \* para aparecer todas as classes da lista).\
   As classes já cadastradas são: **Alimentos, Controlado, Ético, Fracionado, Genérico, Kit de produtos, Liberado, Perfumaria, Similar, Varejinho**.
2. Quando você for **cadastrar uma classe**, você já deve colocar o nome que você quer no campo **Descrição**, marcar o parâmetro **Classe Ativa** e **Gravar**. É o mínimo que o sistema pede.
3. Aqui também é possível cadastrar uma **subclasse para subdividir** e fazer um micro gerenciamento.
   * **Por exemplo**: dentro da Classe Perfumaria, você pode cadastrar uma subclasse de Shampoos e outra com o nome Hidratantes. Ou nos casos dos medicamentos que sejam Genérico e Controlado ao mesmo tempo, você pode criar uma subclasse Controlado ou uma subclasse Genérico para ter um melhor gerenciamento.
   * Mas a **subclasse não estará vinculada a classe**, pois ela poderá ser usada por outras classes também.\
     Isso é bom para organizar, por exemplo, diferentes comissões e descontos só para aqueles produtos daquela subclasse.\
     Essa separação de subclasse você vai definir em **Cadastro dos Produtos**. Quando a gente for ver como cadastrar um produto, posso te mostrar.
4. A configuração do desconto não é fixo, é o desconto máximo permitido. O percentual máximo de desconto é responsável por limitar o usuário de conceder um desconto na venda além do estipulado pelo gestor do estabelecimento, caso ultrapasse o limite será solicitado o usuário e senha de quem contenha a permissão **"Liberações - Desconto superior ao permitido".**\
   O percentual informado neste campo irá valer para todos os produtos da classe, exceto os que contenha esta informação no cadastro de produto. Caso tenha informação de desconto no cadastro do produto, essa informação será priorizada.
5. Já o campo de **Comissão x Desconto** serve para, justamente, definir a porcentagem de comissão conforme a porcentagem de desconto.\
   Ela é inversamente proporcional:
   * Quanto maior o desconto, menor a comissão.
   * Quanto maior a comissão, menor o desconto.
   * Ou seja, você pode definir que o atendente dê máximo de desconto e não receber comissão.
   * Ou para que ele receber o máximo de comissão, ele não poderá atribuir nenhum desconto.
   * Mas isso é ajustável, você que define o mínimo e o máximo de desconto e de comissão.
6. Esse parâmetro de **“Ajustar preço de custo” e “Ajustar preço de venda”,** é usado para quando for atualizar os produtos da [**ABCFarma** ](https://site.abcfarma.org.br/lista-da-abcfarma/)que pode ocorrer uma vez por mês. Geralmente a **grande atualização ocorre em Abril.**\
   Quando os novos preços da ABCFarma forem liberados, você consegue fazer a atualização de todos esses produtos pelo sistema de uma vez.\
   O sistema atualizará conforme estiver marcado nesses parâmetros. Se vai ser somente preço de custo, somente preço de venda ou os dois.. Com isso todos os produtos dessa classe serão atualizados conforme esses parâmetros.
7. Já o campo **Liberados**, mostra o percentual aplicado entre o preço de custo e preço de venda dos produtos do ABCFarma que não possui PMC (Preço Máximo ao Consumidor). Geralmente é aplicado 45% no preço de custo, para gerar o preço de venda.
8. <mark style="color:blue;">**O passo abaixo deve ser passado conforme percepção da necessidade do cliente.**</mark>
   * Um detalhe em relação às classes que podem ser criadas, é a **Classe Serviços**.\
     Você pode criar um produto com a descrição de sua preferência e incluir este na Classe Serviços. Com isso, o sistema permitirá informar o valor na hora da venda.

</details>

<details>

<summary><mark style="color:red;">*</mark> FABRICANTES</summary>

* Este módulo serve para cadastrar, inativar ou excluir o Fabricante do produto. Basta colocar o **nome**, marcar a opção **Fabricante Ativo** e gravar. Aqui você também consegue pesquisar no campo código um Fabricante já existente e assim poder inativar ou excluir (caso você ainda não tenha associado ele a um produto).

</details>

<details>

<summary>FORNECEDORES</summary>

O fornecedor já é cadastrado no momento da entrada da NF de forma automática, no entanto, é possível cadastrar um manualmente. Basta preencher todas as informações.

* **Tipo de Cadastro**: informa se o cadastro foi feito manualmente ou por XML na entrada de nota.

</details>

<details>

<summary><mark style="color:red;">*</mark> PRODUTOS</summary>

**Neste módulo é onde poderá fazer o cadastro ou a alteração em algum produto em específico.**

1. O **código do produto** é gerado automaticamente ao cadastrar um produto.
2. Então nesse campo Código é o **campo padrão de pesquisa**. Basta colocar pelo menos três letras para pesquisar ou o \* para carregar todos os itens.
   * ​​​​​​​É possível também colocar o \* entre dois termos de pesquisa, por exemplo: você pode digitar **Parac\*750** para o sistema trazer resultados de Paracetamol de 750mg.
3. Outra coisa, quando você inicia a pesquisa, a princípio, o sistema irá mostrar apenas os produtos ativos. Para mostrar os inativos junto, deve teclar **F5**.
4. Aqui também é possível pesquisar pelo princípio ativo do produto pelo comando **F6**, se a informação estiver no cadastro. (mostrar onde fica a informação do princípio ativo no cadastro do produto).
5. Tem também como pesquisar produtos similares através do **F7**.
6. Loja com integração:
   * Tem o comando **F10** para consultar o **Estoque de Filiais** na tela de Pesquisa. Basta selecionar o produto clicando em cima e teclar F10.
7. No **campo código de barras**, ao dar entrada na nota fiscal, ele será preenchido automaticamente, mas é possível alterar e incluir um outro código de barras, caso o produto tenha mais de um código de barras.
8. **NCM**: Nomenclatura Comum do Mercosul, trata-se de um código estabelecido pelo Governo Brasileiro para identificar a natureza das mercadorias e assim compor o imposto.
9. **CEST**: Código Especificador da Substituição Tributária, estabelece uma forma de identificar e uniformizar mercadorias e bens sujeitos ao regime de substituição tributária que também compõe o imposto.
10. **Registro MS**: Registro do Ministério da Saúde, é o código de identificação do medicamento no ministério da saúde, ele é obrigatório para medicamentos controlados. Caso você não tenha essa informação ou se na caixa do produto não tiver, somente o farmacêutico responsável pelo estabelecimento poderá ajudar para incluir esse dado.
11. **Descrição**: é nome que aparece no momento da venda. 24 caracteres para fracionados.
12. **Princípio ativo**: com esse campo preenchido, é possível fazer pesquisa de produtos digitando o nome do princípio ativo.
13. **Informações adicionais do produto**: as informações contidas aqui, poderão ser visualizadas no caso de emissão de NFe.
14. **Código ABCFarma**: se tiver a **numeração do código**, quer dizer que pertence à ABCFarma; se tiver a palavra **Extinto**, significa que já pertenceu a ABCFarma e se estiver **Livre** ou **vazio**, quer dizer que não pertence a ABCFarma.
    * Mais para frente vamos ver na entrada de nota fiscal como associar um produto da nota com um já existente caso apresente conflito.
    * <mark style="color:red;">**\***</mark>**&#x20;IMPORTANTE**: o _sistema DMASTER FARMA ao ser implantado no estabelecimento é enviado com uma base cadastral de medicamentos, este medicamentos são de origem da base da ABCFARMA e é de extrema importância que os cadastros dos medicamentos utilizados sejam estes que possuem código da ABCFARMA para que no momento da atualização eles sofram os devidos reajustes._
15. **Localização**: serve para colocar a localização do produto na loja. Em qual armário, ou gaveta, seção ou corredor ou estante... etc.
16. **Custo atual:** valor de compra do produto conforme entrada de NFe , porém é editável.
17. **Custo médio**: valor médio de custo das compras dos últimos 90 dias.
18. **%Markup**: informa o ganho em cima do custo. Exemplo: quantos porcentos você quer ganhar em cima do custo? Se um produto tiver custo de R$ 10,00 e você quiser ter 100% de ganho em cima do custo, o percentual do Markup deverá ser 100%, com isso, o preço final será o dobro do valor do custo, ou seja R$ 20,00.
19. **Lucro**: informa o ganho em cima do custo atual em relação ao preço de venda. Aproveitando o exemplo acima, o lucro neste caso será de 50%, ou seja, a metade do valor da venda refere-se ao custo.
    * Pode-se dizer que no lucro, o caminho é inverso. Se um produto custa R$ 20 e o custo for R$ 10, então quer dizer que você terá 50% de lucro já que o custo é a metade do valor da venda.
20. **Preço:** preço de venda do produt&#x6F;**.**
21. **Questionar se ele vai trabalhar com a F. Popular.** Em caso positivo, explicar os parâmetros da Farmácia Popular.
    * **Preço F.Pop**: ele só deve ser habilitado se o produto for da Farmácia Popular para a venda pela Farmácia Popular ocorrer sem problemas.
22. **Preço c/Desc**: aqui você pode definir o preço com desconto fixo (ou preço promocional) ou, temos um outro módulo que serve para definir o desconto de vários produtos ao mesmo tempo ou todos os produtos de uma classe. Ao realizar o processo pelo outro módulo, o valor com desconto aparecerá nesse campo.
23. **Desc%**: desconto máximo permitido. Prevalece ao desconto da Classe.
24. **Comissão%**: de venda para o atendente. Prevalece ao desconto da Class
25. **Fabricantes**: serve para informar o Fabricante do produto.
    * ​​​​​​​Para colocar um novo, deve cadastrá-lo no **atalho F3**.
26. **​​​​​​​Classes**: serve para informar a Classe, para colocar um novo, deve cadastrá-lo no **atalho** **F4​​​​​​​.**
27. **Subclasses**: não é obrigatório informar a subclasse. Para cadastrar também é no **atalho** **F4**
28. **ICMS**: refere-se a alíquota do ICMS do produto. Neste caso, havendo dúvida, deve ser verificado com Contabilidade a alíquota correta.
29. **CSOSN e CFOP**: são preenchidos automaticamente ao escolher o ICMS, mas é possível alterá-los caso você receba alguma orientação da contabilidade.
30. **Lista PIS/COFINS**: caso não tenha familiaridade também deve ser verificado com a contabilidade. Contudo, existe um padrão:
    * **Lista Positiva** **- Isento**: são os medicamentos em geral.
    * **Lista Negativa** **- Monofásico**: todos os produtos que possuem mistura química, mistura homogênea ou volume do tipo (ML ou Gramas). Exemplos: shampoos, condicionadores, esmaltes, tinturas, praticamente todos os itens de perfumaria.
    * **Lista Neutra - Tributação normal**: produtos plásticos, descartáveis ou a base de algodão. Exemplos: fraldas, absorventes, bicos, mamadeiras, aparelhos de barbear, cotonetes etc.
31. **Imp. União e Imp. Estado**: imposto recolhido. Preenchido conforme no NCM, mas também pode ser alterado. Eles aparecem no cupom fiscal.
    * Caso o campo não esteja atualizando conforme o NCM, deve ser atualizado a tabela no módulo **Atualizar** > **Tabela IBPTax**.
32. **Gr. Sugestão**: o sistema permite sugerir um produto no momento da venda de outro produto. O sistema possui um módulo para criar um grupo que vamos ver mais pra frente. Nisso você coloca o número do grupo aqui em pelo menos dois produtos para que, ao lançar um deles, o sistema indique o outro na hora da venda para você oferecer para o seu cliente.
33. CAMPOS REFERENTE AO FRACIONAMENTO
    * ​​​​​​​Antes do fracionamento, **devemos zerar o estoque** para fazer a contagem correta e não apresentar erro.
    * Marcar o parâmetro **Produto Fracionado**.
    * **Unidade**: somente informativo e para organização do fracionamento.
    * **Qt. Unid. Emb.**: informar a quantidade que vem na embalagem e automaticamente o sistema já informa o preço dividido a quantidade pelo preço do produto no campo fracionamento, mas a descrição e o preço podem ser alterados.
      * Para achar o valor da unidade, multiplicar o preço unitário que quer vender pela quantidade de unidade da embalagem e colocar o resultado no campo **Preço**.
34. **Classe terapêutica**: aqui é para você definir se o produto é Controlado, Sem Controle, ou Não Medicamento.
35. **Tipo de receituário:** obrigatório em produtos controlados. Serve para informar o tipo de receita. Ele fica inabilitado ao selecionar a opção Sem Controle ou Não Medicamento.
36. **Produto ativo**: com esse parâmetro desmarcado, ele sai da lista de pesquisa padrão.
    * Qualquer produto que tenha sofrido qualquer alteração ou movimentação, como uma venda, não será possível **Excluir**, mas você poderá **Inativar**.
37. **Uso contínuo**: com essa opção marcada o sistema, na hora da venda, lhe dá a possibilidade de incluir os dados do cliente e da quantidade que o cliente tem que tomar por dia. Nisso ele calcula conforme a quantidade que ele está levando para dizer até quando vai durar a medicação.
    * Mais para frente vamos ver como extrair o relatório com a relação dos clientes com esse tipo de medicação. Isso é para fazer uma ação de fidelização, campanha ou promoção.
38. **Demanda**: aqui aparece quantidade vendida nos últimos 90 dias.caso você não queira mais vender para o cliente através do convênio ou não queira fazer venda naquele cartão.
39. **UN**: mostra a quantidade do estoque. Em caso de produto fracionado, mostra a quantidade de caixas ou embalagens.
40. **Frações**: mostra as quantidades de frações.
41. **Ult. Alteração:** data da última alteração efetuada no cadastro.
42. **Ult. Compra:** data da última entrada de nota.
43. **Ult. Venda:** data conforme a última venda efetivad&#x61;**.**
44. ​​​​​​​**GRAVAR**

</details>

<details>

<summary>PREÇO POR FILIAL - Integração</summary>

**Quando a loja possui uma filial e o cadastro é integrado, é possível inserir um preço exclusivo da loja.**

1. Acessar **Cadastro** > **Produto** > **Preço por Filial**
2. Seleciona a Filial e clicar em **F1 - Pesquisar**
   * Com isso será carregado todos os produtos já configurados com preço de venda ou promocional exclusivo da filial.
3. Para Configurar um novo preço da loja, basta:
   * Selecionar a **Filial**;
   * Clicar em **Adicionar**;
   * Pesquisar o produto;
   * Clicar na **Venda Filial** e/ou **Prom**. **Filial**, digitar o valor desejado e **Gravar**.

</details>

<details>

<summary>KITS DE PRODUTOS</summary>

Este módulo serve para agrupar produtos para vender em duas quantidades ou mais com um preço promocional. O kit pode ser do mesmo produto (kit simples) ou de produtos diferentes (kit misto).

<mark style="color:blue;">Produto fracionado não pode fazer parte dos kits.</mark>

**Observações**

* O senhor pretende usar este recurso?
  * Caso não, apenas apresente o módulo.

**KIT SIMPLES: mesmo produto.**

1. **Código**: neste campo é onde você pesquisa os produtos. Os três primeiros campos são do cadastro do produto.
2. Em **Descrição do Kit**, você define o nome para o kit que vai aparecer na hora da venda.
3. Mais abaixo você define os valores de desconto:
   * Por %;
   * Por preço da unidade;
   * A quantidade que vai ser vendida no kit;
   * O preço final do kit.
4. No momento da venda, quando você colocar o produto ele vai te dar a opção de vender um ou o kit.

**KIT MISTO: produtos diferentes.**

1. Antes de iniciar aqui, você deve cadastrar um produto com o nome e preço total do KIT que você vai vender e colocar na Classe Kit de Produtos (não precisa definir estoque). Depois de ter criado ele em Cadastro de Produtos, na aba kit misto:
2. No campo **Código do kit**: pesquisar pelo nome ou código do kit criado.
3. No campo **Código**: pesquisar os produtos que você vai inserir no kit.
4. Os valores dos produtos devem somar o total do kit cadastrado, **Preço do kit**.
5. No momento da venda, você pesquisa pelo nome do Kit.
6. Caso você insira um produto pertencente a um Kit, ele apenas informa que existe um kit, mas não dá opção para selecionar e incluir o kit.

</details>

<details>

<summary>SUGESTÃO DE VENDA</summary>

1. A função deste módulo é sugerir um produto ao vender um outro produto. Então quando você for lançar um determinado produto na pré-venda, o sistema irá sugerir um outro produto conforme você definir os produtos dentro do mesmo grupo de sugestão.
2. Primeiro você deve **criar um grupo** dando um nome e clicar em gravar.
3. É possível pesquisar o grupo existente através do campo código.
4. Ir em **Cadastro de Produto**, pesquisar e selecionar o produto que você queira inserir no grupo de sugestão.
5. No campo **Gr. Sugestão**: pesquisar o grupo que você criou e selecione ele.
6. Fazer isso com todos os produtos para dar a mesma sugestão.

</details>

<details>

<summary><mark style="color:red;">*</mark> CONVÊNIOS &#x26; CARTÕES &#x26; PIX</summary>

Este módulo serve para cadastrar todos os meios de pagamento além do dinheiro. Aqui você cadastra os cartões de crédito e débito, pix e convênios.

1. Os dois primeiros convênios são para vendas à prazo, como em um crediário direto para o cliente final ou cliente CNPJ.
2. **Convênio próprio**: com essa opção marcada você cadastra o convênio da loja para o consumidor final, direto para o seu cliente. Pagamento à prazo, parcelado ou não.
3. **Convênio empresa**: neste você cadastra o convênio de parceria com outra empresa. Onde os funcionários dessa outra empresa poderão comprar com você e depois a empresa conveniada irá efetuar o pagamento para você em uma determinada data. Pagamento é à prazo, e pode ser parcelado ou não.
4. **Convênio Entregas**: é bom ter esse cadastro se você for trabalhar com entregas, pois para registrar uma entrega pelo sistema, é necessário ter o cadastro do cliente, e para cadastrar um cliente é obrigatório vincular ele a algum convênio. Então se você não for trabalhar com convênio à prazo ou se não quiser criar um convênio à vista, poderá selecionar esta opção.
5. **Convênio à vista**: é indicado para incluir os clientes fiéis que pagam à vista e você queira ofertar um desconto diferenciado ou simplesmente manter uma base de clientes.
6. No campo código é possível pesquisar um convênio existente para fazer alterações.
7. **Novo Cadastro**: para cadastrar uma forma de pagamento, basta colocar a descrição no campo Nome e:
   * Campos obrigatórios:
     * **Endereço**: em todos os convênios.
     * **Vencimento**: em convênio empresa.

**RESTRIÇÕES**

1. **Bloquear Convênio/Cartão**: caso você não queira mais vender para o cliente através do convênio ou não queira fazer venda naquele cartão.
2. **Acatar Ofertas P/Convênio**: quando habilitado e houver produto com preço promocional, o sistema irá analisar o que será melhor para o cliente final, o preço promocional ou o preço do convênio, e quando desabilitado, sempre efetuará a venda com o preço do convênio caso haja um desconto configurado em Parâmetros Gerais.
3. **Perfil Convênio na Entrega**: serve para aplicar desconto do convênio quando for realizar uma entrega do convênio. Quando desabilitado, o sistema irá ignorar os descontos.

**PARÂMETROS GERAIS**

1. **Desc. Geral**: desconto fixo que será aplicado a todos os produtos quando for vender para um cliente deste convênio em questão.
2. **Multas Atraso:** é cobrado uma vez quando houver atraso.
3. **Juros Atraso:** é cobrado mensalmente quando houver atraso.
4. **Nº cópias cupom**: para cupom vinculado.
5. **Tolerância Atraso**: pode ser considerado o prazo para identificação do pagamento ou um período apenas para você se organizar. Ou também, caso você venha fazer o fechamento dos faturamentos uma vez por semana, pode ser 7 dias.
6. **Carência Vcto:** quantos dias antes do vencimento você quer que a fatura feche.
7. **Dia do Vcto**: vencimento do **Convênio**.
   * Obrigatório para **Convênio Empresa**.
   * Para **Convênio Próprio**, se o vencimento não for preenchido, o sistema atribuirá o "0", com isso os vencimentos ficarão para 30 dias corridos a partir da venda. Contudo, ainda é possível escolher um vencimento direto no cadastro do cliente.
8. **Nº Máximo Parcelas**: cartão de crédito, convênio próprio e empresa.
9. **Imprimir cupom**: refere-se ao vinculado dos cartões de crédito (mostra as parcelas), débito e PIX.
10. **Taxa Operadora**: débito, crédito e PIX. O valor é em porcentagem e para melhor ajustar o saldo\lucro em **Fluxo de Caixa DRE**.
11. **Mensagem Cupom Gerencial**: disponível para edição somente para os convênios próprio e empresa. Mensagem padrão: _Reconheço e pagarei a dívida acima. AGRADECEMOS A PREFERÊNCIA_.
12. **Adquirente TEF (ainda não é compatível com NFCe)**: usado para quem vai vincular o sistema da máquina de cartão com o sistema. (Verificar com a operadora de cartão se eles disponibilizam e como funciona e com o setor comercial).

**CLASSES E OUTROS DESCONTOS**

1. Serve para aplicar um desconto diferenciado para pagamentos à vista ou à prazo para uma determinada classe.
   * Depois do preenchimento, basta **Gravar**.
   * Para vetar para uma determinada Classe que tenha o Desc. Geral configurado, basta colocar zero nos dois campos, **à vista** e no **à prazo**
2. Para **Excluir**, o convênio ou o cartão não pode ter **nenhuma movimentação**, mas lembrando que **é possível bloquear**.

</details>

<details>

<summary><mark style="color:red;">*</mark> CADASTRO DE CLIENTES</summary>

1. Para cadastro de clientes, é **necessário** informar pelo menos o **nome** e o **convênio**.
   * E se for um cliente do Convênio Entrega, é necessário informar o número de telefone.
2. A pesquisa de cliente no momento da venda pode ser feita por **nome**, **matrícula** e **celular** (formato XXXX<mark style="color:red;">**-**</mark>XXXX).
   * Para isso, basta gravar essas informações no cadastro.
3. Para realizar as entregas, é necessário ter o endereço cadastrado e o CPF nos casos em que forem cobrar taxa de entrega. (Requisitos da SEFAZ caso o cliente use o produto 888888)
4. **Cód. Titular**: serve para **indicar um titular** de um **convênio próprio**. Toda vez que o **dependente comprar**, será **lançado na conta do titular**.
5. **Setor**: aqui você pode selecionar o Setor/região do cliente para gerenciar as entregas através dos entregadores mais próximos. O cadastro é feito em **Setores**.
6. **Data de nascimento**: o sistema tem um relatório de clientes que permite você extrair todos os clientes que fazem aniversário em uma determinada data para você poder fazer campanhas/marketing.
7. **Segundo endereço:** do cliente caso tenha outro endereço de entrega.
8. **Convênio**: é obrigatório vincular o cliente a um convênio, seja um à vista ou à prazo.
9. **Limite de crédito**: limite que o cliente poderá usar para comprar na loja e pagar à prazo.
10. **Crédito atual**: este atualiza limite disponível para compra conforme o cliente for comprando e/ou pagando.
11. **Vencimento Fixo/Prazo Dias**: cliente de convênio próprio podem ter seu próprio vencimento. Para isso, deve informar o dia em Prazo/Dias. Para seguir o vencimento do convênio, basta marcar Vencimento Fixo.
12. **Observação**: campo livre para preenchimento de informações que serão exibidas nos módulos de vendas, pré-vendas e parcelamento de clientes.

</details>

<details>

<summary>SETORES</summary>

1. Quando se tem uma estrutura com **Matriz e Filiais**, usamos esta opção de Setores para cadastrar a localização de cada loja.
2. Setores é utilizado para que, ao cadastrar um novo cliente, você poderá informar qual a loja mais próxima do mesmo, para melhor atendê-lo no caso de vendas de entrega.
3. O sistema já possuí alguns setores cadastrados (Centro, Norte, Sul, Leste, Oeste e Centro Oeste), podendo já serem utilizados, bastando apenas selecionar o setor e vincular a filial a ser associada.
4. É possível também, cadastrar novos setores de acordo com a necessidade ou até mesmo editar os já existentes.

</details>

<details>

<summary>NAT. OPERAÇÕES &#x26; PARTILHA ICMS</summary>

1. Aqui é onde você cadastra, exclui ou altera os **códigos tributários** como o **ICMS** e o **CFOP**
   * O sistema já vem com uma base padrão para serem incluídos nos cadastros dos produtos, caso precise.
   * Claro que, qualquer dúvida sobre qual usar, deve ser verificar com a contabilidade.
2. **Natureza de Operação**: geralmente esse código **(CFOP - Código Fiscal de Operações e Prestações)** já vem na nota fiscal e o sistema já possui uma base para fazer a conversão do CFOP de saída do fornecedor para o seu CFOP de entrada. Caso não tenha cadastrado, o sistema informa que não existe um determinado CFOP no cadastrado. Neste caso basta abrir um chamado conosco que passamos a orientação.
3. **Partilha ICMS** ­- caso precise emitir uma nota de venda para outro Estado: selecionar qual o Estado de destino para onde será enviado a NF e posteriormente preencher o percentual ICMS de todos os campos informados.
4. **Alíquota ICMS**: serve para cadastrar um novo ICMS, caso tenha recebido orientação da contabilidade.

</details>

<details>

<summary>TIPOS DE DESPESAS</summary>

1. Serve para cadastrar as despesas da loja para ter um maior controle dos gastos. Como por exemplo: despesa com pessoal, fornecedores de energia, água, internet etc.
2. Este módulo serve para criar e categorizar as demais despesas da loja para ter um melhor gerenciamento das despesas e também saber o lucro real conforme as vendas no relatório de **Fluxo de Caixa DRE** que veremos mais para frente.
   * Informar rapidamente que no módulo **Contas a Pagar** em **Operacional** ele inclui os valores e em **Fluxo de Caixa DRE** para visualizar em relatório com uma visão macro.

</details>

<details>

<summary><mark style="color:red;">*</mark> ENTRADA NF</summary>

1. Neste módulo é possível dar entrada por duas maneiras:
2. **Via Chave**: quando você tiver um certificado digital importado no sistema, basta inserir a Chave que o sistema baixa os dados da SEFAZ.
3. **Via XML**: tem fornecedores que enviam o XML junto com a NF por e-mail. Ou se você baixar o site da SEFAZ é possível importar o XML e todos os dados serão preenchidos. Sites para downloads dos XML:
   * Para baixar nestes sites, será necessário que o certificado digital esteja instalado no computador.
     * [Portal da NFe](https://www.nfe.fazenda.gov.br/portal/principal.aspx)
     * [FSIST](https://www.fsist.com.br/)
4. _Se, e somente se, o cliente questionar, informar sobre a entrada manual._
   * _<mark style="color:red;">Já informar que não é recomendável, pois ele precisará incluir todas as informações, inclusive os dados tributários, o que vai gerar um desgaste de tempo e alta probabilidade de erro.</mark>_
5. Após inserir os dados da NF, os produtos serão carregados no campo abaixo e eles podem ter os seguintes status:
   * <img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FyuS3o5rEplBO61gJTPVD%2Fimage.png?alt=media&#x26;token=9de56b87-9c25-4ca8-a8a8-c1c75ad5d33a" alt="" data-size="line"> : código de barras do produto não encontrado e vai ser necessário cadastrá-lo ou associá-lo no comando F2. Isso ocorre pois o código de barras que veio na nota não é o mesmo que está no cadastro. Mas é possível fazer a associação.
     * Sempre que houver a necessidade de vincular um medicamento, sempre dê preferência aos que possuem o código da ABCFarma. Pois quando houver a necessidade de atualizar os preços de acordo com a tabela da ABCFarma, não ocorra o erro de um medicamento não ser atualizado.
   * <img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FWuAOAdla5hZvVhYK6pp9%2Fimage.png?alt=media&#x26;token=f3519bf0-e83f-48cc-82ee-f2d7a1456008" alt="" data-size="line"> : o produto foi encontrado no cadastro, porém o preço de custo está diferente. Nisso você pode alterar o preço em **F2** ou ignorar em **F3** (caso você queira efetuar o ajuste depois em **Auditoria de NF**). O preço pode ser alterado no campo **Preço Sugerido** diretamente ou no campo **Markup** ou **Lucro**. Quando um é alterado, o outro calcula automaticamente.
   * <img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FH8KUhJ192ZBfT8SNEeAS%2Fimage.png?alt=media&#x26;token=4acbf0bb-6f2f-4423-af22-9aca42e22f55" alt="" data-size="line"> : o produto foi encontrado com preço promocional. Neste caso, ao tentar alterar o preço, o sistema questiona se você deseja manter o desconto ou não.
   * <img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FOZl7VSwzNWXDBKY6bJbX%2Fimage.png?alt=media&#x26;token=2453ee1e-59bf-41ca-88c9-9cf8a4a180cc" alt="" data-size="line"> : quer dizer que o cadastro foi localizado e o preço de custo está igual na nota e no cadastro.
6. Se o cliente estiver com uma nota com poucos produtos, mostrar como alterar os preços dos produtos na entrada da NF.
7. Somente quando todos os produtos estiverem com **status** <img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FOZl7VSwzNWXDBKY6bJbX%2Fimage.png?alt=media&#x26;token=2453ee1e-59bf-41ca-88c9-9cf8a4a180cc" alt="" data-size="line">, a nota poderá ser gravada.
8. **F9 - Material de Uso ou Consumo**: para dar entrada em notas de produtos que serão de uso próprio ou da loja, ou seja, não haverá alteração no estoque de vendas. É indicado para entrada com NF de despesas de materiais de uso: tipo materiais de limpeza, de escritório, bobina\papel de impressora. Esses valores serão contados como despesas e aparecerão no **Fluxo de Caixa DRE**.
9. **F10** - **Ativo Imobilizado**: são itens para bens necessários à manutenção das atividades da loja. Como computadores, móveis. (Bens duráveis)
10. **Notas Fiscais de Bonificação**: são produtos disponibilizados pelo fornecedor para amostras grátis ou brindes.
    * Para este tipo de nota, tem que marcar a opção Bonificação antes de puxar o XML da nota.

</details>

<details>

<summary><mark style="color:red;">*</mark> SUPORTE TÉCNICO</summary>

1. Abertura de chamado via sistema.
2. Horários de atendimento.
3. Classificação da solicitação para resultar na prioridade correta.
4. Abertura de chamado via [site DMASTER](https://dmaster.com.br/abrechamado.asp).

</details>
