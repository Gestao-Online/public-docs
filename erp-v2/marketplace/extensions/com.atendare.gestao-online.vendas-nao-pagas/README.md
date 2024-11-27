# 📦 App Atendare - Vendas não pagas

Com a extensão da Atendare para vendas não pagas, você terá um envio de leads e atualizações de vendas não pagas para melhor controle das vendas que não se concretizaram em seu site de vendas.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_inicio.png)

Com a extensão instalada, você precisa configurá-la clicando no botão de configuração que é exibido a partir do momento que você instala a extensão no sistema.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_btn_config.png)

## Configurando API Atendare

No primeiro momento, você precisa configurar a ligação com a API da Atendare, são três campos para preenchimento.

### Token da API Atendare

Na sequência, você precisa preencher o token da API, este token é único e você pode solicitar com o suporte da Atendare, conforme eles explicam no site de ajuda. 

Exemplo: 19d18f5cb22f1d116f09dc8bd438fc871d513838

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_token_api.png)

### Configuração do Atendare

O primeiro campo a ser preenchido é o **ID do pipeline**, esse número vai indicar qual pipeline será vinculado para receber os dados do nosso sistema.

O segundo campo é o **ID do responsável padrão**. Dentro do Atendare, cada usuário pertence a um papel que contém diversas permissões específicas que definem os acessos de cada um. Esse número de ID será necessário para identificarmos e vincularmos com o painel que será usado.

No terceiro e quarto campos temos o **ID da Etapa de vendas não pagas** e o **ID da Etapa de vendas pagas**. Essas etapas irão separar vendas que ainda não foram pagas das que já tiveram o pagamento efetuado. Então em seu pipeline novo ou já criado, coloque os ID's de referência onde nossa extensão irá fazer o preenchimento automático.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_atendare.png)

Estas informações você pode precisa solicitar diretamente com o suporte da Atendare, pois esses IDs exigem um certo nível de complexidade que eles podem repassar com mais facilidade a você.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_atendare_suporte.png)

### Configuração de Venda

Para que as informações corretas sejam encaminhadas ao CRM da Atendare, você pode definir os [**`Tipos de movimentação`**](https://docs.gestao.plus/erp-v2/funcionalidades/parametrizacoes/tipo_movimentacao) que serão permitidos. As opções que aparecerão neste campo estão cadastradas na tela **Tipo de movimentação**. Você pode digitar o nome do tipo e logo ele será buscado, e para selecionar o que deseja, você pode clicar sobre a opção de que precisa.

Observe nossa demonstração abaixo.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_venda_tipo_movimentacao.gif)

O mesmo vale para a seleção dos [**`Tipos de negociação`**](https://docs.gestao.plus/erp-v2/funcionalidades/financeiro/tipos_negociacao) permitidos, você também pode clicar no campo e logo digitar o nome do tipo de negociação que deseja permitir para o painel da Atendare.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_venda_tipo_negociacao.gif)

## Configuração de periodicidade de pagamento

Na parte final, você pode configurar o tempo que o cliente demora para efetuar o pagamento da compra para ser enviado para a lista de vendas não pagas.

### Periodicidade Boleto

Você pode definir a periodicidade  em **`Dias`**, **`Horas`** ou **`Minutos`**, podendo escolher clicando no campo. Após definir, você agora pode preencher o campo ao lado com o número, seja em dia, hora ou minutos. Lembre-se de, quando digitar o valor em número, pressionar a tecla Enter para confirmar a opção desejada.

Observe nossa demonstração abaixo.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_boleto.gif)

### Periodicidade Cartão de crédito

Você pode definir a periodicidade  em **`Dias`**, **`Horas`** ou **`Minutos`**, podendo escolher clicando no campo. Após definir, você agora pode preencher o campo ao lado com o número, seja em dia, hora ou minutos. Lembre-se de, quando digitar o valor em número, pressionar a tecla Enter para confirmar a opção desejada.

Observe nossa demonstração abaixo.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_cartao.gif)

### Periodicidade Pix

Você pode definir a periodicidade  em **`Dias`**, **`Horas`** ou **`Minutos`**, podendo escolher clicando no campo. Após definir, você agora pode preencher o campo ao lado com o número, seja em dia, hora ou minutos. Lembre-se de, quando digitar o valor em número, pressionar a tecla Enter para confirmar a opção desejada.

Observe nossa demonstração abaixo.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_config_pix.gif)

## Salvando configurações 

Após preencher todas as informações, você pode clicar no botão **`Salvar configurações`** e assim a extensão está devidamente configurada e funcionando, já começando a separar as vendas não pagas com a periodicidade que você configurou.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_salvar.gif)

## Resultado no Atendare

Dentro do CRM da Atendare as informações serão mostradas conforme exemplo abaixo. 

Separado por número da compra, nome do produto, valor da compra, tipo de movimentação utilizada e mais abaixo o nome do cliente.

![](/erp-v2/assets/marketplace/go_atendare_vendas_nao_pagas/tela_marketplace_go_atendare_vendas_nao_pagas_atendare_exemplo.png)