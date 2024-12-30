<div style="text-align: justify">

## GO Digisac

Otimize o atendimento aos clientes com um sistema digital de mensagens para a sua empresa. Ao configurar o GO Digisac Robô Vendas, você poderá acompanhar por meio de um dashboard personalizado todos os atendimentos que estão sendo realizados em tempo real.

Com a extensão instalada, você precisa configurá-la clicando no botão de configuração que é exibido a partir do momento que você instala a extensão no sistema.

## Configurando API

No primeiro momento você precisa configurar a ligação com a API, são três campos para preenchimento.

### URL base da API

A URL da API pode ser obtida no painel da **Digisac**, assim que conseguir ela, coloque neste campo conforme mostrado.

Exemplo: https://nomedasuaempresa.digisac.me/api/v1

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_url_api.png?raw=true)

### Token da API

Na sequência, você precisa preencher o token da API, este token é único e você pode encontrar ele também no painel de acesso da Digisac. 

Exemplo: 19d18f5cb22f1d116f09dc8bd438fc871d513838

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_token_api.png?raw=true)

### Token da API Gestão Online

Agora é preciso obter o token da API da Gestão Online, esse token você só irá conseguir entrando em contato com o nosso suporte. Pois esse código é exclusivo e não compartilhável por motivo de segurança no uso do sistema.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_token_api_gestao_online.png?raw=true)

## Configuração de venda

### Unidade de venda

Agora, partindo para a configuração da venda que o robô irá fazer, primeiramente precisamos configurar a **Unidade de Venda**, porque essa unidade será a que o robô irá utilizar para fazer o lançamento das vendas.

<div style="background-color:rgb(210, 233, 255); border-left: 6px solid rgb(142, 181, 255); padding: 15px; margin: 20px 0; border-radius: 5px; font-family: Arial, sans-serif; color: #333; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);">
    <h4 style="margin: 0 0 10px; font-size: 1.2em; color: #555;">ℹ️ INFO</h4>
    <p style="margin: 0; line-height: 1.5;"><strong>Unidade de venda:</strong> Para mais informações sobre como utilizar ou configurar uma unidade de venda, <a href="https://docs.gestao.plus/erp-v2/funcionalidades/agendamentos_atividades/tipo_agendamentos" target="_blank">clique aqui</a>.</p>
</div>

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_token_unidade_venda.png?raw=true)

### Produto para venda

Definido a unidade, você agora precisa escolher qual produto ou produtos seu robô irá comercializar, observe em nossa demonstração que você pode definir mais de um item ao mesmo tempo.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_token_produto.gif?raw=true)

### Forma de pagamento

A escolha das formas de pagamento disponíveis seguem a mesma regra de escolha do produto, ao clicar no campo de preenchimento você pode digitar as formas de pagamento que deseja utilizar. Pode adicionar o pix, cartão de crédito em 1x, 2x ou até 12x. Veja abaixo nosso exemplo.

<div style="background-color:rgb(210, 233, 255); border-left: 6px solid rgb(142, 181, 255); padding: 15px; margin: 20px 0; border-radius: 5px; font-family: Arial, sans-serif; color: #333; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);">
    <h4 style="margin: 0 0 10px; font-size: 1.2em; color: #555;">ℹ️ INFO</h4>
    <p style="margin: 0; line-height: 1.5;"><strong>Atenção:</strong> Fique atento para definir somente formas de pagamento digitais, pois qualquer outro meio não será possível a finalização da venda.</p>
</div>

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_forma_pagamento.gif?raw=true)

### Desconto ou Acréscimo para cliente novo, ou antigo

Na conquista por cliente um atrativo é sempre interessante, por isso colocamos a opção de você adicionar desconto em dinheiro ou porcentagem para esse cliente novo que nunca fez uma compra ainda, e para clientes antigos pode colocar um valor de acréscimo. Mas você também pode fazer o contrário, e colocar valores maiores para clientes novos e valores menores para clientes antigos.

Essa estratégia vai ficar a seu critério, pois estes campos não são de preenchimento obrigatório. 😉

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_desconto_acrescimo.gif?raw=true)

## Configuração do robô

Agora os próximos passos você terá vários campos para preencher, cada um fará com que o seu robô funcione perfeitamente e evite erros no momento em que o cliente for efetuar uma compra.

### Criar menu inicial

Ativando a opção **Criar menu inicial** você precisará criar os departamentos que serão mostrados para o cliente, no caso o campo **Opções de menu**, neste campo os nomes dos departamentos precisam ser separados por vírgula. 

Criamos algumas opções, e a última opção vamos chamar de *Comprar pelo WhatsApp*, pois usaremos ela mais abaixo.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu.png?raw=true)

Você pode ativar o **aviso de horário de atendimento** para os departamentos que cadastrar no campo anterior, ao ativar esta opção, preencha o campo ao lado com a mensagem personalizada do horário de atendimento.

Essa mensagem será mostrada ao cliente caso esteja fora do horário de atendimento configurado no painel do Digisac.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_aviso_horario.png?raw=true)

O mesmo vale para o campo de **aviso de feriado**, com os feriados já previamente cadastrados no painel do Digisac, você pode ativar essa função e configurar uma mensagem de aviso padrão para ser exibida aos clientes no ato da compra.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_aviso_feriado.png?raw=true)

Agora você precisa digitar o **Nome na opção de compra do menu**. Esta opção é que será para o cliente efetuar a compra. No exemplo anterior, nós criamos uma opção no menu com o nome *Comprar pelo WhatsApp*, então neste campo iremos repetir esse nome, porque assim faremos esse vínculo com a opção.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_compra.png?raw=true)

Logo ao lado, temos o campo **Departamento (Contingência)**, aqui você vai inserir o nome do departamento no Digisac que o Robô irá transferir o cliente no caso de qualquer imprevisto no fluxo de venda do robô.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_contigencia.png?raw=true)

### Configurando textos iniciais

Continuando com a configuração, agora temos o campo de texto exibido acima do menu de opções. Esse será o texto que o robô irá enviar com o menu inicial.

Você pode colocar por exemplo a seguinte mensagem: **"Olá, seja bem-vindo, escolha uma das opções a seguir:"**.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_menu.png?raw=true)

Ao lado, temos o campo **Texto de listagem Produtos (pré)**, aqui você pode colocar o texto que o robô irá enviar antes da listagem de produtos.

Para preencher este campo, você pode usar, por exemplo: **"Nós temos uma gama de produtos, qual melhor te atenderia?"**.

Em seguida, os produtos são listados para o cliente selecionar.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_produtos.png?raw=true)

Descendo um pouco mais, temos o campo **Texto desconto/acréscimo cliente antigo (pré)** que o robô irá enviar antes da listagem de produtos, mas isso, caso seja um cliente antigo e você tenha configurado um desconto ou acréscimo no campo <a href="https://docs.gestao.plus/inicio/go-digisac#desconto-ou-acrescimo-para-cliente-novo-ou-antigo" target="_blank">**Desconto/Acréscimo(Cliente antigo)**</a>, que foi explicado em configuração de venda.

Um exemplo de texto que você pode preencher este campo: **"Vi aqui no nosso sistema que você é um cliente antigo, temos um descontão exclusivo para você!"**

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_desconto_antigo.png?raw=true)

No mesmo seguimento, ao lado, temos a configuração da mensagem do campo **Texto desconto/acréscimo cliente novo (pré)**, este será o texto que o robô vai enviar antes da listagem de produtos, mas somente caso o cliente seja novo e você tenha configurado um desconto ou acréscimo no campo, [**Desconto/Acréscimo(Cliente antigo)**](https://docs.gestao.plus/inicio/go-digisac#desconto-ou-acrescimo-para-cliente-novo-ou-antigo), que foi explicado em configuração de venda.

Você pode utilizar um texto de exemplo: **"Vi aqui no nosso sistema que é a sua primeira compra conosco, temos um descontão exclusivo para você!"**

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_desconto_novo.png?raw=true)

### Configuração de textos para dados dos clientes

Aqui fica o campo **Texto preenchimento CPF/CNPJ (pré)**, esse será o texto que o robô irá enviar ao cliente perguntando seu CPF ou CNPJ. Pois, dependendo da resposta, uma nova mensagem será mostrada ao cliente.

Das possíveis mensagens de exemplo que você pode utilizar: **"Para prosseguir, digite o CPF ou o CNPJ:"**

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_cpf_cnpj.png?raw=true)

Para o caso de preenchimento do campo anterior mostrado ao cliente ser um CPF, você precisa configurar o campo **Texto preenchimento nome PF (pré)**, esse será o texto que o robô vai enviar perguntando o nome do cliente quando for pessoa física.

A mensagem deste campo pode ser, por exemplo: **"Para prosseguir, insira o seu nome:"**

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_caso_cpf.png?raw=true)

No caso de preenchimento do campo anterior mostrado ao cliente ser um CNPJ, você precisa configurar o campo **Texto preenchimento Nome/Razão social PJ (pré)**, esse será o texto que o robô vai enviar perguntando o nome do cliente quando for pessoa jurídica.

Pode ser esta mensagem, por exemplo: **"Para prosseguir, insira a razão social da sua empresa:"**

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_caso_cnpj.png?raw=true)

Agora com o CPF/CNPJ, nome da pessoa/empresa preenchidos, o próximo passo é solicitar o e-mail do cliente. Configurando o campo **Texto preenchimento E-mail (pré)**, fará com que o robô envie o texto perguntando o e-mail ao cliente. Você pode colocar um texto de exemplo assim: **"Agora, nos informe um e-mail válido:"**

<div style="background-color:rgb(210, 233, 255); border-left: 6px solid rgb(142, 181, 255); padding: 15px; margin: 20px 0; border-radius: 5px; font-family: Arial, sans-serif; color: #333; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);">
    <h4 style="margin: 0 0 10px; font-size: 1.2em; color: #555;">ℹ️ INFO</h4>
    <p style="margin: 0; line-height: 1.5;"><strong>Informativo:</strong> O painel do Digisac fará a conferência do e-mail do cliente para, caso ele digite algo fora do padrão, solicitar que ele digite o e-mail novamente.</p>
</div>

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_email.png?raw=true)

Continuando, o próximo passo é o campo **Texto preenchimento CEP (pré)** para que o robô identifique e busque os dados do endereço de forma mais rápida. 

Essa é uma das últimas mensagens, pode ser, por exemplo: **"Para finalizar, nos informe o CEP:"**

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_cep.png?raw=true)

### Configurando texto para pagamento

Feito isso, agora você tem o campo de **Texto escolhe Forma de pagamento (pré)**, neste campo você definirá o texto que o robô irá enviar perguntando qual a forma de pagamento. Lembrando que as opções que aparecem para o cliente são configuradas na parte de [**configuração de venda**](https://docs.gestao.plus/inicio/go-digisac#forma-de-pagamento), mostrada mais ao início do nosso manual.

Um exemplo de mensagem que você pode utilizar: **"Para finalizar, escolha a forma de pagamento:"**

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_pgto.png?raw=true)

Agora, com a forma de pagamento escolhida e o cliente realizando o pagamento, você vai configurar a mensagem do campo **Texto resumo pedido (pré)**, para que o robô envie uma mensagem informando sobre a geração do pedido.

Exemplo de mensagem que pode ser utilizada: **"Aguarde um momento enquanto estamos processando o seu pedido."**

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_resumo_pedido.png?raw=true)

Finalizada a compra, você pode configurar a mensagem e o agradecimento para que o robô envie agradecendo sobre a compra realizada. Pode ser, por exemplo, a seguinte mensagem: **"Obrigado pela compra! Se ficar com alguma dúvida sobre o pagamento, é só me chamar aqui."**

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_resumo_pedido_realizado.png?raw=true)

Agora você precisa somente clicar no botão **`Salvar`** para que seu robô comece a funcionar.

**E assim chegamos ao fim da configuração do seu robô de vendas! Viu só, foram somente alguns poucos passos!** 😅

<br>

## Acompanhando as vendas do robô

Montamos em nossa plataforma um dashboard para que você acompanhe todas as vendas que estão acontecendo em tempo real.

Para acessar essa tela, você precisa utilizar a barra de pesquisa e procurar pelo nome **Dash - Robô de vendas**. Veja abaixo nossa demonstração.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_tela_dash_robo.gif?raw=true)

Nesta tela, você terá o relatório das vendas, com número do pedido, situação do pagamento, produtos, etc.

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_tela_dash_robo_campos.png?raw=true)

Além de você ver todos os dados das vendas, você pode clicar sobre uma venda e uma janela será aberta para você mostrando a movimentação desta venda.

<div style="background-color:rgb(210, 233, 255); border-left: 6px solid rgb(142, 181, 255); padding: 15px; margin: 20px 0; border-radius: 5px; font-family: Arial, sans-serif; color: #333; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);">
    <h4 style="margin: 0 0 10px; font-size: 1.2em; color: #555;">ℹ️ INFO</h4>
    <p style="margin: 0; line-height: 1.5;"><strong>Tela de vendas:</strong> Caso queira mais informações sobre como configurar uma venda, <a href="https://docs.gestao.plus/erp-v2/funcionalidades/comercial/vendas" target="_blank">clique aqui</a>.</p>
</div>

![](https://github.com/Gestao-Online/public-docs/blob/5c72fb708c9a01ff49633b315c7bb70d996ac10e/erp-v2/assets/marketplace/go-digisac/tela_marketplace_tela_dash_robo_campos_janela_movimentacao.gif?raw=true)

</div>