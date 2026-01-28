# 📦 App Atendimento Express - Soluti

Aplicação desenvolvida para integração com SisAR e V.Line, permitindo, de forma prática durante a venda, fazer o agendamento da videoconferência do cliente ou entrar na fila de atendimento e, em poucos minutos, ser atendido.

A solução permite essa integração com as ferramentas da Soluti, agilizando as vendas de certificados digitais.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/a3f10d02e4fb6a66948e4223418c985636b1a55c/erp-v2/assets/marketplace/atendimento_express_soluti/extensao_atendimento_express_02.png?raw=true" alt="0" width="800"> 
</div>

<br>

## Como configurar?

Ao clicar no ícone de configurações, você verá algumas definições que podem ser aplicadas a esta extensão. O primeiro campo você irá definir o tipo de plano que irá utilizar, sendo eles:

- **Gratuito:** Fluxo padrão de atendimento, usando o sistema de preenchimento de dados através do envio da foto do documento, e criação obrigatória da senha, e atendimento indo para fila padrão do V.Line.
- **Premium:** Fluxo personalizado de atendimento, podendo remover a solicitação de foto do documento, definindo uso da consulta via SERPRO, podendo escolher fila de atendimento personalizada, e até remover a solicitação de senha de emissão antes de criar o agendamento.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/f61b361401d708fe77fb6375a0238498dc94a406/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_02_01.png?raw=true" alt="0" width="500"> 
</div>

No campo Tipo de Movimentação, é possível selecionar quais podem ter permissão de exibir o botão de Atendimento Express na venda (Vale lembrar que este botão só ficará disponível para uso quando a entrega do produto estiver liberada).

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/f61b361401d708fe77fb6375a0238498dc94a406/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_02_02.png?raw=true" alt="0" width="500"> 
</div>

Logo abaixo, você possui três campos que pode deixar habilitado, ou desabilitar, isso irá depender da forma como for conduzir o atendimento.

No primeiro botão, caso fique habilitado, será solicitado que envie a foto da CNH ou RG da pessoa que será atendida, dessa forma o nosso sistema fará leitura dos dados, e preencherá os campos principais para prosseguir.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/f61b361401d708fe77fb6375a0238498dc94a406/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/fluxo-certificado-soluti.gif?raw=true" alt="0" width="200"> 
</div>

No segundo, caso habilitado, será solicitado a criação de uma senha antes de prosseguir com o agendamento ou atendimento. Caso desabilitado, não terá necessidade de senha até o momento da videoconferência.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_18.png?raw=true" alt="0" width="200"> 
</div>

No terceiro, caso habilitado, você poderá incluir filas de atendimento customizadas, podendo separar por Unidades, incluindo o token especifico de cada fila de atendimento do V.Line.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/f61b361401d708fe77fb6375a0238498dc94a406/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_02_03.gif?raw=true" alt="0" width="500"> 
</div>

No último campo para configuração, determina se será feito consultas no Serpro para obter os dados da empresa e se será feito consulta no DATA VALID para verificação dos dados do sócio ou do titular do certificado digital, desta forma agilizando o processo de preenchimento dos dados. São duas opções:

- **Gestão Online:** Usando esta opção você irá utilizar o sistema de consultas do próprio Gestão Online, não precisando configurar nenhum item a mais, apenas começar a usar, e as consultas serão feitas tanto para CPF quanto para CNPJ.
- **Próprio:** Este contrato é recomendado quando você já possui acesso de consultas no SERPRO, sendo necessário inclusão do ClientID e ClientSecret para habilitar o uso.

<div style="text-align: center">
    <img src="erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_02_04.gif" alt="0" width="200"> 
</div>

## Como funciona?

Uma vez instalado no sistema, você pode efetuar a venda de um certificado digital e, no momento em que a entrega for liberada, conforme a configuração definida no tipo de movimentação, pode atualizar a página da venda e o botão **Atendimento Express** ficará disponível para uso.

Observe abaixo o procedimento de exibição. Para nosso teste, a entrega será liberada após a baixa do financeiro; para isso, iremos forçar a baixa do valor de um boleto.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/a3f10d02e4fb6a66948e4223418c985636b1a55c/erp-v2/assets/marketplace/atendimento_express_soluti/extensao_atendimento_express_03.gif?raw=true" alt="0" width="800"> 
</div>

<br>

Observe que, após o valor ser baixado e a página atualizada, o botão passa a ficar disponível para utilização. Ao clicar neste botão, uma janela será exibida com um link que o levará à tela de agendamento da Soluti. Você pode copiar essa URL e abrir no próprio navegador, ou enviá-la por e-mail ou WhatsApp para o cliente.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/a3f10d02e4fb6a66948e4223418c985636b1a55c/erp-v2/assets/marketplace/atendimento_express_soluti/extensao_atendimento_express_04.png?raw=true" alt="0" width="800"> 
</div>

<br>

Agora, com o link copiado, você pode abri-lo em um navegador e seguir os passos solicitados, podendo continuar o processo pelo celular ou pelo computador. Em nosso exemplo, colamos a URL no navegador e aguardamos o carregamento das informações para seguir com a validação do certificado.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/a3f10d02e4fb6a66948e4223418c985636b1a55c/erp-v2/assets/marketplace/atendimento_express_soluti/extensao_atendimento_express_05.gif?raw=true" alt="0" width="800"> 
</div>

<br>

Após clicar em **Continuar por aqui** ou usar a opção de QR Code para prosseguir pelo celular, você será encaminhado para a tela de confirmação dos termos e condições da Política de Privacidade. Clicando no ícone **Eu concordo com os Termos e Condições da Política de Privacidade**, você poderá clicar em **Começar** para iniciar o processo de emissão.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_07.png?raw=true" alt="0" width="400"> 
</div>

<br>

Iniciando o processo de emissão, será exibida a tela **Titular do certificado**. Esta tela apresentará os dados do titular que constam no cadastro dele no Gestão Online. Caso haja alguma inconsistência nos dados, é possível alterar o titular clicando em **Alterar titular**. Caso clique nesse botão, você será redirecionado para uma tela onde precisará apenas informar o CNPJ e, em seguida, retornará para a tela **Titular do certificado**. Para prosseguir com o atendimento, basta clicar em **Continuar**.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_08.png?raw=true" alt="0" width="400"> 
</div>

<br>

Após confirmar os dados, você é direcionado para a tela de seleção do **Responsável Legal**. Nela será apresentado o responsável legal do CNPJ informado na venda e seu respectivo CPF. Caso o CNPJ tenha mais de um responsável legal relacionado a ele, todos serão listados para que um seja selecionado. Ao selecionar o responsável, você poderá prosseguir para a próxima etapa.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_09.png?raw=true" alt="0" width="400"> 
</div>

<br>

A tela seguinte informa que, caso você possua qualquer certificado em nuvem válido, é possível utilizá-lo para emitir um novo. Vamos prosseguir o guia primeiramente em um cenário onde não há certificado em nuvem e, posteriormente, utilizando um certificado existente.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_10.png?raw=true" alt="0" width="400"> 
</div>

<br>

Ao selecionar a opção de nova videoconferência, você é redirecionado para a tela de seleção entre **Atendimento VIP** ou **Agendamento**. Nela, é possível escolher entre entrar na fila diretamente para atendimento, caso a AR possua o VLine, clicando em **Entrar na fila**, ou realizar o agendamento conforme os horários disponíveis.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_11.png?raw=true" alt="0" width="400"> 
</div>

<br>

Caso selecione a opção de entrar na fila de atendimento de forma imediata, será exibida uma mensagem informando que sua solicitação está na fila, juntamente com o protocolo, número do pedido e número da solicitação. Clicando em **Clique aqui para abrir a videoconferência**, você será encaminhado à videoconferência para concluir o processo de emissão do certificado.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/f61b361401d708fe77fb6375a0238498dc94a406/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_12.png?raw=true" alt="0" width="400"> 
</div>

<br>

Caso opte por agendar a videoconferência, no campo abaixo serão apresentados os horários cadastrados no VLine, disponíveis para a conclusão do processo de emissão. É possível selecionar um horário no dia atual ou consultar os horários disponíveis em outra data clicando em **Buscar horários**. Após selecionar a data e o horário desejado, basta confirmar o agendamento.

<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_13.png?raw=true" alt="0" width="300">

  <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_14.png?raw=true" alt="0" width="300">

  <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_15.png?raw=true" alt="0" width="300">
</div>

<br>

Após concluir o agendamento, você receberá uma mensagem de confirmação juntamente com o protocolo, a data e o horário do agendamento da videoconferência, número do pedido e número da solicitação. A mensagem também informa que o link da videoconferência foi enviado por e-mail.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/f61b361401d708fe77fb6375a0238498dc94a406/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_16.png?raw=true" alt="0" width="400"> 
</div>

<br>

Agora, partindo de um cenário de emissão do certificado digital utilizando um certificado em nuvem, você pode clicar na opção **Usar o certificado digital em nuvem** para iniciar o processo.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_17.png?raw=true" alt="0" width="400"> 
</div>

<br>

Você será direcionado para a tela de criação da senha de emissão e revogação do seu Certificado Digital. É muito importante salvar esta senha, pois ela será utilizada para emitir e revogar o certificado posteriormente.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_18.png?raw=true" alt="0" width="400"> 
</div>

<br>

Em seguida, será exibida a senha cadastrada para que você possa salvá-la de alguma forma.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_19.png?raw=true" alt="0" width="400"> 
</div>

<br>

Na próxima etapa, serão exibidos alguns dos principais certificados digitais em nuvem disponíveis. Você deve selecionar qual será utilizado e clicar em **Autenticar**.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/128d7018e50d02b28c9d26d3ec5a83089b7bffcd/erp-v2/marketplace/extensions/br.com.atendimento-express.gestao-online/assets/extensao_atendimento_express_20.png?raw=true" alt="0" width="400"> 
</div>

<br>

Você será direcionado à página referente ao seu certificado, onde, após preencher seus dados e o token correspondente, o certificado solicitado será avaliado para aprovação. Caso seja aprovado, você receberá um e-mail de confirmação do Termo de Titularidade.