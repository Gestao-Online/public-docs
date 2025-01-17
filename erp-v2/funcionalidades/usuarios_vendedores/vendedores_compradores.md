# 👔 Vendedores & Compradores

Aqui você tem a visão de todos os vendedores e compradores cadastrados na plataforma, podendo fazer cadastro, edição e até excluir um vendedor/comprador cadastrado.

O cadastro de um vendedor/comprador é necessário caso o usuário tenha atividades relacionadas as funcionalidades comerciais (compra e venda)

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_compradores.gif)

<br>

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar vendedor/comprador.

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_menu_direito.png)

<br>

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Adicionar novo vendedor

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo vendedor, confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_add_vendedor.png)


<br>

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento dos dados do novo usuário:

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_add_vendedor_page.png)

<br>

Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_menu_direito_vendedores.png)

<br>

### Aba Geral

Olhando para a aba **`Geral`**, por padrão, quando você for criar um vendedor é exigido preencher os campos com asterisco. Agora os outros campos para preenchimento podem deixar para o usuário quando confirmar a conta, listamos os campos abaixo:

- **Nome** (Nome completo do vendedor);
- **E-mail** (Não pode ser modificado depois, use o mesmo da conta de usuário);
- **Empresa** (Aqui você define a empresa de trabalho, e para mais informações [clique aqui](/erp-v2/funcionalidades/parametrizacoes/empresas.md));
- **Unidade** (Nome do local/setor de trabalho, para mais informações [clique aqui](/erp-v2/funcionalidades/unidades_locais_estoque/unidades_lojas.md));
- **Centro de resultado** (Defina qual parte da empresa pertence, para mais informações [clique aqui](/erp-v2/funcionalidades/parametrizacoes/centro_resultado.md));
- **Status** (Aqui você define o status do vendedor, sendo ativado ou desativado);
- **Usuário** (Defina o usuário existente do vendedor, aqui estabeleceremos o vínculo do usuário autenticado com o perfil do vendedor);
- **Local estoque** (Qual local terá acesso, para saber mais [clique aqui](/erp-v2/funcionalidades/unidades_locais_estoque/local_estoque.md));

{% hint style="danger" %}
<img src="/erp-v2/assets/marketplace/coroa_premium.png" alt="" data-size="line"> Para ter acesso aos campos Empresa, Unidade, Centro de Resultado e Local de Estoque, é necessário instalar o Módulo referente a cada um deles, a parte pelo [Marketplace](/erp-v2/marketplace/inicio.md) do Gestão Online, entre em contato com o nosso time [Comercial](https://api.whatsapp.com/send?phone=556237735650&text=Ol%C3%A1%20gostaria%20de%20mais%20informa%C3%A7%C3%B5es%20sobre%20o%20marketplace%20do%20Gest%C3%A3o.Online) para maiores informações.
{% endhint %}

Já os campos de `Configuraçāo adicional`, servem para facilitar o dia a dia do vendedor/comprador, preenchendo automáticamente os campos no momento de uma venda/pedido. Com valores estabelecidos aqui, como "padrāo para o vendedor".

- **Tipo de movimentação** (Definir o tipo de entrada/saída sendo compra ou venda, para saber mais [clique aqui](/erp-v2/funcionalidades/parametrizacoes/tipo_movimentacao.md));
- **Tipo de negociação** (Definir a forma de pagamento padrão, para saber mais [clique aqui](/erp-v2/funcionalidades/financeiro/tipo_negociacao.md)).

<br>

{% hint style="info" %}
Quando você for criar um vendedor é exigido preencher os campos com asterisco, o restante pode ser preenchido depois.
{% endhint %}

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_criar_vendedor.png)

<br>

Uma observação para o preenchimento dos dados de vendedor, nós colocamos um menu de acesso rápido nas opções unidade, usuário e local de  estoque, confira abaixo a demonstração:

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_menu_extra.gif)

<br>

## Configurações adicionais

Logo abaixo do preenchimento dos dados do vendedor, você encontrará dois campos: Tipo de Movimentação (com valor padrão) e Tipo de Negociação (com valor padrão). Assim que esses campos forem preenchidos, quando ele realizar uma venda, o sistema os preencherá automaticamente com os valores que você definiu.

Caso esses campos sejam deixados em branco, o vendedor precisará selecioná-los manualmente toda vez que realizar uma venda.

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_config_adicional.gif)

<br>

## Salvando novo vendedor

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do usuário será salvo e o acesso disponível ao vendedor usando seu login de usuário:

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_salvar.gif)

<br>

## Abas adicionais após criar vendedor

Se você observar na parte superior, após criar o vendedor, três abas ficarão na cor azul disponíveis para você editar as informações, vejamos um pouco mais sobre elas:

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_guias.png)

<br>

### Aba perfil de desconto (vendas)

A primeira é a de perfil de desconto (vendas), por padrão ficará em branco, mas vamos inserir informação nelas, primeiro clicando no botão adicionar item:

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_guia_perfil_desconto.png)

<br>

Você pode deixar definido um limite de desconto em vendas para esse vendedor, sendo valor (em reais R$) ou percentual. Esse mesmo valor pode ser editado futuramente, removido ou até criar outros novos perfis de descontos:

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_guia_.gif)

<br>

### Aba perfil de desconto (compras)

Você também pode deixar definido um limite de desconto em compras para esse vendedor, sendo valor (em reais R$) ou percentual. Esse mesmo valor pode ser editado futuramente, removido ou até criar outros novos perfis de descontos:

![](/erp-v2/assets/funcionalidades/vendedores/aba_vendedores_guia_2.gif)


{% hint style="warning" %}
**Detalhe:** As abas citadas acima, fazem referência a tela principal [Perfil de Desconto](/erp-v2/funcionalidades/usuarios_vendedores/perfil_desconto.md), nela está organizado todos os perfis mostrados acima.
{% endhint %}

### Aba Parceiros (Carteira vendedor)

Na última aba, temos os parceiros (Carteira vendedor), nela é listado primeiro todos os parceiros (clientes/indicadores/fornecedores) que tenham vínculo a este vendedor. 

Podendo fazer até mesmo o cadastro de novos parceiros, diretamente vinculados ao vendedor:

![](/erp-v2/assets/funcionalidades/vendedores/aba_parceiros_inicio.png)

<br>

{% hint style="warning" %}
**Detalhe:** A aba citada acima, faz referência a tela principal [Clientes/parceiros](/erp-v2/funcionalidades/parceiros/clientes.md), nela está organizado todas as informações mostradas acima.
{% endhint %}