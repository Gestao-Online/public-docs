# 📦 App Sincronia da Agenda

A extensão foi criada para que os agendamentos criados no sistema sejam vinculados a vendas criadas fora dos prazos agendados (seja prazo a menos ou a mais) ou que não tenham sido feitas através da tela do agendamento (Que já trás quase todos so dados preenchidos para fazer a venda).

Ou seja, a partir do momento que você configurar esta extensão em seu Gestão Online, a cada nova venda realizada, ele fará uma busca nos agendamentos existentes dentro do período que você configurar, comparando se existe algum outro agendamento criado para este cliente. E caso exista, será automaticamente feito o vínculo da venda com o agendamento existente.

Com a extensão instalada, você precisa configurá-la clicando no botão de configuração que é exibido, conforme exemplo abaixo

![](https://github.com/Gestao-Online/public-docs/blob/e8752bd0abf7d2143f80ea0934c4850cc35ef8d5/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_02.gif?raw=true)

### Configurando a extensão

A configuração de uso desta extensão é bem simples e intuitiva. O primeiro campo para preenchimento é o  [**Tipo de agendamento**](https://docs.gestao.plus/erp-v2/funcionalidades/agendamentos_atividades/tipo_agendamentos){:target="_blank"} / <a href="[URL](https://docs.gestao.plus/erp-v2/funcionalidades/agendamentos_atividades/tipo_agendamentos)" target="_blank">Tipo de agendamento</a>, caso você ainda não tenha criado um tipo, pode conferir no nosso manual do usuário o passo a passo de criar um tipo de agendamento.

Ao clicar no campo, ele trará a lista com todos os tipos de agendamento disponíveis para uso, você então seleciona os que serão usados como base para fazer a sincronia dos agendamentos com a vendas:

![](https://github.com/Gestao-Online/public-docs/blob/e8752bd0abf7d2143f80ea0934c4850cc35ef8d5/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_03.gif?raw=true)

No segundo campo, você irá definir a quantidade de dias do intervalo de busca dos agendamentos, por exemplo, ao colocar 15 dias, no momento em que uma venda for efetuada, o sistema irá buscar na tela de agendamentos o nome deste cliente, sendo a busca feita em 15 dias antes a frente da venda feita. Caso ele encontre, a junção da venda e do agendamento é realizada automaticamente. (Caso não encontre, seguirá o fluxo padrão do sistema).

![](https://github.com/Gestao-Online/public-docs/blob/e8752bd0abf7d2143f80ea0934c4850cc35ef8d5/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_04.png?raw=true)

### Salvando as configurações

Feito isso, você pode clicar no botão salvar, e assim as configurações serão aplicadas no sistema, e a partir deste momento a extensão passa a funcionar para as novas vendas realizadas.

![](https://github.com/Gestao-Online/public-docs/blob/e8752bd0abf7d2143f80ea0934c4850cc35ef8d5/erp-v2/assets/marketplace/go_sync_agenda/extensao_agenda_sync_05.gif?raw=true)
