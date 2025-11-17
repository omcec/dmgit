# Impressoras

<details>

<summary>Informações Importantes</summary>

Esse tipo de impressora, diferente da impressora fiscal, não necessita de nenhum procedimento de homologação, não possui memória interna e não realiza a impressão de redução Z, leitura X e leitura de memória fiscal.

Ela é utilizada para imprimir cupons fiscais, no caso de NFCe, ou cupons não fiscais, no caso do sistema de frente de caixa ser não fiscal, ou seja, os cupons impressos, não tem valor fiscal.

Para uma impressora térmica funcionar corretamente no sistema de frente de caixa DMASTER ECF, ela precisa estar instalada no computador e comunicando corretamente, ou seja, basicamente se a impressora for instalada e imprimir página de teste do Windows, provavelmente ela funcionará corretamente no sistema.

As impressoras térmicas que já funcionam no sistema hoje são: Bematech MP4200, Daruma DR800, Epson TM-T20, Elgin i7, Elgin i9, Evadin e ControlID. Mas basicamente, qualquer impressora térmica que comunique e imprima pelo Windows irá funcionar.

</details>

{% hint style="info" %}
Abaixo estão sendo explicados os processos de instalação de algumas das impressoras térmicas que é possível utilizar no frente de caixa DMASTER ECF, porém, qualquer impressora térmica irá funcionar, desde que esteja comunicando com o computador e realizando impressões.
{% endhint %}

Abaixo estão sendo explicados os processos de instalação de algumas das impressoras térmicas que é possível utilizar no frente de caixa DMASTER ECF, porém, qualquer impressora térmica irá funcionar, desde que esteja comunicando com o computador e realizando impressões.

### Epson TM-T20 <a href="#epson-tm-t20" id="epson-tm-t20"></a>

O primeiro passo para realizar a instalação da impressora térmica **Epson TM-T20** é copiar o arquivo **APD\_501a\_T20.exe do servidor DMASTER,** no caminho **\\\arquivos\Suporte\08. Impressoras\02. Não Fiscal\Epson\TM-T20\Windows\Advanced Printer Driver\V5** para a pasta **MCUtil do terminal caixa do cliente**.

Executar o aplicativo copiado e a instalação será iniciada.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FsuylcnNokV8ax4nBDv4O%252FInstalacao%2520impressora%2520Epson%2520nao%2520fiscal%2520driver.PNG%3Falt%3Dmedia%26token%3Db3611c6a-42fc-4b26-8f48-68315be7ce2b\&width=768\&dpr=4\&quality=100\&sign=e041f89c\&sv=2)

Na tela que abrir em seguida, clicar em **next** para confirmar a instalação.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FOeEGuk2qgXQOP4RrgOsS%252FInstalacao%2520impressora%2520Epson%2520nao%2520fiscal.PNG%3Falt%3Dmedia%26token%3Db2896e85-1863-4e97-9c44-313d8fa3b2f6\&width=300\&dpr=4\&quality=100\&sign=97f56ebf\&sv=2)

Depois, será necessário aceitar as condições. Para isto, é preciso marcar a opção **agree,** clicar em **install e** aguardar o processo de instalação do driver.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FgsIU0t6YsthqjDXwunOR%252FInstalacao%2520impressora%2520Epson%2520nao%2520fiscal%25201.PNG%3Falt%3Dmedia%26token%3Dd2ac6bd7-6a9f-4b42-8ad3-ff5c473ff57a\&width=300\&dpr=4\&quality=100\&sign=b9b532a6\&sv=2) ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FwxbuaeYb6ZC1YoHlA5fz%252FInstalacao%2520impressora%2520Epson%2520nao%2520fiscal%25202.PNG%3Falt%3Dmedia%26token%3Df8224906-35db-4797-8377-3a018d491e68\&width=300\&dpr=4\&quality=100\&sign=45cfa433\&sv=2)

Os drivers e utilitários serão instalados. Ao fim da instalação, será necessário registrar a impressora. Para isto, clicar em **next**.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F3JnNgLX6MQQ2pe8ViNZC%252FInstalacao%2520impressora%2520Epson%2520nao%2520fiscal%25203.PNG%3Falt%3Dmedia%26token%3D721fe6fb-4aeb-4144-8fbe-765a37771342\&width=300\&dpr=4\&quality=100\&sign=308d1fc8\&sv=2)

Na tela de configuração exibida em seguida, certificar que, na seção **Communication Settings**, a opção selecionada em **Port Type** é a mesma utilizada para ligar a impressora ao computador. Caso seja uma conexão USB, por exemplo, deve ser selecionada a opção USB. Para concluir a configuração, clicar em **Save Settings**.

Para definir a impressora como padrão no Windows, o parâmetro Set as default printer deve ser marcado.

<figure><img src="https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F6emCt3ofiaZAMBq0pdbz%252FInstalacao%2520impressora%2520Epson%2520nao%2520fiscal%25204.PNG%3Falt%3Dmedia%26token%3De250a221-febe-4e0c-a968-ad8eb074b5ac&#x26;width=300&#x26;dpr=4&#x26;quality=100&#x26;sign=d85cf301&#x26;sv=2" alt=""><figcaption></figcaption></figure>

Após salvar, será perguntado se deseja imprimir uma página de teste, podendo clicar em sim ou não, conforme a preferência.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FVOtwPhFZO1mBs5T35N79%252FInstalacao%2520impressora%2520Epson%2520nao%2520fiscal%25205.PNG%3Falt%3Dmedia%26token%3De15f7cac-4415-4372-bf9b-717291bc5983\&width=300\&dpr=4\&quality=100\&sign=5a2034dc\&sv=2)

Para finalizar a instalação do driver, clicar em **next** e na janela que abrir em seguida, clique em **close**.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FvtakfEWKg4WejdM9dQoH%252FInstalacao%2520impressora%2520Epson%2520nao%2520fiscal%2520concluido.PNG%3Falt%3Dmedia%26token%3D4ec6c018-956e-4a9b-9a27-387872971603\&width=300\&dpr=4\&quality=100\&sign=aa0109a2\&sv=2) ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FYWEWW8dPuna5Mf2Ve0C4%252FInstalacao%2520impressora%2520Epson%2520nao%2520fiscal%25206.PNG%3Falt%3Dmedia%26token%3D63d57a84-882e-4523-974d-769755b2e20a\&width=300\&dpr=4\&quality=100\&sign=cd197a88\&sv=2)

Após concluir a instalação, a impressora já pode ser encontrada em **Dispositivos e impressoras,** no painel de controle.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FNMi7UM3Xq3nZ1D5ow7D3%252FInstalacao%2520impressora%2520Epson%2520dispositivos%2520e%2520impressoras.PNG%3Falt%3Dmedia%26token%3Dbe676e2e-7970-4748-be6f-74cae78a4d9e\&width=300\&dpr=4\&quality=100\&sign=a7d13755\&sv=2)

### Evadin EP-26M <a href="#evadin-ep-26m" id="evadin-ep-26m"></a>

O primeiro passo para realizar a instalação da impressora térmica **Evadin EP-26M** é copiar o arquivo **POS Printer Driver Setup V7.17.exe** do **servidor DMASTER** , no caminho **\\\arquivos\Suporte\08. Impressoras\02. Não Fiscal\Evadin** para a pasta **MCUtil do terminal caixa do cliente.**

Executar o aplicativo copiado e a instalação iniciará. O primeiro aplicativo a ser instalado será o instalador do aplicativo de configuração e instalação da impressora.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FUi6OHlQLVSgW17ct6dfG%252FInstalacao%2520evadin%2520driver.png%3Falt%3Dmedia%26token%3D40e2b56e-4b07-4cf1-aad3-07d73e99b041\&width=300\&dpr=4\&quality=100\&sign=f5c85e50\&sv=2)

Na primeira tela do instalador, é preciso aceitar as condições do fabricante, para isso, deve-se selecionar a opção **Eu aceito os termos do contrato** e clicar em **avançar.**

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FxteVQ9bixd2Llgswh5nc%252FInstalacao%2520evadin%25201.png%3Falt%3Dmedia%26token%3Dd98510ed-7d74-44c6-a000-9163ee46afb5\&width=300\&dpr=4\&quality=100\&sign=33fc0d46\&sv=2)

Na próxima tela aberta, é informado o caminho onde o aplicativo de instalação será armazenado, sendo necessário apenas clicar em **avançar.**

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FeL1SN5GxmLmIi2kHIqDv%252FInstalacao%2520evadin%25202.png%3Falt%3Dmedia%26token%3D9d42b200-f17f-4d9d-a984-50b175d30a12\&width=300\&dpr=4\&quality=100\&sign=c408bb5a\&sv=2)

Na tela de tarefas adicionais que foi aberta, caso o parâmetro esteja marcado, após a finalização do processo, será criado um ícone do instalador na área de trabalho.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FvWTB6qX2eqc9azwjtBUR%252FInstalacao%2520evadin%25203.png%3Falt%3Dmedia%26token%3Dfa97e424-bc63-40c5-981a-fc6f69f5002d\&width=300\&dpr=4\&quality=100\&sign=c80eeb51\&sv=2)

Para finalmente iniciar a instalação do aplicativo, clicar em **instalar.**

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F8oWiyOEnUYttMdlQZQzC%252FInstalacao%2520evadin%25204.png%3Falt%3Dmedia%26token%3Df2eecf94-d15e-42fe-becf-514b45128c9b\&width=300\&dpr=4\&quality=100\&sign=50cc0651\&sv=2)

Na próxima tela, a instalação do aplicativo foi finalizada. Marcar o parâmetro **Executar POS Printer Driver V7.17,** para que o aplicativo de configuração e instalação da impressora seja executado e clicar em **concluir.**

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fm6TC8D0VfBOaFk0WwkxB%252FInstalacao%2520evadin%25205.png%3Falt%3Dmedia%26token%3Dee506610-2969-469c-a239-db15a8c1b0de\&width=300\&dpr=4\&quality=100\&sign=904e83cb\&sv=2)

Com a tela de instalação e configuração aberta, selecionar o tipo de conexão utilizado para ligar a impressora ao computador. Caso seja USB, por exemplo, selecionar a opção USB na seção **Printer Interface.** Na seção **Select Printer Series** selecionar **POS-80C.** Após as configurações, clicar em **install now, para que a impressora seja instalada**

O Windows é selecionado automaticamente de acordo com o computador.

Para definir a impressora como padrão no Windows, o parâmetro Set default printer deve ser marcado.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FXysxLFKgK7Dy7dmIUDay%252FInstalacao%2520evadin%25206.png%3Falt%3Dmedia%26token%3D61c78cc4-993c-4b2c-b336-1cf844c6ca20\&width=300\&dpr=4\&quality=100\&sign=96c9736d\&sv=2)

Após instalada a impressora, será perguntado se deseja configurar a impressora, podendo clicar em sim ou não, conforme a preferência. Se clicar em sim, será aberta a tela de propriedades da impressora, como mostrado abaixo.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252Fvuwfrxmnvv0l4A0hrgNC%252FInstalacao%2520evadin%2520propriedades.png%3Falt%3Dmedia%26token%3D1a3ff951-210e-41a6-8e42-cd04df507473\&width=300\&dpr=4\&quality=100\&sign=6f917137\&sv=2)

Após concluir a configuração e instalação, a impressora já pode ser encontrada em **Dispositivos e impressoras,** no painel de controle.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FFT51CsW7kc8Kkb2a3iaJ%252FInstalacao%2520evadin%2520painel%2520de%2520controle.png%3Falt%3Dmedia%26token%3D97430186-550c-4f83-b261-a3bff39cccaa\&width=300\&dpr=4\&quality=100\&sign=4e817811\&sv=2)

### Elgin i7 ou Elgin i9 <a href="#elgin-i7-ou-elgin-i9" id="elgin-i7-ou-elgin-i9"></a>

O primeiro passo para realizar a instalação da impressora térmica **Elgin i7 ou Elgin i9** é copiar o arquivo **ELGIN i9 Printer Driver\_v-1.7.3.exe** do **servidor DMASTER** , no caminho **\\\arquivos\Suporte\08. Impressoras\02. Não Fiscal\Elgin\i9** para a pasta **MCUtil do terminal caixa do cliente.**

Executar o aplicativo copiado e a instalação será iniciada.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FImAIqA02QtZE8EA2V3IU%252FInstalacao%2520Elgin%2520arquivo.PNG%3Falt%3Dmedia%26token%3Df485d9b2-e414-4087-be76-aaf2b09a5ada\&width=300\&dpr=4\&quality=100\&sign=5866a679\&sv=2)

Na primeira tela aberta, aceitar o contrato e clicar em **seguinte**.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FhaB9OUXeJcagSrwQYw7Y%252FInstalacao%2520Elgin.PNG%3Falt%3Dmedia%26token%3D4a7e0814-96c1-4052-a606-ed69e47df9bc\&width=300\&dpr=4\&quality=100\&sign=25712294\&sv=2)

Na tela seguinte, com a impressora conectada ao computador, selecionar a opção **instale o driver da impressora** e clicar em **seguinte.**

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252F8SxBWGUXcqJSgxVU6OSi%252FInstalacao%2520Elgin%25201.PNG%3Falt%3Dmedia%26token%3D4d404d67-bf08-40c3-88c7-07445a2a3032\&width=300\&dpr=4\&quality=100\&sign=57536979\&sv=2)

Para finalizar a instalação, na próxima tela, ao lado esquerdo, selecionar qual opção é utilizada para ligar a impressora ao computador e qual o modelo da impressora. Após as configurações, clicar em **seguinte**. Na janela seguinte, será informado que o processo foi concluído, então deve-se clicar em **concluir para fechar o instalador.**

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FMwfba5yJgxC2uw1sCx7z%252FInstalacao%2520Elgin%25202.PNG%3Falt%3Dmedia%26token%3D64f54fb6-53ac-4d73-8ee4-e3ae6e4dd9b9\&width=300\&dpr=4\&quality=100\&sign=7193a55a\&sv=2) ![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FNn95BhkvWzbyjt7p4JMQ%252FInstalacao%2520Elgin%25203.PNG%3Falt%3Dmedia%26token%3Dceb112ec-102d-4b35-850d-586a48c58063\&width=300\&dpr=4\&quality=100\&sign=9279d605\&sv=2)

Após concluir a instalação, a impressora já pode ser encontrada em **Dispositivos e impressoras,** no painel de controle.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FZtHwyRp5uE92xyrn1FMY%252FInstalacao%2520Elgin%2520dispositovs.PNG%3Falt%3Dmedia%26token%3Dddb9425a-bd7c-457f-8ac2-82be19fd7040\&width=300\&dpr=4\&quality=100\&sign=2919d721\&sv=2)

Caso ocorra erro na impressão de documentos após a instalação da impressora, deve ser instalado o driver conversor. Copiar o arquivo **PL2303-Prolific\_DriverInstaller\_v1200.exe** do servidor DMASTER, no caminho **\\\arquivos\Suporte\08. Impressoras\02. Não Fiscal\Elgin\i9\Conversor interno elgin (i9)\PL2303\_Prolific\_DriverInstaller\_v1200** para a pasta **MCUtil do terminal caixa cliente.**

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FQvgq9bvkmULosksHvemp%252Fdriver%2520elgin.png%3Falt%3Dmedia%26token%3D129255d7-816a-4b64-8b20-72986f66c4cd\&width=300\&dpr=4\&quality=100\&sign=2bb8ce71\&sv=2)

### Realizando impressão de teste <a href="#realizando-impressao-de-teste" id="realizando-impressao-de-teste"></a>

Para certificar que a impressora está comunicando com o computador pode ser realizada a impressão de uma página de teste do Windows. Se a comunicação estiver funcionando corretamente, a página de teste será impressa. Para realizar o processo, é preciso acessar o caminho **Painel de controle > Dispositivos e impressoras**, selecionar a impressora desejada, clicar sobre ela com o botão direito do mouse e clicar na opção **propriedades da impressora.**

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FZqR2L5lYM2M0G64z9chP%252Fpropriedades%2520da%2520impressora.png%3Falt%3Dmedia%26token%3D72358098-bbf9-4dae-a2cd-2d6f8a6fbe5a\&width=300\&dpr=4\&quality=100\&sign=f12b0812\&sv=2)

Na próxima janela aberta, clicar na opção **imprimir página de teste** e a impressão deve sair na impressora.

![](https://dmaster.gitbook.io/~gitbook/image?url=https%3A%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FxR9vHRCZrI448banCsbq%252Fimprimir%2520pagina%2520de%2520teste.PNG%3Falt%3Dmedia%26token%3D2b91250e-1360-47c7-8a92-e10957b530fc\&width=300\&dpr=4\&quality=100\&sign=1c26053f\&sv=2)
