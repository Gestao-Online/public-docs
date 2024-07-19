# 💳 Listar contas

Nesta aba você encontra listadas todas as contas bancárias cadastradas na plataforma da **Gestão Online**. E caso tenha alguma conta faltando. você pode efetuar o cadastro seguindo este manual.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_contas.gif)

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

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

Ao clicar neste botão uma janela será aberta para que você preencha os dados para emitir um relatório. De forma simples, podemos dizer que este relatório de fluxo de caixa é usado por você para acompanhar a situação financeira da sua empresa.

Nesta janela aberta tem alguns campos de preenchimento obrigatório, sendo eles **Conta** e **Tipo**. Conforme marcado na imagem abaixo:

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_contas_btn_fluxo_caixa.png)

Ao clicar no primeiro campo de **Conta** será carregado as contas cadastradas na plataforma. Lembrando que estas são as contas que aparecem nesta aba.

Você pode definir a **data de inicio e fim** dos relatórios que serão exibidos, e o **tipo de arquivo**, que pode ser `PDF` ou `EXCEL` para efeutar o download.

Observe abaixo o exemplo que fizemos, o relatório é mostrado em uma nova aba permitindo o download ou impressão. Nosso relatório é somente para ilustrar, não possui dados de entrada ou saída.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_contas_btn_fluxo_caixa_conta.gif)

## Adicionar nova conta bancária

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar uma nova conta bancária, confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_contas_add.png)

Após clicarmos no botão adicionar nova conta bancária, uma nova página será aberta e nela ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;   
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar rascunho;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_menu.png)

No momento do cadastro de uma nova conta bancária, você precisará preencher alguns campos obrigatórios que têm o asterisco vermelho. Eles são essenciais para o mínimo funcionamento em nosso sistema.

{% hint style="info" %}
**Informativo:** É sempre importante lembrar de fazer o preenchimento completo dos dados da conta bancária. 😉👍
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta.png)

No primeiro campo temos as opções de contas, cada uma mostrará novos campos para você preencher e complementar o cadastro da conta bancária, vejamos cada uma das opções abaixo.

## Conta tipo caixinha

Usado por exemplo para o caixa de uma loja, esta opção exibe somente os campos de **Descrição** e escolha da empresa, as informações bloqueadas de alteração são **Saldo inicial**, **Data Saldo inicial** e **Tipo conciliação**.

Na descrição você pode colocar um nome que facilite a identificação desta conta bancária quando precisa buscá-la para uso.

Já no campo de empresa, o vínculo é feito com a **aba empresas**, e você pode escolher uma empresa cadastrada. E para mais informações sobre a aba Empresas, [**`clique aqui`**](/erp-v2/funcionalidades/parametrizacoes/empresas.md)

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_caixinha.png)

## Conta tipo poupança e Corrente

Além dos campos padrões **Tipo**, **Descrição** e **Empresa**, também fica disponível o campo de **Banco**, **Agência bancária** e **Conta**.

Nestes campos você pode clicar e nossa plataforma fará a busca dos bancos cadastrados, observe o exemplo abaixo:

{% hint style="warning" %}
**Bancos:** Caso queira mais informações sobre como cadastrar novos bancos, [**`clique aqui`**](/erp-v2/funcionalidades/financeiro/bancos.md).
**Agências:** E para mais informações sobre cadastrar agências bancárias, [**`clique aqui`**](/erp-v2/funcionalidades/financeiro/agencia_bancaria.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca.gif)

Na parte final da página, tem o botão **Pagamento Boleto**, podendo ser utilizando em pagamentos do tipo online ou PDV (Ponto De Venda), nisso novos campos serão mostrados para você preencher, temos então as duas opções:

### Dados para geração de transação

Este **Token e/ou Número Convênio** tem uma relação direta e fundamental com a emissão de um boleto bancário, pois ele identifica a empresa ou entidade que está emitindo o boleto dentro do sistema do banco. Cada cedente possui um código único que permite ao banco distinguir entre diferentes empresas que utilizam seus serviços de cobrança.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_convenio.png)

### Dados para geração do boleto

Dos campos para preenchimento você tem, **Nosso Número Sequência**, nele o código do /Convênio é frequentemente utilizado como parte da fórmula para gerar o "Nosso Número", que é o identificador único de cada boleto. A inclusão do código ajuda a garantir que cada "Nosso Número" seja único e rastreável.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_nosso_numero.png)

Logo na sequência tem os campos de **mensagem personalizada** e **Local pagamento**, podem ser utilizadas para explicar sobre multas e juros que serão aplicadas ao boleto, e dar instruções sobre o local de pagamento.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_mensagens.png)

Agora no tipo de multa você tem três opções disponívei, sendo elas, **isento**, **valor em reais** e **valor em percentual**. Ao escolher reais ou percentual, um novo campo será mostrado para você definir o valor:

{% hint style="warning" %}
**Valor Multa:** De acordo com o **Código Tributário Nacional** o valor da multa para boletos não pode passar de 2%.
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_multa.png)

Pode também configurar o juro mora ou moratórios, podendo ser em dinheiro ou porcentagem igual o exemplo da multa que mostramos acima.

{% hint style="warning" %}
**Valor Juro:** Esses juros consistem em uma taxa aplicada sobre o atraso no pagamento de uma conta, sendo possível colocar 1% ao mês no máximo, conforme estabelecido pelo **Código Tributário Nacional**.
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_juro.png)

**Espécie do documento**, as espécies precisam ser usadas de acordo com o tipo de documento que você vai usar para pagar, ou se o banco pedir um tipo específico. Pois garante a segurança e a finalidade do boleto emitido.

Das espécies mais comuns nós temos:

- **DM - Duplicata mercantil:** um título de crédito no qual o comprador se compromete a pagar o valor indicado na fatura dentro de um prazo mínimo de 30 dias.

- **DR - Duplicata Rural:** usada para vendas a prazo de bens agrícolas, extrativos ou pastoris, realizadas diretamente por produtores rurais ou suas cooperativas, também pode ser utilizada como título de crédito.

- **NP - Nota promissória:** é um documento que serve como promessa de pagamento de uma dívida.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_especie.png)

Os últimos dois campos para preenchimento são, os **Dias Limite** para definir a quantidade de dias limite para pagamento após o vencimento do boleto. E o campo **Variação da carteira** que é usado somente pelo Banco do Brasil:

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_poupanca_boleto_dias_variacao.png)

## Conta tipo cartão de crédito

Com a opção tipo **Cartão de Crédito** definida, será solicitado o banco. Lembrando que você pode adicionar um novo banco com o atalho do ícone <img src="/erp-v2/assets/icon_adds.png" alt="" data-size="line">, ou então editar um banco já cadastrado clicando no ícone <img src="/erp-v2/assets/icon_nova_aba.png" alt="" data-size="line">. 

{% hint style="warning" %}
**Bancos:** Caso queira mais informações sobre como cadastrar novos bancos, [**`clique aqui`**](/erp-v2/funcionalidades/financeiro/bancos.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_cc_banco.png)

Já no campo de empresa, o vínculo é feito com a **aba empresas**, e você pode escolher uma empresa cadastrada. E para mais informações sobre a aba Empresas, [**`clique aqui`**](/erp-v2/funcionalidades/parametrizacoes/empresas.md)

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_cc_empresa.png)

Os últimos campos para configurar são os de **Multa percentual** e **Juro percentual** quando o cliente atrasa o pagamento da fatura. O Código de Defesa do Consumidor (CDC) estabelece que essa multa é de 2% ao mês, independentemente do número de dias de atraso. Além disso, também há a cobrança de juros de mora, que não pode ultrapassar 1% ao mês. Assim, a soma da multa por atraso e dos juros de mora pode chegar a 3% ao mês.

![](/erp-v2/assets/funcionalidades/financeiro/aba_listar_add_conta_cc_multa_juro.png)

