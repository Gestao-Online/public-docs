# Como configurar o sistema para emissão de notas fiscais de serviço (NFSe)

A configuração para emissão de NFSe é muito importante e precisa evitar que erros ocorram. Pois isso implica em vendas paradas e problemas em solicitação.

Vejamos agora o procedimento passo a passo para configurar a emissão de notas fiscais no nosso sistema.

{% hint style="danger" %}
**Atenção:** Você precisará de informações importantes para o preenchimento das informações mostradas aqui. Para caso de dúvidas, recomendamos solicitar as informações junto ao contador de sua empresa, pois ele pode fornecer as informações corretas e necessárias.
{% endhint %}

Primeiro será necessário efetuar o cadastro de sua empresa, e esta parte em específico é bem prática em casos de CNPJ, pois nosso sistema, após você digitar o CNPJ, trará os dados completos de sua empresa. Fazendo assim, com que tenhamos foco na parte fiscal mais rápido.

Faremos um teste com o CNPJ da gestão online, observe os dados serem preenchidos automaticamente.

![](/erp-v2/assets/guia_utilizacao/guia_utilizacao_emitir_nfse_campo_cnpj.gif)

## NFSe ativado

Agora o preenchimento dos dados fiscais da empresa. Destas informações, se sua empresa é optante pelo **Simples Nacional**, o indicador de **Inscrição Estadual**, se você é tomador ou prestador de serviço, qual o **Regime Tributário** utilizado, e por último, ativar a opção de NFSe ativo (esta opção fará com que mais opções fiquem disponíveis para você acessar).

![](/erp-v2/assets/guia_utilizacao/guia_utilizacao_emitir_nfse_campos_preenchimento_geral.png)

### Campo NFSe ambiente

Neste campo você vai definir o ambiente de criação das Notas Fiscais. Você terá duas opções para utilização, vejamos a definição de cada uma:

- **Homologação:** É o ambiente de testes sem nenhuma validade fiscal ou jurídica, podendo também usar dados reais ou fictícios no preenchimento do documento.
- **Produção:** É o ambiente designado para documentos com valor fiscal, ou seja, são documentos válidos e reconhecidos fiscal e juridicamente.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_ambiente.png)

### Campo NFSe RPS Série

O campo de série utilizada no recibo provisório de serviço (RPS) pode ser composto por número (1, 2 ou 3, por exemplo) ou letras (A, S, NFS, para o exemplo), varia de acordo com cada prefeitura, portanto, consulte-a com o município da empresa antes de iniciar a emissão das NFS-e.

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