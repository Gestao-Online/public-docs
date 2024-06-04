# 📊 Naturezas

Aqui você tem a visão de todas as receitas e despesas que estão diretamente relacionadas à operação do negócio e ao fluxo de caixa. Essa classificação é essencial para a análise da saúde econômica e financeira da empresa.

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Natureza.

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_menu.png)

<br>

### Filtros de naturezas

No menu de filtro você pode definir uma busca específica por naturezas, seja por ID, descrição, status e tipo. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro.gif)

<br>

Você pode fazer uso dos filtros de cada categoria que aparecem com o resultado das naturezas, no primeiro filtro você pode buscar pelo ID:

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro_id.png)

<br>

Nesta janela que se abriu, tem algumas funções importantes para abordarmos, o primeiro é o tipo de busca, com algumas opções:

- **Igual a:** Este filtro é usado para buscar registros que possuam um valor exatamente igual ao especificado. Por exemplo, se você busca por “idade igual a 30”, retornará apenas os registros com a idade exata de 30 anos;
- **Diferente de:** Com este filtro, você pode buscar registros que tenham valores diferentes do especificado. Por exemplo, se você busca por “status diferente de ‘concluído’”, retornará todos os registros com status diferentes de “concluído”.
- **Menor que:** É utilizado para buscar registros cujo valor seja menor do que o especificado. Por exemplo, se você busca por “preço menor que 100”, retornará todos os registros com preço inferior a 100.
- **Menor ou igual a:** Semelhante ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “quantidade menor ou igual a 10”, retornará registros com quantidade igual ou menor que 10.
- **Maior que:** Busca registros cujo valor seja maior do que o especificado. Por exemplo, se você busca por “receita maior que 5000”, retornará registros com receita superior a 5000.
- **Maior ou igual a:** Semelhante ao filtro anterior, mas inclui também os registros com valor igual ao especificado. Por exemplo, se você busca por “nota maior ou igual a 7”, retornará registros com nota igual ou maior que 7.
- **Dentro de:** Este filtro é usado para buscar registros cujo valor esteja dentro de um intervalo específico. Por exemplo, se você busca por “id dentro de 15 a 19”, retornará registros com id entre 15 e 19.
- **Fora de:** Similar ao filtro anterior, mas busca registros cujo valor esteja fora do intervalo especificado. Por exemplo, se você busca por “preço fora de 5 a 10”, retornará registros com preço abaixo de 5 ou acima de 10.

{% hint style="info" %}
**Informativo:** No uso do filtro **`Dentro de`** ou **`Fora de`** você precisa inserir todos os valores que ficarão dentro ou fora da busca, igual exemplo abaixo:
{% endhint %}

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro_dentrode.gif)

<br>

Depois do filtro de ID, está o filtro de **`Descrição`**, para colocar o texto que será buscado, por isso é sempre importante o preenchimento completo dos dados de cada natureza 😉👍

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro_descricao.png)

<br>

Por último os demais filtros de `Status` e `Tipo` com as opções já predefinidas que ajudam na busca:

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro_status.png)

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro_tipo.png)

<br>

Por último, na mesma linha dos filtros, tem a **`Configuração do grid`**, ao clicar nele uma janela pop-up é aberta e então você pode redefinir os filtros utilizados, pode ser por exibição clicando no marcador, ou até alterar a ordem deles apenas clicando e arrastando! 😁

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro_grid.png)

.

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro_grid.gif)

<br>

Na dúvida sobre o que fazer caso fique tudo muito misturado? Fique despreocupado! Colocamos o botão `Restaurar`, e ele volta a ordem padrão automaticamente, confira abaixo o exemplo:

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro_grid_restaurar.png)

<br>

Você também pode aumentar ou diminuir o tamanho visível da coluna clicando na linha de separação, reordenar os filtros apenas clicando e movendo para a posição que você preferir e se arrastar ele para fora será oculto, confira abaixo:

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_filtro_mouse.gif)

<br>

Se você observar, sempre ao **`lado direito`** de cada natureza criada, você têm dois botões:

- <img src="/erp-v2/assets/modulos/icon_add_item_filho.png" alt="" data-size="line"> Adicionar item dependente;
- <img src="/erp-v2/assets/modulos/icon_editar_item.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_excluir_item.png" alt="" data-size="line"> Excluir item.

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_editar_excluir.png)

<br>

### Botão direito mouse aba naturezas

Lembrando que, em cada item mostrado, você pode usar a função secundária do mouse (Botão direito) e acessar mais opções:

- <img src="/erp-v2/assets/modulos/icon_editar_item_mouse.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> Abrir/Editar item em nova aba;
- <img src="/erp-v2/assets/modulos/icon_excluir_item_mouse.png" alt="" data-size="line"> Excluir item(s).

Você pode conferir no nosso teste abaixo:

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_btn_mouse.gif)

<br>

### Paginação aba produtos

Logo na parte final fica a **`Paginação`**, onde você pode aumentar a quantidade visível de itens mostrados para até 1000 itens na página:

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_paginacao.png)

<br>

### Adicionar novo tipo de natureza

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo tipo de natureza, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_add.png)

<br>

Clicando neste botão, você será direcionado para esta página, para fazer o preenchimento das informações do novo produto.

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Ele possui as seguintes opções:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_add_menu.png)

<br>

Olhando para os campos disponíveis, por padrão, quando você for criar um novo item, é exigido descrição, status e tipo. 

- **Descrição** (Nome para identificar o novo item a ser criado);
- **Identificador** (Código de identificação gerado automaticamente por nossa plataforma);
- **Analítica** (Quando ativado, significa ser um item único, quando desativada fica disponível possuir itens dependentes);
    - ![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_add_imagem.gif)
- **Status** (Se este item estará ativou ou não);
- **Tipo** (Definir se é receita ou despesa).

<br>

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_add_itens.png)

<br>

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do novo item será salvo:

![](/erp-v2/assets/modulos/parametrizacao/aba_naturezas_add_salvar.gif)

<br>

