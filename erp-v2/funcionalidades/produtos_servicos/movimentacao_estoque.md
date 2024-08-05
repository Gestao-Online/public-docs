# 📤 Movimentação de estoque

Aqui você tem a visão das movimentações do estoque de produtos na plataforma. Esta tela funciona como um "extrato" ou "histórico" de toda movimentação (entrada e saída) de produtos em cada respectivo local de estoque.

É possível fazer e acompanhar lançamentos do tipo:

    - Transferência
    - Venda
    - Compra
    - Devolução
    - Ajuste

O lançamento de "ajuste", por exemplo, pode ser utilizado para fazer ajustes na quantidade disponível em um local de estoque de um produto, de forma manual no sistema (para um estoque inicial ou ajuste de estoque após um inventário, por exemplo).

Já o lançamento de "transferência" pode ser utilizado para transferir determinada quantidade de produtos que está disponível em um local de estoque para outro. (Assim o sistema faz automaticamente a saída de um local de estoque e a entrada no outro).

Os lançamentos do tipo "Venda", "Compra" e "Devolução" normalmente são lançados de forma automática, integrada à camada de pedidos/vendas/compras. Então, por exemplo: de acordo com as regras estabelecidas no [**`Tipo de movimentação`**](/erp-v2/funcionalidades/parametrizacoes/tipo_movimentacao.md), uma venda pode dar saída no estoque (do tipo Venda) quando o vendedor "confirmar a venda" ou quando o "pagamento estiver liquidado".

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque.gif)

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar movimentação no estoque.

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_menu.png)

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Adicionar nova movimentação de estoque

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo produto ao estoque, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/estoque_produto/aba_estoque_add.png)

Ao clicar neste botão, você será direcionado para esta página, para criar uma movimentação de estoque:

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_add_inicio.png)

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_add_menu.png)

Olhando para a criação de movimentação, quando você for criar uma nova movimentação de estoque, é necessário preencher todos os campos marcados com o asterisco vermelho:

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_itens.png)

## Campo Tipo

O primeiro campo é de escolha de **Tipo**, ele possui cinco opções, a primeira é de *Transferência*. Quando selecionamos esta opção, novos campos ficam disponíveis para preenchermos, pois iremos definir um local de saída e destino para o nosso produto de exemplo.

Os dois campos ao lado são de **Data lançamento** (Este campo exibe um mini calendário para você escolher a data) e **Quantidade**, iremos preencher a data e como exemplo, vamos transferir somente um item.

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_add_mvt_transferencia_campos_data_qtd.png)

Agora o campo de **Produto** é vinculado automaticamente com a **aba Produtos**, caso queira mais informações sobre esta aba [clique aqui](/erp-v2/funcionalidades/produtos_servicos/produtos.md). Neste mesmo campo você pode ver que tem um ícone de lupa para que possa buscar os produtos em modo de lista.

Iremos selecionar nosso produto de exemplo (A caneca de café da Gestão Online) 😁👍

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_add_movimentacao_transferencia_campo_produto.gif)

Agora nos campos abaixo, temos a escolha do local de estoque que se encontra nosso produto, estes campos estão vinculados diretamente com a **aba Estoque**. Como seleiconamos o tipo **Transferência**, vamos escolher o local de estoque que tem o produto, e para onde ele vai. 

Não esquecendo que precisamos também definir para qual **empresa** ele será tranferido. Podendo uma empresa possuir mais de um local de estoque.

Outro item que marcaremos, é o tipo de lançamento, colocando como saída e o destino como entrada. Observe nosso exemplo abaixo.

{% hint style="warning" %}
**Local de estoque:** Caso queira informações sobre como utilizar a aba Local de Estoque, [**`clique aqui`**](/erp-v2/funcionalidades/unidades_locais_estoque/local_estoque.md).
{% endhint %}

{% hint style="warning" %}
**Empresas:** Caso queira informações sobre como utilizar a aba Empresas, [**`clique aqui`**](/erp-v2/funcionalidades/parametrizacoes/empresas.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_add_movimentacao_transferencia_campos_local_estoque_empresa_lancamento.png)

Por último a **Descrição** dessa movimentação que você está realizando, no nosso caso é somente um teste, então iremos descrever para que o registro fique no sistema.

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_add_movimentacao_transferencia_campo_descricao.png)

### Salvando movimentação de tipo transferência

Após finalizar o preenchimento, você clica em **`Salvar`** e o registro da nova movimentação de transferência será adicionada:

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_add_movimentacao_transferencia.gif)


## Campo




, venda, compra, devolução e ajuste);

- **Produto** (Defina qual produto terá a movimentação, para mais informações, 
- **Local de Estoque** (Defina qual local está o produto, para mais informações, [clique aqui](/erp-v2/funcionalidades/unidades_locais_estoque/local_estoque.md));
- **Empresa** (Defina qual empresa tem o produto, para mais informações, [clique aqui](/erp-v2/funcionalidades/parametrizacoes/empresas.md));
- **Lançamento** (Entrada ou saída);
- **Descrição** (Motivo da movimentação).



## Salvando movimentação de estoque

Após finalizar o preenchimento, você clica em **`Salvar`** e o registro da nova movimentação será adicionado:

![](/erp-v2/assets/funcionalidades/movimentacao_estoque/aba_movimentacao_estoque_add_produto_salvar.gif)

<br>