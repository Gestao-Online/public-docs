# ⏩ Tipo de tributação

Nesta aba você encontra todos os tipos de tributação que estão cadastrados na plataforma da **Gestão Online**. Esses tipos definem os cenários de emissão das Notas Fiscais. E caso queira criar, editar ou excluir um tipo existente, precisa somente seguir este manual.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao.gif)

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar novo tipo de tributação.

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros de busca [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md).
{% endhint %}

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse, [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse).
{% endhint %}

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_menu.png)

## Adicionar novo tipo de tributação

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar um novo tipo de tributação. Confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add.png)

Após clicar no botão para adicionar um novo tipo de tributação, uma nova página será aberta e, ao lado direito da tela, é possível visualizar um pequeno menu cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_cadeado.png" alt="" data-size="line"> Restrições/Exceções;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_menu.png)

## Campos obrigatórios

No momento do cadastro de um novo tipo de tributação, você precisará preencher alguns campos obrigatórios que têm o asterisco vermelho. Eles são essenciais para o mínimo funcionamento em nosso sistema.

{% hint style="info" %}
**Informativo:** É sempre importante lembrar de fazer o preenchimento completo dos dados do tipo de tributação. 😉👍
{% endhint %}

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_campos_obrigatorios.png)

O primeiro campo é para inserir o **nome** desse tipo de tributação que estamos criando, e no campo **finalidade**, você define se essas configurações serão válidas para o tipo venda ou compra.

Para nosso exemplo, vamos colocar o nome como padrão e a finalidade vamos utilizar venda. Observe abaixo:

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_campos_nome_finalidade.png)

Como o campo de **observação** não tem preenchimento obrigatório, vamos deixar ele em branco.

Após salvarmos este tipo de tributação, algumas guias passam a ficar disponíveis para preenchimento. Observe abaixo:

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_salvar.gif)

## Guias disponíveis após salvar

Após salvar o novo tipo de tributação, algumas guias ficará disponíveis para você preencher, no primeiro momento estarão todas vazias, mas ao seguir em nosso manual, vamos fazer o preenchimento um a um.

### Guia ICMS

Na guia de ICMS (Imposto sobre Circulação de Mercadorias e Serviços) que é um imposto estadual brasileiro que incide sobre a movimentação de mercadorias e a prestação de serviços de transporte e comunicação. E também um dos principais tributos no Brasil e desempenha um papel crucial na arrecadação de receitas para os Estados e Municípios. 

Nós vamos clicar no ícone <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo item, onde será mostrado os campos de preenchimento com as informações necessárias para salvarmos.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms.png)

O primeiro campo de preenchimento é o do NCM (Nomenclatura Comum do Mercosul), ele precisa já estar configurado para você poder utilizá-lo. Para mais informações sobre a **aba NCM**, [**`clique aqui`**](/erp-v2/funcionalidades/fiscal/ncm.md).

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campo_ncm.gif)

Em sequência temos o campo CFOP (Código Fiscal de Operações e Prestações), ele precisa já estar configurado para você poder utilizá-lo. Para mais informações sobre a **aba CFOP**, [**`clique aqui`**](/erp-v2/funcionalidades/fiscal/cfop.md).

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campo_cfop.gif)

No campos de **estados**, você precisa clicar para quais estados serão válidos esta configuração. Em nosso exemplo, vamos marcar todos os estados, menos o do Goiás, pois essa configuração será para o tipo interestadual. Depois faremos um só com o estado de Goiás.

Lembrando que essa configuração que fizemos é valida para outros estados. Pois cada um possui uma configuração diferente a ser seguida.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campo_estados.gif)

Agora no campo **Tipo de Situação Tributária** nós temos duas opções de escolha, o primeiro é o CST (Código de Situação Tributária) que é um código utilizado na legislação tributária brasileira para identificar a situação tributária de um produto ou serviço em relação ao ICMS, e temos o CSON (Código de Situação da Operação de Nota Fiscal) é um código utilizado no Brasil para indicar a situação tributária específica de uma operação registrada em uma Nota Fiscal Eletrônica (NF-e).

Para nosso exemplo de cadastro interestadual iremos marcar a opçõa do CSON, e vamos marcar no campo ao lado de **Situação Tributária** a opção 101 - Tributada com permissão de crédito. Existem outras opções, mas isso depende da ocasião. Observe abaixo:

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campos_situacao_tributaria.png)

Em **Modalidade da Base de Cálculo** iremos escolher a opção valor da operação, e definir a alíquota como 18,00%. Isso em sequência no campo **Origem da Mercadoria** nós vamos marcar primeira opção Nacional, exceto as indicadas nos códigos 3, 4, 5 e 8.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campos_modalidade_aliquota.png)

Os demais campos não iremos fazer o preenchimento para este exemplo. Porém, se você observar, no final da página tem mais campos com opções caso seja necessário em alguma ocasião. Observe abaixo as opções disponíveis.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campos_tipo_situacao_tributaria.png)

Após tudo preenchido, vamos agora salvar esta configuração de ICMS para usarmos. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_salvar.gif)

Criamos também uma configuração única somente para o estado de Goiás, lembrando mais uma vez é somente para ilustrar que pode ser feito de maneira separada a configuração de cada estado. Como pode observar abaixo, agora temmos duas configurações para ICMS, uma para insterestadual e outra estadual. 😁👍

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_itens.png)

### Guia IPI

Na guia de IPI (Imposto sobre Produtos Industrializados) que é um imposto federal brasileiro que incide sobre a produção e a importação de produtos industrializados. 

Nós vamos clicar no ícone <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo item, onde será mostrado os campos de preenchimento com as informações necessárias para salvarmos.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi.png)

O primeiro campo de preenchimento é de **Origem da Mercadoria**. As informações já estão pré-definidas, você precisa apenas escolher a que melhor se aplica para o seu caso.

E nosso exemplo vamos marcar a primeira opção. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_origem.png)

No segundo campo, temos a Situação Tributária (CST). Em nossa exemplo marcaremos a opção **50 - Saída Tributada**, essa situação "50" indica que a operação está com o imposto suspenso. Isso significa que, temporariamente, o ICMS não é cobrado na saída do produto ou serviço, mas poderá ser cobrado em uma etapa posterior. 

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_situacao_tributaria.png)

No campo de **Código de enquadramento** nós deixaremos em branco. Mas saiba que os códigos de enquadramento do IPI são diversos e atendem a diferentes situações previstas na legislação.

Agora no campo de **Alíquota** coloraremos o valor de 11,00% para este nosso exemplo. E o campo **Base de cálculo** nós deixaremos também com valores zerados.

E no **Tipo de Cálculo IPI** ficará com a opção de "base cálculo X alíquota", onde a base de cálculo é o valor do produto industrializado e a alíquota é um percentual aplicado sobre a base de cálculo para determinar o valor do imposto a ser pago.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_aliquota_calculo.png)

Após tudo preenchido, vamos agora salvar esta configuração de IPI para usarmos. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_salvar.gif)

Ainda na guia de IPI, você pode adicionar excessões caso haja, você tem um pequeno menu recolhível que trás uma opção a mais para você.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_excessao.png)

### Guia PIS

Na guia de PIS (Programa de Integração Social) que é uma contribuição social brasileira que incide sobre o faturamento das empresas e tem como objetivo financiar o seguro-desemprego, abono salarial e outras despesas do Programa de Integração Social.

Nós vamos clicar no ícone <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo item, onde será mostrado os campos de preenchimento com as informações necessárias para salvarmos.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis.png)

O primeiro campo de preenchimento é de **Origem da Mercadoria**. As informações já estão pré-definidas, você precisa apenas escolher a que melhor se aplica para o seu caso.

E nosso exemplo vamos marcar a primeira opção. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_origem.png)

No segundo campo, temos a Situação Tributária (CST). Em nossa exemplo marcaremos a opção **01 - Operação tributável com alíquota básica**, o código "01" é usado quando a mercadoria está sujeita à tributação normal do ICMS, sem qualquer tipo de isenção, redução de base de cálculo, ou substituição tributária.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_situacao_tributaria.png)

Agora no campo de **Alíquota** coloraremos o valor de 11,00% para este nosso exemplo. E o campo **Base de cálculo** e **Redução na Base de Cálculo** nós deixaremos com valores zerados.

E no campo **Tipo de Cálculo IPI** ficará com a opção de "base cálculo X alíquota", onde a base de cálculo é o valor do produto industrializado e a alíquota é um percentual aplicado sobre a base de cálculo para determinar o valor do imposto a ser pago.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_aliquota_calculo.png)

Após tudo preenchido, vamos agora salvar esta configuração de PIS para usarmos. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_salvar.gif)

Continuando na guia de PIS, você pode adicionar excessões caso haja, você tem um pequeno menu recolhível que trás uma opção a mais para você.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_excessao.png)

### Guia COFINS

Na guia de COFINS (Contribuição para o Financiamento da Seguridade Social) que é um imposto federal brasileiro que incide sobre o faturamento das empresas. E tem como principal objetivo financiar a seguridade social, que abrange a previdência social, a saúde e a assistência social.

Nós vamos clicar no ícone <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo item, onde será mostrado os campos de preenchimento com as informações necessárias para salvarmos.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins.png)

O primeiro campo de preenchimento é de **Origem da Mercadoria**. As informações já estão pré-definidas, você precisa apenas escolher a que melhor se aplica para o seu caso.

E nosso exemplo vamos marcar a primeira opção. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_origem.png)

No segundo campo, temos a Situação Tributária (CST). Em nossa exemplo marcaremos a opção **01 - Operação tributável com alíquota básica**, o código "01" é usado quando a mercadoria está sujeita à tributação normal do ICMS, sem qualquer tipo de isenção, redução de base de cálculo, ou substituição tributária.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_situacao_tributaria.png)

Agora no campo de **Alíquota** coloraremos o valor de 11,00% para este nosso exemplo. E o campo **Base de cálculo** e **Redução na Base de Cálculo** nós deixaremos com valores zerados.

E no campo **Tipo de Cálculo IPI** ficará com a opção de "base cálculo X alíquota", onde a base de cálculo é o valor do produto industrializado e a alíquota é um percentual aplicado sobre a base de cálculo para determinar o valor do imposto a ser pago.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_aliquota_calculo.png)

Após tudo preenchido, vamos agora salvar esta configuração de COFINS para usarmos. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_salvar.gif)

Continuando na guia de COFINS, você pode adicionar excessões caso haja, você tem um pequeno menu recolhível que trás uma opção a mais para você.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_excessao.png)

