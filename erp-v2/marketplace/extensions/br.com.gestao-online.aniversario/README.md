<div style="text-align: justify">

# Aniversário

A **Extensão Aniversário** é uma funcionalidade do **Gestão Online** que envia automaticamente **mensagens de feliz aniversário** para clientes, parceiros e colaboradores no dia de seu aniversário.
<br>
**Observação:**
É fundamental que o campo de **data de aniversário** esteja preenchido para que a extensão funcione corretamente.

## **Configuração da Extensão**

### **1. Acesso à Configuração**

Para configurar a extensão Aniversário:

<div style="text-align: center">
    <img src="assets/config.gif" alt="Aniversário GIF" width="800"> 
</div>

<br>

1. Acesse o menu de **Extensões** no sistema  
2. Localize a extensão **Aniversário** 
3. Clique em **Configurar**

### **2. Campos de Configuração**

Na tela de configuração, você encontrará **dois campos principais**:

<div align="center">

| Campos | Funções |
| -------------------------------------- | ------------------------------------------------------ |
| **Tipo Cliente** | Filtrar por cliente, Fornecedor, Indicador, Transportadora ou Funcionário |
| **Tipo Parceiro** | Filtrar por tipo de parceiro cadastrado na base da empresa. |
<br>
</div>

**Observação:**
É necessário preencher pelo menos **um dos campos** para que a extensão funcione corretamente.

#### **Tipo Cliente**

Permite selecionar um ou mais tipos de clientes que receberão a mensagem de aniversário.
<div style="text-align: center">
    <img src="assets/tipoCliente_config.png" width="800"> 
</div>

#### **Tipo Parceiro**

Permite selecionar um ou mais tipos de parceiros que receberão a mensagem de aniversário.
<div style="text-align: center">
    <img src="assets/tipoParceiro_config.png" width="800"> 
</div>

<div style="background-color:rgb(248, 248, 230); border-left: 6px solid rgb(253, 249, 27); padding: 15px; margin: 20px 0; border-radius: 5px; color: #333; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);"><h4 style="margin: 0 0 10px; font-size: 1em;">⚠️ Importante:</h4><p style="margin: 0; line-height: 1.5;">Se ambos os campos forem selecionados, o destinatário deve atender aos dois critérios para receber a mensagem.</div>

# Filtragem e Validação

* Apenas registros com **data de nascimento preenchida** receberão a mensagem.
* Pessoas jurídicas (clientes com CNPJ) **não recebem e-mails**.
* O sistema aplica os filtros configurados para garantir que apenas os destinatários corretos sejam contemplados.

# Email
Um e-mail no formato abaixo será enviado automaticamente ao cliente no dia de seu aniversário, contendo o nome do cliente e o nome da base:

<div style="text-align: center">
    <img src="assets/email.png" width="500"> 
</div>

</div>