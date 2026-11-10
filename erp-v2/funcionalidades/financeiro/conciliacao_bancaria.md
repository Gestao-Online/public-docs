# Conciliação bancária

Após ativar a conciliação bancária, é necessário realizar a importação do arquivo OFX do seu extrato bancário. Você pode fazer a importação clicando no ícone **Importar extrato de conciliação**:

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_1.png)

<br>

Será exibida a tela de importação de OFX. Você deve clicar em **Escolher arquivo** para abrir o seu explorador de arquivo e selecionar o OFX que será feito a conciliação. Nesta tela é possível selecionar algumas flags para forçar a importação e evitar possíveis erros durante o processo. Essas opções existem para situações específicas, como ajustes retroativos ou correções pontuais. 



{% hint style="danger" %}
**Importante:** Pular validações deve ser feito com cautela, pois pode gerar inconsistências nos próximos extratos. 
{% endhint %}



![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_2.png)

<br>

Durante a importação, alguns erros podem ocorrer por motivos específicos, por exemplo:

**Conta incorreta (ou arquivo OFX de outra conta):**

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_3.png)

<br>

Este alerta ocorre quando o código do banco ou o número da conta informado no OFX não coincide com a conta cadastrada no sistema.

Recomendação: verifique se o arquivo corresponde à conta selecionada antes de prosseguir.

<br>

**Saldo inicial incorreto:**

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_4.png)

<br>


Ao importar o primeiro extrato, o sistema calcula e sugere um saldo inicial. Caso o saldo informado seja diferente do esperado, o alerta será exibido. É possível pular essa checagem, mas isso não é recomendado, pois um saldo inicial incorreto afetará os extratos seguintes.

<br>


**Período já importado (sobreposição de datas):**

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_5.png)

<br>

Esse alerta aparece quando o período do novo OFX inclui datas já importadas anteriormente. Se optar por continuar, o sistema importará apenas as linhas não duplicadas, considerando o identificador único de cada linha no extrato OFX o (FITID).

<br>

**Lacunas de período (datas faltando):**

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_6.png)

<br>

Este alerta indica que há buracos entre extratos. Isso ocorre quando o saldo do extrato atual não se conecta com o saldo final do extrato anterior. Recomendações: verificar períodos faltando, reimportar extratos consolidados ou ignorar linhas com pequenas diferenças.

Vale ressaltar que as validações têm como objetivo garantir que o extrato importado reflita fielmente os dados bancários. Pular checagens deve ser exceção, especialmente para saldo inicial e lacunas de período.


<br>

Após importar o arquivo OFX, você pode conferir os movimentos pendentes e conciliados acessando o guia **Extrato/Conciliação**

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_7.png)

<br>

Com a guia aberta, serão exibidas as movimentações referentes ao OFXs importados. A tela apresentará informações como a situação da conciliação (amarelo para pendente de conciliação e verde para conciliado), a data, o tipo (Débito ou Crédito), a conta bancária referente à conciliação, a descrição que consta no extrato e o valor.

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_8.png)

<br>

Para realizar a conciliação dos itens importados, você deve clicar no ícone no canto superior direito "Conciliação" e então será direcionado para a respectiva tela.

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_9.png)

<br>

Na tela de conciliação será exibida uma dashboard com as informações de giro (entrada e saída) contabilizando a quantidade de movimentos e o valor total somado deles. É apresentado também o total de movimentos e quantos foram Conciliados, não conciliados ou ignorados, é exibido junto o saldo atual do banco de acordo com os dados importados.

É possível visualizar também na tela, um campo para filtrar a busca por data. Aplicando no filtro o período de data que deseja consultar, você deve clicar em atualizar para fazer a busca. É possível também fazer a conciliação de outras contas desativando a flag **Filtrar**, mas para realizar a conciliação apenas da conta em específico ela precisa estar ativada.

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_10.png)

<br> 

Na parte inferior da tela, ficam as relações das movimentações no Gestão do lado esquerdo e a movimentação relacionada no extrato ao lado direito. Caso não tenha um movimento no extrato relacionado, é informado ao lado direito que não há um resultado encontrado.

Para conciliar um movimento basta clicar no ícone verde **Conciliar**, com isso, será alterado para um ícone amarelo que pode ser clicado posteriormente para desconciliar o movimento caso necessário.


![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_11.png)

<br> 


No canto superior direito da tela, existe o ícone para acessar a tela "Conciliação inteligente", onde é possível realizar um relacionamento automático.

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_12.png)

<br> 


Nesta tela você seleciona a data inicial e final do período que irá realizar a conciliação, o tipo do movimento (todos os tipos, crédito, débito, pagamento e transferência) e o modo, que é referente a quantidade de resultados no extrato, podendo ser todos, os primeiros 100, 200, 300, 400 ou 500. 

Você pode também ativar as flags para buscar apenas os movimentos conciliados, não conciliados e ignorados.

![](/erp-v2/assets/funcionalidades/financeiro/conciliacao_bancaria_13.png)

<br> 