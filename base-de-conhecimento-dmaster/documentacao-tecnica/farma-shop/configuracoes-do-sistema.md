# Configurações do sistema

Os sistemas DMASTER FARMA e DMASTER SHOP, possuem parâmetros que podem ser definidos de acordo com a necessidade do cliente. Para realizar alterações nos parâmetros, é utilizado o módulo de configurações do sistema. Para acessar o módulo, é necessário clicar no menu **utilitários** e utilizar as teclas **SHIFT + F12** juntas. Será aberta uma tela solicitando senha do usuário **Admin** (somente esse usuário tem acesso e é utilizado apenas pela Dmaster).

Na seção Autenticação são exibidas as seguintes informações:

* **Nome do Servidor**, de acordo com o **config.ini** da pasta **MBHSist**;
* Senha de acesso ao banco de dados.

Na seção **Configurações** são exibidas as seguintes informações:

* **Número da loja**, que será alterado apenas se a loja possuir integração entre lojas. Nesse caso, cada loja possui um número, que deve ser sequencial;
* **Código da automação**, onde o número **1** refere-se a **DMASTER FARMA** e o **2** refere-se a **DMASTER SHOP;**
* A configuração para desativar produtos sem movimentação há algum tempo, é realizada inserindo a quantidade de dias no parâmetro **"Desativar Produtos S/Mov"**;
* Os parâmetros relacionados a balança, são utilizados apenas no **DMASTER SHOP**, quando o estabelecimento utiliza balança que imprime etiquetas, para que o sistema leia as informações.

Na seção **Parâmetros do Sistema**, é possível visualizar as informações cadastrais do estabelecimento como: CNPJ, telefone e nome fantasia. Esses dados são de acordo com o controle interno Dmaster que são importados no momento da instalação do sistema.

Além dos dados cadastrais, nessa seção também é exibido o nome do computador onde o módulo está sendo acessado e a mensagem que será exibida no final do cupom fiscal impresso no sistema.

Na seção **Parametrização**, é onde serão definidos os parâmetros de acordo com a necessidade do cliente. Se o parâmetro estiver marcado ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FSOqcn0jYWUYUA1Aqq9tj%252Fmarcado.PNG%3Falt%3Dmedia%26token%3D08916f52-ddcd-4a56-9590-df6898c3c5e2\&width=300\&dpr=4\&quality=100\&sign=c0c11aea\&sv=2)significa que está habilitado. Se estiver desmarcado ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FWX3hiWiHPFL0UAyOgDJt%252Fdesmarcado.PNG%3Falt%3Dmedia%26token%3Da780cb93-8dc2-4df5-9532-4b22bc99cef1\&width=300\&dpr=4\&quality=100\&sign=a001d276\&sv=2)quer dizer que está desabilitado. Abaixo serão listados e explicados cada um dos parâmetros.

* O parâmetro ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fc54xhhi6fRHPaSjqfe7I%252FTerminal%2520adm.PNG%3Falt%3Dmedia%26token%3D9e61f77e-acdd-4441-a2da-8fdbfe9a61ac\&width=300\&dpr=4\&quality=100\&sign=517ab352\&sv=2),ficará habilitado apenas no computador da loja que deverá ser aberto o sistema primeiro e será o administrador do sistema.

{% hint style="warning" %}
O parâmetro é habilitado/desabilitado caso a informação de terminal administrador seja alterada no Config.ini da pasta MBHSist.
{% endhint %}

* O parâmetro![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FabIK2UrxP5152C7IEylk%252FPesquisa%2520dinamica.PNG%3Falt%3Dmedia%26token%3Ddfb2a418-5602-40d4-8ed4-50a2e359b4f6\&width=300\&dpr=4\&quality=100\&sign=8ed040a2\&sv=2) , funciona da seguinte forma: se habilitado, ao começar a digitar palavras para realizar pesquisas (confirmar se é apenas produtos), a partir da terceira letra digitada os resultados já surgem. Se desabilitado, os resultados só irão aparecer se, após digitar a palavra desejada for utilizada a tecla Enter.
* O parâmetro![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fd37FAZQcJYpERcoq4Y2T%252FSNGPC%2520integrado.PNG%3Falt%3Dmedia%26token%3D3c0d0577-fc1a-4984-942b-26a024f24723\&width=300\&dpr=4\&quality=100\&sign=9e5470aa\&sv=2), é habilitado quando os sistemas DMASTER FARMA E DMASTER SNGPC são integrados.

{% hint style="warning" %}
Esse parâmetro é habilitado automaticamente após a execução do aplicativo de integração de SNGPC.
{% endhint %}

* O parâmetro ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FY33u7rdMebkjFW5N7DxT%252FCalcular%2520comissao.PNG%3Falt%3Dmedia%26token%3D5843a351-5c22-440f-812c-e7118ac3f564\&width=300\&dpr=4\&quality=100\&sign=346588e6\&sv=2), quando habilitado, ao realizar uma venda de convênio, a comissão é calculada na hora da venda. Quando desabilitado, a comissão é calculada apenas na hora pagamento da conta.
* O parâmetro ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FM2nqlg6AVwc1AiUSbiIR%252FPre%2520venda.PNG%3Falt%3Dmedia%26token%3Dccb3d7dc-aeb7-4c6e-a08a-a3af4ad3daab\&width=300\&dpr=4\&quality=100\&sign=aeafd56b\&sv=2)é utilizado para definir se as vendas realizadas no módulo de pré-vendas serão efetivadas como pedido ou pré-vendas para efetivação no frente de caixa.
* Quando o parâmetro![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FJDMBte1eWEvIEhM6sTAJ%252FPre%2520entrada.PNG%3Falt%3Dmedia%26token%3D5221693e-a98f-4d8b-8762-24fbb4f5d480\&width=300\&dpr=4\&quality=100\&sign=4d073370\&sv=2) está habilitado, o usuário pode realizar pré-entrada de nota fiscal de compra quando necessário.
* Para estabelecimentos que não fazem controle de estoque e desejam realizar vendas de produtos que possuem estoque menor que 0 no sistema, é habilitado o parâmetro ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fxguq6Hur0y6h4JnIheCr%252FVender%2520quantidade%2520maior.PNG%3Falt%3Dmedia%26token%3D32510ef0-cd7f-4098-9113-e2169741c2d7\&width=300\&dpr=4\&quality=100\&sign=9e215477\&sv=2). Com o parâmetro desabilitado, só é permitida a venda no sistema de produtos que possuem estoque maior que 0.
* Para realizar o fechamento do caixa, é necessário informar os valores referente as vendas do dia/turno. Com os parâmetros ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FFEcbVGOU4JYIlKkREinu%252FConferir%2520venda%2520cartao.PNG%3Falt%3Dmedia%26token%3Dde658352-2733-4661-bc70-cb12740e86dd\&width=300\&dpr=4\&quality=100\&sign=4efc662b\&sv=2),![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FfXim9UuVRqtHTQXVprgX%252FConferir%2520venda%2520convenio.PNG%3Falt%3Dmedia%26token%3Ddc2816a8-187e-421a-a4cf-47548e4c8ea2\&width=300\&dpr=4\&quality=100\&sign=ede15cc2\&sv=2) e ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F9D8CupVMQ7jRM5hPxXBQ%252Fconferir%2520venda%2520pbm.PNG%3Falt%3Dmedia%26token%3D7dbd2104-de0b-4947-a4fe-ab465f17feb5\&width=300\&dpr=4\&quality=100\&sign=ca05c66a\&sv=2)habilitados, o usuário deverá inserir os valores de venda para cada uma das formas de pagamento (cartão, convênio e PBM's). Caso estejam desabilitados, o usuário não precisará informar os valores, pois o sistema irá informar automaticamente de acordo com as vendas realizadas.
* ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FD1ErbfjMvLVjDJK2eqEo%252FAgrupar%2520itens.PNG%3Falt%3Dmedia%26token%3Dd3590a81-b3a3-46bf-9b0b-a04ae342bd87\&width=300\&dpr=4\&quality=100\&sign=55b0ff93\&sv=2): parâmetro utilizado para agrupar itens iguais lançados na pré-venda, ou seja, quando lançada mais de uma quantidade do mesmo produto, o registro será visto apenas uma vez no grid, mas com várias quantidades. Quando desabilitado, produtos lançados com várias quantidades, os registros no grid serão lançados de acordo com a quantidade informada.

{% hint style="warning" %}
Produtos fracionados não são agrupados.
{% endhint %}

* Os sistemas DMASTER FARMA e DMASTER SHOP calculam automaticamente a demanda de cada produto de acordo com as vendas, para que sejam realizadas compras. Caso o usuário queira informar a demanda manualmente, é necessário habilitar o parâmetro ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FimqxmpdjDd0ZeYXOSfzS%252FDmanda.PNG%3Falt%3Dmedia%26token%3Ddf34ef2b-395b-4b13-b0b2-3fb75a0814be\&width=300\&dpr=4\&quality=100\&sign=59eea9d0\&sv=2).

{% hint style="warning" %}
Caso o parâmetro seja habilitado, a demanda manual será habilitada para todos os produtos.
{% endhint %}

* ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FPRzmOOMQUbEzhrYtidog%252FSolicitar%2520senha.PNG%3Falt%3Dmedia%26token%3D6f3a8d9b-8c5d-4d83-b520-bf496da4155e\&width=300\&dpr=4\&quality=100\&sign=dcc32d75\&sv=2): parâmetro responsável por solicitar usuário e senha no momento da abertura e fechamento do caixa, se habilitado.
* ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FcWfkows0Ogz4f4FuUNZy%252FAdm%2520produtos.PNG%3Falt%3Dmedia%26token%3D5aee76ce-9347-4741-95d4-eca61a96cc67\&width=300\&dpr=4\&quality=100\&sign=8d712588\&sv=2): quando habilitado esse parâmetro, o estabelecimento poderá realizar alterações no cadastro de produto. O parâmetro só é desabilitado quando dois estabelecimentos são Matriz e Filial e possuem um tipo de integração , onde a Matriz é quem realiza alterações no cadastro de produto. Nesse caso, o parâmetro é desabilitado na Filial.
* Para acessar os módulo dos sistemas DMASTER FARMA e DMASTER SHOP é solicitado usuário. Para que não seja necessário informar usuário e senha para acessar os módulos, é habilitado o parâmetro ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FbFAuIOZ9QayA6NlmwPfQ%252FLogin%2520iniciar.PNG%3Falt%3Dmedia%26token%3D8f1ca925-0b97-434a-8bde-e02813d752f3\&width=300\&dpr=4\&quality=100\&sign=e2366d8a\&sv=2), para que seja informado usuário e senha apenas na abertura do sistema.

{% hint style="warning" %}
Com esse parâmetro habilitado, qualquer alteração que for realizada será no usuário informado na abertura do sistema.
{% endhint %}

É possível abandonar a tela de usuário na abertura do sistema, utilizando a tecla ESC. Assim, a cada módulo acessado, deverá ser informado o usuário. Esse processo também é utilizado quando é necessário realizar algum processo com o usuário Admin.

* ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FmIFVkheOjaYpyyh6miTp%252Ftroco%2520pre%2520venda.PNG%3Falt%3Dmedia%26token%3D4289df5f-ff06-4f4c-a430-5b6afccd393c\&width=300\&dpr=4\&quality=100\&sign=43af880d\&sv=2): quando habilitado este parâmetro, ao final do processo de criar uma pré-venda, caso a venda seja em dinheiro, é necessário informar qual o valor será recebido, para que o troco seja calculado.

{% hint style="warning" %}
Após realizar qualquer alteração no módulo de configurações, o sistema é reiniciado.

Para alterar os dados cadastrais (CNPJ, nome fantasia e telefone), é necessária realizar a alteração no cadastro do cliente no controle interno Dmaster e logo após atualizar os dados da empresa.
{% endhint %}
