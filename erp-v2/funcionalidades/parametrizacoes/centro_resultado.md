# 💰 Centro de Resultado

Neste local, você pode visualizar todos os centros de resultados que estão diretamente ligados às operações do negócio e ao financeiro. Isso permite uma análise mais detalhada das origens das receitas e despesas geradas pela unidade, conforme o centro de resultados selecionado.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_centro_resultado.gif)

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar centro de resultado.
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_centro_resultado_menu.png)

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Adicionar novo tipo de natureza

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo centro de resultado. Confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_centro_resultado_add.png)

Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar item filho.
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_centro_resultado_add_menu.png)

## Campos obrigatórios

No momento do cadastro de um novo centro de resultado, você precisará preencher alguns campos obrigatórios que têm o asterisco vermelho. 

Sendo a descrição, identificador e status, estes itens são o mínimo necessário para poder salvar um novo centro de resultado.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_centro_resultado_add_centro.png)

### Campo descrição e identificador

Olhando para os campos disponíveis, por padrão, quando você for criar um novo centro de resultado, será exigido que preencha uma **Descrição** para identificar o novo item que você está criando. Será pedido tambem um código **Identificador**, mas ele é gerado automaticamente por nossa plataforma, então você não precisa se preocupar.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_centro_resultado_add_campos_descricao_identificador.png)

### Campo analítica

Em específico, no campo **Analítica**, caso deixe ele em ativo, o centro de resultado criado deixa de possuir uma hierarquia. O uso da hierarquia é interessante para melhorar a identificação e separação de novos centros de resultado que você for adicionar, podendo definir um como principal e os demais como dependentes.

Para melhor exemplo, veja o campo **Identificador** ele tem a sequência padrão usada em nosso sistema, neste caso 001.000.000. Caso você fizesse o cadastro de algum centro de resultado vínculada a este identificado com o começo 001, os demais teriam o identificador 001.001.000, 001.002.00, 001.003.000... e assim em diante. 😁👍

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_centro_resultado_add_menu.gif)

Conforme o modelo abaixo, temos um exemplo de um item com itens dependentes, neste caso, o centro de resultado, possui dependentes, um deles é o administrativo, e esse adminsitrativo também possui itens dependentes, como financeiro, departamento pessoal e etc.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_centro_resultado_add_campo_analitica_exemplo.png)

## Salvando centro de resultado

Após finalizar o preenchimento, você clica em **`Salvar`** e o registro do novo centro de resultado será salvo:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_centro_resultado_add_salvar.gif)

<br>