<div style="text-align: justify">

# GO Signer

A **GO Signer** é uma extensão do sistema Gestão Online que permite assinar anexos presentes nas vendas confirmadas.

Esta extensão permite o envio, acompanhamento e recebimento automático de documentos assinados digitalmente, de forma segura e integrada ao sistema.

**Modelo de anexo assinado**

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/anexo_assinado.png?raw=true" alt="0" width="800"> 
</div>

## **Configuração da Extensão**

### **1\. Acesso à Configuração**

Para configurar a extensão GO Signer:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/fluxo_config_extensao%20.gif?raw=true" alt="GO Signer GIF" width="800"> 
</div>

<br>

1. Acesse o menu de **Extensões** no sistema  
2. Localize a extensão **GO Signer** 
3. Clique em **Configurar**

### **2\. Campos de Configuração**

Na tela que abrir, você verá **três campos**:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/config.png?raw=true" alt="GO Signer GIF" width="800"> 
</div>

<br>

<div align="center">

| Campos | Funções |
| -------------------------------------- | ------------------------------------------------------ |
| **Chave de acesso do usuário** | Identificação da sua conta no GoSigner, utilizada para autorizar e validar o envio dos documentos para assinatura. |
| **Chave de acesso GoSigner** | Chave de segurança da sua conta GoSigner, responsável por autenticar a integração e garantir a proteção dos dados. |
| **Homologação** | <br>Define o ambiente da integração:<br>• <strong>Ativo</strong> → ambiente de **Testes** da extensão(Sandbox)<br>• <strong>Inativo</strong> → ambiente de produção |

</div>

**Campos Obrigatórios**
1. Chave de acesso do usuário  
2. Chave de acesso GoSigner

# Fluxo de Assinatura

O botão **“Assinar Contrato”** ficará disponível no canto superior esquerdo da tela de venda, após a confirmação da venda.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/botao_assinar.png?raw=true" alt="Botão Assinar Contrato na tela de venda" width="800"> 
</div>

Ao clicar no botão, **abrirá uma nova tela** onde deverá ser informado o **CPF** do responsável pela assinatura e selecionar o tipo de assinatura desejado: **Assinatura Simples** ou **Assinatura Qualificada**.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/tipo_assinatura.png?raw=true" alt="Tela de seleção do tipo de assinatura" width="800"> 
</div>

---

## 1. Assinatura Simples
A **Assinatura Simples** é uma assinatura eletrônica que **não utiliza certificado digital**, na qual a identidade do assinante é validada por meio de **dados pessoais, token enviado por e-mail e geolocalização**, garantindo autenticidade e integridade dos documentos assinados.

Para a **Assinatura Simples**, o sistema guiará você pelos seguintes passos:

### • Seleção de Documentos
Após escolher o tipo de assinatura, serão exibidos os anexos disponíveis. Marque **"Ativado"** nos documentos que deseja assinar e **"Desativado"** nos que não deseja. Em seguida, clique em **"Confirmar"** para prosseguir.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/selecionando_documento.gif?raw=true" alt="Selecionando documentos para assinatura" width="800"> 
</div>

### • Link de Acesso
Apos confirmar a seleção o sistema gera um **link exclusivo**, que deve ser enviado ao cliente para que ele acesse a **GoSigner** e assine os documentos.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/link_exclusivo.png?raw=true" alt="Link exclusivo para assinatura" width="800"> 
</div>

### • Ações do Cliente
Ao abrir o link, o cliente será direcionado para a página de autenticação da **GoSigner**, onde poderá preencher os dados e concluir a assinatura.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/tela_autenticacao.png?raw=true" alt="Tela de autenticação da GoSigner" width="800"> 
</div>

### • Autenticação e Token
O cliente deverá preencher seu **nome completo** e **autorizar a geolocalização** para autenticar.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/autenticando_geoloc.gif?raw=true" alt="Cliente autenticando com geolocalização" width="800"> 
</div>

Em seguida, será exibido um modal solicitando o **token de autenticação**, que foi enviado para o e-mail do cliente.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/token_email.png?raw=true" alt="Solicitação de token de autenticação" width="800"> 
</div>

O cliente deve **copiar e colar o token** no campo indicado e clicar em **"Conferir Token"**. Após isso, basta clicar no botão **"Assinar"** para concluir o processo.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/documento_assinado.gif?raw=true" alt="Finalizando assinatura pelo cliente" width="800"> 
</div>

Após a assinatura, esta tela de conclusão será exibida para o cliente:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/assinatura_concluida.png?raw=true" width="800"> 
</div>

### • Validação na Venda
Após a assinatura do cliente, os documentos assinados serão **marcados visualmente** na tela de venda do Gestão Online e um **histórico** de assinatura será gerado automaticamente.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/descricao_venda.png?raw=true" alt="Documentos assinados visualmente na venda" width="800"> 
</div>

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/historico_gerado.png?raw=true" alt="Historico gerado na venda" width="800"> 
</div>

---

## 2. Assinatura Qualificada
A **Assinatura Qualificada** é uma assinatura eletrônica que **utiliza certificado digital ICP-Brasil**, garantindo o mais alto nível de segurança jurídica e autenticidade, sendo equivalente à assinatura manuscrita com reconhecimento de firma.

A **Assinatura Qualificada** segue um fluxo similar, com alterações apenas na etapa de autenticação do certificado.

Ao acessar o link da GoSigner, o cliente verá a seguinte página:

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/assinatura_qualificada.png?raw=true" alt="Tela inicial para Assinatura Qualificada" width="800"> 
</div>

### • Certificado em Nuvem
Ao selecionar a opção **Certificado em Nuvem**, o cliente deverá informar o **provedor do certificado** e preencher os **dados de autenticação** no modal exibido, para que a assinatura seja realizada de forma segura.


<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/certificado_nuvem.png?raw=true" alt="Certificado em nuvem - preenchimento de login" width="800"> 
</div>

### • Certificado Local
Ao selecionar a opção **Certificado Local**, será necessário realizar o **download e a instalação do plugin indicado**. Após a instalação, o certificado local será identificado e o anexo ficará disponível para assinatura.


<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/master/erp-v2/assets/marketplace/go-signer/certificado_local.png?raw=true" alt="Certificado local - download do plugin" width="800"> 
</div>
