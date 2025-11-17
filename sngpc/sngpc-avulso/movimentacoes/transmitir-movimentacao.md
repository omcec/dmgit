# Transmitir movimentação

### **Gerar arquivo**

Na utilização do DMASTER SNGPC, é necessário efetuar o envio de todas movimentações lançadas no sistema para a Anvisa. Esta movimentação terá que ser envida no prazo de 7 em 7 dias, por exigência da própria Anvisa. Para enviar as movimentações, deve ser acessado o menu transmitir movimentação.

{% hint style="info" %}
Ao acessar o menu transmitir movimentação, será mostrado o período a ser enviado respeitando o limite de 7 dias.
{% endhint %}

{% hint style="info" %}
Só é possível realizar o envio de um arquivo por dia.
{% endhint %}

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FjvHz9A7lCSGOc2nSZ7PP%2FTransmiss%C3%A3o%20de%20arquivos.PNG?alt=media&#x26;token=c08fcd27-9374-436e-9fc5-02b000e1e842" alt=""><figcaption></figcaption></figure>

Ao clicar no botão gerar, será solicitado login e senha do Responsável Técnico no portal da ANVISA. Após os dados serem inseridos, o sistema irá realizar o envio do arquivo para a ANVISA.\
Após enviar, o arquivo será analisado e caso as movimentações estejam corretas, o arquivo será aceito e validado. Caso haja divergência nas informações o, o arquivo será rejeitado e deverá ser corrigido e retransmitido.

### Enviados

Menu utilizado para visualizar informações dos arquivos gerados. Neste módulo é possível visualizar, emitir relatório, cancelar e consultar situação dos arquivos gerados.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Ft23pmwCH0RXuAFytBGNZ%2FEnviados.JPG?alt=media&#x26;token=5cc418bb-b0c7-4bb7-a073-4197181c096b" alt=""><figcaption></figcaption></figure>

#### Situação do arquivo

O arquivo pode conter algumas situações. Estas serão citadas e explicadas a seguir.

* **Aguardando validação:** o arquivo ainda está aguardando a validação da ANVISA;
* **Arquivo aceito:** o arquivo foi validado e aceito pela ANVISA;
* **Arquivo rejeitado:** o arquivo foi validado e rejeitado pela ANVISA;
* **Arquivo cancelado:** arquivo foi cancelado;
* **Não transmitido:** arquivo foi gerado, mas não foi enviado para a ANVISA.

#### Cancelar arquivo

Para realizar o cancelamento de um arquivo gerado, é preciso selecioná-lo e utilizar a tecla F2.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FgWLWXJceORFJk6n8cUgT%2FCancelar%20arquivo%201.jpg?alt=media&#x26;token=bc148979-1a4a-4c5d-9fd0-760a75cb3770" alt=""><figcaption></figcaption></figure>

Após o processo anterior, será apresentada uma mensagem que deve confirmada para concluir o processo de cancelamento do arquivo.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F75nqlkjU7s8FzcQ5BiUs%2FCancelar%20arquivo.JPG?alt=media&#x26;token=d0730850-f97d-4794-ac96-d7e71691ed94" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Só é possível cancelar arquivos com situação não transmitido.
{% endhint %}

#### Incluir/Alterar Hash

Opção utilizada quando é necessário incluir o Hash do arquivo. Isso ocorre quando o sistema não consegue realizar a consulta do arquivo e inclusão do Hash automaticamente. Sendo assim, é necessário realizar os seguintes passos:

1. Acessar o portal da ANVISA
2. Ir até o menu Relatórios > Status de transmissão **\*consultar passo a passo em** **Consulta status de transmissão**
3. Copiar o Hash que consta no arquivo em questão
4. Acessar o menu enviados no DMASTER SNGPC
5. Selecionar o registro desejado
6. Utilizar a tecla F3
7. Colar o Hash copiado do portal da ANVISA

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F3Y6t7TqNsD13ovhzdBSF%2FIncluir%20hash%201.JPG?alt=media&#x26;token=f729039b-ba69-454f-aade-1c0e3c50754e" alt=""><figcaption></figcaption></figure>

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FmxIuZRuRs0tU5ysUDI3G%2FIncluir%20hash.JPG?alt=media&#x26;token=da5e90e4-7b28-4888-9de9-b64d07442b6f" alt=""><figcaption></figcaption></figure>

Após os passos acima, o sistema irá conseguir realizar a consulta do arquivo.

#### Consultar situação

Essa opção é utilizada para forçar o sistema a realizar a consulta da situação do arquivo gerado. O sistema pode não conseguir consultar o arquivo enviado e utilizando esta opção, a consulta é realizada naquele momento.\
Para realizar a consulta é preciso selecionar o registro desejado e utilizar a tecla F5, dessa forma, o sistema irá realizar a consulta no portal da ANVISA para atualizar a situação do arquivo enviado.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fpvf5PzTU9rWzRSyxE99J%2FConsultar%20situacao.jpg?alt=media&#x26;token=d2bc12ce-f93e-4f72-b66c-50bc15cb22e7" alt=""><figcaption></figcaption></figure>

#### Visualizar relatório

Opção utilizada para visualizar o relatório dos arquivos gerados. Nesse relatório irá conter os registros de entrada e saída que contém naquele arquivo.\
Para utilizar essa opção é necessário selecionar o registro e utilizar a tecla F8. O relatório será gerado e poderá ser salvo e/ou impresso.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FEJ65elBSdPEo8doSYBnX%2FRelatorio%20enviados%20entrada.JPG?alt=media&#x26;token=2bd56503-630c-45ec-a274-0f9a159ad6a6" alt=""><figcaption></figcaption></figure>
