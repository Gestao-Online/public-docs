# 🧩 Grupo de produto

Os grupos de produtos são utilizados para classificar os itens em seu estoque ou catálogo de uma forma relevante para a gestão do negócio. 

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar grupo de produto.

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_menu.png)

<br>

### Filtros grupo de produto

No menu de filtro você pode definir uma busca específica por categorias, seja por ID, identificador, descrição ou status. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_filtro.gif)

<br>

Você pode fazer uso dos filtros para buscar os grupos de produtos, no primeiro filtro você pode buscar pelo ID da categoria:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_filtro_id.png)

<br>

Nesta janela que se abriu, tem algumas funções importantes para abordarmos, o primeiro é o tipo de busca, com algumas opções:

- **Igual a:** Este filtro é usado para buscar registros que possuam um valor exatamente igual ao especificado. Por exemplo, se você busca por “idade igual a 30”, retornará apenas os registros com a idade exata de 30 anos;
- **Diferente de:** Com este filtro, você pode buscar registros que tenham valores diferentes do especificado. Por exemplo, se você busca por “status diferente de ‘concluído’”, retornará todos os registros com status diferentes de “concluído”.
- **Menor que:** É utilizado para buscar registros cujo valor seja menor do que o especificado. Por exemplo, se você busca por “preço menor que 100”, retornará todos os registros com preço inferior a 100.
- **Menor ou igual a:** Semelhante ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “quantidade menor ou igual a 10”, retornará registros com quantidade igual ou menor que 10.
- **Maior que:** Busca registros cujo valor seja maior do que o especificado. Por exemplo, se você busca por “receita maior que 5000”, retornará registros com receita superior a 5000.
- **Maior ou igual a:** Semelhante ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “nota maior ou igual a 7”, retornará registros com nota igual ou maior que 7.
- **Dentro de:** Este filtro é usado para buscar registros cujo valor esteja dentro de um intervalo específico. Por exemplo, se você busca por “id dentro de 15 a 19”, retornará registros com id entre 15 e 19 anos.
- **Fora de:** Similar ao filtro anterior, mas busca registros cujo valor esteja fora do intervalo especificado. Por exemplo, se você busca por “preço fora de 5 a 10”, retornará registros com preço abaixo de 5 ou acima de 10.

{% hint style="info" %}
**Informativo:** No uso do filtro **`Dentro de`** ou **`Fora de`** você precisa inserir todos os valores que ficarão dentro ou fora da busca, igual exemplo abaixo:
{% endhint %}

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_filtro_dentrode.gif)

<br>

Ao lado do filtro ID, você tem o filtro **`Identificador`**, dependendo da quantidade de categorias que você tiver cadastrado, os identificadores podem ajudar na busca, o uso deste filtro é bem simples, precisando apenas digitar o número do identificador para ele fazer a busca:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_filtro_identificador.png)

<br>

Você também pode utilizar o filtro **`Status`** para filtrar sua busca, com as opções de ativado ou desativado:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_filtro_status.png)

<br>

Por último, na mesma linha dos filtros, tem a **`Configuração do grid`**, ao clicar nele uma janela pop-up é aberta e então você pode redefinir os filtros utilizados, pode ser por exibição clicando no marcador, ou até alterar a ordem deles apenas clicando e arrastando! 😁

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_filtro_grid.png)

.

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_filtro_grid.gif)

<br>

Na dúvida sobre o que fazer caso fique tudo muito misturado? Fique despreocupado! Colocamos o botão `Restaurar`, e ele volta a ordem padrão automaticamente, confira abaixo o exemplo:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_filtro_grid_restaurar.png)

<br>

Você também pode pode aumentar ou diminuir o tamanho visível da coluna clicando na linha de separação, reordenar os filtros apenas clicando e movendo para a posição que você preferir e se arrastar ele para fora será oculto, confira abaixo:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_filtro_mouse.gif)

<br>

Se você observar, sempre ao **`lado direito`** de cada grupo de produto criado, você têm dois botões:

- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar item dependente;
- <img src="/erp-v2/assets/modulos/icon_editar_item.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_excluir_item.png" alt="" data-size="line"> Excluir item.

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_editar_excluir.png)

<br>

### Botão direito mouse aba grupo de produto

Lembrando que, em cada item mostrado, você pode usar a função secundária do mouse (Botão direito) e acessar mais opções:

- <img src="/erp-v2/assets/modulos/icon_add_item_filho.png" alt="" data-size="line"> Adicionar item dependente;
- <img src="/erp-v2/assets/modulos/icon_editar_item_mouse.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> Abrir/Editar item em nova aba;
- <img src="/erp-v2/assets/modulos/icon_excluir_item_mouse.png" alt="" data-size="line"> Excluir item(s).

Você pode conferir no nosso exemplo abaixo:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_btn_mouse.gif)

<br>

### Paginação aba grupo de produto

Logo na parte final fica a **`Paginação`**, onde você pode aumentar a quantidade visível de grupos de produto mostrados para até 1000 itens na página:

![](/erp-v2/assets/modulos/servicos/aba_servicos_paginacao.png)

<br>

### Adicionar novo grupo de produto

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar uma novo grupo de produto, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_add.png)

<br>

Ao clicar neste botão, você será levado para esta página, para fazer a adição do grupo de produto:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_add_inicio.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar item dependente;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_add_menu.png)

<br>

Olhando para a guia **`Geral`**, por padrão, quando você for criar um grupo de produto, é exigido descrição, identificador e status, para que ele seja salvo. 

- **Descrição** (Descreva o grupo de produto que está criando);
- **Identificador** (Número gerado automaticamente por nossa plataforma);
- **Imagem (Principal)** (Caso precise para facilitar identificação do grupo);
- **Descrição complementar** (Na falta de imagem, a descrição cai muito bem como opção extra);
- **Analítica** (Se o grupo de produtos será específico ou não);
- **Status** (Ativado ou desativado).

<br>

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_add_produto_itens.png)

<br>

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do grupo de produto será salvo:

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_add_produto_salvar.gif)

<br>

A partir do momento que você concluir a criação de um novo grupo de produto, ficará disponível a guia `Produtos`.

{% hint style="info" %}
**Informativo:** Esta guia só ficará disponível a partir do momento que você salvar este item.
{% endhint %}

Você pode cadastrar os produtos no grupo manualmente, definindo descrição, código, status, tipo e até unidade/medida para envio de email.

![](/erp-v2/assets/modulos/grupo_produto/aba_grupo_produto_add_produto_guia_estoque.png)

{% hint style="danger" %}
**Atenção:** Se você deseja saber mais informações sobre produtos [clique aqui](/erp-v2/modulos/produtos_servicos/produtos.md)
{% endhint %}

<br>