# 🧾 Extratos de conta bancária

Nesta aba você encontra listados todos os extratos bancários integrados ao banco da conta na plataforma da **Gestão Online**. 

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_extratos_contas.gif)

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_caixa.png" alt="" data-size="line"> Gerar financeiro;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros de busca [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md).
{% endhint %}

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse, [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse).
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_extratos_contas_menu.png)

## Botão Gerar extrato

No primeiro botão do menu superior, temos o ícone <img src="/erp-v2/assets/icon_caixa.png" alt="" data-size="line"> para gerar financeiro para conciliação das taxas de vendas/movimentações.

Ao clicar neste ícone, uma janela será aberta para você preencher algumas informações para gerar o financeiro. De início, ele pede a data de início e fim do extrato do financeiro que será gerado:

![](/erp-v2/assets/funcionalidades/financeiro/aba_extratos_contas_menu_btn_gerar.gif)

Em seguida, você define de qual conta será gerado esse financeiro, lembrando que este campo está diretamente ligado à aba [**`Listar contas`**](/erp-v2/funcionalidades/financeiro/listar_contas_bancarias.md), ao trazer todas as contas.

![](/erp-v2/assets/funcionalidades/financeiro/aba_extratos_contas_menu_btn_gerar_conta.png)

Logo abaixo, está o campo da **Taxa do parceiro fornecedor**, para você selecionar o parceiro/fornecedor do lançamento da taxa. Ex: GOPag, Cielo ou Banco do Brasil. E este campo está diretamente ligado à aba [**`Parceiros`**](/erp-v2/funcionalidades/parceiros/fornecedores.md).

![](/erp-v2/assets/funcionalidades/financeiro/aba_extratos_contas_menu_btn_gerar_fornecedor.png)

Em penúltimo, para preenchimento, temos a taxa natureza, basicamente ela permite indicar o tipo de natureza que definirá esse financeiro que está sendo gerado. E assim como os campos anteriores, você tem uma ligação direta deste campo com a aba [**`Naturezas`**](/erp-v2/funcionalidades/parametrizacoes/naturezas.md)

![](/erp-v2/assets/funcionalidades/financeiro/aba_extratos_contas_menu_btn_gerar_natureza.png)

Por último, fica o campo de modo, nele você escolhe a quantidade de resultados a serem mostrados, como, por exemplo, definir para mostrar só os 100 primeiros resultados, etc. Observe a demonstração abaixo.

![](/erp-v2/assets/funcionalidades/financeiro/aba_extratos_contas_menu_btn_gerar_modo.png)

## Botão Gerar financeiro

Após preenchido os dados, você clica no botão **Gerar financeiro** e o carregamento será realizado. Caso haja alguma transação pendente ou diferente do que se tem registrado no sistema, ao clicar no botão gerar financeiro, ele fará essa sincronia automaticamente.

Lembrando que nesta mesma página é mostrado o extrato da conta bancária que foi sincronizada com o métodos OFX, VAN ou API, no caso quando se tem ativado o tipo de conciliação como integrado na [**aba de Listar contas**](/erp-v2/funcionalidades/financeiro/listar_contas_bancarias.md), que faz a atualização automática das contas bancárias.

![](/erp-v2/assets/funcionalidades/financeiro/aba_extratos_contas_menu_btn_gerar_financeiro.gif)