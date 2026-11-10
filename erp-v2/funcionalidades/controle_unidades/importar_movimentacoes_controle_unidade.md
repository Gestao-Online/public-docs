# Importar movimentações para controle de unidade

Na tela de contrato de controle de unidade, você verá no menu superior o botão <img src="/erp-v2/assets/icon_importar.png" alt="" data-size="line"> de processar movimentações.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_btn_importar.png)

Clicando nele uma nova janela será mostrada solicitando que envie um arquivo do tipo planilha para que possa processar as informações na plataforma.

{% hint style="warning" %}
**Atenção:** Os formatos de planilha aceitos no sistema são `.csv`, .`xls`, `xlsx` e `.ods`.
{% endhint %}

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_btn_importar_janela.png)

A estrutura de informações da planilha não é complexa, sendo somente cinco colunas e algumas informações como **ID contrato** e **ID unidade** sendo necessárias como identificador para o tipo de lançamento receita ou despesa. Muita atenção para os valores, não é necessário a utilização do cifrão, o sistema fará a conversão automaticamente, quando ler a planilha enviada.

{% hint style="info" %}
É possível baixar o modelo desta planilha. [**`PLANILHA MODELO CONTRATO.xlsx`**](https://github.com/Gestao-Online/public-docs/raw/master/erp-v2/assets/PLANILHA%20MODELO%20CONTRATO.xlsx)
{% endhint %}

Observe abaixo o exemplo de planilha que utilizaremos.

![Modelo de planilha com preenchimento de exemplo](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_modelo_planilha.png)

Para nosso exemplo, temos duas unidades com contrato cadastradas, UNIDADE A e UNIDADE B. Iremos usar a planilha para processar algumas movimentações para estas unidades.

{% hint style="warning" %}
**Atenção:** É comum aparecer alguma mensagem de erro em caso de uso do software Microsoft Excel, por isso sempre verifique se existe alguma célula preenchida ou com alguma formatação antes de fazer o envio. 😁
{% endhint %}

Observe o procedimento passo a passo.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_btn_importar_janela_importando.gif)

Pronto, com a planilha carregada, agora é possível conferir se as movimentações foram carregadas corretamente.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_btn_importar_janela_olhando_importacoes.gif)