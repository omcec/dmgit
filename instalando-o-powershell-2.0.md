# Instalando o PowerShell 2.0

Para ser possível realizar a instalação do SQL 2008, é necessário instalar o ps2DLC via powershell em modo administrador que ativa o PowerShell 2.0 nas versão do W11 despois de agosto.

Como mitigação temporária de último recurso, você pode reinstalar o PowerShell 2.0 usando as seguintes etapas:

a.       Baixe o arquivo [ps2DLC.zip](https://download.microsoft.com/download/2b37839b-e146-465a-a78c-c9066609c553/ps2DLC.zip) .

b.      Extraia o arquivo ps2DLC.zip para uma pasta de sua escolha. \
cd C:\Users\Bruno\Downloads\ps2DLC

c.       Inicie uma janela do PowerShell no modo de administração.

d.      Altere para a pasta que contém os arquivos extraídos do PowerShell 2.0.

e.       Execute o seguinte comando:

.\loadGAC.ps1&#x20;

Se for exibido o erro **"O arquivo loadGAC.ps1 não pode ser carregado porque a execução de scripts foi desabilitada neste sistema."**, é necessário seguir os passos abaixo:

1. Abra o **PowerShell** como administrador.
2. Execute o seguinte comando:

```powershell
// Set-ExecutionPolicy Unrestricted
```

Executar o .\loadGAC.ps1  novamente

<figure><img src=".gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>

&#x20;Após a instalação, o executável roda normalmente.

{% file src=".gitbook/assets/Para ser possível realizar a instalação do SQL 2008 (1).pdf" %}



&#x20;

&#x20;

&#x20;

&#x20;
