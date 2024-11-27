# Notificação automática de vencimento

O módulo de disparo automático de notificações de vencimento de agendamentos foi desenvolvido para garantir que os usuários sejam informados de forma eficaz e pontual sobre compromissos agendados que estão prestes a vencer. 

Com este recurso, o sistema monitora constantemente os prazos definidos e, quando necessário, envia notificações automáticas via e-mail, configurado para lembrar os clientes de suas responsabilidades. 

![](/erp-v2/assets/marketplace/go_notificacoes_auto/tela_marketplace_inicio.png)

Com a extensão instalada, você precisa configurá-la clicando no botão de configurações que é exibido a partir do momento que você instala a extensão no sistema.

![](/erp-v2/assets/marketplace/go_notificacoes_auto/tela_marketplace_btn_config.png)

Ao clicar em configuração, uma nova janela será mostrada a você, com as configurações do disparo automático de mensagens.

O primeiro campo é do [**`Tipo de agendamento`**](https://docs.gestao.plus/erp-v2/funcionalidades/agendamentos_atividades/tipo_agendamentos), que também é uma tela em nosso sistema. As opções mostradas neste campo já precisam estar cadastradas, você pode acompanhar nosso manual sobre como utilizar essa tela.

![](/erp-v2/assets/marketplace/go_notificacoes_auto/tela_marketplace_config_tipos_agendamento.gif)

Em seguida, o campo de **Status**, ele já vem com opções pré-definidas. Em nosso exemplo, vamos escolher a opção agendamento para que o envio de mensagem seja feito exclusivamente para estes agendamentos.

![](/erp-v2/assets/marketplace/go_notificacoes_auto/tela_marketplace_config_status.png)

Na sequência, temos a configuração da notificação, nela temos algumas opções, na primeira o botão de ativar ou não a notificação para ser enviada no final de semana, ou feriados.

![](/erp-v2/assets/marketplace/go_notificacoes_auto/tela_marketplace_config_envio_fds.png)

Você também pode definir qual horário de início e fim do envio das notificações. Durante esse período de horas que você determinar, os disparos serão feitos automaticamente.

Observe nossa demonstração abaixo, adicionamos uma função para facilitar a escolha dos horários.

![](/erp-v2/assets/marketplace/go_notificacoes_auto/tela_marketplace_config_horas.gif)

Por último, precisa somente definir quantos dias antes do vencimento irá ser enviado a notificação. Exemplos de dias: 

 - 0 - Para vencimento no dia atual;
 - 15 - Para 15 dias antes do vencimento;
 - 30 - Para 30 dias antes do vencimento.

{% hint style="info" %}
**Informativo:** Quando for digitar o valor, pressione a tecla **Enter** para que o número seja validado.
{% endhint %}

Observe nossa demonstração abaixo, inserindo os valores **0**, **15** e **30**.

![](/erp-v2/assets/marketplace/go_notificacoes_auto/tela_marketplace_config_dias_vencimento.gif)

Agora é só você clicar no botão **`Salvar configuração`** e pronto, os disparos automáticos serão feitos! 😁