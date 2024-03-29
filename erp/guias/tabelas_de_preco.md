# Tabelas de Preço

Tabelas de preços podem ser utilizadas através do sistema para precificar os produtos em diferentes modalidades de venda, pré\_pago, ecommerce, vendas normais ou os seus custos. São adicionadas dentro do cadastro das unidades para determinar o preço dos itens em cada modalidade.

Para cadastrar uma tabela de preço, procure pela página **`Tabela de preços`** através do ícone de pesquisa.

![](../../.gitbook/assets/1_tabela_de_preco.png)

Para criar uma nova tabela selecione a opção **Adicionar Item** no menu secundário padrão.

Um formulário será aberto solicitando as informações da tabela, escolha o seu nome, data em que entrará em vigor e o seus tipos. O seu tipo determinará qual a modalidade em que a tabela será utilizada e seu propósito, venda comum, venda online, custo, comissão ou comissão de indicador.

## Tipos de Tabelas de Preço

![](../../.gitbook/assets/4_tabela_de_preco_2.png)

* Tabela de Venda: Esse tipo de tabela é utilizada para determinar o preço final dos itens em uma unidade, ou seja o preço de venda para o cliente.
* Tabela de Venda Online: Utilizada para precificar os itens do ecommerce da unidade.
* Tabela de Comissão: Esse tipo de tabela é utilizada para o modelo de comissão, em que após a venda feita no **cartão** ou **boleto** a Matriz/Sede recebe o dinheiro e repassa a comissão \(determinada pela tabela\) para a Unidade.
* Tabela de Custo: Tabela usada no modelo custo, em que após a venda feita no **dinheiro** a unidade recebe o pagamento e repassa o custo do produto \(determinado pela tabela\) para a Matriz/Sede ficando com a diferenca.
* Tabela de Comissão Indicador: Essa tabela será usada para determinar o quanto um [parceiro indicador](https://github.com/Gestao-Online/public-docs/tree/acb2954355d3608fa2a0b29dfacf54ad6b8231e2/.gitbook/assets/cadastro_parceiro.md) ganhará sobre cada venda feita para um cliente indicado por ele. Após a criação da tabela, para utilizá-la, adicione-a durante o cadastro do parceiro.

**Observação Importante:** A partir das versões mais recentes também é possível selecionar o *Modo de configuração* de uma tabela, muito útil para quando estiver cadastrando tabelas de preço que serão utilizadas para comissionar seus parceiros indicadores, dentre as opções temos:
  - **Valor fixo por produto/serviço.** O valor para cada produto será cadastrado diretamente na tabela.
  - **Valor fixo e/ou percentual por produto/serviço de outra tabela.** Habilita a seção Origem/Herança.
  - **Valor percentual da venda/movimentação.** Determine os grupos de produtos dos quais será retirado o percentual definido durante a venda. Você pode utilizar esta opção quando estiver cadastrando uma tabela para comissões e deseja que o parceiro receba uma porcentagem da venda final.

## Tabelas com Origem/Herança

O sistema Gestão Online oferece flexibilidade para ajustar suas tabelas, através da seção **`Origem/Herança`** é possível cadastrar uma nova tabela da qual os preços serão os mesmos de outra tabela e também selecionar uma porcentagem para aumentar ou diminuir o valor de cada item com base em uma tabela anterior. Além disso, você também pode adicionar os mesmos itens da tabela herdada à nova porém com valores diferentes.

Por exemplo:

* Criar tabela base **A**:
  * Produto 1: R$ 100
  * Produto 2: R$ 200
* Criar tabela **B** com Origem/Herança puxando da tabela **A** com 10% a menos em cada item, a estrutura da tabela **B** ficará:

  * Produto 1: R$ 90
  * Produto 2: R$ 180

  Assim não é necessário adicionar um item de cada vez na tabela **B**.

**Por exemplo**: Cadastre uma tabela chamada `Comissão` que herde da tabela `Teste` retirando 10% do preço de cada item, então você pode adicionar um mesmo item da tabela `Teste` na tabela `Comissão` com um valor completamente diferente.

Caso queira impedir que a nova tabela herde todos os itens da anterior, adicione os itens que não deseja herdar a um grupo e selecione o grupo no campo **Grupo de produto**.

### Tabelas para comissão

Para definir quanto o parceiro irá ganhar em uma venda para cada produto, precisamos cadastrar uma tabela de preço para indicações.

Após o cadastro básico expanda a opção `Origem/Herança`, selecione a tabela que deseja usar como base para o comissionamento e selecione a opção `Computa Percentual` após selecionar essa opção digite quantos % deseja remover do preço de cada produto da tabela herdada, por exemplo, se deseja comissionar o parceiro com 15% do valor de uma venda, digite \_85% no campo `Percentual`.

![](../../.gitbook/assets/7_cliente_parceiro.png)

Apartir de agora, podemos adicionar a tabela criada aos detalhes do parceiro indicador para ele ganhar os 15% de comissão para cada cliente indicado.

## Adicionando itens a tabela

Para adicionar um item à uma tabela selecione a aba **`Itens da Tabela`** e clique no ícone `Adicionar item`.

![](../../.gitbook/assets/3_tabela_de_preco.png)

Um formulário será aberto solicitando o produto a ser adicionado e seu preço, você pode adicionar um valor fixo ou percentual.

Após determinar o valor do produto clique em `Salvar`

![](../../.gitbook/assets/4_tabela_de_preco.png)

