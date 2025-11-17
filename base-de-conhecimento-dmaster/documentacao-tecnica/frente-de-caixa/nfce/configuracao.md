# Configuração

Data de atualização: 13/03/2024 às 15:35h

{% hint style="info" %}
**IMPORTANTE** Antes de iniciar a configuração, todos os processos e requisitos descritos em [Instalação do NFC-e](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/instalacao-do-nfc-e) já devem estar concluídos.
{% endhint %}

### Requisitos para configuração <a href="#requisitos-para-configuracao" id="requisitos-para-configuracao"></a>

#### Versão dos aplicativos <a href="#versao-dos-aplicativos" id="versao-dos-aplicativos"></a>

Com os processos concluídos e requisitos atendidos, a configuração do NFCe pode ser iniciada. O primeiro passo é verificar se todos os sistemas DMASTER estão na última versão disponível, caso não estejam, é preciso atualizar. Para verificar a versão dos sistemas é utilizado o controle interno DMASTER, acessando o **cadastro do cliente** e na seção **dados do sistema**, clicar no botão **verificar versões**. Ao clicar no botão, o campo que ficar com a cor vermelha indica que o sistema está desatualizado.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FyF0GA4UENRgq2cpsOcqh%252Fversao%2520sistema.PNG%3Falt%3Dmedia%26token%3Dfbf2b53c-e885-42fd-bcb8-cb583823cae8&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=8168e4c9&#x26;sv=2" alt=""><figcaption></figcaption></figure>

### Configuração <a href="#configuracao" id="configuracao"></a>

#### Importando informações <a href="#importando-informacoes" id="importando-informacoes"></a>

Após certificar que todos os sistemas estão atualizados, deve ser realizada a inclusão das informações necessárias para o funcionamento do NFCe. Acessar o menu **utilitários > empresa > certificado digital & NFCe** no sistema DMASTER FARMA ou DMASTER SHOP. Ao abrir o módulo, as informações de CNPJ, razão social e regime tributário do estabelecimento já estarão preenchidas, de acordo com o cadastro do cliente no controle interno DMASTER. Insira as informações de **ID Token e CSC**, que foram gerados pela contabilidade do estabelecimento. Clicar no botão ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FRcXg57s7YHhhzmgCD6Qu%252Fbotao%2520certificado.png%3Falt%3Dmedia%26token%3D3adf5f12-15b5-44d3-88d3-d6d07e67db0d\&width=300\&dpr=4\&quality=100\&sign=18318860\&sv=2) , acesse o caminho onde o arquivo do certificado digital se encontra e após encontrá-lo, selecione e clique em abrir. Após selecionar o arquivo, o caminho é inserido no campo **path do certificado**. Agora o cliente deve digitar a **senha** do certificado. Com todas as informações preenchidas, clicar em **carregar** e os demais campos serão preenchidos, são eles:

* **Razão social:** razão social na qual o certificado digital foi emitido, que deve ser a mesma do estabelecimento;
* **CNPJ:** CNPJ no qual o certificado digital foi emitido, que deve ser o mesmo do estabelecimento;
* **Número de série:** número de série do certificado digital;
* **Dt. Emissão:** data de emissão do certificado digital;
* **Dt. Vencimento:** data de vencimento do certificado digital.
* **Data cadastro:** data que o processo de importação foi realizado no sistema DMASTER;

Após o carregamento das informações, clicar em **gravar** e aguardar o processamento. Ao final do processo, será gerada uma mensagem de conclusão do processo.

Ao clicar em gravar, o sistema precisa atualizar o certificado digital no cadastro do cliente no controle interno DMASTER e no Portal Invoisys. Para isso, ele precisa comunicar com o servidor da DMASTER e do Portal e por isso o processamento pode demorar alguns segundos.

<figure><img src="../../../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F5uat6rjHUapIlAz92gQy%252Fimportar%2520informacoes%25201.png%3Falt%3Dmedia%26token%3D26a9ce5c-f431-464f-b78b-925c20d2b3a2&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=26abde13&#x26;sv=2" alt="" width="563"><figcaption></figcaption></figure>

**Exportando tabela de cadastro de produtos inválidos**

Com a migração do modelo ECF para o NFCE a exigência de um cadastro de produto correto se tornou extremamente necessário para a emissão do documento fiscal. Com isso, será possível exportar uma tabela apenas com os produtos inválidos através do sistema DMASTER ou utilizar o gestor tributário para ajustar as informações fiscais inválidas dos produtos. A exportação da tabela(Ultilitários - Exportação de produtos) ou utilização do gestor tributário deves ser realizado de acordo com a documentação descrita em [Utilitários](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/farma-shop/utilitarios).

Após a exportação da planilha, caso tenha muitos produtos que precisam de ajuste, orientar o cliente sobre isso e verificar se ele prefere ajustar todos os produtos primeiro e depois finalizar a instalação do NFCe ou realizar a instalação e ir ajustando os produtos de acordo com as vendas realizadas.

Se o cliente optar por ajustar os produtos antes da instalação, deve orientá-lo a abrir um novo chamado quando finalizar o processo, para que possamos finalizar a instalação e o chamado de instalação de NFCe deve ser agendando para o setor operacional para 120 dias após a data atual. Caso ele opte por instalar o NFCe antes de realizar os ajustes, deve informar a ele que, se realizar venda dos produtos inválidos, será gerado erro que deverá ser corrigido por ele e caso atinja 50 vendas com erro, o sistema não permite emissão de novas vendas até que os erros sejam corrigidos.

Para realizar a correção dos produtos inválidos, o cliente tem tem duas opções:

1. Realizar a correção no cadastro do produto do sistema DMASTER produto por produto.
2. Realizar a correção diretamente na planilha CSV que foi exportada e posteriormente solicitar ao suporte DMASTER que faça a importação no sistema. A importação deverá ser realizada de acordo com documentação descrita em [Informações úteis](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/informacoes-uteis).
3. Via gestor tributario (IMendes).

#### Copiando arquivos <a href="#copiando-arquivos" id="copiando-arquivos"></a>

**IMPORTANTE**

Para clientes que ainda estão com impressora fiscal em funcionamento, antes de iniciar a instalação é preciso orientá-lo a retirar a redução Z da impressora e fazer o fechamento do caixa. Após realizar esse processo, não será possível reverter o processo de NFCe para ECF. Com isso, deve ser confirmado com o cliente se o processo de instalação poderá ser concluído naquele momento.

Para clientes que não utilizam impressora fiscal, deve orientar apenas a fazer o fechamento do caixa.

Para iniciar a configuração do NFCe, é preciso realizar a cópia dos arquivos do **Servidor DMASTER** para o **Terminal Caixa** do cliente. Acessar o caminho **\\\arquivos\Suporte\ 07. Utilitários de Sistema\15. NFCe.**&#x20;

Para **NFCe direto**, ou seja, realizando a comunicação direto com a SEFAZ-MG, deve copiar todos os arquivos da pasta Direto e colar na pasta **MBHSist do Terminal caixa** do cliente.

Caso o estabelecimento possua mais de um caixa, estes arquivos devem ser copiados para a pasta MBHSist de todos eles.

#### Instalando e configurando impressora <a href="#instalando-e-configurando-impressora" id="instalando-e-configurando-impressora"></a>

Após realizar a instalação da impressora, de acordo com os processos do link [Impressora Térmica](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/impressora-termica) , será necessário configurá-la. Para isso, é preciso **alterar o nome** e **compartilhar na rede**. Para isso, é preciso acessar o **painel de controle**, alterar a **exibição para ícones grandes** e clicar em **Dispositivos e impressoras.**

No link [Impressora Térmica](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/impressora-termica) **,** estão sendo explicados os processos de instalação de algumas das impressoras térmicas que é possível utilizar no frente de caixa DMASTER ECF, porém, qualquer impressora térmica irá funcionar, desde que esteja comunicando com o computador e realizando impressões.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FwXo33kruwXEhbuV4wsSa%252Fpainel%2520de%2520controle.PNG%3Falt%3Dmedia%26token%3Dc222615f-86e3-4aae-be5c-bd7bcc53343d&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=a20298b0&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Encontrar a impressora desejada, clicar com o **botão direito do mouse sobre ela** e selecionar a opção **Propriedades da impressora.** Na aba geral, alterar o nome da impressora para **NFCePrinter**, obrigatoriamente. Clicar na aba **compartilhamento** e marcar a opção **compartilhar esta impressora** e o nome do compartilhamento deve ser igual ao nome da impressora definido anteriormente.

O compartilhamento da impressora é realizado para que seja possível inserir o caminho do compartilhamento no ConfigECF e o DMASTER NFCE funcione corretamente.

Clicar em **ok** para concluir a configuração.

<figure><img src="../../../../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F1TVQ7xepchCQMwZ7zQ0V%252Fcompartilhamento%2520impressora.png%3Falt%3Dmedia%26token%3Db8dbd8ad-ab8f-449d-be71-42a7aea1d681&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=e14bc598&#x26;sv=2" alt=""><figcaption></figcaption></figure>

**Configurando o aplicativo**

O próximo passo é, de fato, a configuração do NFCe. Após essa configuração, o processo não pode ser revertido.

Abrir o aplicativo **DMConfigurações** e clicar no menu **NFCe**.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F76ZQPAhF2tAB4z1o8MoX%252Fnfce%2520dmconfiguracoes.png%3Falt%3Dmedia%26token%3D4747419e-17b7-4fc5-9897-eaa7818de9f2&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=520cafb1&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Na tela de configuração serão exibidas algumas informações, que serão explicadas a seguir.

* Os campos **CSC e ID CSC**, contém informações do estabelecimento que foram geradas pela contabilidade. Estes códigos fazem parte dos requisitos, descritos em [#requisitos-para-instalacao-do-nfc-e](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/instalacao-do-nfc-e#requisitos-para-instalacao-do-nfc-e);
* Os campos **usuário, senha e URL base**, contém informações da DMASTER. Email e senha do NFCe da DMASTER e caminho do portal Invoisys, para onde são enviados os registros de vendas realizadas pelo estabelecimento;
* O parâmetro ambiente, é onde é definido se a utilização do NFCe será no modo produção ou homologação. **OBRIGATORIAMENTE O AMBIENTE DEVE ESTAR COMO PRODUÇÃO.**
* O campo **path do XML Autorizado**, contém o caminho da pasta no **servidor** onde os arquivos XMLs das vendas de NFCe são salvos;
* Caso o cliente possua TEF, no campo **utiliza TEF** deve ser selecionado Sim;
* No campo **modo transacional**, deve ser selecionada a opção **por caixa (ECF)**;
* O parâmetro **exibir valor liquido do item no cupom**, deve ficar **marcado** por padrão e é utilizado para que o valor líquido dos produtos seja impresso no cupom fiscal.
* Por padrão, o cupom fiscal é impresso contendo a informação de razão social e nome fantasia. Caso o cliente queira que seja impresso apenas o nome fantasia, o parâmetro **suprimir razão social do cupom** deve ficar **marcado.**
* **Emissão direta com o SEFAZ-MG:** esse parâmetro será marcado quando o NFCe utilizar a comunicação direta com o SEFAZ e não mais com o Invoysis.
* A opção **\[F5] - Consultar último documento de NFCe no Invoisys** é utilizado quando é realizada substituição de servidor no estabelecimento e foram efetuadas vendas após o horário do backup utilizado na substituição. Com isso, utiliza-se esta opção para consultar se o número do último documento de NFCe emitido é igual ao último número do sistema. Caso seja diferente, o sistema irá atualizar o último número de acordo com o Invoisys.
* Ao clicar no botão **terminais NFCe,** é possível visualizar a informação de quais computadores estão configurados com o NFCe, ou seja, quais computadores possuem o aplicativo AppDMNFCe **EM EXECUÇÃO**. As informações exibidas na tela são: **nome do computador, número do caixa, data e hora de configuração do NFCe, e data e hora de atualização do aplicativo AppDMNFCe.** Quando é realizada a substituição do terminal caixa, é preciso excluir o registro que consta o número de caixa que será configurado em outro computador. Se o processo não for realizado, ao tentar abrir o AppDMNFCe, será gerado um erro informando que aquele número de caixa já está configurado em outro computador. Para excluir o registro de um computador, é preciso selecionar o registro desejado e clicar em **excluir.**

Após realizar todas as configurações necessárias, clicar em **Gravar** para que a configuração seja concluída.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FdaRAuwvinyEl3yVAnB0e%252FConfiguracao.png%3Falt%3Dmedia%26token%3D2307f310-d2c8-4929-a61e-4ab26e970e4f&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=4e5db556&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Configurando frente de caixa <a href="#configurando-frente-de-caixa" id="configurando-frente-de-caixa"></a>

Após as configurações anteriores, agora será necessário efetuar as configurações do frente de caixa. Para isso, abrir o ConfigECF e na aba configurações do ECF, verificar se o número do caixa está correto.

Se o cliente utiliza o frente de caixa não fiscal, o número do caixa estará maior que 10. Nesse caso, deve ser alterado para 1.

Caso o cliente possua mais de um caixa na loja, os números devem ser sequenciais e iniciados do número 1.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F21mdzeMpMwzu3tNlyock%252Fconfig%2520ecf%2520caixa.png%3Falt%3Dmedia%26token%3D6be95cb8-c1e8-4014-9422-8f78c2cce829&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=42cf04cc&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após a configuração do número do caixa, clicar na aba impressora fiscal e realizar as seguintes configurações:

* No campo **marca**, selecionar NFCe;
* Em **modelo não fiscal**, selecionar o modelo da impressora não fiscal utilizada pelo estabelecimento;
* No campo **porta,** inserir o **caminho do compartilhamento da impressora** que foi definido em [#configurando-impressora-nao-fiscal](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/nfce/configuracao#configurando-impressora-nao-fiscal);

O caminho do compartilhamento deve ser da seguinte forma: **\\\nomedocomputador\nomedaimpressora.**

**Exemplo:** \\\caixa\nfceprinter.

* No campo **tam. avanço papel**, por padrão, é selecionada a opção **5**;
* O parâmetro **impressão do documento** possui duas opções: **Perguntar em todos os cupons:** em toda venda finalizada, será perguntado ao usuário se deseja que o cupom fiscal daquela venda seja impresso; **Emitir todos os cupons:** o cupom fiscal de todas as vendas finalizadas serão emitidos.
* O parâmetro **largura de impressão**, também por padrão, é selecionada a opção **48 colunas**;
* Se a impressora possuir guilhotina, o parâmetro **impressora com guilhotina** deve ser marcada;
* O parâmetro **arredondamento de casas decimais** deve sempre ficar habilitado;
* Com todas as configurações realizadas, clicar no parâmetro **forçar recadastramento do ECF** e clicar em **salvar** para concluir o processo.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FW6z9H7ku79leOvFTQ88V%252Fconfigecf%2520.png%3Falt%3Dmedia%26token%3Dca5b8b42-1e82-481b-9a3d-5f64af8ab3fb&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=96d86f75&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Para o funcionamento correto do NFCe e impressão dos cupons fiscais, o aplicativo AppDMNFCe deve ficar em execução no terminal caixa, durante todo o funcionamento do estabelecimento.

A abertura do aplicativo é feita junto com o DMASTER ECF, ou seja, ao abrir o sistema de frente de caixa, o aplicativo do NFCe é iniciado e carregado próximo ao relógio.

Após realizar todas as configurações necessárias, os sistemas DMASTER devem ser reiniciados em todos os computadores, para que as informações alteradas sejam atualizadas em todos eles.
