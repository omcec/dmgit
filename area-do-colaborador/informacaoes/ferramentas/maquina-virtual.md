# Maquina Virtual

### O que é máquina virtual ? <a href="#o-que-e-maquina-virtual" id="o-que-e-maquina-virtual"></a>

Uma máquina virtual (VM) ou _virtual machine_ é um programa que simula um ambiente computacional, capaz de executar sistemas operacionais e aplicativos como se fosse uma máquina física. Também chamada de processo ou camada de virtualização, permite rodar um sistema operacional dentro de outro.

O processo é diferente de um emulador, que visa copiar os recursos de um programa ou sistema e fazê-lo rodar em conjunto com o seu computador. Neste caso, a máquina virtual opera de forma completamente independente e isolada, podendo inclusive rodar sistemas operacionais que normalmente não seriam compatíveis com sua arquitetura.

**Fonte:** [**TecnoBlog**](https://tecnoblog.net/responde/o-que-e-uma-maquina-virtual/)

### O que é Hyper-V ? <a href="#o-que-e-hyper-v" id="o-que-e-hyper-v"></a>

**Hyper-V** é uma tecnologia que permite a virtualização do hardware em um computador físico. Em outras palavras, é possível criar e gerenciar computadores virtuais e seus recursos, onde cada máquina virtual (VM) é considerada um sistema isolado. Uma aplicação prática e muito comum para isto é a utilização de diversos sistemas operacionais em uma mesma máquina.

O Hyper-V é baseado no hipervisor que é uma camada adicional entre os recursos físicos e virtuais, responsável por gerenciar para que os recursos de hardware da máquina seja distribuída eficientemente entre as VMs.

**Fonte:** [**Portal GSTI**](https://www.portalgsti.com.br/hyper-v/sobre/)

#### **Documentação oficial do Hyper-V** <a href="#documentacao-oficial-do-hyper-v" id="documentacao-oficial-do-hyper-v"></a>

**Documentação:** [**https://docs.microsoft.com/pt-br/virtualization/hyper-v-on-windows/**](https://docs.microsoft.com/pt-br/virtualization/hyper-v-on-windows/)

### Hyper-V <a href="#hyper-v" id="hyper-v"></a>

#### Habilitando o Hyper-V no Windows 10 <a href="#habilitando-o-hyper-v-no-windows-10" id="habilitando-o-hyper-v-no-windows-10"></a>

O Hyper-V é um recurso nativo das versões Pro e Enterprise do Windows 10, com uso voltado a usuários corporativos e, por causa disso, não está disponível na versão Home.

Mesmo nas versões compatíveis, especialmente a Pro (que é acessível a usuários finais) o Hyper-V não vem instalado por padrão. Logo, você precisa ativar o programa antes de usa-lo:

1. Digite “Ativar ou desativar recursos do Windows” no campo de busca do Windows 10 e clique na opção que aparecer;
2. Marque a caixa “Hyper-V” e clique em “OK”;
3. O Windows 10 irá instalar os recursos do Hyper-V no computador;
4. Ao final do processo, clique em “Reiniciar agora” e reinicie o Windows.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2Ffiles.tecnoblog.net%2Fwp-content%2Fuploads%2F2019%2F08%2Fhyper-v-002-700x368.jpg\&width=768\&dpr=4\&quality=100\&sign=d0cf0a2e\&sv=2)Painel de controle / Programas e Recursos / Recursos do Windows / Hyper-V

**Fonte:** [**Tecnoblog**](https://tecnoblog.net/responde/como-criar-uma-maquina-virtual-com-o-hyper-v/)

#### **Criando uma placa de rede virtual** <a href="#criando-uma-placa-de-rede-virtual" id="criando-uma-placa-de-rede-virtual"></a>

Para termos conectividade nas maquinas virtuais que serão criadas precisaremos criar uma placa de rede de acordo a nossa necessidade. Para criar uma placa de rede virtual é necessário seguir os seguintes passos:

1. Abra o **Gerenciador do Hyper-V**;
2. Acesse **Ação -> Gerenciador de comutador virtual;**
3. Selecione a opção **"Novo comutador de rede virtual";**
4. Escolha o tipo de comutador virtual necessário para o seu cenário:
5. Clique em **"Criar comutador virtual";**
6. Defina o nome do comutador conforme sua escolha;
7. Caso seja o tipo do comutador seja "Externo" você deverá selecionar a placa de rede fisica para ele se associar.
8. Clique em OK;

**Tipos de comutador**

**Externo:** com esse comutador haverá comunicação entre todos os dispositivos, seja rede física ou virtual. Nesse caso é possível comunicar, máquina virtual com máquina virtual, Host e máquina virtual, ou com outros servidores e VMs fora desse Host. Resumindo: conexão com qualquer que seja o tráfego de rede.

**Interno:** com esse comutador as VMs só conseguem conversar com o Host físico e entre as VMs, não tem conexão externa, o switch nesse caso, ele não está conectado ao adaptador de rede físico.

**Particular:** com esse comutador não temos conexão com a rede física nem comunicação com o Host, só há conexões com as próprias VMs desse Host.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252F1SweukZqLmcX4prdlYU3%252Fimage.png%3Falt%3Dmedia%26token%3D302d2a89-6e00-41cf-bb95-6225c1eb9bca\&width=768\&dpr=4\&quality=100\&sign=c189be4f\&sv=2)

#### Criando uma máquina virtual <a href="#criando-uma-maquina-virtual" id="criando-uma-maquina-virtual"></a>

Com o Hyper-V ativo, você já pode criar uma máquina virtual. Embora ele ofereça algumas opções de instalação automática, como o Ubuntu, é recomendado que você já possua o arquivo de imagem do sistema **(ISO)** em seu computador.

O primeiro passo para criar a máquina virtual é abrir o programa Gerenciador do Hyper-V, que pode ser pesquisado no menu iniciar do computador.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FfwWPA3C4bKuRAMfnBeuD%252Fimage.png%3Falt%3Dmedia%26token%3D5bc127a0-ec96-48f8-a53f-c8690c840d39\&width=300\&dpr=4\&quality=100\&sign=e00f4e79\&sv=2)

Na tela inicial do gerenciador que será aberta, clique em **Novo**, ao lado direito e logo após clique em **Máquina Virtual**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FBoK0h2Bu5mfOTDK8Q7oU%252Fimage.png%3Falt%3Dmedia%26token%3D9d87d717-9a0a-464d-8798-d5aba22e2be4\&width=768\&dpr=4\&quality=100\&sign=b61fedba\&sv=2)

Na seção, **antes de começar**, clique em **avançar**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FgjUZFWjwTnjmFRtClYPc%252Fimage.png%3Falt%3Dmedia%26token%3D9ca58af8-0aa9-468d-9fc0-a313cce10304\&width=768\&dpr=4\&quality=100\&sign=8df67877\&sv=2)

Na seção **especificar nome e local**, será definido o nome da máquina virtual e onde os arquivos serão salvos. Preencha os campos com as informações desejadas e clique em **avançar**.

**Local da maquina virtual**

Caso deseje alterar o local onde os arquivos da maquina virtual serão salvos, é necessário clicar no **check box "Armazenar a máquina virtual em outro local"** e definir qual seria o local a partir do botão **"Procurar".**

**DMASTER - Local da maquina virtual**

Na DMASTER é orientado que todos os arquivos das maquinas virtuais sejam salvos dentro de uma pasta chamada HYPER-V que fique no C: do computador. (Caso esta pasta não exista, crie a mesma no path informado acima.)

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252F7Jdm6Es1nngrFknGFDAx%252Fimage.png%3Falt%3Dmedia%26token%3Da55cf0f7-6ec0-40a6-baac-8177f4aa5828\&width=768\&dpr=4\&quality=100\&sign=2d36139a\&sv=2)![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FNC5CJMKGkaCrORC1w5Qe%252Fimage.png%3Falt%3Dmedia%26token%3D300af953-8813-4561-ad0a-4ef92fa35398\&width=768\&dpr=4\&quality=100\&sign=269c21a2\&sv=2)

Na seção **especificar geração**, selecione a opção **geração 1** e clique em **avançar**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FOCK6KK9FLN8yNKYinDX8%252Fimage.png%3Falt%3Dmedia%26token%3De8d7b259-3545-4699-a682-279149835c1d\&width=768\&dpr=4\&quality=100\&sign=1520d374\&sv=2)

Na seção **atribuir memória**, será definido a quantidade de memória RAM da máquina virtual.

Preencha o campo com a informação desejada e clique em **avançar**.

**Quantidade de memória RAM da maquina virtual**

A quantidade de memória RAM da maquina virtual para ser definida deve levar em consideração a quantidade de memória RAM do computador físico e também se há outros processos em execução que exigem dessa memória RAM física, pois caso a memória RAM física não seja suficiente a maquina virtual não irá funcionar corretamente.

**Use a memória dinâmica para esta máquina virtual**

Ao deixar a opção de "**Use a memória dinâmica para esta máquina virtual"** habilitada a maquina virtual poderá utilizar uma quantidade de memória RAM dinamicamente, ou seja, ela poderá variar de acordo a necessidade da maquina virtual.

**OBS:** Não é orientado deixar essa opção habilitada, pois ela pode utilizar uma quantidade de memória RAM indesejada podendo causar lentidões e alguns problemas.

**DMASTER - Quantidade de memória RAM**

Na DMASTER é aconselhado definir a quantidade de memória RAM da maquina virtual **3072MB para servidores,** **2048MB para terminais e desmarcar** o parâmetro **use a memória dinâmica para esta máquina virtual.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FAXd6Kox7dceazcdNsPmM%252Fimage.png%3Falt%3Dmedia%26token%3D8a5886fc-17f0-4c9b-ba97-001c547eeaed\&width=768\&dpr=4\&quality=100\&sign=b746c9c9\&sv=2)

Na seção **configurar rede**, no campo **conexão**, selecione a placa de rede desejada e clique em **avançar**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252Fq7kgKFHuFQt31b0gZeys%252Fimage.png%3Falt%3Dmedia%26token%3D1019db64-efbc-4cd5-aeaa-3be91ed91b33\&width=768\&dpr=4\&quality=100\&sign=86b04d25\&sv=2)

Na seção **conectar disco rígido virtual (HD)**, deverá selecionar a opção desejada e clique em **avançar**.

**Opções de discos virtuais**

Dentre as opções disponíveis é possível criar um novo disco rígido virtual, definindo o seu nome, local de armazenamento no PC e tamanho, usar um disco rígido virtual existente, sendo necessário localizar onde está armazenado ou anexar um disco rígido virtual mais tarde.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FOMSV3KANm0dlbqU7B2hh%252Fanexar%2520disco.png%3Falt%3Dmedia%26token%3D4537cc53-82d4-470a-bf22-2c2f25bf293b\&width=768\&dpr=4\&quality=100\&sign=9385e868\&sv=2)

Na seção **resumo**, serão mostradas as informações da máquina virtual que está sendo criada. Se tudo estiver correto, clique em **concluir**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FI2SAJ0ovwBhTkxmtlPAZ%252Fimage.png%3Falt%3Dmedia%26token%3Dc434b482-e5a2-4eb9-b0f2-666c8713787e\&width=768\&dpr=4\&quality=100\&sign=2ccc99c8\&sv=2)

Após os processos acima, a máquina virtual foi criada e já pode ser iniciada. Para iniciá-la, clicar com o botão direito do mouse sobre ela e clicar em iniciar e posteriormente clique em conectar, ou utilizar o duplo click do mouse.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252Fw8DbasB6bOaHgnxQGQrT%252Finiciar%2520mv.png%3Falt%3Dmedia%26token%3D36ec9f94-f192-44c6-80f3-9360752612bc\&width=768\&dpr=4\&quality=100\&sign=c03d05ba\&sv=2)

#### Clonando uma máquina virtual <a href="#clonando-uma-maquina-virtual" id="clonando-uma-maquina-virtual"></a>

Para clonar uma maquina virtual é necessário seguir alguns passos e vamos exemplifica-los a seguir:

1. Criar uma maquina virtual com as especificações necessárias, mas definindo na seção "Conectar um disco rígido virtual" a opção "Anexar um disco rígido virtual mais tarde"
2. Na pasta da nova máquina virtual que foi criada, é preciso criar uma nova pasta com o nome **Virtual Hard Disks** e copiar o arquivo de disco rígido da pasta Virtual Hard Disks da máquina virtual inicial para essa pasta. Renomear o arquivo para o nome da máquina clonada que foi criada.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FgMjhPchq8Al3RTqp9L3L%252Fimage.png%3Falt%3Dmedia%26token%3D7f646d08-0ec1-4467-b638-c7c2b025fa36\&width=300\&dpr=4\&quality=100\&sign=f890bad9\&sv=2) ![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FpqfP7Tk34Mwv86zIUCKY%252Fimage.png%3Falt%3Dmedia%26token%3D8bb6ff34-68d9-4e88-b7c3-1c1963201033\&width=300\&dpr=4\&quality=100\&sign=1de8683\&sv=2)

Após o processo acima, clique com o botão direito do mouse sobre a máquina virtual criada e clicar em **configurações,** para anexar o disco rígido virtual clonado a ela.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252Fu8Ln6mKiIsJpWAqK06Td%252Fimage.png%3Falt%3Dmedia%26token%3D597c5bb4-2ec1-4e68-ac59-c4fd13b9183b\&width=768\&dpr=4\&quality=100\&sign=3644d795\&sv=2)

Na próxima tela, clique em **Controlador IDE 0,** selecione o **disco rígido virtual** e clique em **Adicionar**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FifTpDurqZ8xZU6iZnBKs%252Fimage.png%3Falt%3Dmedia%26token%3Db9faa016-6249-49d1-bc65-16e3478f7c2e\&width=768\&dpr=4\&quality=100\&sign=e5a6389\&sv=2)

Na opção **disco rígido virtual**, clique em **procurar**, acesse o caminho onde se encontra o disco rígido virtual copiad&#x6F;**,** selecione o arquivo do disco rígido virtual **(.vhdx)** e clique em **ok**.

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FdogTVdEAFqA8m9DAqsXY%252Fimage.png%3Falt%3Dmedia%26token%3Dabd556aa-1440-4a40-916d-4ef563e83ab6\&width=768\&dpr=4\&quality=100\&sign=f98a8d53\&sv=2)

Após os processos acima, a máquina virtual clonada já pode ser iniciada. Para iniciá-la, clicar com o botão direito do mouse sobre ela e clicar em conectar, ou utilizar o duplo click do mouse.

#### Excluindo uma máquina virtual <a href="#excluindo-uma-maquina-virtual" id="excluindo-uma-maquina-virtual"></a>

Caso seja necessário excluir uma máquina virtual, é preciso clicar sobre ela com o botão direito do mouse e clicar em **Excluir**.

**Após realizar a exclusão de uma maquina virtual não será possível recupera-la.**

![](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/~gitbook/image?url=https%3A%2F%2F3274737765-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F7FinqXqwN2Owb7BpFKU0%252Fuploads%252FJHrICaneDeiOBy3iUNYB%252Fimage.png%3Falt%3Dmedia%26token%3D774fc440-7bdd-4432-a9c6-ab7c93ea48c2\&width=768\&dpr=4\&quality=100\&sign=5c2efde8\&sv=2)
