# 🎁 Produtos

Na tela "Produtos", você pode visualizar todos os produtos cadastrados na plataforma, além de ter a opção de cadastrar um novo produto, editar as informações existentes e excluir produtos cadastrados.

Aqui podem ser cadastrados os produtos que a sua empresa comercializa, assim, ao lançar uma venda/pedido, o sistema já terá as informações ligadas a esse produto (fiscal, financeiro, etc.). Agilizando muito o processo de venda e/ou recorrência.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md), favor acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos.gif)

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_importar.png" alt="" data-size="line"> Importar;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar produto.

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_menu.png)

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Menu lateral esquerdo

No lado esquerdo da tela está o menu lateral, nele estão atalhos para outras telas da plataforma, sendo eles:

- <img src="/erp-v2/assets/funcionalidades/icon_produtos_servicos.png" alt="" data-size="line"> Todos os produtos/serviços;
- <img src="/erp-v2/assets/funcionalidades/icon_produto.png" alt="" data-size="line"> Produtos (Tela atual);
- <img src="/erp-v2/assets/funcionalidades/icon_servicos.png" alt="" data-size="line"> [Serviços](/erp-v2/funcionalidades/produtos_servicos/servicos.md);
- <img src="/erp-v2/assets/funcionalidades/icon_kits.png" alt="" data-size="line"> [Kits](/erp-v2/funcionalidades/produtos_servicos/kits.md);

Clicando no ícone da seta, você exibe completamente, e clicando nela novamente, volta ao modo recolhido, confira exemplo abaixo:

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_menu_esquerdo.gif)

## Adicionar novo produto

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo produto, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add.png)

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento das informações do novo produto:

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_inicio.png)

Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/produtos/aba_produto_add_menu.png)

Olhando para a guia **`Geral`**, por padrão, quando você for criar um novo produto, é exigida descrição, status, unidade/medida e grupo. 

- **Descrição** (Nome para identificar o novo produto a ser criado);
- **Imagem (Principal)** (Para facilitar identificação do produto);

![](/erp-v2/assets/funcionalidades/produtos/aba_produto_add_imagem.gif)

- **Descrição complementar** (A descriçāo complementar, é utilizada em catálogos, páginas de venda online e em outros lugares que precisam detalhar melhor o produto);
- **Código** (SKU ou código de barras referente ao produto);
- **Status** (Com duas opções para selecionar, entre ativado e desativado);
- **Unidade/Medida** (Serão mostradas as opções cadastradas [aqui](/erp-v2/funcionalidades/parametrizacoes/unidade_medida_produto_servico.md));
- **Grupo** (Serão mostradas as opções cadastradas [aqui](/erp-v2/funcionalidades/produtos_servicos/grupo_produto.md));
- **Valor Custo** (Aqui você declara o valor deste produto);
- **Tipo de entrega:**
    - **Digital** Se trata de um produto digital (como um ebook ou infoproduto por exemplo), onde nāo há uma entrega física
    - **Unidade:** Entrega física exclusivamente na unidade de entrega/venda. (Retirada)
    - **Transporte:** Entrega física via transportadora (Nesse caso, é necessário colocar informações de medida do produto por exemplo)

{% hint style="warning" %}
**Importante:** A foto do produto precisa ter um dos seguintes formatos, PNG, JPEG ou SVG. O tamanho também tem um limite que é de apenas 5MB! 🖼️
{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_itens.png)

## Tipo de entrega

Como explicado, anteriormente temos 3 opções que definem o "tipo de entrega do produto"

### Tipo de entrega Digital (Produto digital)

Produtos digitais e/ou virtuais. Nāo necessariamente possuem uma entrega física que precisa controlar campos como altura,largura, peso etc. Por isso, utilize essa modalidade caso trabalhe com venda de InfoProdutos, Ebooks, Produtos Digitais etc

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_entrega_unidade.png)

### Tipo de entrega Unidade (Produto físico)

Caso seja produto físico, que será "Retirado" em uma unidade, o sistema nāo irá exigir alguns campos (Como altura, largura, peso etc). Mas irá solicitar o preeenchimento dos campos fiscais descritos abaixo. (Para NFe e/ou NFCe)

{% hint style="warning" %}
**Atençāo:** Em caso de dúvidas sobre o preenchimento, sempre solicite ajuda do seu contador para preencher esses campos.
{% endhint %}

No primeiro campo **NFe/NFCe Tipo**, você define qual tipo de produto será cadastrado, observe que tem disponível várias opções. Em nosso exemplo, iremos marcar a primeira opção.

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_entrega_unidade_tipo.png)

Em sequência, você tem o campo de **Origem da Mercadoria**, nele você tem várias opções para marcar, escolha a que melhor define a origem do produto que você está cadastrando no momento. No exemplo, vamos utilizar a opção *0 - Nacional, exceto as indicadas nos códigos 3,4,5 e 8*.

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_entrega_unidade_origem.png)

Os próximos campos são agora para referências ao código NCM (Nomenclatura Comum do Mercosul). Em nossa plataforma, você pode configurar o NCM usado em sua empresa e, caso queira mais informações sobre esta tela, [**`clique aqui`**](/erp-v2/funcionalidades/fiscal/ncm.md).

Mas observe que neste mesmo campo de **NCM**, você tem o botão <img src="/erp-v2/assets/funcionalidades/icon_adds.png" alt="" data-size="line"> de atalho para adicionar um novo código NCM, ou no botão <img src="/erp-v2/assets/funcionalidades/icon_nova_aba.png" alt="" data-size="line"> para editar o código NCM selecionado em uma nova tela.

Para nosso exemplo, adicionamos o NCM de referência a produtos criados com cerâmica. 😁👍

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_entrega_unidade_ncm.png)

E agora no campo de CEST (Código Especificador da Substituição Tributária) sendo um código padronizado que identifica mercadorias sujeitas ao regime de substituição tributária e de antecipação do recolhimento do ICMS (Imposto sobre Circulação de Mercadorias e Serviços), e caso queira mais informações sobre esta tela, [**`clique aqui`**](/erp-v2/funcionalidades/fiscal/cest.md).

Neste mesmo campo de **CEST**, você tem o botão <img src="/erp-v2/assets/funcionalidades/icon_adds.png" alt="" data-size="line"> de atalho para adicionar um novo código CEST, ou no botão <img src="/erp-v2/assets/funcionalidades/icon_nova_aba.png" alt="" data-size="line"> para editar o código CEST selecionado em uma nova tela.

Para nosso exemplo, adicionamos o CEST de referência ao NCM deste produto, que é o de "artigos de casa".

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_entrega_unidade_cest.png)

### Tipo de entrega transporte  (Produto físico)

Caso no campo **Tipo de entrega** você marque a opção *Transporte*, além dos campos citados acima de configuração de NF, aparecerão as configurações que serāo necessárias para o envio deste produto.

Essas informações são de *Altura*, *Largura*, *Comprimento* e *Peso*. Lembrando que estas informações são feitas com base na embalagem que este produto terá para envio e a unidade de medida é em centímetros.

Observe nosso exemplo, preenchemos todos os dados necessários, incluindo o peso do nosso produto. E os dados de Nota Fiscal, usamos os mesmos explicados acima no tipo entrega unidade. 😁👍

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_entrega_transporte.png)

## Salvando novo produto

Após finalizar o preenchimento, você clica em **`Salvar`** e o registro do novo produto será salvo:

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_salvar.gif)

## Abas estoque

A partir do momento que você concluir a criação de um novo produto, ficarão disponíveis três abas para você acessar, a primeira é de `Estoque`.

{% hint style="warning" %}
**Informativo:** Só aparecerão três abas, se você escolher as opções unidade ou transporte no tipo de entrega.
{% endhint %}

Você pode cadastrar seu produto no estoque, definindo local, empresa e até quantidade mínima para envio de e-mail.

{% hint style="warning" %}
**Atenção:** Verifique a forma de ajustar o estoque inicial em [**`Movimentação Estoque`**](/erp-v2/funcionalidades/produtos_servicos/movimentacao_estoque.md)

{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_guia_estoque.gif)

## Aba categorias

Agora, na aba de **`Categorias`**, você pode definir uma categoria para o produto cadastrado. Ao clicar em adicionar, será mostrada a lista para você escolher uma opção. Essas opções já estão pré-cadastradas na tela categoria de produto:

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre a categoria de produto, [clique aqui](/erp-v2/funcionalidades/produtos_servicos/categoria_produto.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_guia_categorias.gif)

## Aba tabelas de preço

Já na aba `Tabelas de preço` é possível verificar todas as tabelas de preço a que esse produto já está vinculado, permitindo também adicionar facilmente o produto a uma tabela de preço:

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre tabela de preço, [clique aqui](/erp-v2/funcionalidades/parametrizacoes/tabelas_precos.md).
{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_add_produto_guia_tabela_preco.gif)

## Importar produtos

Esta função será de grande ajuda caso você já tenha uma lista com os produtos que deseja cadastrar. 

No botão de importação, ao clicar nele, será aberta uma janela pop-up para você fazer a importação da planilha com os dados. Logo após importar, precisa definir manualmente os campos relacionados para a nossa plataforma poder fazer a importação.

Confira abaixo o procedimento:

{% hint style="info" %}
**Informativo:** Para importação, é válido somente arquivo de planilha no formato **" .xlsx "** ou **" .csv "**
{% endhint %}

![](/erp-v2/assets/funcionalidades/produtos/aba_produtos_importar.gif)