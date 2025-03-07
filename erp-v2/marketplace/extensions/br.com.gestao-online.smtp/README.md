<div style="text-align: justify">

### Configurando a Personalização de SMTP

Este passo a passo vai te ajudar a configurar o SMTP no seu ERP, permitindo o envio de e-mails personalizados usando o servidor de e-mail da sua empresa. Siga as instruções abaixo:

Nesta aplicação ao clicar no botão de configurações uma notificação pop-up irá se abrir mostrando os campos disponíveis para alteração.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/dd8468ade6418c6fb1616645af0d484158434034/erp-v2/marketplace/extensions/br.com.gestao-online.smtp/assets/extensao_smtp_03.gif?raw=true" alt="0" width="800"> 
</div>

<br>

### Configurando credenciais

Preencha os campos obrigatórios marcados com * conforme as informações fornecidas pelo seu provedor de e-mail.

<div style="background-color:rgb(248, 248, 230); border-left: 6px solid rgb(253, 249, 27); padding: 15px; margin: 20px 0; border-radius: 5px; color: #333; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);"><h4 style="margin: 0 0 10px; font-size: 1em;">⚠️ Importante:</h4><p style="margin: 0; line-height: 1.5;">Verifique com o seu provedor de e-mail quais são as configurações corretas de domínio, porta e SSL.</div>

No primeiro campo temos o **Nome de Domínio**, nele você pode preencher por exemplo: smtp.suaempresa.com. Caso não saiba o domínio, consulte o suporte técnico do provedor.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/54d925b74c39fa8f951e55343c85ea0129dd699a/erp-v2/marketplace/extensions/br.com.gestao-online.smtp/assets/extensao_smtp_04.png?raw=true" alt="0" width="800"> 
</div>

<br>

No segundo campo você irá preecnher com o número da porta que será usada para conexão com o servidor SMTP. A portas mais comuns são:

- **587**: Para conexões TLS.
- **465**: Para conexões SSL.
- **25**: Para servidores que não exigem criptografia (menos comum).

Mas sempre recomendamos que verifique com o seu provedor qual porta deve ser utilizada.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/54d925b74c39fa8f951e55343c85ea0129dd699a/erp-v2/marketplace/extensions/br.com.gestao-online.smtp/assets/extensao_smtp_05.png?raw=true" alt="0" width="800"> 
</div>

<br>

Agora nos campos de nome de usuário e senha, você primeiro irá digitar o nome de usuário da conta de e-mail que será utilizada para enviar os e-mails. Geralmente, é o próprio endereço de e-mail.

Insira também a senha correspondente à conta de e-mail utilizada. Certifique-se de que a senha está correta e que a conta tem permissão para envio via SMTP.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/6343ee767a357237bc979400a5e2a6ff66ed170e/erp-v2/marketplace/extensions/br.com.gestao-online.smtp/assets/extensao_smtp_06.png?raw=true" alt="0" width="800"> 
</div>

<br>

No campo de **Email Remetente** informe o e-mail que será exibido nas mensagens enviadas pelo seu Gestão Online, ou o mesmo e-mail usado no nome de usuário.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/fb730c31b578b9c3f4a24cee13d4cb0e9df8f98b/erp-v2/marketplace/extensions/br.com.gestao-online.smtp/assets/extensao_smtp_07.png?raw=true" alt="0" width="800"> 
</div>

<br>

O campo SSL (Segurança da Conexão) é um seletor com três opções. Verifique com o provedor de e-mail qual tipo de segurança é necessário e selecione a opção adequada. Das três opções disponíveis, você pode escolher entre:

- **Vazio**: Escolha esta opção caso o servidor SMTP não exija criptografia.
- **SSL**: Escolha esta opção se o servidor requer uma conexão segura via SSL.
- **TLS**: Escolha esta opção se o servidor requer uma conexão segura via TLS.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/f227b3ee3de5b5ecf7b1ffc03d9291fc371b539e/erp-v2/marketplace/extensions/br.com.gestao-online.smtp/assets/extensao_smtp_08.png?raw=true" alt="0" width="800"> 
</div>

Por último, após preencher os campos necessários, você pode clicar no botão **Testar credenciais** e enviaremos um teste para o seu servidor de SMTP. Se tudo estiver correto, você receberá uma mensagem de que foi configurado com sucesso.

<div style="background-color:rgb(255, 227, 227); border-left: 6px solid rgb(253, 27, 27); padding: 15px; margin: 20px 0; border-radius: 5px; color: #333; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);"><h4 style="margin: 0 0 10px; font-size: 1em;">🚨 Atenção:</h4><p style="margin: 0; line-height: 1.5;">Caso apareça alguma mensagem de erro neste momento, você precisa revisar as informações inseridas, e se o erro persistir, você pode entrar em contato com nosso suporte para verificarmos o que pode ter acontecido.</div>

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/d4829a588dee359e4b6947b7b2c2962fd8a85a93/erp-v2/marketplace/extensions/br.com.gestao-online.smtp/assets/extensao_smtp_09.gif?raw=true" alt="0" width="800"> 
</div>

<br>

Com os dados preenchidos corretamente, e o teste realziado com sucesso, agora você pode clicar no botão Salvar configurações para finalziar o processo. Uma mensagem será msotrada a você na janela de configuração da extensão, informando que as alterações levarão um tempo de até 6 horas para estarem em pleno funcionamento.

<div style="text-align: center">
    <img src="https://github.com/Gestao-Online/public-docs/blob/e55fa94eca0258e234b90f5083c93966a3d022cf/erp-v2/marketplace/extensions/br.com.gestao-online.smtp/assets/extensao_smtp_10.png?raw=true" alt="0" width="800"> 
</div>

<br>

**Agora o seu SMTP está configurado e pronto para uso! 🎉**

</div>