# Como configurar o sistema para emissão de notas fiscais de serviço (NFSe)

A configuração para emissão de NFSe é crucial para evitar erros que possam interromper vendas e gerar problemas com solicitações.

Neste guia, vamos detalhar o procedimento passo a passo para configurar a emissão de notas fiscais no nosso sistema.

{% hint style="danger" %}
**Atenção:** Você precisará de informações importantes para o preenchimento dos dados mostrados aqui. Em caso de dúvidas, recomendamos que solicite essas informações ao contador de sua empresa, que poderá fornecer as orientações corretas e necessárias.
{% endhint %}

## Cadastro da Empresa

Primeiro, é necessário efetuar o cadastro da sua empresa. Essa parte é prática, especialmente para CNPJs. Ao digitar o CNPJ, nosso sistema preenche automaticamente os dados completos da empresa, permitindo que você foque rapidamente na parte fiscal.

Vamos fazer um teste com o CNPJ da Gestão Online. Observe os dados sendo preenchidos automaticamente:

![](/erp-v2/assets/guia_utilizacao/guia_utilizacao_emitir_nfse_campo_cnpj.gif)

## Configuração dos Dados Fiscais

### NFSe ativado

Após o cadastro inicial, você deve preencher os dados fiscais da empresa. As principais informações incluem:

- Se a empresa é optante pelo **Simples Nacional**.
- Indicador de **Inscrição Estadual**.
- Se você é tomador ou prestador de serviço.
- Qual o **Regime Tributário** utilizado.
- Ativar a opção de NFSe ativo (isso habilitará mais opções para você acessar).

![](/erp-v2/assets/guia_utilizacao/guia_utilizacao_emitir_nfse_campos_preenchimento_geral.png)

### Campo NFSe ambiente

Neste campo, você define o ambiente de criação das Notas Fiscais. Existem duas opções:

- **Homologação:** Ambiente de testes sem validade fiscal ou jurídica. Você pode usar dados reais ou fictícios.
- **Produção:** Ambiente designado para documentos com valor fiscal, válidos e reconhecidos fiscalmente.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_ambiente.png)

### Campo NFSe RPS Série

O campo de série utilizada no Recibo Provisório de Serviço (RPS) pode ser composto por números (1, 2, 3, etc.) ou letras (A, S, NFS, etc.). Consulte o município da empresa para obter a série correta antes de iniciar a emissão das NFS-e.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_serie.png)

### Campo NFSe RPS Número

Preencha aqui o número inicial que será utilizado no RPS. Cada RPS gerado possui uma numeração, portanto, informe a sequência correta conforme a prefeitura.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_numero.png)

### Campo NFSe RPS Lote

Alguns municípios utilizam o conceito de lote para emissão de NFS-e. É um controle de quantidade de notas emitidas por CNPJ e deve ser sequencial. Essa informação pode ser verificada no portal da prefeitura.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_lote.png)

### NFSe Prefeitura Login e senha

Esses campos variam de prefeitura para prefeitura. O preenchimento correto permite o acesso automático ao portal para emissão de NFSe.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_login_senha.png)

## NFSe configuração padrão

Ativando esta opção, novos campos ficam disponíveis para preenchimento. Abaixo, veja a definição e o modo de preenchimento de cada um:

### Campo NFSe principal código de serviço

Aqui, você pode adicionar um novo código ou usar os códigos cadastrados na tela [**`LC116`**](/erp-v2/funcionalidades/fiscal/lc116.md). Este campo define o tipo de serviço para a NFSe.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_codigo_servico.png)

### Campo NFSe principal código de tributação

Preencha o código de tributação principal conforme as orientações específicas do seu município.

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