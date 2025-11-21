# Particularidades SHOP

{% tabs %}
{% tab title="Balança Acoplada" %}
Esse tipo de configuração é utilizado quando o estabelecimento possui uma balança ligada ao computador do caixa, ou seja, o peso colocado na balança será lido pelo sistema Dmaster ECF.

#### Configuração <a href="#configuracao" id="configuracao"></a>

1.  Levando em consideração que a balança já está ligada e instalada no computador, será necessário verificar a comunicação, qual porta ela está conectada e qual a velocidade. Para isso, utilizamos o aplicativo **testabalança.exe**, que se encontra no caminho **\\\arquivos\suporte\09.Ferramentas\Teste de balanca**. Copiar o aplicativo para a pasta **MCUtil** do caixa do cliente.&#x20;

    <figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FknlBrBfaEGFISbwS0dpj%252Fteste%2520balanca.png%3Falt%3Dmedia%26token%3Dd7a77be9-1ee4-4b5f-984e-b9a9fae6f430&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=564f473f&#x26;sv=2" alt=""><figcaption></figcaption></figure>
2.  Ao executar o aplicativo, será aberta a seguinte tela onde será necessário selecionar a **marca** da balança no campo **Balança**, selecionar a porta que a mesma está conectada no campo **Porta Serial** e por fim, selecionar a **velocidade**, no campo **Baud rate**. Com o peso já em cima da balança, clicar em **ativar** e logo após clicar em **Ler Peso**. O peso que aparece na balança deve ser lido e será mostrado no campo **Último peso lido**. **\*Caso deseje ler outra vez o peso da balança, é necessário clicar em Desativar, e logo após ativar novamente e ler o peso.**&#x20;

    <figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FPrK0jKh5ZqvaSBCX5Jtv%252Fteste%2520balanca%25201.png%3Falt%3Dmedia%26token%3Db5eba6ee-e50a-48db-bd7a-50d36de1e37b&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=a0591932&#x26;sv=2" alt=""><figcaption></figcaption></figure>
3.  Após verificar se a balança está comunicando, em qual porta está ligada e em qual velocidade, é necessário inserir as informações no **ConfigECF**. Para isso será necessário marcar o parâmetro **Balança acoplada**, inserir a **porta de comunicação** e selecionar a **velocidade**, que foram verificadas no aplicativo **testabalança.exe**.&#x20;

    <figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FDijU83WaJIvX7twkbeR1%252Fbalanca%2520acoplada.png%3Falt%3Dmedia%26token%3D1b619d04-9e42-410e-a67d-c9da565f3c1a&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=861cbbc6&#x26;sv=2" alt=""><figcaption></figcaption></figure>
4. Após realizar a configuração, é necessário copiar o arquivo **captura peso** da pasta **MCecf** para a pasta **inicializar do windows**. Executar o aplicativo e ele deve ficar **carregado próximo ao relógio**. &#x20;

<figure><img src="../../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>



<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FEpElb8TdI99Ny6IIccWE%252FCaptura%2520peso%25201.png%3Falt%3Dmedia%26token%3D9f36d803-1c79-4bff-ae6a-ddbf98d94a7d&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=12d84d39&#x26;sv=2" alt=""><figcaption></figcaption></figure>



1.  Caso seja necessário fechar o aplicativo **CapturaPeso**, é necessário clicar com o **botão direito do mouse**, clicar em **fechar** e a senha é a data do dia. **Exemplo: 13042022**.&#x20;

    <figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FWPxgBqU1MxGbMs5S8Gs0%252Ffechar%2520captura%2520peso.png%3Falt%3Dmedia%26token%3D4a41686b-1cee-479a-bb77-4dff87bd6b1c&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=2e78362&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Utilização <a href="#utilizacao" id="utilizacao"></a>

Após colocar o peso na balança, pesquisar o produto na tela de vendas do Dmaster ECF, o sistema irá fazer a leitura do peso que está na balança. Após lido o peso, deve -se utilizar a tecla Enter e o produto será carregado na tela com sua quantidade e valor. Com o produto lançado na tela, a venda pode ser finalizada normalmente.&#x20;

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F58OYuuz7u6ZYw0t99bld%252Fproduto%2520lancado.png%3Falt%3Dmedia%26token%3D5d739ccf-c4d7-4aca-9570-07806fec4ead&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=d9f4cb01&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FwshJsqWeNozj3CVovbrX%252FPeso%2520.png%3Falt%3Dmedia%26token%3D59adfbd1-af76-4bb3-a5a9-d425d93b2e29&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=e2d255bb&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<br>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="Balança de Etiqueta" %}
Esse tipo de configuração é utilizado quando o cliente possui uma balança onde pesa os produtos e a mesma imprime uma etiqueta com os dados do produto (descrição, código, quantidade, valor, validade). O código contido na etiqueta será lido pelo sistema Dmaster ECF.

#### Configuração <a href="#configuracao-1" id="configuracao-1"></a>

A principio é necessário pedir ao cliente uma imagem da etiqueta que é impressa pela balança, para que seja possível verificar as informações necessárias para a configuração. Um exemplo abaixo:&#x20;

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F58kuAydRKNihR9Z68fPt%252FEtiqueta%2520Balan%25C3%25A7a1.jpg%3Falt%3Dmedia%26token%3D6dcbbaaa-21b1-4093-91a1-e016df505f78&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=845fb743&#x26;sv=2" alt=""><figcaption></figcaption></figure>

**Legenda da etiqueta:**

* **2 -** Digito identificador de produto de balança **(Informação que deve ser inserida no campo 1º digito cod. balança);**
* **000200 -** Caracteres para o código do produto **(Informação que deve ser inserida no campo nº digitos balança);**
* **00573 -** Preço do produto (a ser dividido por 100 para criar as duas casas decimais);
* **5 -** Caractere validador do código de barras.

Com a imagem da etiqueta em mãos, será necessário realizar a configuração no **ConfigECF**.

* No campo **1º dígito cod. balança**, é inserido o **primeiro digito do código impresso na etiqueta**;
* No campo **nº dígitos balança**, é inserida a **quantidade de dígitos referente ao código do produto**;

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FQKnQaCSlr4dXoVOVZos8%252Fbalanca%2520etiqueta.png%3Falt%3Dmedia%26token%3Db0f1e253-8943-4ecb-bf7b-2eb9a15ab900&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=b12131fe&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após inserir as informações no ConfigECF, também é necessário configurar no Dmaster Shop, seguindo os seguintes passos:

1. Acessar as configurações gerais do sistema (Shift + F12 no módulo utilitários);
2. Expandir a tela de configurações;
3. Inserir as informações corretas nos campos **Digito inicia etiq. balança** e **Qt. digitos codigbalança**. As informações devem ser iguais as que foram inseridas no ConfigECF.&#x20;



<figure><img src="../../.gitbook/assets/balança (1).png" alt=""><figcaption></figcaption></figure>

#### Utilização <a href="#utilizacao-1" id="utilizacao-1"></a>

Após realizar as configurações anteriores, ao digitar o código impresso na etiqueta, ou ler o mesmo através de um leitor de código de barras na tela de vendas do Dmaster ECF, o produto será lançado na tela com sua respectiva quantidade e valor de acordo com a informação contida na etiqueta e a venda poderá ser finalizada normalmente.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FXhpnqdTU0e1Y513IP62n%252Fproduto%2520lancado%25201.png%3Falt%3Dmedia%26token%3D6aa78fbd-1b7c-4818-b3eb-4e253e8b5ffb&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=5c7d6cfa&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FEIjkUoNCWOOaH2RIWhXv%252Fcodigo.png%3Falt%3Dmedia%26token%3Dab9eeed1-4b75-4274-9323-5f2e7346db45&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=e3114667&#x26;sv=2" alt=""><figcaption></figcaption></figure>

[<br>](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FvieZCUKwCDjJOYujhGGR%2FParticularidades%20DMASTER%20SHOP.pdf?alt=media\&token=5bb487cb-bda0-4689-acc7-cdf36b9fdaef)
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}



{% tabs %}
{% tab title="Módulo de emissão de boleto" %}
**ATENÇÃO:**

* O módulo de emissão de boleto é utilizado apenas no sistema Dmaster Shop.
* Os bancos homologados são Bradesco e Itaú.
* Para utilização do módulo, o cliente deve possuir cobrança registrada em algum dos bancos homologados.
* O cliente deve enviar para o e-mail [atendimento@dmaster.com.br](mailto:atendimento@dmaster.com.br) os seguintes dados: Agência, Conta Cobrança, Dígito da conta e número da carteira. **\*Se o banco em questão for Bradesco, o cliente deve informar também o código da empresa no banco.**
* O prazo é de 3 a 7 dias úteis para homologação devido à necessidade de fazer testes para depois cliente começar a utilizar o módulo.
* O módulo é utilizado para clientes que necessitam emitir boleto de determinada venda.

### Configuração <a href="#configuracao-2" id="configuracao-2"></a>

A configuração é realizada pelo setor comercial.

### Utilização <a href="#utilizacao-2" id="utilizacao-2"></a>

#### Emissão de boleto <a href="#emissao-de-boleto" id="emissao-de-boleto"></a>

1. O primeiro passo é emitir o boleto através do módulo de parcelamento de clientes.
2.  Após pesquisar o cliente no módulo, clicar no botão **Emitir boleto** e confirmar a emissão.&#x20;

    <figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FhcE2OtTJVq8pOC0esT2p%252FParcelamento%2520de%2520clientes.png%3Falt%3Dmedia%26token%3D9edd3153-0d7d-43fe-9709-c51bf1c1ebd6&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=7046c5b5&#x26;sv=2" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../.gitbook/assets/image (57).png" alt=""><figcaption></figcaption></figure>
3. Após o processo acima, o boleto será aberto para impressão.

#### Registro de boleto <a href="#registro-de-boleto" id="registro-de-boleto"></a>

1.  O próximo passo é registrar o boleto emitido. Para isso é necessário acessar o módulo **Utilitários > Cobrança bancária > Manutenção de boletos**.&#x20;

    <figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fr3TKQPAkgRtOlMIvsQF5%252FModulo%2520utilitarios.png%3Falt%3Dmedia%26token%3D02e1c99a-bf50-4fc7-ad8a-28fff8a6450c&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=be1be93b&#x26;sv=2" alt=""><figcaption></figcaption></figure>
2.  Na tela seguinte, escolher a data de emissão desejada, selecionar situação **Pendentes** e clicar no botão ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F6rY0W5dXQEzGtjDof2eF%252FBotao%2520ver.PNG%3Falt%3Dmedia%26token%3D7376cb5e-b904-402e-a6fd-33a7fb2851d0\&width=300\&dpr=4\&quality=100\&sign=dd5fb60b\&sv=2) para mostrar os dados no grid, irão aparecer todos os boletos emitidos e pendentes de registro. Clicar em **Registrar Boletos** e todos os boletos do grid serão registrados. **\*O processo de registro de boleto pode ser realizado ao final do dia ou ao longo do dia.** \[

    <figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FLsi26xsbEJ7oOukRJduQ%252FTela%2520inicial.png%3Falt%3Dmedia%26token%3Dd4f57c6d-fa5a-44a6-8176-946cf2e27d5a&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=94ad1115&#x26;sv=2" alt=""><figcaption></figcaption></figure>
3. Após clicar em **Registrar boletos** será aberta a tela para selecionar uma pasta onde o arquivo será salvo. Selecionar a pasta e clicar em **Abrir**.

O processo de registrar boleto gera um arquivo no layout que o banco aceita. Esse arquivo deve ser enviado através do Internet Banking do cliente.

**Importante:** Caso o arquivo não seja enviado ao banco, o boleto não será registrado e caso o destinatário efetue o pagamento do mesmo, o banco devolve o dinheiro a quem pagou o boleto. É obrigatório o processo de registro de boleto. Deve ser realizado diariamente.

#### Baixa de boleto <a href="#baixa-de-boleto" id="baixa-de-boleto"></a>

No dia seguinte ao processo de registrar o boleto, é feito o processo de baixa. O cliente deve puxar o retorno da cobrança no Internet Banking e importar o arquivo em **Baixa c/ arquivo**.

1. Para realizar a baixa é necessário acessar o menu **Utilitários > Cobrança Bancária > Manutenção de boletos**
2. Na tela seguinte, clicar em **Baixa c/ arquivo**. Irá abrir a tela para selecionar o arquivo desejado para baixa.
3. Selecionar o arquivo e clicar em **Abrir**.

**Observação:** O arquivo de baixa pode conter retorno de boletos pagos ou rejeitados.

<figure><img src="../../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FndBK6bHZ0bJ20MF42NTe%252FBaixa%2520com%2520arquivp.png%3Falt%3Dmedia%26token%3Df4a1f2b1-4020-4d62-b963-cf4a2fe029cf&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=c6d71c8a&#x26;sv=2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Tab 2" %}

{% endtab %}
{% endtabs %}









