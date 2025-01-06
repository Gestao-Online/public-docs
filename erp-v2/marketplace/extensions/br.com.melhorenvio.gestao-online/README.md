<div style="text-align: justify">

### Tenha a praticidade do Melhor Envio ao seu Gestão Online

O Melhor Envio é uma plataforma que integra lojas online aos Correios e transportadoras privadas, otimizando o processo de cotar, gerar e rastrear fretes.

Com a extensão instalada, você precisa configurá-la clicando no botão de configuração que é exibido a partir do momento que você instala a extensão no sistema.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/2021042c6174305b0b2bbb567360d0afeed67359/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_05.png?raw=true" alt="0" width="800"> 
</div>

<br>

### Como funciona a integração com a Melhor Envio? 

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/2021042c6174305b0b2bbb567360d0afeed67359/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_04.png?raw=true" alt="0" width="800"> 
</div>

<br>

### Configurando API do Melhor Envio

No momento que você clicar no botão de **Configuração**, dois campos vão precisar da sua atenção, sendo eles, Cliente ID e Client Secret. Ambas informações que você só irá conseguir no momento em que já tiver o cadastro feito na plataforma do  <a href="https://melhorenvio.com.br/cadastre-se#" target="_blank">Melhor Envio</a>.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/77bef59dfb149c4707a456487f4a5d178894b3a8/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_06.png?raw=true" alt="0" width="800"> 
</div>

<br>

Com a sua conta do **Melhor Envio** criada e aberta, você precisará acessar o menu lateral esquerdo e clicar no menu *Integrações* e escolher a opção **Área Dev**. Conforme mostrado no exemplo abaixo:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/a5aef554d99b419eb4898c3e64bc50ed5274d1e8/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_07.png?raw=true" alt="0" width="800"> 
</div>

Agora, uma nova tela será mostrada a você, e será necessário **Cadastrar aplicativo**, pois será através dela que você terá acesso ao Cliente ID e Secret ID.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/8193318169e86c305e8a6ee44cad4160dee8b833/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_08.png?raw=true" alt="0" width="800"> 
</div>

### Cadastrar Aplicativo

Ao clicar em Cadastrar aplicativo, uma janela pop-up será mostrada para você preencher com os dados necessários. Mas atenção, alguns campos precisam de um certo padrão para que tudo funcione corretamente junto ao Gestão Online. Observa abaixo o metódo a ser seguido:

* **Nome da plataforma:** Integração Gestão Online - *"Nome da sua empresa"*

* **Site da plataforma:** URL do seu Gestão Online (Ex.: https://www.suaempresa.gestao.plus/loja)

* **Email de contato:** Email de contato da sua empresa (Ex.: contato@exemplo.com.br)

* **Email do seu suporte técnico:** Email de suporte da sua empresa (Ex.: suporte@exemplo.com.br)

* **URL do seu ambiente para testes:** URL de staging da loja (Ex.: https://www.suaempresa.gestao.plus/)

* **URL onde vamos direcionar o cliente após instalação (callback):** Neste campo, você irá preencher com este link padronizado para o Gestão Online, a única parte que irá modificar é a que está selecionada de laranja, para você inserir o nome utilizado no seu link de acesso (Por padrão o nome da sua empresa).<br><div style="background-color:rgb(252, 227, 227); border-left: 6px solid rgb(255, 62, 62); padding: 15px; margin: 20px 0; border-radius: 5px; color: #333; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);"><h4 style="margin: 0 0 10px; font-size: 1.2em; color: #555;">⚠️ Atenção:</h4><p style="margin: 0; line-height: 1.5;">Neste link, é necessário fazer uso somente do HTTP. Caso coloque HTTPS a conexão irá falhar, observe:.<br>http://<strong>suaempresa</strong>.gestao.plus/action?controller-route=8d0d3fc82f56dcbfac551bf86a8b1ba4&action=oAuth2&step=callback</p></div>

* **Descrição:** Neste campo você pode inserir as anotações que desejar (Ex.: Integração com Gestão Online) 

<br>

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/8e45ef8dd7a5926122e4303aed6da1b0b93eab18/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_09.gif?raw=true" alt="0" width="800"> 
</div>

<br>

Com estar informações preenchidas corretamente, agora você pode clicar no botão **Cadastrar** e o registro das informações será feito, disponibilizando o acesso ao Client ID e Secret ID, observe abaixo:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/bb1a3430cb69461407ecbbdfc1d8613480822c7d/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_10.gif?raw=true" alt="0" width="800"> 
</div>

<br>

Agora, você precisa copiar os dois ID's, colar nos campos da tela de configuração e salvar as informações da extensão no Gestão Online. O procedimento é bem simples e rápido, observe nossa demonstração abaixo:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/ad63b587018c7640b3fda75352962614b39d2232/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_11.gif?raw=true" alt="0" width="800"> 
</div>

<br>

### Autorização do Aplicativo

Depois de salvar os dados, você precisa acessar novamente as configurações e clicar no botão **Fazer login**. Uma nova janela será mostrada a você para preencher os dados de envio da sua empresa e escolher as empresas de envio disponíveis.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/a1bf8699127beddb25cf80038ea1e219216389a2/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_12.gif?raw=true" alt="0" width="800"> 
</div>

<br>

Nesta nova janela você precisará fornecer mais informações. Na primeira parte será solicitado CNPJ, Inscrição Estadual padrão e CNAE, pois essas informações serão necessárias para a emissão de etiquetas do Melhor Envio.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/465df6a8f61af31e9136b839d6c2d8b4739a0905/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_13.png?raw=true" alt="0" width="600"> 
</div>

<br>

Em sequência, você pode definir um prazo maior para a entrega, caso o produto que esteja enviando possua algum tipo de customização e você precise de um tempo a mais. Pode também ser incluído um valor além do padrão do frete que a transportadora 

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/601506c345782daec4b2f70c56ee2eaf0472cff6/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_14.png?raw=true" alt="0" width="600"> 
</div>

<br>

Selecione qual a transportadora você irá disponibilizar para os clientes poderem escolher a forma de envio.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/89e608f702f302df1155fbfcbe27430d104350fb/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_15.png?raw=true" alt="0" width="600"> 
</div>

<br>

Após escolher o modelo de produto, será definido o tamanho padrão da caixa para embalagem. Essa medida é necessária para calcular o frete e garantir que o produto chegue até o cliente em perfeitas condições.

Para garantir a segurança de suas encomendas, escolha entre as opções de seguro: **Assegurar Sempre** para cobertura total ou **Só quando necessário** para escolher quais itens serão protegidos. Informe o valor padrão que será utilizado para calcular o custo do seguro e adicionar ao valor total da etiqueta.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/3162ee78c4da191921a3f96041b5f8e902642756/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_16.png?raw=true" alt="0" width="600"> 
</div>

<br>

Por último, caso tenha escolhido a Jadlog como uma das formas de envio, você precisará definir qual agência fará a postangem dos seus envios. Clicando no campo selecionado abaixo, uma lista com todas as unidades próximas disponíveis será mostrada a você. (Em caso de dúvidas, pode clicar no botão Mapa de agências e verificar melhor onde cada uma está localizada)

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/a7c66773fa049baefb922eeeb9e90ac85b1acc37/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_17.png?raw=true" alt="0" width="600"> 
</div>

Por último você pode clicar no botão **Autorizar** e em seguida a janela de configuração será fechada, e a extensão passará a mostrar o nome 'Você está autenticado", confirmando que a configuração foi realizada com sucesso e agora você pode começar a utilizar no seu Gestão Online.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/502fcfc4637a6e6e57a8117b36cc0860e9e9c17e/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_19.png?raw=true" alt="0" width="800"> 
</div>

### Configuração para vendas online

Caso você enha o módul ode vnedas online instalado em seu Gestão Online. Pode ativar esta função e quando seus clientes efetuarem compras atravás da sua Landing page, o sistema de entrega ficará disponível para os produtos que você configurar, e assim o cliente poderá escolher o método de entrega e pagar tudo junto.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/d8c763d82a299b46e83a6ece5d7958af1f7dcec8/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_20.png?raw=true" alt="0" width="600"> 
</div>

### O que muda no meu sistema?

Para que tudo funcione perfeitamente no momento das suas vendas, você precisa configurar os produtos que terão este formato de envio. Na tela de produtos, e com o produto selecinado aberto para edição, você irá procurar o campo **Tipo de entrega** e definir ele com a opção **TRANSPORTE**, dessa forma, novos campos irão aparecer para você, com as informações de dimensão e peso do produto. Após preencher tudo não esqueça de clicar no botão de salvar.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/204d68877ddf40575c7965453e9aa706f66b45bc/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_18.png?raw=true" alt="0" width="800"> 
</div>

<br>

No momento que estiver realizando a venda e estiver com o rascunho salvo, você agora pode clicar no botão **Adicionar frete** do menu superior. Ao clicar nele, uma janela será mostrada a você com o produto definido para o envio com o frete, e no campo abaixo, a escolha de qual transportadora será utilizada juntamente com o valor do frete a ser pago em cada uma das opções.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/5931aafe207606f8ce27bd62f4a085e6eaea610e/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melho_envio_21.gif?raw=true" alt="0" width="800"> 
</div>

<br>

Ao clicar em **confirmar** e a venda for paga (Valor do frete já é incluído na venda), automaticamente o sistema vai repassar os dados para o Melhor Envio, e você pode atualizar a página para ter acesso a última etapa. Observe abaixo as mudanças que aparecem:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/4a38db78f8ee91daef0dd46b6f783a87fd22d543/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melhor_envio_22.gif?raw=true" alt="0" width="800"> 
</div>

<br>

Agora, você tem dois novos botões para uso, sendo **Imprimir Etiqueta** para você já preparar o envio do produto ao cliente, e o botão **Cancelar etiqueta** caso aconteça algo com a venda. Veja 

<div style="background-color:rgb(206, 223, 255); border-left: 6px solid rgb(62, 139, 255); padding: 15px; margin: 20px 0; border-radius: 5px; color: #333; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);"><h4 style="margin: 0 0 10px; font-size: 1.2em; color: #555;">ℹ️ Informativo:</h4><p style="margin: 0; line-height: 1.5;">As informações da etiqueta também estarão disponíveis na central de Envios Liberado do <a href="https://www.melhorenvio.com.br/painel/meus-envios#liberados">Melhor Envio.</a></p></div>

Quando clicar em **Imprimir Etiqueta** uma nova aba será aberta no seu navegador com a etiqueta pronta com todos os dados seus e do cliente, faltando somente você imprimir e levar o produto ao ponto de entrega.


<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/a73489d59b4b39df104d107fe2f7585d9be7e82b/erp-v2/marketplace/extensions/br.com.melhorenvio.gestao-online/assets/extensao_melhor_envio_23.gif?raw=true" alt="0" width="800"> 
</div>

## Configuração finalizada com sucesso! 🚀

</div>