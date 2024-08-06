# 🧰 Serviços

Na tela "Serviços", você pode visualizar todos os produtos cadastrados na plataforma, além de ter a opção de cadastrar um novo produto/serviço, editar as informações existentes e excluir serviços cadastrados.

Aqui podem ser cadastrados os serviços que a sua empresa presta, assim ao lançar uma venda/pedido o sistema já terá as informações ligadas a esse serviço (fiscal, financeiro etc). Agilizando muito o processo de venda e/ou recorrência.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos.gif)

Nesta aba tem um menu ao lado direito da tela com as seguintes funções:

- <img src="/erp-v2/assets/icon_importar.png" alt="" data-size="line"> Importar;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar Serviço.

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_menu.png)

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Menu lateral esquerdo

No lado esquerdo da tela está o menu lateral, nele estão atalhos para outras abas da plataforma, sendo eles:

- <img src="/erp-v2/assets/funcionalidades/icon_produtos_servicos.png" alt="" data-size="line"> Todos os produtos/serviços;
- <img src="/erp-v2/assets/funcionalidades/icon_produto.png" alt="" data-size="line"> [Produtos](/erp-v2/funcionalidades/produtos_servicos/produtos.md);
- <img src="/erp-v2/assets/funcionalidades/icon_servicos.png" alt="" data-size="line"> Serviços (Aba atual);
- <img src="/erp-v2/assets/funcionalidades/icon_kits.png" alt="" data-size="line"> [Kits](/erp-v2/funcionalidades/produtos_servicos/kits.md);

Clicando no ícone da seta, você exibe de forma completa, e clicando nela novamente, volta ao modo recolhido, confira exemplo abaixo: 

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_menu_esquerdo.gif)

## Adicionar novo serviço

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo serviço, confira abaixo o procedimento para fazer a adição corretamente:

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add.png)

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento das informações do novo serviço:

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_inicio.png)

Ao lado direito da tela, você pode ver um pequeno menu na cor cinza. Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_menu.png)

Olhando para a guia **`Geral`**, por padrão, quando você for criar novo serviço, é exigido preencher a descrição, status, unidade/medida e grupo. 

- **Descrição** (Nome para identificar o novo serviço a ser criado);
- **Imagem (Principal)** (Se necessário);
    - ![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_campo_imagem.gif)
- **Descrição complementar** (Na falta de imagem, a descrição cai muito bem como opção extra);
- **Código** (SKU ou código de barras referente ao serviço);
- **Status** (Com duas opções para selecionar, entre ativado e desativado);
- **Unidade/Medida** (Serão mostradas as opções cadastradas [aqui](/erp-v2/funcionalidades/parametrizacoes/unidade_medida_produto_servico.md));
- **Grupo** (Serão mostradas as opções cadastradas [aqui](/erp-v2/funcionalidades/produtos_servicos/grupo_produto.md));
- **Valor Custo** (Aqui você declara o valor deste serviço);
- **Tipo de entrega**;
- **Utilizar configuração padrão NFSe da empresa** (Caso essa opção esteja ativada, serão utilizados os critérios fiscais Nfse padrão da empresa emitente).

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_itens.png)

## Tipo de entrega

Agora falando em específico do campo de **Tipo de entrega** ficou marcado a opção digital, mas você pode marcar a opção unidade, ou transporte. Essas informações não irão afetar o cadastro, a única que trará campos a mais será a de transporte, pois terá informações de caixa/embalagem de envio para configurar.

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_entrega_digital.png)

## Utilizar configuração padrão NFSe da empresa

Quando este campo está ativo, as configurações de NFSe são todas vínculadas ao cadastro da empresa na tela [**` Empresas`**](/erp-v2/funcionalidades/parametrizacoes/empresas.md). Por isso, no momento que ativamos esta opção, todos os demais campos de configuração de nota fiscal desaparecem.

Pois o sistema entende que esse serviço que será prestado, pode entrar na configuração padrão da NFSe (no quesito de CNAE, alíquota etc)

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_entrega_digital_nfse_empresa.gif)

## Não utilizar configuração padrão NFSe da empresa

Agora quando este campo está desativado, ficam disponíveis os campo de preenchimento para NFSe. 

Essa opção é útil quando existe algum tipo de serviço que há um enquadramento diferente de CNAE ou alíquota, permitindo que o sistema compute de forma diferente os impostos por tipo de serviço prestado. Usando por exemplo uma configuração diferente do padrão da NFSe da tela [**`Empresas`**](/erp-v2/funcionalidades/parametrizacoes/empresas.md).

Essas informações são fornecidas por seu contador, mas iremos fazer um exemplo de preenchimento.

### Campo NFSe código de serviço

Este código tem vínculo direto com a **aba LC116** que dispõe sobre o Imposto Sobre Serviços de Qualquer Natureza (ISSQN), de competência dos municípios e do Distrito Federal, e dá outras providências. Nesta aba você pode baixar todos os códigos disponíveis, ou inserí-los manualmente.

Em nosso exemplo, estamos usando o código *1.08 – Planejamento, confecção, manutenção e atualização de páginas eletrônicas*.

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_entrega_digital_nfse_codigo.png)

Logo mais abaixo no campo de **NFSe Código de tributação**, este código também é fornecido pelo seu contador. Em nosso exemplo, usamos um código nacional para o tipo de serviço que estamos criando. 

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_entrega_digital_nfse_tributacao.png)

Agora no campo de CNAE (Código Nacional de Atividade Econômica), esse código é um sistema que classifica as atividades econômicas em setores específicos. 
Logo mais abaixo no campo de **NFSe Código de tributação**, este código também é fornecido pelo seu contador. Em nosso exemplo, usamos um código nacional para o tipo de serviço que estamos criando. Para a atividade que estamos cadastrando, o CNAE geralmente utilizado é *6202-3/00 - Desenvolvimento e Licenciamento de Programas de Computador Customizáveis*.

Lembre-se, este é apenas nosso exemplo. 😁👍

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_entrega_digital_nfse_cnae.png)

No campo de **NFSe ISS Tipo Tributação**, você tem algumas opções padrões para escolher. Pois o ISS (Imposto Sobre Serviços) é um tributo municipal que incide sobre a prestação de serviços. E uma informação importante que determina como o imposto será calculado e recolhido.

Em nosso modelo de exemplo, utilizaremos a opção *Tributável dentro do município*, pois é usada quando o serviço é prestado dentro do município onde a empresa está registrada, o ISS é devido ao próprio município.

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_entrega_digital_nfse_iss.png)

O campo de **NFSe ISS Exigibilidade** refere-se às condições em que o ISS deve ser pago ou se há alguma suspensão dessa obrigação. Esse campo é importante para indicar a situação tributária do serviço prestado. 

Para o nosso caso, vamos marcar a opção *Exigível*, pois na cidade de Goiânia-GO é exigível o ISS.

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_entrega_digital_nfse_iss_exigibilidade.png)

O último campo é o de **Alíquota**, essa informação você pode encontrar no portal prefeitura da sua cidade, ou com o seu contador.

Em nosso exemplo, na cidade de Goiânia-GO, a alíquota do ISS para serviços de tecnologia da informação, como o planejamento e manutenção de páginas eletrônicas, costuma ser de 5%. Então colocaremos este valor no campo.

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_entrega_digital_nfse_iss_aliquota.png)

## Salvando novo serviço

Após finalizar o preenchimento, você clica em **`Salvar`** e o registro do novo local de estoque será salvo:

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_salvar.gif)

## Guia Itens

A partir do momento que você concluir a criação do novo serviço, ficarão disponíveis três guias para você acessar, a primeira é de `Itens`.

Nesta guia, você pode vincular um produto/serviço ao que você acabou de criar, escolhendo um dos já disponíveis e definindo a quantidade. Pode também utilizar os filtros disponíveis caso tenha muitos itens sendo exibidos. Depois é só salvar e aparecerá, confira abaixo:

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_guia_itens.gif)

## Guia Categorias

Agora, na guia de `Categorias`, você pode definir uma categoria para o serviço cadastrado. Ao clicar em adicionar, será mostrada a lista para você escolher uma opção. Essas opções já estão pré-cadastradas na aba de categoria de produto.

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre a categoria de produto, [clique aqui](/erp-v2/funcionalidades/produtos_servicos/categoria_produto.md)
{% endhint %}

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_guia_categoria.gif)

## Guia tabelas de preço

Já na guia `Tabelas de preço` é possível verificar todas as tabelas de preço que esse serviço já está vinculado, permitindo também adicionar facilmente o serviço a uma tabela de preço:

{% hint style="warning" %}
**Informativo:** Se você deseja saber mais informações sobre tabela de preço, [clique aqui](/erp-v2/funcionalidades/parametrizacoes/tabelas_precos.md)
{% endhint %}

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_add_servico_guia_tabela_preco.gif)

## Importar serviços

Esta função será de grande ajuda caso você já tenha uma lista com os serviços que deseja cadastrar. 

No botão de importação, ao clicar nele, será aberta uma janela pop-up para você fazer a importação da planilha com os dados. Logo após você importar, você define manualmente os campos relacionados para que a nossa plataforma possa fazer a importação. 

Confira abaixo o procedimento:

{% hint style="info" %}
**Informativo:** Para importação, é válido somente arquivo de planilha no formato **" .xlsx "**
{% endhint %}

![](/erp-v2/assets/funcionalidades/servicos/aba_servicos_importar.gif)