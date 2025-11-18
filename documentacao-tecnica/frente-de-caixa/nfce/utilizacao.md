# Utilização

{% hint style="info" %}
Com a configuração do NFCe concluída, é possível acessar um novo menu no DMASTER FARMA e DMASTER SHOP. Ao acessar a tela de pré-vendas e utilizar a tecla **F2**, é aberta a tela de **manutenção da emissão de NFCe**. Esta tela será utilizada para realizar alguns processos do NFCe que serão explicados posteriormente.
{% endhint %}

{% hint style="info" %}
**Tipos de emissão do cupom fiscal**

**Normal:** quando a comunicação com o Sefaz está funcionando corretamente, então a venda é autorizada na hora da impressão do cupom fiscal;

**Em contingência:** quando a comunicação com o Sefaz não está funcionando corretamente, então o cupom fiscal é impresso em contingência, mesmo que a venda possua erros, para que o estabelecimento não fique sem imprimir cupom fiscal para seu cliente final, mas a venda ainda não foi autorizada no Sefaz, ou seja, caso possua algum erro naquela venda, após a normalização da comunicação com o Sefaz, o erro será exibido na tela de manutenção de NFCe para que seja realizada a devida correção. Caso esteja tudo correto com a venda, ao normalizar a comunicação com o Sefaz, ela será enviada automaticamente e sairá da tela de manutenção da emissão de NFCe.
{% endhint %}

{% hint style="info" %}
Caso o cupom fiscal tenha sido impresso em contingência e ao comunicar com o Sefaz o sistema informar que a venda possui erro, ao corrigir e reenviar a venda, o cupom fiscal não será impresso, porque já foi impresso em contingência na finalização da venda.
{% endhint %}

#### **Aplicativo em Contingência** <a href="#aplicativo-em-contingencia" id="aplicativo-em-contingencia"></a>

Caso o aplicativo esteja executando em modo de contingência, ou seja, todos os cupons são emitidos em contingência por algum motivo, que podem ser, por exemplo, Sefaz indisponível e estabelecimento sem internet. Para saber se o aplicativo está operando em contingência, é necessário abrir o mesmo e verificar se está com o símbolo ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FgvV08rouMKzUNx6X2XMQ%252Fimage.png%3Falt%3Dmedia%26token%3Dcd6e0a14-a937-4232-b703-b1ca3c1f8f4c\&width=300\&dpr=4\&quality=100\&sign=9991cb38\&sv=2).

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FqaHAgN2K2goycl43fQmk%252Fimage.png%3Falt%3Dmedia%26token%3Dc3016136-8bb5-4f0c-a2de-ae4c4661815e\&width=300\&dpr=4\&quality=100\&sign=45d32e1\&sv=2)

Com o aplicativo do NFCe em execução, as vendas podem ser realizadas normalmente. Ao finalizar uma venda no frente caixa, será exibida no topo da tela a mensagem **Autorizando a NFCe Aguarde...** Se a venda for finalizada sem erros, será exibida a mensagem **Imprimindo NFCe...**

{% hint style="info" %}
O tempo limite para impressão do cupom e/ou autorização da venda é 99 segundos.
{% endhint %}

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fl4PWvUnc6DEFDBs0PhIv%252Fautorizando.png%3Falt%3Dmedia%26token%3D9ae5d537-a96a-44a1-bc48-423c86328690&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=17f1ad90&#x26;sv=2" alt="" width="375"><figcaption><p>Exemplo do módulo de vendas do frente de caixa <br>aguardando autorização do documento de NFCE</p></figcaption></figure>



<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F41YjqkJx1PJQ71BBHMbM%252Fimprimindo.png%3Falt%3Dmedia%26token%3D5af18a89-098f-44af-92b3-460aabf23b5e&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=9ae35a63&#x26;sv=2" alt="" width="375"><figcaption><p>Exemplo do módulo de vendas do frente de caixa <br>aguardando impressão do documento de NFCE</p></figcaption></figure>

#### Adiantar consulta de venda aguardando o Sefaz <a href="#adiantar-consulta-de-venda-aguardando-o-sefaz" id="adiantar-consulta-de-venda-aguardando-o-sefaz"></a>

Ao finalizar uma venda, caso haja algum problema na comunicação com o Sefaz, a venda ficará com o status **Aguardando confirmação do Sefaz de recebimento da NFCe em contingência.** **Próxima consulta (data e hora)**. Com esse status na venda, é possível que ela seja consultada antes do horário que esteja informado na mensagem. Para realizar a consulta naquele momento, são utilizadas as teclas **Shift + F5**. Após realizar o comando, a hora será atualizada na mensagem e a consulta será realizada. Caso a comunicação já esteja normalizada, a venda será enviada. Caso contrário, o horário será atualizado para mais tarde, e assim a consulta vai sendo realizada até que a comunicação se normalize.

O processo de adiantar a consulta da venda no Sefaz é **utilizada apenas pela equipe DMASTER**, não sendo necessário passar a informação para o cliente.

Para visualizar as vendas com status aguardando o Sefaz, é preciso utilizar a tecla F4 ou marcar o parâmetro \[F4] - Visualizar agendamentos, na tela de manutenção da emissão de NFCe.

#### Reenvio de vendas com erro <a href="#reenvio-de-vendas-com-erro" id="reenvio-de-vendas-com-erro"></a>

Para facilitar o reenvio das vendas que estão com erro na tela de manutenção de NFCe, pode ser utilizado as teclas **Shift+F6.** Dessa forma, todas as vendas com erro serão enviadas pelo sistema uma a uma, sem a necessidade de realizar o reenvio manual de cada registro com erro.

Caso possua uma venda com erro e esta for reenviada, o aplicativo NFCe do caixa onde ela foi realizada deve estar aberto. Caso contrário, o cupom da venda não será impresso e a venda não será autorizada.

#### Cancelamento de cupom fiscal <a href="#cancelamento-de-cupom-fiscal" id="cancelamento-de-cupom-fiscal"></a>

Qualquer venda que esteja na tela de manutenção da emissão de NFCe aguardando confirmação ou aguardando envio para o Sefaz, não é possível cancelar o cupom fiscal e fazer devolução da venda. É necessário aguardar que a venda seja autorizada no Sefaz para realizar tais processos.

O cancelamento do cupom fiscal pode ser feito em até **30 minutos** após a autorização da venda. No processo de cancelamento não é impresso **nenhum** cupom referente ao mesmo.

Para realizar o cancelamento do cupom, é preciso verificar o número do cupom fiscal, acessar a tela de **manutenção da emissão de NFCe** e no campo **cancelamento NFCe**, inserir o **número do cupom fiscal** e clicar em **Enviar**. Após clicar em enviar, confirmar a mensagem de cancelamento, informar o motivo na próxima tela e aguardar o processamento. Ao final do processo de cancelamento, é preciso realizar a devolução da venda no menu **Operacional > devoluções**.

No NFCe, a devolução da venda só pode ser total. Não é possível realizar devolução parcial, exceto se a devolução em questão for de produto de SNGPC. **(Para estabelecimentos que possuem SNGPC integrado)**

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fw2sRw4NgmadpgfEaCiRI%252Fimage.png%3Falt%3Dmedia%26token%3D211bbe88-cbc3-4125-97d2-dd8558aab810\&width=768\&dpr=4\&quality=100\&sign=7ebaa3c3\&sv=2)Exemplo do cupom fiscal de NFCE

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FeDMWAAnckvShEP3TGE6T%252Fimage.png%3Falt%3Dmedia%26token%3D96d5851f-0f06-4992-b4ee-5be49d861412&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=e86f23b7&#x26;sv=2" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FvbK6oikcrtF3WmEeEMi6%252Fimage.png%3Falt%3Dmedia%26token%3D498f2f97-598b-4c63-bc13-40ebaea3b87b&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=29c585e9&#x26;sv=2" alt=""><figcaption><p>Exemplo do módulo de devolução de venda.</p></figcaption></figure>

Após exceder o prazo de 30 minutos, o cancelamento do cupom fiscal deve ser realizado pela contabilidade ou o estabelecimento deve emitir uma nota fiscal eletrônica no sistema DMASTER NFe para acobertar aquele cupom.

#### Reimpressão de cupom fiscal <a href="#reimpressao-de-cupom-fiscal" id="reimpressao-de-cupom-fiscal"></a>

No NFCe é possível realizar a reimpressão de cupons fiscais. Para isso, é preciso acessar a tela de **manutenção da emissão de NFCe** e no campo **reimpressão NFCe**, digitar o **número do cupom fiscal** e clicar em **enviar.**

A reimpressão de cupom fiscal de NFCe pode ser realizada quantas vezes forem necessárias e qualquer venda que tenha sido realizada.

Ao utilizar o comando de reimpressão, apenas o cupom fiscal da venda é impresso, ou seja, se a venda possuir cupom vinculado, este não é reimpresso.

Ao enviar o comando de reimpressão, o cupom é reimpresso no caixa em que foi realizada a última venda.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FU1zYbw7UCD0R5iOk8LiK%252Fimage.png%3Falt%3Dmedia%26token%3D2e831772-aad8-49cb-9fb0-95b51278fa4c&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=65806bc4&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Inutilizar número de NFCe <a href="#inutilizar-numero-de-nfce" id="inutilizar-numero-de-nfce"></a>

Esta opção será utilizada para **inutilizar** determinado número de NFC-e. É necessário apenas digitar o **número do NFC-e** que será inutilizado e clicar em **Enviar**.

**Informações**

Normalmente esta funcionalidade não tem muito valor para o usuário do sistema, tendo em vista que o próprio sistema já possui a inteligência de verificar os pulos de sequencia e realizar o comando de inutilização automaticamente ao devolver uma venda ou ao baixar o movimento mensal.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FpOX6MdNb0niUmT0Xn718%252Fimage.png%3Falt%3Dmedia%26token%3D2787cb01-5c18-4994-b678-cb71230f5a02&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=bb23f25&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Relatórios NFCe <a href="#relatorios-nfce" id="relatorios-nfce"></a>

Se houver vendas com erro pendente de correção ou aguardando o Sefaz no período selecionado, é possível visualizar o relatório, porém as vendas com erro não constarão nele.

Para baixar os arquivos do NFCe, não pode haver venda com erro pendente de correção ou aguardando o Sefaz no mês desejado.

Esta opção é utilizada para baixar os XMLs e relatório das vendas de NFCe emitidas. É possível também visualizar e salvar apenas o relatório.

Para visualizar apenas o relatório, é preciso acessar a tela de **manutenção da emissão de NFCe,** no campo **relatórios NFCe**, inserir o **período** desejado e clicar em **ok**. Após esse processo, o relatório será aberto com informação de todas as vendas que foram realizadas naquele período.

<figure><img src="../../../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FYawydjSIvllYaaTZBaBs%252Fimage.png%3Falt%3Dmedia%26token%3D9234e962-c742-4a02-8a0e-4461b04588ef&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=857ad837&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Download de XML NFCE <a href="#download-de-xml-nfce" id="download-de-xml-nfce"></a>

**Download de XML do movimento do mês**

Para baixar os arquivos do NFCe (relatórios e XMLs das vendas), é preciso utilizar o botão![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fwki8LYXYs1VrIrz205ax%252Fbaixar%2520arquivos.png%3Falt%3Dmedia%26token%3D708ea3fe-089b-43d3-871b-16d706bc2cf2\&width=89\&dpr=4\&quality=100\&sign=533bea49\&sv=2). Na próxima tela, selecionar a opção **movimento do mês** e clicar em **ok**. Na tela seguinte, selecionar o **mês** desejado e clicar em **ok.** Agora será necessário selecionar onde os arquivos serão salvos. Eles podem ser salvos em qualquer pasta do computador, podendo ser escolhido pelo cliente. Após selecionar o local, clicar em **ok** e a baixa dos arquivos iniciará. Os arquivos são baixados de 7 em 7 dias e o ao final, é criada uma pasta com o nome NFCe, no local selecionado pelo cliente. Nesta pasta irá constar dois arquivos, uma pasta contendo todos os arquivos e a mesma pasta compactada, para que o cliente consiga enviar por e-mail, se necessário.

​![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2Ffiles.gitbook.com%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F5M6GuxtXs97WsaJy0oX5%252Ftipo%2520de%2520baixa.png%3Falt%3Dmedia%26token%3Df365007e-04a2-41c0-8950-0ce975669f9d\&width=300\&dpr=4\&quality=100\&sign=2df2b76c\&sv=2) ​​![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2Ffiles.gitbook.com%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F11l4Ns1b6ZjAZGKUbIQa%252Fselecionar%2520mes.png%3Falt%3Dmedia%26token%3Db9d057be-1f3b-4ba0-aaf4-d9400c34070d\&width=300\&dpr=4\&quality=100\&sign=f58d19be\&sv=2)​​![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2Ffiles.gitbook.com%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fz3GBCR68fixHdwevVC3m%252Fsalvar.png%3Falt%3Dmedia%26token%3Daaca328b-6c16-4605-bc68-5818c9063303\&width=300\&dpr=4\&quality=100\&sign=717a764b\&sv=2) ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2Ffiles.gitbook.com%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FFnHZrOsNcZKlEiQYMePE%252Farquivos%2520nfce.png%3Falt%3Dmedia%26token%3Debc2af93-a2ac-48fd-b86f-4ed6f1f5ac0f\&width=300\&dpr=4\&quality=100\&sign=65a9a33e\&sv=2)

**Logo**

Inicialmente a logo impressa no cupom será do NFC-e. Caso o cliente possua sua própria logo e queira inserir no cupom de NFC-e, deve ser enviado o arquivo com dimensão **107 x 120** e extensão **PNG**. Esse arquivo deve estar com nome **logodanfe.png** e deve ser copiado para a pasta **MBHSist do cliente**. Após esse processo, a logo do cliente será impressa no cupom fiscal.

O processo de envio dos arquivos XMLs e relatório é o que substitui a redução Z que era impressa na impressora fiscal.

O processo de baixa dos arquivos (relatório e XMLs) é realizado mensalmente, pois o estabelecimento precisa enviar estes arquivos para sua contabilidade. No inicio do mês, este processo é realizado para baixar os arquivos de vendas do mês anterior.

**Download de XML por documento**

É possível também realizar a baixa do XML por número do cupom fiscal. Para isso, na tela de **tipo de baixa**, é selecionada a opção **por documento** e na tela seguinte é informado o **número do cupom fiscal** que o usuário deseja baixar. Após informar o número do cupom fiscal, selecionar o local desejado para salvar o arquivo.

O XML do número desejado é salvo no local desejado dentro de uma pasta cujo nome será **"nfce-\[ número do cupom fiscal ]"**.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FMWGn7SHQ9wdS3dHAY8wM%252Fnfce%2520numero.png%3Falt%3Dmedia%26token%3D7b7b5643-9500-433c-890d-74f75e4d42c8\&width=768\&dpr=4\&quality=100\&sign=700f127\&sv=2)Exemplo do XML do documento salvo

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FGEICKWXROxIPCtVVGJKV%252FTipo%2520de%2520baixa.PNG%3Falt%3Dmedia%26token%3De044ebd6-2f20-4d4e-a3d7-5f0edd6bbaee\&width=768\&dpr=4\&quality=100\&sign=3017b4a3\&sv=2)Seleção de baixa de XML por documento

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fu2xTuwMv2QtnqgzlGJ7c%252Fbaixa%2520documento.PNG%3Falt%3Dmedia%26token%3D9c914638-0f06-401a-b697-d16051034b38\&width=768\&dpr=4\&quality=100\&sign=570205d7\&sv=2)Seleção do número do NFC-e para baixa do XML

**Download XMLs NFCe Direto**

O processo de baixa dos arquivos XMLs das vendas quando é utilizado o NFCe direto pode ser demorado, pois ele verifica se os XMLs constam na pasta de XMLS autorizados do servidor da loja, e em caso positivo, cria o arquivo XML na pasta NFCe da área de trabalho. Caso o XML não exista na pasta, é realizado o download direto da SEFAZ e criado na pasta NFCe da área de trabalho.
