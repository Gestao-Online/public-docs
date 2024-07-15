# 🫴 Liberação de desconto

Na aba liberação de desconto você encontrará todas as solicitações de descontos para vendas, com status aguardando análise, liberado e negado. 

Estas solicitações são provenientes de vendas, pedido de venda ou compras, que ultrapassem o limite determinado de desconto no [**`perfil de desconto`**](/erp-v2/funcionalidades/usuarios_vendedores/perfil_desconto.md) de um vendedor, seja ele em valor ou percentual.

Esta aba está vinculada diretamente a aba de vendas, venda recorrente, pedido de venda, perfil de deconto (venda/compra). São muitos vínculos, mas isso faz o sistema da **Gestão Online** ser preciso nos resultados.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/comercial/aba_liberacao_desconto.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;

![](/erp-v2/assets/funcionalidades/comercial/aba_liberacao_desconto_menu.png)

<br>

{% hint style="warning" %}
**Exportar:** Caso queira mais informações sobre como utilizar o botão <img src="/erp-v2/assets/icon_exportar.png" alt="" data-size="line"> exportar movimentações [**`clique aqui`**](/erp-v2/primeiro_acesso/exportar.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

{% hint style="info" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Editando uma liberação de desconto

As liberação surgirão automaticamente nesta aba sempre que houver uma solicitação de desconto, cada uma delas tem um botão de editar e outro de excluir, em nosso exemplo, temos uma solicitação de liberação aguardando análise, vamos clicar no ícone <img src="/erp-v2/assets/funcionalidades/icon_editar_item.png" alt="" data-size="line">editar item, para acessarmos mais informações:

![](/erp-v2/assets/funcionalidades/comercial/aba_liberacao_desconto_editar.png)

<br>

Ao abrir para editar, no lado direito da tela, você pode ver um pequeno menu na cor cinza. Veja abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar rascunho;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;


![](/erp-v2/assets/funcionalidades/comercial/aba_liberacao_desconto_editar_menu.png)

<br>

Os campos já vem a maioria preenchidos com as informações da venda. Os disponíveis para alteração são o de **Status** que você define entre, negado, liberado e aguardando análise. Também o campo de **Tipo liberação de desconto**, onde você vai escolher se será desconto em valor ou porcentagem, e pos último o campo de observação para maior controle interno deixar escrito o motivo do desconto ou de não ter o desconto.

Para salvar alguma alteração nesta solicitação de liberação de desconto, é necessáio pelo menos o preenchimento do campo **Tipo liberação de desconto** que está marcado com asterisco:

![](/erp-v2/assets/funcionalidades/comercial/aba_liberacao_desconto_editar_campos.png)

### Tipo liberação de desconto

Neste campo você pode selecionar entre valor ou percentual, logo em seguida ao lado irá surgir um novo campo para você inserir o valor/percentual de desconto que realmente será aplicado aquela venda.

Importante lembrar que a opção escolhida deve estar relacionada ao perfil de desconto do vendedor. O valor pode ser maior ou menor que o solicitado, quem decide é você.

![](/erp-v2/assets/funcionalidades/comercial/aba_liberacao_desconto_editar_tipo_liberacao.png)

No exemplo acima, está sendo solicitado um desconto de R$ 60,00 na venda, e para liberar um desconto o supervisor deve possuir um **perfil de desconto** superior ou igual ao valor solicitado.

Observe abaixo o perfil de desconto (venda) deste vendedor, ele tem perfil para desconto de até R$ 50,00 no tipo valor, e no tipo percentual tem até 10% para utilizar:

![](/erp-v2/assets/funcionalidades/comercial/aba_liberacao_desconto_editar_tipo_liberacao_aba_vendedor.png)

## Salvando rascunho de uma nova venda

Após o preenchimento destas informações, você precisa alterar o campo de **status** para definir o rumo da liberação. Observe no nosso exemplo abaixo, definimos o valor e agora vamos liberar o desconto para a venda poder ser realizada. Inserimos também uma descrição para ficar registrado a situação em casos futuros de checagem:

![](/erp-v2/assets/funcionalidades/comercial/aba_liberacao_desconto_editar_tipo_liberacao_salvando.png)

Clicando no botão de salvar, uma janela de confirmação irá aparecer, e agora saindo do modo de edição, podemos ver que a liberação de desconto foi aprovada, e a venda pode seguir, ficando os registros da venda na guia **liberação**. Observe abaixo nossa demonstração:

![](/erp-v2/assets/funcionalidades/comercial/aba_liberacao_desconto_editar_tipo_liberacao_salvando.gif)

