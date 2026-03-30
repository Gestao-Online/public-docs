# 🔀 Split de pagamentos

O Módulo de Split de Pagamento permite realizar a divisão automática de valores entre responsáveis por unidade e/ou indicadores, utilizando integração direta com o sistema de pagamentos GOPag.

Para o correto funcionamento, é obrigatório que todos os envolvidos na divisão possuam conta ativa na GOPag. Caso contrário, precisará utilizar outro método de venda, até que a situação seja regularizada.

## Instalação e Configuração dos Recursos

Após a instalação da extensão pelo marketplace do Gestão Online, o sistema passa a disponibilizar novos campos e validações em pontos específicos do ERP. Esses ajustes impactam diretamente o fluxo de configuração financeira e o processo de venda, exigindo atenção nas etapas a seguir.

### Configuração do Tipo de Negociação

A primeira configuração necessária está na tela de Tipo de Negociação, ao editar o item que deseja ativar a opção, será exibido um botão responsável por habilitar o uso do split de pagamento naquele tipo de negociação. Essa ativação é indispensável, pois determina se as vendas vinculadas a esse tipo poderão utilizar a divisão automática de valores.

<div style="text-align: center"> <img src="/erp-v2/assets/funcionalidades/financeiro/modulo_split_de_pagamentos_01.png" alt="0" width="800"> </div>

{% hint style="warning" %}
**Atenção:** Sem essa opção habilitada, o sistema não executará o split, mesmo que as demais configurações estejam corretas.
{% endhint %}

### Configuração do Tipo de Movimentação

A configuração seguinte ocorre no Tipo de Movimentação, é recomendado criar um tipo de movimentação exclusivo para operações com split, separandos dos demais métodos presentes em seu sistema.

Dentro dessa tela, alguns pontos exigem atenção. A opção de Comissão Unidade só será exibida quando a opção de Tabela de preço secundária estiver habilitada. Já a opção de Comissão de Indicador estará disponível quando a opção de permitir indicação esteja habilitado.

<div style="text-align: center"> <img src="/erp-v2/assets/funcionalidades/financeiro/modulo_split_de_pagamentos_02.gif" alt="0" width="800"> </div>

Ainda nessa configuração, o campo Configuração indicação deve obrigatoriamente estar definido como "Após baixar financeiro/confirmar pagamento", pois é nesse momento que o sistema realiza a validação da conta GOPag dos participantes do split.

Essa definição garante consistência no controle financeiro e evita problemas relacionados a estornos ou divergências no repasse de valores.

<div style="text-align: center"> <img src="/erp-v2/assets/funcionalidades/financeiro/modulo_split_de_pagamentos_03.png" alt="0" width="800"> </div>

### Configuração no Cadastro de Indicadores e Unidades

Outro ponto essencial está no cadastro dos participantes do split, sejam eles parceiros indicadores ou responsáveis por unidade. No cadastro, é necessário habilitar a opção **Participa de split**, indicando que aquele parceiro poderá receber valores provenientes da divisão.

{% hint style="info" %}
**Informação:** Para responsáveis por unidade, basta marcar essa opção, pois o sistema utilizará automaticamente a tabela de custo/comissão (Definida no Tipo de Movimentação) vinculada no momento da venda.
{% endhint %}

<div style="text-align: center"> <img src="/erp-v2/assets/funcionalidades/financeiro/modulo_split_de_pagamentos_04.png" alt="0" width="800"> </div>

Após marcar esta opção, um botão de convidar para GOPag será exibido, permitindo o envio de um convite para que o parceiro crie sua conta na plataforma de pagamentos. Essa etapa é fundamental para garantir que todos os participantes do split estejam devidamente configurados e aptos a receber os repasses financeiros. 

{% hint style="danger" %}
**Atenção:** Esse vínculo é fundamental, pois ao realizar o cadastro por esse link, a GOPag reconhece automaticamente que aquele parceiro pertence à base de um cliente específico.
{% endhint %}

<div style="text-align: center"> <img src="/erp-v2/assets/funcionalidades/financeiro/modulo_split_de_pagamentos_06.png" alt="0" width="800"> </div>

<div style="text-align: center"> <img src="/erp-v2/assets/funcionalidades/financeiro/modulo_split_de_pagamentos_09.png" alt="0" width="800"> </div>

Para parceiros indicadores, além de marcar a participação no split, é necessário configurar os campos adicionais relacionados à tabela de comissão de indicação, pois será com base nessas informações que o sistema determinará o valor a ser repassado.

{% hint style="warning" %}
**Tabela de preço:** Caso queira mais informações sobre como utilizar as tabelas preço [**`clique aqui`**](/erp-v2/funcionalidades/parametrizacoes/tabelas_precos.md).
{% endhint %}

<div style="text-align: center"> <img src="/erp-v2/assets/funcionalidades/financeiro/modulo_split_de_pagamentos_05.png" alt="0" width="800"> </div>

Além disso, todos os parceiros que possuem conta vinculada à GOPag passam a exibir uma coluna específica indicando o status da conta. Essa informação é utilizada nas validações do processo de venda.

### Processo de Venda e Validação do Split

No momento da realização da venda, o fluxo permanece o mesmo do processo padrão do sistema. O usuário deve informar os dados da venda, o parceiro indicador, conforme a regra de negócio adotada. (A unidade será preenchida automaticamente com base na configuração do usuário).

Após inserir os produtos e demais informações, ao clicar no botão de **Confirmar** da venda, o sistema executa uma validação automática dos participantes envolvidos no split.

<div style="text-align: center"> <img src="/erp-v2/assets/funcionalidades/financeiro/modulo_split_de_pagamentos_08.gif" alt="0" width="800"> </div>

Nesse momento, o sistema força uma verificação junto à GOPag para identificar se os parceiros informados possuem conta ativa. Embora exista uma rotina automática que realiza essa checagem periodicamente, a confirmação da venda dispara essa validação em tempo real.

Se os participantes estiverem com a conta ativa, o sistema atualiza automaticamente essa informação no cadastro alterando na coluna de status de Split e permite a continuidade da venda.

Caso algum dos envolvidos não possua conta ativa, o sistema interrompe o processo e exibe um modal informando que a conta GOPag ainda não foi habilitada para aquele parceiro.

### Aviso para Criação de Conta GOPag no ato da venda

Quando identificado que um parceiro não possui conta ativa, o sistema emite um aviso para criação da conta na GOPag. Esse aviso é fundamental para orientar o parceiro a regularizar sua conta e garantir que futuras vendas possam ser processadas corretamente.

<div style="text-align: center"> <img src="/erp-v2/assets/funcionalidades/financeiro/modulo_split_de_pagamentos_07.gif" alt="0" width="800"> </div>

É importante seguir o procedimento explicado no tópico "Configuração no Cadastro de Indicadores e Unidades", pois caso o parceiro crie a conta diretamente pelo site da GOPag, sem utilizar o link de convite, o processo tende a ser mais demorado para aprovação, pois não haverá vínculo com seu sistema.