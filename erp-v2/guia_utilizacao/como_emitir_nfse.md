# Como configurar o sistema para emissão de notas fiscais de serviço (NFSe)

<!-- CONFIRMAR MAIS INFORMAÇÕES COM O PAULO SOBRE ESSAS CONFIGURAÇÕES, POIS NÃO CONSEGUI EFETUAR UM TESTE DE HOMOLOGAÇÃO COM UMA NFSe, ACREDITO QUE FALTA ALGUM ITEM, OU ALGUMA CONFIGURAÇÃO QUE FIZ ERRADO. -->

A configuração para emissão de NFSe é muito importante e precisa evitar que erros ocorram. Pois isso implica em vendas paradas e problemas em solicitação.

Vejamos agora o procedimento passo a passo para configurar a emissão de notas fiscais no nosso sistema.

{% hint style="danger" %}
**Atenção:** Você precisará de informações importantes para o preenchimento das informações mostradas aqui. Para caso de dúvidas, recomendamos solicitar as informações junto ao contador de sua empresa, pois ele pode fornecer as informações corretas e necessárias.
{% endhint %}

Primeiro será necessário efetuar o cadastro de sua empresa, e esta parte em específico é bem prática em casos de CNPJ, pois nosso sistema, após você digitar o CNPJ, trará os dados completos de sua empresa. Fazendo assim, com que tenhamos foco na parte fiscal mais rápido.

Faremos um teste com o CNPJ da gestão online, observe os dados serem preenchidos automaticamente.

![](/erp-v2/assets/guia_utilizacao/guia_utilizacao_emitir_nfse_campo_cnpj.gif)

## NFSe ativado

Agora o preenchimentos dos dados fiscais da empresa. Destas informações se sua empresa é optante pelo **Simples Nacional**, o indicador de **Inscrição Estadual**, se você é tomador ou prestador serviço, qual o **Regime Tributário** utilizado, e por último ativar a opção de NFSe ativo (Esta opção fará com que mais opções fiquem disponíveis para você acessar).

![](/erp-v2/assets/guia_utilizacao/guia_utilizacao_emitir_nfse_campos_preenchimento_geral.png)

### Campo NFSe ambiente

Neste campo você vai definir o ambiente de criação das Notas Fiscais. Você terá duas opções para utilização, vejamos a definição de cada uma:

- **Homologação:** É o ambiente de testes sem nenhuma validade fiscal ou jurídica, podendo também usar dados reais ou fictícios no preenchimento do documento.
- **Produção:** É o ambiente designado para documentos com valor fiscal, ou seja, são documentos válidos e reconhecidos fiscal e juridicamente.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_ambiente.png)

### Campo NFSe RPS Série

O campo de série utilizada no recibo provisório de serviço (RPS), pode composto por número (1, 2 ou 3, por exemplo) ou letras (A, S, NFS, pro exemplo), varia de acordo com cada prefeitura, portanto, consulte-a com o município da empresa antes de iniciar a emissão das NFS-e.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_serie.png)

### Campo NFSe RPS Número

Neste campo você preenche o número inicial que será utilizado no recibo provisório de serviço (RPS). Cada RPS gerado possui uma numeração, por isso, ao configurar a emissão de NFS-e, é importante que a numeração do RPS seja informada de acordo com a sequência da sua prefeitura.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_numero.png)

### Campo NFSe RPS Lote

Alguns municípios utilizam o conceito de lote para emissão de NFS-e. Ele nada mais é que um controle de quantidade de notas que foram emitidas por CNPJ e deve ser sequencial. Lembrando que essa informação também é encontrada no portal da prefeitura da empresa que está sendo cadastrada no momento.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_lote.png)

### NFSe Prefeitura Login e senha

Esses campos tem variação de prefeitura para prefeitura. Mas com o preenchimento destes campos o acesso ao portal pode ser feito automaticamente, para emissão de NFSe.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_login_senha.png)

## NFSe configuração padrão

Quando você ativa esta opção, novos campos ficam disponíveis para você preencher. Vejamos a definição e modo de preenchimento de cada um dos campos logo abaixo.

### Campo NFSe principal código de serviço

Neste campo, você pode adicionar um novo código ou usar os códigos cadastrados na tela [**`LC116`**](/erp-v2/funcionalidades/fiscal/lc116.md). Através deste campo você define o tipo de serviço para esta NFSe.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_codigo_servico.png)

### Campo NFSe principal código de tributação

asdfasdfasdfas

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_codigo_tributacao.png)

### Campo NFSe principal CNAE

O código CNAE ou, por extenso, Classificação Nacional de Atividades Econômicas, é uma forma de padronizar, em todo o território nacional, os códigos de atividades econômicas e os critérios de enquadramento usados pelos mais diversos órgãos da administração tributária do Brasil.

Cada município possui sua própria lista de códigos, por isso confira corretamente o código antes de fazer o preenchimento.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_codigo_cnae.png)

### NFSe principal ISS tipo tributação

O Imposto sobre Serviços de Qualquer Natureza (ISSQN) é a mesma coisa que o Imposto Sobre Serviços (ISS). É um tributo de competência municipal, regulamentado pela Lei Complementar nº 116/2003 e incide sobre cada prestação de serviço com uma alíquota entre 2% e 5%, dependendo do tipo de serviço prestado e conforme taxado pelo município. 

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_iss_tipo_tributacao.png)

### NFSe principal ISS Exigibilidade

Neste campo você tem algumas opções disponíveis, dentre elas estão:

- **Exigível:** Serviço prestado está sujeito à tributação pelo ISS e que o imposto deve ser pago dentro do prazo estabelecido pela legislação municipal
- **Não incidência:** Serviços que não estão sujeitos à cobrança do ISS de acordo com a legislação.
- **Isenção:** Serviço prestado está sujeito ao ISS, mas há uma disposição legal específica que isenta o contribuinte do pagamento do imposto.
- **Exportação:** Aplica-se a serviços prestados para clientes no exterior.
- **Imunidade:** Certas entidades, como templos de qualquer culto, partidos políticos, sindicatos de trabalhadores e instituições de educação e assistência social sem fins lucrativos, podem ser imunes ao ISS.
- **Suspenso por ação judicial:** Situações em que há uma ação judicial em andamento questionando a exigibilidade do ISS. Durante o período de suspensão, o pagamento do imposto é temporariamente interrompido até que haja uma decisão final do judiciário.
- **Suspenso por ação administrativa:** Suspensa devido a um processo administrativo, como um recurso ou pedido de revisão protocolado junto à administração tributária municipal. Até que haja uma decisão administrativa, o pagamento do imposto é suspenso.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_iss_exigibilidade.png)

### NFSe principal ISS Alíquota

 O valor da alíquota do ISS (Imposto Sobre Serviços) varia de acordo com o tipo de serviço prestado, conforme estabelecido na legislação local. Geralmente variam de 2% a 5%, dependendo da natureza do serviço​​. 
 
 É importante verificar a legislação específica ou consultar a Secretaria de Finanças do município para obter informações detalhadas sobre a alíquota aplicável ao seu caso específico.

 ![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_iss_aliquota.png)

### NFSe principal valor base cálculo

A base de cálculo do ISS é determinada conforme o valor total dos serviços prestados, podendo ser ajustada por fatores como **Descontos Incondicionais** (Reduções aplicadas diretamente no valor do serviço antes da emissão da NFS-e). E **Deduções Permitidas** (Alguns municípios permitem deduzir determinados valores, como materiais fornecidos pelo prestador de serviços ou subcontratações).

 ![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_iss_base_calculo.png)

### NFSe principal valor deduções

O valor percentual de deduções, refere-se aos montantes que podem ser subtraídos do valor total da prestação de serviços antes do cálculo do ISS (Imposto Sobre Serviços). As deduções são permitidas em situações específicas, conforme a legislação municipal. As mais comuns são:

- **Descontos Incondicionais:** Aplicado diretamente sobre o valor do serviço na hora da contratação, e que não estão condicionados a nenhum evento futuro. Esses descontos são subtraídos do valor total antes do cálculo do ISS.

- **Materiais Fornecidos:** Em alguns casos, os materiais fornecidos pelo prestador de serviços incorporados na prestação do serviço podem ser deduzidos da base de cálculo do ISS.

- **Subcontratações:** Valores pagos a terceiros subcontratados para a execução de parte do serviço, podem ser deduzidos da base de cálculo, conforme a legislação permitir.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_deducoes.png)

## Configurando Tipo de tributação

Outra parte importante para o preechimento dos dados é na tela de **Tipo de tributação**, aqui você precisará cadastrar um tipo de tributação do zero. Essas informações serão utilizadas e ativadas a depender da configuração ativa no **Tipo de movimentação**.

O primeiro campo é para inserir o **nome** desse tipo de tributação que estamos criando, e no campo **finalidade**, você define se essas configurações serão válidas para o tipo venda ou compra.

Para nosso exemplo, colocaremos o nome como padrão e, para finalidade, utilizaremos a venda. Observe abaixo:

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_campos_nome_finalidade.png)

Como o campo de **observação** não tem preenchimento obrigatório, deixaremos ele em branco.

Após salvarmos este tipo de tributação, algumas guias passam a ficar disponíveis para preenchimento. Observe abaixo:

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_salvar.gif)

## Abas disponíveis após salvar

Após salvar o novo tipo de tributação, algumas guias ficarão disponíveis para você preencher. No primeiro momento, estarão todas vazias, mas, ao seguir em nosso manual, faremos o preenchimento um a um.

### Aba ICMS

Na guia de ICMS (Imposto sobre Circulação de Mercadorias e Serviços), é um imposto estadual brasileiro que incide sobre a movimentação de mercadorias e a prestação de serviços de transporte e comunicação. É também um dos principais tributos no Brasil e desempenha um papel crucial na arrecadação de receitas para os Estados e Municípios.

Clicaremos no ícone <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo item, que mostrará os campos de preenchimento com as informações necessárias para salvarmos.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms.png)

O primeiro campo de preenchimento é o do NCM (Nomenclatura Comum do Mercosul), ele precisa já estar configurado para você poder utilizá-lo. Para mais informações sobre a **Tela  NCM**, [**`clique aqui`**](/erp-v2/funcionalidades/fiscal/ncm.md).

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campo_ncm.gif)

Em sequência temos o campo CFOP (Código Fiscal de Operações e Prestações), ele precisa já estar configurado para você poder utilizá-lo. Para mais informações sobre a **Tela  CFOP**, [**`clique aqui`**](/erp-v2/funcionalidades/fiscal/cfop.md).

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campo_cfop.gif)

No campo de **estados**, você precisa clicar para quais estados serão válidos esta configuração. Em nosso exemplo, marcaremos todos os estados, menos o de Goiás, pois essa configuração será para o tipo interestadual. Depois faremos um só com o estado de Goiás.

Lembrando que essa configuração que fizemos é valida para outros estados. Pois cada um possui uma configuração diferente a ser seguida.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campo_estados.gif)

Agora, no campo **Tipo de Situação Tributária**, temos duas opções de escolha. A primeira é o CST (Código de Situação Tributária), sendo um código usado na legislação tributária brasileira para identificar a situação tributária de um produto ou serviço em relação ao ICMS. A segunda é o CSON (Código de Situação da Operação de Nota Fiscal), o qual é um código usado no Brasil para indicar a situação tributária específica de uma operação registrada em uma Nota Fiscal Eletrônica (NF-e).

Para nosso exemplo de cadastro interestadual, iremos marcar a opção do CSON e vamos marcar no campo ao lado de **Situação Tributária** a opção 101 - Tributada com permissão de crédito. Existem outras opções, mas isso depende da ocasião. Observe abaixo:

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campos_situacao_tributaria.png)

Em **Modalidade da Base de Cálculo**, escolhemos a opção valor da operação e definimos a alíquota como 18,00%. Isso em sequência, no campo **Origem da Mercadoria**, nós marcamos a primeira opção Nacional, exceto as indicadas nos códigos 3, 4, 5 e 8.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campos_modalidade_aliquota.png)

Os demais campos não farão o preenchimento para este exemplo. Porém, se você observar, no final da página há mais campos com opções caso seja necessário em alguma ocasião. Observe abaixo as opções disponíveis.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_campos_tipo_situacao_tributaria.png)

Após tudo preenchido, vamos agora salvar esta configuração de ICMS para usarmos. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_salvar.gif)

Criamos também uma configuração única somente para o estado de Goiás, lembrando mais uma vez que é somente para ilustrar que pode ser feita de maneira separada a configuração de cada estado. Como pode observar abaixo, agora temos duas configurações para ICMS, uma para interestadual e outra estadual. 😁👍

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_icms_itens.png)

### Aba IPI

Na guia de IPI (Imposto sobre Produtos Industrializados), é um imposto federal brasileiro que incide sobre a produção e a importação de produtos industrializados.

Clicaremos no ícone <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo item, onde serão mostrados os campos de preenchimento com as informações necessárias para salvarmos.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi.png)

O primeiro campo de preenchimento é de **Origem da Mercadoria**. As informações já estão pré-definidas, você precisa apenas escolher a que melhor se aplica para o seu caso.

E nosso exemplo, marcaremos a primeira opção. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_origem.png)

No segundo campo, temos a Situação Tributária (CST). Em nosso exemplo, marcaremos a opção **50 - Saída Tributada**, essa situação "50" indica que a operação está com o imposto suspenso. Isso significa que, temporariamente, o ICMS não é cobrado na saída do produto ou serviço, mas poderá ser cobrado em uma etapa posterior.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_situacao_tributaria.png)

No campo de **Código de enquadramento**, deixaremos em branco. Mas saiba que os códigos de enquadramento do IPI são diversos e atendem a diferentes situações previstas na legislação.

Agora, no campo de **Alíquota**, coloraremos o valor de 11,00% para este nosso exemplo. E o campo **Base de cálculo** deixaremos também com valores zerados.

No **Tipo de Cálculo IPI** ficará com a opção de "base cálculo X alíquota", onde a base de cálculo é o valor do produto industrializado e a alíquota é um percentual aplicado sobre a base de cálculo para determinar o valor do imposto a ser pago.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_aliquota_calculo.png)

Após tudo preenchido, vamos agora salvar esta configuração de IPI para usarmos. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_salvar.gif)

Ainda na guia de IPI, você pode adicionar exceções. Caso haja, você tem um pequeno menu recolhido que traz uma opção a mais para você.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_ipi_excessao.png)

### Aba PIS

Na guia de PIS (Programa de Integração Social), sendo uma contribuição social brasileira que incide sobre o faturamento das empresas e planeja financiar o seguro-desemprego, abono salarial e outras despesas do Programa de Integração Social.

Clicaremos no ícone <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo item, onde serão mostrados os campos de preenchimento com as informações necessárias para salvarmos.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis.png)

O primeiro campo de preenchimento é de **Origem da Mercadoria**. As informações já estão pré-definidas, você precisa apenas escolher a que melhor se aplica para o seu caso.

E nosso exemplo, marcaremos a primeira opção. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_origem.png)

No segundo campo, temos a Situação Tributária (CST). Em nosso exemplo, marcaremos a opção **01 - Operação tributável com alíquota básica**. O código "01" é usado quando a mercadoria está sujeita à tributação normal do ICMS, sem qualquer tipo de isenção, redução de base de cálculo ou substituição tributária.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_situacao_tributaria.png)

Agora, no campo de **Alíquota**, coloraremos o valor de 11,00% para este nosso exemplo. E o campo **Base de cálculo** e **Redução na Base de Cálculo** deixaremos com valores zerados.

No campo **Tipo de Cálculo IPI** ficará com a opção de "base cálculo X alíquota", onde a base de cálculo é o valor do produto industrializado e a alíquota é um percentual aplicado sobre a base de cálculo para determinar o valor do imposto a ser pago.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_aliquota_calculo.png)

Após tudo preenchido, vamos agora salvar esta configuração de PIS para usarmos. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_salvar.gif)

Continuando na guia de PIS, você pode adicionar exceções caso haja. Você tem um pequeno menu recolhido que traz uma opção a mais para você.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_pis_excessao.png)

### Aba COFINS

Na guia de COFINS (Contribuição para o Financiamento da Seguridade Social) que é um imposto federal brasileiro que incide sobre o faturamento das empresas. E tem como principal objetivo financiar a seguridade social, que abrange a previdência social, a saúde e a assistência social.

Clicaremos no ícone <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo item, onde serão mostrados os campos de preenchimento com as informações necessárias para salvarmos.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins.png)

O primeiro campo de preenchimento é de **Origem da Mercadoria**. As informações já estão pré-definidas, você precisa apenas escolher a que melhor se aplica para o seu caso.

Em nosso exemplo, marcaremos a primeira opção. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_origem.png)

No segundo campo, temos a Situação Tributária (CST). Em nosso exemplo, marcaremos a opção **01 - Operação tributável com alíquota básica**. O código "01" é usado quando a mercadoria está sujeita à tributação normal do ICMS, sem qualquer tipo de isenção, redução de base de cálculo ou substituição tributária.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_situacao_tributaria.png)

Agora, no campo de **Alíquota**, coloraremos o valor de 11,00% para este nosso exemplo. E o campo **Base de cálculo** e **Redução na Base de Cálculo** deixaremos com valores zerados.

E no campo **Tipo de Cálculo IPI** ficará com a opção de "base cálculo X alíquota", onde a base de cálculo é o valor do produto industrializado e a alíquota é um percentual aplicado sobre a base de cálculo para determinar o valor do imposto a ser pago.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_aliquota_calculo.png)

Após tudo preenchido, vamos agora salvar esta configuração de COFINS para usarmos. Observe abaixo.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_salvar.gif)

Continuando na guia de COFINS, você pode adicionar exceções caso haja. Você tem um pequeno menu recolhido que traz uma opção a mais para você.

![](/erp-v2/assets/funcionalidades/fiscal/aba_tipo_tributacao_add_guia_cofins_excessao.png)