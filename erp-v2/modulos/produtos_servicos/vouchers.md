# 🎟️ Vouchers

Aqui você tem a visão de todos os vouchers cadastrados na plataforma Gestão.Online, podendo cadastrar um novo voucher, editar os existentes e até excluir um voucher cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/modulos/vouchers/aba_vouchers.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Voucher.

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_menu.png)

<br>

### Filtros de vouchers

No menu de filtro você pode definir uma busca específica por vouchers, seja por ID, produto e status. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_filtro.gif)

<br>

Você pode fazer uso dos filtros de cada categoria que aparecem com o resultado dos vouchers, no primeiro filtro você pode buscar pelo ID do voucher:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_filtro_id.png)

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

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_filtro_dentrode.gif)

<br>

Agora no filtro por **`Status`** existem duas opções para você utilizar nas buscas, sendo elas:

- Ativado;
- Desativado;

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_filtro_status.png)

<br>

Por último, na mesma linha dos filtros, tem a **`Configuração do grid`**, ao clicar nele uma janela pop-up é aberta e então você pode redefinir os filtros utilizados, pode ser por exibição clicando no marcador, ou até alterar a ordem deles apenas clicando e arrastando! 😁

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_filtro_grid.png)

.

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_filtro_grid.gif)

<br>

Na dúvida sobre o que fazer caso fique tudo muito misturado? Fique despreocupado! Colocamos o botão `Restaurar`, e ele volta a ordem padrão automaticamente, confira abaixo o exemplo:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_filtro_grid_restaurar.png)

<br>

Você também pode aumentar ou diminuir o tamanho visível da coluna clicando na linha de separação, reordenar os filtros apenas clicando e movendo para a posição que você preferir e se arrastar ele para fora será oculto, confira abaixo:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_filtro_mouse.gif)

<br>

Se você observar, sempre ao **`lado direito`** de cada serviço criado, você tem dois botões:

- <img src="/erp-v2/assets/modulos/icon_editar_item.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_excluir_item.png" alt="" data-size="line"> Excluir item.

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_editar_excluir.png)

<br>

### Botão direito mouse aba vouchers

Lembrando que, em cada item mostrado, você pode usar a função secundária do mouse (Botão direito) e acessar mais opções:

- <img src="/erp-v2/assets/modulos/icon_editar_item_mouse.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> Abrir/Editar item em nova aba;
- <img src="/erp-v2/assets/modulos/icon_excluir_item_mouse.png" alt="" data-size="line"> Excluir item(s).

Você pode conferir no nosso teste abaixo:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_btn_mouse.gif)

<br>

### Paginação da aba vouchers

Logo na parte final fica a **`Paginação`**, onde você pode aumentar a quantidade visível de vouchers mostrados para até 1000 itens na página:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_paginacao.png)

<br>

### Adicionar novo voucher

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo voucher, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add.png)

<br>

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento das informações do novo voucher:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_inicio.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_cadeado.png" alt="" data-size="line"> Restrições/Exceções;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_menu.png)

<br>

Quando você for criar um voucher, é exigido produto, status e permissão de produto secundário. 

- **Produto:** Você pode escolher um dos produtos disponíveis na lista, ou digitar o nome dele para selecionar;
- **Status:** Aqui você define se o voucher estará ativado ou desativado;
- **Permite produto secundário:** Caso você ative esta opção, poderá vincular outro produto ao voucher.

<br>

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_voucher_itens.png)

<br>

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do novo voucher será salvo:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_voucher_salvar.gif)

<br>

Ainda falando do menu dessa aba temos <img src="/erp-v2/assets/icon_cadeado.png" alt="" data-size="line"> o ícone de restrições/exceções, quando clicamos nele, uma janela pop-up será aberta com algumas configurações disponíveis para você preencher:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_restricoes.png)

São três campos para preenchimento das informações, sendo eles o tipo de movimentação, unidade e vendedor, e cada um tendo ao lado a opção para definir, que tipo de restrição terá, das opções sem restrições,  restrição (Só pode ser utilizado com) e exceção (Só não pode ser utilizado com)

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_restricoes2.png)

Observe que após salvar as informações, a janela `Voucher Item` passará a ficar disponível, nela temos outro menu:

- <img src="/erp-v2/assets/icon_importar.png" alt="" data-size="line"> Importar códigos;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Exibir informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar código;

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_menu_guia_itens.png)

<br>

Na primeira opção do menu, temos o `Importar códigos` com ele você pode pegar uma lista de código pronta e fazer a importação direta para nossa plataforma, com apenas alguns cliques, observe:

{% hint style="warning" %}
**Atenção:** O formato de arquivo aceito para essa importação é **" .txt "**, confira antes de tentar fazer a importação.
{% endhint %}

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_importar.gif)

<br>

Mas caso queira, pode fazer a inserção do código de voucher manualmente, é bem rápido e prático, dá uma olhadinha aqui abaixo 😁

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_codigo.gif)

<br>

Não esqueça que são duas guias, a primeira de itens, onde adicionamos os códigos dos vouchers e a segunda de histórico de uso do nosso voucher.

Esse histórico trás ID, código, movimentação, se está disponível para uso e a data/hora que foi utilizado:

![](/erp-v2/assets/modulos/vouchers/aba_vouchers_add_guia_historico.png)
