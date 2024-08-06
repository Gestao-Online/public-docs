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

Nesta tela tem um menu ao lado direito da tela com as seguintes funções:

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






## Salvando nova empresa

Após finalizar o preenchimento você clica em **`Salvar`** e o registro da nova empresa será salvo:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_salvar.gif)

Duas novas guias ficam disponíveis a partir do momento que você salva uma nova empresa, são elas:

## Aba Anexar documentos

- Anexos documentos, nesta primeira aba, você pode inserir uma descrição, fazer upload do arquivo e definir o tipo com as opções disponíveis abaixo:
    - Cópia do cartão do CNPJ ou cópia do contrato social da empresa;
    - Documento de identidade com foto (RG e CPF ou CNH) do proprietário/sócios;
    - Comprovante de residência em seu nome (ou familiares) do proprietário/sócios;
    - Comprovante da atividade exercida (cartão de visita, link de site, nota fiscal de compra de produtos ou prestação de serviços, etc.);
    - Comprovante da atividade exercida (cartão de visita, link de site, nota fiscal de compra de produtos ou prestação de serviços, etc.);
    - Outros Documentos;
    - Outros arquivos de processamento.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_guia_anexo.png)

## Aba Anexos arquivos de processamento

- Anexos arquivos de processamento, vão aparecer todos os arquivos utilizados em transações realizadas por esta empresa na plataforma da **Gestão Online**.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_empresas_add_guia_arquivos.png)