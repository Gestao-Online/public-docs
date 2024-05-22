# 👔 Vendedores & Compradores

Aqui você tem a visão de todos os vendedores e compradores cadastrados na plataforma Gestão.Online, podendo fazer cadastro, edição e até excluir um vendedor/comprador cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_compradores.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar vendedor/comprador.

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_menu_direito.png)

<br>

### Filtros vendedores & compradores

No menu de filtro você pode definir uma busca específica por vendedores, seja por nome, status, unidade ou usuário. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro.gif)

<br>

Você pode fazer uso dos filtros de cada categoria que aparecem com o resultado dos vendedores, no primeiro filtro pode buscar pelo ID do vendedor/comprador:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro_id.png)

Nesta janela que se abriu, estão algumas funções importantes para abordarmos, o primeiro é o tipo de busca, com algumas opções:

- **Igual a:** Este filtro é usado para buscar registros que possuam um valor exatamente igual ao especificado. Por exemplo, se você busca por “idade igual a 30”, retornará apenas os registros com a idade exata de 30 anos;
- **Diferente de:** Com este filtro, você pode buscar registros que tenham valores diferentes do especificado. Por exemplo, se você busca por “status diferente de ‘concluído’”, retornará todos os registros com status diferentes de “concluído”.
- **Menor que:** É utilizado para buscar registros cujo valor seja menor do que o especificado. Por exemplo, se você busca por “preço menor que 100”, retornará todos os registros com preço inferior a 100.
- **Menor ou igual a:** Similar ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “quantidade menor ou igual a 10”, retornará registros com quantidade igual ou menor que 10.
- **Maior que:** Busca registros cujo valor seja maior do que o especificado. Por exemplo, se você busca por “receita maior que 5000”, retornará registros com receita superior a 5000.
- **Maior ou igual a:** Similar ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “nota maior ou igual a 7”, retornará registros com nota igual ou maior que 7.
- **Dentro de:** Este filtro é usado para buscar registros cujo valor esteja dentro de um intervalo específico. Por exemplo, se você busca por “id dentro de 15 a 19”, retornará registros com id entre 15 e 19 anos.
- **Fora de:** Similar ao filtro anterior, mas busca registros cujo valor esteja fora do intervalo especificado. Por exemplo, se você busca por “preço fora de 5 a 10”, retornará registros com preço abaixo de 5 ou acima de 10.

{% hint style="info" %}
**Informativo:** No uso do filtro **`Dentro de`** ou **`Fora de`** você precisa inserir todos os valores que ficarão dentro ou fora da busca, igual exemplo abaixo:
{% endhint %}

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro_dentrode.gif)

<br>

Depois do filtro de ID, tem o filtro de **`Nome`**, para colocar o texto que será buscado, por isso é sempre importante o preenchimento completo dos dados de cada vendedor/comprador 😉👍

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro_nome.png)

<br>

Agora no filtro por **`Status`** para uso nas buscas, existem duas opções para você utilizar, sendo elas:

- <img src="/erp-v2/assets/modulos/icon_status_ativado.png" alt="" data-size="line"> Ativado;
- <img src="/erp-v2/assets/modulos/icon_status_desativado.png" alt="" data-size="line"> Desativado;

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro_status.png)

<br>

Você pode pesquisar por **`Unidade`** (Observe que colocamos o ícone <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> abrir item em nova aba para facilitar o acesso a informações da unidade), confira exemplo abaixo, pois é necessário digitar o nome da unidade para aparecer na busca:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro_unidade.gif)

<br>

No filtro **`Usuário`** você pode digitar o nome ou parte do nome do usuário de acesso do vendedor (Observe que colocamos o ícone <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> abrir item em nova aba para facilitar o acesso a informações do usuário do vendedor), pois cada vendedor precisa de um nome de usuário para ter acesso a nossa plataforma:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro_usuario.png)

<br>

Por último, na mesma linha dos filtros, está a **`Configuração do grid`**, ao clicar nele uma janela pop-up é aberta e então você pode redefinir os filtros utilizados, pode ser por exibição clicando no marcador, ou até alterar a ordem deles apenas clicando e arrastando! 😁

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro_grid.png)

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro_grid.gif)

<br>

Na dúvida sobre o que fazer caso fique tudo muito misturado? Pois você pode ficar despreocupado! Colocamos o botão redefinir, e ele volta a ordem padrão automaticamente, confira abaixo o exemplo:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtro_grid_restaurar.gif)

<br>

Você também pode pode aumentar ou diminuir o tamanho visível da coluna clicando na linha de separação, reordenar os filtros apenas clicando e movendo para a posição que você preferir e se arrastar ele para fora será oculto, confira abaixo:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_filtros_mouse.gif)

<br>

Se você observar, sempre ao **`lado direito`** de cada vendedor mostrado, você têm dois botões:

- <img src="/erp-v2/assets/modulos/icon_editar_item.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_excluir_item.png" alt="" data-size="line"> Excluir item.

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_editar_excluir.png)

<br>

### Botão direito mouse aba usuários

Lembrando que em cada item mostrado, você pode usar a função secundária do mouse (Botão direito) e acessar mais opções:

- <img src="/erp-v2/assets/modulos/icon_editar_item_mouse.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> Abrir/Editar item em nova aba;
- <img src="/erp-v2/assets/modulos/icon_excluir_item_mouse.png" alt="" data-size="line"> Excluir item(s).

Você pode conferir no nosso teste abaixo:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_btn_mouse.gif)

<br>

### Paginação aba vendedores

Logo na parte final fica a **`Paginação`**, onde você pode aumentar a quantidade visível de vendedores mostrados para até 1000 itens na página:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_paginacao.png)

<br>

### Dashboard vendedores 

Assim que se acessa a página inicial dos vendedores/compradores você pode ver um ícone na lateral esquerda da tela se mexendo, ao clicarmos nele uma janela lateral aparecerá com algumas informações, vejamos abaixo:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_dashboard.gif)

<br>

Explicando cada bloco dele, temos primeiro os indicadores de quantidade, vendedores ativos e inativos. Esses números são atualziados em tempo real na plataforma, podendo também utilizar o botão <img src="/erp-v2/assets/modulos/icon_refresh.png" alt="" data-size="line"> refresh para atualizar os dados:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_dashboard_1.png)

<br>

Logo abaixo das quantidades, nós temos um gráfico de coluna com a quantidade de vendedores por centro de resultado:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_dashboard_2.png)

<br>



### Adicionar novo vendedor

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo vendedor, confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_add_vendedor.png)


<br>

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento dos dados do novo usuário:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_add_vendedor_page.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_menu_direito_vendedores.png)

<br>

Olhando para a guia **`Geral`**, por padrão, quando você for criar um vendedor é exigido preencher os campos com asterisco. Agora os outros campos para preenchimento pode deixar para o usuário quando ele confirmar a conta, listamos os campos abaixo:

- **Nome** (Nome completo do vendedor);
- **E-mail** (Não pode ser modificado depois, use o mesmo da conta de usuário);
- **Empresa** (Defina a empresa de trabalho, e para mais informações [clique aqui](/erp-v2/modulos/parametrizacoes/empresas.md));
- **Unidade** (Nome do local/setor de trabalho, para mais informações [clique aqui](/erp-v2/modulos/unidades_locais_estoque/unidades_lojas.md));
- **Centro de resultado** (Defina qual parte da empresa pertence, para mais informações [clique aqui](/erp-v2/modulos/parametrizacoes/centro_resultado.md));
- **Status** (Aqui você define o status do vendedor, sendo ativado ou desativado);
- **Usuário** (Defina o usuário existente do vendedor, sem ele não tem como prosseguir);
- **Local estoque** (Qual local ele terá acesso, para saber mais [clique aqui](/erp-v2/modulos/unidades_locais_estoque/local_estoque.md));
- **Tipo de movimentação** (Definir o tipo de entrada/saída sendo compra ou venda, para saber mais [clique aqui](/erp-v2/modulos/parametrizacoes/tipo_movimentacao.md));
- **Tipo de negociação** (Definir a forma de pagamento padrão, para saber mais [clique aqui](/erp-v2/modulos/financeiro/tipo_negociacao.md)).

<br>

{% hint style="danger" %}
**Atenção:** Quando você for criar um vendedor é exigido preencher os campos com asterisco, o restante pode ser preenchido depois.
{% endhint %}

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_criar_vendedor.png)

<br>

Uma observação para o preenchimento dos dados de vendedor, nós colocamos um menu de acesso rápido nas opções unidade, usuário e local de  estoque, confira abaixo a demostração:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_menu_extra.gif)

<br>

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do usuário será salvo e o acesso disponível ao vendedor usando seu login de usuário:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_salvar.gif)


<br>

### Guias adicionais após criar vendedor

Se você observar na parte superior, após criar o vendedor, três guias ficarão na cor azul disponíveis para você editar as informações, vejamos um pouco mais sobre elas:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_guias.png)

<br>

A primeira é a de perfil de desconto (vendas), por padrão ela ficará em branco, mas vamos inserir informação nelas, primeiro clicando no botão adicionar item:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_guia_perfil_desconto.png)

<br>

Você pode deixar definido um limite de desconto em vendas para esse vendedor, sendo ela em valor ou percentual. Esse mesmo valor pode ser editado futuramente, removido ou até criar outros novos perfis de descontos:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_guia_.gif)

<br>

Você também pode deixar definido um limite de desconto em compras para esse vendedor, sendo ela em valor ou percentual. Esse mesmo valor pode ser editado futuramente, removido ou até criar outros novos perfis de descontos:

![](/erp-v2/assets/modulos/vendedores/aba_vendedores_guia_2.gif)


{% hint style="warning" %}
**Detalhe:** As guias citadas acima, fazem referência a aba principal [Perfil de Desconto](/erp-v2/modulos/usuarios_vendedores/perfil_desconto.md), nela está organizado todos os perfis mostrados acima.
{% endhint %}

Na última guia, temos os parceiros (Carteira vendedor), nela é listado primeiro todos os parceiros que tenham vínculo a este vendedor. 

Podendo ele fazer até mesmo o cadastro de novos clientes, fornecedores, indicadores e até transportadoras com o seu login:

![](/erp-v2/assets/modulos/vendedores/aba_parceiros_inicio.png)

<br>

{% hint style="warning" %}
**Detalhe:** A guia citada acima, faz referência a aba principal [Clientes/parceiros](/erp-v2/modulos/parceiros/clientes.md), nela está organizado todas as informações mostradas acima.
{% endhint %}