# 🏭 Local de estoque

Aqui você tem a visão de todos os locais de estoque cadastrados na plataforma Gestão.Online, podendo fazer cadastro, editar informações, adicionar item dependente e até excluir um estoque cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/modulos/estoque/aba_estoque.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Unidade/Loja.
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;

![](/erp-v2/assets/modulos/estoque/aba_estoque_menu.png)

<br>

### Filtros local de estoque

No menu de filtro você pode definir uma busca específica por local de estoque, seja por descrição, status e identificador. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/estoque/aba_estoque_filtro.gif)

<br>

Você pode fazer uso dos filtros de cada categoria que aparecem com o resultado dos locais de estoque, no primeiro filtro você pode buscar pelo ID do estoque:

![](/erp-v2/assets/modulos/estoque/aba_estoque_filtro_id.png)

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

![](/erp-v2/assets/modulos/estoque/aba_estoque_filtro_dentrode.gif)

<br>

Depois do filtro de ID, está o filtro de **`Identificador`**, para colocar o código identificador do local de estoque:

![](/erp-v2/assets/modulos/estoque/aba_estoque_filtro_identificador.png)

<br>

Agora no filtro por **`Status`** existem duas opções para você utilizar nas buscas, sendo elas:

- Ativado;
- Desativado;

![](/erp-v2/assets/modulos/estoque/aba_estoque_filtro_status.png)

<br>

Por último, na mesma linha dos filtros, tem a **`Configuração do grid`**, ao clicar nele uma janela pop-up é aberta e então você pode redefinir os filtros utilizados, pode ser por exibição clicando no marcador, ou até alterar a ordem deles apenas clicando e arrastando! 😁

![](/erp-v2/assets/modulos/estoque/aba_estoque_filtro_grid.png)

.

![](/erp-v2/assets/modulos/estoque/aba_estoque_filtro_grid.gif)

<br>

Na dúvida sobre o que fazer caso fique tudo muito misturado? Pois você pode ficar despreocupado! Colocamos o botão redefinir, e ele volta a ordem padrão automaticamente, confira abaixo o exemplo:

![](/erp-v2/assets/modulos/estoque/aba_estoque_filtro_grid_restaurar.png)

<br>

Você também pode pode aumentar ou diminuir o tamanho visível da coluna clicando na linha de separação, reordenar os filtros apenas clicando e movendo para a posição que você preferir e se arrastar ele para fora será oculto, confira abaixo:

![](/erp-v2/assets/modulos/estoque/aba_estoque_filtro_mouse.gif)

<br>

Se você observar, sempre ao **`lado direito`** de cada local de estoque mostrado, você têm dois ou três botões:

- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar item filho (Quando um local de estoque tem outro local dependente);
- <img src="/erp-v2/assets/modulos/icon_editar_item.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_excluir_item.png" alt="" data-size="line"> Excluir item.

![](/erp-v2/assets/modulos/estoque/aba_estoque_editar_excluir.png)

<br>

### Botão direito mouse aba local de estoque

Lembrando que em cada item mostrado, você pode usar a função secundária do mouse (Botão direito) e acessar mais opções:

- <img src="/erp-v2/assets/modulos/icon_add_item_filho.png" alt="" data-size="line"> Adicionar item filho;
- <img src="/erp-v2/assets/modulos/icon_editar_item_mouse.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> Abrir/Editar item em nova aba;
- <img src="/erp-v2/assets/modulos/icon_excluir_item_mouse.png" alt="" data-size="line"> Excluir item(s).

Você pode conferir no nosso teste abaixo:

![](/erp-v2/assets/modulos/estoque/aba_estoque_btn_mouse.gif)

<br>

### Paginação aba local de estoque

Logo na parte final fica a **`Paginação`**, onde você pode aumentar a quantidade visível de usuários mostrados para até 1000 itens na página:

![](/erp-v2/assets/modulos/estoque/aba_estoque_paginacao.png)

<br>

### Adicionar novo local de estoque

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo local de estoque, confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/modulos/estoque/aba_estoque_add.png)

<br>

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento dos dados do novo local de estoque:

![](/erp-v2/assets/modulos/estoque/aba_estoque_add_inicio.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar novo local de estoque;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/modulos/estoque/aba_estoque_add_menu.png)

<br>

Olhando para a guia **`Geral`**, por padrão, quando você for criar novo local de estoque é exigido descrição, identificador e status. 

- **Descrição** (Nome para identificar o novo local de estoque);
- **Identificador** (É gerado por padrão pela plataforma, mas você pode colocar outro, desde que, não esteja sendo utilizado);
- **Analítica** (Quando ativada não aceitará integração outros locais de estoque como dependentes);
- **Status** (Com duas opções para selecionar, entre ativado e desativado);

<br>

![](/erp-v2/assets/modulos/estoque/aba_estoque_add_unidade_itens.png)

<br>

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do novo local de estoque será salvo:

![](/erp-v2/assets/modulos/estoque/aba_estoque_add_unidade_salvar.gif)

<br>

A partir do momento que você concluir a criação, uma nova guia ficará disponível, a de `Movimentações/Transferências`, e aqui serão mostradas todas as transferencias, vendas,  compras, devoluções e ajustes.

Você já tem acesso as movimentações, poder buscar movimentações específicas, editar uma movimentação, ou até excluir.

{% hint style="danger" %}
**Informativo:** Se você deseja saber mais informações sobre Movimentações/Transferencias [clique aqui](/erp-v2/modulos/produtos_servicos/movimentacao_estoque.md)
{% endhint %}

![](/erp-v2/assets/modulos/estoque/aba_estoque_add_unidade_guia_movimentacao.gif)

