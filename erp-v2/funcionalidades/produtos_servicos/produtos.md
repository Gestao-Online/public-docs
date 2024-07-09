# 🎁 Produtos

Aqui você tem a visão de todos os produtos cadastrados na plataforma **Gestão.Online**, podendo cadastrar um novo produto, editar informações existentes e até excluir um produto cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

<br>

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_importar.png" alt="" data-size="line"> Importar;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Produto.

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_menu.png)

<br>

{% hint style="warning" %}
**Filtros:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Menu lateral esquerdo

No lado esquerdo da tela está o menu lateral, nele estão atalhos para outras abas da plataforma, sendo eles:

- <img src="/erp-v2/assets/funcionalidades/icon_produtos_servicos.png" alt="" data-size="line"> Todos os produtos/serviços;
- <img src="/erp-v2/assets/funcionalidades/icon_produto.png" alt="" data-size="line"> Produtos (Aba atual);
- <img src="/erp-v2/assets/funcionalidades/icon_servicos.png" alt="" data-size="line"> [Serviços](/erp-v2/funcionalidades/produtos_servicos/servicos.md);
- <img src="/erp-v2/assets/funcionalidades/icon_kits.png" alt="" data-size="line"> [Kits](/erp-v2/funcionalidades/produtos_servicos/kits.md);

Clicando no ícone da seta, você exibe completamente, e clicando nela novamente, volta ao modo recolhido, confira exemplo abaixo:

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_menu_esquerdo.gif)

<br>

## Adicionar novo produto

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo produto, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add.png)

<br>

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento das informações do novo produto:

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_inicio.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/produtos/aba_produto_add_menu.png)

<br>

Olhando para a guia **`Geral`**, por padrão, quando você for criar um novo produto, é exigido descrição, status, unidade/medida e grupo. 

- **Descrição** (Nome para identificar o novo produto a ser criado);
- **Imagem (Principal)** (Para facilitar identificação do produto);
    - ![](/erp-v2/assets/funcionalidades/produtos/aba_produto_add_imagem.gif)
- **Descrição complementar** (Na falta de imagem, a descrição cai muito bem como opção extra);
- **Código** (SKU ou código de barras referente ao produto);
- **Status** (Com duas opções para selecionar, entre ativado e desativado);
- **Unidade/Medida** (Serão mostradas as opções cadastradas [aqui](/erp-v2/funcionalidades/parametrizacoes/unidade_medida_produto_servico.md));
- **Grupo** (Serão mostradas as opções cadastradas [aqui](/erp-v2/funcionalidades/produtos_servicos/grupo_produto.md));
- **Valor Custo** (Aqui você declara o valor deste produto);
- **Tipo de entrega:**
    - **Digital** Não mostrará as opções de NFe/NFCe e não terá a guia estoque quando salvar o produto;
    - **Unidade:** Ao marcar esta opção, terá que confirmar as informações de NFe/NFCe, sendo tipo, origem da mercadoria, NCM e CEST;
    - **Transporte:** Ao escolher, poderá definir as dimensões do produto, altura, largura, comprimento e peso. E também as informações de NFe/NFCe, sendo tipo, origem da mercadoria, NCM e CEST;

<br>

{% hint style="warning" %}
**Importante:** A foto do produto precisa ter um dos seguintes formatos, PNG, JPEG ou SVG. O tamanho também tem um limite que é de apenas 5MB! 🖼️
{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_itens.png)

<br>

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do novo produto será salvo:

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_salvar.gif)

<br>

## Guias adicionais ao criar um produto

A partir do momento que você concluir a criação de um novo produto, ficarão disponíveis três guias para você acessar, a primeira é de `Estoque`.

{% hint style="warning" %}
**Informativo:** Só aparecerão três guias, se você escolher as opções unidade ou transporte no tipo de entrega.
{% endhint %}

Você pode cadastrar seu produto no estoque, definindo local, empresa e até quantidade mínima para envio de e-mail.

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_guia_estoque.gif)

<br>

## Guia Categorias

Agora, na guia de **`Categorias`**, você pode definir uma categoria para o produto cadastrado. Ao clicar em adicionar, será mostrada a lista para você escolher uma opção. Essas opções já estão pré-cadastradas na aba categoria de produto:

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre categoria de produto [clique aqui](/erp-v2/funcionalidades/produtos_servicos/categoria_produto.md)
{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_guia_categorias.gif)

<br>

## Guia tabelas de preço

Por último, na guia `Tabelas de preço`  você pode adicionar um valor ou percentual, e qual tabela de preço existente irá ser vinculado:

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre tabela de preço [clique aqui](/erp-v2/funcionalidades/parametrizacoes/tabelas_precos.md)
{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_guia_tabela_preco.gif)

<br>

## Importar produtos

Esta função será de grande ajuda caso você já tenha uma lista com os produtos que deseja cadastrar. 

No botão de importação, ao clicar nele, será aberta uma janela pop-up para você fazer a importação da planilha com os dados. Logo após importar, precisa definir manualmente os campos relacionados para a nossa plataforma poder fazer a importação.

Confira abaixo o procedimento:

{% hint style="info" %}
**Informativo:** Para importação, é válido somente arquivo de planilha no formato **" .xlsx "** ou **" .csv "**
{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_importar.gif)