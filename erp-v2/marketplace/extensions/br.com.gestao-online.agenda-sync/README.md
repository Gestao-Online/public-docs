<div style="text-align: justify">

## Configurando Sincronia da Agenda

A extensão foi desenvolvida para garantir que os agendamentos criados no sistema sejam sincronizados às vendas realizadas fora dos prazos estabelecidos (seja antecipadamente ou após o período agendado) ou aquelas que não foram feitas diretamente pela tela de agendamento, a qual já preenche automaticamente a maioria dos dados necessários para a venda.

Ao configurar essa extensão em seu Gestão Online, todas as novas vendas realizadas passarão por uma verificação automática. O sistema buscará, dentro do período configurado, agendamentos previamente criados para o cliente em questão. Caso algum agendamento seja encontrado, a venda será automaticamente sincronizada a ele.

Após instalar a extensão, será necessário configurá-la. Para isso, clique no botão de configuração exibido na interface, conforme o exemplo abaixo.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/e8752bd0abf7d2143f80ea0934c4850cc35ef8d5/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_02.gif?raw=true" alt="0" width="800"> 
</div>

### Configurando a extensão

A configuração de uso desta extensão é bem simples e intuitiva. O primeiro campo para preenchimento é o  <a href="https://docs.gestao.plus/erp-v2/funcionalidades/agendamentos_atividades/tipo_agendamentos" target="_blank">**Tipo de agendamento**</a>, caso você ainda não tenha criado um tipo, pode conferir no nosso manual do usuário o passo a passo de criar um tipo de agendamento.

Ao clicar no campo, ele trará a lista com todos os tipos de agendamento disponíveis para uso, você então seleciona os que serão usados como base para fazer a sincronia dos agendamentos com a vendas:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/e8752bd0abf7d2143f80ea0934c4850cc35ef8d5/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_03.gif?raw=true" alt="0" width="800"> 
</div>

No segundo campo, você deverá definir o intervalo de dias para a busca de agendamentos. Por exemplo, ao configurar 30 dias, sempre que uma venda for realizada, o sistema buscará na tela de agendamentos por registros do cliente correspondentes a até 30 dias antes ou depois da data da venda.

Se um agendamento for encontrado dentro desse intervalo, a sincronização entre a venda e o agendamento será realizada automaticamente. Caso contrário, o processo seguirá o fluxo padrão do sistema.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/e8ee06bc24312a6101147148c6238989d0a7638f/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_04.png?raw=true" alt="0" width="800"> 
</div>

### Salvando as configurações

Feito isso, você pode clicar no botão salvar, e assim as configurações serão aplicadas no sistema, e a partir deste momento a extensão passa a funcionar para as novas vendas realizadas.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/7387cc785ca10f322c256d4c770cc49a5a2c3c59/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_05.gif?raw=true" alt="0" width="800"> 
</div>

### Utilização em vendas retroativas

Após instalada a extensão, se você acessar a tela de Agendamentos, verá um novo botão disponível para uso no menu superior da tela.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/813ce113f4cad197ff7e1ef35e42705a5d2da65e/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_06.png?raw=true" alt="0" width="800"> 
</div>

Clicando nele uma janela pop-up será mostrada a você com as opções de **sincronizar de agendamento passados**. Onde você precisará definir a data de início e data de fim da busca.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/813ce113f4cad197ff7e1ef35e42705a5d2da65e/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_07.png?raw=true" alt="0" width="800"> 
</div>

O campo de **Paginação** é onde você poderá dividir o processo de sincronização em etapas menores, otimizando o tempo e o desempenho do sistema.

Por exemplo, suponha que você precise sincronizar as vendas realizadas há um ano, mas o volume de vendas nesse período é muito alto. Se optar por sincronizar o **período completo**, o sistema poderá levar um tempo considerável para concluir a operação.

Por outro lado, ao escolher opções como **Dividir por mês, semana**, ou até mesmo **a cada 3 dias**, o processo será dividido em blocos menores, permitindo uma sincronização mais ágil e eficiente. Isso reduz a sobrecarga no sistema e possibilita monitorar o progresso de forma mais clara.

*Essa flexibilidade é especialmente útil para empresas com grandes volumes de dados históricos.*

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/813ce113f4cad197ff7e1ef35e42705a5d2da65e/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_08.png?raw=true" alt="0" width="800"> 
</div>

Após clicar no botão **Sincronizar**, o sistema irá iniciar o processo e você pode aguardar até ele mostrar a mensagem de sincronização criada com sucesso

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/813ce113f4cad197ff7e1ef35e42705a5d2da65e/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_09.gif?raw=true" alt="0" width="800"> 
</div>

### Botão direito do mouse

Uma outra forma de atalho de uso da função de sincronização retroativa de vendas, ou sincronização instantânea, é o uso do botão direito do mouse ao clicar em um agendamento criado, observe que um novo botão ficarpá disponível para você utilizar e fazer a sincronia no momento que clicar sobre ele.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/f2074c91188dcbedf8091d12cff0c0bca88fb05c/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_10.gif?raw=true" alt="0" width="800"> 
</div>

O mesmo vale também para a seleção de múltiplus agendamentos, usando o modo de seleção com a tecla 'shift' teclado, e assim os itens selecionados serão sincronizados quando você clicar em sincronizar, conforme mostrado abaixo:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/f2074c91188dcbedf8091d12cff0c0bca88fb05c/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_11.gif?raw=true" alt="0" width="800"> 
</div>

</div>
