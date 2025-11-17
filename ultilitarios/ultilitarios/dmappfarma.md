# DMAppFarma

## DMAppFarma

Este aplicativo tem o objetivo de exportar a base de dados de produtos do estabelecimento para um arquivo CSV, onde as informações contidas nesse arquivos serão importadas por uma empresa responsável para um tipo de loja online.

O usuário responsável pelo estabelecimento deverá utilizar o aplicativo sempre que houver necessidade de exportação dos dados. Após a exportação, o arquivo .CSV deve ser enviado para a empresa responsável realizar os devidos procedimentos.

Os processos para instalação e utilização do aplicativo serão citados e explicados a seguir.

#### Copiar o executável <a href="#copiar-o-executavel" id="copiar-o-executavel"></a>

Copiar o executável **DMAppFarma** do Servidor Dmaster para a pasta **MBHSist** do **SERVIDOR** do cliente.

O aplicativo irá funcionar APENAS no servidor.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FIFOY3uY20Ldayj8TB06P%252Farquivos%2520dmaster.png%3Falt%3Dmedia%26token%3D923b1cec-9a86-4b46-9d39-af57e40bf5de\&width=300\&dpr=4\&quality=100\&sign=8e21b5e5\&sv=2) ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FpHdTJEcWxid7S27Cl6R4%252FArquivos%2520mbhsist.png%3Falt%3Dmedia%26token%3D945c137d-1c21-4395-9506-b41cdc4cb7b2\&width=300\&dpr=4\&quality=100\&sign=cfe0fc2f\&sv=2)

#### Executar o aplicativo e exportar os produtos <a href="#executar-o-aplicativo-e-exportar-os-produtos" id="executar-o-aplicativo-e-exportar-os-produtos"></a>

Ao executar o aplicativo, **automaticamente** são criados na área de trabalho os atalhos do **executável DMAppFarma** e da **pasta ExportaçãoAppFarma**. Será aberta a tela inicial, onde é necessário verificar alguns parâmetros. São eles:

**Exportar somente produtos ativos:** ao marcar este parâmetro, serão exportados **APENAS** os produtos ativos no sistema;

**Exportar somente produtos com estoque:** ao marcar este parâmetro, serão exportados **APENAS** os produtos que possuem estoque no sistema;

**Exportar produtos com preço promocional:** ao marcar este parâmetro, os produtos que possuem preço promocional, serão exportados com este preço e não com preço de venda.

Após verificar os parâmetros, clicar no botão **Exportar** e será aberta a tela de confirmação, indicando o caminho do arquivo .CSV gerado.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F71WRrWqvCdqgqKJeFYh2%252FTela%2520inicial.PNG%3Falt%3Dmedia%26token%3De8940df4-05ea-4470-b7d5-8436d16631c9\&width=300\&dpr=4\&quality=100\&sign=d3611d15\&sv=2)![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FqCygnub4Q0xlFGzqvRuy%252Fimage.png%3Falt%3Dmedia%26token%3D68d41c6f-0b6a-4e71-9b6d-4d77a449c5a0\&width=300\&dpr=4\&quality=100\&sign=765acb96\&sv=2)

#### Informações arquivo gerado <a href="#informacoes-arquivo-gerado" id="informacoes-arquivo-gerado"></a>

Todos os arquivos gerados são salvos na pasta **ExportaçãoAppFarma** e dentro do arquivo constam as seguintes informações do produto: **código de barras, descrição, estoque e preço.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FFhlf7pXjObRuJUtfGB2y%252FArquivo%2520gerado.PNG%3Falt%3Dmedia%26token%3Db011d82c-9724-4be9-ad12-fd8a33e8d0a5\&width=300\&dpr=4\&quality=100\&sign=c3880978\&sv=2)

#### **Envio do arquivo** <a href="#envio-do-arquivo" id="envio-do-arquivo"></a>

Após a geração do arquivo, o mesmo deve ser enviado para a empresa responsável realizar os devidos procedimentos. A partir daí, a Dmaster não se responsabiliza pelo processo.
