# Processo de Integração

### O que é INTEGRAÇÃO DMASTER FARMA - SNGPC?

A funcionalidade de integração DMASTER FARMA – SNGPC foi desenvolvida com o objetivo de facilitar o operacional da Drogaria, sendo que com a integração desabilitada, toda movimentação realizada com os produtos controlados pela ANVISA deve ser informada novamente no sistema DMASTER SNGPC. Com isso a integração DMASTER FARMA – SNGPC acaba com a redundância de processos na Drogaria, facilitando e agilizando todo o processo operacional, onde o próprio sistema se responsabiliza de gerar as informações para o sistema DMASTER SNGPC.

### Requisitos para realizar integração

Para habilitar a integração DMASTER FARMA – SNGPC é necessário que a situação do inventário esteja confirmada na ANVISA e no sistema DMASTER SNGPC. A necessidade de o inventário estar confirmado é para que não seja alterada nenhuma informação de produto, lote e estoque sem a devida operação/movimentação no sistema. Sendo assim o primeiro passo para habilitar a integração é o inventario estar confirmado na ANVISA e no sistema DMASTER SNGPC. É necessário também que a movimentação esteja em dia, pois as movimentações precisam estar alinhadas. Caso as movimentações não estejam em dia e for realizada a integração, se houver erros em movimentações anteriores, não será possível realizar correções.

### Aplicativo de integração (DMIntegraSNGPC)

Para habilitar a integração DMASTER FARMA – SNGPC é necessário utilizar o aplicativo DMIntegraSNGPC.exe. Ele será responsável por fazer as validações necessárias e ajustes para o bom funcionamento do sistema integrado

{% hint style="info" %}
O aplicativo DMIntegraSNGPC.exe é encontrado no caminho **\\\arquivos\Suporte\07. Utilitarios de Sistema\13. Integra SNGPC.** Todo o conteúdo da pasta Integra SNGPC deve ser copiado para a pasta MBHSist do Servidor do estabelecimento.
{% endhint %}

{% hint style="info" %}
Para realizar o processo de integração, não podem haver pré-vendas pendentes no sistema.
{% endhint %}

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F7TLJ7CEHoIqxp5CqkhdF%2FDmIntegraSNGPC.PNG?alt=media&#x26;token=62606f62-6c57-4c34-9ece-cc02371ae62e" alt=""><figcaption><p>Tela inicial do aplicativo DMIntegraSNGPC</p></figcaption></figure>

**Procedimentos realizados pelo aplicativo de integração nos cadastros de produtos**

O primeiro procedimento realizado pelo aplicativo DMIntegraSNGPC.exe é validar as informações do cadastro de produto do DMASTER FARMA, verificando os cadastros de produtos que estejam classificados como controlados pela ANVISA e que não estejam no cadastro de produto do SNGPC, ajustando cadastros com registro MS duplicado, validando produtos que estejam como fracionado e que estejam classificados como controlados pela ANVISA e ajustando cadastros de produtos com informações inválidas para produtos controlados pela ANVISA.

**Ajustes no cadastro de produto**

Neste procedimento o aplicativo irá validar se o cadastro do sistema DMASTER SNGPC está igual ao cadastro do DMASTER FARMA, validando se o cadastro do produto existe e se as informações de registro MS, classe terapêutica e tipo de receituário estão corretas. Se houver qualquer divergência entre os cadastros o aplicativo irá exportar um relatório para o usuário consultar e realizar os devidos ajustes manualmente.

**Ajuste do estoque realizado pelo aplicativo de integração**

O próximo procedimento a ser realizado é validar a movimentação do estoque de cada cadastro de produto classificado como controlado pela ANVISA. O estoque do DMASTER SNGPC será validado, por isso, se existirem produtos no DMASTER FARMA que a movimentação do estoque não esteja igual à soma dos lotes do sistema DMASTER SNGPC, o sistema irá solicitar autorização para realizar as devidas correções no estoque criando ajustes de estoque de entrada ou saída no DMASTER FARMA, sendo que os produtos que não estejam com a movimentação do estoque correta serão exportados para um relatório para consulta.

**Habilitação do parâmetro de integração SNGPC**

O último procedimento a ser realizado é habilitar o parâmetro de integração no sistema DMASTER FARMA, mas para isso todos os passos anteriores devem ter sidos realizados e estar marcados como concluído.

{% hint style="info" %}
Após a conclusão dos procedimentos é orientado que os sistemas DMASTER FARMA, DMASTER SNGPC, DMASTER ECF, DMINTEGRA e DMASTER NF-e sejam reinicializados para o carregamento do parâmetro de SNGPC integrado.
{% endhint %}

Os processos de utilização da integração deve ser verificada em utilizacao.
