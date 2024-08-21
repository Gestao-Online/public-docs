# 🏭 Local de estoque

Aqui você tem a visão de todos os locais de estoque cadastrados na plataforma, podendo fazer cadastro, editar informações, adicionar item dependente e até excluir um estoque cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/estoque/aba_estoque.gif)

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Unidade/Loja;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro.

![](/erp-v2/assets/funcionalidades/estoque/aba_estoque_menu.png)

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Adicionar novo local de estoque

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo local de estoque. Confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/funcionalidades/estoque/aba_estoque_add.png)

### Menu superior

Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar novo local de estoque;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/estoque/aba_estoque_add_menu.png)

### Campo descrição, e status

Olhando para a aba **`Geral`**, por padrão, quando você for criar um local de estoque é exigido descrição, identificador e status. Em **Descrição**, você define um nome ao local de estoque que está sendo cadastrado no momento, o campo **Identificador**, é gerado um código padrão que será usando para identificar este local de estoque em nossa plataforma. E o campo de **Status** você tem duas opções para selecionar, entre ativado para o local de estoque ficar ativa e disponível, e inativo para que ele deixe de funcionar.

![](/erp-v2/assets/funcionalidades/estoque/aba_estoque_add_unidade_itens.png)

### Campo Analítica e identificador

Em específico, no campo **Analítica**, caso deixe ele em ativo, o local de estoque criado deixa de possuir uma hierarquia. O uso da hierarquia é interessante para melhorar a identificação e separação de novos locais de estoque que você for adicionar, podendo definir um como principal e os demais como dependentes, pois a regra aplicada ao principal é repassada para os dependentes automaticamente.

Para melhor exemplo, veja o campo **Identificador** ele tem a sequência padrão usada em nosso sistema, neste caso 01.00. Caso você fizesse o cadastro de algum local de estoque vínculado a este local de estoque identificado como 01, os demais teriam o identificador 01.01, 01.02, 01.03... e assim em diante. 😁👍

![](/erp-v2/assets/funcionalidades/estoque/aba_estoque_add_btn_analitica.gif)

## Salvando novo local de estoque

Após finalizar o preenchimento, você clica em **`Salvar`** e o registro do novo local de estoque será salvo:

![](/erp-v2/assets/funcionalidades/estoque/aba_estoque_add_unidade_salvar.gif)

### Aba Movimentações/Transferências

A partir do momento que você concluir a criação, uma nova guia ficará disponível, a de `Movimentações/Transferências`, e aqui serão mostradas todas as transferências, vendas,  compras, devoluções e ajustes. Esta aba não sofre alterações ou remoções, pois é ligada direto ao sistema e isso atrapalharia sua integridade. 

Observe também que esta aba é similar a tela de **Movimentação Estoque**, porém, trazendo somente as informações deste estoque que você criou.

{% hint style="warning" %}
**Tela Movimentações estoque:** Se você deseja saber mais informações sobre Movimentações de estoque, [clique aqui](/erp-v2/funcionalidades/produtos_servicos/movimentacao_estoque.md)
{% endhint %}

![](/erp-v2/assets/funcionalidades/estoque/aba_estoque_add_unidade_guia_movimentacao.gif)