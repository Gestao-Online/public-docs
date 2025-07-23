<div style="text-align: justify">


Extensão Consulta CPF/CNPJ SERPRO
=================================

Visão Geral
-----------

A extensão Consulta CPF/CNPJ permite consultar automaticamente dados oficiais de pessoas físicas diretamente na base do governo brasileiro através da API do SERPRO. Com ela, você pode preencher automaticamente o nome e data de nascimento de clientes apenas digitando o CPF.

O que a extensão faz
--------------------

*   Consulta dados oficiais de CPF na base do governo (SERPRO)
*   Preenche automaticamente campos de nome e data de nascimento
*   Valida CPFs em tempo real
*   Mantém histórico de consultas
*   Gerencia tokens de acesso automaticamente

Configuração da API SERPRO
==========================

Obtendo credenciais no SERPRO
-----------------------------

###  Solicitar acesso à API

Faça login no Portal de Serviços do SERPRO utilizando o certificado digital e‑CNPJ da empresa. No menu lateral, acesse a seção "APIs Disponíveis" e utilize o campo de busca para localizar a API Consulta CPF DF (você também pode digitar apenas “CPF”). Após localizar a API desejada, clique em "Solicitar acesso" e escolha o plano de consumo mais adequado às suas necessidades.

###  Aguardar aprovação

*   O SERPRO analisará seu pedido.
*   Você receberá um e‑mail de confirmação.
*   Prazo médio: 1 – 3 dias úteis.

### Obter as credenciais

1.  Após a aprovação, acesse a área do cliente no portal.

###  Solicitar acesso à API

Faça login no Portal de Serviços do SERPRO utilizando o certificado digital e‑CNPJ da empresa. No menu lateral, acesse a seção "APIs Disponíveis" e utilize o campo de busca para localizar a API Consulta CPF DF (você também pode digitar apenas “CPF”). Após localizar a API desejada, clique em "Solicitar acesso" e escolha o plano de consumo mais adequado às suas necessidades.

###  Aguardar aprovação

*   O SERPRO analisará seu pedido.
*   Você receberá um e‑mail de confirmação.
*   Prazo médio: 1 – 3 dias úteis.

### Obter as credenciais

1.  Após a aprovação, acesse a área do cliente no portal.
<p align="center">
  <img src="https://github.com/Gestao-Online/public-docs/raw/master/erp-v2/marketplace/extensions/br.com.gestao-online.consulta-documento/assets/extensao-consulta5.png" alt="GO DocBuilder GIF">
</p>

2.  Localize a aplicação criada e clique em Visualizar chaves.
3.  Anote suas credenciais:

*   Consumer Key – chave pública (ex.: a1b2c3d4e5f6...).
*   Consumer Secret – chave secreta (ex.: z9y8x7w6v5u4...).

Importante: mantenha a Consumer Secret em sigilo. Ela concede acesso total às APIs contratadas.
<p align="center">
  <img src="https://github.com/Gestao-Online/public-docs/raw/master/erp-v2/marketplace/extensions/br.com.gestao-online.consulta-documento/assets/extensao-consulta4.png" alt="GO DocBuilder GIF">
</p>

### Configurando na extensão

#### Acessar configurações

Clique em "Configurar" ou no ícone de engrenagem

#### Preencher campos

Preencha apenas os campos necessários:

Consumer Key:

*   Cole sua chave pública obtida no SERPRO
*   Exemplo: a1b2c3d4e5f6g7h8i9j0k1l2

Consumer Secret:

*   Cole sua chave secreta obtida no SERPRO
*   Exemplo: z9y8x7w6v5u4t3s2r1q0p9o8

Payload:

*   DEIXE ESTE CAMPO VAZIO
*   O sistema preenche automaticamente
  
<p align="center">
  <img src="https://github.com/Gestao-Online/public-docs/raw/master/erp-v2/marketplace/extensions/br.com.gestao-online.consulta-documento/assets/extensao-consulta6.png" alt="GO DocBuilder GIF">
</p>

#### Salvar configuração

Clique em "Salvar" e aguarde a mensagem de confirmação que irá aparecer na tela.

Como usar
---------

### Consultando CPF de um cliente

Para acessar os dados do cliente, entre no cadastro da venda e clique no botão “+” localizado na seção Cliente/Parceiro.
<p align="center">
  <img src="https://github.com/Gestao-Online/public-docs/raw/master/erp-v2/marketplace/extensions/br.com.gestao-online.consulta-documento/assets/extensao-consulta.gif" alt="GO DocBuilder GIF">
</p>



####  Preencher CPF

1.  Localize o campo "CPF/CNPJ"
2.  Digite o CPF do cliente
3.  Formato aceito:

*   Com pontos e traço: 123.456.789-00
*   Só números: 12345678900
*   Ambos funcionam
<p align="center">
  <img src="https://github.com/Gestao-Online/public-docs/raw/master/erp-v2/marketplace/extensions/br.com.gestao-online.consulta-documento/assets/extensao-consulta2.png" alt="GO DocBuilder GIF">
</p>
####  Executar consulta

Após digitar o CPF, localize o botão "Consultar CPF", que aparece próximo ao campo. Clique no botão e aguarde o processamento por alguns segundos.

<p align="center">
  <img src="https://github.com/Gestao-Online/public-docs/raw/master/erp-v2/marketplace/extensions/br.com.gestao-online.consulta-documento/assets/extensao-consulta3.png" alt="GO DocBuilder GIF">
</p>




#### Verificar resultado

Após a consulta bem-sucedida, os campos serão preenchidos automaticamente:

*   Nome: Nome completo da pessoa
*   Data de Nascimento: Data no formato DD/MM/AAAA
*   Razão Social: Copiado automaticamente do nome

Funcionalidades avançadas
-------------------------

### Validação automática

*   A extensão valida o formato do CPF automaticamente
*   CPFs inválidos retornam erro antes da consulta
*   Economiza consultas desnecessárias

### Gerenciamento de token

*   Tokens de acesso são renovados automaticamente
*   Não há necessidade de intervenção manual
*   Sistema mantém autenticação sempre válida

Solução de problemas
--------------------

### Erro: "Parâmetros insuficientes"

Causa: Consumer Key ou Consumer Secret não configurados ou inválidos

Solução:

Verifique se os campos Consumer Key e Consumer Secret foram preenchidos corretamente. Confirme se as credenciais estão válidas e funcionando, testando-as diretamente no portal do SERPRO. Se necessário, reconfigure a extensão para garantir o correto funcionamento da integração.

### Erro: "Preencha um CPF para realizar a consulta"

Causa: Campo CPF está vazio

Solução:

Digite um CPF válido no campo, utilizando o formato 123.456.789-00 ou 12345678900. Em seguida, tente realizar a consulta novamente.

### Erro: "Ocorreu um erro ao realizar a consulta desse CPF"

Possíveis causas:

*   CPF inválido ou inexistente
*   Problema temporário na API do SERPRO
*   Limite de consultas excedido
*   Credenciais inválidas

Soluções:

Verifique se o CPF informado está correto e existe na base da Receita Federal. Certifique-se também de que o seu limite de consultas na API do SERPRO não foi excedido. Caso esteja tudo certo, teste suas credenciais diretamente no portal do SERPRO. Se o problema persistir, aguarde alguns minutos e tente novamente.

### Botão "Consultar CPF" não aparece

Possíveis causas:

*   Extensão não instalada corretamente
*   Extensão desativada
*   Configuração incompleta
*   Campo CPF não é para Pessoa Física

Soluções:

Verifique se a extensão está devidamente instalada e ativa no sistema. Confirme se as credenciais foram configuradas corretamente e certifique-se de que você está realizando a consulta em um cadastro do tipo Pessoa Física. Caso tudo esteja em ordem, recarregue a página e tente novamente.

### Erro de autenticação

Causa: Token expirado ou credenciais inválidas

Solução:

*   A extensão renovará o token automaticamente
*   Se persistir, reconfigure as credenciais
*   Verifique se suas credenciais ainda estão válidas no SERPRO

### Como monitorar uso

Acesse o portal do SERPRO, vá até a opção "Consultar Consumo" e monitore o número de consultas mensais realizadas. Se necessário, configure alertas para ser notificado ao atingir o limite.

Suporte e contato
-----------------

### Suporte da extensão

*   Confirme configuração das credenciais
*   Teste conectividade com internet

### Dicas importantes

Mantenha suas credenciais seguras e nunca compartilhe o Consumer Secret com terceiros. Monitore regularmente seu uso mensal da API.

Benefícios
----------

Ganhe agilidade com cadastros até 10 vezes mais rápidos, eliminando erros com dados oficiais validados diretamente na base do governo. Aumente a produtividade da equipe ao focar no atendimento em vez da digitação, garantindo precisão, compliance e confiabilidade com uma base de dados sempre atualizada.