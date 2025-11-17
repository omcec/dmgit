# Glossário

**Servidor:** computador onde é armazenado o banco de dados, com todas as informações do sistema. Este, deve ser o **primeiro computador a ser ligado** no estabelecimento no dia.

**Terminal comum:** computador de balcão, utilizado apenas para consulta de preços e/ou realização de pré-vendas. As informações do sistema são puxados do banco de dados que está no Servidor.

**Terminal de backup:** computador onde será realizada a cópia do backup do sistema. Este, deve estar ligado o tempo todo que o estabelecimento estiver com o sistema funcionando, para que o backup seja copiado para ele. Priorizamos o caixa como terminal administrador, porque na teoria, ele ficará ligado o tempo todo. No terminal de backup deve conter a pasta MCBkp, que é onde o backup será salvo. Esta pasta deve estar compartilhada na rede.

**Terminal administrador:** computador que administra o sistema, ou seja, algumas funções específicas devem ser realizadas nele, obrigatoriamente. Este, deve ser o **primeiro computador a abrir o sistema** no dia. Na maioria das vezes, o Servidor é também o terminal administrador, mas não é obrigatório, o terminal administrador pode ser qualquer computador do estabelecimento.

**Terminal caixa:** computador onde possui o sistema de frente de caixa. Este, é responsável por realizar a impressão das vendas realizadas pelo estabelecimento.

{% hint style="warning" %}
Todos os terminais da loja precisam se comunicar com o Servidor na rede para que os sistemas funcionem corretamente neles.
{% endhint %}

**Backup:** cópia de segurança dos dados do sistema. O backup é realizado de hora em hora, salvando um arquivo no próprio Servidor e outro no terminal de backup, se o estabelecimento possuir mais de um computador na loja, caso contrário, o backup é salvo apenas no Servidor e nesse caso, o cliente deve salvar o backup em uma mídia externa para se resguardar de uma possível perda de todos os dados caso o computador apresente algum problema.

**Config.ini:** arquivo de configuração inicial dos sistemas DMASTER FARMA e DMASTER SHOP.

**SQL Server:** Sistema Gerenciador de Banco de Dados, onde é armazenado o banco de dados do sistema. Este, é instalado apenas no Servidor.

**Banco de dados:** é o agrupamento de dados que precisam ser armazenados para segurança ou conferência futura. Onde são armazenados todos os dados do sistema a cada alteração realizada.

**Net framework:** é uma plataforma de desenvolvimento e execução de sistemas e aplicações.

**Firewall:** é uma barreira que o computador possui para que não seja infectado por vírus através da internet.

**Rede:** quando vários dispositivos são interligados por meio de um equipamento de internet. Estes, podem acessar pastas compartilhadas uns dos outros.

**IP (Internet Protocol):** número identificador do computador na rede, este número é único e cada computador possui o seu.

{% hint style="info" %}
**Exemplo de IP:** 192.168.5.120
{% endhint %}

**ABCFARMA (Associação Brasileira do comércio Farmacêutico):** órgão responsável por gerenciar e disponibilizar a lista de medicamentos com seus devidos preços de custo e venda que serão praticados pelas Drogarias. Quando há aumentos nos preços dos medicamentos definido pelo Governo, a ABCFarma é responsável por disponibilizar a lista com as devidas alterações. A atualização de preços, deve ser realizada também no sistema DMASTER FARMA, para que o estabelecimento realize vendas com os novos preços. A atualização, nem sempre é apenas dos preços, pode ocorrer também alteração de fabricante dos medicamentos e remoção de medicamentos da lista da ABCFarma.

**PMC (Preço Máximo ao Consumidor):** é o preço máximo permitido para venda ao consumidor final e inclui os impostos incidentes.

**Farmácia Popular:** programa do Governo que oferece medicamentos para determinadas doenças com preços baixos ou até de graça para a população. Pertencem ao programa medicamentos para hipertensão, diabetes, asma, colesterol, rinite, Parkinson, osteoporose e glaucoma. Além disso, anticoncepcionais e fraldas geriátricas também fazem parte da Farmácia Popular.

**Fluxo de caixa/DRE:** fluxo do dinheiro no caixa do estabelecimento, ou seja, todo valor que foi recebido (receitas) diminuído dos gastos (despesas).

**Sintegra:** arquivo gerado para informar os registros de entrada e saída da empresa.

**SPED (Sistema Público de Escrituração Digital):** é a digitalização de todas as informações de interesse do fisco com seus contribuintes.

**NFCe (Nota Fiscal do Consumidor Eletrônica):** documento fiscal eletrônico emitido para o consumidor final.

**SEFAZ (Secretaria de Estado de Fazenda):** órgão utilizado nos sistemas Dmaster NFe e Dmaster NFCe. Ao utilizar os dois sistemas, é realizada comunicação como SEFAZ para que as notas sejam geradas corretamente.

**PBMs (Programa de Benefício em Medicamentos)**: programa de descontos utilizado pelas Drogarias para oferecer preços melhores para seus clientes.

**Certificado Digital:** identidade eletrônica de uma pessoa ou empresa. É a identificação virtual que permite assinar documentos a distancia. É utilizado para os sistemas Dmaster NFe e Dmaster NFCe.

**ANVISA (Agência Nacional de Vigilância Sanitária):** órgão responsável por receber informações de movimentação de medicamentos controlados enviadas do SNGPC.

**Senha do dia:** senha utilizada para realizar alguns processos. É alterada diariamente de acordo com a data e é encontrada no rodapé do Controle interno Dmaster com o nome Senha de hoje. A senha do dia possui 6 dígitos, mas os dígitos importantes são apenas os 3 últimos, ou seja, se for preciso utilizar a senha do dia para algum processo, é possível digitar números aleatórios no início, mas o final precisa ser os números finais da senha do dia.

{% hint style="info" %}
**Exemplo: Senha do dia: 125123**&#x20;

**Pode ser digitada da seguinte forma: 000123 - 123123**
{% endhint %}

**Senha token:** senha utilizada para o usuário Admin dos sistemas Dmaster e encontrada no rodapé do controle interno Dmaster, como o nome Senha Token. Esta senha é alterada constantemente durante o dia. Para utilizá-la é necessário acessar o controle interno Dmaster e utilizar a tecla F2, assim ela será alterada para 6 dígitos, que deverão ser utilizados no processo desejado.

**ID do cliente e Chave:** informações que identificam o cliente e o terminal administrador da loja. É responsável também por verificar a situação financeira do cliente com a Dmaster. Essas informações são encontradas no cadastro do cliente no controle interno Dmaster.
