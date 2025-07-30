<div style="text-align: justify">

## Agendamento de movimentações

Após instalação da extensão, você precisará configurar os tipos de movimentações que terão permissão em utilizar essa funcionalidade, junto aos horários e tempo entre horários disponíveis.

<br>

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_01.png" alt="" width="800"> 
</div>

## Configurando a extensão

O primeiro campo a ser alterado é o de Tipo de Movimentação. Essa regra permite você limitar quais tipos poderão utilizar a função de criar agendamento de movimentação. Impedindo assim que outros tipos de movimentaçao, a não ser os que você definiu, sejam impedidos de utilizar a criação de agendamento de movimentação.

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_02.png" alt="Campo tipo de movimentação" width="800"> 
</div>

Na mesma sequência, defina agora o intervalo mínimo entre os agendamentos que serão criados. Vale lembrar que em cada horário que for configurar, você poderá colocar um intervalo maior do que este, caso seja necessário, porém, nunca poderá ser menor que o definido neste campo.

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_03.png" alt="Campo intervalo mínimo" width="800"> 
</div>

## Definindo os horários disponíveis

Logo abaixo você pode observar que temos a tela de horários a serem definidos. Para iniciar a inclusão de horários permitidos para agendamento, clique no ícone <img src="https://github.com/Gestao-Online/public-docs/blob/3f6427595232dc7ae5ac4604133bcea3e6ad5828/erp-v2/assets/icon_add.png?raw=true" alt="" data-size="line" width="20"> adicionar novo item.

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_04.png" alt="Incluir novo item" width="800"> 
</div>

<br>

Neste novo item criado, observe que você tem alguns campos de preenchimento obrigatório para poder prosseguir. Lembrando que sempre ao terminar de configurar, clicar no botão de salvar.

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_05.png" alt="Campos para preenchimento obrigatorio" width="800"> 
</div>

<br>

No primeiro campo, você irá definir o dia da semana referente ao horário que irá configurar na sequencia.

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_06.png" alt="Dia da semana" width="800"> 
</div>

<br>

Agora no segundo e terceiro campo, você vai determinar o horário inicial e horário final de atendimento. Vale lembrar que, você pode definir mais de um horário para o mesmo dia, apenas incluindo um novo item.

<div style="display: flex; justify-content: center; gap: 20px;">
    <img src="./assets/config_agenda_movimentacao_07.png" alt="Hora inicio" width="400">
    <img src="./assets/config_agenda_movimentacao_08.png" alt="Hora fim" width="400">
</div>

<br>

O próximo campo a ser preenchido é o de intervalo entre horários. Valendo a regra de que este intervalo pode ser preenchido com valor maior do que o determinado no campo **Intervalo mínimo para agendamentos**, e nunca abaixo.

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_09.png" alt="Intervalo mínimo para agendamentos" width="800"> 
</div>

<br>

O último item a ser configurado, são os slots disponíveis para preencher os horários. Um exemplo interssante de uso para este campo, seria com a definição da quantidade de pessoas disponíveis para atender os clientes nos horários agendados. Então conforme preenchido o exemplo, se definirmos o número 3, nós teremos três horários repetidos para utilizar, e assim sucessivamente.

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_10.png" alt="Slots disponíveis" width="800"> 
</div>

<br>

Por último, e super importante, clique no botão <img src="https://github.com/Gestao-Online/public-docs/blob/9ae7f1913e6f6776e8238b25e8fa76f0e0eead74/erp-v2/assets/icon_salvar.png?raw=true" alt="" data-size="line" width="20"> Salvar para registrar a nova configuração de horários disponíveis para uso. Observe que agora, uma nova linha com o horário disponível foi criada, e desta forma você poder seguir configurando todos os horários disponíveis que possuir.

<div style="display: flex; justify-content: center; gap: 20px;">
    <img src="./assets/config_agenda_movimentacao_11.png" alt="Hora inicio" width="400">
    <img src="./assets/config_agenda_movimentacao_12.png" alt="Hora fim" width="400">
</div>

<br>

Agora com todos os campos devidamente configurados, vamos clicar no botão **Salvar configuração** e seguir com a criação dos agendamentos.

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_13.png" alt="Salvar configuração" width="800"> 
</div>

## Criando um agendamento

Após configurado, você pode acessar uma das vendas no seu sistema Gestão Online e verificar que agora existe um novo botão disponível no menu superior (Vale frisar que o botão só está aparecendo devido o Tipo de Movimentação ter sido validado no momento da configuração explicada anteriormente).

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_14.png" alt="Botão agendamento" width="800"> 
</div>

<br>

Ao clicar neste botão, observe que uma nova janela será mostrada a você. O primeiro campo a ser preenchido é o da Data em que será realizado este agendamento. Logo após definir a data, você precisa clicar no botão **Buscar horários** para que sistema faça a verificação dos horários disponíveis no momento para agendamento, e então liberar o campo de **Horários disponíveis**, conforme mostramos no exemplo abaixo:

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_16.gif" alt="Passo a passo criar agendamento" width="800"> 
</div>

<br>

Agora voltando para a tela de Vendas no sistema, você pode observar que um novo ícone foi incluido na coluna de Status, indicando que um agendamento foi criado para aquela movimentação (Ao passar o mouse sobre o ícone, uma prévia com a data de hora do agendamento será mostrada a você)

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_17.png" alt="Coluna Status" width="800"> 
</div>

<br>

## Acessando o dashboard de Agendamento de Movimentações

Para ter uma visão geral de todos os agendamentos de movimentação criados em seu sistema Gestão Online, você pode acessar a Lupa de pesquisa no canto superior da tela, e digitar por "Dashboard - Agendamento de movimentações" e ele aparecerá na lista para você acessar.

Observe que ao clicar em um item, ele será mostrado a você em detalhes com os dados de referencia da venda. Conforme demonstramos abaixo

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_18.gif" alt="Dashboard - Agendamento de movimentações" width="800"> 
</div>

<br>

O mesmo vale para os agendamento Avulsos, ou vindos do Atendimento Express, ambos possuem uma coloração diferente para cada situação, sendo os itens de cor cinza, agendamentos avulso que você consegue criar através da tela de Vendas, ou os itens vemelhos que são criados a partir do atendimento express (Caso possua esta extensão instalada).

<div style="text-align: center">
    <img src="./assets/config_agenda_movimentacao_19.png" alt="Dashboard - Agendamento de movimentações" width="800"> 
</div>

Pronto, desta forma você pode agora utilizar a extensão Agendamento de Movimentações em seu Gestão Online!

</div>