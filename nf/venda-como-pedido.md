# Venda como pedido

A venda sendo gerada como **pedido**, a finalidade da nota fiscal deverá ser **venda de mercadoria dentro ou fora do estado**, e não como substituição de cupom fiscal

Caso o pedido seja gerado como substituição de cupom fiscal, apresentará o erro abaixo.\


<mark style="color:red;">DMASTER Farma</mark>

<mark style="color:red;">Retorno obtido da consulta do recibo do lote da NFE.</mark>

<mark style="color:red;">104 - Lote processado</mark>

<mark style="color:red;">Detalhes do erro do protocolo: 701 - Rejeicao: Nao informado Nota Fiscal referenciada (Lancamento relativo a Cupom Fiscal) \[nItem: 1]</mark>

<mark style="color:red;">OK</mark>



<figure><img src="../.gitbook/assets/image (116).png" alt=""><figcaption></figcaption></figure>

#### <img src="https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2Fsindicato.org.br%2Fwp-content%2Fuploads%2F2017%2F01%2Fnfe_big.jpg&#x26;width=42&#x26;dpr=4&#x26;quality=100&#x26;sign=ffd014bf&#x26;sv=2" alt="" data-size="line">**F12 – Venda com NF-e (Pedido)** <a href="#f12-venda-com-nf-e-pedido" id="f12-venda-com-nf-e-pedido"></a>

Existe a opção de enviar uma pré-venda direto para o sistema **NF-e** (Emissor de Nota Fiscal Eletrônica). Para isso, é necessário, após lançar os produtos na tela, informar o cliente através da tecla **F9**, selecionar a forma de pagamento e utilizar a tecla **F12**. Feito isso, o ícone do NF-e será exibido no canto superior esquerdo, conforme representado abaixo:

<figure><img src="https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FtScpZj0hoAGaPNaiHCuL%252FPre%2520vendas.PNG%3Falt%3Dmedia%26token%3Da08aa90f-5938-4592-a521-2a0d0ac2c61a&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=4dfb9b18&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Por fim, é necessário apenas informar o código do atendente e finalizar a pré-venda no botão **ok** ou utilizando a tecla **Enter**, e será gerado um registro da venda no NF-e.

<figure><img src="https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FsUzmeAeFrcag03PhBme3%252Fimage.png%3Falt%3Dmedia%26token%3D42135109-df2a-4384-8f20-798c0ea36252&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=c3f6d351&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**Observações**</mark>

{% hint style="danger" %}
* Quando o registro da venda é enviado para o NF-e, a pré-venda não é enviada para o sistema emissor de cupom fiscal.
* Ao enviar o registro de venda para o NF-e, o número de documento da mesma ficará zerado.
* Para realizar uma venda de pedido e necessário que o caixa esteja aberto.
{% endhint %}



