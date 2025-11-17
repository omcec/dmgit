# Instalação

{% hint style="danger" %}
#### <mark style="color:$danger;">**Atenção**</mark>**: Esta instalação é somente para clientes que possui somente o contrato do sistema Dmaster SNGPC;**
{% endhint %}

1. Preparando o computador.&#x20;

&#x20; 1.1 Clicar em **Iniciar** e depois em **Painel de Controle.** E depois configurar o tipo de exibição para **Categoria**.&#x20;

<figure><img src="../../.gitbook/assets/image (120).png" alt=""><figcaption></figcaption></figure>

&#x20;1.2. Clicar em **Rede e Internet,** em Central de Rede e Compartilhamento e depois em \
**Alterar as configurações de compartilhamento avançadas.**&#x20;

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

&#x20;

1.3. Na tela seguinte marcar as seguintes opções:

* Ativar descoberta de rede.
* Ativar compartilhamento de arquivo e impressora.
* Desativar compartilhamento de pasta pública
* Usar criptografia de 128 bits (...).
* Desativar compartilhamento protegido por senha. Após marcar todas essas opções clicar em Salvar Alterações.&#x20;

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

2. Alterar o nome do Computador para o padrão do sistema e reiniciar o computador

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

3. Realizar a cópia e transferência dos arquivos referente ao sistema.&#x20;

&#x20;3.1. Copiar e transferir a pasta **MCSngpc em \arquivos\Suporte\05. Sistemas**, colar a pasta    em “C:\”.  Criar uma pasta vazia chamada **MCUtil**.

![](<../../.gitbook/assets/image (4).png>)    <img src="../../.gitbook/assets/image (5).png" alt="" data-size="original">

&#x20;

3.2. Copiar e transferir o arquivo SngpcNet.exe em **\arquivos\Suporte\02. Atualização de** \
**Executaveis\MCSngpc** e colar na pasta MCSngpc **em C:\ MCSngpc.**&#x20;

&#x20;  ![](<../../.gitbook/assets/image (10).png>)   ![](<../../.gitbook/assets/image (12).png>)



3.3. Copiar e transferir todos os arquivos da pasta **MCBackup em \arquivos\Suporte\02.**\
**Atualização de Executaveis\MCBackup** e colar na pasta MCSngpc em **C: \MCSngpc.**

&#x20;![](<../../.gitbook/assets/image (16).png>)  ![](<../../.gitbook/assets/image (17).png>)



3.4. Copiar e transferir o arquivo **1. MCDados Instalacao Dmaster Farma e Sngpc XX-XX.mdf em**\
**\arquivos\Suporte\04. Banco de Dados** e colar este arquivo na pasta MCSngpc em **C:\MCSngpc**\
**e renomeá-lo para MCDados.mdf.**

<figure><img src="../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>



4. Após a cópia dos arquivos iniciaremos a instalação e configuração dos sistemas.

4.1. Copiar o **setupServidor.exe** do caminho **\arquivos\Suporte\03. Instaladores**

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

4.2. Cole na MCUtil da máquina do cliente e execute o arquivo setupServidor.exe.

* Caso o computador não possua o Net Framework 3.5 e/ou 4.0 instalado, o instalador irá solicitar o download e instalação do mesmo.

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

4.3. Clicar em **Install** e aguardar.\
4.4. Será gerada a tela como mostrada abaixo. Clicar em **Next** > e depois clicar em **Install**.

<figure><img src="../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

4.5. Caso não ocorra nenhum problema com a instalação, será gerada uma tela igual a imagem\
abaixo. Clicar em **Finish**.

<figure><img src="../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

4.6. Após a instalação será gerada uma tela de configurações. Todas as opções já estarão marcadas \
como padrão, mas é orientado a verificar se será necessário realizar alguma alteração.\
Verificar se este computador será o **Terminal de Backup**, se sim, o parâmetro deverá ser\
marcado. Marcar o parâmetro **anexar banco de dados**.\
Clicar em **Executar**.

<mark style="color:$danger;">\*Se for necessário fazer alguma alteração. Clicar em Alterar e digitar a senha do dia.</mark>

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

4.7. Marcar todos os sistemas que serão configurados neste servidor e clicar em Gravar.

<figure><img src="../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

4.8. Aguardar a instalação do SQL Server. Poderá demorar vários minutos. Clicar em **OK** na\
mensagem gerada.&#x20;

Fechar a tela do instalador.

<figure><img src="../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

5. Exportar e importar dados da empresa.&#x20;

5.2. Abrir o arquivo **DM Configurações e digitar a senha do dia.**

<figure><img src="../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

5.3. Clicar em **Dados da empresa**\
![](<../../.gitbook/assets/image (38).png>)



6.4. Na tela seguinte, na aba **Exportação**, inserir o código do cliente, apertar **Enter** e o nome\
fantasia do estabelecimento será carregado. Após as informações de código e nome fantasia\
carregados, clicar em **Exportar Dmaster.** Será aberta a tela para inserir login e senha do controle interno Dmaster. Após inserir a informações, clicar em **Entrar**.

<div><figure><img src="../../.gitbook/assets/image (39).png" alt="" width="362"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure></div>

6.5. Clicar em **Importação.** Clicar em **pesquisar** e selecionar o arquivo para ser importado.\
Após selecionar o arquivo **.json**, clicar em **Abrir** e logo após, clicar em **Importar Dados**.

<div align="left"><figure><img src="../../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (121).png" alt=""><figcaption></figcaption></figure></div>

7. Configurar o backup.

&#x20;7.1. Clicar em **Configuração > Backup.** Configurar o backup com os dados corretos. Clicar em **Gravar** e o backup será iniciado automaticamente.

<figure><img src="../../.gitbook/assets/Sem título.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (125).png" alt="" width="269"><figcaption></figcaption></figure>

8. Após as instalações, iremos configurar o **DMASTER - Sngpc.**&#x20;

8.1. Abrir o arquivo **Config.ini** em **C:\MCSngpc** e realizar as seguintes configurações:

* Em Servidor digitar: LocalHost;
* Em Base digitar: MCDados;

{% hint style="warning" %}
<mark style="color:red;">Em StatusManipulacao digitar:</mark>&#x20;

**0 (Se cliente não trabalhar com produto manipulado)**&#x20;

**1 (Se cliente trabalhar com produto manipulado);**
{% endhint %}

* Em VerificacaoOnLine digitar 1 Salvar e fechar o arquivo após as alterações.![](<../../.gitbook/assets/image (130).png>)    ![](<../../.gitbook/assets/image (131).png>)



8.2. **Abrir** o sistema **Dmaster Sngpc**. O mesmo deverá abrir normalmente.&#x20;

<figure><img src="../../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>

9. Servidor **Dmaster Sngpc** instalado e configurado.









{% file src="../../.gitbook/assets/Instalação DMASTER SNGPC Avulso 4.docx.pdf" %}

