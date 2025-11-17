# DMInventários

<details>

<summary>Sobre o aplicativo</summary>

Este aplicativo é utilizado quando o cliente vai realizar balanço da loja, ou seja, será feita a contagem de estoque dos produtos sem utilizar o módulo de inventário do sistema.\
A contagem do estoque é realizada pelo cliente juntamente com uma empresa especializada no processo.\
O aplicativo tem o objetivo de exportar um arquivo com os dados dos produtos, para que seja feita a contagem do estoque e após o término da contagem, é feita a importação do arquivo com as informações de estoque que serão inseridos no sistema.

</details>

<details>

<summary>Ultilização do aplicativo</summary>



Para iniciar o processo, é preciso copiar o aplicativo para a pasta MBHSist do Servidor do estabelecimento. O mesmo se encontra no caminho: **\\\arquivos\Suporte\07. Utilitarios de Sistema\12. Inventário.** ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FPmQYNbsJp6OV34kdKLt0%252FDMInventarios%2520servidor.png%3Falt%3Dmedia%26token%3D574283ba-f309-4db5-8ba6-2d5bf4c8a6f0\&width=300\&dpr=4\&quality=100\&sign=ef42220a\&sv=2) ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FBGPZCYi346ifcpIsfAjE%252FDMInventarios%2520mbhsist.png%3Falt%3Dmedia%26token%3D9333621b-5b4d-4557-8b08-9b3db68347e5\&width=300\&dpr=4\&quality=100\&sign=c49c82f3\&sv=2)

#### **Exportação** <a href="#exportacao" id="exportacao"></a>

**Formato de exportação:**

Nome Arquivo: Produtos\_Exportacao.txt Utiliza um caractere de Espaço para separação; ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FUspvXhXaiX4fifV6wEGZ%252FTabela%2520exportacao.PNG%3Falt%3Dmedia%26token%3D94ef664e-b64a-4ea2-8774-0ee5cb2f76ca\&width=300\&dpr=4\&quality=100\&sign=967d4a0a\&sv=2)

1. Executar o aplicativo, clicar na opção **Inventário empresas** e na próxima tela, selecionar a opção **exportar arquivos.** ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FdUv60lcQNZq1SIkk1rUd%252FTela%2520inicial.PNG%3Falt%3Dmedia%26token%3D7b1205da-306e-4434-9ad0-6dea31b6a591\&width=300\&dpr=4\&quality=100\&sign=fba1662d\&sv=2) ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FSDDSFpmWv0jPFSyhYcHK%252FExportar%2520e%2520importar.PNG%3Falt%3Dmedia%26token%3D5c3df6d7-a8ba-41de-afba-35c1c2e370c5\&width=300\&dpr=4\&quality=100\&sign=cacbae66\&sv=2)
2. Após o passo anterior, será gerada uma mensagem informando sobre a exportação do arquivo. **Observação:** o arquivo **Produtos\_Exportacao.txt** é gerado sempre na pasta onde o aplicativo DMInventário se encontra, neste caso, dentro da pasta MBHSist. ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FeywBU9c3sXnS3CFoX9Hv%252FArquivo%2520exportacao%2520gerado.PNG%3Falt%3Dmedia%26token%3Dcbe1eadf-9eff-4d95-9116-d460e2be225b\&width=300\&dpr=4\&quality=100\&sign=697fd0be\&sv=2)
3. Após o arquivo ser gerado, copiá-lo para a área de trabalho do computador para facilitar para o cliente.

#### **Importação** <a href="#importacao" id="importacao"></a>

**Formato para importação:**

Nome Arquivo: Produtos\_Importacao.txt Utiliza um caractere de Espaço para separação;

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fr3MqpYyxCdmTDZxOiDYP%252FTabela%2520importacao.PNG%3Falt%3Dmedia%26token%3D79fef78a-2fc0-4ab6-8b44-6aa5d3253874\&width=300\&dpr=4\&quality=100\&sign=ad810aa4\&sv=2)

**Observação:** Certifique-se de realizar um Backup do Banco de Dados antes do processo de importação.

Após a finalização da contagem pela parte do cliente, será necessário importar o arquivo para o sistema. O arquivo deve conter o nome **Produtos\_Importacao.txt** e estar na mesma pasta onde o aplicativo DMInventário está, neste caso na pasta MBHSist.

1. Executar o aplicativo, clicar na opção **Inventário empresas** e na próxima tela, selecionar a opção Importar arquivos. ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FgAzGVWBmcxcJdDUzwaXH%252FTela%2520inicial.PNG%3Falt%3Dmedia%26token%3D39566f3f-c868-4a92-9177-dd89cba0ed0c\&width=300\&dpr=4\&quality=100\&sign=da4c12b7\&sv=2) ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FkMMs7IXNLA1ym9PmI9QR%252Fimportar.PNG%3Falt%3Dmedia%26token%3D220385a1-8bb1-4169-ac3d-b071258d0af1\&width=300\&dpr=4\&quality=100\&sign=c1b4ae63\&sv=2)
2. Nesse momento, o estoque que consta no arquivo será importado para o sistema Dmaster. ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FaMXDzA6lKNQxPHu5Oa0j%252FIMportacao%2520realizada.PNG%3Falt%3Dmedia%26token%3Da2ba40ae-071f-4ebd-942f-15d0ccb33902\&width=300\&dpr=4\&quality=100\&sign=41d38870\&sv=2)

</details>
