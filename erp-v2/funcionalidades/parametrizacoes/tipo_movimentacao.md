# 🔁 Tipo de movimentação

Aqui você tem a visão de todas as movimentações cadastradas na plataforma **Gestão Online**, podendo cadastrar um novo tipo de movimentação, editar informações existentes e até excluir uma movimentação cadastrada.

Estas movimentações serão utilizadas em vendas, vendas recorrentes, pedidos de venda, compras, pedidos de compra, importações e financeiro.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao.gif)

<br>

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_bandeira.png" alt="" data-size="line"> Testar permissão de uso online;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Empresa.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_menu.png)

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Adicionar novo tipo de movimentação

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo item, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add.png)

<br>

Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_cadeado.png" alt="" data-size="line"> Restrições/Exceções;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

{% hint style="warning" %}
**Botão restrições/exceções:** Para mais informações sobre uso do botão <img src="/erp-v2/assets/icon_cadeado.png" alt="" data-size="line"> restrições/exceções, [**`clique aqui`**](/erp-v2/primeiro_acesso/permissoes_restricoes_excecoes.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_menu.png)

<br>

## Menu de Restrições e Exceções

Ao clicar no botão de restrições/exceções, uma nova janela irá de abrir. Aqui você pode encontrar as definições de uso para a movimentação em específico que você está editando.

{% hint style="danger" %}
**Atenção:** Esta alteração só ficará disponível quando o **`Tipo de movimentação`** já estiver criado. Caso faça antes de criar, uma janela de aviso aparecerá informando que não será possível prosseguir. 😉
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_btn_restricao.png)

Seguindo o exemplo demonstrado abaixo, você pode definir, por exemplo, um tipo de negociação em dinheiro e definir se ele será sem restrição, restrição (Só pode ser utilizado com) e exceção (Só não pode ser utilizado com).

E essa configuração pode ser feita com grupo de produto, um produto, uma empresa, vendedor, unidade e até um parceiro. Fazendo assim com que a possibilidade de erro por falta de atenção em alguma venda não aconteça, pois a restrição/exceção entrará em ação assim que for preciso.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_btn_restricao.gif)

## Campos de preenchimento obrigatório

No momento do cadastro de um tipo de movimentação, você precisará preencher alguns campos obrigatórios que tem o asterisco vermelho. 

Sendo eles descrição, status e tipo. Estes itens são o mínimo necessário para poder salvar um novo tipo de movimentação.

{% hint style="info" %}
**Informativo:** Os outros dois campos **Usuário** e **Data de Alteração** serão preenchidos por nossa plataforma, dados estes que não podem ser alterados por nenhum usuário. 😉👍
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_movimentacao.png)

<br>

A descrição do tipo de movimentação fica à sua escolha. Já o campo de **Status** define se o tipo de movimentação estará disponível para uso ou não.

## Tipos de movimentação

Você tem vários tipos para definir qual movimentação será, estão entre eles:

- Venda;
- Venda recorrente;
- Pedido de venda;
- Compra;
- Pedido de compra;
- Financeiro;
- Importação;

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipos.png)

## Tipo Venda

No tipo venda, você pode definir o que acontecerá na plataforma, por exemplo, se irá atualizar o financeiro, estoque, controle de unidade. Também definir permissões como entrega, indicação, desconto, frete e vouchers.

Não só estas definições, mas descendo um pouco no menu, você verá os `Requisitos da movimentação`, podendo assim escolher a origem da movimentação, valor, número de produtos e quantidade.

{% hint style="info" %}
**Informativo:** As configurações não se limitam só a estes campos apresentados, pois a cada opção marcada um novo menu é aberto ao fim da página, com as configurações específicas daquele campo que você marcou. 😉👍
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_venda.gif)

### Atualiza controle de unidade (comercial/saldo)

Ao marcar a opção atualiza controle de unidade (comercial/saldo), isso criará um vínculo com a tela **Controle de unidade**.

{% hint style="info" %}
**Controle de unidade:** Para mais informações sobre como configurar esta tela, [**`clique aqui`**](/erp-v2/funcionalidades/controle_unidades/contrato_unidades.md).

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_venda_controle_comercial.png)

Um novo espaço ficará disponível com dois campos para marcar, o primeiro é o de controle contrato para você definir entre as opções:

- **Despesa (valor venda/financeiro):**  Esta opção categoriza uma transação como uma despesa, calculada com base no valor de venda ou no valor financeiro do contrato. Utilizada quando um contrato representa um custo registrado a partir do valor acordado para a venda.

- **Receita (valor venda/financeiro):** Esta opção categoriza uma transação como uma receita, calculada com base no valor de venda ou no valor financeiro do contrato. Utilizada quando um contrato representa uma entrada de dinheiro, registrada a partir do valor acordado para a venda.

- **Despesa (valor custo/comissão):** Esta opção categoriza uma transação como uma despesa, calculada com base no valor de custo ou nas comissões. Utilizada quando um contrato representa um custo, registrado a partir do valor de custo das mercadorias ou serviços, ou das comissões pagas.

- **Receita (valor custo/comissão):** Esta opção categoriza uma transação como uma receita, calculada com base no valor de custo ou nas comissões. Utilizada quando um contrato resulta em uma entrada de dinheiro, registrada a partir do valor de custo das mercadorias ou serviços, ou das comissões recebidas.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_venda_controle_comercial_controle_controle_despesa_receita.png)

No segundo campo, você tem o **Tipo controle contrato**. Aqui basicamente você define se a informação será registrada no controle de contrato ao confirmar uma movimentação, ou fazendo uma baixa no financeiro.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_venda_controle_comercial_tipo_controle.png)

### Atualiza controle de unidade (produtivo/fechamento)

Ao marcar a opção atualizacontrole de unidade (produtivo/fechamento), isso criará um vínculo com a tela **Controle de unidade**.

{% hint style="info" %}
**Controle de unidade:** Para mais informações sobre como configurar esta tela, [**`clique aqui`**](/erp-v2/funcionalidades/controle_unidades/contrato_unidades.md).

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_venda_controle_produtivo.png)

Um novo espaço ficará disponível com o campo controle contrato para você definir/escolher entre as opções:

- **Despesa (valor venda/financeiro):** Utilizada quando um contrato representa um custo registrado a partir do valor acordado para a venda.
- **Receita (valor venda/financeiro):** Utilizada quando um contrato representa uma entrada de dinheiro, registrada a partir do valor acordado para a venda.
- **Despesa (valor custo/comissão):** Utilizada quando um contrato representa um custo, registrado a partir do valor de custo das mercadorias ou serviços, ou das comissões pagas.
- **Receita (valor custo/comissão):** Utilizada quando um contrato resulta em uma entrada de dinheiro, registrada a partir do valor de custo das mercadorias ou serviços, ou das comissões recebidas.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_venda_controle_produtivo_controle_contrato.png)

## Tipo Venda recorrente

No tipo venda recorrente, você pode ativar permissão de desconto, permitir geração de comissão para indicador. Não só estas opções como também as funções de `Requisitos da movimentação` citados acima no tipo venda.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_recorrente.gif)

## Tipo Pedido de venda

No tipo pedido de venda, você define se a tabela de preço secundária será custo, comissão ou não ficará habilitada. Pode definir atualização do financeiro e estoque. Também permitir gerar fiscal, permitir entrega, frete, desconto, indicação e adição de vouchers.

Lembrando que cada item marcado pode abrir um novo menu de opções na parte de baixo da página!

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_pedido.gif)

## Tipo Compra

No tipo compra, você pode atualizar o financeiro, estoque, controle de unidade (Seja comercial/saldo ou produtivo/fechamento) e também gerar fiscal. Lembrando que cada item marcado, um novo menu será disponibilizado com mais opções para preenchimento. Agora, os campos de usuário e data de alteração não podem ser alterados, por servirem para controle da nossa plataforma.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_compra.gif)

## Tipo Pedido de compra

Já o tipo pedido de compra não possui menus alternativos para preenchimento, sendo ele uma função do tipo única, sem necessidade de intervenção. Mas não esqueça que o botão de restrições se aplica nele, caso necessite.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_pedido_compra.png)

## Tipo Financeiro

No tipo financeiro você pode ativar a atualização de controle da unidade (Comercial/saldo), sendo assim definir o controle contrato entre despesa e receita de venda/financeiro, receita e despesa de custo/comissão. E no tipo de controle de contrato você tem como definir ao confirmar movimentação/venda/financeiro ou ao baixar financeiro.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_financeiro.gif)

## Tipo Importação

Agora, o tipo importação também não possui menus alternativos para preenchimento, sendo uma função única, sem necessidade de intervenção. Mas não esqueça que o botão de restrições se aplica nele, caso necessite.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_tipo_importacao.png)

<br>

Após finalizar o preenchimento, você clica em **`Salvar`** e o registro do novo tipo de movimentação será salvo:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_movimentacao_add_salvar.gif)

<br>
