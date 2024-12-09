# 🔂 Controle movimentação unidade

{% hint style="danger" %}
<img src="https://cdn-icons-png.flaticon.com/512/9967/9967681.png" alt="" data-size="line"> Esta tela é contratada a parte pelo [Marketplace](/erp-v2/marketplace/inicio.md) do Gestão Online, entre em contato com o nosso time [Comercial](https://api.whatsapp.com/send?phone=556237735650&text=Ol%C3%A1%20gostaria%20de%20mais%20informa%C3%A7%C3%B5es%20sobre%20o%20marketplace%20do%20Gest%C3%A3o.Online) para maiores informações.
{% endhint %}

Nesta tela você encontra todos os controles de movimentação de unidade cadastrados na plataforma.  

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_ctrl_movimentacao.gif)

Nesta tela tem um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar novo controle de movimentação.

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros de busca [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md).
{% endhint %}

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse, [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse).
{% endhint %}

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_ctrl_movimentacao_menu.png)

## Entendendo melhor o controle de movimentação

O controle de movimentação funciona de forma semelhante a um "extrato de um banco" de uma conta corrente por exemplo, onde a cada lançamento ocorre uma entrada (Crédito) ou uma saída (Débito), e sempre é recomputado o saldo atual.

Caso seja necessário algum ajuste no saldo, ou o lançamento de alguma despesa ou receita diretamente no controle da unidade, é possível adicionar um novo lançamento manualmente (explicado logo abaixo), entre crédito ou débito, e o valor deste lançamento. Após salvar, ele aparecerá no "extrato" imediatamente já recomputando o saldo. 😁

Mas lembre-se, normalmente essas movimentações de crédito ou débito, são programadas para serem geradas automaticamente por nossa plataforma, atráves de fluxos de comissão ou custo que são disparados atráves de rotinas financeiras, ou de movimentações das vendas por exemplo.

## Adicionar novo controle de movimentação

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar um novo controle de movimentação. Confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_ctrl_movimentacao_add.png)

Após clicarmos no botão adicionar novo controle de movimentação, uma nova página será aberta e, Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;   
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

No momento do cadastro de um novo controle de movimentação de unidade, você precisará preencher alguns campos obrigatórios que têm o asterisco vermelho. 

{% hint style="info" %}
**Informativo:** É sempre importante lembrar de fazer o preenchimento completo dos dados desse contrato e verificar com atenção o lançamento. 😉👍
{% endhint %}

{% hint style="warning" %}
**Atenção:** Esse lançamento não permite correção. Pois assim como um "extrato" bancário uma vez lançado, não é possível remover/alterar. Então se por exemplo, alguém envia um PIX para a sua conta por engano, não há como desfazer aquela entrada no extrato, mesmo que você devolva, aquela linha da entrada e saída continuaram aparecendo no extrato. (Inclusive, caso isso ocorra, recomendamos que seja feito uma operação inversa para reverter a alteração que está tentando ser cancelada)
{% endhint %}

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_ctrl_movimentacao_add_controle.png)

O campo **tipo lançamento**, tem duas opções para você escolher, entre *crédito* ou *débito*. Para nosso exemplo, vamos usar a opção de crédito.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_ctrl_movimentacao_add_campo_lancamento.png)

Logo ao lado, temos o campo **Unidade**, lembre-se de que ele está vinculado com a **Tela Unidade** e as opções que ele trará são as cadastradas nesta tela. 😁 (Pode ser que esse campo não apareça, caso você usando essa tela a partir de uma "Aba" dentro da tela que já está referenciando uma unidade/contrato)

{% hint style="warning" %}
**Tela Unidades:** Caso queira mais informações sobre como utilizar a tela Unidades, [**`clique aqui`**](/erp-v2/funcionalidades/unidades_locais_estoque/unidades_lojas.md).
{% endhint %}

Em nosso exemplo, vamos escolher a opção **SEDE/MATRIZ**. Observe abaixo:

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_unidade.gif)

Os demais campos são de **valor** e **histórico**, lembrando que o valor é um item obrigatório e precisa ser preenchido corretamente. Já o campo de histórico não é obrigatório, mas é importante seu preenchimento em situações manuais como essa que estamos fazendo de exemplo. (Para que seja mantido a rastreabilidade, e o motivo do lançamento da operação de crédito ou débito, que terá efeito imediato no saldo da unidade)

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_campo_valor_historico.png)

Após fazer o preenchimento dos dados do novo controle, você pode clicar no ícone <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> de salvar.

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_add_salvar.gif)

Uma informação importante para os gestores da empresa, esse controle de movimentação tem interação direta com a **Tela  contrato do controle de unidade**. Observe abaixo que a movimentação que criamos aqui como exemplo já consta no contrato criado no exemplo da tela. Veja abaixo:

![](/erp-v2/assets/funcionalidades/controle_unidades/aba_contrato_aba_movimentacao.gif)

<br>

<br>