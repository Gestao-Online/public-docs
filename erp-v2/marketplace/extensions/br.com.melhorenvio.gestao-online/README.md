<div style="text-align: justify">

### Tenha a praticidade do Melhor Envio ao seu Gestão Online

O Melhor Envio é uma plataforma que integra lojas online aos Correios e transportadoras privadas, otimizando o processo de cotar, gerar e rastrear fretes.

Com a extensão instalada, você precisa configurá-la clicando no botão de configuração que é exibido a partir do momento que você instala a extensão no sistema.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/2021042c6174305b0b2bbb567360d0afeed67359/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_05.png?raw=true" alt="0" width="600"> 
</div>

### Como funciona a integração com a Melhor Envio? 

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/2021042c6174305b0b2bbb567360d0afeed67359/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_04.png?raw=true" alt="0" width="600"> 
</div>

<br>

### Configurando API do Melhor Envio

No momento que você clicar no botão de **Configuração**, dois campos vão precisar da sua atenção, sendo eles, Cliente ID e Client Secret. Ambas informações que você só irá conseguir no momento em que já tiver o cadastro feito na plataforma do  <a href="https://melhorenvio.com.br/cadastre-se#" target="_blank">Melhor Envio</a>.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/77bef59dfb149c4707a456487f4a5d178894b3a8/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_06.png?raw=true" alt="0" width="600"> 
</div>

<br>

Com a sua conta do **Melhor Envio** criada e aberta, você precisará acessar o menu lateral esquerdo e clicar no menu *Integrações* e escolher a opção **Área Dev**. Conforme mostrado no exemplo abaixo:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/a5aef554d99b419eb4898c3e64bc50ed5274d1e8/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_07.png?raw=true" alt="0" width="600"> 
</div>

Agora, uma nova tela será mostrada a você, e será necessário **Cadastrar aplicativo**, pois será através dela que você terá acesso ao Cliente ID e Secret ID.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/8193318169e86c305e8a6ee44cad4160dee8b833/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_08.png?raw=true" alt="0" width="600"> 
</div>

### Cadastrar Aplicativo

Ao clicar em Cadastrar aplicativo, uma janela pop-up será mostrada para você preencher com os dados necessários. Mas atenção, alguns campos precisam de um certo padrão para que tudo funcione corretamente junto ao Gestão Online. Observa abaixo o metódo a ser seguido:

* **Nome da plataforma:** Integração Gestão Online - *"Nome da sua empresa"*

* **Site da plataforma:** URL do seu Gestão Online (Ex.: https://www.suaempresa.gestao.plus/loja)

* **Email de contato:** Email de contato da sua empresa (Ex.: contato@exemplo.com.br)

* **Email do seu suporte técnico:** Email de suporte da sua empresa (Ex.: suporte@exemplo.com.br)

* **URL do seu ambiente para testes:** URL de staging da loja (Ex.: https://www.suaempresa.gestao.plus/)

* **URL onde vamos direcionar o cliente após instalação (callback):** Neste campo, você irá preencher com este link padronizado para o Gestão Online, a única parte que irá modificar é a que está selecionada de laranja, para você inserir o nome utilizado no seu link de acesso (Por padrão o nome da sua empresa).<br><strong style="color: red;">*Atenção para o uso do HTTP. Caso coloque HTTPS a conexão irá falhar.*</strong><br>http://<strong style="color: orange;">suaempresa</strong>.gestao.plus/action?controller-route=8d0d3fc82f56dcbfac551bf86a8b1ba4&action=oAuth2&step=callback

* **Descrição:** Neste campo você pode inserir as anotações que desejar (Ex.: Integração com Gestão Online) 

<br>

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/8e45ef8dd7a5926122e4303aed6da1b0b93eab18/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_09.gif?raw=true" alt="0" width="600"> 
</div>

![]()

<br>

Com estar informações preenchidas corretamente, agora você pode clicar no botão **Cadastrar** e o registro das informações será feito, disponibilizando o acesso ao Client ID e Secret ID, observe abaixo:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/bb1a3430cb69461407ecbbdfc1d8613480822c7d/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_10.gif?raw=true" alt="0" width="600"> 
</div>

![]()

Agora, você precisa copiar os dois ID's para continuar a configuração da extensão no Gestão Online. O procedimento é bem simples e rápido, observe nossa demonstração abaixo:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/77bef59dfb149c4707a456487f4a5d178894b3a8/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_06.png?raw=true" alt="0" width="600"> 
</div>

</div>