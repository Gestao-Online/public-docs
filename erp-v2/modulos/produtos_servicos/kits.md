# 🛍️ Kits de produto/serviço

Aqui você tem a visão de todos os kits de produto/serviço cadastrados na plataforma Gestão.Online, podendo cadastrar um novo kit, editar informações existentes e até excluir um kit cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem de acordo com o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

![](/erp-v2/assets/modulos/kits/aba_kits.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_importar.png" alt="" data-size="line"> Importar;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder info;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Kits.

![](/erp-v2/assets/modulos/kits/aba_kits_menu.png)

<br>

### Filtros de kits

No menu de filtro você pode definir uma busca específica por kits de produto/serviço, seja por ID, descrição, código, status e grupo. Lembrando que os filtros podem ser usados em conjunto para melhorar a sua pesquisa:

![](/erp-v2/assets/modulos/kits/aba_kits_filtro.gif)

<br>

Você pode utilizar os filtros de cada categoria que aparecem junto aos resultados dos kits. No primeiro filtro, você pode buscar pelo ID dos kits.

![](/erp-v2/assets/modulos/kits/aba_kits_filtro_id.png)

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

![](/erp-v2/assets/modulos/kits/aba_kits_filtro_dentrode.gif)

<br>

Depois do filtro de ID, está o filtro de **`Descrição`**, para colocar o texto que será buscado, por isso é sempre importante o preenchimento completo dos dados de cada kits adicionado 😉👍

![](/erp-v2/assets/modulos/kits/aba_kits_filtro_descricao.png)

<br>

Agora no filtro por **`Código`** existem três opções para você utilizar nas buscas igual ao filtro ID, sendo elas `Igual a`, `Dentro de` e `Fora de`.

![](/erp-v2/assets/modulos/kits/aba_kits_filtro_codigo.png)

<br>

Agora no filtro por **`Status`** existem duas opções para você utilizar nas buscas, sendo elas:

- Ativado;
- Desativado;

![](/erp-v2/assets/modulos/kits/aba_kits_filtro_status.png)

<br>

Outro filtro que você pode utilizar é o de `Grupo`, ele mostrará a lista de [`Grupo de produto`](/erp-v2/modulos/produtos_servicos/grupo_produto.md) com as opções que já estão definidas na aba Grupo de produto:

![](/erp-v2/assets/modulos/kits/aba_kits_filtro_grupo.gif)

<br>

Por último, na mesma linha dos filtros, tem a **`Configuração do grid`**, ao clicar nele uma janela pop-up é aberta e então você pode redefinir os filtros utilizados, pode ser por exibição clicando no marcador, ou até alterar a ordem deles apenas clicando e arrastando! 😁

![teste](/erp-v2/assets/modulos/kits/aba_kits_filtro_grid.png)

.

![](/erp-v2/assets/modulos/kits/aba_kits_filtro_grid.gif)

<br>

Na dúvida sobre o que fazer caso fique tudo muito misturado? Fique despreocupado! Colocamos o botão `Restaurar`, e ele volta a ordem padrão automaticamente, confira abaixo o exemplo:

![](/erp-v2/assets/modulos/kits/aba_kits_filtro_grid_restaurar.png)

<br>

Você também pode pode aumentar ou diminuir o tamanho visível da coluna clicando na linha de separação, reordenar os filtros apenas clicando e movendo para a posição que você preferir e se arrastar ele para fora será oculto, confira abaixo:

![](/erp-v2/assets/modulos/kits/aba_kits_filtro_mouse.gif)

<br>

Se você observar, sempre ao **`lado direito`** de cada kti criado, você têm dois botões:

- <img src="/erp-v2/assets/modulos/icon_editar_item.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_excluir_item.png" alt="" data-size="line"> Excluir item.

![](/erp-v2/assets/modulos/kits/aba_kits_editar_excluir.png)

<br>

### Botão direito mouse aba kits

Lembrando que, em cada item mostrado, você pode usar a função secundária do mouse (Botão direito) e acessar mais opções:

- <img src="/erp-v2/assets/modulos/icon_editar_item_mouse.png" alt="" data-size="line"> Editar item;
- <img src="/erp-v2/assets/modulos/icon_abrir_editar_item_nova_aba_mouse.png" alt="" data-size="line"> Abrir/Editar item em nova aba;
- <img src="/erp-v2/assets/modulos/icon_excluir_item_mouse.png" alt="" data-size="line"> Excluir item(s).

Você pode conferir no nosso teste abaixo:

![](/erp-v2/assets/modulos/kits/aba_kits_btn_mouse.gif)

<br>

# Menu lateral esquerdo

No lado esquerdo da tela está o menu lateral, nele estão atalhos para outras abas da plataforma, sendo eles:

- <img src="/erp-v2/assets/modulos/icon_produtos_servicos.png" alt="" data-size="line"> Todos os produtos/serviços;
- <img src="/erp-v2/assets/modulos/icon_produto.png" alt="" data-size="line"> [Produtos](/erp-v2/modulos/produtos_servicos/produtos.md);
- <img src="/erp-v2/assets/modulos/icon_servicos.png" alt="" data-size="line"> [Serviços](/erp-v2/modulos/produtos_servicos/servicos.md);
- <img src="/erp-v2/assets/modulos/icon_kits.png" alt="" data-size="line"> Kits (Aba atual);

Clicando no ícone da seta você exibe ele de forma completa, e clicando nela novamente, ele volta ao modo recolhido, confira exemplo abaixo: 

![](/erp-v2/assets/modulos/kits/aba_kits_menu_esquerdo.gif)

<br>

### Paginação aba produtos

Logo na parte final fica a **`Paginação`**, onde você pode aumentar a quantidade visível de kits mostrados para até 1000 itens na página:

![](/erp-v2/assets/modulos/servicos/aba_servicos_paginacao.png)

<br>

### Adicionar novo produto

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo produto, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/modulos/kits/aba_kits_add.png)

<br>

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento das informações do novo kit:

![](/erp-v2/assets/modulos/kits/aba_kits_add_inicio.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/modulos/kits/aba_kits_add_menu.png)

<br>

Olhando para a guia **`Geral`**, por padrão, quando você for criar um novo kit, é exigido descrição, status, unidade/medida e grupo. 

- **Descrição** (Nome para identificar o novo kit a ser criado);
- **Imagem (Principal)** (Para facilitar identificação do kit);
    - ![](/erp-v2/assets/modulos/kits/aba_kits_add_imagem.gif)
- **Descrição complementar** (Na falta de imagem, a descrição cai muito bem como opção extra);
- **Código** (SKU ou código de barras referente ao kit);
- **Status** (Com duas opções para selecionar, entre ativado e desativado);
- **Unidade/Medida** (Serão mostradas as opções cadastradas [aqui](/erp-v2/modulos/parametrizacoes/unidade_medida_produto_servico.md));
- **Grupo** (Serão mostradas as opções cadastradas [aqui](/erp-v2/modulos/produtos_servicos/grupo_produto.md));
- **Valor Custo** (Aqui você declara o valor deste kit);
- **Tipo de entrega:**
    - **Digital** Não mostrará as opções de NFe/NFCe;
    - **Unidade:** Não mostrará as opções de NFe/NFCe;
    - **Transporte:** Ao escolher, poderá definir as dimensões do produto, altura, largura, comprimento e peso.

<br>

![](/erp-v2/assets/modulos/kits/aba_kits_add_kit_itens.png)

<br>

Após finalizar o preenchimento você clica em **`Salvar`** e o registro do novo kit de produto/serviço será salvo:

![](/erp-v2/assets/modulos/kits/aba_kits_add_kit_salvar.gif)

<br>

A partir do momento que você concluir a criação do novo kit, ficarão disponíveis três guias para você acessar, a primeira é de `Itens`.

Nesta guia você pode vincular um produto/serviço ao kit que você acabou de criar, escolhendo um dos já disponíveis e definindo a quantidade. 

Pode também utilizar os filtros disponíveis caso tenha muitos itens sendo exibidos. Depois é só salvar e ele aparecerá, confira abaixo:

![](/erp-v2/assets/modulos/kits/aba_kits_add_kit_guia_itens.gif)

<br>

Agora na guia de `Categorias`, você pode definir uma categoria para o kit cadastrado, ao clicar em adicionar será mostrada a lista para você escolher uma opção, essas opções já estão pré cadastradas na aba categoria de produto

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre categoria de produto [clique aqui](/erp-v2/modulos/produtos_servicos/categoria_produto.md)
{% endhint %}

![](/erp-v2/assets/modulos/kits/aba_kits_add_kit_guia_categoria.gif)

<br>

Por último na guia `Tabelas de preço` você pode adicionar um valor ou percentual e de qual tabela de preço existente ele irá ser vinculado:

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre tabela de preço [clique aqui](/erp-v2/modulos/parametrizacoes/tabelas_precos.md)
{% endhint %}

![](/erp-v2/assets/modulos/kits/aba_kits_add_kit_guia_tabela_preco.gif)

<br>

### Importar kits

Esta função será de grande ajuda caso você já tenha uma lista com os serviços que deseja cadastrar. 

No botão de importação ao clicar nele será aberta uma janela pop-up para você fazer a importação da planilha com os dados, logo após, você importar ela, você define manualmente os campos relacionados para que a nossa plataforma possa fazer a importação. 

Confira abaixo o procedimento:

{% hint style="info" %}
**Info:** Para importação, é válido somente arquivo de planilha no formato **" .xlsx "**
{% endhint %}

<!-- Em conversa com o Werick, ele me explicou que está padronizado para cadastrar o tipo para SERVIÇO e que teria que alterar depois pq a demanda é maior para serviço do que para produto, por isso sempre que importar, será aplicado o tipo serviço. -->

![](/erp-v2/assets/modulos/kits/aba_kits_importar.gif)
