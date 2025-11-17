# Cadastro de produtos

### Classificação ou alteração de produto na MATRIZ

#### **Produto novo**

Para realizar a classificação de um produto controlado pela ANVISA no DMASTER FARMA, os campos necessários para identificá-lo corretamente são:

1. Registro MS
2. Classe terapêutica
3. Tipo de receituário

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FJZlNIgF6rsAM49pjnyTH%2FCadastro%20produto.PNG?alt=media&#x26;token=55a232d7-6892-4623-be85-1aca6c54358b" alt=""><figcaption></figcaption></figure>

Após inserir a classificação correta do produto e clicar em gravar, o cadastro é enviado para o DMASTER SNGPC.

#### **Produto existente sem estoque**

Para produto que já possui cadastro no DMASTER FARMA, mas ainda não possui estoque, o processo de classificação é o mesmo descrito em #produto-novo.

#### **Produto existente com estoque**

Para produto que já possui cadastro e estoque, após realizar a classificação de acordo com #produto-novo, será aberta a tela de classificação, onde será necessário informar os dados de entrada daquele produto, pois o sistema precisa saber a origem do estoque.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fw8x9GwCllP4ySdI6Ynvz%2FClassificacao%20SNGPC%201.png?alt=media&#x26;token=8e5df80a-7618-4132-989f-7987f20b3608" alt=""><figcaption></figcaption></figure>

\
Caso o estoque do produto esteja incorreto, é possível realizar o ajuste também na tela de classificação. Para isso, é preciso informar a quantidade total em estoque no campo quantidade total adquirida. Após inserir todas as informações e gravar, o ajuste será realizado e o cadastro do produto será enviado para o DMASTER SNGPC.\
Se o estoque real do produto é 0, deve-se utilizar a tecla \[F2] - Sem entradas para o produto, sendo assim, o estoque será zerado e o cadastro será enviado para o DMASTER SNGPC.

### Adicionar Registro MS

É possível que um produto controlado possua mais de um Registro MS. Para realizar a adição de MS através do cadastro do produto no DMASTER FARMA é preciso seguir os passos:

1. Clicar no botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FakIplvvVzYrwTgEGK38e%2FBot%C3%A3o%20incluir%20registro%20MS.png?alt=media\&token=b49518d1-59db-4874-9624-886ff9c98788)
2. Clicar na opção Registro MS
3. Digitar o MS que deverá ser adicionado
4. Botão de incluir. Após incluir, utilizar a tecla ESC para que a tecla de relação de Registro MS feche
5. Gravar e finalizar

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FHDI0XhcRv7EHdvw9RhTE%2FAdicao%20de%20MS%201.PNG?alt=media&#x26;token=3a8c0639-cd88-4e41-b504-dd69e6c7e5a9" alt=""><figcaption></figcaption></figure>

Após os processo acima, o registro MS que foi adicionado poderá ser visualizado ao acessar o menu relação de registros MS, como mostrado na imagem abaixo.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FA47fPT4ANnOiwA2aDv4z%2FRelacao%20de%20registro%20MS.PNG?alt=media&#x26;token=cfeab750-ac3b-45be-9158-32bf8bf5416d" alt=""><figcaption></figcaption></figure>

Após adicionar o registro MS no cadastro do produto, ele será cadastrado no DMASTER SNGPC e poderá ser visualizado no módulo de inventário atual, como mostrado na imagem abaixo. Nesse caso, o cadastro do MS associado vai possuir a informação do código interno do produto no DMASTER FARMA no campo código 2.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fb4jOkMMkGSXUbJRaIvH2%2FProduto%20com%20varios%20MS.PNG?alt=media&#x26;token=8ef2d07a-7c22-4f31-900b-492dcd751ad2" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Uma vez que o Registro MS foi associado a um produto, ele não poderá ser excluído.
{% endhint %}

### Classificação ou alteração de produto na FILIAL

#### **Produto com estoque**

Para realizar a classificação ou alteração do cadastro de um produto é necessário que essa alteração seja feita na MATRIZ, de acordo com o processo descrito em #classificacao-ou-alteracao-de-produto-na-matriz, para que o aplicativo de integração de cadastros faça a replicação dos dados para todas as FILIAIS, mas se o produto já possuir estoque na FILIAL o aplicativo não irá cadastra-lo no sistema SNGPC, apenas irá atualizar os dados no DMASTER FARMA e será necessário que o usuário informe as movimentações de entrada para aquele estoque do DMASTER FARMA utilizando a tecla \[F8] no cadastro do produto e seguindo de acordo com o processo descrito em #produto-existente-com-estoque.

#### Produto sem estoque

Caso o produto ainda não possua estoque na Filial, o produto será APENAS classificado no DMASTER FARMA e enviado para o DMASTER SNGPC.
