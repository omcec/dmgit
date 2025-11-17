# Erros

<details>

<summary>Erro de Abertura</summary>

Ao executar o AppDMNFCe, pode ser que ocorra o seguinte erro:

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FbHgRnZfYE3P0QLvOKOm2%252Ferro%2520nfce%2520abertura.png%3Falt%3Dmedia%26token%3Da6823827-be91-450c-9c9e-f48ab2fdb82f\&width=300\&dpr=4\&quality=100\&sign=44da231\&sv=2)

Este erro ocorre, quando o **Net Framework 4.5** ou **superior** não está instalado no computador ou está faltando alguns dos arquivos contidos na seção [Copiando arquivos](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/nfce/configuracao#copiando-arquivos). Para correção, é necessário instalar o mesmo ou copiar os arquivos faltantes.

O erro abaixo, pode ocorrer na abertura do NFCe Direto:

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FTk2CmkHm6XEeCBnnqPFe%252FErro%2520NFCE%2520Direto.png%3Falt%3Dmedia%26token%3D20024ecf-0640-4dfe-8de2-212f108a248d\&width=300\&dpr=4\&quality=100\&sign=9b05f18f\&sv=2)

Para correção do erro, deve ser configurado o executável para executar como administrador.

</details>

<details>

<summary>Verificando Erros de Venda</summary>



A mensagem abaixo ocorre quando existe algum tipo de erro na venda em questão. Nesse caso a venda não é autorizada pelo Sefaz, mas o registro dela já está gravado no sistema, ou seja, as informações dessa venda já podem ser visualizadas nos relatórios.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Ft0VGlkWA06srU7syyNmc%252FAlerta%2520erros.png%3Falt%3Dmedia%26token%3D5cd7f217-cc7e-4d04-bb67-17b997eee0b7\&width=300\&dpr=4\&quality=100\&sign=1a0f74ed\&sv=2)

Para verificar qual é o erro e posteriormente realizar a correção é preciso acessar a tela de **manutenção da emissão de NFCe (Operacional > Pré- vendas > F2)**. Ao acessá-la, selecionar o registro da venda e verificar a descrição do erro no campo **mensagem**.

Após verificar o erro, é preciso realizar as devidas correções. Para corrigir erros que são provenientes do cadastro do produto, é preciso clicar no botão ![](https://dmaster.gitbook.io/~gitbook/image?url=https:%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F7t9Ro9mebgGWC1A5zhRk%252Fbotao%2520mais.png%3Falt=media%26token=82a00495-28d3-4de8-8b7c-2c05112ce91d\&width=300\&dpr=4\&quality=100\&sign=f517186d87d7aa31fd55e8f75e255cf7baee629e615d16647a1adc98e68344c3)e serão exibidos os produtos da venda. Clicar no **código do produto** que está com erro, ao lado esquerdo e o cadastro do mesmo será aberto. Realizar as devidas correções e **gravar**. Voltar a tela anterior e clicar no botão **reenviar**. Se as informações estiverem corretas, a venda será enviada para o Sefaz e irá sair da tela de manutenção do NFCe, e caso ainda houver erros, ela ainda ficará na tela com a descrição do erro.

<figure><img src="../../../../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>

**Observação:**

* Venda de PBM não é possível reenviar. Caso apresente erro, é preciso realizar a devolução e refazê-la. A venda de PBM possui essa especificidade, pois ela depende normalmente de ser autorizada pelo próprio PBM no momento da emissão da VENDA e a comunicação com o PBM é feita apenas no frente de caixa, sendo que se apenas reenviarmos não seria possível realizar esta comunicação.

<figure><img src="../../../../.gitbook/assets/image (114).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary></summary>



</details>
