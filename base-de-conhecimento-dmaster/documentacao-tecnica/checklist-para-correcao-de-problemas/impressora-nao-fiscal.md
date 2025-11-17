# Impressora não fiscal

A não impressão dos cupons, pode acontecer por vários motivos. Com isso, serão citados abaixo alguns pontos a serem verificados para que o problema seja solucionado. **Caso não seja possível resolver o erro após realizar todos os passos, uma solicitação de ajuda deve ser aberta para o responsável.**

{% hint style="info" %}
No final do documento estão descritas algumas soluções que já foram mapeadas pela equipe e documentadas no servidor arquivos DMASTER. Caso o erro seja constatado, consulte na seção abaixo se existe alguma solução já mapeada.

[Algumas soluções já mapeadas pela equipe](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/checklist-para-correcao-de-problemas/impressora-nao-fiscal#algumas-solucoes-ja-mapeadas-pela-equipe)
{% endhint %}



{% hint style="danger" %}
**Conceitos importantes**

Para realizar a impressão de documentos no sistema DMASTER nós possuímos dois sistemas responsáveis por tal funcionalidade.

O sistema de NFCE é responsável pela impressão do CUPOM FISCAL DE NFCE.

O sistema de frente de caixa (ECF) é responsável pela impressão de todas as outras impressões de cupom vinculado, fechamento de caixa e etc.
{% endhint %}

#### Siga os passos abaixo em ordem a fim de encontrar onde esteja o erro de comunicação <a href="#siga-os-passos-abaixo-em-ordem-a-fim-de-encontrar-onde-esteja-o-erro-de-comunicacao" id="siga-os-passos-abaixo-em-ordem-a-fim-de-encontrar-onde-esteja-o-erro-de-comunicacao"></a>

**Estado do equipamento**

* [ ] Impressora ligada
* [ ] Impressora conectada ao computador
* [ ] Impressora com papel
* [ ] Impressora sem luz de erro
* [ ] Computador ligado

**Estado do sistema**

* [ ] Aplicativo do NFCE em execução no caixa onde não está havendo a impressão.

**Configurações do sistema**

* [ ] Nome da impressora no painel de controle. (NFCEPRINTER)
* [ ] Modelo da impressora correto no ConfigECF
* [ ] Caminho da impressora correto no ConfigECF

**Reinicio dos equipamentos e sistemas**

* [ ] Reiniciar impressora
* [ ] Reiniciar aplicativo NFCE no caixa onde não está havendo a impressão.
* [ ] Reiniciar computador

**Compartilhamento da impressora e comunicação**

* [ ] Impressora comunicando com o computador
* [ ] Impressão de teste via Windows. (Pagina de teste)
* [ ] Impressão de teste direto na porta. \
  **Comando:** "dir > \\\NomeDoComputador\NomeDoCompartilhamentoDaImpressora" no Prompt de comando.
* [ ] Configuração da porta da impressora no painel de controle
* [ ] Configuração de descoberta de rede habilitada
* [ ] Configuração de compartilhamento de arquivo e impressora habilitada
* [ ] Configuração de compartilhamento por senha desabilitada
* [ ] Compartilhamento da impressora
* [ ] Permissão da pasta Printers do Windows
* [ ] Refazer o compartilhamento da impressora.

**Outros**

* [ ] Reinstalação da impressora
* [ ] Atualização do Windows
* [ ] Trocar o cabo da porta USB/Serial do computador
* [ ] Troca de cabo de comunicação com a impressora
