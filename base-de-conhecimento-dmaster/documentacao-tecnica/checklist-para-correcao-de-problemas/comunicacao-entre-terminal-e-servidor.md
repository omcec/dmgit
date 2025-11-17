# Comunicação entre terminal e servidor

O erro de comunicação entre os computadores é bem comum e pode ocorrer por diversos motivos. Com isso, serão citados abaixo alguns pontos a serem verificados para que o erro seja constatado e solucionado. **Caso não seja possível resolver o erro após realizar todos os passos, uma solicitação de ajuda deve ser aberta para o responsável.**

{% hint style="info" %}
No final do documento estão descritas algumas soluções que já foram mapeadas pela equipe e documentadas no servidor arquivos DMASTER. Caso o erro seja constatado, consulte na seção abaixo se existe alguma solução já mapeada. [Algumas soluções já mapeadas pela equipe](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/checklist-para-correcao-de-problemas/comunicacao-entre-terminal-e-servidor#algumas-solucoes-ja-mapeadas-pela-equipe)
{% endhint %}

#### **Siga os passos abaixo em ordem a fim de encontrar onde esteja o erro de comunicação entre os computadores** <a href="#siga-os-passos-abaixo-em-ordem-a-fim-de-encontrar-onde-esteja-o-erro-de-comunicacao-entre-os-computa" id="siga-os-passos-abaixo-em-ordem-a-fim-de-encontrar-onde-esteja-o-erro-de-comunicacao-entre-os-computa"></a>

**Estado dos equipamentos**

* [ ] Servidor ligado
* [ ] Terminal ligado
* [ ] Cabo de rede conectado no servidor
* [ ] Cabo de rede conectado no terminal



**Configurações do sistema**

* [ ] Configuração de servidor correta no config.ini do terminal
* [ ] Validar comunicação via nome do servidor
* [ ] Validar comunicação via IP do servidor
* [ ] Data e hora de ambos os computadores estão corretas

{% hint style="info" %}
Para lojas que possuem a funcionalidade de acesso online, a informação do servidor no config.ini deve conter a porta SQL Server conforme configurada no Sql Configuration.&#x20;

**Exemplo:** \[ Nome do Servidor ] , \[ Porta do SQL ] | Nome Do Terminal | ......
{% endhint %}

**Configurações do SQL Server (Apenas no Servidor)**

* [ ] Serviço do SQL em funcionamento no servidor
* [ ] Conferir se a porta do SQL em funcionamento é a mesma utilizada no config.ini
* [ ] Pipes nomeados habilitados

**Reinicio dos equipamentos**

* [ ] Reiniciar servidor
* [ ] Reiniciar terminal
* [ ] Reiniciar TODOS equipamentos de rede

**Comunicação de rede**

* [ ] Servidor com conexão de rede
* [ ] Terminal com conexão de rede
* [ ] Servidor e terminal na mesma rede
* [ ] Terminal acessa o compartilhamento do servidor por nome
* [ ] Terminal acessa o compartilhamento do servidor por IP
* [ ] Terminal pinga o IP do servidor pelo CMD
* [ ] Servidor acessa o compartilhamento do terminal por nome
* [ ] Servidor acessa o compartilhamento do terminal por IP
* [ ] Servidor pinga o IP do terminal pelo CMD

**Configurações de compartilhamento**

* [ ] Configuração de descoberta de rede habilitada
* [ ] Configuração de compartilhamento de arquivo e impressora habilitada
* [ ] Configuração de compartilhamento por senha desabilitada
* [ ] Compartilhamento da pasta criado
* [ ] Permissão do compartilhamento da pasta realizada
* [ ] Segurança da pasta compartilhada realizada

**Configurações do Firewall**

* [ ] Parâmetro bloquear conexões de entrada no Servidor desabilitado
* [ ] Regras de entrada para a porta do SQL Server em funcionamento no servidor
* [ ] Regras de entrada para a porta do SQL Server em funcionamento no terminal
* [ ] Regras de saída para a porta do SQL Server em funcionamento criada no servidor
* [ ] Regras de saída para a porta do SQL Server em funcionamento criada no terminal
