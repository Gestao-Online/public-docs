# Tabelas de preços

Aqui estão concentradas todas as tabelas de preços utilizáveis na plataforma **Gestão.Online**, podendo cadastrar uma nova tabela, editar informações existentes e até excluir uma tabela cadastrada.

Estas tabelas serão utilizadas em cadastro de produtos, registro de vendas e repasse de comissões para parceiros.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

<br>

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_precos.gif)

<br>

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Tabela de preços.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_menu.png)

<br>

{% hint style="warning" %}
**Filtros:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](https://docs.gestao.plus/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Adicionar nova tabela de preços

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo produto, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add.png)

<br>

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_folha_pdf.png" alt="" data-size="line"> [Tabela de preço (em relatório)](https://docs.gestao.plus/erp-v2/funcionalidades/parametrizacoes/tabelas_precos#botao-tabela-de-precos-em-relatorio);
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_menu.png)

<br>

No momento da criação de uma nova tabela de preços, você precisará preencher alguns campos obrigatórios que têm o asterisco vermelho. 

Sendo eles, descrição, data vigor e modo de uso, estes itens são o mínimo necessário para poder salvar uma nova tabela de preços na nossa plataforma.

{% hint style="info" %}
**Informativo:** Mas é sempre importante lembrar de fazer o preenchimento completo dos dados de cada tabela criada! 😉👍
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_empresa.png)

<br>

Nos primeiros campos de preenchimento, você tem a descrição para explicar e definir qual tabela será criada, e logo ao lado o campo de preenchimento da data em que esta tabela entrará em vigor (começará a valer).

Nos campos abaixo, você tem disponível as opções de ativar e desativar, para os seguintes campos:

- **Tipo Tabela de Venda:** Esta tabela é destinada à venda de serviços ou produtos em um ponto de venda físico (PDV), definindo os preços e condições de venda diretamente no estabelecimento comercial;
- **Tipo Tabela de Venda Online:** Esta tabela é para vendas realizadas online, definindo os preços e condições de venda para produtos ou serviços disponibilizados em uma plataforma de e-commerce;
- **Tipo Tabela de Comissão:** Tabela referente às comissões para vendas de serviços ou produtos online, determinando as comissões que serão pagas aos vendedores por cada venda realizada online;
- **Tipo Tabela de Custo:** Esta tabela é utilizada para definir os custos de serviços ou produtos fornecidos por unidades parceiras, estabelecendo os valores que serão pagos aos parceiros pela prestação de serviços ou fornecimento de produtos;
- **Tipo Tabela de Comissão Indicador:** Tabela específica para comissões de serviços ou produtos indicados por parceiros, definindo as comissões que serão pagas aos parceiros que indicarem novos clientes ou negócios.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_campos.gif)

<br>

Nos últimos dois campos de preenchimento, há um **modo de uso** com duas opções para esta tabela:

- **Exclusivo:** Único parceiro/unidade poderá utilizar essa tabela.;
- **Compartilhado:** Mais de um parceiro poderá usar essa tabela.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_modo_uso.png)

Por último, você tem o **modo de configuração**, ele tem algumas opções, dependendo da que você precisa novos campos para preencher ficarão disponíveis. Vejamos abaixo a explicação das opções disponíveis:

- **Valor Fixo por produto/serviço:** Esta opção não possui campos adicionais para preencher;
- **Valor fixo e/ou percentual por produto/serviço de outra tabela:** Nesta opção, você precisará indicar uma tabela de preço já existente para vinculação. Precisa definir se irá computar percentual, e você pode preencher esse percentual. E por último, definir um grupo de produto para vínculo com a tabela que está criando;
    - ![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_modo_config_2.png)
- **Valor percentual da venda/movimentação:** Ao selecionar esta opção, é possível definir o percentual para cada movimentação e escolher a qual grupo de produtos ele estará vinculado;
    - - ![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_modo_config_3.png)
- **Valor da venda/movimentação subtraindo o valor produto/serviço de outra tabela:** Com este modo de configuração você define uma tabela de preço para subtrair o valor de outra tabela de produto ou serviço já criada.

<br>

## Salvando nova tabela de preços

Após finalizar o preenchimento você clica em **`Salvar`** e o registro da nova tabela de preço será salva, e estará disponível para uso:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_salvar.gif)

## Guia Itens da tabela

Assim que é criada a tabela de preços, duas guias aparecem disponíveis para uso, **itens da tabela** e **histórico**. Quando clicamos na guia de itens veremos a seguinte tela:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_guia_itens.png)

Aqui você pode adicionar itens a tabela de preços, precisando somente clicar no campo produto/serviço e começara digitar o nome para logo ele aparecer para você selecionar. Depois é só definir qual será o valor do item

{% hint style="info" %}
**Informativo:** Para adicionar um item a tabela de preços, ele precisa já estar cadastrado na aba produto/serviço! 😉👍
Caso tenha alguma dúvida sobre produto/serviço [clique aqui!](/erp-v2/funcionalidades/produtos_servicos/README.md)
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_guia_itens.gif)

## Guia histório

Na guia de histórico você tem as movimentações que foram feitas nessa tabela que você criou, seja adicionando, alterando ou removendo um item dela. Até alteração em valores, tudo ficará registrado, informando o nome do usuário que fez a alteração, assim como a data e o horário exato da modificação.

Vale lembrar que estas informações não podem ser alteradas por nenhum dos usuários ou administradores da plataforma. Essas informações garantem o bom funcionamento e integridade do ERP da **Gestão.Online**.

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_guia_historico.png)

<br>

## Botão duplicar

Vale lembrar que, no momento em que você salva uma tabela de preços na guia geral dela, o menu superior ganha novos botões.

O botão duplicar para criar uma cópia da tabela já com as configurações e produtos que você adicionou:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_menu_duplicar.png)

## Botão importar

Com o botão importar você pode trazer vários itens ao mesmo tempo, para adicionar à sua tabela de preço, podendo trazer essas informações de uma planilha:

{% hint style="warning" %}
**Filtros:** Caso queira informações sobre como utilizar as funções de importação [**`clique aqui`**](/erp-v2/primeiro_acesso/importar.md) para acessar a explicação.
{% endhint %}

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_menu_importar.png)

## Botão tabela de preços (em relatório)

Caso você queira ver um relatório PDF de todos os itens cadastrados na tabela de preços, basta um clique e será exibido para você. Observe o exemplo que fizemos abaixo:

![](/erp-v2/assets/funcionalidades/parametrizacao/aba_tabelas_add_menu_relatorio.gif)

<br>

<br>