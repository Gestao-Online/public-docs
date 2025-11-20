# Como configurar o sistema para emissão de notas fiscais de serviço (NFSe)

A configuração para emissão de NFSe é crucial para evitar erros que possam interromper vendas e gerar problemas com solicitações.

Este guia detalha o procedimento passo a passo para configurar a emissão de notas fiscais no sistema.

{% hint style="danger" %}
**Atenção:** Informações importantes são necessárias para o preenchimento dos dados mostrados aqui. Em caso de dúvidas, solicite essas informações ao contador de sua empresa, que poderá fornecer as orientações corretas e necessárias.
{% endhint %}

## Cadastro da Empresa

Primeiro, efetue o cadastro da sua empresa. Essa parte é prática, especialmente para CNPJ. Ao digitar o CNPJ, o sistema preenche automaticamente os dados completos da empresa, permitindo que o foco seja rapidamente na parte fiscal.

Veja um teste com o CNPJ da Gestão Online. Observe os dados preenchidos automaticamente:

![](/erp-v2/assets/guia_utilizacao/guia_utilizacao_emitir_nfse_campo_cnpj.gif)

## Configuração dos Dados Fiscais

### Anexar certificado Digital

Nos dados fiscais, adicione o certificado digital da empresa, permitindo assinar documentos com validade jurídica e fazer transações online com segurança.

{% hint style="warning" %}
**Importante:** Os certificados digitais são aceitos em **`.pfx`** ou **`.p12`**.
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_certificado.png)

### NFSe ativado

Após o cadastro inicial, preencha os dados fiscais da empresa. As principais informações incluem:

- Se a empresa é optante pelo **Simples Nacional**.
- Indicador de **Inscrição Estadual**.
- Se é tomador ou prestador de serviço.
- Qual o **Regime Tributário** utilizado.
- Ativar a opção NFSe ativo (isso habilitará mais opções).

![](/erp-v2/assets/guia_utilizacao/guia_utilizacao_emitir_nfse_campos_preenchimento_geral.png)

### Campo NFSe ambiente

Neste campo, defina o ambiente de criação das notas fiscais. Existem duas opções:

- **Homologação:** Ambiente de testes sem validade fiscal ou jurídica. É possível usar dados reais ou fictícios.
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

Adicione um novo código ou use os códigos cadastrados na tela [**`LC116`**](/erp-v2/funcionalidades/fiscal/lc116.md). Este campo define o tipo de serviço para a NFSe.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_codigo_servico.png)

### Campo NFSe principal código de tributação

Preencha o código de tributação principal conforme as orientações específicas do seu município.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_codigo_tributacao.png)

### Campo NFSe principal CNAE

O código CNAE (Classificação Nacional de Atividades Econômicas) padroniza os códigos de atividades econômicas no Brasil. Verifique o código específico do seu município antes de preencher.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_codigo_cnae.png)

### NFSe principal ISS tipo tributação

O ISSQN (Imposto sobre Serviços de Qualquer Natureza) é um tributo de competência municipal, regulamentado pela Lei Complementar nº 116/2003. A alíquota varia entre 2% e 5%, dependendo do serviço e do município.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_iss_tipo_tributacao.png)

### NFSe principal ISS Exigibilidade

Este campo oferece várias opções, como:

- **Exigível:** O serviço prestado está sujeito ao ISS, e o imposto deve ser pago dentro do prazo.
- **Não Incidência:** Serviços que não estão sujeitos ao ISS.
- **Isenção:** Serviços isentos do ISS por disposição legal.
- **Exportação:** Aplicável a serviços prestados a clientes no exterior.
- **Imunidade:** Certas entidades, como templos religiosos e partidos políticos, podem ser imunes ao ISS.
- **Suspenso por Ação Judicial:** Suspensão temporária devido à ação judicial.
- **Suspenso por Ação Administrativa:** Suspensão temporária devido a processo administrativo.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_iss_exigibilidade.png)

### NFSe principal ISS Alíquota

A alíquota do ISS varia entre 2% e 5%, dependendo do serviço prestado. Verifique a legislação local ou consulte a Secretaria de Finanças do município para obter informações detalhadas.

 ![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_iss_aliquota.png)

### NFSe principal valor base cálculo

A base de cálculo do ISS é o valor total dos serviços prestados, ajustado por fatores como **Descontos Incondicionais** e **Deduções Permitidas**. Verifique as regras específicas do seu município.

 ![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_iss_base_calculo.png)

### NFSe principal valor deduções

As deduções referem-se aos valores que podem ser subtraídos antes do cálculo do ISS. Exemplos comuns incluem:

- **Descontos Incondicionais:** Aplicados diretamente no valor do serviço.
- **Materiais Fornecidos:** Materiais fornecidos pelo prestador podem ser deduzidos.
- **Subcontratações:** Valores pagos a terceiros subcontratados podem ser deduzidos, conforme a legislação.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_campo_deducoes.png)