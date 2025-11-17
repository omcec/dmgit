# Entrada de nota

### **DMASTER FARMA**

Para realizar a entrada de notas no sistema DMASTER FARMA é necessário importar o XML via arquivo ou via chave de acesso, ou também pode lançar os dados manualmente **(não orientado).**

Para realizar a entrada de produto controlado, o mesmo já deve estar classificado no DMASTER FARMA. Desta forma, o sistema identificará que o produto é controlado e o mesmo será enviado para o DMASTER SNGPC no momento da gravação da nota.\
Se o produto ainda não estiver classificado na hora da entrada, é possível realizar a classificação de acordo com o processo descrito em #produto-novo.\
A nota pode ser gravada normalmente se o produto estiver sem classificação, mas posteriormente deve ser realizado o processo de acordo com #entrada-realizada-com-produto-nao-classificado.

Após realizar os devidos ajustes nos preços dos produtos os itens que são controlados pela ANVISA **(já classificados no cadastro de produto)** ficarão com a situação igual a imagem abaixo **(Número 1)**, esta situação tem o objetivo de atentar o usuário a confirmar os dados de lote **(Número 2)** e Validade **(Número 3)** que após confirmação dos dados deverá pressionar a tecla **F2** e seguir com a gravação da nota.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F6uBBuS9xRlczRvboma0Z%2FEntrada%20SNGPC%20Integrado.png?alt=media&#x26;token=af55977a-d0aa-42e9-b1ac-9d9bf83f2aac" alt=""><figcaption></figcaption></figure>

Ao utilizar a tecla F2, será aberta a tela de classificação que deve ser preenchida de acordo com o descrito em #produto-existente-com-estoque .

{% hint style="info" %}
Ao inserir os dados do produto, o cadastro já é feito no SNGPC, mas só após gravar a nota, é inserido estoque no SNGPC.
{% endhint %}

### Adicionar Registro MS

Processo deve ser realizado de acordo com #adicionar-registro-ms.

### **Entrada realizada com produto não classificado**

Caso seja realizada entrada de produto controlado, mas o mesmo ainda não foi classificado, será necessário seguir os passos:

1. Realizar a devolução do produto na nota no sistema DMASTER FARMA, seguindo o processo de acordo com devolucao-de-nota-de-entrada.
2. Classificar o produto corretamente no DMASTER FARMA, sem inserir o estoque da entrada, mas caso o produto já possua algum estoque, este deve ser informado.\
   Processo realizado de acordo com #produto-novo.
3. Realizar a entrada da nota manualmente no módulo de entradas do DMASTER SNGPC. Após esse processo, o sistema irá realizar as validações necessárias e a devolução do produto será excluída no DMASTER FARMA.

É possível também que seja feita a exclusão da nota, mas esse processo só deve ser realizado em último caso, pois gera muitos impactos relacionados a estoque de outros produtos da nota, data da movimentação e etc.\
Caso seja realizada essa opção, será preciso seguir os passos:

1. Excluir a nota de entrada no sistema DMASTER FARMA.
2. Classificar o produto corretamente no DMASTER FARMA, sem inserir o estoque da entrada, mas caso o produto já possua algum estoque, este deve ser informado. Processo realizado de acordo com #produto-novo.
3. Realizar a entrada da nota novamente no DMASTER FARMA.

#### **DMASTER SNGPC**

O módulo de entrada de nota no sistema DMASTER SNGPC só é utilizado quando for necessário realizar alguma correção em uma entrada que não foi inserida os dados que são enviados para a ANVISA ou não foi possível alterar os dados inseridos no momento da entrada na tela de Confirmação de lançamentos.

Para realizar esta correção é necessário antes realizar a devolução dos itens a serem corrigidos no módulo de Devolução de nota de entrada no DMASTER FARMA e posteriormente fazer o lançamento manual no módulo de entrada abaixo, informando o CNPJ do fornecedor, número da nota e data de entrada para o sistema fazer as devidas validações.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FNxeCjLROCe8OGgqs2Acx%2FEntrada%20SNGPC%20Integrado%201.png?alt=media&#x26;token=a81587c1-0cd4-40cb-953c-28c834cb5d75" alt=""><figcaption></figcaption></figure>
