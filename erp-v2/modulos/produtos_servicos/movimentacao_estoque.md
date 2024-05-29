# 📤 Movimentação de estoque

Aqui você tem a visão do estoque de produtos na plataforma Gestão.Online, podendo cadastrar um novo produto, editar informações existentes e até excluir um produto cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar movimentação no estoque.

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_menu.png)

<br>

### Filtros de movimentação estoque

No menu de filtro você pode definir uma busca específica por movimentações, seja por ID, tipo, data de lançamento, lançamento, quantidade e até usuário. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro.gif)

<br>

Você pode fazer uso dos filtros de cada categoria que aparecem com o resultado dos produtos, no primeiro filtro você pode buscar pelo ID da movimentação:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_id.png)

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

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_dentrode.gif)

<br>

Depois do filtro de ID, está o filtro de **`Tipo`**, ele tem as opções:

- <img src="/erp-v2/assets/modulos/icon_transferencia.png" alt="" data-size="line"> Transferência;
- <img src="/erp-v2/assets/modulos/icon_venda.png" alt="" data-size="line"> Venda;
- <img src="/erp-v2/assets/modulos/icon_compra.png" alt="" data-size="line"> Compra;
- <img src="/erp-v2/assets/modulos/icon_devolucao.png" alt="" data-size="line"> Devolução;
- <img src="/erp-v2/assets/modulos/icon_ajuste.png" alt="" data-size="line"> Ajuste.

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_tipo.png)

<br>

Agora no filtro **`Data Lançamento`** você pode utilizar o calendário para definir a data que está procurando:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_data.gif)

<br>

O filtro **`Local de estoque`** mostrará os locais cadastrados ao clicar na barra de pesquisa, ou utilizando o modo de lista completo para você buscar. Observe abaixo:

{% hint style="warning" %}
**Informativo:** Os locais de estoque são criados na aba `Local de estoque`, para mais informações [clique aqui](/erp-v2/modulos/unidades_locais_estoque/local_estoque.md).
{% endhint %}

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_local.gif)

<br>

Logo ao lado, temos o filtro por `Lançamento`, sendo duas opções clicáveis, entre saída e entrada:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_lancamento.png)

<br>

Outro filtro disponível é o de `Quantidade`, podendo utilizar a busca por quantidade com alguns filtros iguais do ID:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_qtd.png)

<br>

No filtro `Usuário Lançamento` você pode escolher um usuário em específico, podendo até ver a lista de usuários disponiveis:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_usuario.gif)

<br>

Por último, na mesma linha dos filtros, tem a **`Configuração do grid`**, ao clicar nele uma janela pop-up é aberta e então você pode redefinir os filtros utilizados, pode ser por exibição clicando no marcador, ou até alterar a ordem deles apenas clicando e arrastando! 😁

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_grid.png)

.

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_grid.gif)

<br>

Na dúvida sobre o que fazer caso fique tudo muito misturado? Fique despreocupado! Colocamos o botão `Restaurar`, e ele volta a ordem padrão automaticamente, confira abaixo o exemplo:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_grid_restaurar.png)

<br>

Você também pode pode aumentar ou diminuir o tamanho visível da coluna clicando na linha de separação, reordenar os filtros apenas clicando e movendo para a posição que você preferir e se arrastar ele para fora será oculto, confira abaixo:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_filtro_mouse.gif)

<br>

Se você observar, sempre ao **`lado direito`** de cada movimentação de estoque criada, você têm dois botões:

- <img src="/erp-v2/assets/modulos/icon_editar_item.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_excluir_item.png" alt="" data-size="line"> Excluir item.

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_editar_excluir.png)

<br>

### Botão direito mouse aba movimentação estoque

Lembrando que, em cada item mostrado, você pode usar a função secundária do mouse (Botão direito) e acessar mais opções:

- <img src="/erp-v2/assets/modulos/icon_editar_item_mouse.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> Abrir/Editar item em nova aba;
- <img src="/erp-v2/assets/modulos/icon_excluir_item_mouse.png" alt="" data-size="line"> Excluir item(s).

Você pode conferir no nosso teste abaixo:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_btn_mouse.gif)

<br>

### Paginação aba movimentação estoque

Logo na parte final fica a **`Paginação`**, onde você pode aumentar a quantidade visível de movimentações mostradas para até 1000 itens na página:

![](/erp-v2/assets/modulos/servicos/aba_servicos_paginacao.png)

<br>

### Adicionar nova movimentação de estoque

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo produto ao estoque, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/modulos/estoque_produto/aba_estoque_add.png)

<br>

Ao clicar neste botão, você será direcionado para esta página, para criar uma movimentação de estoque:

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_add_inicio.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_add_menu.png)

<br>

Olhando para criação de movimentação, quando você for criar uma nova movimentação de estoque, é ncessário preencher todos os campos marcados com o asterisco vermelho: 

- **Tipo** (Transferência, venda, compra, devolução e ajuste);
- **Data Lançamento** (Definir o dia que está sendo feita a movimentação);
- **Quantidade** (Itens a mais ou a menos);
- **Produto** (Defina qual produto terá a movimentação, para maiores informações [clique aqui](/erp-v2/modulos/produtos_servicos/produtos.md));
- **Local de Estoque** (Defina qual local está o produto, para maiores informações [clique aqui](/erp-v2/modulos/unidades_locais_estoque/local_estoque.md));
- **Empresa** (Defina qual empresa tem o produto, para maiores informações [clique aqui](/erp-v2/modulos/unidades_locais_estoque/unidades_lojas.md));
- **Lançamento** (Entrada ou saída);
- **Descrição** (Motivo da movimentação).

<br>

![](/erp-v2/assets/modulos/movimentacao_estoque/aba_movimentacao_estoque_itens.png)

<br>

Após finalizar o preenchimento você clica em **`Salvar`** e o registro da nova movimentação será adicionada:

![](/erp-v2/assets/modulos/estoque_produto/aba_estoque_add_produto_salvar.gif)

<br>