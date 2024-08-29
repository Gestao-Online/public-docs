# GO Digisac

Otimize o atendimento aos clientes com um sistema digital de mensageria para a sua empresa. Ao configurar o GO Digisac Robo Vendas, você poderá acompanhar através de um dashboard personalizado todos os atendimentos que estão sendo realizados em tempo real.

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_inicio.png)

Com a extensão instalada, você precisa configurá-la clicando no botão de configuração que é exibido a partir do momento que você instala a extensão no sistema.

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_btn_config.png)

## Configurando API

No primeiro momento você precisa configurar a ligação com a API, são três campos para preenchimento.

### URL base da API

A URL da API pode ser obtida no painel da **Digisac**, assim que conseguir ela, coloque neste campo conforme mostrado.

Exemplo: https://nomedasuaempresa.digisac.me/api/v1

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_url_api.png)

### Token da API

Na sequência, você precisa preencher o token da API, este token é único e você pode encontrar ele também no painel de acesso da Digisac. 

Exemplo: 19d18f5cb22f1d116f09dc8bd438fc871d513838

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_token_api.png)

### Token da API Gestão Online

Agora é preciso obter o token da API da Gestão Online, esse token você só irá conseguir entrando em contato com o nosso suporte. Pois esse código é exclusivo e não compartilhável por motivo de segurança no uso do sistema.

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_token_api_gestao_online.png)

## Configuração de venda

### Undiade de venda

Agora partindo para a configuração da venda que o robô irá fazer, primeiramente precisamos configurar a **Unidade de venda**, por que essa unidade será a que o robo irá utilizar para fazer o lançamento das vendas.

{% hint style="info" %}
**Unidade de venda:** Para maiores informações sobre como utilizar ou configurar uma unidade de venda, [**`Clique aqui`**](/erp-v2/funcionalidades/agendamentos_atividades/tipo_agendamentos.md).
{% endhint %}

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_token_unidade_venda.png)

### Produto para venda

Definido a unidade, você agora precisa escolher qual produto ou produtos seu robô irá comercializar, observe em nossa demonstração que você pode definir mais de um item ao mesmo tempo.

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_token_produto.gif)

### Forma de pagamento

A escolha das formas de pagamento disponíveis seguem a mesma regra de escolha do produto, ao clicar no campo de preenchimento você pode digitar as formas de pagamento que deseja utilizar. Pode adicionar o pix, cartão de crédito em 1x, 2x ou até 12x. Veja abaixo nosso exemplo.

{% hint style="warning" %}
**Atenção:** Fique atento para definir somente formas de pagamento digitais, pois qualquer outro meio não será possivel a finalização da venda.
{% endhint %}

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_forma_pagamento.gif)

### Desconto ou Acréscimo para cliente novo ou antigo

Na conquista por cliente um atrativo é sempre interessante, por isso colocamos a opção de você adicionar desconto em dinheiro ou porcentagem para esse cliente novo que nunca fez uma compra ainda, e para clientes antigos pode colocar um valor de acréscimo. Mas você também pode fazer o contrário, e colocar valores maiores para clientes novos e valores menores para clientes antigos.

Essa estratégia vai ficar a seu critério, pois estes campos não são de preenchimento obrigatório. 😉

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_go_digisac_desconto_acrescimo.gif)

## Configuração do robô

Agora os próximos passos você terá vários campos para preencher, cada um fará com que o seu robô funcione perfeitamente e evite erros no momento em que o cliente for efetuar uma compra.

### Criar menu inicial

Ativando a opção **Criar menu inicial** você precisará criar os departamentos que serão mostrados para o cliente, no caso o campo **Opções de menu**, neste campo os nomes dos departamentos precisam ser separados por vírgula. 

Criamos algumas opções, e a última opção vamos chamar de *Comprar pelo Whatsapp*, pois usaremos ela mais abaixo.

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu.png)

Agora você precisa degitar o **Nome na opção de compra do menu**. Esta opção é que será para o cliente efetuar a compra, no exemplo anterior nós criamos uma opção no menu com o nome *Comprar pelo Whatsapp*, então neste campo iremos repetir esse nome, porque assim faremos esse vínculo com a opção.

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_compra.png)

Logo ao lado, temos o campo **Departamento (Contigência)**, aqui você vai inserir o nome do departamento no Digisac que o Robô irá transferir o cliente no caso de qualquer imprevisto no fluxo de venda do robô.

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_contigencia.png)

### Configurando textos

Continuando com a configuração, agora temos o campo de texto exibido acima do menu de opções. Esse será o texto que o robô irá enviar junto com menu inicial.

Você pode colocar por exemplo a seguinte mensagem: **"Olá, seja bem-vindo, escolha uma das opções a seguir:"**.

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_menu.png)

Ao lado, temos o campo **Texto de listagem Produtos (pré)**, aqui você pode colocar o texto que o robô irá enviar antes da listagem de produtos.

Para preencher este campo você pode usar por exemplo: **"Nós temos uma gama de produtos, qual melhor te atenderia?"**. E m seguida os produtos são listados para o cliente selecionar.

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_produtos.png)

Descendo um pouco mais, temos o campo **Texto desconto/acrescimo cliente antigo (pré)** que o robô irá enviar antes da listagem de produtos, mas isso, caso seja um cliente antigo e você tenha configurado um desconto ou acréscimo no campo [**Desconto/Acrescimo(Cliente antigo)**](/erp-v2/marketplace/go-digisac###_desconto_ou_acrescimo_para_cliente_novo_ou_antigo), que foi explicado em configuração de venda.

Um exemplo de texto que você pode preencher este campo: **"Vi aqui no nosso sistema que você é um cliente antigo, temos um descontão exclusivo para você!"**

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_desconto_antigo.png)

No mesmo seguimento, ao lado, temos a configuração da mensagem do campo **Texto desconto/acrescimo cliente novo (pré)**, este será o texto que o robô vai enviar antes da listagem de produtos mas somente caso o cliente seja novo e você tenha configurado um desconto ou acréscimo no campo, [**Desconto/Acrescimo(Cliente antigo)**](/erp-v2/marketplace/go-digisac###_desconto_ou_acrescimo_para_cliente_novo_ou_antigo), que foi explicado em configuração de venda.

Você pode utilizar um texto de exemplo: **"Vi aqui no nosso sistema que é a sua primeira compra conosco, temos um descontão exclusivo para você!"**

![](/erp-v2/assets/marketplace/go-digisac/tela_marketplace_config_robo_criar_menu_opc_texto_desconto_novo.png)

