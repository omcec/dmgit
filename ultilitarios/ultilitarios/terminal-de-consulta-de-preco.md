# Terminal de Consulta de preço

O terminal de consulta de preço é um equipamento que fica na loja, conectado a rede interna da loja e comunicando com o Servidor através do IP. O processo de configuração e utilização serão explicados a seguir e são utilizados apenas para o **terminal busca preço G2**.

**Observação:** para realizar as configurações do aplicativo, o Java precisa estar instalado no computador.

<details>

<summary>Configuração do equipamento</summary>

A configuração do equipamento deve ser realizada para que o mesmo comunique com o servidor da loja através do IP. Dessa forma, o IP do servidor deve estar fixo.

**Observação:** a configuração no equipamento deve ser realizada pela empresa em que o cliente adquiriu o mesmo. É orientado configurar o equipamento em uma faixa de IP mais alta, por exemplo: 192.168.1.222, para que não ocorra conflito com os demais computadores da rede.

</details>

<details>

<summary>Exportação do arquivo</summary>

Para utilização do terminal de consulta de preço, deve ser exportado um arquivo no sistema, contendo todos os produtos cadastrados. Para isso, deve acessar o módulo **Utilitários > Atualizar > Term. Busca Preço G2.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FXvM8uLTEuZDWCv1AdEJT%252FExportar%2520produto.png%3Falt%3Dmedia%26token%3Da200f0fb-cc60-4f65-8aa9-d951833bfa25\&width=300\&dpr=4\&quality=100\&sign=323fa3fd\&sv=2)

Na próxima tela, será exibido o nome do terminal de consulta, sendo necessário apenas clicar em ok para escolher onde o arquivo será salvo. **Observação:** o arquivo é salvo com o nome **BUSCAPRECOG2.txt.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Ft4PqgYEGU1YY8Eh8hIQo%252FExporta%2520arquivo.PNG%3Falt%3Dmedia%26token%3Dba2620a6-df97-4aba-9396-8da1758efecf\&width=300\&dpr=4\&quality=100\&sign=95410523\&sv=2)

</details>

<details>

<summary>Configuração do aplicativo</summary>

O primeiro passo é copiar a pasta **BuscaPreço do Servidor Dmaster**, no caminho **\\\arquivos\Suporte\07. Utilitarios de Sistema** para **C: do servidor do cliente**.

Após a cópia da pasta, executar o arquivo **tc-server-2.4.9.jar**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FTMMu6oeuogbzo8rcCYLd%252Faplicativo%2520tcserver.PNG%3Falt%3Dmedia%26token%3D8daaa814-b409-4b2f-9d31-c695568af490\&width=300\&dpr=4\&quality=100\&sign=3b8cee98\&sv=2)

**Observação:** o aplicativo tc-server-2.4.9 deve ser inserido na pasta iniciar do Windows.

Na tela inicial do aplicativo, clicar em **produtos** e logo após clicar em **Configurações do banco de dados**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FvgIVRVxC6gEVcxPvdgYG%252FTC%2520Server%2520inicial.PNG%3Falt%3Dmedia%26token%3D79d53f7d-237e-488f-a454-28154c8ab942\&width=300\&dpr=4\&quality=100\&sign=dd068d06\&sv=2)

Na próxima tela, na seção **gerenciamento de base de dados**, selecionar a opção **Externo (arquivo de texto).** Logo abaixo, na seção **Externo (arquivo de texto)**, clicar em pesquisar para buscar o arquivo que é gerado pelo sistema DMASTER.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fg4rnshmzZ2Sz2e7kzxW5%252FConfig1.PNG%3Falt%3Dmedia%26token%3D0e6e7397-5054-4236-9600-fd6b251a0b71\&width=300\&dpr=4\&quality=100\&sign=6be4ac3a\&sv=2)![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F8U2Lp2h4KWE2zgi3DTn1%252FPesquisa%2520arquivo.PNG%3Falt%3Dmedia%26token%3D7b9190cd-43ca-4bf4-bffe-2ec82af11961\&width=300\&dpr=4\&quality=100\&sign=409f6016\&sv=2)

Ainda é possível configurar o **intervalo** de atualização, ou seja, o tempo que o aplicativo irá ler o arquivo de texto. O tempo mínimo é 10 minutos, dessa forma, o aplicativo irá ler o arquivo de 10 em 10 minutos.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FYR9JQadsCsszic8gAoUH%252FConfig%2520intervalo.png%3Falt%3Dmedia%26token%3D51210192-e9e4-4461-94ff-70343a1a4985\&width=300\&dpr=4\&quality=100\&sign=5bdd9aee\&sv=2)

Após toda a configuração, clicar em **ok** para salvar.

Ao fim da configuração, serão mostrados todos os produtos na tela inicial do aplicativo.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FQo99Lw2ZTs260LfUlakq%252FConfig%2520final.PNG%3Falt%3Dmedia%26token%3D9b738aee-dca4-4a0c-a206-94844fbc0ef8\&width=300\&dpr=4\&quality=100\&sign=55e22ab6\&sv=2)

**Observação:** ao final dos processos, o aplicativo deve ser apenas **minimizado**. Assim, ele ficará carregado próximo ao relógio.

Após a configuração do aplicativo, a cada alteração que houver no sistema, deve ser realizada a exportação do arquivo, de acordo com [Exportação de arquivo](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/utilitarios/terminal-de-consulta-de-preco#exportacao-de-arquivo)para que o aplicativo realize a atualização para o equipamento.

</details>
