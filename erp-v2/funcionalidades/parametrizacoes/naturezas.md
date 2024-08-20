# 📊 Naturezas

Aqui você tem a visão de todas as receitas e despesas que estão diretamente relacionadas à operação do negócio e ao fluxo de caixa. Essa classificação é essencial para a análise da saúde econômica e financeira da empresa.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas.gif)

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Natureza.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas_menu.png)

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Adicionar novo tipo de natureza

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo tipo de natureza. Confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas_add.png)

Clicando neste botão, você será direcionado para esta página, para fazer o preenchimento das informações do novo tipo de natureza.

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Com as seguintes opções:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas_add_menu.png)

## Campos de preenchimento obrigatório

Todos os campos marcados com o asterisco vermelho precisam ser preenchidos obrigatóriamente, essas informações são essenciais para o correto funcionamento da nossa plataforma.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas_add_itens.png)

### Campo descrição e identificador

Olhando para os campos disponíveis, por padrão, quando você for criar um novo tipo de natureza, será exigido que preencha uma **Descrição** para identificar o novo item que você está criando. Será pedido tambem um código **Identificador**, mas ele é gerado automaticamente por nossa plataforma, então você não precisa se preocupar.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas_add_campos_descricao.png)

### Campo analítica

Em específico, no campo **Analítica**, caso deixe ele em ativo, a natureza criada deixa de possuir uma hierarquia. O uso da hierarquia é interessante para melhorar a identificação e separação das novas naturezas que você for adicionar, podendo definir uma como principal e as demais como dependentes.

Para melhor exemplo, veja o campo **Identificador** ele tem a sequência padrão usada em nosso sistema, neste caso 01.000.000. Caso você fizesse o cadastro de alguma natureza vínculada a esta identificada como o começo 001, os demais teriam o identificador 001.001.000, 001.002.00, 001.003.000... e assim em diante. 😁👍

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas_add_campo_analitica.gif)

Conforme o modelo abaixo, temos um exemplo de um item com itens dependentes, neste caso, a natureza receitas, possui dependentes, no caso a receita de vendas e parceiros. 

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas_add_campo_analitica_exemplo.png)

### Campos status e tipo

Nos dois últimos campos temos o de **Status** para definir se este item estará ativo ou não, e o campo de **Tipo** para você definir se essa natureza será do tipo receita ou despesa.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas_add_campo_status_tipo.png)

## Salvando nova natureza

Após finalizar o preenchimento, você clica em **`Salvar`** e o registro do novo item será salvo:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_naturezas_add_salvar.gif)

<br>

