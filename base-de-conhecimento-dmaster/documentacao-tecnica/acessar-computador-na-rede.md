# Acessar computador na rede

#### Como acessar um computador na rede ? <a href="#como-acessar-um-computador-na-rede" id="como-acessar-um-computador-na-rede"></a>

Sabemos que é possível acessar um computador pela rede, desde que a rede de ambos seja a mesma. Para que isso seja possível, são necessários alguns requisitos:

* Os computadores devem estar na **mesma rede**, para isso, o endereço IP de cada um deve estar na **mesma faixa**;
* Os computadores devem estar com a rede funcionando corretamente;
* A opção **ativar descoberta de rede** deve estar **habilitada** tanto no computador que vai acessar, quanto no computador que vai ser acessado no caminho **Painel de controle > Central de rede e compartilhamento > alterar as configurações de compartilhamento avançadas > Ativar descoberta de rede;**
* Para que seja possível visualizar também as pastas compartilhadas no computador acessado, a opção **ativar compartilhamento de arquivo e impressora** deve estar habilitada no caminho **Painel de controle > Central de rede e compartilhamento > alterar as configurações de compartilhamento avançadas > Ativar compartilhamento de arquivos e impressoras.**

{% hint style="info" %}
**Exemplos de IP na mesma faixa e rede:** 192.168.<mark style="color:red;">**5**</mark>.12 e 192.168.<mark style="color:red;">**5**</mark>.13.&#x20;

**Exemplo de IP em faixa e redes diferentes:** 192.168.<mark style="color:red;">**1**</mark>.2 e 192.168.<mark style="color:red;">**5**</mark>.1. O que identifica se estão na mesma rede é o <mark style="color:red;">**terceiro campo**</mark><mark style="color:red;">.</mark>&#x20;

Se os números estão diferentes é porque não estão na mesma rede.
{% endhint %}

Com os requisitos atendidos, deve-se seguir os passos.

Na barra de busca do Windows, digitar **\\\NomeDoComputador ou \\\IPdoComputador** e utilizar **Enter.** Se a comunicação entre eles estiver funcionando, na nova tela aberta será exibido todo o conteúdo compartilhado daquele computador, como pastas, impressoras e etc.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fnobkp6r54nCMjaneJCqW%252Facessando%2520pc.png%3Falt%3Dmedia%26token%3D11921d1a-0ac4-4254-9717-c2361e3d7358\&width=768\&dpr=4\&quality=100\&sign=39829963\&sv=2)

Se desejar acessar uma pasta diretamente, é preciso digitar **\\\NomeDoComputador\NomeDaPastaCompartilhada ou \\\IPdoComputador\NomeDaPastaCompartilhada** e utilizar **Enter,** assim, se a comunicação estiver funcionando e a pasta estiver compartilhada corretamente, o conteúdo da pasta será exibido.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FRqr0Bz1MrfnDJH1ZmrQm%252Facessando%2520pasta.png%3Falt%3Dmedia%26token%3De699bc0d-4418-4965-a072-c98e5a0996aa\&width=768\&dpr=4\&quality=100\&sign=4ad1341d\&sv=2)

Caso os requisitos não tenham sido atendidos, ao tentar acessar um computador na rede é exibida a mensagem informando que o Windows não pode acessar o caminho informado.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FpY2DO7WcN0vXVTn0AMlp%252Fsem%2520acesso.PNG%3Falt%3Dmedia%26token%3D988c22d0-0033-4bb2-b3be-a353b74d8f34\&width=768\&dpr=4\&quality=100\&sign=7610d71c\&sv=2)
