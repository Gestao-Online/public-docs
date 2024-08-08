# 🏨 Empresas

Aqui você tem a visão de todos as empresas cadastradas na plataforma **Gestão Online**, podendo cadastrar uma nova empresa, editar informações existentes e até excluir uma empresa cadastrada.

Estas empresas serão utilizadas em cadastro de estoques, lojas e vínculos com produtos e serviços.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas.gif)

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Empresa.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_menu.png)

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Adicionar nova empresa

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar nova empresa, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add.png)

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_menu.png)

No momento do cadastro de uma nova empresa, você precisará preencher alguns campos obrigatórios que tem o asterisco vermelho. 

Sendo eles CNPJ, nome fantasia e razão social, estes itens são o mínimo necessário para poder salvar uma nova empresa.

{% hint style="info" %}
**Informativo:** Mas é sempre importante lembrar de fazer o preenchimento completo dos dados de cada empresa. 😉👍
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa.png)

Você pode adicionar uma imagem para empresa, facilitando assim a identificação da mesma em buscas e relatórios. Confira abaixo como adicionar:

{% hint style="warning" %}
**Importante:** A foto de perfil precisa ter um dos seguintes formatos, PNG, JPEG ou SVG. O tamanho também tem um limite que é de apenas 5MB! 🖼️
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_imagem.gif)

Outro item importante no momento de salvar uma nova empresa é o número de celular, pois pode ser utilizado para hiperlinks do WhatsApp, Telegram e outros mensageiros.

Logo abaixo, você tem os dados de endereço da empresa, com o sistema de autocompletar a partir do momento que preencher o CEP, depois é só preencher o número, caso tenha e o complemento do local se for necessário 😁

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_endereco.gif)

## Dados Fiscais da empresa

Chegando ao final da página de cadastro da nova empresa, nos deparamos com os dados fiscais. Lembre-se em caso de dúvidas, preencha-os conforme a orientação do contador da empresa.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_fiscais.png)

### Anexar certificado Digital

Nos dados fiscais você pode adicionar o certificado digital da empresa, permitindo assinar documentos com validade jurídica e fazer transações online com segurança.

{% hint style="warning" %}
**Importante:** Os certificados digitais são aceitos em **`.pfx`** ou **`.p12`**.
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_certificado.png)

### Optante pelo Simples

Este campo serve para definir se sua empresa ou a empresa que está sendo cadastrada não é optante pelo Simples nacional que é um regime compartilhado de arrecadação, cobrança e fiscalização de tributos aplicável às Microempresas e Empresas de Pequeno Porte.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_campo_optante.png)

### NFe indicador de IE

No campo de indicador de IE (Inscrição Estadual), é essencial para se referir ao pagamento de ICMS. São três opções para escolher:

- **Contribuinte do ICMS:** Quando o destinatário da nota fiscal é um contribuinte de ICMS, é necessário preencher a sua inscrição estadual. Esse contribuinte pode ser tanto uma pessoa física quanto jurídica, embora seja mais comum que seja uma pessoa jurídica.

- **Contribuinte isento:** O contribuinte isento realiza atividades sujeitas ao ICMS, mas não possui inscrição estadual por estar dispensado ou proibido. Não é possível emitir uma NF-e para um destinatário isento com o campo de inscrição estadual preenchido. Em alguns estados, como Amazonas, Bahia, Ceará, Goiás, Mato Grosso, Mato Grosso do Sul, Minas Gerais, Pernambuco, Rio Grande do Norte e Sergipe, não existem contribuintes isentos; nesses casos, se a pessoa não possui inscrição estadual, ela é considerada não contribuinte.

- **Não contribuinte de ICMS:** O não contribuinte de ICMS, geralmente é o destinatário que não possui inscrição estadual, pois é desobrigado e não contribui com o ICMS. Isso é comum entre prestadores de serviços. Embora raro, alguns não contribuintes possuem inscrição estadual devido a exigências burocráticas em certos estados. Um exemplo são as construtoras, que em alguns estados têm inscrição estadual, mas não contribuem com o ICMS.

Escolha a opção que define o cadastro da empresa:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_campo_indicador.png)

### Incentivador Cultural

Uma empresa com a opção "Incentivador cultural" ativa é aquela que participa de programas de incentivo cultural, financiando ou patrocinando projetos culturais. Essas empresas podem receber benefícios fiscais, como deduções no imposto de renda, por apoiar iniciativas artísticas e culturais, promovendo o desenvolvimento e a diversidade cultural na sociedade.

Então, caso essa nova empresa se aplique, deixe esta opção ativada.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_campo_incentivador_cultural.png)

### Incentivo Fiscal

Os incentivos fiscais basicamente são opções dadas pelo governo como parte de sua política de desenvolvimento econômico, visando estimular e apoiar determinados setores ou atividades econômicas, incluindo pequenas e médias empresas (PMEs).

Se a empresa que está cadastrando possuir algum incentivo fiscal, marque esta opção.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_campo_incentivo_fiscal.png)

### Cidade prestação do serviço

Aqui você terá duas opções para escolher, sendo **Tomador** (quem contrata o serviço). Isso pode acontecer em situações onde a legislação municipal ou um acordo entre as partes designa o tomador como responsável pelo pagamento do imposto. Ou escolher a opção **Prestador** (quem realiza o serviço). Esse é o caso mais comum, onde o prestador inclui o valor do imposto na nota fiscal e recolhe o ISS ao município onde está registrado.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_campo_prestacao_servico.png)

### Regime Tributário

No **Regime Tributário** você terá as opções, simples nacional, simples nacional - excesso, normal - lucro presumido, normal - lucro real ou nenhum. Pois define as regras e métodos para o cálculo dos impostos que a empresa deve pagar, baseados em sua receita, lucro e tipo de atividade. Essa carga tributária é o conjunto de todos os impostos que uma empresa deve pagar ao governo, seja do município, do estado ou do país. 

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_campo_regime_tributario.png)

### Regime tributário especial

Após definir o tipo de tributo, coloque qual classificação a empresa se encaixa, entre Microempresa municipal, estimativa, sociedade de profissionais, cooperativa, microempresário individual - MEI, microempresa ou pequeno porte - ME EPP, ou então sem o regime tributário especial.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_campo_regime_tributario_especial.png)

## NFSe ativo

Com a função *nota fiscal de serviço eletronico* ativa, novos campos são liberados para preenchimento logo abaixo na página. Estes dados são para que a emissão das notas fiscais funionem perfeitamente, pois os itens solicitados são necessários para a comunicação do nosso sistema com o emissor de NF.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfse_ativo.png)

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

## NFe Ativo

Com a função *nota fiscal eletronica* ativa, novos campos são liberados para preenchimento logo abaixo na página. Estes dados são para que a emissão das notas fiscais funionem perfeitamente, pois os itens solicitados são necessários para a comunicação do nosso sistema com o emissor de NF.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfe_ativo.png)

### Campo NFe ambiente

Neste campo você vai definir o ambiente de criação das Notas Fiscais Eletrônicas. Você terá duas opções para utilização, vejamos a definição de cada uma:

- **Homologação:** É o ambiente de testes sem nenhuma validade fiscal ou jurídica, podendo também usar dados reais ou fictícios no preenchimento do documento.
- **Produção:** É o ambiente designado para documentos com valor fiscal, ou seja, são documentos válidos e reconhecidos fiscal e juridicamente.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfe_campo_ambiente.png)

### Campo NFe impressão FCP

A presença do FCP (Fundo de Combate à Pobreza) que é um instituto criado para minimizar o impacto de desigualdades sociais entre os Estados brasileiros, depende do estado em que o emitente e o destinatário da nota se encontram. Pois alguns estados não fazem uso dessa opção.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfe_campo_fcp.png)

### NFe impressão Partilha

A partilha do ICMS introduz uma nova sistemática para o recolhimento do ICMS Interestadual em operações que envolvem consumidores finais não contribuintes do ICMS. Essa sistemática aplica-se às vendas de mercadorias realizadas entre estados, ou seja, em operações interestaduais.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfe_campo_partilha.png)

### NFe Série

O número de série possibilita identificar o modo de emissão e fazer o controle das saídas. Além disso, em casos de empresas que trabalham com mais de uma série, facilita a identificação do grupo de notas.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfe_campo_serie.png)

### NFe Número

O número (ou "nnf", de "número da nota fiscal") inicial que será utilizado no envio da NF-e (Nota Fiscal Eletrônica) é um elemento importante para a identificação e sequenciamento das notas fiscais emitidas por uma empresa.

Caso a empresa atinja o número máximo permitido ou precise reiniciar a sequência, deverá seguir as regras estabelecidas pela legislação e notificar a Secretaria da Fazenda, se necessário.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfe_campo_numero.png)

### NFe Principal CNAE

Na NF-e, o código CNAE é utilizado para classificar a atividade econômica principal da empresa emissora. É importante para determinar o regime de tributação e as obrigações fiscais da empresa.
O código CNAE é informado no cadastro da empresa junto à Receita Federal e não necessariamente precisa ser especificado em cada NF-e emitida, mas é essencial para o enquadramento fiscal e tributário da empresa.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfe_campo_cnae.png)

## NFCe Ativo

Com a função *nota fiscal de consumidor eletronica* ativa, novos campos são liberados para preenchimento logo abaixo na página. Observe que são quase os mesmos campos de preenchimento da NFe.

Estes dados são para que a emissão das notas fiscais funionem perfeitamente, pois os itens solicitados são necessários para a comunicação do nosso sistema com o emissor de NF.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfce_ativo.png)

### Campo NFCe ambiente

Neste campo você vai definir o ambiente de criação das Notas Fiscais de Consumidor Eletrônicas. Você terá duas opções para utilização, vejamos a definição de cada uma:

- **Homologação:** É o ambiente de testes sem nenhuma validade fiscal ou jurídica, podendo também usar dados reais ou fictícios no preenchimento do documento.
- **Produção:** É o ambiente designado para documentos com valor fiscal, ou seja, são documentos válidos e reconhecidos fiscal e juridicamente.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfce_campo_ambiente.png)

### Campo NFCe impressão FCP

A presença do FCP (Fundo de Combate à Pobreza) que é um instituto criado para minimizar o impacto de desigualdades sociais entre os Estados brasileiros, depende do estado em que o emitente e o destinatário da nota se encontram. Pois alguns estados não fazem uso dessa opção.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfce_campo_fcp.png)

### NFCe Série

O número de série possibilita identificar o modo de emissão e fazer o controle das saídas. Além disso, em casos de empresas que trabalham com mais de uma série, facilita a identificação do grupo de notas.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfce_campo_serie.png)

### NFCe Número

O número (ou "nnf", de "número da nota fiscal") inicial que será utilizado no envio da NFC-e (Nota Fiscal de Consumidor Eletrônica) é um elemento importante para a identificação e sequenciamento das notas fiscais emitidas por uma empresa.

Caso a empresa atinja o número máximo permitido ou precise reiniciar a sequência, deverá seguir as regras estabelecidas pela legislação e notificar a Secretaria da Fazenda, se necessário.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfce_campo_numero.png)

### NFCe ID Token

O ID Token é uma chave ou código gerado pela Secretaria da Fazenda (SEFAZ) do estado que permite que a empresa emissora autentique suas transações de NFC-e. Ele ajuda a assegurar que a nota fiscal é emitida por uma fonte confiável e autorizada.

A empresa solicita o ID Token junto à SEFAZ do seu estado. A SEFAZ gera o ID Token e o disponibiliza para a empresa.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfce_campo_id_token.png)

### NFCe CSC Token

O CSC (Código de Segurança do Contribuinte), também conhecido como Token, é uma medida de segurança utilizada na emissão da NFC-e. Ele em conjunto com outros dados da NFC-e, é utilizado para criar um QR Code que permite a verificação da autenticidade da NFC-e pelo consumidor ou pela fiscalização.

O contribuinte (empresa) solicita o CSC junto à Secretaria da Fazenda (SEFAZ) do seu estado. A SEFAZ gera e fornece um CSC exclusivo para a empresa.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_empresa_dados_fiscal_nfce_campo_csc_token.png)

## Salvando nova empresa

Após finalizar o preenchimento você clica em **`Salvar`** e o registro da nova empresa será salvo:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_salvar.gif)

Duas novas abas ficam disponíveis a partir do momento que você salva uma nova empresa, são elas:

### Aba Anexar documentos

- Anexos documentos, nesta primeira aba, você pode inserir uma descrição, fazer upload do arquivo e definir o tipo com as opções disponíveis abaixo:
    - Cópia do cartão do CNPJ ou cópia do contrato social da empresa;
    - Documento de identidade com foto (RG e CPF ou CNH) do proprietário/sócios;
    - Comprovante de residência em seu nome (ou familiares) do proprietário/sócios;
    - Comprovante da atividade exercida (cartão de visita, link de site, nota fiscal de compra de produtos ou prestação de serviços, etc.);
    - Comprovante da atividade exercida (cartão de visita, link de site, nota fiscal de compra de produtos ou prestação de serviços, etc.);
    - Outros Documentos;
    - Outros arquivos de processamento.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_guia_anexo.png)

### Aba Anexos arquivos de processamento

- Anexos arquivos de processamento, vão aparecer todos os arquivos utilizados em transações realizadas por esta empresa na plataforma da **Gestão Online**.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_guia_arquivos.png)