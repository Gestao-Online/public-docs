<div style="text-align: justify">

### Configurando a extensão Atendare

Com a extensão instalada, agora é hora de configurá-la. Ao clicar no botão de configuração, uma nova janela será exibida com instruções passo a passo para concluir o processo.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/790c435d5b24eee7da4f78fff0e4f0db68a492ad/erp-v2/marketplace/extensions/com.atendare.gestao-online/assets/extensao_atendare_01.png?raw=true" alt="0" width="800"> 
</div>

### Token da API Atendare

Este token é único e você pode solicitar com o suporte da Atendare, abrindo um chamado diretamente com eles utilizando sua conta do Atendare e aguardar a resposta com o token para você utilizar. Exemplo de token: 19d18f5cb22f1d116f09dc8bd438fc871d513838

<a href="https://help.atendare.com/br/abrir-chamado/" target="_blank">**Abrir chamado Atendare**</a>


<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/1228d9a560b3c2c5bce97e483f62a09cf42fdfd8/erp-v2/marketplace/extensions/com.atendare.gestao-online/assets/extensao_atendare_02.png?raw=true" alt="0" width="800"> 
</div>
















### Configuração do Atendare

O primeiro campo a ser preenchido é o **ID do pipeline**, esse número vai indicar qual pipeline será vinculado para receber os dados do nosso sistema.

O segundo campo é o **ID do responsável padrão**. Dentro do Atendare, cada usuário pertence a um papel que contém diversas permissões específicas que definem os acessos de cada um. Esse número de ID será necessário para identificarmos e vincularmos com o painel que será usado.

No terceiro e quarto campos temos o **ID da Etapa de vendas não pagas** e o **ID da Etapa de vendas pagas**. Essas etapas irão separar vendas que ainda não foram pagas das que já tiveram o pagamento efetuado. Então em seu pipeline novo ou já criado, coloque os ID's de referência onde nossa extensão irá fazer o preenchimento automático.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7d9826a40d1ccf33d7df0043bb43f2fb9883e19b/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_atendare.png?raw=true" alt="0" width="800"> 
</div>

Estas informações você pode precisa solicitar diretamente com o suporte da Atendare, pois esses IDs exigem um certo nível de complexidade que eles podem repassar com mais facilidade a você.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7d9826a40d1ccf33d7df0043bb43f2fb9883e19b/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_atendare_suporte.png?raw=true" alt="0" width="800"> 
</div>

### Configuração de Venda

Para que as informações corretas sejam encaminhadas ao CRM da Atendare, você pode definir os <a href="https://docs.gestao.plus/erp-v2/funcionalidades/parametrizacoes/tipo_movimentacao" target="_blank">**Tipos de movimentação**</a> que serão permitidos. As opções que aparecerão neste campo estão cadastradas na tela **Tipo de movimentação**. Você pode digitar o nome do tipo e logo ele será buscado, e para selecionar o que deseja, você pode clicar sobre a opção de que precisa.

Observe nossa demonstração abaixo.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7d9826a40d1ccf33d7df0043bb43f2fb9883e19b/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_venda_tipo_movimentacao.gif?raw=true" alt="0" width="800"> 
</div>

O mesmo vale para a seleção dos <a href="https://docs.gestao.plus/erp-v2/funcionalidades/financeiro/tipos_negociacao" target="_blank">**Tipos de negociação**</a> permitidos, você também pode clicar no campo e logo digitar o nome do tipo de negociação que deseja permitir para o painel da Atendare.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7d9826a40d1ccf33d7df0043bb43f2fb9883e19b/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_venda_tipo_negociacao.gif?raw=true" alt="0" width="800"> 
</div>

### Configuração de periodicidade de pagamento

Na parte final, você pode configurar o tempo que o cliente demora para efetuar o pagamento da compra para ser enviado para a lista de vendas não pagas.

### Periodicidade Boleto

Você pode definir a periodicidade  em **Dias**, **Horas** ou **Minutos**, podendo escolher clicando no campo. Após definir, você agora pode preencher o campo ao lado com o número, seja em dia, hora ou minutos. Lembre-se de, quando digitar o valor em número, pressionar a tecla Enter para confirmar a opção desejada.

Observe nossa demonstração abaixo.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7d9826a40d1ccf33d7df0043bb43f2fb9883e19b/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_boleto.gif?raw=true" alt="0" width="800"> 
</div>

### Periodicidade Cartão de crédito

Você pode definir a periodicidade  em **Dias**, **Horas** ou **Minutos**, podendo escolher clicando no campo. Após definir, você agora pode preencher o campo ao lado com o número, seja em dia, hora ou minutos. Lembre-se de, quando digitar o valor em número, pressionar a tecla Enter para confirmar a opção desejada.

Observe nossa demonstração abaixo.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7d9826a40d1ccf33d7df0043bb43f2fb9883e19b/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_cartao.gif?raw=true" alt="0" width="800"> 
</div>

### Periodicidade Pix

Você pode definir a periodicidade  em **Dias**, **Horas** ou **Minutos**, podendo escolher clicando no campo. Após definir, você agora pode preencher o campo ao lado com o número, seja em dia, hora ou minutos. Lembre-se de, quando digitar o valor em número, pressionar a tecla Enter para confirmar a opção desejada.

Observe nossa demonstração abaixo.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7d9826a40d1ccf33d7df0043bb43f2fb9883e19b/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_pix.gif?raw=true" alt="0" width="800"> 
</div>

### Salvando configurações 

Após preencher todas as informações, você pode clicar no botão **Salvar configurações** e assim a extensão está devidamente configurada e funcionando, já começando a separar as vendas não pagas com a periodicidade que você configurou.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7d9826a40d1ccf33d7df0043bb43f2fb9883e19b/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_salvar.gif?raw=true" alt="0" width="800"> 
</div>

### Resultado no Atendare

Dentro do CRM da Atendare as informações serão mostradas conforme exemplo abaixo. 

Separado por número da compra, nome do produto, valor da compra, tipo de movimentação utilizada e mais abaixo o nome do cliente.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7d9826a40d1ccf33d7df0043bb43f2fb9883e19b/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_atendare_exemplo.png?raw=true" alt="0" width="600"> 
</div>

</div>