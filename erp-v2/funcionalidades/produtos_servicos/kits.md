# 🛍️ Kits de produto/serviço

Nessa tela do sistema, você pode visualizar todos os kits de produtos/serviços cadastrados, além de ter a opção de cadastrar um novo kit, editar as informações existentes e excluir kits cadastrados.

Os "Kits" são úteis para agrupar produtos e/ou serviços. Permitindo criar "combos" com os produtos e serviços já existentes no sistema, facilitando o lançamento da venda, precificação e gestão de estoque.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/kits/aba_kits.gif)


Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_importar.png" alt="" data-size="line"> Importar;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Kits.

![](/erp-v2/assets/funcionalidades/kits/aba_kits_menu.png)

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Menu lateral esquerdo

No lado esquerdo da tela está o menu lateral, nele estão atalhos para outras telas da plataforma, sendo eles:

- <img src="/erp-v2/assets/funcionalidades/icon_produtos_servicos.png" alt="" data-size="line"> Todos os produtos/serviços;
- <img src="/erp-v2/assets/funcionalidades/icon_produto.png" alt="" data-size="line"> [Produtos](/erp-v2/funcionalidades/produtos_servicos/produtos.md);
- <img src="/erp-v2/assets/funcionalidades/icon_servicos.png" alt="" data-size="line"> [Serviços](/erp-v2/funcionalidades/produtos_servicos/servicos.md);
- <img src="/erp-v2/assets/funcionalidades/icon_kits.png" alt="" data-size="line"> Kits (Tela atual);

Clicando no ícone da seta, você exibe completamente, e clicando nela novamente, volta ao modo recolhido, confira exemplo abaixo:

![](/erp-v2/assets/funcionalidades/kits/aba_kits_menu_esquerdo.gif)

## Adicionar novo produto

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo produto, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/kits/aba_kits_add.png)

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento das informações do novo kit:

![](/erp-v2/assets/funcionalidades/kits/aba_kits_add_inicio.png)

Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/kits/aba_kits_add_menu.png)

Olhando para a guia **`Geral`**, por padrão, quando você for criar um novo kit, é exigido descrição, status, unidade/medida e grupo. 

- **Descrição** (Nome para identificar o novo kit a ser criado);
- **Imagem (Principal)** (Para facilitar identificação do kit);
    - ![](/erp-v2/assets/funcionalidades/kits/aba_kits_add_imagem.gif)
- **Descrição complementar** (A descriçāo complementar, é utilizada em catálogos, páginas de venda online e em outros lugares que precisam detalhar melhor o produto);
- **Código** (SKU ou código de barras referente ao kit);
- **Status** (Com duas opções para selecionar, entre ativado e desativado);
- **Unidade/Medida** (Serão mostradas as opções cadastradas [aqui](/erp-v2/funcionalidades/parametrizacoes/unidade_medida_produto_servico.md));
- **Grupo** (Serão mostradas as opções cadastradas [aqui](/erp-v2/funcionalidades/produtos_servicos/grupo_produto.md));
- **Valor Custo** (Aqui você declara o valor deste kit);
- **Tipo de entrega:**
    - **Digital** Se trata de um produto digital (como um ebook ou infoproduto por exemplo), onde nāo há uma entrega física
    - **Unidade:** Entrega física exclusivamente na unidade de entrega/venda. (Retirada)
    - **Transporte:** Entrega física via transportadora (Nesse caso, é necessário colocar informações de medida do produto por exemplo)

![](/erp-v2/assets/funcionalidades/kits/aba_kits_add_kit_itens.png)

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do novo kit de produto/serviço será salvo:

![](/erp-v2/assets/funcionalidades/kits/aba_kits_add_kit_salvar.gif)

A partir do momento que você concluir a criação do novo kit, ficarão disponíveis três guias para você acessar, a primeira é de `Itens`.

Nesta guia você pode vincular um produto/serviço ao kit que você acabou de criar, escolhendo um dos já disponíveis e definindo a quantidade. 

Pode também utilizar os filtros disponíveis caso tenha muitos itens sendo exibidos. Depois é só salvar e aparecerá, confira abaixo:

![](/erp-v2/assets/funcionalidades/kits/aba_kits_add_kit_guia_itens.gif)

Agora, na guia de **`Categorias`**, você pode definir uma categoria para o kit cadastrado. Ao clicar em adicionar, será mostrada a lista para você escolher uma opção. Essas opções já estão pré-cadastradas na tela categoria de produto:

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre categoria de produto [clique aqui](/erp-v2/funcionalidades/produtos_servicos/categoria_produto.md)
{% endhint %}

![](/erp-v2/assets/funcionalidades/kits/aba_kits_add_kit_guia_categoria.gif)

Já na guia `Tabelas de preço` é possível verificar todas as tabelas de preço que esse kit já está vinculado, permitindo também adicionar facilmente o kit a uma tabela de preço:

{% hint style="danger" %}
<img src="/erp-v2/assets/marketplace/coroa_premium.png" alt="" data-size="line"> Para ter acesso a Aba tabelas de preço, é necessário instalar o Módulo Tabelas de Preço a parte pelo [Marketplace](/erp-v2/marketplace/inicio.md) do Gestão Online, entre em contato com o nosso time [Comercial](https://api.whatsapp.com/send?phone=556237735650&text=Ol%C3%A1%20gostaria%20de%20mais%20informa%C3%A7%C3%B5es%20sobre%20o%20marketplace%20do%20Gest%C3%A3o.Online) para maiores informações.
{% endhint %}

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre tabela de preço [clique aqui](/erp-v2/funcionalidades/parametrizacoes/tabelas_precos.md)
{% endhint %}

![](/erp-v2/assets/funcionalidades/kits/aba_kits_add_kit_guia_tabela_preco.gif)

## Importar kits

Esta função será de grande ajuda caso você já tenha uma lista com os serviços que deseja cadastrar. 

No botão de importação, ao clicar nele, será aberta uma janela pop-up para você fazer a importação da planilha com os dados. Logo após, você importar, precisa definir manualmente os campos relacionados para a nossa plataforma poder fazer a importação.

Confira abaixo o procedimento:

{% hint style="info" %}
**Informativo:** Para importação, é válido somente arquivo de planilha no formato **" .xlsx "**
{% endhint %}

![](/erp-v2/assets/funcionalidades/kits/aba_kits_importar.gif)
