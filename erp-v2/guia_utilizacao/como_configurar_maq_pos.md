# Como configurar e vincular os pagamentos da minha maquininha POS GOPag?

Para utilizar a forma de pagamento com maquininha POS no Gestão Online, primeiro acesse o módulo **Financeiro**, clique na opção **Conta Bancária** e clique em [**Listar Contas**](https://docs.gestao.plus/erp-v2/funcionalidades/financeiro/listar_contas_bancarias). Você então terá acesso à tela de contas bancárias cadastradas dentro do sistema.

{% hint style="warning" %}
**Atenção:** As configurações da maquininha POS da GOPag só podem ser realizadas por usuários de alto nível dentro do Gestão Online. Por isso, algumas telas mostradas aqui talvez não estejam disponíveis. Para maiores dúvidas, contate o suporte.
{% endhint %}

![](/erp-v2/assets/guia_utilizacao/como_configurar_maq_pos_01.gif)

## Procurando conta bancária na tela Listar Contas

Com a tela [**Listar Contas**](https://docs.gestao.plus/erp-v2/funcionalidades/financeiro/listar_contas_bancarias) aberta, procure a sua conta GOPag cadastrada e clique em editar item.

![](/erp-v2/assets/guia_utilizacao/como_configurar_maq_pos_02.png)

Com o item aberto, observe que na parte mais baixa há uma opção chamada Pagamento Cartão Físico. Marque-a como ativa e em seguida salve a alteração realizada.

![](/erp-v2/assets/guia_utilizacao/como_configurar_maq_pos_03.png)

## Criando venda de exemplo 

Com a função de uso da máquina ativada, crie uma venda dentro do sistema e escolha uma das opções de pagamento via cartão de crédito ou débito habilitadas na tela [**Tipo de Movimentação**](https://docs.gestao.plus/erp-v2/funcionalidades/parametrizacoes/tipo_movimentacao).

No exemplo, vamos utilizar a opção **Cartão de Crédito 1x**. Após preencher todos os dados da venda e adicionar o produto/serviço que será vendido, observe que ao salvar a venda um novo botão ficará disponível no menu superior.

![](/erp-v2/assets/guia_utilizacao/como_configurar_maq_pos_04.gif)

## Sincronizando venda com maquininha POS GOPag

Agora com a maquininha em mãos, receba o pagamento com o cliente. 

Em seguida ao sair a primeira via impressa, será exibido um nome chamado AUTO junto com um código. Este será o código a ser adicionado na venda do Gestão Online para fazer o vínculo da venda.

![](/erp-v2/assets/guia_utilizacao/como_configurar_maq_pos_05.png)

Na venda criada, clique no novo botão <img src="/erp-v2/assets/icon_pos_tef.png" alt="" data-size="line"> que apareceu no menu superior, e então uma janela pop-up será exibida para escolher de qual máquina será feito o vínculo da venda.

![](/erp-v2/assets/guia_utilizacao/como_configurar_maq_pos_06.png)

Das opções mostradas, escolha a POS Maquina sem fio.

![](/erp-v2/assets/guia_utilizacao/como_configurar_maq_pos_07.png)

Preencha o campo com o código de autorização exibido na via impressa da máquininha. Em seguida, clique no botão <img src="/erp-v2/assets/icon_vincular_pagamento.png" alt="Vincular pagamento" data-size="line">.

![](/erp-v2/assets/guia_utilizacao/como_configurar_maq_pos_08.png)

Neste momento, o sistema fará o vínculo com o pagamento realizado e, no Gestão Online, será dada baixa no financeiro, e a venda atualizará o status de pagamento para pago.