# 🔂 Contrato do controle de unidades

Nesta tela é possível gerenciar todos os contratos de controle de unidade cadastrados na plataforma. Os contratos dessa tela, precisam ser parâmetrizados conforme o acordado entre a **Empresa** (Franqueadora) e a **Unidade** (Franquia).

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato.gif)

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_importar.png" alt="" data-size="line"> Importar;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar novo contrato.

{% hint style="info" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros de busca [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md).
{% endhint %}

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse, [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse).
{% endhint %}

{% hint style="danger" %}
**Botão permissões:** Para mais informações sobre uso do botão <img src="/erp-v2/assets/icon_cadeado.png" alt="" data-size="line"> permissões, [**`clique aqui`**](/erp-v2/primeiro_acesso/permissoes_restricoes_excecoes.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_menu.png)

## Adicionar novo contrato de controle

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar um novo contrato de controle de unidade. Confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add.png)

Após clicarmos no botão adicionar novo contrato de controle, uma nova página será aberta e, Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;   
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

Este mesmo menu ganhará novos botões para uso assim que você salvar o novo contrato de controle de unidade. 😁

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_menu.png)

## Campos obrigatórios

No momento do cadastro de um novo contrato de controle de unidade, você precisará preencher alguns campos obrigatórios que têm o asterisco vermelho. Eles são essenciais para o mínimo funcionamento em nosso sistema.

{% hint style="info" %}
**Informativo:** É sempre importante lembrar de fazer o preenchimento completo dos dados desse contrato. 😉👍
{% endhint %}

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_contrato.png)

### Campo Unidade

No primeiro campo **Unidade**, que é um campo de preenchimento obrigatório. Você escolhe a qual unidade esse contrato terá vínculo. Lembrando que para escolher a unidade, é necessário já ter o cadastro feito na tela **Unidades**.

 Observe que nesse mesmo campo, temos um ícone <img src="/erp-v2/assets/funcionalidades/icon_nova_aba.png" alt="" data-size="line"> para editar a unidade selecionada abrindo ela em uma nova tela.

Acompanhe nossa demonstração de uso abaixo. Lembrando que neste exemplo vamos escolher a opção sede/matriz.

{% hint style="warning" %}
**Atenção:** É necessário que dentro do cadastro da unidade indicada, tenha um "Parceiro responsável" pela unidade, para que as rotinas automatizadas funcionem corretamente. Caso queira mais informações sobre como utilizar a tela de unidades, [**`clique aqui`**](/erp-v2/funcionalidades/unidades_locais_estoque/unidades_lojas.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_contrato_campo_unidade.gif)

Ao lado do campo de unidade, temos o de **Empresa**. Indique a "Empresa" que possui o contrato com essa unidade. Lembrando que para escolher a empresa, é necessário ele já ter o cadastro feito na tela [**`Empresas`**](/erp-v2/funcionalidades/parametrizacoes/empresas.md)

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_contrato_campo_empresa.gif)

Agora no campo de data, você precisa inserir a **data de validade** deste contrato que está criando, ela ajudará acompanhar com avisos caso esteja próximo ao vencimento.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_data_validade.png)

Depois você define se o **status** desse contrato estará ativado ou desativado. Isso fará com que o sistema trate das informações geradas pelo contrato ou não.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_status.png)

<!-- CONFIRMAR COM O PAULO ESTA PARTE, POIS FIQUEI COM DÚVIDA SOBRE USO DO CAMPO DE TIPO CONTRATO -->

### Campo tipo contrato

No campo **Tipo Contrato**, você tem quatro opções disponíveis, vejamos um pouco mais sobre cada uma. Observe que, ao clicar em algumas opções, um novo campo será mostrado ao lado para preencher o valor:

- **Sem limite:** A unidade não tem um limite para trabalhar com saldo negativo, isso pode implicar no impedimento de uso de algumas funcionalidades (Por exemplo: em uma venda na modalidade pré-pago)

- **Limite Aprovado:** É a quantia limite final disponível para uso.

- **Limite Pré-Aprovado:** É uma oferta condicional que ainda pode passar por uma verificação adicional antes de se tornar um **Limite aprovado**,

- **Ilimitado:** A unidade poderá utilizar o tanto que precisar, sem um limite definido.

Em nosso exemplo iremos selecionar o tipo **Limite Aprovado** e colocaremos o valor de R$ 1.000,00. Observe abaixo:

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_tipo_contrato_valor_limite.png)

### Campo fechamento automático

Agora uma atenção maior a este campo de **Fechamento automático**, pois nele temos uma série de novos campos e botões no menu superior ficarão disponíveis, a partir do momento que selecionar uma das opções.

### Fechamento todo dia do mês

Destas opções disponíveis, você tem para deixar ele desativado, onde não aparecerá nenhum campo extra para preenchimento. A opção de fechamento *Todo dia do mês* selecionado, você precisa depois definir os dias do mês, esses valores você precisa digitar e logo após pressionar a tecla enter para que seja confirmado. Observe nossa demonstração abaixo.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_fechamento_mes.gif)

### Fechamento todo dia da semana

 Agora marcando a opção de fechamento *Todo dia da semana*, aparecerão novos campos, o primeiro para você escolher o **dia da semana de fechamento automático**.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_fechamento_dia_semana.png)

Logo após, o campo de **fechamento automático tipo de negociação**, lembre-se que este campo está vinculado diretamente com a tela **Tipo de negociação** e as opções que ele trará, são as cadastradas nesta tela. 😁

{% hint style="info" %}
**Tipo de negociação:** Além de poder utilizar os tipos de negociação já disponíveis (que são compartilhados com a tela de vendas e financeiro, por exemplo), também é possível cadastrar um tipo de negociação com propósito específico para 'Fechamento/Acerto' ou até mesmo 'particular' para esse contrato. Por exemplo: boleto com prazo de 2 dias para pagamento; caso atrase, já incide juros e multa.
{% endhint %}

{% hint style="warning" %}
**Tipo de negociação:** Caso queira mais informações sobre como utilizar a tela tipo de negociação, [**`clique aqui`**](/erp-v2/funcionalidades/financeiro/tipos_negociacao.md).
{% endhint %}

Em nosso exemplo, vamos escolher a opção **Boleto - GOPag**. Observe abaixo:

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_fechamento_tipo_negociacao.png)

Logo ao lado, temos o campo **Fechamento automático tipo de movimentação**, lembre-se que ele tem vinculado com a tela **Tipo de movimentação** e as opções que ele trará, são as cadastradas nesta tela. 😁

{% hint style="warning" %}
**Tipo de movimentação:** Caso queira mais informações sobre como utilizar a tela tipo de movimentação, [**`clique aqui`**](/erp-v2/funcionalidades/parametrizacoes/tipo_movimentacao.md).
{% endhint %}

Em nosso exemplo, vamos escolher a opção **Venda - Unidade (Custo)**. Observe abaixo:

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_fechamento_tipo_movimentacao.png)

Agora, quanto aos demais campos em cinza, o preenchimento será feito automaticamente por nossa plataforma. 😁

E o último campo para preenchimento é o de **Observação**, onde você pode deixar alguma anotação a respeito deste contrato.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_observacao.png)

### Salvando controle de unidade

Após fazer o preenchimento dos dados do novo contrato, você pode clicar no ícone <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> de salvar para ser registrado o contrato do controle de unidade e ficar disponível para utilização.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_salvar.gif)

## Abas após salvar

Assim que você salvar o contrato de controle, novas abas ficarão disponíveis para você utilizar, elas aparecem na parte de baixo da página.

### Aba Movimentações de saldo

A primeira é de movimentação de saldo, exibindo todos os tipos de lançamentos, sendo débito ou crédito, informando os valores de saldo, limites e saldo final.

Nessa tela, o sistema funciona de forma semelhante a um "extrato de um banco" de um conta corrente por exemplo, onde a cada lançamento ocorre uma entrada (Crédito) ou uma saída (Débito), e sempre é recomputado o saldo atual.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_guia_movimentacoes_saldo.png)

Caso seja necessário algum ajuste no saldo, ou o lançamento de alguma despesa ou receita diretamente no controle da unidade, é possível adicionar um novo lançamento manualmente, entre crédito ou débito, e o valor deste lançamento. Após salvar, ele aparecerá no "extrato" imediatamente já recomputando o saldo. 😁

Mas lembre-se, normalmente essas movimentações de crédito ou débito, são programadas para serem geradas automaticamente por nossa plataforma, atráves de fluxos de comissão ou custo que são disparados atráves de rotinas financeiras, ou de movimentações das vendas por exemplo. 

{% hint style="warning" %}
**Controle de movimentação de unidades:** Caso queira mais informações sobre essa tela, [**`clique aqui`**](/erp-v2/funcionalidades/controle_unidades/controle_movimentacao.md).
{% endhint %}

{% hint style="danger" %}
Em caso de dúvidas sobre esse fluxo, entre em contato com o nosso suporte. 
{% endhint %}

### Aba Movimentações pendentes de fechamento

Aqui estão todas as movimentações pendentes, que estão na fila para entrarem em um "fechamento", seja um pedido, venda, compra e recorrência. Ela é espelho da nossa **Tela de movimentações**, porém, trazendo só os itens pendentes deste contrato que criamos. 😉

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_guia_movimentacoes_pendentes.png)

As movimentações que aparecem aqui, dentro das regras criadas no "Fechamento automático", serão apuradas resultando em **uma linha na movimentação de saldo**, sendo ela de débito (caso o fechamento seja negativo, ou seja a unidade tem algo a pagar para a empresa). Ou sendo ela de crédito (caso o fechamento seja positivo, ou seja a unidade tem algo para receber da empresa)

Observe o exemplo abaixo, foi criado o contrato com fechamento automático todo mês no dia 01 e 16. É importar lembrar que a funcionalidade desse fechamento tem um vínculo com a tela **Tipo de movimentação**, pois nela, precisa estar ativado a opção *Atualiza controle de unidade*.

{% hint style="warning" %}
**Tipo de movimentação:** Caso queira mais informações sobre essa tela, [**`clique aqui`**](/erp-v2/funcionalidades/parametrizacoes/tipo_movimentacao.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_guia_movimentacoes_pendentes_exemplo.png)

Observe que existe uma movimentação pendente de fechamento. Ela só será processada na data que está definido neste contrato criado.

Mas caso ocorra algum imprevisto e você precise fazer o fechamento destas movimentação antes do perído que você determinou, pode clicar no botão <img src="/erp-v2/assets/icon_processar.png" alt="" data-size="line">**processar fechamento automático**, e ele irá virar uma linha na tela **Movimentações de saldo**.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_guia_movimentacoes_pendentes_exemplo_btn_processar.png)

Após clicar para fazer o fechamento, observe que um nova linha foi adicionada a tela **Movimentação de saldo**, e uma informação importante, essa única linha trará várias movimentações, e você pode gerar um relatório e acompanhar cada uma clicando com o botão direito do mouse, observe nosso exemplo abaixo.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_guia_movimentacoes_pendentes_exemplo_fechamento_gerar_relatorio.gif)

Este documento gerado trás algumas informações importantes, como por exemplo, o parceiro/cliente (final) que efetuou a venda/compra, qual foi o produto, o histórico dessa venda, valor de referência, o tipo (caso seja crédito ou débito) e o valor final.

Já parte final do relatório em PDF colocamos as somas e cálculos de fechamento, saldo anterior e atual, conforme marcado na imagem abaixo.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_guia_movimentacoes_pendentes_exemplo_fechamento_gerar_relatorio_campos.png)

### Aba Fechamentos de contrato

Aqui você encontrará o histórico dos fechamentos (automáticos ou manuais) que ocorreram nesse contrato.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_guia_fechamentos_contrato.png)

Quando utilizado na modalidade automática normalmente, um novo lançamento é feito logo em seguida da apuração das **Movimentações pendentes de fechamento** e o sistema computa um saldo negativo para a unidade (ou seja, a unidade está "devendo" a empresa). Aí nesse caso, automáticamente a plataforma criará uma "Venda" com a cobrança exatamente no valor que a Unidade deve a empresa (O envio da cobrança é realizado para o "Parceiro" indicado como o responsável da unidade)

Mesmo em outras situações e/ou outras modalidades, como por exemplo, gestão direta de saldo (Indepentende de ter ou não "Movimentações pedentes de fechamento"), se o sistema computar um saldo negativo ele realizará o mesmo comportamento (Irá gerar uma "Venda" com a cobrança do saldo que está negativo)

O tipo de movimentação recomendado que seja utilizado para os "Fechamentos do contrato" faz com que o "Saldo" seja incrementado automáticamente (Seja criado uma nova linha no "Extrato" do controle da unidade com uma movimentação de crédito) no valor correspondente do saldo negativo de quando foi apurado, zerando o saldo que anteriormente estava negativado. 

{% hint style="warning" %}
**Atenção:** Caso exista lançamentos no extrato que fiquem entre o período da apuração e a liquidação do pagamento, o saldo sempre será computado da maneira adequada. (O saldo será acumulado para um acerto posterior)
{% endhint %}

{% hint style="info" %}
Lembrando que é possível realizar um fechamento manualmente, caso o saldo esteja negativo. Sempre que necessário. (Botão na barra de ferramentas do contrato)
{% endhint %}


{% hint style="info" %}
Caso necessite ajustar algo no fechamento apurado, como por exemplo alterar a data de vencimento do boleto bancário, um ajuste na nota fiscal ou qualquer outra situação, basta abrir a "Venda". Para mais informações sobre como utilizar a tela de movimentações/vendas, [**`clique aqui`**](/erp-v2/funcionalidades/comercial/vendas.md).
{% endhint %}

### Aba Histórico

Por último, na aba de histórico, você consegue acompanhar todas as modificações/alterações feitas no contrato através desta aba.

Os lançamentos aqui são automáticos, ao ajustar um campo por exemplo. Ou até mesmo baseado em eventos que acontecem; quando uma unidade é bloqueada por inadimplência, ou desbloqueada ao efetuar o pagamento. Ou mesmo quando um gestor faz a liberação de confiança (para permitir que uma unidade, mesmo que inadimplente, continue operando).


![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_guia_historico.png)

## Botões do menu superior

O menu superior apresenta funcionalidades diferentes de acordo com a configuração do contrato.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_menu_novos_btns.png)

### Botão Processar movimentações pendentes de fechamento

Clicando neste ícone, uma nova janela será aberta para você, solicitando que informe a data final para então o sistema processar o fechamento.

Nessa caso o botão acionará uma ação que irá realizar a apuração das vendas que estão na tela `Movimentações pendentes de fechamento` o sistema irá computar cada venda uma que está pendente de fechamento computando uma "Comissão" ou um "Custo" a cada venda, respeitando a `tabela de preço de custo ou comissão` e o `tipo de movimentação` realizado na venda, no final terá o resultado se a operação será de `débito` (ou seja, a unidade está "devendo" a empresa) ou de `crédito` (ou seja, a unidade tem um valor "a receber" da empresa).

Observe nosso teste abaixo, a mensagem que será mostrada é informando que não temos nenhum caso de fechamento pendente. 

Porém, se houvesse algum caso, ele teria realizado o fechamento automaticamente e mostrado a mensagem de fechamentos realizados com sucesso.


![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_menu_novos_btns_processar_pendentes_fechamento.gif)

### Botão Processar fechamento automático

Agora o botão processar fechamento automático faz basicamente o papel de antecipar o fechamento que você programou.

Quando você clica neste botão, uma janela será mostrada para você. Nela, pode escolher uma das duas opções de tipo. A primeira é `processar "Movimentações pendentes de fechamento" e saldo atual`, e a outra `somente saldo atual`.


![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_menu_novos_btns_processar_fechamento_automatico.png)

Na opção de `somente saldo atual`, caso o saldo atual da unidade seja negativo (ou seja, a unidade está "devendo" a empresa). Nesse caso, automáticamente a plataforma criará uma "Venda" com a cobrança exatamente no valor que a Unidade deve a empresa (O envio da cobrança é realizado para o "Parceiro" indicado como o responsável da unidade)

Já na opção de `processar "Movimentações pendentes de fechamento" e saldo atual`, o sistema realizará a ação descrita anteriormente neste manual em "Botão Processar movimentações pendentes de fechamento" e logo em seguida também já irá realizar a operação de saldo descrita na opção anterior (de `somente saldo atual`)

### Botão Atualizar status

Este botão irá atualizar todas as situações do contrato que você gerou, forçando a verificação de todos os itens interligados nesse contrato, antecipando as rotinas que são executadas automáticamente a cada alguns minutos.

Por exemplo, um pagamento que já foi realizado e ainda não foi atualizado no contrato a liberação da unidade que está bloqueada por inadimplência.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_menu_novos_btns_atualizar_status.gif)

### Botão Gerar previsão de fechamento

Por último, o botão de **gerar previsão do fechamento**, ao clicar nele, uma janela pop-up será aberta para você poder preencher alguns campos. O primeiro é o de *data final*, pois ele irá processar uma previsão do fechamento de movimentações entregues com base na data que for colocada. 

Você também tem a opção de enviar este relatório por e-mail, pois ele criará um arquivo em PDF e enviará em anexo.

Observe nosso exemplo abaixo, criando o arquivo e abrindo-o.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_menu_novos_btns_gerar_previsao.gif)