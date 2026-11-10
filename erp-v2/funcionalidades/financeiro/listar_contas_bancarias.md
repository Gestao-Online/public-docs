# 💳 Listar contas

Nesta tela você encontra listadas todas as contas bancárias cadastradas na plataforma da **Gestão Online**. E caso tenha alguma conta faltando, você pode efetuar o cadastro seguindo este manual.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_contas.gif)

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_grafico.png" alt="" data-size="line"> Relatório de fluxo de caixa;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar conta bancária.

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros de busca [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md).
{% endhint %}

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse).
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_contas_menu.png)

## Botão relatório de fluxo de caixa financeiro

Ao clicar neste botão, uma janela será aberta para que você preencha os dados para emitir um relatório. De forma simples, podemos dizer que este relatório de fluxo de caixa é usado por você para acompanhar a situação financeira da sua empresa.

Nesta janela aberta tem alguns campos de preenchimento obrigatório, sendo eles **Conta** e **Tipo**. Conforme marcado na imagem abaixo:

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_contas_btn_fluxo_caixa.png)

Ao clicar no primeiro campo de **Conta** será carregado as contas cadastradas na plataforma. Lembrando que estas são as contas que aparecem nesta tela.

É possível definir a **data de inicio e fim** dos relatórios que serão exibidos, e o **tipo de arquivo**, que pode ser `PDF` ou `EXCEL` para efetuar o download.

Observe abaixo o exemplo que fizemos, o relatório é mostrado em uma nova tela permitindo o download ou impressão. Nosso relatório é somente para ilustrar, não possui dados de entrada ou saída.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_contas_btn_fluxo_caixa_conta.gif)

## Adicionar nova conta bancária

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar uma nova conta bancária, confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_contas_add.png)

Após clicarmos no botão adicionar nova conta bancária, uma nova página será aberta e nela, Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;   
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar rascunho;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_menu.png)

No momento do cadastro de uma nova conta bancária, será necessário preencher alguns campos obrigatórios que têm o asterisco vermelho. Eles são essenciais para o mínimo funcionamento no sistema.

{% hint style="info" %}
**Informativo:** É sempre importante lembrar de fazer o preenchimento completo dos dados da conta bancária. 😉👍
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta.png)

No primeiro campo temos as opções de contas, cada uma mostrará novos campos para você preencher e complementar o cadastro da conta bancária, vejamos cada uma das opções abaixo.

## Conta tipo caixinha

Usado, por exemplo, para o caixa de uma loja, esta opção exibe somente os campos de **Descrição** e para escolher a empresa. As informações bloqueadas de alteração são **Saldo inicial**, **Data Saldo inicial** e **Tipo conciliação**.

Na descrição você pode colocar um nome que facilite a identificação desta conta bancária quando precisa buscá-la para uso.

Já no campo de empresa, o vínculo é feito com a **Tela  empresas**, e você pode escolher uma empresa cadastrada. E para mais informações sobre a tela Empresas, [**`clique aqui`**](/erp-v2/funcionalidades/parametrizacoes/empresas.md)

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_caixinha.png)

## Conta tipo poupança e Corrente

Além dos campos padrões **Tipo**, **Descrição** e **Empresa**, também fica disponível o campo de **Banco**, **Agência bancária** e **Conta**.

Nestes campos você pode clicar e nossa plataforma fará a busca dos bancos cadastrados, observe o exemplo abaixo:

{% hint style="warning" %}
**Bancos:** Caso queira mais informações sobre como cadastrar novos bancos, [**`clique aqui`**](/erp-v2/funcionalidades/financeiro/bancos.md).
**Agências:** E para mais informações sobre cadastrar agências bancárias, [**`clique aqui`**](/erp-v2/funcionalidades/financeiro/agencia_bancaria.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca.gif)

No final da página, há o botão de **Pagamento Boleto**, que pode ser usado para pagamentos online ou PDV (Ponto De Venda). Em seguida, novos campos serão exibidos para você preencher, resultando em duas opções:

### Dados para geração de transação

Este **Token e/ou Número Convênio** tem uma relação direta e fundamental com a emissão de um boleto bancário, ao identificar a empresa ou entidade que está emitindo o boleto no sistema do banco. Cada cedente possui um código único que permite ao banco distinguir entre diferentes empresas que utilizam seus serviços de cobrança.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_convenio.png)

### Dados para geração do boleto

Dos campos para preenchimento, você tem **Nosso Número Sequência**, nele o código do convênio é frequentemente utilizado como parte da fórmula para gerar o "Nosso Número", sendo o identificador único de cada boleto. A inclusão do código ajuda a garantir que cada "Nosso Número" seja único e rastreável.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_nosso_numero.png)

Logo na sequência tem os campos de **mensagem personalizada** e **Local pagamento**, podem ser utilizadas para explicar sobre multas e juros que serão aplicadas ao boleto, e dar instruções sobre o local de pagamento.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_mensagens.png)

Agora, no tipo de multa, você tem três opções disponíveis: **isento**, **valor em reais** e **valor em percentual**. Ao escolher reais ou percentual, um novo campo será mostrado para você definir o valor:

{% hint style="warning" %}
**Valor Multa:** Conforme o **Código Tributário Nacional**, o valor da multa para boletos não pode passar de 2%.
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_multa.png)

Pode também configurar o juro mora ou moratórios, podendo ser em dinheiro ou porcentagem igual o exemplo da multa que mostramos acima.

{% hint style="warning" %}
**Valor Juro:** Esses juros consistem em uma taxa aplicada sobre o atraso no pagamento de uma conta, sendo possível colocar 1% ao mês no máximo, conforme estabelecido pelo **Código Tributário Nacional**.
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_juro.png)

**Espécie do documento**, as espécies precisam ser usadas conforme o tipo de documento que você usa para pagar, ou se o banco pedir um tipo específico. Pois garante a segurança e a finalidade do boleto emitido.

Das espécies mais comuns, temos:

- **DM - Duplicata mercantil:** um título de crédito no qual o comprador se compromete a pagar o valor indicado na fatura num prazo mínimo de 30 dias.

- **DR - Duplicata Rural:** usada para vendas a prazo de bens agrícolas, extrativos ou pastoris, realizadas diretamente por produtores rurais ou suas cooperativas, também pode ser utilizada como título de crédito.

- **NP - Nota promissória:** é um documento que serve como promessa de pagamento de uma dívida.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_especie.png)

Os últimos dois campos para preenchimento são os **Dias Limite**, para definir a quantidade de dias limite para pagamento após o vencimento do boleto. E o campo **Variação da carteira**, o qual é usado somente pelo Banco do Brasil:

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_dias_variacao.png)

## Conta tipo cartão de crédito

Com a opção tipo **Cartão de Crédito** definida, será solicitado o banco. Lembrando que você pode adicionar um novo banco com o atalho do ícone <img src="/erp-v2/assets/icon_adds.png" alt="" data-size="line">, ou então editar um banco já cadastrado clicando no ícone <img src="/erp-v2/assets/icon_nova_aba.png" alt="" data-size="line">. 

{% hint style="warning" %}
**Bancos:** Caso queira mais informações sobre como cadastrar novos bancos, [**`clique aqui`**](/erp-v2/funcionalidades/financeiro/bancos.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_cc_banco.png)

Já no campo de empresa, o vínculo é feito com a **Tela  empresas**, e você pode escolher uma empresa cadastrada. E para mais informações sobre a tela Empresas, [**`clique aqui`**](/erp-v2/funcionalidades/parametrizacoes/empresas.md)

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_cc_empresa.png)

Os últimos campos para configurar são os de **Multa percentual** e **Juro percentual** quando o cliente atrasa o pagamento da fatura. O Código de Defesa do Consumidor (CDC) estabelece que essa multa é de 2% ao mês, independentemente do número de dias de atraso. Além disso, também há a cobrança de juros de mora, que não pode ultrapassar 1% ao mês. Assim, a soma da multa por atraso e dos juros de mora pode chegar a 3% ao mês.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_cc_multa_juro.png)

## Conta tipo meios de recebimento

Opção essa também recomendada para o tipo loja física, ao deixar disponível várias opções de pagamento.

As informações seguem sendo as mesmas dos demais tipos falados acima, sendo necessário informar o **Banco**, a **Descrição** e a **Empresa**. 

O que diferencia são os vários tipos de forma de pagamento, a primeira sendo o [**`Boleto`**](https://docs.gestao.plus/erp-v2/funcionalidades/financeiro/listar_contas_bancarias#dados-para-geracao-do-boleto), que já foi explicado logo acima, o segundo sendo o **`Cartão`** que já foi explicado também no tópico anterior.

Agora na opção **`Cartão físico`** é usado para pagamento por máquina física POS m-POS e/ou PINPAD.

E por último o pagamento por PIX, precisando somente do banco para o recebimento dos pagamentos.

Todas as transações estarão vinculadas ao Token/número do convênio, que explicamos acima, para revê-lo [**`clique aqui`**](https://docs.gestao.plus/erp-v2/funcionalidades/financeiro/listar_contas_bancarias#dados-para-geracao-de-transacao)

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_cc_formas_pagamento.png)

##  Tipos de conciliação

Você tem três opções de conciliação bancária para utilização, sendo sos tipos, desativada, onde não existe a função de conciliação, o tipo simples, onde as informações são inseridas manualmente no sistema, e a conciliação integrada, que para o caso do banco da GOPag tudo é vinculado automaticamente para você.

### Tipo conciliação - Desativado

Com o tipo de conciliação desativada, deixa de existir as opções dentro do sistema.

### Tipo conciliação - Simples 

Com o modo de conciliação simples ativado, todos os dados de comparação da conta bancária com o sistema deverão ser feitos de forma manual, precisando ter muito cuidade com os preenchimentos e verificando bem os lançamentos para não haver divergencia entre os valorese possíveis relatórios que for emitir dentro do sistema.

O primeiro botão <img src="/erp-v2/assets/icon_mao_dinheiro.png" alt="" data-size="line"> **Ativar/Alterar conciliação** permite que você defina o saldo inicial da sua conta, a data em que irá iniciar essa conciliação e qual o tipo de conciliação você irá utilizar. 

Em nosso caso, será o tipo **Simples**.

{% hint style="warning" %}
**Atenção:** Ao definir o saldo inicial, recomendamos usar o saldo atual da sua conta bancária e começar a registrar as transações corretamente a partir desse ponto. Isso evita o trabalho excessivo de lançar todas as transações anteriores, o que seria muito oneroso e desnecessário. 
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_concilicacao_simples_menu_ativar.gif)



### Tipo conciliação - Integrado 

Com o modo de concicliação integrado ativado, você não precisará se preocupar com os lançamentos no fluxo de caixa com a conta bancária.

O primeiro botão <img src="/erp-v2/assets/icon_mao_dinheiro.png" alt="" data-size="line"> **Ativar/Alterar conciliação** permite que você defina o saldo inicial da sua conta, a data em que irá iniciar essa conciliação e qual o tipo de conciliação você irá utilizar. Em nosso caso, o tipo será **Integrado**.

{% hint style="warning" %} 
**Atenção:** Ao definir o saldo inicial, recomendamos usar o saldo atual da conta e começar a registrar as transações corretamente a partir desse ponto. Isso evita o trabalho excessivo de lançar todas as transações anteriores, o que seria muito oneroso e desnecessário. 
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_concilicacao_integrado_menu_ativar.gif)

Desta forma, a conciliação automática estará ativa em sua conta, lembrando que esta função é ativa **somente** para a conta GOPag, caso você utilize outro tipo de banco, você pode utilizar a função **Importar arquivo OFX**. 

Caso queira mais informações pode acessar nosso manual de [Exportar arquivo OFX](/erp-v2/funcionalidades/financeiro/exportar_ofx.md) e conferir a maneira de exportar do seu banco.

Não só os botões do menu, como também novas abas são mostradas a você, entre elas a de **Extrato**.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_concilicacao_integrado_aba_extrato.png)

Com o extrato já no sistema (seja por meio da GOPag ou Importação do arquivo OFX), você pode clicar no botão <img src="/erp-v2/assets/icon_lupa_dinheiro.png" alt="" data-size="line"> **Busca extrato para conciliação**.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_concilicacao_integrado_btn_lupa_dinheiro.png)

Com a janela de **Busca extrato para conciliação**, você precisa definir a data inicial e data final de busca, em seguida clicar no botão **Buscar**. 

{% hint style="info" %} 
**Improtante:** A data de inicio não pode ser menor que a data do saldo inicial que você configurou. 📆
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_concilicacao_integrado_busca_extrato.gif)

Em seguida, você pode utilizar o botão **Conciliação inteligente**, ao clicar nele uma janela será aberta com algumas opções para você preencher.

Dos campos disponiveis, primeiro são as datas de início e datas de fim da concicliação inteligente.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_concilicacao_inteligente_datas.png)

É possível definir o tipo de conciliação entre, crédito, débito, pagamento, transferência ou todos os tipos.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_concilicacao_inteligente_tipos.png)

E por último o modo que a conciliação inteligente irá tratar as informações do extrato, como por exemplo, os 100 primeiros resultados, os 500 primeiros resultados, ou então todos os resultados do período.

{% hint style="info" %} 
**Importante:** No sistema, caso o número de informações seja muito grande, uma mensagem será exibida informando que não será possível processar tudo de uma vez, neste caso, use as outras opções disponíveis e siga com a conciliação até encerrar.
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_concilicacao_inteligente_modo.png)

Agora você pode conferir suas transações, e verá que a conciliação já foi realizada. Em alguns casos pode ocorrer de uma transação ou outra não serem lidas, neste caso você pode efetuar manualmente a conciliação.

## Salvando uma conta bancária

Após fazer o preenchimento dos dados e definir qual conta você precisa cadastrar, você pode clicar no ícone <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> de salvar para que ela seja registrada e fique disponível para utilização.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_salvar.gif)

## Abas após salvar nova conta

Assim que você salvar a conta bancária, as novas guias estarão disponíveis para você utilizar. Elas são a de **Movimentações/Transferências**, **Saldo**, **Arquivo remessa** e **Arquivos retorno**. 

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia.png)

### Aba Movimentações/Transferências

Aqui estão todas as movimentações bancárias entre as contas, desde saques, resgates, aplicações ou até mesmo depósitos.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_movimentacoes.png)

As movimentações podem ser inseridas manualmente, ao clicar em adicionar uma nova movimentação/transferência, você terá alguns campos para preencher, o primeiro é o tipo, com algumas opções para você escolher. Em nosso exemplo de demonstração, marcamos a opção depósito:

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_movimentacoes_add_tipo.png)

Logo em seguida, é preciso preencher a data de lançamento, lembrando que este item é obrigatório.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_movimentacoes_add_data_lancamento.png)

Na sequência, temos os campos de valor, para definir qual a quantia da movimentação, a conta (A qual é preenchida automaticamente, não podendo ser modificada), e o tipo de lançamento, sendo um débito ou crédito.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_movimentacoes_add_valor_conta_lancamento.png)

Por último, temos a descrição da movimentação, para poder identificar a movimentação realizada, lembrando que é também um item obrigatório.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_movimentacoes_add_descricao.png)

Após salvar esta movimentação, ela ficará com um status definido como **Pendente de conciliação**, caso já tenha confirmado a conciliação, você pode mudar o status clicando manualmente com o botão direito do mouse sobre a movimentação, observe nosso exemplo abaixo, mudando essa movimentação do tipo depósito.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_movimentacoes_add_mudar_concilicaca.gif)

### Aba Saldo

Nesta guia ficam os valores do saldo da conta cadastrada desde o seu saldo inicial, todas as movimentações registradas aqui são feitas automaticamente, somente para apreciação, não tendo opção de adicionar/remover manualmente.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_saldo.png)

### Aba Arquivo remessa

O arquivo de remessa é um documento enviado ao banco ou instituição financeira para notificar a emissão de uma cobrança registrada, como um boleto, por exemplo. 

Esse arquivo inclui informações que possibilitam registrar ou dar baixas em cobranças, realizar pagamentos de títulos, impostos e processar a folha de pagamento.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_arquivos_remessa.png)

Você pode adicionar o arquivo remessa manualmente, clicando no botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar, esta tela será mostrada a você. 

Pode adicionar a descrição do arquivo, e clicar no botão **Escolher arquivo**. Uma janela será aberta para selecionar o arquivo e enviar para o sistema.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_arquivos_remessa_add.png)

É possível também, através do menu superior, clicar no botão gerar remessa, e o arquivo será criado para você automaticamente.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_arquivos_remessa_btn_gerar.png)

### Aba Arquivos retorno

O arquivo de retorno é a resposta do banco às transações registradas no arquivo de remessa. 

Ele contém informações detalhadas sobre as transações originadas a partir da remessa, incluindo, por exemplo, a confirmação do pagamento das taxas condominiais pelos condôminos.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_arquivos_retorno.png)

Você pode adicionar o arquivo retorno da conta bancária clicando no ícone <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar, e então você verá a essa tela com as informações para preenchimento, com descrição e o botão para fazer upload do arquivo.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_guia_arquivos_retorno_add.png)